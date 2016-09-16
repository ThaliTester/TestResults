#### Test 85594025c926e20_thali04_samsung-SM-G935F Logs


```
--------- beginning of main
,09-16 18:19:37.193  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:37.363  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:37.543  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:37.673  9939  9939 I FIPS_bssl: FIPS approved mode (1) | 9939 | app_process
09-16 18:19:37.673  9939  9939 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 18:19:37.683  9939  9939 D AndroidRuntime: CheckJNI is OFF
09-16 18:19:37.683  9939  9939 D AndroidRuntime: readGMSProperty: start
09-16 18:19:37.683  9939  9939 D AndroidRuntime: readGMSProperty: already setted!!
09-16 18:19:37.683  9939  9939 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-16 18:19:37.683  9939  9939 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-16 18:19:37.683  9939  9939 D AndroidRuntime: readGMSProperty: end
09-16 18:19:37.683  9939  9939 D AndroidRuntime: addProductProperty: start
09-16 18:19:37.703  9939  9939 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 18:19:37.723  9939  9939 I Radio-JNI: register_android_hardware_Radio DONE
09-16 18:19:37.723  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:37.723  9939  9939 E AffinityControl: AffinityControl: registerfunction enter
09-16 18:19:37.733  9939  9939 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-16 18:19:37.763  3426  4844 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-16 18:19:37.763  3426  4844 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-16 18:19:37.783  3426  4844 D ResourcesManager: For user 0 new overlays fetched Null
09-16 18:19:37.783  3426  4844 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 18:19:37.783  3426  4844 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-16 18:19:37.793  3426  4844 D ActivityManager: mDVFSHelper.acquire()
09-16 18:19:37.793  3426  4844 V WindowManager: addAppToken: AppWindowToken{d02b67bc7 token=Token{6e52906 ActivityRecord{adf57e1 u0 com.test.thalitest/.MainActivity t75}}} to stack=2 task=75 at 0
09-16 18:19:37.793  3426  3561 I InjectionManager: Inside getClassLibPath caller 
09-16 18:19:37.813  3426  3561 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-16 18:19:37.813  3426  3561 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{411cbf V.E...... R.....ID 0,0-0,0}
09-16 18:19:37.813  3426  3561 W WindowManager: Failed looking up window
09-16 18:19:37.813  3426  3561 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@d359f8c does not exist
09-16 18:19:37.813  3426  3561 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 18:19:37.813  3426  3561 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 18:19:37.813  3426  3561 D ISSUE_DEBUG: InputChannelName : 8b9c6d5 Starting com.test.thalitest
09-16 18:19:37.813  9948  9948 E Zygote  : v2
09-16 18:19:37.813  9948  9948 I libpersona: KNOX_SDCARD checking this for 10177
09-16 18:19:37.813  9948  9948 I libpersona: KNOX_SDCARD not a persona
09-16 18:19:37.823  9948  9948 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 18:19:37.823  9948  9948 E Zygote  : accessInfo : 0
09-16 18:19:37.823  9948  9948 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-16 18:19:37.823  3426  4844 I ActivityManager: Start proc 9948:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-16 18:19:37.823  3426  4844 D InputDispatcher: Focused application set to: xxxx
09-16 18:19:37.823  9939  9939 D AndroidRuntime: Shutting down VM
09-16 18:19:37.823  3426  3859 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-16 18:19:37.833  3010  3010 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-16 18:19:37.853  6525  6525 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 18:19:37.863  9948  9948 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 18:19:37.863  9948  9948 D ActivityThread: Added TimaKeyStore provider
09-16 18:19:37.863  3426  3856 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3426
09-16 18:19:37.863  3426  3856 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 18:19:37.863  3426  3856 D PowerManagerService: mDisplayReady: false
09-16 18:19:37.863  3426  3856 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 18:19:37.863  3426  3565 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 18:19:37.863  3426  3561 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 18:19:37.863  3426  3565 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 18:19:37.863  3426  3426 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 18:19:37.863  3426  3856 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 18:19:37.863  6525  6525 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 18:19:37.863  3426  3565 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 18:19:37.863  3010  3010 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f9c9c3c00
09-16 18:19:37.863  3426  3565 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 18:19:37.863  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-16 18:19:37.863  3426  3575 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-16 18:19:37.863  3426  4846 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3426
09-16 18:19:37.863  3426  3561 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-16 18:19:37.863  3426  3561 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-16 18:19:37.863  3426  3561 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-16 18:19:37.873  3010  3054 W SurfaceFlinger: Ignoring duplicate VSYNC event from HWC (t=216300989844)
09-16 18:19:37.883  3426  3565 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 18:19:37.883  3426  3565 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 18:19:37.883  3426  3565 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 18:19:37.883  3426  3565 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 18:19:37.883  3426  3565 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 18:19:37.883  3426  3565 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 18:19:37.883  3426  3565 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 18:19:37.883  3426  3565 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 18:19:37.883  3426  3565 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 18:19:37.883  3426  3565 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 18:19:37.883  3426  3565 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 18:19:37.883  3426  3565 D PowerManagerService: mDisplayReady: true
09-16 18:19:37.883  3426  3565 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-16 18:19:37.883  3426  3426 I KnoxTimeoutHandler: SD activityfalse
09-16 18:19:37.893  3426  4844 V WindowStateAnimator: Finishing drawing window Window{3bdfd2b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-16 18:19:37.903  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:37.903  6190  6190 E CocktailBarPositionManager: Window direction: 0
09-16 18:19:37.903  6190  6190 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-16 18:19:37.933  3426  3561 V WindowStateAnimator: Finishing drawing window Window{8b9c6d5 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-16 18:19:37.933  3426  4201 D ActivityManager:  Launching com.test.thalitest, updated priority
09-16 18:19:37.943  3010  3010 D libEGL  : eglInitialize EGLDisplay = 0x7fe9be0a38
09-16 18:19:37.943  3426  4476 V WindowStateAnimator: Finishing drawing window Window{ebb39a5 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-16 18:19:37.943  6525  6525 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 18:19:37.943  6525  6525 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 18:19:37.943  6525  6525 V ActivityThread: updateVisibility : ActivityRecord{a7b21 token=android.os.BinderProxy@cd31faa {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-16 18:19:37.943  3010  3018 I SurfaceFlinger: id=18 Removed VSBConnecti (8/13)
09-16 18:19:37.953  6190  6201 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-16 18:19:37.953  3010  4505 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/13)
09-16 18:19:37.953  3010  3843 D libEGL  : eglTerminate EGLDisplay = 0x7f951fee78
09-16 18:19:37.953  3010  3843 D libEGL  : eglTerminate EGLDisplay = 0x7f951fee78
09-16 18:19:37.953  3426  3426 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-16 18:19:37.963  3010  3843 I SurfaceFlinger: id=10 Removed MauncherAct (4/12)
09-16 18:19:37.963  3010  4505 I SurfaceFlinger: id=10 Removed MauncherAct (-2/12)
09-16 18:19:37.963  3010  4377 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
09-16 18:19:37.963  3010  3010 D libEGL  : eglTerminate EGLDisplay = 0x7fe9be0b58
09-16 18:19:37.963  3010  3010 D libEGL  : eglTerminate EGLDisplay = 0x7fe9be0b28
09-16 18:19:37.963  3010  3010 D libEGL  : eglTerminate EGLDisplay = 0x7fe9be0b58
09-16 18:19:37.963  3010  3010 D libEGL  : eglTerminate EGLDisplay = 0x7fe9be0b28
09-16 18:19:37.963  3010  3843 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
09-16 18:19:37.983  4328  4328 V ActivityThread: updateVisibility : ActivityRecord{52b0f8c token=android.os.BinderProxy@e431f4d {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-16 18:19:37.983  4328  4328 D Launcher: onTrimMemory. Level: 20
09-16 18:19:38.013  3426  3426 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3426 (0x0)
09-16 18:19:38.013  3426  3426 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3426 (0x0)
09-16 18:19:38.013  3426  3426 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 18:19:38.013  3426  3426 D PowerManagerService: mDisplayReady: false
09-16 18:19:38.013  3426  3426 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 18:19:38.013  3426  3565 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 18:19:38.013  3426  3426 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 18:19:38.013  3426  3565 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 18:19:38.013  3426  3565 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 18:19:38.013  3426  3565 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 18:19:38.013  3426  3575 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-16 18:19:38.013  3010  3010 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f9c9c3c00
09-16 18:19:38.013  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-16 18:19:38.013  3426  3565 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 18:19:38.013  3426  3565 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 18:19:38.013  3426  3565 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 18:19:38.013  3426  3565 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 18:19:38.013  3426  3565 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 18:19:38.013  3426  3565 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 18:19:38.013  3426  3565 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 18:19:38.013  3426  3565 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 18:19:38.013  3426  3565 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 18:19:38.013  3426  3565 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 18:19:38.013  3426  3565 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 18:19:38.013  3426  3565 D PowerManagerService: mDisplayReady: true
09-16 18:19:38.013  3426  3565 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-16 18:19:38.083  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:38.253  6190  6190 I TrayVisibilityController: handleMessage : msg.what = 1
09-16 18:19:38.273  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:38.293  3426  4201 I WindowManager: Screenshot max retries 4 of Token{6e52906 ActivityRecord{adf57e1 u0 com.test.thalitest/.MainActivity t75}} appWin=Window{8b9c6d5 u0 d0 Starting com.test.thalitest} drawState=4
09-16 18:19:38.293  6190  6200 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-16 18:19:38.293  3426  3561 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 18:19:38.293  3426  3528 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-16 18:19:38.293  3426  3426 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 18:19:38.293  3426  3561 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-16 18:19:38.293  3426  3561 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-16 18:19:38.293  6190  6190 I Utils   : isCurrentUser current = 0, ownerId = 0
09-16 18:19:38.293  6190  6190 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-16 18:19:38.293  6190  6190 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-16 18:19:38.293  3426  3859 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-16 18:19:38.303  3426  3426 I KnoxTimeoutHandler: SD activityfalse
09-16 18:19:38.303  3426  6444 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 18:19:38.303  3426  6444 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 18:19:38.333  6190  6190 E CocktailBarPositionManager: Window direction: 0
09-16 18:19:38.333  6190  6190 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-16 18:19:38.343  9948  9948 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 18:19:38.343  9948  9948 D RelationGraph: garbageCollect()
09-16 18:19:38.353  9948  9948 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-16 18:19:38.353  3426  4422 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 18:19:38.353  9948  9948 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-16 18:19:38.353  3426  6444 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-16 18:19:38.363  3426  6444 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 18:19:38.363  9948  9948 D ResourcesManager: For user 0 new overlays fetched Null
09-16 18:19:38.363  3426  6444 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-16 18:19:38.363  3426  6444 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 18:19:38.363  3426  6444 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 18:19:38.373  9948  9948 I InjectionManager: Inside getClassLibPath caller 
09-16 18:19:38.383  9948  9948 D InjectionManager: InjectionManager
09-16 18:19:38.383  9948  9948 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-16 18:19:38.383  9948  9948 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-16 18:19:38.383  9948  9948 I InjectionManager: featureStore :{}
09-16 18:19:38.393  9948  9948 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-16 18:19:38.393  9948  9948 D RelationGraph: garbageCollect()
09-16 18:19:38.393  9948  9948 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-16 18:19:38.423  9948  9948 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-16 18:19:38.443  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:38.473  9948  9948 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-16 18:19:38.483  9948  9948 D ResourcesManager: For user 0 new overlays fetched Null
09-16 18:19:38.483  9948  9948 I InjectionManager: Inside getClassLibPath caller 
09-16 18:19:38.493  9948  9948 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-16 18:19:38.543  3426  3883 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-16 18:19:38.563  9948  9948 I cr_LibraryLoader: Time to load native libraries: 41 ms (timestamps 6951-6992)
09-16 18:19:38.563  9948  9948 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-16 18:19:38.623  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:38.633  9948  9963 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-16 18:19:38.643  3426  3883 I MdnieScenarioControlService: mGameModeLauncher : false
09-16 18:19:38.643  3426  3883 I MdnieScenarioControlService: setUIMode
09-16 18:19:38.643  9948  9948 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6d36630}
09-16 18:19:38.643  9948  9948 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-16 18:19:38.673  9948  9948 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-16 18:19:38.713  9948  9948 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-16 18:19:38.783  3426  3528 W ActivityManager: Activity pause timeout for ActivityRecord{adf57e1 u0 com.test.thalitest/.MainActivity t75}
09-16 18:19:38.803  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:38.863  9948  9948 D libEGL  : eglInitialize EGLDisplay = 0xffd90f0c
09-16 18:19:38.953  3426  4605 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
09-16 18:19:38.953  3426  4605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-16 18:19:38.983  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:39.033  9948  9948 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-16 18:19:39.043  9948  9948 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-16 18:19:39.053  9948  9948 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-16 18:19:39.073  9948  9948 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-16 18:19:39.113  9948  9948 D Activity: performCreate Call Injection manager
09-16 18:19:39.113  9948  9948 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
09-16 18:19:39.123  9948  9948 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-16 18:19:39.133  9948  9948 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{fc439af I.E...... R.....ID 0,0-0,0}
09-16 18:19:39.143  9948 10000 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-16 18:19:39.143  3426  4605 W WindowManager: Failed looking up window
09-16 18:19:39.143  3426  4605 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@bcfd3ec does not exist
09-16 18:19:39.143  3426  4605 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-16 18:19:39.143  3426  4605 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-16 18:19:39.143  3426  4605 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-16 18:19:39.143  3426  4605 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-16 18:19:39.143  3426  4605 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-16 18:19:39.143  3426  4605 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-16 18:19:39.143  3426  3977 D ISSUE_DEBUG: InputChannelName : e9753b5 com.test.thalitest/com.test.thalitest.MainActivity
09-16 18:19:39.153  3426  4476 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-16 18:19:39.153  3426  4476 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 18:19:39.153  3426  3426 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 18:19:39.153  3426  3426 I KnoxTimeoutHandler: Shared devices show user statefalse
09-16 18:19:39.153  9948  9948 V ActivityThread: updateVisibility : ActivityRecord{4c90545 token=android.os.BinderProxy@df7f4d7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-16 18:19:39.163  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:39.163  9948  9963 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-16 18:19:39.183  9948  9948 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9948
09-16 18:19:39.183  3426  3473 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9948 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 18:19:39.193  3426  3870 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-16 18:19:39.193  3426  3870 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-16 18:19:39.193  3426  3870 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-16 18:19:39.203  3426  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-16 18:19:39.203  3426  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-16 18:19:39.203  9948  9948 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-16 18:19:39.213  3426  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-16 18:19:39.213  3426  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-16 18:19:39.213  3426  3870 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 18:19:39.223  3010  3010 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
09-16 18:19:39.253  9948 10000 D libEGL  : eglInitialize EGLDisplay = 0xdc5bf7c4
09-16 18:19:39.253  9948 10000 I OpenGLRenderer: Initialized EGL, version 1.4
09-16 18:19:39.253  9948 10000 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-16 18:19:39.263  3426  4184 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3426
09-16 18:19:39.263  3426  4184 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 18:19:39.263  3426  4184 D PowerManagerService: mDisplayReady: false
09-16 18:19:39.263  3426  4184 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 18:19:39.263  3426  3565 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 18:19:39.263  3426  4184 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 18:19:39.263  3426  3565 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 18:19:39.263  3426  3565 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 18:19:39.263  3426  3565 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 18:19:39.263  3010  3010 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f9c9c3c00
09-16 18:19:39.263  3426  3575 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-16 18:19:39.263  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-16 18:19:39.263  3426  3561 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-16 18:19:39.263  3426  3561 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-16 18:19:39.283  3426  3565 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 18:19:39.283  3426  3565 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 18:19:39.283  3426  3565 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 18:19:39.283  3426  3565 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 18:19:39.283  3426  3565 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 18:19:39.283  3426  3565 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 18:19:39.283  3426  3565 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 18:19:39.283  3426  3565 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 18:19:39.283  3426  3565 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 18:19:39.283  3426  3565 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 18:19:39.283  3426  3565 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 18:19:39.283  3426  3565 D PowerManagerService: mDisplayReady: true
09-16 18:19:39.283  3426  3565 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-16 18:19:39.283  6190  6190 E CocktailBarPositionManager: Window direction: 0
09-16 18:19:39.283  6190  6190 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-16 18:19:39.293  3426  6445 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-16 18:19:39.293  9948  9948 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-16 18:19:39.303  3426  4060 V WindowStateAnimator: Finishing drawing window Window{e9753b5 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-16 18:19:39.303  9948  9948 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-16 18:19:39.313  3426  4173 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3426
09-16 18:19:39.313  3426  3561 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 18:19:39.313  3426  3426 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 18:19:39.313  3426  4394 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3426
09-16 18:19:39.313  3426  3561 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s34ms (total +1s524ms)
09-16 18:19:39.313  3426  3561 D ActivityManager: mDVFSHelper.release()
09-16 18:19:39.313  3426  3561 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{adf57e1 u0 com.test.thalitest/.MainActivity t75} time:217749
09-16 18:19:39.313  3426  3426 I KnoxTimeoutHandler: SD activityfalse
09-16 18:19:39.323  3426  3473 V WindowStateAnimator: Finishing drawing window Window{e9753b5 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-16 18:19:39.323  3426  3561 D ViewRootImpl: #3 mView = null
09-16 18:19:39.323  3010  3020 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
09-16 18:19:39.323  9948 10004 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-16 18:19:39.323  9948 10004 D libEGL  : eglInitialize EGLDisplay = 0xdae7f3f4
09-16 18:19:39.323  3010  4505 I SurfaceFlinger: id=20 Removed uhalitest (-2/11)
09-16 18:19:39.333  9948  9948 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@df7f4d7 time:217760
09-16 18:19:39.343  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:39.343  3010  3010 D libEGL  : eglTerminate EGLDisplay = 0x7fe9be0b58
09-16 18:19:39.353  9948 10004 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-16 18:19:39.413  9948  9948 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9948
09-16 18:19:39.463  3426  3426 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3426 (0x0)
09-16 18:19:39.463  3426  3426 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 18:19:39.463  3426  3426 D PowerManagerService: mDisplayReady: false
09-16 18:19:39.463  3426  3426 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 18:19:39.463  3426  3565 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 18:19:39.463  3426  3426 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 18:19:39.463  3426  3565 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 18:19:39.463  3426  3565 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 18:19:39.463  3426  3565 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 18:19:39.463  3426  3575 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-16 18:19:39.463  3010  3010 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f9c9c3c00
09-16 18:19:39.463  3426  3561 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-16 18:19:39.463  3010  3010 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-16 18:19:39.463  3426  3561 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-16 18:19:39.483  3426  3565 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 18:19:39.483  3426  3565 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 18:19:39.483  3426  3565 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 18:19:39.483  3426  3565 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 18:19:39.483  3426  3565 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 18:19:39.483  3426  3565 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 18:19:39.483  3426  3565 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 18:19:39.483  3426  3565 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 18:19:39.483  3426  3565 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 18:19:39.483  3426  3565 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 18:19:39.483  3426  3565 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 18:19:39.483  3426  3565 D PowerManagerService: mDisplayReady: true
09-16 18:19:39.483  3426  3565 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-16 18:19:39.483  6190  6190 E CocktailBarPositionManager: Window direction: 0
09-16 18:19:39.483  6190  6190 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-16 18:19:39.523  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:39.603  9948  9948 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-16 18:19:39.693  9948 10011 D jxcore_app_log: JniHelper::setJavaVM(0xf4bb4000), pthread_self() = -632026832
09-16 18:19:39.693  9948 10011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-16 18:19:39.693  9948 10011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-16 18:19:39.693  9948 10011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-16 18:19:39.693  9948 10011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-16 18:19:39.693  9948 10011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-16 18:19:39.693  9948 10011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7cec9f added. We now have 1 listener(s)
09-16 18:19:39.703  9948 10011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
09-16 18:19:39.703  9948 10011 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-16 18:19:39.703  9948 10011 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 18:19:39.703  9948 10011 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-16 18:19:39.703  9948 10011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bf384a added. We now have 1 listener(s)
09-16 18:19:39.703  9948 10011 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 18:19:39.703  9948 10011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 18:19:39.703  9948 10011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-16 18:19:39.703  9948 10011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-16 18:19:39.703  9948 10011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-16 18:19:39.703  9948 10011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-16 18:19:39.703  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:39.713  9948 10011 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 18:19:39.713  9948 10011 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
09-16 18:19:39.713  9948 10011 D BluetoothAdapter: STATE_ON
09-16 18:19:39.723  9948 10011 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-16 18:19:39.723  9948 10011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 18:19:39.723  9948 10011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 18:19:39.723  9948 10011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 18:19:39.723  9948 10011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 18:19:39.723  9948 10011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 18:19:39.723  9948 10011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 18:19:39.723  9948 10011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 18:19:39.723  9948 10011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 18:19:39.723  9948 10011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-16 18:19:39.723  9948 10011 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 18:19:39.723  9948 10011 I io.jxcore.node.LifeCycleMonitor: start: OK
09-16 18:19:39.723  9948  9948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 18:19:39.733  9948  9948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 18:19:39.753  9948  9948 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-16 18:19:39.783  4028  4028 D Recents : onTaskStackChanged
,09-16 18:19:39.793  4028  4028 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-16 18:19:39.803  4028  4028 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 18:19:39.883  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:40.053  9948 10012 W jxcore-log: Initializing JXcore engine
09-16 18:19:40.053  9948 10012 W jxcore-log: JXcore engine is ready
,09-16 18:19:40.063  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:40.073  5053  5053 E audit   : type=1400 msg=audit(1474042780.073:262): avc:  denied  { ioctl } for  pid=10012 comm="Thread-164" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3097 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-16 18:19:40.073  5053  5053 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-16 18:19:40.073  5053  5053 E audit   : type=1300 msg=audit(1474042780.073:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d938a3c8 items=0 ppid=3178 pid=10012 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-164" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-16 18:19:40.073  5053  5053 E audit   : type=1327 msg=audit(1474042780.073:262): proctitle="com.test.thalitest"
09-16 18:19:40.073  5053  5053 E audit   : type=1320 msg=audit(1474042780.073:262): 
09-16 18:19:40.073  5053  5053 E audit   : type=1400 msg=audit(1474042780.073:263): avc:  denied  { ioctl } for  pid=10012 comm="Thread-164" path="socket:[39004]" dev="sockfs" ino=39004 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-16 18:19:40.073  5053  5053 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-16 18:19:40.073  5053  5053 E audit   : type=1300 msg=audit(1474042780.073:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d938a3c8 items=0 ppid=3178 pid=10012 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-164" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-16 18:19:40.073  5053  5053 E audit   : type=1327 msg=audit(1474042780.073:263): proctitle="com.test.thalitest"
09-16 18:19:40.073  5053  5053 E audit   : type=1320 msg=audit(1474042780.073:263): 
,09-16 18:19:40.073  9948 10012 W jxcore-log: Starting JXcore engine
,09-16 18:19:40.113  9948 10012 W jxcore-log: Platform android
09-16 18:19:40.113  9948 10012 W jxcore-log: 
09-16 18:19:40.113  9948 10012 W jxcore-log: Process ARCH arm
09-16 18:19:40.113  9948 10012 W jxcore-log: 
,09-16 18:19:40.183  9948 10012 I jxcore-log: JXcore Cordova bridge is ready!
09-16 18:19:40.183  9948 10012 I jxcore-log: 
09-16 18:19:40.183  9948 10012 W jxcore-log: JXcore engine is started
09-16 18:19:40.183  9948 10011 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-16 18:19:40.183  9948  9948 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-16 18:19:40.243  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:40.423  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:40.603  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:40.783  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:40.793  3426  3910 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/75_task.xml.bak
,09-16 18:19:40.963  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:41.143  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:41.303  3426  6444 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-16 18:19:41.323  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:41.503  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:41.683  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:41.863  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:42.043  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:42.223  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:42.403  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:42.583  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:42.763  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:42.943  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:43.123  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:43.303  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:43.483  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:43.663  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:43.843  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:44.023  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:44.203  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:44.383  3426  6444 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-16 18:19:44.383  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:44.563  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:44.743  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:44.923  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:44.943  3426  4142 E Watchdog: !@Sync 7 [09-16 18:19:44.956]
,09-16 18:19:45.103  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:45.283  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:45.283  3426  6444 D SSRM:n  : SIOP:: AP = 360, PST = 317 (W:6), CP = 266, CUR = 148, LCD = 1
,09-16 18:19:45.293  3426  6444 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-16 18:19:45.463  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:45.643  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:45.823  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:46.003  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:46.183  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:46.233  9948 10012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 18:19:46.233  9948 10012 I jxcore-log: 
,09-16 18:19:46.233  9948 10012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 18:19:46.233  9948 10012 I jxcore-log: 
,09-16 18:19:46.243  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.243  9948 10012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 18:19:46.243  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 18:19:46.243  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 18:19:46.243  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 18:19:46.243  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 18:19:46.243  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 18:19:46.243  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 18:19:46.243  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 18:19:46.253  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.253  9948 10012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 18:19:46.253  9948 10012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 18:19:46.253  9948 10012 I jxcore-log: 
09-16 18:19:46.253  9948 10012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 18:19:46.253  9948 10012 I jxcore-log: 
,09-16 18:19:46.363  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:46.413  9948 10012 I jxcore-log: Running unit tests
09-16 18:19:46.413  9948 10012 I jxcore-log: 
,09-16 18:19:46.413  9948 10012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 18:19:46.413  9948 10012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef111b3 added. We now have 2 listener(s)
09-16 18:19:46.413  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-16 18:19:46.413  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 18:19:46.413  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 18:19:46.413  9948 10012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 18:19:46.413  9948 10012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37b4370 added. We now have 2 listener(s)
,09-16 18:19:46.413  9948 10012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 18:19:46.413  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 18:19:46.413  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 18:19:46.423  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.433  9948 10012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 18:19:46.433  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 18:19:46.433  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 18:19:46.433  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 18:19:46.433  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 18:19:46.433  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 18:19:46.433  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 18:19:46.433  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 18:19:46.433  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.433  9948 10012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 18:19:46.433  9948 10012 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 18:19:46.433  9948 10012 D executeNativeTests: Running unit tests
,09-16 18:19:46.443  9948  9948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 18:19:46.443  9948  9948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 18:19:46.473  9948 10012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 18:19:46.473  9948 10012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c5401e added. We now have 3 listener(s)
09-16 18:19:46.473  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-16 18:19:46.473  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 18:19:46.473  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 18:19:46.473  9948 10012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 18:19:46.473  9948 10012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab9a0ff added. We now have 3 listener(s)
09-16 18:19:46.473  9948 10012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 18:19:46.483  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 18:19:46.483  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 18:19:46.493  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.493  9948 10012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 18:19:46.493  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 18:19:46.493  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 18:19:46.493  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 18:19:46.493  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 18:19:46.493  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 18:19:46.493  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 18:19:46.493  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 18:19:46.493  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.503  9948 10012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 18:19:46.503  9948 10012 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 18:19:46.503  9948 10012 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 18:19:46.503  9948 10012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 18:19:46.503  9948 10012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 18:19:46.503  9948 10012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 18:19:46.503  9948 10012 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-16 18:19:46.503  9948 10012 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 18:19:46.503  9948 10012 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 18:19:46.503  9948 10012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 18:19:46.503  9948 10012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-16 18:19:46.503  9948 10012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 18:19:46.503  9948 10012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 18:19:46.503  9948 10012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 18:19:46.503  9948 10012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 18:19:46.503  9948 10012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 18:19:46.503  9948 10012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 18:19:46.503  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 18:19:46.503  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 18:19:46.503  9948 10012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c5401e removed from the list
09-16 18:19:46.503  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 18:19:46.503  9948 10012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab9a0ff removed from the list
,09-16 18:19:46.503  9948  9948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 18:19:46.513  9948  9948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 18:19:46.513  9948 10012 D io.jxcore.node.ConnectivityMonitor: stop
09-16 18:19:46.513  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 18:19:46.513  9948 10012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 18:19:46.513  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 18:19:46.513  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 18:19:46.513  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 18:19:46.513  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 18:19:46.513  9948 10012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab9a0ff not in the list
09-16 18:19:46.513  9948 10012 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-16 18:19:46.513  9948 10012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 18:19:46.513  9948 10012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 18:19:46.513  9948 10012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 18:19:46.513  9948 10012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 18:19:46.513  9948 10012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 18:19:46.513  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 18:19:46.513  9948 10012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c5401e not in the list
09-16 18:19:46.513  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 18:19:46.513  9948 10012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab9a0ff not in the list
09-16 18:19:46.513  9948 10012 D io.jxcore.node.ConnectivityMonitor: stop
09-16 18:19:46.513  9948 10012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 18:19:46.513  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 18:19:46.513  9948 10012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 18:19:46.513  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 18:19:46.513  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 18:19:46.513  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 18:19:46.513  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 18:19:46.513  9948 10012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab9a0ff not in the list
,09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 18:19:46.523  9948 10012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 18:19:46.523  9948 10012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 18:19:46.523  9948 10012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 18:19:46.523  9948 10012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 18:19:46.523  9948 10012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 18:19:46.523  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 18:19:46.523  9948 10012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c5401e not in the list
09-16 18:19:46.523  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 18:19:46.523  9948 10012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab9a0ff not in the list
09-16 18:19:46.523  9948 10012 D io.jxcore.node.ConnectivityMonitor: stop
09-16 18:19:46.523  9948 10012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 18:19:46.523  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 18:19:46.523  9948 10012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 18:19:46.523  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 18:19:46.523  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 18:19:46.523  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 18:19:46.523  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 18:19:46.523  9948 10012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab9a0ff not in the list
09-16 18:19:46.523  9948 10012 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 18:19:46.523  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 18:19:46.533  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.533  9948 10012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 18:19:46.533  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 18:19:46.533  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 18:19:46.533  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 18:19:46.533  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 18:19:46.533  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 18:19:46.533  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 18:19:46.533  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 18:19:46.533  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.543  9948 10012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 18:19:46.543  9948 10012 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 18:19:46.543  9948 10012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 18:19:46.543  9948 10012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 18:19:46.543  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 18:19:46.543  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 18:19:46.543  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 18:19:46.543  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:46.543  9948  9948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 18:19:46.553  9948 10012 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 18:19:46.553  9948 10012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 18:19:46.553  9948  9948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 18:19:46.553  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.553  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.563  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.573  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 18:19:46.573  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.573  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.573  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 18:19:46.573  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 18:19:46.583  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.583  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.583  9948 10012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-16 18:19:46.593  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.593  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.593  9948 10012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-16 18:19:46.593  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 18:19:46.593  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-16 18:19:46.603  9948 10012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 18:19:46.603  9948 10012 D BluetoothLeScanner: Start Scan
,09-16 18:19:46.603  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.603  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.613  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.613  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.623  5043  5059 D BtGatt.GattService: registerClient() - UUID=c358d85b-9d51-40ad-b363-1676e3188da4
,09-16 18:19:46.663  5043  5194 D BtGatt.GattService: onClientRegistered() - UUID=c358d85b-9d51-40ad-b363-1676e3188da4, clientIf=7
,09-16 18:19:46.673  9948  9958 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-16 18:19:46.673  5043  5446 D BtGatt.GattService: start scan with filters
,09-16 18:19:46.673  5043  5446 D BtGatt.GattService: getScanSettings
,09-16 18:19:46.683  5043  5446 D BtGatt.GattService: Is it foreground application = true
,09-16 18:19:46.683  5043  5446 D BtGatt.GattService: not a background application
,09-16 18:19:46.693  5043  5446 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-16 18:19:46.703  5043  5446 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 18:19:46.703  5043  5446 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 18:19:46.703  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 18:19:46.703  5043  5235 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-16 18:19:46.703  5043  5235 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
09-16 18:19:46.703  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 18:19:46.703  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 18:19:46.703  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 18:19:46.703  5043  5224 D BtGatt.ScanManager: handling starting scan
09-16 18:19:46.703  5043  5224 D BtGatt.ScanManager: isFilteringSupported
09-16 18:19:46.703  5043  5224 D BluetoothAdapter: enableStandAloneBleMode=
,09-16 18:19:46.713  5043  5224 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.713  5043  5224 D BluetoothAdapter: STATE_ON,
09-16 18:19:46.713  9948 10012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 18:19:46.713  9948 10012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 18:19:46.713  9948  9948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 18:19:46.713  5043  5224 D BluetoothAdapter: STATE_ON
09-16 18:19:46.713  5043  5224 D BluetoothAdapter: STATE_ON
,09-16 18:19:46.713  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 18:19:46.723  5043  5224 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d36630
,09-16 18:19:46.723  5043  5235 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 94,
09-16 18:19:46.723  5043  5235 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest,
09-16 18:19:46.723  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 18:19:46.723  9948 10012 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 18:19:46.723  3426  3856 V AlarmManager:  remove PendingIntent] PendingIntent{9735e52: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:46.733  5043  5194 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-16 18:19:46.733  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:46.733  5043  5224 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
09-16 18:19:46.733  5043  5224 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-16 18:19:46.733  5043  5224 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-16 18:19:46.733  5043  5224 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-16 18:19:46.733  3426  3977 V AlarmManager:  remove PendingIntent] PendingIntent{2485523: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:46.733  5043  5235 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 14
,09-16 18:19:46.733  5043  5194 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
,09-16 18:19:46.733  5043  5235 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24567379
09-16 18:19:46.733  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:46.733  5043  5235 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
,09-16 18:19:46.733  5043  5224 D BtGatt.ScanManager: Starting BLE batch scan
09-16 18:19:46.733  5043  5224 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-16 18:19:46.733  5043  5235 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 18:19:46.743  3426  4476 V AlarmManager:  remove PendingIntent] PendingIntent{ecf1a20: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
09-16 18:19:46.733  5043  5235 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-16 18:19:46.733  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 5 => 5
09-16 18:19:46.733  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 5 => 5
09-16 18:19:46.733  5043  5235 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 18:19:46.733  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 5 => 5
,09-16 18:19:46.743  5043  5194 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-16 18:19:46.743  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 5 => 5
09-16 18:19:46.743  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:46.743  3426  3983 V AlarmManager:  remove PendingIntent] PendingIntent{ce40fd9: PendingIntentRecord{4c50d9e com.android.bluetooth broadcastIntent}}
,09-16 18:19:46.743  5043  5235 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 18:19:46.743  5043  5235 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 18:19:46.743  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 5 => 5
09-16 18:19:46.743  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 5 => 5
09-16 18:19:46.743  5043  5235 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24567379
,09-16 18:19:46.743  5043  5194 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-16 18:19:46.743  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 18:19:46.743  3426  4422 V AlarmManager:  remove PendingIntent] PendingIntent{841207f: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:46.753  3426  4184 V AlarmManager:  remove PendingIntent] PendingIntent{cdbb84c: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:46.753  3426  4605 V AlarmManager:  remove PendingIntent] PendingIntent{27cd095: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:46.763  3426  3473 V AlarmManager:  remove PendingIntent] PendingIntent{ef065aa: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:46.763  3426  3983 V AlarmManager:  remove PendingIntent] PendingIntent{6d1459b: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:46.763  3426  4173 V AlarmManager:  remove PendingIntent] PendingIntent{b320d38: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:46.773  3426  4394 V AlarmManager:  remove PendingIntent] PendingIntent{5a6e111: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:46.773  3426  4844 V AlarmManager:  remove PendingIntent] PendingIntent{4c73276: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:46.783  3426  4863 V AlarmManager:  remove PendingIntent] PendingIntent{774a077: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:46.783  3426  3474 V AlarmManager:  remove PendingIntent] PendingIntent{896c4e4: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:46.903  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:47.083  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:47.213  9948  9948 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 18:19:47.213  9948  9948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 18:19:47.213  9948  9948 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 18:19:47.263  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:47.333  3153  3631 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-16 18:19:47.443  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:47.623  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:47.753  3426  3818 V AlarmManager: Expired Alarm result :4
,09-16 18:19:47.753  5043  5043 D BtGatt.ScanManager: awakened up at time 226180
,09-16 18:19:47.753  5043  5224 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-16 18:19:47.753  3426  4201 V AlarmManager:  remove PendingIntent] PendingIntent{c6c0002: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:47.763  5043  5194 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=7
,09-16 18:19:47.763  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:47.763  5043  5194 D BtGatt.GattService: current time is 226198811645
09-16 18:19:47.763  3426  4184 V AlarmManager:  remove PendingIntent] PendingIntent{588cd13: PendingIntentRecord{4c50d9e com.android.bluetooth broadcastIntent}}
09-16 18:19:47.773  5043  5194 D BtGatt.GattService: Batch record : [-106, -15, -31, -128, 20, -7, 1, 0, -98, 14, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -117, 46, 5, 3, 2, -25, 21, 62, 65, 100, -126, 28, 6, 8, 116, 105, 115, 54, 54, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 71, -122, -77, 84, 69, -12, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, 4, -82, 2, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -83, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 50, -35, 86, -77, -92, -11, 1, 0, -97, 8, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 21, 50, 5, 3, 2, -33, 21, 61, 74, -78, -25, 28, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 81, 34, 97, 112, -14, -5, 1, -128, -78, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-16 18:19:47.773  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -117, 46, 5, 3, 2, -25, 21, 62, 65, 100, -126, 6, 8, 116, 105, 115, 54, 54, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
09-16 18:19:47.773  5043  5194 D ScanRecord: parseFromBytes
,09-16 18:19:47.773  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:47.773  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-16 18:19:47.773  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:47.773  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:47.773  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-16 18:19:47.773  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:47.773  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:47.773  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-16 18:19:47.773  5043  5194 D ScanRecord: parseFromBytes
,09-16 18:19:47.773  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:47.773  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 21, 50, 5, 3, 2, -33, 21, 61, 74, -78, -25, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
09-16 18:19:47.773  5043  5194 D ScanRecord: parseFromBytes
,09-16 18:19:47.773  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:47.773  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 18:19:47.773  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:47.773  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:47.783  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-16 18:19:47.783  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:47.783  5043  5194 D ScanRecord: first manudata for manu ID
,09-16 18:19:47.783  9948  9959 D ScanRecord: parseFromBytes
,09-16 18:19:47.783  9948  9959 D ScanRecord: first manudata for manu ID
,09-16 18:19:47.793  9948  9959 D ScanRecord: parseFromBytes
09-16 18:19:47.793  9948  9959 D ScanRecord: first manudata for manu ID
,09-16 18:19:47.793  9948  9959 D ScanRecord: parseFromBytes
09-16 18:19:47.793  9948  9959 D ScanRecord: first manudata for manu ID
09-16 18:19:47.793  9948  9959 D ScanRecord: parseFromBytes
09-16 18:19:47.793  9948  9959 D ScanRecord: first manudata for manu ID
09-16 18:19:47.793  3426  4605 V AlarmManager:  remove PendingIntent] PendingIntent{96d4b50: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:47.793  9948  9959 D ScanRecord: parseFromBytes
,09-16 18:19:47.793  9948  9959 D ScanRecord: first manudata for manu ID
09-16 18:19:47.793  9948  9959 D ScanRecord: parseFromBytes
09-16 18:19:47.793  9948  9959 D ScanRecord: first manudata for manu ID
09-16 18:19:47.793  9948  9959 D ScanRecord: parseFromBytes
,09-16 18:19:47.793  9948  9959 D ScanRecord: first manudata for manu ID
,09-16 18:19:47.793  3426  3473 V AlarmManager:  remove PendingIntent] PendingIntent{5ba149: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:47.803  3426  3983 V AlarmManager:  remove PendingIntent] PendingIntent{99e1a4e: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:47.803  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:47.803  3426  4173 V AlarmManager:  remove PendingIntent] PendingIntent{aa9276f: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:47.813  3426  4060 V AlarmManager:  remove PendingIntent] PendingIntent{2e3cc7c: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:47.823  3426  4844 V AlarmManager:  remove PendingIntent] PendingIntent{7340905: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:47.823  3426  4863 V AlarmManager:  remove PendingIntent] PendingIntent{ac58d5a: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:47.833  3426  3474 V AlarmManager:  remove PendingIntent] PendingIntent{4cacb8b: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:47.833  3426  4422 V AlarmManager:  remove PendingIntent] PendingIntent{cdf3468: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:47.843  3426  4184 V AlarmManager:  remove PendingIntent] PendingIntent{d713081: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:47.843  3426  3584 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-16 18:19:47.853  3426  3584 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-16 18:19:47.863  3426  3856 V AlarmManager:  remove PendingIntent] PendingIntent{abf2526: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:47.983  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:48.163  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:48.343  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:48.523  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:48.703  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:48.773  3426  3818 V AlarmManager: Expired Alarm result :4
,09-16 18:19:48.773  5043  5043 D BtGatt.ScanManager: awakened up at time 227207
,09-16 18:19:48.773  5043  5224 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-16 18:19:48.783  3426  3473 V AlarmManager:  remove PendingIntent] PendingIntent{6a72f14: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:48.793  5043  5194 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
,09-16 18:19:48.793  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 18:19:48.793  3426  3474 V AlarmManager:  remove PendingIntent] PendingIntent{2ff53bd: PendingIntentRecord{4c50d9e com.android.bluetooth broadcastIntent}}
09-16 18:19:48.793  5043  5194 D BtGatt.GattService: current time is 227223683644
09-16 18:19:48.793  5043  5194 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -75, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -74, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 85, -113, -37, 31, -33, 8, 0, 4, -82, 11, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-16 18:19:48.793  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-16 18:19:48.793  5043  5194 D ScanRecord: parseFromBytes
,09-16 18:19:48.793  5043  5194 D ScanRecord: first manudata for manu ID
,09-16 18:19:48.793  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-16 18:19:48.793  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:48.793  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:48.803  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-16 18:19:48.803  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:48.803  5043  5194 D ScanRecord: first manudata for manu ID
,09-16 18:19:48.803  9948  9958 D ScanRecord: parseFromBytes
09-16 18:19:48.803  9948  9958 D ScanRecord: first manudata for manu ID
09-16 18:19:48.803  9948  9958 D ScanRecord: parseFromBytes
09-16 18:19:48.803  9948  9958 D ScanRecord: first manudata for manu ID
09-16 18:19:48.803  3426  4422 V AlarmManager:  remove PendingIntent] PendingIntent{3686db2: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:48.803  9948  9958 D ScanRecord: parseFromBytes
09-16 18:19:48.803  9948  9958 D ScanRecord: first manudata for manu ID
,09-16 18:19:48.813  3426  4184 V AlarmManager:  remove PendingIntent] PendingIntent{e8f2103: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:48.813  3426  3856 V AlarmManager:  remove PendingIntent] PendingIntent{a522880: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:48.823  3426  4863 V AlarmManager:  remove PendingIntent] PendingIntent{526eb9: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:48.823  3426  3977 V AlarmManager:  remove PendingIntent] PendingIntent{cebb2fe: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:48.883  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:49.063  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:49.073  3153  3631 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-16 18:19:49.083  4290  5896 I GCM     : GCM message de.axelspringer.yana.zeropage 0:1474042788473812%c87a4dc1ff0711f0
,09-16 18:19:49.103  3426  4060 V AlarmManager:  remove PendingIntent] PendingIntent{f58ca5f: PendingIntentRecord{e84c7d7 com.google.android.gms broadcastIntent}}
,09-16 18:19:49.143  3426  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{af14cac u0 com.google.android.c2dm.intent.RECEIVE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6e00997 4609:de.axelspringer.yana.zeropage/u0a2}
,09-16 18:19:49.243  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:49.423  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:49.603  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:49.783  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:49.793  3426  3818 V AlarmManager: Expired Alarm result :4
,09-16 18:19:49.803  5043  5043 D BtGatt.ScanManager: awakened up at time 228231
,09-16 18:19:49.803  5043  5224 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-16 18:19:49.803  3426  4476 V AlarmManager:  remove PendingIntent] PendingIntent{7e9ad7b: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:49.813  5043  5194 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-16 18:19:49.813  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 18:19:49.813  3426  4422 V AlarmManager:  remove PendingIntent] PendingIntent{97c8798: PendingIntentRecord{4c50d9e com.android.bluetooth broadcastIntent}}
,09-16 18:19:49.833  3426  4201 V AlarmManager:  remove PendingIntent] PendingIntent{2e63bf1: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:49.833  3426  4844 V AlarmManager:  remove PendingIntent] PendingIntent{fb123d6: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:49.963  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:50.153  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:50.333  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:50.503  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:50.683  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:50.823  3426  3818 V AlarmManager: Expired Alarm result :4
,09-16 18:19:50.823  5043  5043 D BtGatt.ScanManager: awakened up at time 229252
,09-16 18:19:50.823  5043  5224 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-16 18:19:50.823  5043  5194 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-16 18:19:50.823  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 18:19:50.823  3426  4422 V AlarmManager:  remove PendingIntent] PendingIntent{c7e8544: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
09-16 18:19:50.833  3426  3473 V AlarmManager:  remove PendingIntent] PendingIntent{511a62d: PendingIntentRecord{4c50d9e com.android.bluetooth broadcastIntent}}
,09-16 18:19:50.843  3426  4201 V AlarmManager:  remove PendingIntent] PendingIntent{cf3a762: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:50.853  3426  4844 V AlarmManager:  remove PendingIntent] PendingIntent{88a50f3: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:50.863  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:51.043  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:51.223  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:51.403  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:51.583  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:51.733  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:51.743  9948 10012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 18:19:51.743  9948 10012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 18:19:51.743  9948 10012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 18:19:51.743  9948 10012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 18:19:51.743  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 18:19:51.743  9948 10012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 18:19:51.743  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-16 18:19:51.743  9948 10012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 18:19:51.743  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 18:19:51.743  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 18:19:51.743  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-16 18:19:51.753  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:51.753  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:51.753  9948 10012 D BluetoothLeScanner: Stop Scan
,09-16 18:19:51.763  5043  5446 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 18:19:51.763  5043  5446 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 18:19:51.763  5043  5446 D BtGatt.GattService: stopScan() - queue size =1
09-16 18:19:51.763  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:51.763  5043  5235 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-16 18:19:51.763  5043  5235 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
09-16 18:19:51.763  5043  5235 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 18:19:51.763  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 5 => 5
,09-16 18:19:51.763  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 5 => 5
09-16 18:19:51.763  5043  5235 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-16 18:19:51.773  5043  5235 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-16 18:19:51.773  5043  5224 D BtGatt.ScanManager: filter size is 1
09-16 18:19:51.773  5043  5059 D BtGatt.GattService: unregisterClient() - clientIf=7
09-16 18:19:51.773  5043  5224 D BtGatt.ScanManager: delete FilterIndex - 3
,09-16 18:19:51.773  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 18:19:51.773  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-16 18:19:51.773  3426  4844 V AlarmManager:  remove PendingIntent] PendingIntent{680b1b0: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
09-16 18:19:51.773  5043  5194 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-16 18:19:51.773  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 18:19:51.773  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 18:19:51.773  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-16 18:19:51.773  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 18:19:51.773  5043  5224 D BtGatt.ScanManager: stopping BLe Batch
09-16 18:19:51.773  5043  5194 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
,09-16 18:19:51.773  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:51.773  5043  5224 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-16 18:19:51.783  9948 10012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 18:19:51.783  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:51.783  5043  5194 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=5
09-16 18:19:51.783  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:51.793  3426  4422 V AlarmManager:  remove PendingIntent] PendingIntent{90f7829: PendingIntentRecord{4c50d9e com.android.bluetooth broadcastIntent}}
09-16 18:19:51.783  5043  5194 D BtGatt.GattService: current time is 230219808757
09-16 18:19:51.793  5043  5194 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -82, 5, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -69, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -86, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -75, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -79, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 18:19:51.793  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-16 18:19:51.793  3426  3977 V AlarmManager:  remove PendingIntent] PendingIntent{ae8d7ae: PendingIntentRecord{4c50d9e com.android.bluetooth broadcastIntent}}
09-16 18:19:51.793  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:51.793  5043  5194 D ScanRecord: first manudata for manu ID
,09-16 18:19:51.793  9948 10012 D BluetoothAdapter: STATE_ON
09-16 18:19:51.793  9948 10012 D BluetoothLeAdvertiser: stop advertising
09-16 18:19:51.793  9948 10012 D BluetoothLeAdvertiser: wrapper is null
09-16 18:19:51.793  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 18:19:51.793  9948 10012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 18:19:51.793  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 18:19:51.793  3426  4184 V AlarmManager:  remove PendingIntent] PendingIntent{56f094f: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.793  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-16 18:19:51.793  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:51.793  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:51.793  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-16 18:19:51.793  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:51.793  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:51.793  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 18:19:51.793  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-16 18:19:51.793  5043  5194 D ScanRecord: parseFromBytes
,09-16 18:19:51.793  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:51.793  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 18:19:51.793  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:51.793  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:51.793  9948  9948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 18:19:51.793  9948 10012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 18:19:51.793  9948 10012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 18:19:51.793  9948  9948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 18:19:51.793  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 18:19:51.793  9948  9948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 18:19:51.793  9948 10012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c5401e not in the list
09-16 18:19:51.793  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 18:19:51.793  9948 10012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab9a0ff not in the list
09-16 18:19:51.793  9948 10012 D io.jxcore.node.ConnectivityMonitor: stop
09-16 18:19:51.793  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 18:19:51.803  3426  4394 V AlarmManager:  remove PendingIntent] PendingIntent{73738dc: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.803  3426  4476 V AlarmManager:  remove PendingIntent] PendingIntent{bfe6de5: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.813  3426  3474 V AlarmManager:  remove PendingIntent] PendingIntent{4eec0ba: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.813  3426  4173 V AlarmManager:  remove PendingIntent] PendingIntent{23ceb6b: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.823  3426  4060 V AlarmManager:  remove PendingIntent] PendingIntent{36d06c8: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.823  3426  4863 V AlarmManager:  remove PendingIntent] PendingIntent{42d0361: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.833  3426  4605 V AlarmManager:  remove PendingIntent] PendingIntent{c382e86: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.843  3426  3473 V AlarmManager:  remove PendingIntent] PendingIntent{3bcd347: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.843  3426  3983 V AlarmManager:  remove PendingIntent] PendingIntent{fafc774: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.853  3426  4184 V AlarmManager:  remove PendingIntent] PendingIntent{455749d: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.853  3426  4844 V AlarmManager:  remove PendingIntent] PendingIntent{58ad12: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.863  3426  3856 V AlarmManager:  remove PendingIntent] PendingIntent{8695ce3: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.863  3426  4422 V AlarmManager:  remove PendingIntent] PendingIntent{9bbe6e0: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:51.943  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:52.123  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:52.303  9948  9948 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 18:19:52.303  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:52.483  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:52.663  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:52.843  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:53.023  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:53.203  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:53.283  3426  6483 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-16 18:19:53.383  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:53.563  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:53.743  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:53.923  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:54.103  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:54.283  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:54.463  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:54.643  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:54.823  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:55.003  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:55.183  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:55.323  3426  6444 D SSRM:n  : SIOP:: AP = 330, PST = 315 (W:14), CP = 273, CUR = 148, LCD = 1
,09-16 18:19:55.363  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:55.543  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:55.723  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:55.903  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:56.083  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:56.263  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:56.453  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:56.623  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:56.803  9948 10012 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-16 18:19:56.803  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:56.803  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 18:19:56.823  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.833  9948 10012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 18:19:56.833  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 18:19:56.833  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 18:19:56.833  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 18:19:56.833  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 18:19:56.833  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 18:19:56.833  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 18:19:56.833  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 18:19:56.833  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.843  9948 10012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 18:19:56.843  9948 10012 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 18:19:56.843  9948 10012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 18:19:56.843  9948 10012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 18:19:56.843  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 18:19:56.843  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 18:19:56.843  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 18:19:56.853  9948 10012 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 18:19:56.853  9948 10012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 18:19:56.863  9948  9948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 18:19:56.863  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.863  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.873  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.873  9948  9948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 18:19:56.873  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 18:19:56.883  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.883  9948 10012 D BluetoothAdapter: STATE_ON
09-16 18:19:56.883  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 18:19:56.883  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 18:19:56.893  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.893  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.893  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.903  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.903  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 18:19:56.903  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 18:19:56.903  9948 10012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 18:19:56.903  9948 10012 D BluetoothLeScanner: Start Scan
,09-16 18:19:56.903  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.903  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.913  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.913  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:56.923  5043  5061 D BtGatt.GattService: registerClient() - UUID=ce79e6c4-6600-4ccb-a295-0da6c53e0107
,09-16 18:19:56.963  5043  5194 D BtGatt.GattService: onClientRegistered() - UUID=ce79e6c4-6600-4ccb-a295-0da6c53e0107, clientIf=7
,09-16 18:19:56.963  9948  9959 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-16 18:19:56.963  5043  5446 D BtGatt.GattService: start scan with filters
,09-16 18:19:56.973  5043  5446 D BtGatt.GattService: getScanSettings
,09-16 18:19:56.973  5043  5446 D BtGatt.GattService: Is it foreground application = true
09-16 18:19:56.973  5043  5446 D BtGatt.GattService: not a background application
,09-16 18:19:56.983  5043  5446 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-16 18:19:56.983  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:56.983  5043  5446 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 18:19:56.983  5043  5446 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 18:19:56.983  5043  5235 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-16 18:19:56.983  5043  5235 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
09-16 18:19:56.993  5043  5224 D BtGatt.ScanManager: handling starting scan
09-16 18:19:56.993  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 18:19:56.993  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 18:19:56.993  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 18:19:56.993  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 18:19:56.993  5043  5224 D BluetoothAdapter: STATE_ON
09-16 18:19:56.993  5043  5224 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.003  3426  4846 V AlarmManager:  remove PendingIntent] PendingIntent{793855b: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.003  5043  5235 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 95
,09-16 18:19:57.003  9948 10012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 18:19:57.003  5043  5235 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-16 18:19:57.003  9948 10012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-16 18:19:57.003  9948  9948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 18:19:57.003  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 18:19:57.003  5043  5194 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-16 18:19:57.003  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 18:19:57.013  5043  5224 D BtGatt.ScanManager: set filter index= 4 for clientIf= 7
09-16 18:19:57.013  5043  5224 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-16 18:19:57.013  5043  5224 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-16 18:19:57.013  5043  5224 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-16 18:19:57.013  5043  5194 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-16 18:19:57.013  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:57.013  9948 10012 I io.jxcore.node.ConnectionHelper: start: OK
09-16 18:19:57.013  5043  5224 D BtGatt.ScanManager: Starting BLE batch scan
09-16 18:19:57.013  5043  5224 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-16 18:19:57.013  5043  5235 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 15
09-16 18:19:57.013  5043  5235 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24567379
09-16 18:19:57.013  5043  5235 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-16 18:19:57.013  9948 10012 D BluetoothAdapter: STATE_ON
09-16 18:19:57.013  3426  3474 V AlarmManager:  remove PendingIntent] PendingIntent{bd3b1f8: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.013  5043  5235 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 18:19:57.013  5043  5194 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,09-16 18:19:57.013  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:57.013  5043  5235 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 18:19:57.023  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 5 => 5
,09-16 18:19:57.023  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 5 => 5
09-16 18:19:57.023  5043  5235 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 18:19:57.023  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 5 => 5
09-16 18:19:57.023  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 5 => 5
09-16 18:19:57.023  5043  5235 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 18:19:57.023  5043  5235 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-16 18:19:57.023  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 5 => 5
09-16 18:19:57.023  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 5 => 5
09-16 18:19:57.023  5043  5235 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24567379
09-16 18:19:57.023  5043  5194 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-16 18:19:57.023  3426  4846 V AlarmManager:  remove PendingIntent] PendingIntent{72c86d1: PendingIntentRecord{4c50d9e com.android.bluetooth broadcastIntent}}
09-16 18:19:57.023  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:57.023  9948 10012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 18:19:57.023  9948 10012 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 18:19:57.023  9948 10012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 18:19:57.023  9948 10012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 18:19:57.023  9948 10012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 18:19:57.023  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 18:19:57.023  9948 10012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 18:19:57.023  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 18:19:57.023  9948 10012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 18:19:57.023  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 18:19:57.023  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 18:19:57.023  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 18:19:57.023  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.023  9948 10012 D BluetoothAdapter: STATE_ON
09-16 18:19:57.023  9948 10012 D BluetoothLeScanner: Stop Scan
,09-16 18:19:57.033  3426  4173 V AlarmManager:  remove PendingIntent] PendingIntent{5af4536: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.033  5043  5512 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 18:19:57.033  5043  5512 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 18:19:57.033  5043  5512 D BtGatt.GattService: stopScan() - queue size =1
09-16 18:19:57.033  5043  5235 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-16 18:19:57.033  5043  5235 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
09-16 18:19:57.033  5043  5235 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 18:19:57.033  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 5 => 5
09-16 18:19:57.033  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 5 => 5
09-16 18:19:57.033  5043  5235 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-16 18:19:57.033  5043  5235 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-16 18:19:57.033  5043  5446 D BtGatt.GattService: unregisterClient() - clientIf=7
09-16 18:19:57.033  5043  5224 D BtGatt.ScanManager: filter size is 1
09-16 18:19:57.033  5043  5224 D BtGatt.ScanManager: delete FilterIndex - 4
09-16 18:19:57.043  5043  5194 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-16 18:19:57.043  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:57.043  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 18:19:57.043  3426  4422 V AlarmManager:  remove PendingIntent] PendingIntent{7b1c37: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
09-16 18:19:57.043  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 18:19:57.043  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 18:19:57.043  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 18:19:57.043  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 18:19:57.043  5043  5224 D BtGatt.ScanManager: stopping BLe Batch
,09-16 18:19:57.043  9948 10012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 18:19:57.043  5043  5194 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
,09-16 18:19:57.043  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:57.043  5043  5224 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-16 18:19:57.043  9948 10012 D BluetoothAdapter: STATE_ON
09-16 18:19:57.043  5043  5194 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-16 18:19:57.043  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 18:19:57.043  9948 10012 D BluetoothAdapter: STATE_ON
09-16 18:19:57.043  3426  3473 V AlarmManager:  remove PendingIntent] PendingIntent{8df5a4: PendingIntentRecord{4c50d9e com.android.bluetooth broadcastIntent}}
09-16 18:19:57.043  9948 10012 D BluetoothLeAdvertiser: stop advertising
09-16 18:19:57.043  9948 10012 D BluetoothLeAdvertiser: wrapper is null
09-16 18:19:57.043  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 18:19:57.043  9948 10012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 18:19:57.043  3426  4476 V AlarmManager:  remove PendingIntent] PendingIntent{e21bf0d: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
09-16 18:19:57.043  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 18:19:57.043  3426  4173 V AlarmManager:  remove PendingIntent] PendingIntent{da27ec2: PendingIntentRecord{4c50d9e com.android.bluetooth broadcastIntent}}
09-16 18:19:57.043  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 18:19:57.053  9948  9948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 18:19:57.053  9948 10012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 18:19:57.053  9948 10012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 18:19:57.053  9948  9948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 18:19:57.053  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 18:19:57.053  9948  9948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 18:19:57.053  9948 10012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c5401e not in the list
09-16 18:19:57.053  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 18:19:57.053  9948 10012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab9a0ff not in the list
,09-16 18:19:57.053  9948 10012 D io.jxcore.node.ConnectivityMonitor: stop
09-16 18:19:57.053  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 18:19:57.053  9948 10012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 18:19:57.053  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 18:19:57.053  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 18:19:57.053  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 18:19:57.053  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 18:19:57.053  9948 10012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab9a0ff not in the list
09-16 18:19:57.053  9948 10012 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 18:19:57.053  3426  4846 V AlarmManager:  remove PendingIntent] PendingIntent{cdb44d3: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.053  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 18:19:57.063  3426  4476 V AlarmManager:  remove PendingIntent] PendingIntent{f0b5b2f: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.063  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.063  3426  3977 V AlarmManager:  remove PendingIntent] PendingIntent{2f8553c: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.063  9948 10012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 18:19:57.063  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 18:19:57.063  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 18:19:57.063  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 18:19:57.063  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 18:19:57.063  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 18:19:57.063  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 18:19:57.063  9948 10012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 18:19:57.063  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.073  3426  4476 V AlarmManager:  remove PendingIntent] PendingIntent{61cc2c5: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.073  9948 10012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 18:19:57.073  9948 10012 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 18:19:57.073  9948 10012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 18:19:57.073  9948 10012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 18:19:57.073  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 18:19:57.073  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 18:19:57.073  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 18:19:57.073  3426  4422 V AlarmManager:  remove PendingIntent] PendingIntent{98bc641: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.073  9948 10012 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 18:19:57.073  9948 10012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 18:19:57.083  9948  9948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 18:19:57.083  3426  4173 V AlarmManager:  remove PendingIntent] PendingIntent{e3167e6: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.083  9948 10012 D BluetoothAdapter: STATE_ON
09-16 18:19:57.083  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.083  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.083  9948  9948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 18:19:57.083  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 18:19:57.083  3426  4060 V AlarmManager:  remove PendingIntent] PendingIntent{a958127: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
09-16 18:19:57.093  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.093  9948 10012 D BluetoothAdapter: STATE_ON
09-16 18:19:57.093  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 18:19:57.093  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 18:19:57.093  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.093  3426  4394 V AlarmManager:  remove PendingIntent] PendingIntent{a2c0fd4: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
09-16 18:19:57.093  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.093  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.093  3426  4844 V AlarmManager:  remove PendingIntent] PendingIntent{38d857d: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
09-16 18:19:57.093  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.103  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 18:19:57.103  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 18:19:57.103  9948 10012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 18:19:57.103  9948 10012 D BluetoothLeScanner: Start Scan
,09-16 18:19:57.103  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.103  9948 10012 D BluetoothAdapter: STATE_ON
09-16 18:19:57.103  3426  4605 V AlarmManager:  remove PendingIntent] PendingIntent{d9c1c72: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.103  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.103  9948 10012 D BluetoothAdapter: STATE_ON
,09-16 18:19:57.103  3426  4060 V AlarmManager:  remove PendingIntent] PendingIntent{e4f08c3: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.103  5043  5446 D BtGatt.GattService: registerClient() - UUID=59e13c9d-4e18-46c9-ac15-922df66d0790
,09-16 18:19:57.113  3426  4846 V AlarmManager:  remove PendingIntent] PendingIntent{6245540: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.113  3426  4173 V AlarmManager:  remove PendingIntent] PendingIntent{ef1fc79: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.123  3426  3856 V AlarmManager:  remove PendingIntent] PendingIntent{68b8dbe: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.123  3426  3983 V AlarmManager:  remove PendingIntent] PendingIntent{d8f6e1f: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.123  3426  4060 V AlarmManager:  remove PendingIntent] PendingIntent{499856c: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.133  3426  4201 V AlarmManager:  remove PendingIntent] PendingIntent{98ce735: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.133  3426  4394 V AlarmManager:  remove PendingIntent] PendingIntent{76ec7ca: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.153  5043  5194 D BtGatt.GattService: onClientRegistered() - UUID=59e13c9d-4e18-46c9-ac15-922df66d0790, clientIf=7
,09-16 18:19:57.153  9948  9958 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-16 18:19:57.153  5043  5061 D BtGatt.GattService: start scan with filters
,09-16 18:19:57.153  5043  5061 D BtGatt.GattService: getScanSettings
,09-16 18:19:57.153  5043  5061 D BtGatt.GattService: Is it foreground application = true
09-16 18:19:57.153  5043  5061 D BtGatt.GattService: not a background application
,09-16 18:19:57.153  5043  5061 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-16 18:19:57.163  5043  5061 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 18:19:57.163  5043  5061 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 18:19:57.163  5043  5235 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
,09-16 18:19:57.163  5043  5235 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
09-16 18:19:57.163  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 18:19:57.163  9948 10012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 18:19:57.163  9948 10012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 18:19:57.163  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 18:19:57.163  5043  5224 D BtGatt.ScanManager: handling starting scan
09-16 18:19:57.163  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:57.163  5043  5224 D BluetoothAdapter: STATE_ON
09-16 18:19:57.163  5043  5224 D BluetoothAdapter: STATE_ON
09-16 18:19:57.163  3426  4476 V AlarmManager:  remove PendingIntent] PendingIntent{b46cd3b: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.163  5043  5194 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-16 18:19:57.163  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:57.163  5043  5224 D BtGatt.ScanManager: set filter index= 5 for clientIf= 7
09-16 18:19:57.163  5043  5224 D BtGatt.ScanManager: High Rssi Filter value is = -128
,09-16 18:19:57.163  5043  5224 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-16 18:19:57.163  5043  5224 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-16 18:19:57.173  5043  5235 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 96
09-16 18:19:57.173  5043  5235 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-16 18:19:57.173  9948 10012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 18:19:57.173  9948 10012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 18:19:57.173  5043  5194 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-16 18:19:57.173  9948  9948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 18:19:57.173  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:57.173  5043  5224 D BtGatt.ScanManager: Starting BLE batch scan
09-16 18:19:57.173  5043  5224 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-16 18:19:57.173  3426  3474 V AlarmManager:  remove PendingIntent] PendingIntent{64f8c58: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.173  9948 10012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 18:19:57.173  5043  5235 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 16
,09-16 18:19:57.173  5043  5235 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24567379
09-16 18:19:57.173  5043  5235 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-16 18:19:57.173  5043  5235 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 18:19:57.183  3426  4060 V AlarmManager:  remove PendingIntent] PendingIntent{b1c1b1: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.173  5043  5235 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 18:19:57.173  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 5 => 5
09-16 18:19:57.173  5043  5194 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-16 18:19:57.173  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:57.183  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 5 => 5
09-16 18:19:57.183  5043  5235 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 18:19:57.183  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 5 => 5
09-16 18:19:57.183  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 5 => 5
,09-16 18:19:57.183  5043  5235 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 18:19:57.183  5043  5235 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 18:19:57.183  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 5 => 5
09-16 18:19:57.183  5043  5235 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 5 => 5
09-16 18:19:57.183  3426  4844 V AlarmManager:  remove PendingIntent] PendingIntent{4999696: PendingIntentRecord{4c50d9e com.android.bluetooth broadcastIntent}}
09-16 18:19:57.183  5043  5235 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24567379
09-16 18:19:57.183  9948 10012 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 18:19:57.183  5043  5194 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-16 18:19:57.183  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 18:19:57.183  3426  4394 V AlarmManager:  remove PendingIntent] PendingIntent{f4b0217: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.183  3426  4476 V AlarmManager:  remove PendingIntent] PendingIntent{25d1604: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.193  3426  3474 V AlarmManager:  remove PendingIntent] PendingIntent{96fc7ed: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.193  3426  4863 V AlarmManager:  remove PendingIntent] PendingIntent{1d08622: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.203  3426  4422 V AlarmManager:  remove PendingIntent] PendingIntent{ef3a8b3: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.203  3426  4846 V AlarmManager:  remove PendingIntent] PendingIntent{8978e70: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.203  3426  4173 V AlarmManager:  remove PendingIntent] PendingIntent{8df5e9: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.213  3426  3856 V AlarmManager:  remove PendingIntent] PendingIntent{894e26e: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.213  3426  3977 V AlarmManager:  remove PendingIntent] PendingIntent{3761d0f: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.213  3426  4060 V AlarmManager:  remove PendingIntent] PendingIntent{ebf219c: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.223  3426  4201 V AlarmManager:  remove PendingIntent] PendingIntent{e4707a5: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:57.343  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:57.523  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:57.673  9948  9948 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 18:19:57.673  9948  9948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 18:19:57.673  9948  9948 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 18:19:57.713  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:57.893  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:58.063  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:58.183  3426  3818 V AlarmManager: Expired Alarm result :4
,09-16 18:19:58.183  5043  5043 D BtGatt.ScanManager: awakened up at time 236618
,09-16 18:19:58.193  5043  5224 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-16 18:19:58.193  3426  4605 V AlarmManager:  remove PendingIntent] PendingIntent{a017b2b: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:58.203  5043  5194 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=8
,09-16 18:19:58.203  5043  5194 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 18:19:58.203  5043  5194 D BtGatt.GattService: current time is 236633920906
09-16 18:19:58.203  5043  5194 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -79, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, 4, -83, 1, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 50, -35, 86, -77, -92, -11, 1, 0, -97, 10, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 31, 50, 5, 3, 2, -33, 21, 61, 59, 71, -27, 28, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, -46, -4, -117, 6, 105, -37, 1, -128, -75, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -85, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -73, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -79, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 18:19:58.203  3426  3474 V AlarmManager:  remove PendingIntent] PendingIntent{46abb88: PendingIntentRecord{4c50d9e com.android.bluetooth broadcastIntent}}
,09-16 18:19:58.203  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-16 18:19:58.203  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:58.203  5043  5194 D ScanRecord: first manudata for manu ID
,09-16 18:19:58.203  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-16 18:19:58.203  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:58.203  5043  5194 D ScanRecord: first manudata for manu ID
,09-16 18:19:58.213  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 31, 50, 5, 3, 2, -33, 21, 61, 59, 71, -27, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
09-16 18:19:58.213  5043  5194 D ScanRecord: parseFromBytes
,09-16 18:19:58.213  5043  5194 D ScanRecord: first manudata for manu ID
,09-16 18:19:58.213  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-16 18:19:58.213  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:58.213  5043  5194 D ScanRecord: first manudata for manu ID
,09-16 18:19:58.213  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-16 18:19:58.213  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:58.213  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:58.213  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-16 18:19:58.213  5043  5194 D ScanRecord: parseFromBytes
09-16 18:19:58.213  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:58.213  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-16 18:19:58.213  5043  5194 D ScanRecord: parseFromBytes
,09-16 18:19:58.213  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:58.213  5043  5194 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 18:19:58.213  5043  5194 D ScanRecord: parseFromBytes
,09-16 18:19:58.213  5043  5194 D ScanRecord: first manudata for manu ID
09-16 18:19:58.213  9948  9959 D ScanRecord: parseFromBytes
09-16 18:19:58.213  9948  9959 D ScanRecord: first manudata for manu ID
,09-16 18:19:58.223  9948  9959 D ScanRecord: parseFromBytes
09-16 18:19:58.223  9948  9959 D ScanRecord: first manudata for manu ID
09-16 18:19:58.223  9948  9959 D ScanRecord: parseFromBytes
09-16 18:19:58.223  9948  9959 D ScanRecord: first manudata for manu ID
09-16 18:19:58.223  9948  9959 D ScanRecord: parseFromBytes
,09-16 18:19:58.223  9948  9959 D ScanRecord: first manudata for manu ID
09-16 18:19:58.223  9948  9959 D ScanRecord: parseFromBytes
09-16 18:19:58.223  9948  9959 D ScanRecord: first manudata for manu ID
,09-16 18:19:58.223  9948  9959 D ScanRecord: parseFromBytes
09-16 18:19:58.223  9948  9959 D ScanRecord: first manudata for manu ID
09-16 18:19:58.223  9948  9959 D ScanRecord: parseFromBytes
09-16 18:19:58.223  9948  9959 D ScanRecord: first manudata for manu ID
09-16 18:19:58.223  9948  9959 D ScanRecord: parseFromBytes
09-16 18:19:58.223  9948  9959 D ScanRecord: first manudata for manu ID
,09-16 18:19:58.223  3426  3983 V AlarmManager:  remove PendingIntent] PendingIntent{9c57921: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:58.233  3426  4201 V AlarmManager:  remove PendingIntent] PendingIntent{482d146: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:58.233  3426  4476 V AlarmManager:  remove PendingIntent] PendingIntent{99a9f07: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:58.243  3426  3474 V AlarmManager:  remove PendingIntent] PendingIntent{9b40834: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
09-16 18:19:58.243  3426  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 18:19:58.243  3426  4184 V AlarmManager:  remove PendingIntent] PendingIntent{85f865d: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:58.253  3426  3983 V AlarmManager:  remove PendingIntent] PendingIntent{48abbd2: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:58.253  3426  4844 V AlarmManager:  remove PendingIntent] PendingIntent{ab824a3: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:58.263  3426  4394 V AlarmManager:  remove PendingIntent] PendingIntent{4a373a0: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:58.263  3426  4605 V AlarmManager:  remove PendingIntent] PendingIntent{4932b59: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}
,09-16 18:19:58.263  3426  3856 V AlarmManager:  remove PendingIntent] PendingIntent{9b4c31e: PendingIntentRecord{7d38bf8 com.android.bluetooth broadcastIntent}}

```
