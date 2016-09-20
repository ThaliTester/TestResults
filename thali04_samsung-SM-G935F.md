#### Test 850469116350bd7_thali04_samsung-SM-G935F Logs


```
--------- beginning of main
,09-20 09:37:31.295  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 09:37:31.465  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 09:37:31.645  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 09:37:31.755  9653  9653 I FIPS_bssl: FIPS approved mode (1) | 9653 | app_process
09-20 09:37:31.765  9653  9653 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-20 09:37:31.765  9653  9653 D AndroidRuntime: CheckJNI is OFF
09-20 09:37:31.765  9653  9653 D AndroidRuntime: readGMSProperty: start
09-20 09:37:31.765  9653  9653 D AndroidRuntime: readGMSProperty: already setted!!
09-20 09:37:31.765  9653  9653 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-20 09:37:31.765  9653  9653 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-20 09:37:31.765  9653  9653 D AndroidRuntime: readGMSProperty: end
09-20 09:37:31.765  9653  9653 D AndroidRuntime: addProductProperty: start
09-20 09:37:31.785  9653  9653 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-20 09:37:31.805  9653  9653 I Radio-JNI: register_android_hardware_Radio DONE
09-20 09:37:31.815  9653  9653 E AffinityControl: AffinityControl: registerfunction enter
09-20 09:37:31.815  9653  9653 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-20 09:37:31.825  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 09:37:31.855  3420  4811 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-20 09:37:31.855  3420  4811 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-20 09:37:31.875  3420  4811 D ResourcesManager: For user 0 new overlays fetched Null
09-20 09:37:31.875  3420  4811 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 09:37:31.875  3420  4811 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-20 09:37:31.875  3420  4811 D ActivityManager: mDVFSHelper.acquire()
09-20 09:37:31.885  3420  4811 V WindowManager: addAppToken: AppWindowToken{d0eba5a0e token=Token{4c60809 ActivityRecord{47a1510 u0 com.test.thalitest/.MainActivity t75}}} to stack=2 task=75 at 0
09-20 09:37:31.885  3420  3568 I InjectionManager: Inside getClassLibPath caller 
09-20 09:37:31.895  3420  3568 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-20 09:37:31.895  3420  3568 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7ab9ce6 V.E...... R.....ID 0,0-0,0}
09-20 09:37:31.895  9662  9662 E Zygote  : v2
09-20 09:37:31.895  9662  9662 I libpersona: KNOX_SDCARD checking this for 10177
09-20 09:37:31.895  9662  9662 I libpersona: KNOX_SDCARD not a persona
09-20 09:37:31.905  9662  9662 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-20 09:37:31.905  3420  3568 W WindowManager: Failed looking up window
09-20 09:37:31.905  3420  3568 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@dc41227 does not exist
09-20 09:37:31.905  3420  3568 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 09:37:31.905  3420  3568 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-20 09:37:31.905  3420  3568 D ISSUE_DEBUG: InputChannelName : b2dccd4 Starting com.test.thalitest
09-20 09:37:31.905  3420  4811 I ActivityManager: Start proc 9662:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-20 09:37:31.905  9662  9662 E Zygote  : accessInfo : 0
09-20 09:37:31.905  9662  9662 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-20 09:37:31.905  3420  4811 D InputDispatcher: Focused application set to: xxxx
09-20 09:37:31.905  9653  9653 D AndroidRuntime: Shutting down VM
09-20 09:37:31.905  3420  3856 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-20 09:37:31.905  3008  3008 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-20 09:37:31.925  6160  6160 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 09:37:31.935  9662  9662 D TimaKeyStoreProvider: TimaSignature is unavailable
09-20 09:37:31.935  9662  9662 D ActivityThread: Added TimaKeyStore provider
09-20 09:37:31.935  3420  3479 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 09:37:31.935  3420  3479 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3420
09-20 09:37:31.935  3420  3479 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 09:37:31.935  3420  3479 D PowerManagerService: mDisplayReady: false
09-20 09:37:31.935  6160  6160 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 09:37:31.935  3420  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 09:37:31.935  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa0083c00
09-20 09:37:31.935  3420  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 09:37:31.935  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-20 09:37:31.935  3420  3479 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 09:37:31.935  3420  3568 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 09:37:31.935  3420  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 09:37:31.935  3420  3420 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 09:37:31.935  3420  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 09:37:31.935  3420  3568 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-20 09:37:31.935  3420  3580 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-20 09:37:31.935  3420  4389 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3420
09-20 09:37:31.945  3420  3420 I KnoxTimeoutHandler: SD activityfalse
09-20 09:37:31.945  3420  3568 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-20 09:37:31.945  3420  3571 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 09:37:31.945  3420  3568 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-20 09:37:31.945  3420  3571 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 09:37:31.945  3420  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 09:37:31.945  3420  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 09:37:31.945  3420  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 09:37:31.945  3420  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 09:37:31.945  3420  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 09:37:31.945  3420  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 09:37:31.945  3420  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 09:37:31.945  3420  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 09:37:31.945  3420  3571 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 09:37:31.945  3420  3571 D PowerManagerService: mDisplayReady: true
09-20 09:37:31.945  3420  3571 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-20 09:37:31.955  3420  4811 V WindowStateAnimator: Finishing drawing window Window{627cf13 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-20 09:37:31.955  5823  5823 E CocktailBarPositionManager: Window direction: 0
09-20 09:37:31.955  5823  5823 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-20 09:37:31.985  3420  3979 D ActivityManager:  Launching com.test.thalitest, updated priority
09-20 09:37:31.995  3420  3568 V WindowStateAnimator: Finishing drawing window Window{b2dccd4 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-20 09:37:31.995  3420  4388 V WindowStateAnimator: Finishing drawing window Window{f7a2f4d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-20 09:37:31.995  6160  6160 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 09:37:31.995  6160  6160 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 09:37:31.995  6160  6160 V ActivityThread: updateVisibility : ActivityRecord{512b277 token=android.os.BinderProxy@30454e8 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-20 09:37:31.995  3008  3019 I SurfaceFlinger: id=18 Removed VSBConnecti (8/13)
09-20 09:37:31.995  3008  3017 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/13)
09-20 09:37:32.005  5823  5833 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-20 09:37:32.005  3420  3420 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-20 09:37:32.005  3008  3832 D libEGL  : eglTerminate EGLDisplay = 0x7f9978de78
09-20 09:37:32.005  3008  3832 D libEGL  : eglTerminate EGLDisplay = 0x7f9978de78
09-20 09:37:32.005  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 09:37:32.015  3008  3832 I SurfaceFlinger: id=9 Removed MauncherAct (3/12)
09-20 09:37:32.015  3008  4350 I SurfaceFlinger: id=9 Removed MauncherAct (-2/12)
09-20 09:37:32.015  3008  3019 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
09-20 09:37:32.015  3008  3832 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
09-20 09:37:32.025  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fdc719718
09-20 09:37:32.025  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fdc7196e8
09-20 09:37:32.025  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fdc719718
09-20 09:37:32.025  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fdc7196e8
09-20 09:37:32.025  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fdc7195f8
09-20 09:37:32.035  4322  4322 V ActivityThread: updateVisibility : ActivityRecord{44d2a4f token=android.os.BinderProxy@1524383 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-20 09:37:32.035  4322  4322 D Launcher: onTrimMemory. Level: 20
09-20 09:37:32.085  3420  3420 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3420 (0x0)
09-20 09:37:32.095  3420  3420 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3420 (0x0)
09-20 09:37:32.095  3420  3420 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 09:37:32.095  3420  3420 D PowerManagerService: mDisplayReady: false
09-20 09:37:32.095  3420  3420 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 09:37:32.095  3420  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 09:37:32.095  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa0083c00
09-20 09:37:32.095  3420  3420 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 09:37:32.095  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-20 09:37:32.095  3420  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 09:37:32.095  3420  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 09:37:32.095  3420  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 09:37:32.095  3420  3580 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-20 09:37:32.095  3420  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 09:37:32.095  3420  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 09:37:32.095  3420  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 09:37:32.095  3420  3571 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 09:37:32.095  3420  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 09:37:32.095  3420  3571 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 09:37:32.095  3420  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 09:37:32.095  3420  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 09:37:32.095  3420  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 09:37:32.095  3420  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 09:37:32.095  3420  3571 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 09:37:32.095  3420  3571 D PowerManagerService: mDisplayReady: true
09-20 09:37:32.095  3420  3571 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 09:37:32.185  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 09:37:32.305  5823  5823 I TrayVisibilityController: handleMessage : msg.what = 1
09-20 09:37:32.345  3420  3979 I WindowManager: Screenshot max retries 4 of Token{4c60809 ActivityRecord{47a1510 u0 com.test.thalitest/.MainActivity t75}} appWin=Window{b2dccd4 u0 d0 Starting com.test.thalitest} drawState=4
09-20 09:37:32.345  5823  5834 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-20 09:37:32.345  3420  3548 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-20 09:37:32.345  3420  3568 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 09:37:32.345  3420  3420 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 09:37:32.345  5823  5823 I Utils   : isCurrentUser current = 0, ownerId = 0
09-20 09:37:32.345  5823  5823 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-20 09:37:32.345  5823  5823 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-20 09:37:32.345  3420  6106 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 09:37:32.345  3420  3856 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-20 09:37:32.345  3420  3568 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-20 09:37:32.345  3420  6106 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 09:37:32.355  3420  3568 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-20 09:37:32.355  3420  3420 I KnoxTimeoutHandler: SD activityfalse
09-20 09:37:32.365  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 09:37:32.405  5823  5823 E CocktailBarPositionManager: Window direction: 0
09-20 09:37:32.405  5823  5823 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-20 09:37:32.405  9662  9662 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-20 09:37:32.405  9662  9662 D RelationGraph: garbageCollect()
09-20 09:37:32.405  9662  9662 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 09:37:32.415  3420  4389 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-20 09:37:32.415  9662  9662 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-20 09:37:32.415  3420  6106 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 09:37:32.425  3420  6106 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 09:37:32.425  9662  9662 D ResourcesManager: For user 0 new overlays fetched Null
09-20 09:37:32.425  3420  6106 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 09:37:32.425  3420  6106 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 09:37:32.425  3420  6106 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 09:37:32.435  9662  9662 I InjectionManager: Inside getClassLibPath caller 
09-20 09:37:32.445  9662  9662 D InjectionManager: InjectionManager
09-20 09:37:32.445  9662  9662 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-20 09:37:32.445  9662  9662 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-20 09:37:32.445  9662  9662 I InjectionManager: featureStore :{}
09-20 09:37:32.445  9662  9662 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 09:37:32.445  9662  9662 D RelationGraph: garbageCollect()
09-20 09:37:32.455  9662  9662 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 09:37:32.485  9662  9662 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-20 09:37:32.545  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 09:37:32.565  9662  9662 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-20 09:37:32.565  9662  9662 D ResourcesManager: For user 0 new overlays fetched Null
09-20 09:37:32.565  9662  9662 I InjectionManager: Inside getClassLibPath caller 
09-20 09:37:32.575  9662  9662 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-20 09:37:32.595  3420  3880 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-20 09:37:32.635  9662  9662 I cr_LibraryLoader: Time to load native libraries: 33 ms (timestamps 2012-2045)
09-20 09:37:32.635  9662  9662 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-20 09:37:32.685  9662  9677 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-20 09:37:32.695  3420  3880 I MdnieScenarioControlService: mGameModeLauncher : false
09-20 09:37:32.695  3420  3880 I MdnieScenarioControlService: setUIMode
09-20 09:37:32.695  9662  9662 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {33370cb}
09-20 09:37:32.695  9662  9662 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-20 09:37:32.715  9662  9662 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-20 09:37:32.725  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 09:37:32.765  9662  9662 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-20 09:37:32.835  3420  3548 W ActivityManager: Activity pause timeout for ActivityRecord{47a1510 u0 com.test.thalitest/.MainActivity t75}
09-20 09:37:32.905  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 09:37:32.915  9662  9662 D libEGL  : eglInitialize EGLDisplay = 0xffda001c
09-20 09:37:32.985  3420  4898 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
09-20 09:37:32.985  3420  4898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-20 09:37:33.035  9662  9662 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-20 09:37:33.045  9662  9662 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-20 09:37:33.045  9662  9662 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-20 09:37:33.065  9662  9662 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-20 09:37:33.085  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:33.095  3420  6106 D SSRM:n  : SIOP:: AP = 260, PST = 292 (W:14), CP = 218, CUR = 150, LCD = 1
,09-20 09:37:33.105  9662  9662 D Activity: performCreate Call Injection manager
,09-20 09:37:33.105  9662  9662 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-20 09:37:33.115  9662  9662 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-20 09:37:33.125  9662  9662 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5002c87 I.E...... R.....ID 0,0-0,0}
,09-20 09:37:33.125  9662  9714 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-20 09:37:33.135  3420  4898 W WindowManager: Failed looking up window
09-20 09:37:33.135  3420  4898 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@565b007 does not exist
09-20 09:37:33.135  3420  4898 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 09:37:33.135  3420  4898 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 09:37:33.135  3420  4898 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 09:37:33.135  3420  4898 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-20 09:37:33.135  3420  4898 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-20 09:37:33.135  3420  4898 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-20 09:37:33.135  3420  4388 D ISSUE_DEBUG: InputChannelName : 4584534 com.test.thalitest/com.test.thalitest.MainActivity
,09-20 09:37:33.135  3420  4061 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-20 09:37:33.135  3420  4061 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 09:37:33.135  3420  3420 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-20 09:37:33.135  3420  3420 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-20 09:37:33.145  9662  9662 V ActivityThread: updateVisibility : ActivityRecord{7258fdd token=android.os.BinderProxy@142688e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-20 09:37:33.145  9662  9677 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-20 09:37:33.165  9662  9662 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9662
,09-20 09:37:33.175  3420  4061 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9662 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 09:37:33.175  3420  3867 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-20 09:37:33.175  3420  3867 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-20 09:37:33.175  3420  3867 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-20 09:37:33.185  3420  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 09:37:33.185  3420  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 09:37:33.185  3420  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-20 09:37:33.185  9662  9662 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-20 09:37:33.195  3420  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 09:37:33.195  3420  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-20 09:37:33.195  3420  3867 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 09:37:33.205  3008  3008 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,09-20 09:37:33.235  9662  9714 D libEGL  : eglInitialize EGLDisplay = 0xdc8bf7c4
,09-20 09:37:33.235  9662  9714 I OpenGLRenderer: Initialized EGL, version 1.4
,09-20 09:37:33.245  9662  9714 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-20 09:37:33.245  3420  3479 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3420
,09-20 09:37:33.245  3420  3479 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 09:37:33.245  3420  3479 D PowerManagerService: mDisplayReady: false
,09-20 09:37:33.245  3420  3479 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 09:37:33.245  3420  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-20 09:37:33.245  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa0083c00
09-20 09:37:33.245  3420  3479 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 09:37:33.245  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-20 09:37:33.245  3420  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 09:37:33.245  3420  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 09:37:33.255  3008  3053 W SurfaceFlinger: Ignoring duplicate VSYNC event from HWC (t=192660379399)
,09-20 09:37:33.245  3420  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 09:37:33.245  3420  3580 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-20 09:37:33.245  3420  3568 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-20 09:37:33.245  3420  3568 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-20 09:37:33.265  3420  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 09:37:33.265  3420  3571 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 09:37:33.265  3420  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 09:37:33.265  3420  3571 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 09:37:33.265  3420  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 09:37:33.265  3420  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 09:37:33.265  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 09:37:33.265  3420  3571 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 09:37:33.265  3420  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 09:37:33.265  3420  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 09:37:33.265  3420  3571 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 09:37:33.265  3420  3571 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 09:37:33.265  3420  3571 D PowerManagerService: mDisplayReady: true
09-20 09:37:33.265  3420  3571 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 09:37:33.275  5823  5823 E CocktailBarPositionManager: Window direction: 0
09-20 09:37:33.275  5823  5823 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 09:37:33.275  9662  9662 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-20 09:37:33.285  9662  9662 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-20 09:37:33.295  9662  9718 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-20 09:37:33.295  9662  9718 D libEGL  : eglInitialize EGLDisplay = 0xdb1ac3f4
09-20 09:37:33.295  3420  3477 V WindowStateAnimator: Finishing drawing window Window{4584534 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-20 09:37:33.305  9662  9662 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@142688e time:192711
,09-20 09:37:33.305  3420  3568 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 09:37:33.305  3420  3420 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-20 09:37:33.305  3420  3568 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +973ms (total +1s425ms)
09-20 09:37:33.305  3420  3420 I KnoxTimeoutHandler: SD activityfalse
,09-20 09:37:33.315  3420  3568 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{47a1510 u0 com.test.thalitest/.MainActivity t75} time:192722
09-20 09:37:33.315  3420  3568 D ActivityManager: mDVFSHelper.release()
09-20 09:37:33.315  3420  3568 D ViewRootImpl: #3 mView = null
09-20 09:37:33.315  9662  9718 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-20 09:37:33.315  3008  3019 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
09-20 09:37:33.315  3008  3017 I SurfaceFlinger: id=20 Removed uhalitest (-2/11)
,09-20 09:37:33.325  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fdc719718
,09-20 09:37:33.345  3420  6107 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-20 09:37:33.365  9662  9662 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9662
,09-20 09:37:33.395  3420  3420 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3420 (0x0)
09-20 09:37:33.395  3420  3420 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 09:37:33.395  3420  3420 D PowerManagerService: mDisplayReady: false
09-20 09:37:33.395  3420  3420 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 09:37:33.395  3420  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 09:37:33.395  3420  3420 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 09:37:33.395  3420  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 09:37:33.395  3420  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 09:37:33.395  3420  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 09:37:33.395  3420  3580 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-20 09:37:33.395  3420  3568 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-20 09:37:33.395  3420  3568 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-20 09:37:33.395  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa0083c00
09-20 09:37:33.395  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,09-20 09:37:33.415  3420  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 09:37:33.415  3420  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 09:37:33.415  3420  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 09:37:33.415  3420  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 09:37:33.415  3420  3571 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 09:37:33.415  3420  3571 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 09:37:33.415  3420  3571 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 09:37:33.415  3420  3571 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 09:37:33.415  3420  3571 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 09:37:33.415  3420  3571 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 09:37:33.415  3420  3571 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 09:37:33.415  3420  3571 D PowerManagerService: mDisplayReady: true
09-20 09:37:33.415  3420  3571 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 09:37:33.415  5823  5823 E CocktailBarPositionManager: Window direction: 0
09-20 09:37:33.415  5823  5823 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 09:37:33.445  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:33.535  9662  9662 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-20 09:37:33.625  9662  9725 D jxcore_app_log: JniHelper::setJavaVM(0xf4f74000), pthread_self() = -629147344
,09-20 09:37:33.625  9662  9725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-20 09:37:33.625  9662  9725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-20 09:37:33.625  9662  9725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-20 09:37:33.625  9662  9725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-20 09:37:33.625  9662  9725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-20 09:37:33.625  9662  9725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6e74577 added. We now have 1 listener(s)
09-20 09:37:33.625  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:33.625  9662  9725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
,09-20 09:37:33.625  9662  9725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-20 09:37:33.635  9662  9725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-20 09:37:33.635  9662  9725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-20 09:37:33.635  9662  9725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa6a902 added. We now have 1 listener(s)
09-20 09:37:33.635  9662  9725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-20 09:37:33.635  9662  9725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-20 09:37:33.635  9662  9725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-20 09:37:33.635  9662  9725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-20 09:37:33.635  9662  9725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-20 09:37:33.635  9662  9725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-20 09:37:33.645  9662  9725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 09:37:33.645  9662  9725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
09-20 09:37:33.645  9662  9725 D BluetoothAdapter: STATE_ON
09-20 09:37:33.655  9662  9725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-20 09:37:33.655  9662  9725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 09:37:33.655  9662  9725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 09:37:33.655  9662  9725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 09:37:33.655  9662  9725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 09:37:33.655  9662  9725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 09:37:33.655  9662  9725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 09:37:33.655  9662  9725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 09:37:33.655  9662  9725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-20 09:37:33.655  9662  9725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-20 09:37:33.655  9662  9725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-20 09:37:33.655  9662  9725 I io.jxcore.node.LifeCycleMonitor: start: OK
09-20 09:37:33.655  9662  9662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-20 09:37:33.665  9662  9662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 09:37:33.685  9662  9662 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-20 09:37:33.805  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:33.835  4025  4025 D Recents : onTaskStackChanged
,09-20 09:37:33.845  4025  4025 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-20 09:37:33.855  4025  4025 D ResourcesManager: For user 0 new overlays fetched Null
,09-20 09:37:33.925  3420  4145 E Watchdog: !@Sync 6 [09-20 09:37:33.941]
,09-20 09:37:33.985  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:34.015  9662  9726 W jxcore-log: Initializing JXcore engine
09-20 09:37:34.015  9662  9726 W jxcore-log: JXcore engine is ready
,09-20 09:37:34.035  5025  5025 E audit   : type=1400 msg=audit(1474357054.035:264): avc:  denied  { ioctl } for  pid=9726 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3221 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-20 09:37:34.035  5025  5025 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-20 09:37:34.035  5025  5025 E audit   : type=1300 msg=audit(1474357054.035:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d95043c8 items=0 ppid=3177 pid=9726 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-20 09:37:34.035  5025  5025 E audit   : type=1327 msg=audit(1474357054.035:264): proctitle="com.test.thalitest"
09-20 09:37:34.035  5025  5025 E audit   : type=1320 msg=audit(1474357054.035:264): 
09-20 09:37:34.035  5025  5025 E audit   : type=1400 msg=audit(1474357054.035:265): avc:  denied  { ioctl } for  pid=9726 comm="Thread-160" path="socket:[39967]" dev="sockfs" ino=39967 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-20 09:37:34.035  5025  5025 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-20 09:37:34.035  5025  5025 E audit   : type=1300 msg=audit(1474357054.035:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d95043c8 items=0 ppid=3177 pid=9726 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-20 09:37:34.035  5025  5025 E audit   : type=1327 msg=audit(1474357054.035:265): proctitle="com.test.thalitest"
09-20 09:37:34.035  5025  5025 E audit   : type=1320 msg=audit(1474357054.035:265): 
,09-20 09:37:34.045  9662  9726 W jxcore-log: Starting JXcore engine
,09-20 09:37:34.075  9662  9726 W jxcore-log: Platform android
09-20 09:37:34.075  9662  9726 W jxcore-log: 
09-20 09:37:34.075  9662  9726 W jxcore-log: Process ARCH arm
09-20 09:37:34.075  9662  9726 W jxcore-log: 
,09-20 09:37:34.145  9662  9726 I jxcore-log: JXcore Cordova bridge is ready!
09-20 09:37:34.145  9662  9726 I jxcore-log: 
09-20 09:37:34.145  9662  9726 W jxcore-log: JXcore engine is started
,09-20 09:37:34.155  9662  9725 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-20 09:37:34.155  9662  9662 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-20 09:37:34.165  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:34.345  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:34.525  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:34.705  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:34.885  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:34.885  3420  3906 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/75_task.xml.bak
,09-20 09:37:35.065  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:35.245  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:35.295  4398  4463 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-20 09:37:35.295  4398  4463 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-20 09:37:35.355  3420  6106 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-20 09:37:35.425  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:35.605  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:35.785  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:35.965  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:36.145  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:36.325  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:36.505  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:36.685  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:36.865  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:37.045  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:37.225  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:37.405  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:37.585  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:37.765  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:37.945  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:38.125  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:38.295  9662  9726 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-20 09:37:38.295  9662  9726 I jxcore-log: 
,09-20 09:37:38.295  9662  9726 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-20 09:37:38.295  9662  9726 I jxcore-log: 
,09-20 09:37:38.305  9662  9726 D BluetoothAdapter: STATE_ON
,09-20 09:37:38.305  9662  9726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 09:37:38.305  9662  9726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 09:37:38.305  9662  9726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 09:37:38.305  9662  9726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 09:37:38.305  9662  9726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 09:37:38.305  9662  9726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 09:37:38.305  9662  9726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 09:37:38.305  9662  9726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 09:37:38.305  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:38.305  9662  9726 D BluetoothAdapter: STATE_ON
,09-20 09:37:38.315  9662  9726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-20 09:37:38.315  9662  9726 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-20 09:37:38.315  9662  9726 I jxcore-log: 
,09-20 09:37:38.315  9662  9726 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-20 09:37:38.315  9662  9726 I jxcore-log: 
,09-20 09:37:38.445  3420  6106 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-20 09:37:38.485  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:38.555  9662  9726 D executeNativeTests: Running unit tests
,09-20 09:37:38.565  9662  9726 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
,09-20 09:37:38.565  9662  9726 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-20 09:37:38.565  9662  9726 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-20 09:37:38.565  9662  9726 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-20 09:37:38.565  9662  9726 D com.test.thalitest.ThaliTestRunner: Total duration: 1 ms
09-20 09:37:38.565  9662  9726 I jxcore-log: *Native tests were executed*
09-20 09:37:38.565  9662  9726 I jxcore-log: 
09-20 09:37:38.565  9662  9726 I jxcore-log: Total number of executed tests:  1
09-20 09:37:38.565  9662  9726 I jxcore-log: 
,09-20 09:37:38.565  9662  9726 I jxcore-log: Number of passed tests:  1
09-20 09:37:38.565  9662  9726 I jxcore-log: 
09-20 09:37:38.565  9662  9726 I jxcore-log: Number of failed tests:  0
09-20 09:37:38.565  9662  9726 I jxcore-log: 
09-20 09:37:38.565  9662  9726 I jxcore-log: Number of ignored tests:  0
09-20 09:37:38.565  9662  9726 I jxcore-log: 
09-20 09:37:38.565  9662  9726 I jxcore-log: Total duration:  1
09-20 09:37:38.565  9662  9726 I jxcore-log: 
,09-20 09:37:38.565  9662  9726 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-20 09:37:38.565  9662  9726 I jxcore-log: 
09-20 09:37:38.565  9662  9726 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-20 09:37:38.565  9662  9726 I jxcore-log: 
,09-20 09:37:38.585  9662  9662 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-20 09:37:38.665  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:38.845  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:39.025  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:39.025  9727  9727 I FIPS_bssl: FIPS approved mode (1) | 9727 | app_process
,09-20 09:37:39.035  9727  9727 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-20 09:37:39.035  9727  9727 D AndroidRuntime: CheckJNI is OFF
,09-20 09:37:39.035  9727  9727 D AndroidRuntime: readGMSProperty: start
09-20 09:37:39.035  9727  9727 D AndroidRuntime: readGMSProperty: already setted!!
09-20 09:37:39.035  9727  9727 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-20 09:37:39.035  9727  9727 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-20 09:37:39.035  9727  9727 D AndroidRuntime: readGMSProperty: end
09-20 09:37:39.035  9727  9727 D AndroidRuntime: addProductProperty: start
,09-20 09:37:39.055  9727  9727 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-20 09:37:39.075  9727  9727 I Radio-JNI: register_android_hardware_Radio DONE
,09-20 09:37:39.075  9727  9727 E AffinityControl: AffinityControl: registerfunction enter
,09-20 09:37:39.085  9727  9727 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-20 09:37:39.095  3420  4388 D PackageManager: START PACKAGE DELETE: observer{211850641}
09-20 09:37:39.095  3420  4388 D PackageManager: pkg{<packageName>}
09-20 09:37:39.095  3420  4388 D PackageManager: user{0}
09-20 09:37:39.095  3420  4388 D PackageManager: caller{2000}
09-20 09:37:39.095  3420  4388 D PackageManager: flags{2}
,09-20 09:37:39.095  3420  4388 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-20 09:37:39.095  3420  4388 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-20 09:37:39.095  3420  4388 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-20 09:37:39.095  3420  4388 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-20 09:37:39.095  3420  4388 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-20 09:37:39.095  3420  3589 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-20 09:37:39.095  3420  3589 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-20 09:37:39.095  3420  3589 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-20 09:37:39.095  3420  3589 D ApplicationPolicy: getApplicationUninstallationEnabled
,09-20 09:37:39.095  3420  3589 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-20 09:37:39.095  3420  3589 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-20 09:37:39.095  3420  3589 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-20 09:37:39.095  3420  3589 D PackageManager: !@killApplicatoin: 10177, uninstall pkg
09-20 09:37:39.095  3420  3589 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,09-20 09:37:39.095  3420  3548 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=-1: uninstall pkg
09-20 09:37:39.095  3420  3589 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-20 09:37:39.095  3420  3548 I ActivityManager: Killing 9662:com.test.thalitest/u0a177 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-20 09:37:39.105  3420  3548 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-20 09:37:39.115  3420  3548 D ActivityManager: mDVFSHelper.acquire()
,09-20 09:37:39.125  3420  3589 D AASAinstall: there is not AASApackages.xml file
,09-20 09:37:39.205  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:39.245  3420  4389 D GraphicsStats: Buffer count: 7
,09-20 09:37:39.245  3420  3980 I WindowState: WIN DEATH: Window{4584534 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
09-20 09:37:39.245  3420  4811 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@d180cf6)
,09-20 09:37:39.245  3420  3867 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 09:37:39.245  3420  3867 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 09:37:39.255  3008  3019 I SurfaceFlinger: id=21 Removed NainActivit (6/10)
,09-20 09:37:39.255  3420  3867 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 09:37:39.255  3008  4350 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
,09-20 09:37:39.275  3008  3019 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
,09-20 09:37:39.385  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:39.425  3420  3589 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-20 09:37:39.495  3420  3589 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-20 09:37:39.495  3420  3548 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-20 09:37:39.495  3165  3165 W keystore: ENTER clear_uid from uid 1000 for 10177
,09-20 09:37:39.495  3420  3548 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-20 09:37:39.505  3420  3589 I art     : Starting a blocking GC Explicit
,09-20 09:37:39.505  3420  3548 E ActivityManager: Failure starting process com.test.thalitest
09-20 09:37:39.505  3420  3548 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5277)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5194)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5032)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2643)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3481)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2595)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4997)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4958)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7379)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9146)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8769)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8924)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:458)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2597)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 09:37:39.505  3420  3548 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-20 09:37:39.515  3420  3548 I ActivityManager:   Force finishing activity ActivityRecord{47a1510 u0 com.test.thalitest/.MainActivity t75}
09-20 09:37:39.515  3420  3548 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
09-20 09:37:39.525  3420  3548 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
09-20 09:37:39.535  3008  3008 I SurfaceFlinger: id=22 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-20 09:37:39.565  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:39.575  4322  4322 D Launcher: onRestart, Launcher: 222156692
,09-20 09:37:39.605  3420  4388 V WindowStateAnimator: Finishing drawing window Window{f7a2f4d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-20 09:37:39.625  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fdc7195f8
,09-20 09:37:39.715  3420  3589 I art     : Explicit concurrent mark sweep GC freed 287182(18MB) AllocSpace objects, 64(3MB) LOS objects, 31% free, 34MB/50MB, paused 1.896ms total 216.077ms
,09-20 09:37:39.745  3420  3589 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-20 09:37:39.745  3420  3589 D AASAuninstall: userId = 0, info.removedAppID = 10177, info.uid = 10177, packageName = com.test.thalitest
09-20 09:37:39.745  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:39.745  3420  3589 D AASAinstall: there is not AASApackages.xml file
09-20 09:37:39.745  3420  3589 D PackageManager: result of delete: 1{211850641}
,09-20 09:37:39.745  3420  3589 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-20 09:37:39.745  3420  3589 D PackageManager: userId{-1}
09-20 09:37:39.745  3420  3589 D PackageManager: andCode{true}
09-20 09:37:39.745  9727  9727 I art     : System.exit called, status: 0
09-20 09:37:39.745  9727  9727 I AndroidRuntime: VM exiting with result code 0.
,09-20 09:37:39.855  3420  3548 I WindowManager: Screenshot max retries 4 of Token{61cb24c ActivityRecord{e61c27f u0 com.samsung.android.MtpApplication/.USBConnection t74}} appWin=Window{f7a2f4d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=2
,09-20 09:37:39.855  5823  5834 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,09-20 09:37:39.855  5823  5834 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} Intent { flg=0x10800000 cmp=com.samsung.android.MtpApplication/.USBConnection VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-20 09:37:39.855  3420  3420 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-20 09:37:39.875  3420  3568 W ResourceType: No known package when getting value for resource number 0x7f060012
,09-20 09:37:39.895  4322  4322 D Launcher: onStart, Launcher: 222156692
,09-20 09:37:39.895  3420  3548 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-20 09:37:39.895  4322  4322 D Launcher.HomeView: onStart
09-20 09:37:39.895  4322  4322 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-20 09:37:39.895  3420  3568 W ResourceType: No known package when getting value for resource number 0x7f02003b
,09-20 09:37:39.895  3420  3548 D InputDispatcher: Focused application released
09-20 09:37:39.895  3420  3568 W WindowManager: Token{4c60809 ActivityRecord{47a1510 u0 com.test.thalitest/.MainActivity t75 f}} failed creating starting window
09-20 09:37:39.895  3420  3568 W WindowManager: android.content.res.Resources$NotFoundException: Resource ID #0x7f02003b
09-20 09:37:39.895  3420  3568 W WindowManager: 	at android.content.res.Resources.getValue(Resources.java:2558)
09-20 09:37:39.895  3420  3568 W WindowManager: 	at android.content.res.Resources.getDrawable(Resources.java:2001)
09-20 09:37:39.895  3420  3568 W WindowManager: 	at android.content.res.Resources.getDrawable(Resources.java:1987)
09-20 09:37:39.895  3420  3568 W WindowManager: 	at android.content.Context.getDrawable(Context.java:464)
09-20 09:37:39.895  3420  3568 W WindowManager: 	at com.android.internal.widget.ToolbarWidgetWrapper.setIcon(ToolbarWidgetWrapper.java:352)
09-20 09:37:39.895  3420  3568 W WindowManager: 	at com.android.internal.widget.ActionBarOverlayLayout.setIcon(ActionBarOverlayLayout.java:738)
09-20 09:37:39.895  3420  3568 W WindowManager: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4709)
09-20 09:37:39.895  3420  3568 W WindowManager: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-20 09:37:39.895  3420  3568 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-20 09:37:39.895  3420  3568 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-20 09:37:39.895  3420  3568 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 09:37:39.895  3420  3568 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-20 09:37:39.895  3420  3568 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 09:37:39.895  3420  3568 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-20 09:37:39.905  4322  4322 V ActivityThread: updateVisibility : ActivityRecord{44d2a4f token=android.os.BinderProxy@1524383 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
09-20 09:37:39.895  3420  3568 I Choreographer: Skipped 36 frames!  The application may be doing too much work on its main thread.
,09-20 09:37:39.905  4322  4322 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
,09-20 09:37:39.905  4322  4322 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
09-20 09:37:39.905  4322  4322 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
09-20 09:37:39.905  4322  4322 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
,09-20 09:37:39.905  4322  4322 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
09-20 09:37:39.905  4322  4322 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
09-20 09:37:39.905  4322  4322 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-20 09:37:39.905  4322  4322 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
09-20 09:37:39.905  4322  4322 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
,09-20 09:37:39.905  3420  3980 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,09-20 09:37:39.905  3420  3980 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 09:37:39.915  3420  3589 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=0: pkg removed
,09-20 09:37:39.905  3420  3420 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-20 09:37:39.915  3008  3008 I SurfaceFlinger: id=23 createSurf (1592x384),1 flag=4, VSBConnecti
,09-20 09:37:39.925  3420  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 09:37:39.925  3420  3420 I KnoxTimeoutHandler: Shared devices show user statefalse
09-20 09:37:39.925  3420  3420 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-20 09:37:39.935  9158  9740 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-20 09:37:39.935  3008  3008 I SurfaceFlinger: id=24 createSurf (1440x2560),1 flag=4, MauncherAct
,09-20 09:37:39.945  9158  9740 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-20 09:37:39.955  9158  9740 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-20 09:37:39.955  4322  4647 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-20 09:37:39.965  3420  3568 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 09:37:39.965  3420  3420 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-20 09:37:39.965  3420  3420 I KnoxTimeoutHandler: SD activityfalse
,09-20 09:37:39.975  3420  3548 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-20 09:37:39.975  3420  3548 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-20 09:37:39.985  3420  3568 D ActivityManager: mDVFSHelper.release()
09-20 09:37:39.985  3420  3568 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e61c27f u0 com.samsung.android.MtpApplication/.USBConnection t74} time:199396
,09-20 09:37:39.985  3420  3906 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/75_task.xml
,09-20 09:37:39.995  3420  4892 V WindowStateAnimator: Finishing drawing window Window{627cf13 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING

```
