#### Test 8559402588149d6_thali04_samsung-SM-G935F Logs


```
--------- beginning of main
,09-19 16:10:46.322  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:46.502  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:46.682  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:46.802  9885  9885 I FIPS_bssl: FIPS approved mode (1) | 9885 | app_process
09-19 16:10:46.812  9885  9885 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-19 16:10:46.812  9885  9885 D AndroidRuntime: CheckJNI is OFF
09-19 16:10:46.812  9885  9885 D AndroidRuntime: readGMSProperty: start
09-19 16:10:46.812  9885  9885 D AndroidRuntime: readGMSProperty: already setted!!
09-19 16:10:46.812  9885  9885 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-19 16:10:46.812  9885  9885 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-19 16:10:46.812  9885  9885 D AndroidRuntime: readGMSProperty: end
09-19 16:10:46.812  9885  9885 D AndroidRuntime: addProductProperty: start
09-19 16:10:46.832  9885  9885 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-19 16:10:46.852  9885  9885 I Radio-JNI: register_android_hardware_Radio DONE
09-19 16:10:46.862  9885  9885 E AffinityControl: AffinityControl: registerfunction enter
09-19 16:10:46.862  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:46.862  9885  9885 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-19 16:10:46.892  3407  3983 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-19 16:10:46.892  3407  3983 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-19 16:10:46.922  3407  3983 D ResourcesManager: For user 0 new overlays fetched Null
09-19 16:10:46.922  3407  3983 D GameManagerService: identifyGamePackage. com.test.thalitest
09-19 16:10:46.922  3407  3983 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-19 16:10:46.932  3407  3983 D ActivityManager: mDVFSHelper.acquire()
09-19 16:10:46.932  3407  3983 V WindowManager: addAppToken: AppWindowToken{d0b9be9a8 token=Token{ae00dcb ActivityRecord{539709a u0 com.test.thalitest/.MainActivity t75}}} to stack=2 task=75 at 0
09-19 16:10:46.942  3407  3551 I InjectionManager: Inside getClassLibPath caller 
09-19 16:10:46.952  3407  3551 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-19 16:10:46.952  3407  3551 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ac845c0 V.E...... R.....ID 0,0-0,0}
09-19 16:10:46.962  9894  9894 E Zygote  : v2
09-19 16:10:46.962  9894  9894 I libpersona: KNOX_SDCARD checking this for 10177
09-19 16:10:46.962  9894  9894 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-19 16:10:46.962  9894  9894 I libpersona: KNOX_SDCARD not a persona
09-19 16:10:46.962  3407  3983 I ActivityManager: Start proc 9894:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-19 16:10:46.962  3407  3551 W WindowManager: Failed looking up window
09-19 16:10:46.962  3407  3551 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@f0662f9 does not exist
09-19 16:10:46.962  3407  3551 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 16:10:46.962  3407  3551 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-19 16:10:46.962  3407  3551 D ISSUE_DEBUG: InputChannelName : d76323e Starting com.test.thalitest
09-19 16:10:46.962  9894  9894 E Zygote  : accessInfo : 0
09-19 16:10:46.962  9894  9894 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-19 16:10:46.972  3407  3983 D InputDispatcher: Focused application set to: xxxx
09-19 16:10:46.972  9885  9885 D AndroidRuntime: Shutting down VM
09-19 16:10:46.972  3407  3858 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-19 16:10:46.972  3007  3007 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-19 16:10:46.992  6529  6529 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-19 16:10:47.002  9894  9894 D TimaKeyStoreProvider: TimaSignature is unavailable
09-19 16:10:47.002  9894  9894 D ActivityThread: Added TimaKeyStore provider
09-19 16:10:47.002  3407  4849 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3407
09-19 16:10:47.002  3407  4849 I libsuspend: !@autosuspend_wakeup_count_disable
09-19 16:10:47.002  3407  4849 D PowerManagerService: mDisplayReady: false
09-19 16:10:47.002  3407  4849 I libsuspend: !@autosuspend_wakeup_count_disable done
09-19 16:10:47.002  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 16:10:47.002  3407  3551 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-19 16:10:47.002  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 16:10:47.002  6529  6529 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-19 16:10:47.002  3407  4849 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-19 16:10:47.002  3407  3551 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-19 16:10:47.002  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:10:47.002  3407  3407 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-19 16:10:47.002  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:10:47.002  3407  3569 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-19 16:10:47.002  3407  3551 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-19 16:10:47.002  3407  3551 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-19 16:10:47.012  3007  3007 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fabec3c00
09-19 16:10:47.012  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-19 16:10:47.012  3407  4851 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3407
09-19 16:10:47.022  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 16:10:47.022  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 16:10:47.022  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:10:47.022  3407  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-19 16:10:47.022  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:10:47.022  3407  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
09-19 16:10:47.022  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 16:10:47.022  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 16:10:47.022  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:10:47.022  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:10:47.022  3407  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-19 16:10:47.022  3407  3556 D PowerManagerService: mDisplayReady: true
09-19 16:10:47.022  3407  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-19 16:10:47.032  6196  6196 E CocktailBarPositionManager: Window direction: 0
09-19 16:10:47.032  6196  6196 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-19 16:10:47.032  3407  3407 I KnoxTimeoutHandler: SD activityfalse
09-19 16:10:47.032  3407  4848 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3407
09-19 16:10:47.042  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:47.042  3407  3977 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3407
09-19 16:10:47.052  3407  4459 V WindowStateAnimator: Finishing drawing window Window{62ff0c9 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-19 16:10:47.062  3407  4196 D ActivityManager:  Launching com.test.thalitest, updated priority
09-19 16:10:47.072  3407  3551 V WindowStateAnimator: Finishing drawing window Window{d76323e u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-19 16:10:47.072  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fe7579638
09-19 16:10:47.082  6196  7066 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-19 16:10:47.082  3007  3017 D libEGL  : eglTerminate EGLDisplay = 0x7fab9bee78
09-19 16:10:47.082  3007  3017 D libEGL  : eglTerminate EGLDisplay = 0x7fab9bee78
09-19 16:10:47.092  3407  3407 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-19 16:10:47.092  3407  3983 V WindowStateAnimator: Finishing drawing window Window{2c5b093 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-19 16:10:47.092  6529  6529 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-19 16:10:47.092  6529  6529 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-19 16:10:47.092  3007  4348 I SurfaceFlinger: id=10 Removed MauncherAct (4/13)
09-19 16:10:47.092  6529  6529 V ActivityThread: updateVisibility : ActivityRecord{db594f5 token=android.os.BinderProxy@453ad4f {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-19 16:10:47.092  3007  3658 I SurfaceFlinger: id=10 Removed MauncherAct (-2/13)
09-19 16:10:47.102  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fe7579758
09-19 16:10:47.112  3007  3658 I SurfaceFlinger: id=18 Removed VSBConnecti (7/12)
09-19 16:10:47.112  3007  4517 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/12)
09-19 16:10:47.112  4312  4312 V ActivityThread: updateVisibility : ActivityRecord{93b9748 token=android.os.BinderProxy@bdb6286 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-19 16:10:47.112  4312  4312 D Launcher: onTrimMemory. Level: 20
09-19 16:10:47.122  3007  3017 D libEGL  : eglTerminate EGLDisplay = 0x7fab9bee78
09-19 16:10:47.122  3007  4517 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
09-19 16:10:47.122  3007  3015 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
09-19 16:10:47.142  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fe7579758
09-19 16:10:47.142  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fe7579758
09-19 16:10:47.192  3407  3407 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3407 (0x0)
09-19 16:10:47.192  3407  3407 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3407 (0x0)
09-19 16:10:47.192  3407  3407 I libsuspend: !@autosuspend_wakeup_count_disable
09-19 16:10:47.192  3407  3407 D PowerManagerService: mDisplayReady: false
09-19 16:10:47.192  3407  3407 I libsuspend: !@autosuspend_wakeup_count_disable done
09-19 16:10:47.192  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-19 16:10:47.192  3407  3407 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,09-19 16:10:47.192  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 16:10:47.192  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:10:47.202  3007  3007 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fabec3c00
09-19 16:10:47.192  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:10:47.202  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-19 16:10:47.192  3407  3569 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-19 16:10:47.202  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-19 16:10:47.202  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 16:10:47.202  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:10:47.202  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:10:47.202  3407  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-19 16:10:47.202  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-19 16:10:47.202  3407  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
09-19 16:10:47.202  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 16:10:47.202  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:10:47.202  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:10:47.202  3407  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-19 16:10:47.202  3407  3556 D PowerManagerService: mDisplayReady: true
09-19 16:10:47.202  3407  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-19 16:10:47.222  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:47.382  6196  6196 I TrayVisibilityController: handleMessage : msg.what = 1
09-19 16:10:47.402  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:47.422  3407  4196 I WindowManager: Screenshot max retries 4 of Token{ae00dcb ActivityRecord{539709a u0 com.test.thalitest/.MainActivity t75}} appWin=Window{d76323e u0 d0 Starting com.test.thalitest} drawState=4
09-19 16:10:47.422  6196  6207 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-19 16:10:47.422  3407  3551 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-19 16:10:47.422  3407  3516 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-19 16:10:47.432  3407  3407 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-19 16:10:47.432  3407  3551 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a3db815 u0 com.samsung.android.MtpApplication/.USBConnection t74} time:226433
09-19 16:10:47.432  3407  3551 D ActivityManager: mDVFSHelper.release()
09-19 16:10:47.432  6196  6196 I Utils   : isCurrentUser current = 0, ownerId = 0
09-19 16:10:47.432  3407  3551 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-19 16:10:47.432  6196  6196 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-19 16:10:47.432  3407  3551 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-19 16:10:47.432  6196  6196 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-19 16:10:47.442  3407  3858 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-19 16:10:47.442  3407  6445 D GameManagerService: identifyGamePackage. com.test.thalitest
09-19 16:10:47.442  3407  6445 D GameManagerService: identifyGamePackage. com.test.thalitest
09-19 16:10:47.452  3407  3407 I KnoxTimeoutHandler: SD activityfalse
09-19 16:10:47.482  6196  6196 E CocktailBarPositionManager: Window direction: 0
09-19 16:10:47.482  6196  6196 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-19 16:10:47.492  9894  9894 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-19 16:10:47.492  9894  9894 D RelationGraph: garbageCollect()
09-19 16:10:47.492  9894  9894 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-19 16:10:47.492  3407  4458 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-19 16:10:47.492  9894  9894 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-19 16:10:47.502  3407  6445 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-19 16:10:47.502  3407  6445 D GameManagerService: identifyGamePackage. com.test.thalitest
09-19 16:10:47.512  9894  9894 D ResourcesManager: For user 0 new overlays fetched Null
09-19 16:10:47.512  3407  6445 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-19 16:10:47.512  3407  6445 D GameManagerService: identifyGamePackage. com.test.thalitest
09-19 16:10:47.512  3407  6445 D GameManagerService: identifyGamePackage. com.test.thalitest
09-19 16:10:47.512  9894  9894 I InjectionManager: Inside getClassLibPath caller 
09-19 16:10:47.522  9894  9894 D InjectionManager: InjectionManager
09-19 16:10:47.522  9894  9894 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-19 16:10:47.532  9894  9894 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-19 16:10:47.532  9894  9894 I InjectionManager: featureStore :{}
09-19 16:10:47.532  9894  9894 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-19 16:10:47.532  9894  9894 D RelationGraph: garbageCollect()
09-19 16:10:47.532  9894  9894 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-19 16:10:47.562  9894  9894 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-19 16:10:47.582  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:47.602  9894  9894 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-19 16:10:47.602  9894  9894 D ResourcesManager: For user 0 new overlays fetched Null
09-19 16:10:47.602  9894  9894 I InjectionManager: Inside getClassLibPath caller 
09-19 16:10:47.612  9894  9894 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-19 16:10:47.672  9894  9894 I cr_LibraryLoader: Time to load native libraries: 32 ms (timestamps 6640-6672)
09-19 16:10:47.672  9894  9894 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-19 16:10:47.682  3407  3881 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-19 16:10:47.732  9894  9910 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-19 16:10:47.752  9894  9894 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {41c9d90}
09-19 16:10:47.752  9894  9894 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-19 16:10:47.762  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:47.772  9894  9894 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-19 16:10:47.782  3407  3881 I MdnieScenarioControlService: mGameModeLauncher : false
09-19 16:10:47.782  3407  3881 I MdnieScenarioControlService: setUIMode
09-19 16:10:47.822  9894  9894 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-19 16:10:47.922  3407  3516 W ActivityManager: Activity pause timeout for ActivityRecord{539709a u0 com.test.thalitest/.MainActivity t75}
09-19 16:10:47.942  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:48.032  9894  9894 D libEGL  : eglInitialize EGLDisplay = 0xff91c74c
09-19 16:10:48.122  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:48.132  3407  4459 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
09-19 16:10:48.132  3407  4459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-19 16:10:48.222  9894  9894 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-19 16:10:48.232  9894  9894 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-19 16:10:48.242  9894  9894 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-19 16:10:48.272  9894  9894 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-19 16:10:48.302  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:48.332  9894  9894 D Activity: performCreate Call Injection manager
09-19 16:10:48.342  9894  9894 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
09-19 16:10:48.352  9894  9894 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-19 16:10:48.362  9894  9894 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{69f33ee I.E...... R.....ID 0,0-0,0}
09-19 16:10:48.372  9894  9947 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-19 16:10:48.382  3407  4459 W WindowManager: Failed looking up window
09-19 16:10:48.382  3407  4459 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@1dcd1d9 does not exist
09-19 16:10:48.382  3407  4459 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-19 16:10:48.382  3407  4459 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-19 16:10:48.382  3407  4459 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-19 16:10:48.382  3407  4459 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-19 16:10:48.382  3407  4459 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-19 16:10:48.382  3407  4459 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-19 16:10:48.382  3407  3454 D ISSUE_DEBUG: InputChannelName : 9cba79e com.test.thalitest/com.test.thalitest.MainActivity
09-19 16:10:48.392  3407  3983 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-19 16:10:48.392  3407  3983 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-19 16:10:48.392  3407  3407 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-19 16:10:48.392  3407  3407 I KnoxTimeoutHandler: Shared devices show user statefalse
09-19 16:10:48.402  9894  9894 V ActivityThread: updateVisibility : ActivityRecord{9018f1c token=android.os.BinderProxy@6881fb7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-19 16:10:48.412  9894  9910 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-19 16:10:48.422  3407  6446 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-19 16:10:48.442  9894  9894 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9894
09-19 16:10:48.442  3407  3984 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9894 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-19 16:10:48.442  3407  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-19 16:10:48.452  3407  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-19 16:10:48.462  3407  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-19 16:10:48.472  3407  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-19 16:10:48.482  9894  9894 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-19 16:10:48.482  3407  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-19 16:10:48.482  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:48.492  3407  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-19 16:10:48.492  3407  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-19 16:10:48.502  3407  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-19 16:10:48.502  3407  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-19 16:10:48.502  3007  3007 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
09-19 16:10:48.542  9894  9947 D libEGL  : eglInitialize EGLDisplay = 0xdc7ff7c4
09-19 16:10:48.542  9894  9947 I OpenGLRenderer: Initialized EGL, version 1.4
09-19 16:10:48.542  9894  9947 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-19 16:10:48.542  3407  4184 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3407
09-19 16:10:48.542  3407  4184 I libsuspend: !@autosuspend_wakeup_count_disable
09-19 16:10:48.542  3407  4184 D PowerManagerService: mDisplayReady: false
09-19 16:10:48.542  3407  4184 I libsuspend: !@autosuspend_wakeup_count_disable done
09-19 16:10:48.542  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 16:10:48.542  3407  4184 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-19 16:10:48.542  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 16:10:48.542  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:10:48.542  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:10:48.552  3407  3569 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-19 16:10:48.552  3407  3551 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-19 16:10:48.552  3407  3551 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-19 16:10:48.552  3007  3007 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fabec3c00
09-19 16:10:48.552  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-19 16:10:48.562  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 16:10:48.562  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 16:10:48.562  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:10:48.562  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:10:48.562  3407  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-19 16:10:48.562  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 16:10:48.562  3407  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
09-19 16:10:48.562  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 16:10:48.562  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:10:48.562  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:10:48.562  3407  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-19 16:10:48.562  3407  3556 D PowerManagerService: mDisplayReady: true
09-19 16:10:48.562  3407  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-19 16:10:48.572  6196  6196 E CocktailBarPositionManager: Window direction: 0
09-19 16:10:48.572  6196  6196 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-19 16:10:48.592  9894  9894 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-19 16:10:48.602  3407  3977 V WindowStateAnimator: Finishing drawing window Window{9cba79e u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-19 16:10:48.602  9894  9894 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-19 16:10:48.602  9894  9951 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-19 16:10:48.602  9894  9951 D libEGL  : eglInitialize EGLDisplay = 0xdac9f3f4
09-19 16:10:48.612  3407  3454 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3407
09-19 16:10:48.612  3407  3551 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-19 16:10:48.612  3407  3407 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-19 16:10:48.612  3407  3551 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s190ms (total +1s676ms)
09-19 16:10:48.612  3407  3551 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{539709a u0 com.test.thalitest/.MainActivity t75} time:227613
09-19 16:10:48.612  3407  4423 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3407
09-19 16:10:48.612  3407  3551 D ViewRootImpl: #3 mView = null
09-19 16:10:48.612  3407  3407 I KnoxTimeoutHandler: SD activityfalse
09-19 16:10:48.612  3007  3017 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
09-19 16:10:48.612  3007  3017 I SurfaceFlinger: id=20 Removed uhalitest (-2/11)
09-19 16:10:48.622  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fe7579758
09-19 16:10:48.622  9894  9951 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-19 16:10:48.632  3407  4196 V WindowStateAnimator: Finishing drawing window Window{9cba79e u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-19 16:10:48.632  9894  9894 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6881fb7 time:227633
09-19 16:10:48.662  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:48.672  9894  9894 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9894
09-19 16:10:48.762  3407  3407 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3407 (0x0)
09-19 16:10:48.762  3407  3407 I libsuspend: !@autosuspend_wakeup_count_disable
09-19 16:10:48.762  3407  3407 D PowerManagerService: mDisplayReady: false
09-19 16:10:48.762  3407  3407 I libsuspend: !@autosuspend_wakeup_count_disable done
09-19 16:10:48.762  3407  3407 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-19 16:10:48.762  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-19 16:10:48.762  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 16:10:48.762  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:10:48.762  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:10:48.762  3407  3569 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-19 16:10:48.762  3007  3007 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fabec3c00
09-19 16:10:48.762  3407  3551 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-19 16:10:48.762  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-19 16:10:48.762  3407  3551 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-19 16:10:48.782  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-19 16:10:48.782  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 16:10:48.782  3407  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-19 16:10:48.782  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:10:48.782  3407  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
09-19 16:10:48.782  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:10:48.782  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-19 16:10:48.782  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 16:10:48.782  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:10:48.782  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:10:48.782  3407  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-19 16:10:48.782  3407  3556 D PowerManagerService: mDisplayReady: true
09-19 16:10:48.782  3407  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-19 16:10:48.792  6196  6196 E CocktailBarPositionManager: Window direction: 0
09-19 16:10:48.792  6196  6196 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-19 16:10:48.842  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:48.912  9894  9894 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-19 16:10:48.922  4027  4027 D Recents : onTaskStackChanged
,09-19 16:10:48.932  4027  4027 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-19 16:10:48.942  4027  4027 D ResourcesManager: For user 0 new overlays fetched Null
,09-19 16:10:49.022  9894  9958 D jxcore_app_log: JniHelper::setJavaVM(0xf4e74000), pthread_self() = -632293072
,09-19 16:10:49.022  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:49.022  9894  9958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-19 16:10:49.022  9894  9958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-19 16:10:49.022  9894  9958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-19 16:10:49.022  9894  9958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-19 16:10:49.022  9894  9958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-19 16:10:49.022  9894  9958 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6749e added. We now have 1 listener(s)
,09-19 16:10:49.022  9894  9958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
,09-19 16:10:49.022  9894  9958 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-19 16:10:49.022  9894  9958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-19 16:10:49.022  9894  9958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-19 16:10:49.032  9894  9958 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcea395 added. We now have 1 listener(s)
09-19 16:10:49.032  9894  9958 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 16:10:49.032  9894  9958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-19 16:10:49.032  9894  9958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-19 16:10:49.032  9894  9958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-19 16:10:49.032  9894  9958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-19 16:10:49.032  9894  9958 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-19 16:10:49.032  9894  9958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 16:10:49.032  9894  9958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
09-19 16:10:49.042  9894  9958 D BluetoothAdapter: STATE_ON
09-19 16:10:49.042  9894  9958 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-19 16:10:49.042  9894  9958 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 16:10:49.042  9894  9958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 16:10:49.042  9894  9958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 16:10:49.042  9894  9958 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 16:10:49.042  9894  9958 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 16:10:49.042  9894  9958 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 16:10:49.042  9894  9958 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 16:10:49.042  9894  9958 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 16:10:49.042  9894  9958 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-19 16:10:49.042  9894  9958 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 16:10:49.042  9894  9958 I io.jxcore.node.LifeCycleMonitor: start: OK
09-19 16:10:49.052  9894  9894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 16:10:49.052  9894  9894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 16:10:49.082  9894  9894 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-19 16:10:49.202  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:49.382  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:49.392  9894  9959 W jxcore-log: Initializing JXcore engine
09-19 16:10:49.392  9894  9959 W jxcore-log: JXcore engine is ready
,09-19 16:10:49.412  5032  5032 E audit   : type=1400 msg=audit(1474294249.412:264): avc:  denied  { ioctl } for  pid=9959 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2477 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-19 16:10:49.412  5032  5032 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-19 16:10:49.412  5032  5032 E audit   : type=1300 msg=audit(1474294249.412:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=da33f3c8 items=0 ppid=3177 pid=9959 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-19 16:10:49.412  5032  5032 E audit   : type=1327 msg=audit(1474294249.412:264): proctitle="com.test.thalitest"
09-19 16:10:49.412  5032  5032 E audit   : type=1320 msg=audit(1474294249.412:264): 
09-19 16:10:49.412  5032  5032 E audit   : type=1400 msg=audit(1474294249.412:265): avc:  denied  { ioctl } for  pid=9959 comm="Thread-160" path="socket:[984]" dev="sockfs" ino=984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-19 16:10:49.412  5032  5032 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-19 16:10:49.412  5032  5032 E audit   : type=1300 msg=audit(1474294249.412:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=da33f3c8 items=0 ppid=3177 pid=9959 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-19 16:10:49.412  5032  5032 E audit   : type=1327 msg=audit(1474294249.412:265): proctitle="com.test.thalitest"
09-19 16:10:49.412  5032  5032 E audit   : type=1320 msg=audit(1474294249.412:265): 
,09-19 16:10:49.412  9894  9959 W jxcore-log: Starting JXcore engine
,09-19 16:10:49.452  9894  9959 W jxcore-log: Platform android
09-19 16:10:49.452  9894  9959 W jxcore-log: 
09-19 16:10:49.452  9894  9959 W jxcore-log: Process ARCH arm
09-19 16:10:49.452  9894  9959 W jxcore-log: 
,09-19 16:10:49.522  9894  9959 I jxcore-log: JXcore Cordova bridge is ready!
09-19 16:10:49.522  9894  9959 I jxcore-log: 
09-19 16:10:49.522  9894  9959 W jxcore-log: JXcore engine is started
,09-19 16:10:49.532  9894  9958 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-19 16:10:49.542  9894  9894 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-19 16:10:49.562  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:49.742  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:49.922  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:49.942  3407  3907 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/75_task.xml.bak
,09-19 16:10:50.102  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:50.282  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:50.452  3407  6445 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-19 16:10:50.462  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:50.642  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:50.822  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:51.002  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:51.182  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:51.362  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:51.542  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:51.722  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:51.902  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:52.082  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:52.262  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:52.442  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:52.622  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:52.662  3407  6489 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-19 16:10:52.802  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:52.982  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:53.162  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:53.342  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:53.522  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:53.522  3407  6445 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-19 16:10:53.702  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:53.882  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:54.062  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:54.242  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:54.422  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:54.482  3407  6445 D SSRM:n  : SIOP:: AP = 320, PST = 277 (W:6), CP = 225, CUR = 9, LCD = 1
,09-19 16:10:54.602  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:54.782  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:54.962  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:55.142  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:55.322  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:55.432  8559  8582 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,09-19 16:10:55.472  9894  9959 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-19 16:10:55.472  9894  9959 I jxcore-log: 
,09-19 16:10:55.482  9894  9959 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-19 16:10:55.482  9894  9959 I jxcore-log: 
,09-19 16:10:55.492  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.492  9894  9959 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 16:10:55.492  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 16:10:55.492  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 16:10:55.492  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 16:10:55.492  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 16:10:55.492  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 16:10:55.492  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 16:10:55.492  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 16:10:55.492  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.502  9894  9959 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-19 16:10:55.502  9894  9959 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-19 16:10:55.502  9894  9959 I jxcore-log: 
09-19 16:10:55.502  9894  9959 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-19 16:10:55.502  9894  9959 I jxcore-log: 
,09-19 16:10:55.502  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:55.652  9894  9959 I jxcore-log: Running unit tests
09-19 16:10:55.652  9894  9959 I jxcore-log: 
,09-19 16:10:55.652  9894  9959 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 16:10:55.652  9894  9959 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8a7a85 added. We now have 2 listener(s)
09-19 16:10:55.652  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-19 16:10:55.652  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 16:10:55.652  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 16:10:55.652  9894  9959 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-19 16:10:55.652  9894  9959 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@328e0da added. We now have 2 listener(s)
09-19 16:10:55.652  9894  9959 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 16:10:55.652  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-19 16:10:55.652  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 16:10:55.662  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.672  9894  9959 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 16:10:55.672  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 16:10:55.672  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 16:10:55.672  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 16:10:55.672  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 16:10:55.672  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 16:10:55.672  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 16:10:55.672  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 16:10:55.672  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.682  9894  9959 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 16:10:55.682  9894  9959 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 16:10:55.682  9894  9959 D executeNativeTests: Running unit tests
,09-19 16:10:55.682  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:55.682  9894  9894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 16:10:55.692  9894  9894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 16:10:55.712  9894  9959 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-19 16:10:55.712  9894  9959 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c3a718 added. We now have 3 listener(s)
09-19 16:10:55.712  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-19 16:10:55.712  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 16:10:55.712  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 16:10:55.712  9894  9959 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 16:10:55.712  9894  9959 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c7a571 added. We now have 3 listener(s)
,09-19 16:10:55.712  9894  9959 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 16:10:55.712  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-19 16:10:55.722  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 16:10:55.732  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.732  9894  9959 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 16:10:55.732  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 16:10:55.732  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 16:10:55.732  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 16:10:55.732  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 16:10:55.732  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 16:10:55.732  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 16:10:55.732  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 16:10:55.732  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.742  9894  9959 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-19 16:10:55.742  9894  9959 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-19 16:10:55.742  9894  9959 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-19 16:10:55.742  9894  9959 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 16:10:55.742  9894  9959 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 16:10:55.742  9894  9959 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 16:10:55.742  9894  9959 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-19 16:10:55.742  9894  9959 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-19 16:10:55.742  9894  9959 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-19 16:10:55.742  9894  9959 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 16:10:55.742  9894  9959 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 16:10:55.742  9894  9959 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 16:10:55.742  9894  9959 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 16:10:55.742  9894  9959 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 16:10:55.742  9894  9959 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 16:10:55.742  9894  9959 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 16:10:55.742  9894  9959 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 16:10:55.742  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-19 16:10:55.742  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 16:10:55.742  9894  9959 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c3a718 removed from the list
09-19 16:10:55.742  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 16:10:55.742  9894  9959 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c7a571 removed from the list
,09-19 16:10:55.742  9894  9894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 16:10:55.742  9894  9959 D io.jxcore.node.ConnectivityMonitor: stop
,09-19 16:10:55.742  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 16:10:55.742  9894  9959 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 16:10:55.742  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 16:10:55.752  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 16:10:55.752  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 16:10:55.752  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 16:10:55.752  9894  9959 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c7a571 not in the list
,09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-19 16:10:55.752  9894  9959 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 16:10:55.752  9894  9959 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 16:10:55.752  9894  9959 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 16:10:55.752  9894  9959 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 16:10:55.752  9894  9959 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 16:10:55.752  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 16:10:55.752  9894  9959 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c3a718 not in the list
09-19 16:10:55.752  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 16:10:55.752  9894  9959 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c7a571 not in the list
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectivityMonitor: stop
09-19 16:10:55.752  9894  9959 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 16:10:55.752  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 16:10:55.752  9894  9959 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 16:10:55.752  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 16:10:55.752  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 16:10:55.752  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-19 16:10:55.752  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 16:10:55.752  9894  9959 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c7a571 not in the list
,09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-19 16:10:55.752  9894  9959 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 16:10:55.752  9894  9959 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 16:10:55.752  9894  9959 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 16:10:55.752  9894  9959 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 16:10:55.752  9894  9959 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 16:10:55.752  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 16:10:55.752  9894  9959 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c3a718 not in the list
09-19 16:10:55.752  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 16:10:55.752  9894  9959 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c7a571 not in the list
09-19 16:10:55.752  9894  9959 D io.jxcore.node.ConnectivityMonitor: stop
09-19 16:10:55.752  9894  9959 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 16:10:55.752  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 16:10:55.752  9894  9959 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 16:10:55.752  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 16:10:55.752  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 16:10:55.752  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 16:10:55.752  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 16:10:55.752  9894  9959 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c7a571 not in the list
09-19 16:10:55.762  9894  9959 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-19 16:10:55.762  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 16:10:55.762  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.762  9894  9959 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 16:10:55.762  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 16:10:55.762  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 16:10:55.762  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 16:10:55.762  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 16:10:55.762  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 16:10:55.762  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 16:10:55.762  9894  9959 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 16:10:55.772  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.772  9894  9959 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-19 16:10:55.772  9894  9959 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 16:10:55.772  9894  9959 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 16:10:55.772  9894  9959 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-19 16:10:55.772  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-19 16:10:55.772  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 16:10:55.772  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-19 16:10:55.772  9894  9959 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-19 16:10:55.772  9894  9959 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-19 16:10:55.782  9894  9894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 16:10:55.782  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.782  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.782  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.782  9894  9894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 16:10:55.792  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-19 16:10:55.792  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.792  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.792  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-19 16:10:55.792  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-19 16:10:55.792  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.792  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.802  9894  9959 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-19 16:10:55.802  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.802  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.802  9894  9959 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-19 16:10:55.802  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-19 16:10:55.802  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-19 16:10:55.802  9894  9959 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-19 16:10:55.802  9894  9959 D BluetoothLeScanner: Start Scan
,09-19 16:10:55.812  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.812  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.812  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.812  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.822  5026  5422 D BtGatt.GattService: registerClient() - UUID=71ea4472-68b2-48be-9e2b-f38da0d6bf53
,09-19 16:10:55.862  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:55.872  5026  5127 D BtGatt.GattService: onClientRegistered() - UUID=71ea4472-68b2-48be-9e2b-f38da0d6bf53, clientIf=7
,09-19 16:10:55.872  9894  9904 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-19 16:10:55.872  5026  5038 D BtGatt.GattService: start scan with filters
,09-19 16:10:55.872  5026  5038 D BtGatt.GattService: getScanSettings
,09-19 16:10:55.892  5026  5038 D BtGatt.GattService: Is it foreground application = true
,09-19 16:10:55.892  5026  5038 D BtGatt.GattService: not a background application
,09-19 16:10:55.902  5026  5038 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-19 16:10:55.912  5026  5038 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-19 16:10:55.912  5026  5038 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest,
09-19 16:10:55.922  5026  5166 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN,
09-19 16:10:55.922  5026  5166 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
09-19 16:10:55.922  5026  5157 D BtGatt.ScanManager: handling starting scan
09-19 16:10:55.922  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-19 16:10:55.922  5026  5157 D BtGatt.ScanManager: isFilteringSupported
09-19 16:10:55.922  5026  5157 D BluetoothAdapter: enableStandAloneBleMode=
,09-19 16:10:55.922  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-19 16:10:55.922  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-19 16:10:55.922  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-19 16:10:55.922  5026  5157 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.932  5026  5157 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.932  9894  9959 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-19 16:10:55.932  9894  9959 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-19 16:10:55.932  9894  9894 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-19 16:10:55.942  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-19 16:10:55.942  5026  5166 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 26
09-19 16:10:55.942  5026  5166 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-19 16:10:55.942  5026  5157 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.942  5026  5157 D BluetoothAdapter: STATE_ON
,09-19 16:10:55.942  5026  5157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@41c9d90
,09-19 16:10:55.952  9894  9959 I io.jxcore.node.ConnectionHelper: start: OK
,09-19 16:10:55.952  5026  5166 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 1
09-19 16:10:55.952  3407  4423 V AlarmManager:  remove PendingIntent] PendingIntent{a0ce767: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:55.952  5026  5166 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24571570
09-19 16:10:55.952  5026  5166 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-19 16:10:55.952  5026  5166 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-19 16:10:55.952  5026  5166 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-19 16:10:55.952  5026  5166 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
09-19 16:10:55.952  5026  5166 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 3 => 3
,09-19 16:10:55.952  5026  5166 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-19 16:10:55.962  5026  5166 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
09-19 16:10:55.962  5026  5166 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 3 => 3
09-19 16:10:55.962  5026  5166 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
,09-19 16:10:55.962  3407  4458 V AlarmManager:  remove PendingIntent] PendingIntent{6aa1914: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
09-19 16:10:55.962  5026  5166 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-19 16:10:55.962  5026  5127 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-19 16:10:55.962  5026  5127 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-19 16:10:55.962  5026  5166 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 3
09-19 16:10:55.962  5026  5166 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 3 => 3
09-19 16:10:55.962  5026  5166 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24571570
09-19 16:10:55.962  5026  5157 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
09-19 16:10:55.962  5026  5157 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-19 16:10:55.962  5026  5157 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-19 16:10:55.962  5026  5157 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-19 16:10:55.962  5026  5127 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-19 16:10:55.962  5026  5127 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-19 16:10:55.962  5026  5157 D BtGatt.ScanManager: Starting BLE batch scan
09-19 16:10:55.962  5026  5157 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-19 16:10:55.962  3407  4459 V AlarmManager:  remove PendingIntent] PendingIntent{388f5bd: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:55.972  5026  5127 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-19 16:10:55.972  5026  5127 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-19 16:10:55.972  5026  5127 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,09-19 16:10:55.972  5026  5127 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-19 16:10:55.972  3407  4848 V AlarmManager:  remove PendingIntent] PendingIntent{95e67b2: PendingIntentRecord{899b280 com.android.bluetooth broadcastIntent}}
09-19 16:10:55.972  3407  4849 V AlarmManager:  remove PendingIntent] PendingIntent{6769303: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:55.982  3407  3454 V AlarmManager:  remove PendingIntent] PendingIntent{cd430b9: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:55.982  3407  3452 V AlarmManager:  remove PendingIntent] PendingIntent{5474cfe: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
09-19 16:10:55.992  3407  4427 V AlarmManager:  remove PendingIntent] PendingIntent{3455c5f: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
09-19 16:10:55.992  3407  4179 V AlarmManager:  remove PendingIntent] PendingIntent{72776ac: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
09-19 16:10:56.002  3407  4849 V AlarmManager:  remove PendingIntent] PendingIntent{6fe1f75: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
09-19 16:10:56.002  3407  3984 V AlarmManager:  remove PendingIntent] PendingIntent{1473b0a: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
09-19 16:10:56.012  3407  4423 V AlarmManager:  remove PendingIntent] PendingIntent{30d5f7b: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
09-19 16:10:56.012  3407  4458 V AlarmManager:  remove PendingIntent] PendingIntent{3eb5198: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:56.022  3407  4459 V AlarmManager:  remove PendingIntent] PendingIntent{19e3df1: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:56.042  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:56.222  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:56.402  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:56.442  9894  9894 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-19 16:10:56.442  9894  9894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 16:10:56.442  9894  9894 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-19 16:10:56.582  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:56.762  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:56.942  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:56.972  3407  3818 V AlarmManager: Expired Alarm result :4
,09-19 16:10:56.982  5026  5026 D BtGatt.ScanManager: awakened up at time 235981
,09-19 16:10:56.982  5026  5157 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-19 16:10:56.982  3407  3577 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
09-19 16:10:56.982  3407  4184 V AlarmManager:  remove PendingIntent] PendingIntent{3887857: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:56.992  5026  5127 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=6
09-19 16:10:56.992  5026  5127 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-19 16:10:56.992  5026  5127 D BtGatt.GattService: current time is 235994975562
09-19 16:10:56.992  3407  3454 V AlarmManager:  remove PendingIntent] PendingIntent{fef44: PendingIntentRecord{899b280 com.android.bluetooth broadcastIntent}}
,09-19 16:10:56.992  5026  5127 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -74, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -77, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -106, -15, -31, -128, 20, -7, 1, -128, -98, 15, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -27, 4, 9, 3, 1, -29, 18, 62, -93, -41, 61, 0, 71, -122, -77, 84, 69, -12, 1, -128, -79, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -72, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-19 16:10:56.992  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-19 16:10:57.002  5026  5127 D ScanRecord: parseFromBytes
,09-19 16:10:57.002  5026  5127 D ScanRecord: first manudata for manu ID
09-19 16:10:57.002  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-19 16:10:57.002  5026  5127 D ScanRecord: parseFromBytes
,09-19 16:10:57.002  5026  5127 D ScanRecord: first manudata for manu ID
09-19 16:10:57.002  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -27, 4, 9, 3, 1, -29, 18, 62, -93, -41, 61]
09-19 16:10:57.002  5026  5127 D ScanRecord: parseFromBytes
09-19 16:10:57.002  5026  5127 D ScanRecord: first manudata for manu ID
09-19 16:10:57.002  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-19 16:10:57.002  5026  5127 D ScanRecord: parseFromBytes
09-19 16:10:57.002  5026  5127 D ScanRecord: first manudata for manu ID
09-19 16:10:57.002  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-19 16:10:57.002  5026  5127 D ScanRecord: parseFromBytes
09-19 16:10:57.002  5026  5127 D ScanRecord: first manudata for manu ID
,09-19 16:10:57.002  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-19 16:10:57.002  5026  5127 D ScanRecord: parseFromBytes
09-19 16:10:57.002  5026  5127 D ScanRecord: first manudata for manu ID
,09-19 16:10:57.012  9894  9905 D ScanRecord: parseFromBytes
,09-19 16:10:57.012  9894  9905 D ScanRecord: first manudata for manu ID
,09-19 16:10:57.012  3407  3577 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-19 16:10:57.012  9894  9905 D ScanRecord: parseFromBytes
09-19 16:10:57.012  9894  9905 D ScanRecord: first manudata for manu ID
09-19 16:10:57.012  9894  9905 D ScanRecord: parseFromBytes
09-19 16:10:57.012  9894  9905 D ScanRecord: first manudata for manu ID
09-19 16:10:57.012  9894  9905 D ScanRecord: parseFromBytes
09-19 16:10:57.012  9894  9905 D ScanRecord: first manudata for manu ID
09-19 16:10:57.012  9894  9905 D ScanRecord: parseFromBytes
,09-19 16:10:57.012  9894  9905 D ScanRecord: first manudata for manu ID
09-19 16:10:57.012  9894  9905 D ScanRecord: parseFromBytes
09-19 16:10:57.012  9894  9905 D ScanRecord: first manudata for manu ID
,09-19 16:10:57.022  3407  4851 V AlarmManager:  remove PendingIntent] PendingIntent{447c82d: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:57.032  3407  4459 V AlarmManager:  remove PendingIntent] PendingIntent{15c2162: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:57.032  3407  3977 V AlarmManager:  remove PendingIntent] PendingIntent{a3242f3: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:57.042  3407  3454 V AlarmManager:  remove PendingIntent] PendingIntent{2bebbb0: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:57.042  3407  4190 V AlarmManager:  remove PendingIntent] PendingIntent{285ba29: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:57.052  3407  4851 V AlarmManager:  remove PendingIntent] PendingIntent{65ef1ae: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:57.052  3407  4196 V AlarmManager:  remove PendingIntent] PendingIntent{ea41b4f: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:57.122  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:57.302  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:57.482  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:57.662  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:57.842  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:57.992  3407  3818 V AlarmManager: Expired Alarm result :4
,09-19 16:10:58.002  5026  5026 D BtGatt.ScanManager: awakened up at time 237003
,09-19 16:10:58.002  5026  5157 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-19 16:10:58.012  3407  4184 V AlarmManager:  remove PendingIntent] PendingIntent{396cfe5: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:58.022  5026  5127 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
,09-19 16:10:58.022  3407  4848 V AlarmManager:  remove PendingIntent] PendingIntent{aac7aba: PendingIntentRecord{899b280 com.android.bluetooth broadcastIntent}}
,09-19 16:10:58.022  5026  5127 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-19 16:10:58.022  5026  5127 D BtGatt.GattService: current time is 237022684561
09-19 16:10:58.022  5026  5127 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -79, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -76, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,09-19 16:10:58.022  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-19 16:10:58.022  5026  5127 D ScanRecord: parseFromBytes
09-19 16:10:58.022  5026  5127 D ScanRecord: first manudata for manu ID
09-19 16:10:58.022  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-19 16:10:58.022  5026  5127 D ScanRecord: parseFromBytes
09-19 16:10:58.022  5026  5127 D ScanRecord: first manudata for manu ID
09-19 16:10:58.022  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-19 16:10:58.022  5026  5127 D ScanRecord: parseFromBytes
,09-19 16:10:58.022  5026  5127 D ScanRecord: first manudata for manu ID
09-19 16:10:58.022  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 16:10:58.022  9894  9904 D ScanRecord: parseFromBytes
09-19 16:10:58.022  9894  9904 D ScanRecord: first manudata for manu ID
09-19 16:10:58.022  9894  9904 D ScanRecord: parseFromBytes
,09-19 16:10:58.022  9894  9904 D ScanRecord: first manudata for manu ID
09-19 16:10:58.022  9894  9904 D ScanRecord: parseFromBytes
09-19 16:10:58.022  9894  9904 D ScanRecord: first manudata for manu ID
09-19 16:10:58.032  3407  4423 V AlarmManager:  remove PendingIntent] PendingIntent{eb11d6b: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:58.032  3407  4458 V AlarmManager:  remove PendingIntent] PendingIntent{42250c8: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:58.042  3407  4459 V AlarmManager:  remove PendingIntent] PendingIntent{9e98561: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:58.042  3407  3977 V AlarmManager:  remove PendingIntent] PendingIntent{9178886: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:58.052  3407  3983 V AlarmManager:  remove PendingIntent] PendingIntent{8422547: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:58.202  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:58.382  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:58.562  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:58.742  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:58.922  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:59.022  3407  3818 V AlarmManager: Expired Alarm result :4
,09-19 16:10:59.032  5026  5026 D BtGatt.ScanManager: awakened up at time 238030
,09-19 16:10:59.032  5026  5157 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-19 16:10:59.032  3407  4851 V AlarmManager:  remove PendingIntent] PendingIntent{658169d: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:59.042  5026  5127 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-19 16:10:59.042  5026  5127 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-19 16:10:59.042  3407  4427 V AlarmManager:  remove PendingIntent] PendingIntent{4d3a712: PendingIntentRecord{899b280 com.android.bluetooth broadcastIntent}}
,09-19 16:10:59.062  3407  4179 V AlarmManager:  remove PendingIntent] PendingIntent{4f1cee3: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:59.062  3407  4184 V AlarmManager:  remove PendingIntent] PendingIntent{e9070e0: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:10:59.102  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:59.282  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:59.462  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:59.642  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:59.822  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:10:59.992  3407  3818 V AlarmManager: Expired Alarm result :8
,09-19 16:11:00.002  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:00.042  3407  3818 V AlarmManager: Expired Alarm result :4
,09-19 16:11:00.052  5026  5026 D BtGatt.ScanManager: awakened up at time 239054
,09-19 16:11:00.062  5026  5157 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-19 16:11:00.062  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-19 16:11:00.062  3939  3939 D KeyguardUpdateMonitor: handleTimeUpdate
,09-19 16:11:00.062  3407  4851 V AlarmManager:  remove PendingIntent] PendingIntent{368763f: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:00.062  5026  5127 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
,09-19 16:11:00.062  5026  5127 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-19 16:11:00.062  3407  4190 V AlarmManager:  remove PendingIntent] PendingIntent{b3bbb0c: PendingIntentRecord{899b280 com.android.bluetooth broadcastIntent}}
09-19 16:11:00.062  5026  5127 D BtGatt.GattService: current time is 239067971983
09-19 16:11:00.062  5026  5127 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -76, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-19 16:11:00.062  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-19 16:11:00.062  5026  5127 D ScanRecord: parseFromBytes
09-19 16:11:00.062  5026  5127 D ScanRecord: first manudata for manu ID
09-19 16:11:00.072  9894  9904 D ScanRecord: parseFromBytes
,09-19 16:11:00.072  9894  9904 D ScanRecord: first manudata for manu ID
,09-19 16:11:00.082  3939  3939 D Clock   : received broadcast android.intent.action.TIME_TICK
,09-19 16:11:00.102  3407  3983 V AlarmManager:  remove PendingIntent] PendingIntent{2b47c55: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:00.132  3407  4179 V AlarmManager:  remove PendingIntent] PendingIntent{379066a: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:00.132  3407  4458 V AlarmManager:  remove PendingIntent] PendingIntent{a78375b: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:00.142  3407  4848 V AlarmManager:  remove PendingIntent] PendingIntent{16f7bf8: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:00.142  3939  3939 D DateView: received broadcast android.intent.action.TIME_TICK
,09-19 16:11:00.162  3407  4179 V AlarmManager:  remove PendingIntent] PendingIntent{e0d88d1: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:00.172  7961  7961 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,09-19 16:11:00.172  7961  7961 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-19 16:11:00.182  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:00.362  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:00.432  3407  3818 V AlarmManager: Expired Alarm result :4
,09-19 16:11:00.442  3407  3818 V AlarmManager: Send whitelist package alarm :PendingIntent{f301d8d: PendingIntentRecord{c0705b2 com.samsung.android.app.aodservice broadcastIntent}}
,09-19 16:11:00.442  4762  4762 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
,09-19 16:11:00.442  4762  4762 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,09-19 16:11:00.452  3407  4423 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-19 16:11:00.452  3407  4423 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
,09-19 16:11:00.452  3407  4423 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
09-19 16:11:00.452  3407  4423 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
09-19 16:11:00.452  3167  7790 D Sensorhubs: sendContextData: -72, 56, 1, 1
,09-19 16:11:00.462  3407  4423 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-19 16:11:00.472  3407  4423 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-19 16:11:00.472  3407  4423 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
09-19 16:11:00.472  4762  4762 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@89d45b0, service=Device Physical Context Monitor
,09-19 16:11:00.472  4762  4762 I AlpmModeManager: startAlpmMode : state  = BLANK
09-19 16:11:00.472  4762  4762 D DefaultClockView: Window showed. Time views updating
,09-19 16:11:00.472  3407  4190 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3407
,09-19 16:11:00.472  3407  4190 D PowerManagerService: mDisplayReady: false
,09-19 16:11:00.472  3407  4190 I libsuspend: !@autosuspend_wakeup_count_disable
09-19 16:11:00.472  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 16:11:00.472  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 16:11:00.482  3407  4190 I libsuspend: !@autosuspend_wakeup_count_disable done
09-19 16:11:00.472  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:11:00.482  3007  3007 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fabec3c00
09-19 16:11:00.472  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:11:00.482  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-19 16:11:00.472  3407  3556 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-19 16:11:00.472  3407  3569 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-19 16:11:00.482  3407  3551 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-19 16:11:00.482  3407  3551 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-19 16:11:00.492  3167  3208 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
09-19 16:11:00.492  3407  3821 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
09-19 16:11:00.492  3407  3820 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 14, 11, 0,
,09-19 16:11:00.492  3407  3820 D SensorHubManager: SendSensorHubData: send data = -63, 14, 14, 11, 0
,09-19 16:11:00.492  4762  4762 D AODUpdatePositionController: updatePosition: direction[1] updatePosition: X[8] Y[697] NewPositionTimer[56]
,09-19 16:11:00.502  4762  4762 D DefaultClockView: LocalTime Pattern : HH:mm
,09-19 16:11:00.502  4762  4762 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 16:11 time02: null ampm: null
,09-19 16:11:00.512  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 16:11:00.512  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 16:11:00.512  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:11:00.512  3407  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-19 16:11:00.512  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:11:00.512  3407  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
09-19 16:11:00.512  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 16:11:00.512  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 16:11:00.512  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:11:00.512  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:11:00.512  3407  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-19 16:11:00.512  3407  3556 D PowerManagerService: mDisplayReady: true
09-19 16:11:00.512  3407  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-19 16:11:00.512  3167  3167 D Sensorhubs: sendContextData: -63, 14, 14, 11, 0
,09-19 16:11:00.522  6196  6196 E CocktailBarPositionManager: Window direction: 0
09-19 16:11:00.522  6196  6196 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-19 16:11:00.532  3407  3820 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
09-19 16:11:00.532  3407  3820 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
,09-19 16:11:00.532  3407  3820 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
,09-19 16:11:00.532  3407  3820 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
09-19 16:11:00.532  3407  3820 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
,09-19 16:11:00.532  3407  3823 D SContextService: updateSContext() : event = Device Physical Context Monitor
,09-19 16:11:00.532  4762  4762 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,09-19 16:11:00.532  4762  4762 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,09-19 16:11:00.542  4762  4762 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:pon., 19 wrz 16:11
,09-19 16:11:00.542  4762  4762 I AODService.ClockTimer: startAlarm : TICK
,09-19 16:11:00.542  3407  4190 V AlarmManager: Add whitelist package alarm :PendingIntent{1f8ee37: PendingIntentRecord{c0705b2 com.samsung.android.app.aodservice broadcastIntent}}
,09-19 16:11:00.542  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:00.542  4762  4762 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,09-19 16:11:00.542  4762  4762 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
,09-19 16:11:00.542  3407  4184 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
09-19 16:11:00.542  3407  4184 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,09-19 16:11:00.552  3407  4848 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3407
,09-19 16:11:00.552  4762  4762 I AODService: onSContextChanged: AODScreenShown state is already true
,09-19 16:11:00.552  4762  4762 D DefaultClockView: RootView invalidate()
09-19 16:11:00.552  3407  3984 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3407
,09-19 16:11:00.702  3407  3407 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3407 (0x0)
,09-19 16:11:00.702  3407  3407 I libsuspend: !@autosuspend_wakeup_count_disable
09-19 16:11:00.702  3407  3407 D PowerManagerService: mDisplayReady: false
09-19 16:11:00.702  3407  3407 I libsuspend: !@autosuspend_wakeup_count_disable done
09-19 16:11:00.702  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-19 16:11:00.702  3407  3407 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,09-19 16:11:00.702  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 16:11:00.702  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:11:00.712  3007  3007 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fabec3c00
09-19 16:11:00.702  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:11:00.712  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,09-19 16:11:00.712  3407  3569 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-19 16:11:00.712  3407  3551 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,09-19 16:11:00.712  3407  3551 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-19 16:11:00.722  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:00.742  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-19 16:11:00.742  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 16:11:00.742  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 16:11:00.742  3407  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-19 16:11:00.742  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:11:00.742  3407  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
,09-19 16:11:00.742  3407  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-19 16:11:00.742  3407  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 16:11:00.742  3407  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-19 16:11:00.742  3407  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 16:11:00.742  3407  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-19 16:11:00.742  3407  3556 D PowerManagerService: mDisplayReady: true
,09-19 16:11:00.742  3407  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-19 16:11:00.752  6196  6196 E CocktailBarPositionManager: Window direction: 0
09-19 16:11:00.752  6196  6196 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-19 16:11:00.902  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:00.962  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:11:00.972  9894  9959 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 16:11:00.972  9894  9959 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-19 16:11:00.972  9894  9959 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-19 16:11:00.972  9894  9959 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 16:11:00.972  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-19 16:11:00.972  9894  9959 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-19 16:11:00.972  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-19 16:11:00.972  9894  9959 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-19 16:11:00.972  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 16:11:00.972  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-19 16:11:00.972  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-19 16:11:00.972  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:11:00.982  9894  9959 D BluetoothAdapter: STATE_ON
,09-19 16:11:00.982  9894  9959 D BluetoothLeScanner: Stop Scan
,09-19 16:11:00.992  5026  5422 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-19 16:11:00.992  5026  5422 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-19 16:11:00.992  5026  5422 D BtGatt.GattService: stopScan() - queue size =1
09-19 16:11:00.992  5026  5166 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-19 16:11:00.992  5026  5166 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
09-19 16:11:00.992  5026  5166 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 1
09-19 16:11:00.992  5026  5157 D BtGatt.ScanManager: filter size is 1
,09-19 16:11:00.992  5026  5157 D BtGatt.ScanManager: delete FilterIndex - 3
09-19 16:11:00.992  5026  5038 D BtGatt.GattService: unregisterClient() - clientIf=7
,09-19 16:11:00.992  3407  3454 V AlarmManager:  remove PendingIntent] PendingIntent{51c5fa4: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.002  5026  5127 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32,
,09-19 16:11:01.002  5026  5127 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-19 16:11:01.002  5026  5157 D BtGatt.ScanManager: stopping BLe Batch
09-19 16:11:01.002  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 16:11:01.002  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-19 16:11:01.012  3407  3983 V AlarmManager:  remove PendingIntent] PendingIntent{f10e10d: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.002  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-19 16:11:01.002  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-19 16:11:01.002  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-19 16:11:01.002  5026  5127 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-19 16:11:01.002  5026  5127 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-19 16:11:01.002  9894  9959 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 16:11:01.012  5026  5157 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-19 16:11:01.012  5026  5166 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 3 => 4
,09-19 16:11:01.012  9894  9959 D BluetoothAdapter: STATE_ON
09-19 16:11:01.012  9894  9959 D BluetoothAdapter: STATE_ON
09-19 16:11:01.012  9894  9959 D BluetoothLeAdvertiser: stop advertising
09-19 16:11:01.022  3407  4851 V AlarmManager:  remove PendingIntent] PendingIntent{bcff8c2: PendingIntentRecord{899b280 com.android.bluetooth broadcastIntent}}
09-19 16:11:01.012  9894  9959 D BluetoothLeAdvertiser: wrapper is null
09-19 16:11:01.022  3407  4459 V AlarmManager:  remove PendingIntent] PendingIntent{d6436d3: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
09-19 16:11:01.012  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 16:11:01.012  9894  9959 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-19 16:11:01.012  9894  9959 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 16:11:01.012  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 16:11:01.012  5026  5127 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=4
09-19 16:11:01.012  5026  5127 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-19 16:11:01.012  5026  5127 D BtGatt.GattService: current time is 240018697559
09-19 16:11:01.012  5026  5127 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -75, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -75, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -87, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-19 16:11:01.012  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-19 16:11:01.022  3407  3977 V AlarmManager:  remove PendingIntent] PendingIntent{691d210: PendingIntentRecord{899b280 com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.012  5026  5127 D ScanRecord: parseFromBytes
09-19 16:11:01.012  5026  5127 D ScanRecord: first manudata for manu ID
09-19 16:11:01.022  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-19 16:11:01.022  5026  5127 D ScanRecord: parseFromBytes
09-19 16:11:01.022  5026  5127 D ScanRecord: first manudata for manu ID
,09-19 16:11:01.022  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-19 16:11:01.022  5026  5127 D ScanRecord: parseFromBytes
09-19 16:11:01.022  5026  5127 D ScanRecord: first manudata for manu ID
09-19 16:11:01.022  5026  5127 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-19 16:11:01.022  5026  5127 D ScanRecord: parseFromBytes
,09-19 16:11:01.022  5026  5127 D ScanRecord: first manudata for manu ID
09-19 16:11:01.022  5026  5166 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 3 => 4
09-19 16:11:01.022  5026  5166 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
,09-19 16:11:01.022  5026  5166 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-19 16:11:01.022  9894  9894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 16:11:01.032  3407  3983 V AlarmManager:  remove PendingIntent] PendingIntent{2778109: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
09-19 16:11:01.022  9894  9959 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 16:11:01.022  9894  9959 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 16:11:01.022  9894  9894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 16:11:01.022  9894  9894 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 16:11:01.022  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 16:11:01.022  9894  9959 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c3a718 not in the list
09-19 16:11:01.022  9894  9959 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 16:11:01.022  9894  9959 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c7a571 not in the list
09-19 16:11:01.022  9894  9959 D io.jxcore.node.ConnectivityMonitor: stop
09-19 16:11:01.022  9894  9959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 16:11:01.032  3407  4458 V AlarmManager:  remove PendingIntent] PendingIntent{c28df0e: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.032  3407  4190 V AlarmManager:  remove PendingIntent] PendingIntent{4316d2f: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.042  3407  4459 V AlarmManager:  remove PendingIntent] PendingIntent{9a9ff3c: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.042  3407  3452 V AlarmManager:  remove PendingIntent] PendingIntent{d8e24c5: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.052  3407  3984 V AlarmManager:  remove PendingIntent] PendingIntent{a17de1a: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.052  3407  4184 V AlarmManager:  remove PendingIntent] PendingIntent{3f1ad4b: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.062  3407  4427 V AlarmManager:  remove PendingIntent] PendingIntent{3b5d328: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.062  3407  4851 V AlarmManager:  remove PendingIntent] PendingIntent{3b14841: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.062  3407  4849 V AlarmManager:  remove PendingIntent] PendingIntent{9c5c1e6: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.072  3407  3977 V AlarmManager:  remove PendingIntent] PendingIntent{82bd327: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.072  3407  4423 V AlarmManager:  remove PendingIntent] PendingIntent{c28f9d4: PendingIntentRecord{514813b com.android.bluetooth broadcastIntent}}
,09-19 16:11:01.082  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:01.262  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:01.442  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:01.522  9894  9894 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-19 16:11:01.622  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:01.802  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:01.982  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:02.162  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:02.342  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:02.522  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:02.702  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:02.882  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:03.062  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:03.242  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:03.422  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:03.602  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:03.782  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:03.962  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:04.142  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:04.322  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:04.502  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:04.512  3407  6445 D SSRM:n  : SIOP:: AP = 290, PST = 275 (W:14), CP = 233, CUR = -44, LCD = 1
09-19 16:11:04.512  3407  4196 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-19 16:11:04.512  3407  4196 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-19 16:11:04.512  3407  4196 D BatteryService: online:4, current avg:-44, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
09-19 16:11:04.512  3407  4196 D BatteryService: stay LED for fully charged
09-19 16:11:04.512  3407  3407 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-19 16:11:04.522  3407  3407 I MotionRecognitionService: Plugged
,09-19 16:11:04.522  3407  3407 D MotionRecognitionService:   cableConnection= 1
09-19 16:11:04.522  3407  3407 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-19 16:11:04.522  3407  3407 D MotionRecognitionService: skip setTransmitPower. 
,09-19 16:11:04.522  3407  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-19 16:11:04.522  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-19 16:11:04.522  3939  3939 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-19 16:11:04.532  3939  3939 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-19 16:11:04.542  5066  5066 D CommonServiceConfiguration: getStringValueSetting
,09-19 16:11:04.552  5026  5026 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-19 16:11:04.552  5026  5424 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-19 16:11:04.552  5066  5066 D BatteryMonitor: new battery level: 100
,09-19 16:11:04.562  4762  4762 D BatteryController: saveBatteryData : level[100], status[5]
,09-19 16:11:04.562  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-19 16:11:04.562  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-19 16:11:04.682  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:04.862  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:05.042  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 16:11:05.222  3407  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
