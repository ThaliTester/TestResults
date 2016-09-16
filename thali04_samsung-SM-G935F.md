#### Test 84500654ae9737d_thali04_samsung-SM-G935F Logs


```
--------- beginning of main
09-16 17:10:58.471  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:10:58.651  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:10:58.831  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:10:59.011  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:10:59.091  9898  9898 I FIPS_bssl: FIPS approved mode (1) | 9898 | app_process
09-16 17:10:59.091  9898  9898 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 17:10:59.101  9898  9898 D AndroidRuntime: CheckJNI is OFF
09-16 17:10:59.101  9898  9898 D AndroidRuntime: readGMSProperty: start
09-16 17:10:59.101  9898  9898 D AndroidRuntime: readGMSProperty: already setted!!
09-16 17:10:59.101  9898  9898 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-16 17:10:59.101  9898  9898 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-16 17:10:59.101  9898  9898 D AndroidRuntime: readGMSProperty: end
09-16 17:10:59.101  9898  9898 D AndroidRuntime: addProductProperty: start
09-16 17:10:59.121  9898  9898 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 17:10:59.141  9898  9898 I Radio-JNI: register_android_hardware_Radio DONE
09-16 17:10:59.141  9898  9898 E AffinityControl: AffinityControl: registerfunction enter
09-16 17:10:59.151  9898  9898 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-16 17:10:59.181  3394  4985 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-16 17:10:59.181  3394  4985 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-16 17:10:59.191  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:10:59.211  3394  4985 D ResourcesManager: For user 0 new overlays fetched Null
09-16 17:10:59.211  3394  4985 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 17:10:59.211  3394  4985 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-16 17:10:59.221  3394  4985 D ActivityManager: mDVFSHelper.acquire()
09-16 17:10:59.221  3394  4985 V WindowManager: addAppToken: AppWindowToken{d0a079b5c token=Token{a9165cf ActivityRecord{4e0d62e u0 com.test.thalitest/.MainActivity t75}}} to stack=2 task=75 at 0
09-16 17:10:59.221  3394  3536 I InjectionManager: Inside getClassLibPath caller 
09-16 17:10:59.231  3394  3536 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-16 17:10:59.231  3394  3536 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ad9f9f4 V.E...... R.....ID 0,0-0,0}
09-16 17:10:59.231  9907  9907 E Zygote  : v2
09-16 17:10:59.231  9907  9907 I libpersona: KNOX_SDCARD checking this for 10177
09-16 17:10:59.231  9907  9907 I libpersona: KNOX_SDCARD not a persona
09-16 17:10:59.241  3394  3536 W WindowManager: Failed looking up window
09-16 17:10:59.241  3394  3536 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@faff51d does not exist
09-16 17:10:59.241  3394  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 17:10:59.241  3394  3536 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 17:10:59.241  9907  9907 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 17:10:59.241  3394  3536 D ISSUE_DEBUG: InputChannelName : c086392 Starting com.test.thalitest
09-16 17:10:59.241  9907  9907 E Zygote  : accessInfo : 0
09-16 17:10:59.241  3394  4985 I ActivityManager: Start proc 9907:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-16 17:10:59.241  9907  9907 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-16 17:10:59.241  3394  4985 D InputDispatcher: Focused application set to: xxxx
09-16 17:10:59.241  9898  9898 D AndroidRuntime: Shutting down VM
09-16 17:10:59.241  3394  3860 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-16 17:10:59.261  3008  3008 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-16 17:10:59.281  9907  9907 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:10:59.281  9907  9907 D ActivityThread: Added TimaKeyStore provider
09-16 17:10:59.291  6562  6562 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 17:10:59.301  3394  3455 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3394
09-16 17:10:59.301  3394  3455 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 17:10:59.301  3394  3455 D PowerManagerService: mDisplayReady: false
09-16 17:10:59.301  3394  3455 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 17:10:59.301  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 17:10:59.301  6562  6562 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 17:10:59.301  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 17:10:59.301  3394  3455 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 17:10:59.301  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:10:59.301  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:10:59.311  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f8b483c00
09-16 17:10:59.301  3394  3551 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-16 17:10:59.311  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-16 17:10:59.311  3394  4054 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3394
09-16 17:10:59.311  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 17:10:59.311  3394  3541 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 17:10:59.311  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 17:10:59.311  3394  3541 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 17:10:59.311  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:10:59.311  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:10:59.311  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 17:10:59.311  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 17:10:59.311  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:10:59.311  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:10:59.311  3394  3541 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 17:10:59.311  3394  3541 D PowerManagerService: mDisplayReady: true
09-16 17:10:59.311  3394  3541 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-16 17:10:59.321  3394  4984 D ActivityManager:  Launching com.test.thalitest, updated priority
09-16 17:10:59.331  3394  4397 V WindowStateAnimator: Finishing drawing window Window{1df033c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-16 17:10:59.331  3394  3394 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-16 17:10:59.341  3008  3017 D libEGL  : eglTerminate EGLDisplay = 0x7f8b200e78
09-16 17:10:59.341  3008  3017 D libEGL  : eglTerminate EGLDisplay = 0x7f8b200e78
09-16 17:10:59.341  6219  6229 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-16 17:10:59.341  3008  3594 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-16 17:10:59.341  3394  3511 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-16 17:10:59.341  3008  4464 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-16 17:10:59.351  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fd0db1288
09-16 17:10:59.361  4310  4310 V ActivityThread: updateVisibility : ActivityRecord{1c4c682 token=android.os.BinderProxy@2b21695 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-16 17:10:59.361  4310  4310 D Launcher: onTrimMemory. Level: 20
09-16 17:10:59.371  3394  4500 V WindowStateAnimator: Finishing drawing window Window{c6d430e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-16 17:10:59.371  6562  6562 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 17:10:59.371  6562  6562 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 17:10:59.371  6562  6562 V ActivityThread: updateVisibility : ActivityRecord{5e15be9 token=android.os.BinderProxy@e626c52 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-16 17:10:59.371  3008  4344 I SurfaceFlinger: id=18 Removed VSBConnecti (7/12)
09-16 17:10:59.371  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:10:59.371  3008  3594 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/12)
09-16 17:10:59.381  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fd0db1288
09-16 17:10:59.381  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fd0db1258
09-16 17:10:59.381  3008  3594 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
09-16 17:10:59.381  3008  4464 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
09-16 17:10:59.411  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fd0db1288
09-16 17:10:59.451  3394  3394 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3394 (0x0)
09-16 17:10:59.461  3394  3394 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3394 (0x0)
09-16 17:10:59.461  3394  3394 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 17:10:59.461  3394  3394 D PowerManagerService: mDisplayReady: false
09-16 17:10:59.461  3394  3394 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 17:10:59.461  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 17:10:59.461  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f8b483c00
09-16 17:10:59.461  3394  3394 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 17:10:59.461  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-16 17:10:59.461  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 17:10:59.461  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:10:59.461  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:10:59.461  3394  3551 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-16 17:10:59.461  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 17:10:59.461  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 17:10:59.461  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:10:59.471  3394  3541 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 17:10:59.461  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:10:59.471  3394  3541 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 17:10:59.461  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 17:10:59.461  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 17:10:59.471  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:10:59.471  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:10:59.471  3394  3541 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 17:10:59.471  3394  3541 D PowerManagerService: mDisplayReady: true
09-16 17:10:59.471  3394  3541 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-16 17:10:59.551  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:10:59.641  6219  6219 I TrayVisibilityController: handleMessage : msg.what = 1
09-16 17:10:59.661  3394  4984 I WindowManager: Screenshot max retries 4 of Token{a9165cf ActivityRecord{4e0d62e u0 com.test.thalitest/.MainActivity t75}} appWin=Window{c086392 u0 d0 Starting com.test.thalitest} drawState=1
09-16 17:10:59.661  6219  6230 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-16 17:10:59.671  3394  3536 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 17:10:59.671  3394  3536 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-16 17:10:59.671  3394  3394 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 17:10:59.671  3394  3394 I KnoxTimeoutHandler: SD activityfalse
09-16 17:10:59.681  6219  6219 I Utils   : isCurrentUser current = 0, ownerId = 0
09-16 17:10:59.681  3394  3860 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-16 17:10:59.681  6219  6219 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-16 17:10:59.681  3394  6478 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 17:10:59.681  6219  6219 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-16 17:10:59.681  3394  6478 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 17:10:59.701  9907  9907 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 17:10:59.701  9907  9907 D RelationGraph: garbageCollect()
09-16 17:10:59.711  9907  9907 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-16 17:10:59.711  3394  3455 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:10:59.711  9907  9907 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-16 17:10:59.721  3394  3536 V WindowStateAnimator: Finishing drawing window Window{c086392 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-16 17:10:59.721  3394  3536 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 17:10:59.721  3394  3394 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 17:10:59.721  3394  3536 D ActivityManager: mDVFSHelper.release()
09-16 17:10:59.721  3394  3536 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{557bff8 u0 com.samsung.android.MtpApplication/.USBConnection t74} time:237003
09-16 17:10:59.721  3394  3394 I KnoxTimeoutHandler: SD activityfalse
09-16 17:10:59.731  3394  6478 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-16 17:10:59.731  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:10:59.731  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fd0db1168
09-16 17:10:59.741  3394  6478 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 17:10:59.741  9907  9907 D ResourcesManager: For user 0 new overlays fetched Null
09-16 17:10:59.741  3394  6478 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-16 17:10:59.741  3394  6478 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 17:10:59.741  3394  6478 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 17:10:59.751  9907  9907 I InjectionManager: Inside getClassLibPath caller 
09-16 17:10:59.761  9907  9907 D InjectionManager: InjectionManager
09-16 17:10:59.761  9907  9907 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-16 17:10:59.761  9907  9907 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-16 17:10:59.761  9907  9907 I InjectionManager: featureStore :{}
09-16 17:10:59.771  9907  9907 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-16 17:10:59.771  9907  9907 D RelationGraph: garbageCollect()
09-16 17:10:59.771  9907  9907 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-16 17:10:59.801  9907  9907 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-16 17:10:59.871  9907  9907 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-16 17:10:59.881  9907  9907 D ResourcesManager: For user 0 new overlays fetched Null
09-16 17:10:59.881  9907  9907 I InjectionManager: Inside getClassLibPath caller 
09-16 17:10:59.891  9907  9907 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-16 17:10:59.911  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:10:59.921  3394  3883 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-16 17:10:59.961  9907  9907 I cr_LibraryLoader: Time to load native libraries: 34 ms (timestamps 7212-7246)
09-16 17:10:59.961  9907  9907 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-16 17:10:59.991  3394  3815 V AlarmManager: Expired Alarm result :8
09-16 17:11:00.011  9907  9922 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-16 17:11:00.021  3394  3883 I MdnieScenarioControlService: mGameModeLauncher : false
09-16 17:11:00.021  3394  3883 I MdnieScenarioControlService: setUIMode
09-16 17:11:00.021  9907  9907 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d171308}
09-16 17:11:00.031  9907  9907 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-16 17:11:00.051  9907  9907 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-16 17:11:00.091  9907  9907 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-16 17:11:00.091  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:00.171  3394  3511 W ActivityManager: Activity pause timeout for ActivityRecord{4e0d62e u0 com.test.thalitest/.MainActivity t75}
09-16 17:11:00.251  9907  9907 D libEGL  : eglInitialize EGLDisplay = 0xffaebaac
09-16 17:11:00.271  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:00.321  3394  4255 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
09-16 17:11:00.321  3394  4255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-16 17:11:00.381  9907  9907 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-16 17:11:00.401  9907  9907 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-16 17:11:00.401  9907  9907 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-16 17:11:00.421  9907  9907 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-16 17:11:00.451  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:00.471  9907  9907 D Activity: performCreate Call Injection manager
09-16 17:11:00.471  9907  9907 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
09-16 17:11:00.481  9907  9907 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-16 17:11:00.491  9907  9907 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{d8f0e26 I.E...... R.....ID 0,0-0,0}
09-16 17:11:00.491  9907  9959 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-16 17:11:00.501  3394  4406 W WindowManager: Failed looking up window
09-16 17:11:00.501  3394  4406 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@53245fd does not exist
09-16 17:11:00.501  3394  4406 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-16 17:11:00.501  3394  4406 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-16 17:11:00.501  3394  4406 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-16 17:11:00.501  3394  4406 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-16 17:11:00.501  3394  4406 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-16 17:11:00.501  3394  4406 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-16 17:11:00.501  3394  3857 D ISSUE_DEBUG: InputChannelName : 66912f2 com.test.thalitest/com.test.thalitest.MainActivity
09-16 17:11:00.511  3394  4984 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-16 17:11:00.511  3394  4984 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 17:11:00.511  3394  3394 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 17:11:00.511  3394  3394 I KnoxTimeoutHandler: Shared devices show user statefalse
09-16 17:11:00.511  9907  9907 V ActivityThread: updateVisibility : ActivityRecord{217c014 token=android.os.BinderProxy@94cd5ee {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-16 17:11:00.521  9907  9922 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-16 17:11:00.541  9907  9907 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9907
09-16 17:11:00.541  3394  4984 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9907 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 17:11:00.541  3394  3871 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-16 17:11:00.541  3394  3871 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-16 17:11:00.551  3394  3871 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-16 17:11:00.551  3394  3871 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-16 17:11:00.561  3394  3871 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-16 17:11:00.561  9907  9907 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-16 17:11:00.561  3394  3871 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-16 17:11:00.571  3394  3871 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-16 17:11:00.571  3394  3871 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 17:11:00.581  3008  3008 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
09-16 17:11:00.601  9907  9959 D libEGL  : eglInitialize EGLDisplay = 0xdc63f7c4
09-16 17:11:00.601  9907  9959 I OpenGLRenderer: Initialized EGL, version 1.4
09-16 17:11:00.611  9907  9959 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-16 17:11:00.611  3394  4149 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3394
09-16 17:11:00.611  3394  4149 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 17:11:00.611  3394  4149 D PowerManagerService: mDisplayReady: false
09-16 17:11:00.611  3394  4149 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 17:11:00.611  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 17:11:00.611  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f8b483c00
09-16 17:11:00.611  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 17:11:00.611  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-16 17:11:00.611  3394  4149 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 17:11:00.611  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:11:00.611  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:11:00.611  3394  3551 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-16 17:11:00.611  3394  3536 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-16 17:11:00.611  3394  3536 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-16 17:11:00.631  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:00.631  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 17:11:00.631  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 17:11:00.631  3394  3541 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 17:11:00.631  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:11:00.631  3394  3541 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 17:11:00.631  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:11:00.631  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 17:11:00.631  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 17:11:00.631  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:11:00.631  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:11:00.631  3394  3541 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 17:11:00.631  3394  3541 D PowerManagerService: mDisplayReady: true
09-16 17:11:00.631  3394  3541 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-16 17:11:00.641  6219  6219 E CocktailBarPositionManager: Window direction: 0
09-16 17:11:00.641  6219  6219 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-16 17:11:00.651  9907  9907 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-16 17:11:00.671  3394  4397 V WindowStateAnimator: Finishing drawing window Window{66912f2 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-16 17:11:00.671  9907  9907 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-16 17:11:00.671  3394  6479 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-16 17:11:00.671  3394  4500 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3394
09-16 17:11:00.671  3394  3536 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 17:11:00.681  3394  3394 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 17:11:00.681  3394  3536 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s11ms (total +1s457ms)
09-16 17:11:00.681  3394  3454 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3394
09-16 17:11:00.681  3394  3536 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4e0d62e u0 com.test.thalitest/.MainActivity t75} time:237961
09-16 17:11:00.681  3394  3536 D ViewRootImpl: #3 mView = null
09-16 17:11:00.681  3008  3017 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
09-16 17:11:00.681  3394  3394 I KnoxTimeoutHandler: SD activityfalse
09-16 17:11:00.681  3008  3017 I SurfaceFlinger: id=20 Removed uhalitest (-2/11)
09-16 17:11:00.681  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fd0db1288
09-16 17:11:00.691  9907  9963 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-16 17:11:00.691  9907  9963 D libEGL  : eglInitialize EGLDisplay = 0xdabec3f4
09-16 17:11:00.691  3394  4984 V WindowStateAnimator: Finishing drawing window Window{66912f2 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-16 17:11:00.691  9907  9907 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@94cd5ee time:237975
09-16 17:11:00.721  9907  9963 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-16 17:11:00.761  9907  9907 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9907
09-16 17:11:00.811  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:00.831  3394  3394 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3394 (0x0)
09-16 17:11:00.831  3394  3394 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 17:11:00.831  3394  3394 D PowerManagerService: mDisplayReady: false
09-16 17:11:00.831  3394  3394 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 17:11:00.831  3394  3394 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 17:11:00.831  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 17:11:00.831  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 17:11:00.831  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:11:00.831  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:11:00.831  3394  3551 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-16 17:11:00.831  3394  3536 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-16 17:11:00.831  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f8b483c00
09-16 17:11:00.831  3394  3536 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-16 17:11:00.831  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-16 17:11:00.841  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 17:11:00.841  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 17:11:00.841  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:11:00.841  3394  3541 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 17:11:00.841  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:11:00.841  3394  3541 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 17:11:00.841  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 17:11:00.841  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 17:11:00.841  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:11:00.841  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:11:00.841  3394  3541 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 17:11:00.841  3394  3541 D PowerManagerService: mDisplayReady: true
09-16 17:11:00.841  3394  3541 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-16 17:11:00.851  6219  6219 E CocktailBarPositionManager: Window direction: 0
09-16 17:11:00.851  6219  6219 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-16 17:11:00.901  3394  3815 V AlarmManager: Expired Alarm result :4
09-16 17:11:00.901  3394  3815 V AlarmManager: Send whitelist package alarm :PendingIntent{b5bfee8: PendingIntentRecord{192ea78 com.samsung.android.app.aodservice broadcastIntent}}
09-16 17:11:00.901  3940  3940 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-16 17:11:00.901  3940  3940 D KeyguardUpdateMonitor: handleTimeUpdate
09-16 17:11:00.911  3940  3940 D Clock   : received broadcast android.intent.action.TIME_TICK
09-16 17:11:00.971  3940  3940 D DateView: received broadcast android.intent.action.TIME_TICK
09-16 17:11:00.991  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:00.991  9907  9907 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-16 17:11:01.001  7850  7850 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
09-16 17:11:01.001  7850  7850 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
09-16 17:11:01.011  4723  4723 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
09-16 17:11:01.011  4723  4723 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
09-16 17:11:01.011  3394  4196 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-16 17:11:01.011  3394  4196 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
09-16 17:11:01.021  3394  4196 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
09-16 17:11:01.021  3394  4196 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
09-16 17:11:01.021  3167  7721 D Sensorhubs: sendContextData: -72, 56, 1, 1
09-16 17:11:01.021  3394  4196 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
09-16 17:11:01.021  3394  4196 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-16 17:11:01.021  3394  4196 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
09-16 17:11:01.021  4723  4723 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@cba5d87, service=Device Physical Context Monitor
09-16 17:11:01.021  4723  4723 I AlpmModeManager: startAlpmMode : state  = BLANK
09-16 17:11:01.021  4723  4723 D DefaultClockView: Window showed. Time views updating
09-16 17:11:01.021  3394  4406 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3394
09-16 17:11:01.021  3394  4406 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 17:11:01.021  3394  4406 D PowerManagerService: mDisplayReady: false
09-16 17:11:01.031  3394  4406 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 17:11:01.031  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 17:11:01.031  4723  4723 D AODUpdatePositionController: updatePosition: direction[5] updatePosition: X[-45] Y[713] NewPositionTimer[56]
09-16 17:11:01.031  3394  4406 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 17:11:01.031  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f8b483c00
09-16 17:11:01.031  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 17:11:01.031  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-16 17:11:01.031  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:11:01.031  4723  4723 D DefaultClockView: LocalTime Pattern : HH:mm
09-16 17:11:01.031  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:11:01.031  3394  3551 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-16 17:11:01.041  4723  4723 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 17:11 time02: null ampm: null
09-16 17:11:01.031  3394  3536 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-16 17:11:01.031  3394  3536 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-16 17:11:01.041  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 17:11:01.041  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 17:11:01.041  3394  3541 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 17:11:01.041  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:11:01.041  3394  3541 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 17:11:01.041  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:11:01.041  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 17:11:01.041  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 17:11:01.041  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:11:01.041  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:11:01.041  3394  3541 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 17:11:01.041  3394  3541 D PowerManagerService: mDisplayReady: true
09-16 17:11:01.041  3394  3541 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-16 17:11:01.051  3167  3214 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
09-16 17:11:01.051  3394  3818 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
09-16 17:11:01.051  3394  3817 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 15, 11, 1,
09-16 17:11:01.051  3394  3817 D SensorHubManager: SendSensorHubData: send data = -63, 14, 15, 11, 1
09-16 17:11:01.051  6219  6219 E CocktailBarPositionManager: Window direction: 0
09-16 17:11:01.051  6219  6219 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-16 17:11:01.051  3167  3167 D Sensorhubs: sendContextData: -63, 14, 15, 11, 1
09-16 17:11:01.061  3394  3817 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
09-16 17:11:01.061  3394  3817 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
09-16 17:11:01.061  3394  3817 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
09-16 17:11:01.061  3394  3817 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
09-16 17:11:01.061  3394  3817 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
09-16 17:11:01.061  3394  3820 D SContextService: updateSContext() : event = Device Physical Context Monitor
09-16 17:11:01.061  4723  4723 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
09-16 17:11:01.061  4723  4723 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
09-16 17:11:01.061  4723  4723 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:pt., 16 wrz 17:11
09-16 17:11:01.061  4723  4723 I AODService.ClockTimer: startAlarm : TICK
09-16 17:11:01.071  3394  4054 V AlarmManager: Add whitelist package alarm :PendingIntent{920d1bb: PendingIntentRecord{192ea78 com.samsung.android.app.aodservice broadcastIntent}}
09-16 17:11:01.071  4723  4723 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
09-16 17:11:01.071  4723  4723 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
09-16 17:11:01.071  3394  4196 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
09-16 17:11:01.071  3394  4196 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
09-16 17:11:01.071  4723  4723 I AODService: onSContextChanged: AODScreenShown state is already true
09-16 17:11:01.071  4723  4723 D DefaultClockView: RootView invalidate()
09-16 17:11:01.071  3394  4397 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3394
09-16 17:11:01.101  9907  9970 D jxcore_app_log: JniHelper::setJavaVM(0xf4cf4000), pthread_self() = -631768784
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecd4cd6 added. We now have 1 listener(s)
09-16 17:11:01.111  9907  9970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
09-16 17:11:01.111  9907  9970 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-16 17:11:01.111  9907  9970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 17:11:01.111  9907  9970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-16 17:11:01.111  9907  9970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@716a32d added. We now have 1 listener(s)
09-16 17:11:01.111  9907  9970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 17:11:01.121  9907  9970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 17:11:01.121  9907  9970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-16 17:11:01.121  9907  9970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-16 17:11:01.121  9907  9970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-16 17:11:01.121  9907  9970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-16 17:11:01.121  9907  9970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 17:11:01.121  9907  9970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
09-16 17:11:01.131  9907  9970 D BluetoothAdapter: STATE_ON
09-16 17:11:01.131  9907  9970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-16 17:11:01.131  9907  9970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 17:11:01.131  9907  9970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:01.131  9907  9970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:01.131  9907  9970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 17:11:01.131  9907  9970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 17:11:01.131  9907  9970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 17:11:01.131  9907  9970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 17:11:01.131  9907  9970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 17:11:01.131  9907  9970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-16 17:11:01.131  9907  9970 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 17:11:01.131  9907  9970 I io.jxcore.node.LifeCycleMonitor: start: OK
09-16 17:11:01.141  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:01.141  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:01.161  9907  9907 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-16 17:11:01.171  4024  4024 D Recents : onTaskStackChanged
,09-16 17:11:01.171  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:01.181  4024  4024 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-16 17:11:01.191  4024  4024 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:01.221  3394  3394 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3394 (0x0)
,09-16 17:11:01.221  3394  3394 I libsuspend: !@autosuspend_wakeup_count_disable
,09-16 17:11:01.221  3394  3394 D PowerManagerService: mDisplayReady: false
,09-16 17:11:01.221  3394  3394 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 17:11:01.221  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 17:11:01.221  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f8b483c00
09-16 17:11:01.221  3394  3394 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,09-16 17:11:01.221  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-16 17:11:01.221  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 17:11:01.221  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:11:01.221  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:11:01.221  3394  3551 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-16 17:11:01.221  3394  3536 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-16 17:11:01.221  3394  3536 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-16 17:11:01.231  3394  3541 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 17:11:01.231  3394  3541 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 17:11:01.231  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 17:11:01.231  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,09-16 17:11:01.231  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 17:11:01.231  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:11:01.231  3394  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 17:11:01.231  3394  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 17:11:01.231  3394  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-16 17:11:01.231  3394  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 17:11:01.231  3394  3541 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 17:11:01.231  3394  3541 D PowerManagerService: mDisplayReady: true
,09-16 17:11:01.231  3394  3541 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-16 17:11:01.251  6219  6219 E CocktailBarPositionManager: Window direction: 0
09-16 17:11:01.251  6219  6219 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-16 17:11:01.351  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:01.531  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:01.531  9907  9971 W jxcore-log: Initializing JXcore engine
09-16 17:11:01.531  9907  9971 W jxcore-log: JXcore engine is ready
,09-16 17:11:01.551  5034  5034 E audit   : type=1400 msg=audit(1474038661.551:262): avc:  denied  { ioctl } for  pid=9971 comm="Thread-164" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2094 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-16 17:11:01.551  5034  5034 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-16 17:11:01.551  5034  5034 E audit   : type=1300 msg=audit(1474038661.551:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=da47a3c8 items=0 ppid=3178 pid=9971 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-164" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-16 17:11:01.551  5034  5034 E audit   : type=1327 msg=audit(1474038661.551:262): proctitle="com.test.thalitest"
09-16 17:11:01.551  5034  5034 E audit   : type=1320 msg=audit(1474038661.551:262): 
09-16 17:11:01.551  5034  5034 E audit   : type=1400 msg=audit(1474038661.551:263): avc:  denied  { ioctl } for  pid=9971 comm="Thread-164" path="socket:[15250]" dev="sockfs" ino=15250 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-16 17:11:01.551  5034  5034 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-16 17:11:01.551  5034  5034 E audit   : type=1300 msg=audit(1474038661.551:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=da47a3c8 items=0 ppid=3178 pid=9971 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-164" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-16 17:11:01.551  5034  5034 E audit   : type=1327 msg=audit(1474038661.551:263): proctitle="com.test.thalitest"
09-16 17:11:01.551  5034  5034 E audit   : type=1320 msg=audit(1474038661.551:263): 
,09-16 17:11:01.561  9907  9971 W jxcore-log: Starting JXcore engine
,09-16 17:11:01.591  9907  9971 W jxcore-log: Platform android
09-16 17:11:01.591  9907  9971 W jxcore-log: 
09-16 17:11:01.591  9907  9971 W jxcore-log: Process ARCH arm
09-16 17:11:01.591  9907  9971 W jxcore-log: 
,09-16 17:11:01.681  9907  9971 I jxcore-log: JXcore Cordova bridge is ready!
09-16 17:11:01.681  9907  9971 I jxcore-log: 
09-16 17:11:01.681  9907  9971 W jxcore-log: JXcore engine is started
,09-16 17:11:01.691  9907  9970 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-16 17:11:01.691  9907  9907 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-16 17:11:01.711  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:01.891  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:02.071  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:02.221  3394  3910 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/75_task.xml.bak
,09-16 17:11:02.251  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:02.431  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:02.611  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:02.681  3394  6478 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-16 17:11:02.791  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:02.971  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:03.151  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:03.331  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:03.511  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:03.691  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:03.871  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:04.051  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:04.231  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:04.411  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:04.591  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:04.771  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:04.951  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:05.131  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:05.311  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:05.491  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:05.671  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:05.761  3394  6478 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-16 17:11:05.851  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:06.031  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:06.211  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:06.391  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:06.491  3394  3982 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-16 17:11:06.491  3394  3982 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4329, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-16 17:11:06.491  3394  3982 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-230
09-16 17:11:06.491  3394  3982 D BatteryService: stay LED for fully charged
09-16 17:11:06.491  3394  3394 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-16 17:11:06.501  3394  3394 I MotionRecognitionService: Plugged
,09-16 17:11:06.501  3394  3394 D MotionRecognitionService:   cableConnection= 1
,09-16 17:11:06.501  3394  3394 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-16 17:11:06.501  3394  3394 D MotionRecognitionService: skip setTransmitPower. 
,09-16 17:11:06.501  3394  3865 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-16 17:11:06.501  3394  6478 D SSRM:n  : SIOP:: AP = 360, PST = 306 (W:6), CP = 264, LCD = 1
,09-16 17:11:06.501  3940  3940 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-16 17:11:06.511  3940  3940 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-16 17:11:06.511  3940  3940 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-16 17:11:06.521  5063  5063 D CommonServiceConfiguration: getStringValueSetting
,09-16 17:11:06.521  5023  5023 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-16 17:11:06.521  5023  5437 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-16 17:11:06.521  5063  5063 D BatteryMonitor: new battery level: 100
,09-16 17:11:06.521  4723  4723 D BatteryController: saveBatteryData : level[100], status[5]
,09-16 17:11:06.531  3394  6478 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-16 17:11:06.541  3940  3940 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-16 17:11:06.541  3940  3940 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-16 17:11:06.571  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:06.751  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:06.931  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:07.111  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:07.291  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:07.471  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:07.651  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:07.741  9907  9971 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 17:11:07.741  9907  9971 I jxcore-log: 
,09-16 17:11:07.741  9907  9971 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 17:11:07.741  9907  9971 I jxcore-log: 
,09-16 17:11:07.751  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:07.751  9907  9971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 17:11:07.751  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:07.751  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:07.751  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 17:11:07.751  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 17:11:07.751  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 17:11:07.751  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 17:11:07.751  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 17:11:07.761  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:07.761  9907  9971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 17:11:07.761  9907  9971 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 17:11:07.761  9907  9971 I jxcore-log: 
09-16 17:11:07.761  9907  9971 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 17:11:07.761  9907  9971 I jxcore-log: 
,09-16 17:11:07.831  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:07.921  9907  9971 D ExecuteNativeTests: Running unit tests
,09-16 17:11:07.951  9907  9971 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 17:11:07.951  9907  9971 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 added. We now have 2 listener(s)
09-16 17:11:07.951  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-16 17:11:07.951  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 17:11:07.951  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 17:11:07.951  9907  9971 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 17:11:07.951  9907  9971 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a added. We now have 2 listener(s)
09-16 17:11:07.951  9907  9971 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 17:11:07.961  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 17:11:07.971  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 17:11:07.981  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:07.981  9907  9971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 17:11:07.981  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:07.981  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:07.981  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 17:11:07.981  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 17:11:07.981  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 17:11:07.981  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 17:11:07.981  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 17:11:07.991  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:07.991  9907  9971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 17:11:07.991  9907  9971 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 17:11:07.991  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-16 17:11:07.991  9907  9971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 17:11:07.991  9907  9971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 17:11:07.991  9907  9971 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-16 17:11:08.001  9907  9971 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-16 17:11:08.001  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 17:11:08.001  9907  9971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 17:11:08.001  9907  9971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 17:11:08.001  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.001  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.001  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 17:11:08.001  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.001  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.001  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 17:11:08.001  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 17:11:08.001  9907  9971 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 removed from the list
09-16 17:11:08.001  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.001  9907  9971 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a removed from the list
09-16 17:11:08.001  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 17:11:08.001  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.001  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.001  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.001  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 17:11:08.001  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 17:11:08.001  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 17:11:08.001  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.001  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
,09-16 17:11:08.001  9907  9971 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-16 17:11:08.001  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.001  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 17:11:08.001  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.001  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.001  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 17:11:08.001  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.001  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.001  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 17:11:08.001  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.001  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.001  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.001  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.001  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 17:11:08.001  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.001  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 17:11:08.011  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 17:11:08.011  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.011  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
,09-16 17:11:08.011  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 17:11:08.011  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.011  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 17:11:08.011  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.011  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.011  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.011  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 17:11:08.011  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.011  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.011  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.011  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 17:11:08.011  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.011  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.011  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.011  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.011  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 17:11:08.011  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 17:11:08.011  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.011  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.011  9907  9971 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 17:11:08.011  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 17:11:08.021  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.021  9907  9971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 17:11:08.021  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:08.021  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:08.021  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 17:11:08.021  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 17:11:08.021  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 17:11:08.021  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 17:11:08.021  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 17:11:08.021  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.031  9907  9971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 17:11:08.031  9907  9971 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 17:11:08.031  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 17:11:08.031  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 17:11:08.031  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 17:11:08.031  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 17:11:08.031  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 17:11:08.031  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:08.031  9907  9971 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 17:11:08.031  9907  9971 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 17:11:08.041  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:08.041  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.041  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.041  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.051  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 17:11:08.051  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.051  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.051  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 17:11:08.051  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 17:11:08.051  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.051  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.061  9907  9971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-16 17:11:08.061  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.071  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.071  9907  9971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-16 17:11:08.071  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 17:11:08.071  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 17:11:08.071  9907  9971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 17:11:08.071  9907  9971 D BluetoothLeScanner: Start Scan
,09-16 17:11:08.081  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.081  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.081  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.091  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.101  5023  5036 D BtGatt.GattService: registerClient() - UUID=53c28c30-53aa-4dbf-b023-2ab9897e41c4
,09-16 17:11:08.151  5023  5134 D BtGatt.GattService: onClientRegistered() - UUID=53c28c30-53aa-4dbf-b023-2ab9897e41c4, clientIf=7
,09-16 17:11:08.151  9907  9917 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-16 17:11:08.151  5023  5179 D BtGatt.GattService: start scan with filters
,09-16 17:11:08.161  5023  5179 D BtGatt.GattService: getScanSettings
,09-16 17:11:08.181  5023  5179 D BtGatt.GattService: Is it foreground application = true
,09-16 17:11:08.181  5023  5179 D BtGatt.GattService: not a background application
,09-16 17:11:08.191  5023  5179 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-16 17:11:08.191  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:08.201  5023  5179 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 17:11:08.201  5023  5179 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 17:11:08.201  5023  5199 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
,09-16 17:11:08.201  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 17:11:08.201  5023  5199 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
09-16 17:11:08.201  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 17:11:08.201  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 17:11:08.201  5023  5190 D BtGatt.ScanManager: handling starting scan
,09-16 17:11:08.201  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 17:11:08.201  5023  5190 D BtGatt.ScanManager: isFilteringSupported
09-16 17:11:08.201  5023  5190 D BluetoothAdapter: enableStandAloneBleMode=
09-16 17:11:08.211  5023  5190 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.211  5023  5190 D BluetoothAdapter: STATE_ON
09-16 17:11:08.211  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 17:11:08.211  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 17:11:08.211  9907  9907 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 17:11:08.221  5023  5190 D BluetoothAdapter: STATE_ON
09-16 17:11:08.221  5023  5190 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.221  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 17:11:08.221  5023  5199 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 78
09-16 17:11:08.221  5023  5199 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-16 17:11:08.221  5023  5190 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d280ab
,09-16 17:11:08.221  3394  4716 V AlarmManager:  remove PendingIntent] PendingIntent{ea59fab: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.231  9907  9971 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 7
,09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24567311
09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
,09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
09-16 17:11:08.231  5023  5134 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-16 17:11:08.231  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.231  3394  4445 V AlarmManager:  remove PendingIntent] PendingIntent{c6d4608: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
09-16 17:11:08.231  5023  5199 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24567311
09-16 17:11:08.231  5023  5190 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
09-16 17:11:08.231  5023  5190 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-16 17:11:08.231  5023  5190 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-16 17:11:08.231  5023  5190 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-16 17:11:08.231  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.241  5023  5134 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-16 17:11:08.241  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.241  5023  5190 D BtGatt.ScanManager: Starting BLE batch scan
09-16 17:11:08.241  5023  5190 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-16 17:11:08.241  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.241  9907  9971 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 17:11:08.241  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.241  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 17:11:08.241  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.241  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 17:11:08.241  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 17:11:08.241  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 17:11:08.241  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 17:11:08.241  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 17:11:08.241  5023  5134 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-16 17:11:08.241  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.241  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 17:11:08.241  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 17:11:08.241  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.241  5023  5134 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-16 17:11:08.241  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.241  3394  3844 V AlarmManager:  remove PendingIntent] PendingIntent{80d71a1: PendingIntentRecord{9de9fc6 com.android.bluetooth broadcastIntent}}
09-16 17:11:08.241  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.241  9907  9971 D BluetoothLeScanner: Stop Scan
09-16 17:11:08.251  3394  4985 V AlarmManager:  remove PendingIntent] PendingIntent{19c8b87: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.251  5023  5037 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 17:11:08.251  5023  5037 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 17:11:08.251  5023  5037 D BtGatt.GattService: stopScan() - queue size =1
09-16 17:11:08.251  5023  5199 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-16 17:11:08.251  5023  5199 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
09-16 17:11:08.251  5023  5036 D BtGatt.GattService: unregisterClient() - clientIf=7
09-16 17:11:08.251  5023  5190 D BtGatt.ScanManager: filter size is 1
09-16 17:11:08.251  5023  5199 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 17:11:08.261  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
09-16 17:11:08.261  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.261  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
09-16 17:11:08.261  5023  5190 D BtGatt.ScanManager: delete FilterIndex - 3
09-16 17:11:08.261  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 17:11:08.261  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 17:11:08.261  3394  3857 V AlarmManager:  remove PendingIntent] PendingIntent{394bab4: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.261  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 17:11:08.261  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 17:11:08.261  5023  5199 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-16 17:11:08.261  5023  5199 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-16 17:11:08.261  5023  5134 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-16 17:11:08.261  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.261  5023  5190 D BtGatt.ScanManager: stopping BLe Batch
09-16 17:11:08.261  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 17:11:08.261  5023  5134 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-16 17:11:08.261  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.261  5023  5190 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-16 17:11:08.261  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.261  5023  5134 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
09-16 17:11:08.261  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.261  3394  4406 V AlarmManager:  remove PendingIntent] PendingIntent{26e86dd: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.261  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 17:11:08.271  3394  3455 V AlarmManager:  remove PendingIntent] PendingIntent{214f252: PendingIntentRecord{9de9fc6 com.android.bluetooth broadcastIntent}}
09-16 17:11:08.261  9907  9971 D BluetoothLeAdvertiser: stop advertising
,09-16 17:11:08.271  3394  4984 V AlarmManager:  remove PendingIntent] PendingIntent{22c5923: PendingIntentRecord{9de9fc6 com.android.bluetooth broadcastIntent}}
09-16 17:11:08.261  5023  5134 D BtGatt.GattService: current time is 245549661900
09-16 17:11:08.261  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.261  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 17:11:08.261  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 17:11:08.261  5023  5134 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -73, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-16 17:11:08.271  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 17:11:08.271  5023  5134 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-16 17:11:08.271  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 17:11:08.271  5023  5134 D ScanRecord: parseFromBytes
09-16 17:11:08.271  5023  5134 D ScanRecord: first manudata for manu ID
09-16 17:11:08.271  3394  3454 V AlarmManager:  remove PendingIntent] PendingIntent{41cce20: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.271  9907  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 17:11:08.271  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.271  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 17:11:08.271  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 17:11:08.271  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.271  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 17:11:08.271  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.271  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.271  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.271  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.271  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 17:11:08.271  9907  9971 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-16 17:11:08.281  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 17:11:08.281  9907  9907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 17:11:08.281  9907  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 17:11:08.281  3394  4149 V AlarmManager:  remove PendingIntent] PendingIntent{6b1c99b: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.281  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.291  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.291  9907  9907 D BluetoothAdapter: STATE_ON
09-16 17:11:08.291  3394  4054 V AlarmManager:  remove PendingIntent] PendingIntent{e024138: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.291  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.291  3394  4984 V AlarmManager:  remove PendingIntent] PendingIntent{250511: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.291  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 17:11:08.301  9907  9971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 17:11:08.301  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:08.301  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:08.301  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 17:11:08.301  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 17:11:08.301  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 17:11:08.301  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 17:11:08.301  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 17:11:08.301  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.301  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.301  3394  4196 V AlarmManager:  remove PendingIntent] PendingIntent{3748676: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.301  9907  9907 D BluetoothAdapter: STATE_ON
09-16 17:11:08.301  9907  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 17:11:08.301  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 17:11:08.301  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 17:11:08.301  9907  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 17:11:08.301  9907  9971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 17:11:08.301  9907  9971 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 17:11:08.301  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 17:11:08.301  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-16 17:11:08.301  3394  3454 V AlarmManager:  remove PendingIntent] PendingIntent{ed96477: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.311  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 17:11:08.311  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 17:11:08.311  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 17:11:08.311  3394  4255 V AlarmManager:  remove PendingIntent] PendingIntent{a9a9402: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.311  9907  9971 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 17:11:08.321  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.321  3394  4196 V AlarmManager:  remove PendingIntent] PendingIntent{78fff50: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.321  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.321  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.321  3394  4500 V AlarmManager:  remove PendingIntent] PendingIntent{ffa4549: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.321  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.321  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 17:11:08.321  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 17:11:08.321  9907  9971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 17:11:08.321  9907  9971 D BluetoothLeScanner: Start Scan
,09-16 17:11:08.321  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.331  3394  3857 V AlarmManager:  remove PendingIntent] PendingIntent{e21ee4e: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.331  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.331  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.331  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.331  3394  4985 V AlarmManager:  remove PendingIntent] PendingIntent{9626b6f: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.331  5023  5037 D BtGatt.GattService: registerClient() - UUID=d0b5aff4-7726-4fad-b089-ccc2c5ff1654
,09-16 17:11:08.331  3394  4445 V AlarmManager:  remove PendingIntent] PendingIntent{27dc07c: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.341  3394  3454 V AlarmManager:  remove PendingIntent] PendingIntent{c18ed05: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.341  3394  4406 V AlarmManager:  remove PendingIntent] PendingIntent{5b2a15a: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.351  3394  4984 V AlarmManager:  remove PendingIntent] PendingIntent{fd44f8b: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.351  3394  4985 V AlarmManager:  remove PendingIntent] PendingIntent{e246868: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.351  3394  3844 V AlarmManager:  remove PendingIntent] PendingIntent{5c05481: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.361  3394  3455 V AlarmManager:  remove PendingIntent] PendingIntent{9697926: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.361  3394  4149 V AlarmManager:  remove PendingIntent] PendingIntent{e365967: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.371  3394  4255 V AlarmManager:  remove PendingIntent] PendingIntent{90ba314: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.371  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:08.371  5023  5134 D BtGatt.GattService: onClientRegistered() - UUID=d0b5aff4-7726-4fad-b089-ccc2c5ff1654, clientIf=7
,09-16 17:11:08.371  9907  9918 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-16 17:11:08.371  5023  5510 D BtGatt.GattService: start scan with filters
,09-16 17:11:08.381  5023  5510 D BtGatt.GattService: getScanSettings
,09-16 17:11:08.381  5023  5510 D BtGatt.GattService: Is it foreground application = true
,09-16 17:11:08.381  5023  5510 D BtGatt.GattService: not a background application
,09-16 17:11:08.381  5023  5510 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-16 17:11:08.381  5023  5510 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 17:11:08.381  5023  5510 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 17:11:08.381  5023  5199 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-16 17:11:08.381  5023  5199 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
09-16 17:11:08.381  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 17:11:08.381  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-16 17:11:08.381  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 17:11:08.381  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 17:11:08.381  5023  5190 D BtGatt.ScanManager: handling starting scan
,09-16 17:11:08.391  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 17:11:08.391  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 17:11:08.391  5023  5190 D BluetoothAdapter: STATE_ON
09-16 17:11:08.391  5023  5190 D BluetoothAdapter: STATE_ON
09-16 17:11:08.391  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 17:11:08.391  5023  5199 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 79
09-16 17:11:08.391  5023  5199 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-16 17:11:08.391  3394  4054 V AlarmManager:  remove PendingIntent] PendingIntent{b1cb7bd: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.391  5023  5134 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-16 17:11:08.391  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.391  5023  5190 D BtGatt.ScanManager: set filter index= 4 for clientIf= 7
,09-16 17:11:08.391  5023  5190 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-16 17:11:08.391  5023  5190 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-16 17:11:08.391  5023  5190 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-16 17:11:08.401  5023  5134 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-16 17:11:08.401  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.401  5023  5190 D BtGatt.ScanManager: Starting BLE batch scan
09-16 17:11:08.401  5023  5190 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-16 17:11:08.401  9907  9971 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 17:11:08.401  5023  5134 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,09-16 17:11:08.401  9907  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 17:11:08.401  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.401  3394  3857 V AlarmManager:  remove PendingIntent] PendingIntent{46401b2: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 8
09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24567311
09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
,09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 17:11:08.401  3394  4397 V AlarmManager:  remove PendingIntent] PendingIntent{8c52503: PendingIntentRecord{9de9fc6 com.android.bluetooth broadcastIntent}}
09-16 17:11:08.401  5023  5134 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-16 17:11:08.401  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.401  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
,09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
,09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
,09-16 17:11:08.401  5023  5199 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24567311
09-16 17:11:08.411  9907  9907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 17:11:08.411  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 17:11:08.411  9907  9971 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-16 17:11:08.411  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.411  3394  4500 V AlarmManager:  remove PendingIntent] PendingIntent{89dc80: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.411  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-16 17:11:08.411  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.411  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 17:11:08.411  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 17:11:08.411  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.411  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.411  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.421  3394  3857 V AlarmManager:  remove PendingIntent] PendingIntent{6e212b9: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.421  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.421  9907  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,09-16 17:11:08.421  9907  9907 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-16 17:11:08.421  9907  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 17:11:08.421  3394  4984 V AlarmManager:  remove PendingIntent] PendingIntent{40c86fe: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.421  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-16 17:11:08.421  9907  9907 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 17:11:08.421  3394  4716 V AlarmManager:  remove PendingIntent] PendingIntent{eb0e5f: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.421  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 17:11:08.421  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 17:11:08.421  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-16 17:11:08.421  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 17:11:08.421  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.431  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.431  9907  9971 D BluetoothLeScanner: Stop Scan
09-16 17:11:08.431  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:08.431  5023  5036 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 17:11:08.431  5023  5036 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 17:11:08.431  5023  5036 D BtGatt.GattService: stopScan() - queue size =1
09-16 17:11:08.431  5023  5199 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-16 17:11:08.431  5023  5199 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
,09-16 17:11:08.431  5023  5199 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 17:11:08.431  3394  4716 V AlarmManager:  remove PendingIntent] PendingIntent{ef040ac: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.431  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
09-16 17:11:08.431  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
,09-16 17:11:08.431  5023  5199 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-16 17:11:08.431  5023  5199 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-16 17:11:08.431  5023  5179 D BtGatt.GattService: unregisterClient() - clientIf=7
09-16 17:11:08.431  5023  5190 D BtGatt.ScanManager: filter size is 1
09-16 17:11:08.431  5023  5190 D BtGatt.ScanManager: delete FilterIndex - 4
,09-16 17:11:08.431  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.431  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 17:11:08.431  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 17:11:08.431  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-16 17:11:08.431  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 17:11:08.431  5023  5134 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-16 17:11:08.431  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 17:11:08.431  5023  5190 D BtGatt.ScanManager: stopping BLe Batch
,09-16 17:11:08.441  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 17:11:08.441  5023  5134 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
,09-16 17:11:08.441  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.441  3394  4255 V AlarmManager:  remove PendingIntent] PendingIntent{1082175: PendingIntentRecord{9de9fc6 com.android.bluetooth broadcastIntent}}
09-16 17:11:08.441  5023  5190 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-16 17:11:08.441  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.441  5023  5134 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-16 17:11:08.441  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.441  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.441  3394  4500 V AlarmManager:  remove PendingIntent] PendingIntent{26150a: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.441  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.441  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.441  3394  4196 V AlarmManager:  remove PendingIntent] PendingIntent{a5c317b: PendingIntentRecord{9de9fc6 com.android.bluetooth broadcastIntent}}
09-16 17:11:08.441  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.441  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 17:11:08.441  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 17:11:08.441  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 17:11:08.441  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:08.441  9907  9907 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 17:11:08.451  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.451  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 17:11:08.451  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 17:11:08.451  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.451  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 17:11:08.451  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
,09-16 17:11:08.451  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.451  3394  3454 V AlarmManager:  remove PendingIntent] PendingIntent{5f26a57: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.451  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.451  9907  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 17:11:08.451  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 17:11:08.451  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 17:11:08.451  9907  9907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 17:11:08.451  9907  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 17:11:08.451  3394  4985 V AlarmManager:  remove PendingIntent] PendingIntent{ae7f944: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.461  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.461  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.461  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.461  3394  3844 V AlarmManager:  remove PendingIntent] PendingIntent{1500a2d: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.461  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 17:11:08.461  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.461  9907  9907 D BluetoothAdapter: STATE_ON
09-16 17:11:08.461  9907  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 17:11:08.461  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 17:11:08.461  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 17:11:08.461  9907  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.461  3394  3982 V AlarmManager:  remove PendingIntent] PendingIntent{dfc3b62: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.471  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 17:11:08.471  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 17:11:08.471  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 17:11:08.471  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.471  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.471  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.471  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.471  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.471  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 17:11:08.471  3394  3982 V AlarmManager:  remove PendingIntent] PendingIntent{e4954f3: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.471  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.481  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.481  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.481  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.481  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 17:11:08.481  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.481  9907  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 17:11:08.481  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 17:11:08.481  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 17:11:08.481  9907  9971 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-16 17:11:08.481  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 17:11:08.481  9907  9907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 17:11:08.481  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 17:11:08.491  9907  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 17:11:08.491  3394  4500 V AlarmManager:  remove PendingIntent] PendingIntent{3f5d4ba: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.491  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.491  3394  4445 V AlarmManager:  remove PendingIntent] PendingIntent{8586f6b: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.491  9907  9971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 17:11:08.491  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:08.491  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:08.491  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 17:11:08.491  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 17:11:08.491  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 17:11:08.491  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 17:11:08.491  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 17:11:08.491  9907  9907 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 17:11:08.491  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.491  3394  4716 V AlarmManager:  remove PendingIntent] PendingIntent{75c3ac8: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.501  9907  9971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 17:11:08.501  9907  9971 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 17:11:08.501  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 17:11:08.501  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-16 17:11:08.501  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 17:11:08.501  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 17:11:08.501  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 17:11:08.501  3394  4054 V AlarmManager:  remove PendingIntent] PendingIntent{69c8286: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.501  9907  9971 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 17:11:08.501  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.511  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:08.511  3394  4406 V AlarmManager:  remove PendingIntent] PendingIntent{ef4d89d: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.511  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.511  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.511  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:08.511  3394  3844 V AlarmManager:  remove PendingIntent] PendingIntent{eae4112: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.511  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.511  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 17:11:08.511  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 17:11:08.511  9907  9971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 17:11:08.511  9907  9971 D BluetoothLeScanner: Start Scan
,09-16 17:11:08.521  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.521  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.521  3394  4716 V AlarmManager:  remove PendingIntent] PendingIntent{df160e3: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.521  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.521  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.521  5023  5510 D BtGatt.GattService: registerClient() - UUID=75beedd5-9242-4eaf-aca5-6aea36b374ba
,09-16 17:11:08.521  3394  3844 V AlarmManager:  remove PendingIntent] PendingIntent{ddd9ae0: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.521  3394  4984 V AlarmManager:  remove PendingIntent] PendingIntent{5cb6199: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.551  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:08.561  5023  5134 D BtGatt.GattService: onClientRegistered() - UUID=75beedd5-9242-4eaf-aca5-6aea36b374ba, clientIf=7
,09-16 17:11:08.561  9907  9917 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-16 17:11:08.561  5023  5179 D BtGatt.GattService: start scan with filters
,09-16 17:11:08.561  5023  5179 D BtGatt.GattService: getScanSettings
,09-16 17:11:08.561  5023  5179 D BtGatt.GattService: Is it foreground application = true
,09-16 17:11:08.561  5023  5179 D BtGatt.GattService: not a background application
,09-16 17:11:08.571  5023  5179 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-16 17:11:08.581  5023  5179 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 17:11:08.581  5023  5179 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 17:11:08.581  5023  5199 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-16 17:11:08.581  5023  5199 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
,09-16 17:11:08.581  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 17:11:08.581  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-16 17:11:08.581  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 17:11:08.581  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 17:11:08.581  5023  5190 D BtGatt.ScanManager: handling starting scan
,09-16 17:11:08.591  5023  5190 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.591  5023  5190 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.591  5023  5134 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-16 17:11:08.591  3394  4149 V AlarmManager:  remove PendingIntent] PendingIntent{4ab5c5e: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.591  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.591  5023  5199 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 80
09-16 17:11:08.601  5023  5199 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-16 17:11:08.601  5023  5190 D BtGatt.ScanManager: set filter index= 5 for clientIf= 7
,09-16 17:11:08.601  5023  5190 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-16 17:11:08.601  5023  5190 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-16 17:11:08.601  5023  5190 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-16 17:11:08.601  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 17:11:08.601  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 17:11:08.601  9907  9907 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 17:11:08.601  5023  5134 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-16 17:11:08.601  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.611  3394  4716 V AlarmManager:  remove PendingIntent] PendingIntent{1cf283f: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.601  5023  5190 D BtGatt.ScanManager: Starting BLE batch scan
09-16 17:11:08.601  5023  5190 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-16 17:11:08.611  5023  5134 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-16 17:11:08.611  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 17:11:08.611  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 17:11:08.611  5023  5134 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-16 17:11:08.611  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.611  3394  4984 V AlarmManager:  remove PendingIntent] PendingIntent{331850c: PendingIntentRecord{9de9fc6 com.android.bluetooth broadcastIntent}}
09-16 17:11:08.611  9907  9971 I io.jxcore.node.ConnectionHelper: start: OK
09-16 17:11:08.611  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.611  3394  3857 V AlarmManager:  remove PendingIntent] PendingIntent{5e77e55: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.611  9907  9971 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 17:11:08.611  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-16 17:11:08.611  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 17:11:08.611  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 17:11:08.611  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 17:11:08.611  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 17:11:08.611  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 17:11:08.611  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-16 17:11:08.611  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 17:11:08.611  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 17:11:08.611  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 9
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24567311
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 17:11:08.621  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
,09-16 17:11:08.621  3394  4445 V AlarmManager:  remove PendingIntent] PendingIntent{6cce06a: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.621  5023  5199 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24567311
09-16 17:11:08.621  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.621  9907  9971 D BluetoothLeScanner: Stop Scan
09-16 17:11:08.631  5023  5179 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 17:11:08.631  5023  5179 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 17:11:08.631  5023  5179 D BtGatt.GattService: stopScan() - queue size =1
09-16 17:11:08.631  5023  5199 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
,09-16 17:11:08.631  5023  5199 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
09-16 17:11:08.631  5023  5199 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 17:11:08.631  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 4 => 4
09-16 17:11:08.631  3394  3982 V AlarmManager:  remove PendingIntent] PendingIntent{d98095b: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.631  5023  5037 D BtGatt.GattService: unregisterClient() - clientIf=7
09-16 17:11:08.631  5023  5190 D BtGatt.ScanManager: filter size is 1
09-16 17:11:08.631  5023  5190 D BtGatt.ScanManager: delete FilterIndex - 5
09-16 17:11:08.631  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.631  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 17:11:08.631  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-16 17:11:08.631  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 17:11:08.631  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 17:11:08.631  5023  5199 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 4 => 4
09-16 17:11:08.631  5023  5199 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-16 17:11:08.631  5023  5199 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-16 17:11:08.631  5023  5134 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-16 17:11:08.631  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.631  5023  5190 D BtGatt.ScanManager: stopping BLe Batch
09-16 17:11:08.631  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 17:11:08.631  5023  5134 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
,09-16 17:11:08.631  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 17:11:08.641  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.641  5023  5190 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-16 17:11:08.641  3394  4500 V AlarmManager:  remove PendingIntent] PendingIntent{3f7e5f8: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.641  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.641  9907  9971 D BluetoothLeAdvertiser: stop advertising
,09-16 17:11:08.641  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.641  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.641  3394  4255 V AlarmManager:  remove PendingIntent] PendingIntent{e6eaad1: PendingIntentRecord{9de9fc6 com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.641  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 17:11:08.641  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 17:11:08.641  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 17:11:08.641  5023  5134 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-16 17:11:08.641  5023  5134 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 17:11:08.641  3394  3982 V AlarmManager:  remove PendingIntent] PendingIntent{bd09936: PendingIntentRecord{9de9fc6 com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.641  9907  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 17:11:08.641  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 17:11:08.641  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 17:11:08.641  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 17:11:08.641  9907  9971 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 17:11:08.641  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.641  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.641  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.641  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.641  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 17:11:08.641  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.641  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.641  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.641  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 17:11:08.641  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 17:11:08.651  3394  3454 V AlarmManager:  remove PendingIntent] PendingIntent{c43e037: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.651  9907  9907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 17:11:08.651  9907  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 17:11:08.651  3394  3857 V AlarmManager:  remove PendingIntent] PendingIntent{66c48d3: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.651  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.661  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.661  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.661  3394  4985 V AlarmManager:  remove PendingIntent] PendingIntent{7d7c10: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.661  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 17:11:08.661  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.661  3394  4054 V AlarmManager:  remove PendingIntent] PendingIntent{59ae309: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.661  9907  9907 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.661  9907  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 17:11:08.661  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 17:11:08.661  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 17:11:08.661  9907  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 17:11:08.671  3394  4985 V AlarmManager:  remove PendingIntent] PendingIntent{615990e: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.671  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 17:11:08.671  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 17:11:08.671  3394  4054 V AlarmManager:  remove PendingIntent] PendingIntent{aa89f2f: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.671  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 17:11:08.671  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.681  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.681  9907  9971 D BluetoothLeAdvertiser: stop advertising
,09-16 17:11:08.681  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.681  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.681  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 17:11:08.681  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.681  3394  3454 V AlarmManager:  remove PendingIntent] PendingIntent{7a6493c: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.681  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.681  9907  9971 D BluetoothLeScanner: could not find callback wrapper
,09-16 17:11:08.681  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.681  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.681  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
,09-16 17:11:08.681  9907  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 17:11:08.681  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 17:11:08.681  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 17:11:08.681  9907  9971 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-16 17:11:08.681  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.681  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.681  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.681  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.681  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 17:11:08.681  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 17:11:08.681  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.681  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.681  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.681  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 17:11:08.681  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.681  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 17:11:08.691  3394  4054 V AlarmManager:  remove PendingIntent] PendingIntent{62cbd28: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.691  9907  9907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 17:11:08.691  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 17:11:08.691  9907  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 17:11:08.691  3394  3454 V AlarmManager:  remove PendingIntent] PendingIntent{79eea41: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.691  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 17:11:08.691  9907  9907 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 17:11:08.691  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 17:11:08.691  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 17:11:08.701  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.701  3394  4196 V AlarmManager:  remove PendingIntent] PendingIntent{94fbbe6: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.701  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.701  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.701  9907  9971 D BluetoothLeAdvertiser: wrapper is null
,09-16 17:11:08.701  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.701  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 17:11:08.701  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.701  3394  3454 V AlarmManager:  remove PendingIntent] PendingIntent{c174527: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.701  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.701  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.701  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 17:11:08.701  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.701  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.701  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-16 17:11:08.701  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.701  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.701  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.701  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.701  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.701  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.701  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.701  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.701  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.701  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.701  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.701  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.701  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.701  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 17:11:08.711  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 17:11:08.711  3394  3844 V AlarmManager:  remove PendingIntent] PendingIntent{2483d4: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.711  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.711  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.711  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.711  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.711  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.711  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 17:11:08.711  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.711  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.711  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.711  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.711  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 17:11:08.711  3394  4716 V AlarmManager:  remove PendingIntent] PendingIntent{9aee97d: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.711  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.711  9907  9971 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-16 17:11:08.711  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.711  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 17:11:08.711  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.711  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.711  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.711  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.711  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
,09-16 17:11:08.711  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.711  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.711  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 17:11:08.711  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.711  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.711  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.711  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.711  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 17:11:08.721  3394  3455 V AlarmManager:  remove PendingIntent] PendingIntent{e4bb072: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.721  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.721  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.721  9907  9971 D BluetoothLeAdvertiser: stop advertising
,09-16 17:11:08.721  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.721  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.721  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 17:11:08.721  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.721  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.721  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.721  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 17:11:08.721  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.721  3394  4149 V AlarmManager:  remove PendingIntent] PendingIntent{290cc3: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.721  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.721  9907  9971 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-16 17:11:08.721  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.721  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.721  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.721  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 17:11:08.721  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.721  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.721  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.721  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.721  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
,09-16 17:11:08.721  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.721  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.721  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.721  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 17:11:08.721  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.721  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 17:11:08.731  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.731  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.731  3394  3844 V AlarmManager:  remove PendingIntent] PendingIntent{5300940: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:08.731  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.731  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.731  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.731  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 17:11:08.731  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:08.731  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.731  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.731  9907  9971 D BluetoothLeScanner: could not find callback wrapper
,09-16 17:11:08.731  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.731  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.731  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.731  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 17:11:08.731  9907  9971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 17:11:08.731  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 17:11:08.731  9907  9971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 17:11:08.731  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 17:11:08.731  9907  9971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 17:11:08.731  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.731  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.731  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.731  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.731  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.731  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.731  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.731  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.731  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.731  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.731  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.731  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 17:11:08.731  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.731  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.731  3394  4149 V AlarmManager:  remove PendingIntent] PendingIntent{fc5a079: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.741  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 17:11:08.741  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.741  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.741  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.741  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.741  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.741  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 17:11:08.741  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.741  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.741  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.741  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.741  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.741  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.741  9907  9971 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 17:11:08.741  9907  9971 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 17:11:08.741  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-16 17:11:08.751  9907  9971 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 17:11:08.751  9907  9971 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 17:11:08.751  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 17:11:08.751  9907  9971 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-16 17:11:08.751  9907  9971 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 17:11:08.751  9907  9971 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-16 17:11:08.751  9907  9971 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 17:11:08.751  9907  9971 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 17:11:08.751  9907  9971 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-16 17:11:08.751  9907  9971 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 17:11:08.751  9907  9971 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 17:11:08.751  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-16 17:11:08.751  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-16 17:11:08.751  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-16 17:11:08.751  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-16 17:11:08.751  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-16 17:11:08.751  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-16 17:11:08.751  9907  9971 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-16 17:11:08.751  9907  9971 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 17:11:08.751  9907  9971 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-16 17:11:08.751  9907  9976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 228)
09-16 17:11:08.751  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.761  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.761  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.761  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.761  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.761  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.761  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-16 17:11:08.761  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.761  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.761  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.761  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.761  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.761  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.761  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.761  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.761  9907  9977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 228
09-16 17:11:08.761  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 17:11:08.761  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.761  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.761  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.761  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.761  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.761  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 17:11:08.761  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.761  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.761  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.761  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.761  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.761  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.761  9907  9971 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-16 17:11:08.771  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.771  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.771  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.771  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.771  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.771  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.771  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.771  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.771  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.771  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.771  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.771  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.771  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.771  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.771  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 17:11:08.771  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.771  9907  9976 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-16 17:11:08.771  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.771  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.771  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.771  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.771  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 17:11:08.771  9907  9976 D BluetoothSocket: connect(): myUserId = 0
09-16 17:11:08.771  9907  9976 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 17:11:08.771  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.771  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.771  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.771  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.771  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.771  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.771  9907  9971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-16 17:11:08.771  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.771  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.771  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.771  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.771  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.771  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.771  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.771  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.771  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.771  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.771  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.771  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.771  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.771  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.781  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 17:11:08.781  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.781  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.781  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.781  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.781  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.781  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 17:11:08.781  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.781  3394  4445 D SecContentProvider: insert(), uri = 2
09-16 17:11:08.781  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.781  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.781  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.781  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.781  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.781  9907  9971 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-16 17:11:08.781  9907  9971 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-16 17:11:08.781  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 17:11:08.781  5023  5401 W bt_btif : bta_dm_acl_change(), event : 2
09-16 17:11:08.781  9907  9971 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-16 17:11:08.781  9907  9971 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 17:11:08.781  9907  9971 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-16 17:11:08.781  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 17:11:08.781  9907  9971 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-16 17:11:08.781  9907  9971 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 17:11:08.781  9907  9971 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 17:11:08.781  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 17:11:08.781  9907  9971 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-16 17:11:08.781  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.781  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.781  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.781  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.781  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.781  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.781  3394  4406 V AlarmManager:  remove PendingIntent] PendingIntent{4a061be: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.781  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.781  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.781  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.781  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.781  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.781  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.781  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.781  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.781  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 17:11:08.791  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.791  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.791  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.791  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.791  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.791  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 17:11:08.791  3394  4255 V AlarmManager:  remove PendingIntent] PendingIntent{d05b21f: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.791  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.791  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.791  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.791  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.791  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.791  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.791  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.791  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.791  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.791  3394  4054 V AlarmManager:  remove PendingIntent] PendingIntent{aac796c: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:08.791  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.791  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.791  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.791  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.791  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.791  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.791  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.791  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.791  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.791  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.791  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.791  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.791  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.791  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.791  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.791  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.791  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.791  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.791  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.791  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.791  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.791  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.791  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.791  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.791  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.791  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.791  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 17:11:08.801  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.801  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.801  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.801  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.801  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.801  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 17:11:08.801  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.801  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.801  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.801  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.801  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.801  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.801  9907  9971 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 17:11:08.801  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 17:11:08.801  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-16 17:11:08.801  9907  9971 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-16 17:11:08.801  9907  9971 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 17:11:08.801  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 17:11:08.801  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 17:11:08.801  9907  9907 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-16 17:11:08.801  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.801  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 17:11:08.801  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 17:11:08.801  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-16 17:11:08.801  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.801  9907  9971 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-16 17:11:08.801  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.801  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.801  9907  9907 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 17:11:08.801  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 17:11:08.801  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 17:11:08.801  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 17:11:08.801  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 17:11:08.801  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.811  9907  9978 D BluetoothSocket: bindListen(): myUserId = 0
09-16 17:11:08.811  9907  9978 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 17:11:08.811  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.811  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.811  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.811  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.811  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.811  9907  9978 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 17:11:08.811  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.811  9907  9978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-16 17:11:08.811  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.811  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.811  9907  9978 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 17:11:08.811  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 17:11:08.811  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.811  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.811  9907  9971 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 17:11:08.811  9907  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 17:11:08.811  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.811  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 17:11:08.811  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 17:11:08.811  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.811  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.811  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.811  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.811  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.811  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 17:11:08.811  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.811  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.811  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.811  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.811  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.811  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 17:11:08.821  9907  9907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 17:11:08.821  9907  9907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 17:11:08.821  9907  9907 D BluetoothAdapter: STATE_ON
09-16 17:11:08.821  9907  9907 D BluetoothAdapter: STATE_ON
09-16 17:11:08.821  9907  9907 D BluetoothAdapter: STATE_ON
09-16 17:11:08.821  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 17:11:08.821  9907  9907 D BluetoothAdapter: STATE_ON
09-16 17:11:08.821  9907  9907 D BluetoothAdapter: STATE_ON
09-16 17:11:08.821  9907  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 17:11:08.821  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 17:11:08.821  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 17:11:08.831  9907  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.831  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.831  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.831  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 17:11:08.831  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.831  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.831  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.831  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.831  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.831  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 17:11:08.831  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.841  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.841  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.841  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.841  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.841  9907  9907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 17:11:08.841  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.841  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 17:11:08.841  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 17:11:08.841  9907  9971 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-16 17:11:08.841  9907  9971 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 17:11:08.841  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 17:11:08.841  9907  9971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 17:11:08.841  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.841  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.841  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.841  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.841  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.841  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 17:11:08.841  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.841  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.841  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.841  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.841  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.841  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 17:11:08.841  9907  9907 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 17:11:08.841  9907  9907 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 17:11:08.841  9907  9907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.851  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.851  9907  9907 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 17:11:08.851  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.851  9907  9907 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 17:11:08.851  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 17:11:08.851  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.851  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.851  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.851  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.851  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.851  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 17:11:08.851  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.851  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.851  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.851  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 17:11:08.851  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.851  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
,09-16 17:11:08.861  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 17:11:08.861  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.861  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.861  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.861  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.861  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.861  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.861  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 17:11:08.861  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.861  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.861  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.861  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.861  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.861  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 17:11:08.861  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 17:11:08.861  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.871  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.871  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.871  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.871  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 17:11:08.871  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 17:11:08.871  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.871  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.871  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.871  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.871  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.871  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
,09-16 17:11:08.871  9907  9971 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 17:11:08.871  9907  9971 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 17:11:08.871  9907  9971 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 17:11:08.871  9907  9971 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 17:11:08.871  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 17:11:08.871  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.871  9907  9971 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a7005 not in the list
09-16 17:11:08.871  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 17:11:08.871  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
09-16 17:11:08.871  9907  9971 D io.jxcore.node.ConnectivityMonitor: stop
09-16 17:11:08.871  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.871  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 17:11:08.871  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 17:11:08.871  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 17:11:08.871  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 17:11:08.871  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.871  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.871  9907  9971 D BluetoothLeAdvertiser: stop advertising
09-16 17:11:08.871  9907  9971 D BluetoothLeAdvertiser: wrapper is null
09-16 17:11:08.871  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 17:11:08.871  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 17:11:08.881  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.881  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.881  9907  9971 D BluetoothLeScanner: could not find callback wrapper
09-16 17:11:08.881  9907  9971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 17:11:08.881  9907  9971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 17:11:08.881  9907  9971 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41685a not in the list
,09-16 17:11:08.881  9907  9971 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-16 17:11:08.881  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 17:11:08.881  9907  9971 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-16 17:11:08.881  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 17:11:08.881  9907  9971 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-16 17:11:08.881  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-16 17:11:08.881  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-16 17:11:08.881  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-16 17:11:08.881  9907  9971 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-16 17:11:08.881  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 17:11:08.881  9907  9971 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-16 17:11:08.881  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 17:11:08.881  9907  9971 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-16 17:11:08.881  9907  9971 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-16 17:11:08.881  9907  9971 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-16 17:11:08.881  9907  9971 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-16 17:11:08.891  9907  9971 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-16 17:11:08.891  9907  9971 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-16 17:11:08.891  9907  9971 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-16 17:11:08.891  9907  9971 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-16 17:11:08.891  9907  9971 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 17:11:08.891  9907  9971 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f2ff3 added. We now have 2 listener(s)
09-16 17:11:08.891  9907  9971 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 17:11:08.891  9907  9971 D BluetoothAdapter: enable()
,09-16 17:11:08.891  9907  9971 D BluetoothAdapter: enable(): BT is already enabled..!
,09-16 17:11:08.901  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6c5c617 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a366578 5051:com.samsung.android.providers.context/u0a9}
,09-16 17:11:08.901  9907  9971 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-16 17:11:08.911  3394  4500 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-16 17:11:08.911  3394  4500 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
09-16 17:11:08.911  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:08.911  3394  4500 D WifiService: setWifiEnabled: true pid=9907, uid=10177
,09-16 17:11:08.911  3394  4500 W ActivityManager: Permission Denial: getCurrentUser() from pid=9907, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
,09-16 17:11:08.911  3394  3862 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-16 17:11:08.921  3394  3862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
09-16 17:11:08.921  3394  4500 W WifiService: Failed getting userId using ActivityManagerNative
09-16 17:11:08.921  3394  4500 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9907, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
09-16 17:11:08.921  3394  4500 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28247)
09-16 17:11:08.921  3394  4500 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
09-16 17:11:08.921  3394  4500 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
09-16 17:11:08.921  3394  4500 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-16 17:11:08.921  3394  4500 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
09-16 17:11:08.921  3394  4500 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,09-16 17:11:08.921  3394  3862 D WifiBigDataLog: init : 
,09-16 17:11:08.921  3394  4500 D SettingsProvider: isChangeAllowed() : name = wifi_on
,09-16 17:11:08.921  3394  3865 D WifiStateMachine: setFccChannel: channel = 0
,09-16 17:11:08.921  3394  3865 D WifiController: [FCC]setFccChannel() is called !!!
,09-16 17:11:08.921  9907  9971 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 17:11:08.921  3394  3865 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,09-16 17:11:08.921  9907  9971 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@da5a4b0 added. We now have 3 listener(s)
09-16 17:11:08.921  9907  9971 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 17:11:08.921  3394  3862 D WifiStateMachine: setFccChannelNative: channel = 0
,09-16 17:11:08.921  3394  3862 D WifiNative-wlan0: callSECApiInt - ID [230]
09-16 17:11:08.921  9907  9971 D BluetoothAdapter: STATE_ON
09-16 17:11:08.931  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{15a8a04 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a366578 5051:com.samsung.android.providers.context/u0a9}
,09-16 17:11:08.941  9907  9971 D BluetoothAdapter: STATE_ON
,09-16 17:11:08.941  9907  9971 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 17:11:08.941  9907  9971 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d4ef29 added. We now have 4 listener(s)
09-16 17:11:08.941  9907  9971 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 17:11:08.941  9907  9971 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 17:11:08.941  9907  9971 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@93e82ae added. We now have 5 listener(s)
09-16 17:11:08.941  9907  9971 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 17:11:08.951  3394  4397 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-16 17:11:08.951  3394  4397 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-16 17:11:08.951  3394  4397 D WifiService: setWifiEnabled: false pid=9907, uid=10177
,09-16 17:11:08.951  3394  4397 D SettingsProvider: isChangeAllowed() : name = wifi_on
,09-16 17:11:08.951  3394  3865 D WifiStateMachine: setFccChannel: channel = 0
09-16 17:11:08.951  3394  3865 D WifiController: [FCC]setFccChannel() is called !!!
09-16 17:11:08.951  9907  9971 D BluetoothAdapter: disable()
09-16 17:11:08.951  3394  3865 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
09-16 17:11:08.951  3394  3865 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
,09-16 17:11:08.961  3394  3865 D SecContentProvider: insert(), uri = 2
09-16 17:11:08.961  3394  3862 D WifiBigDataLog: getJsonFormat() - feature : ONOF
09-16 17:11:08.961  3394  3862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-16 17:11:08.971  3394  3862 D WifiBigDataLog: init : 
,09-16 17:11:08.971  3394  3862 D WifiStateMachine: setFccChannelNative: channel = 0
09-16 17:11:08.971  3394  3862 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-16 17:11:08.981  3394  3862 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-16 17:11:08.981  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cb22bed u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a366578 5051:com.samsung.android.providers.context/u0a9}
,09-16 17:11:08.981  3394  3862 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,09-16 17:11:08.991  3394  3982 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,09-16 17:11:08.991  3394  3534 D SecContentProvider: insert(), uri = 2
,09-16 17:11:08.991  5023  5130 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,09-16 17:11:08.991  3394  3862 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 17:11:08.991  3394  3862 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
09-16 17:11:08.991  5023  5130 D BluetoothAdapterProperties: Setting state to 13
09-16 17:11:08.991  5023  5130 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-16 17:11:08.991  5023  5130 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-16 17:11:08.991  5023  5130 D BluetoothAdapterService: updateAdapterState state is 13
09-16 17:11:08.991  9907  9971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 17:11:09.001  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:09.001  9907  9971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 17:11:09.001  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:09.001  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:09.001  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 17:11:09.001  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 17:11:09.001  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 17:11:09.001  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 17:11:09.001  9907  9971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 17:11:09.001  9907  9971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 17:11:09.001  9907  9971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 17:11:09.001  9907  9971 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 17:11:09.001  5023  5023 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-16 17:11:09.001  3394  3534 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
09-16 17:11:09.001  5023  5130 D BluetoothAdapterService: Autoconnection is available 
09-16 17:11:09.001  5023  5130 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-16 17:11:09.001  5023  5130 D BluetoothAdapterService: terminating service from this receiver
,09-16 17:11:09.011  3940  4129 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 17:11:09.011  3940  4129 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,09-16 17:11:09.011  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:09.011  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:09.021  3394  3857 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f9299e9 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a366578 5051:com.samsung.android.providers.context/u0a9}
,09-16 17:11:09.021  3394  3862 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,09-16 17:11:09.021  5023  5130 D BluetoothAdapterProperties: onBluetoothDisable()
,09-16 17:11:09.031  3940  3940 D BluetoothPbap: Proxy object disconnected
09-16 17:11:09.031  3940  3940 D PbapServerProfile: Bluetooth service disconnected
,09-16 17:11:09.031  5023  5130 W bt_btif : btif_dm_cancel_discovery
,09-16 17:11:09.031  3394  4716 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,09-16 17:11:09.031  3394  4149 D SecContentProvider: insert(), uri = 2
,09-16 17:11:09.031  5023  5130 I BluetoothAdapterState: Entering PendingCommandState
,09-16 17:11:09.031  3394  4255 V AlarmManager:  remove PendingIntent] PendingIntent{f86b66e: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:09.041  3394  3862 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,09-16 17:11:09.041  3394  3862 D SecContentProvider: insert(), uri = 2
,09-16 17:11:09.041  3394  4196 V AlarmManager:  remove PendingIntent] PendingIntent{f05610f: PendingIntentRecord{977159c com.android.bluetooth broadcastIntent}}
,09-16 17:11:09.041  5023  5134 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-16 17:11:09.041  5023  5134 D BluetoothAdapterProperties: Scan Mode:20
09-16 17:11:09.041  5023  5130 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,09-16 17:11:09.051  3394  3394 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-16 17:11:09.051  3394  3394 I InputMethodManagerService: [BT Setting State] State =13
,09-16 17:11:09.051  3940  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 17:11:09.051  3940  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-16 17:11:09.051  4345  4345 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,09-16 17:11:09.051  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:09.051  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 17:11:09.051  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:09.051  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:09.051  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 17:11:09.051  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 17:11:09.051  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 17:11:09.051  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 17:11:09.051  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 17:11:09.051  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:09.051  9907  9907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 17:11:09.061  3394  3394 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-16 17:11:09.061  3394  3394 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-16 17:11:09.061  3394  3394 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,09-16 17:11:09.061  7270  7270 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-16 17:11:09.061  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:09.071  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:09.071  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2f1eba5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d91327b 9610:com.android.settings/1000}
,09-16 17:11:09.071  3394  3862 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 17:11:09.071  3394  3862 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 17:11:09.071  3394  3862 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,09-16 17:11:09.071  5023  5130 E BluetoothServiceJni: disableBrEdrNative:
09-16 17:11:09.071  5023  5130 E bt_bluedroid: disable_bredr
,09-16 17:11:09.071  5023  5516 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 17:11:09.071  5023  5131 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-16 17:11:09.071  5023  5131 E bt_btif : BTA got event 0x1a03
09-16 17:11:09.071  5023  5532 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 17:11:09.071  5023  5532 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-16 17:11:09.071  5023  5401 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-16 17:11:09.071  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.071  5023  5533 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 17:11:09.071  5023  5533 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-16 17:11:09.081  3394  3862 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,09-16 17:11:09.081  3394  3862 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 17:11:09.081  9907  9976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 228)
09-16 17:11:09.081  3394  3862 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 17:11:09.081  3394  3862 E WifiNative-wlan0: do suspend true
,09-16 17:11:09.081  5023  5131 D IOP_DB_BT: db_close: nbr users 0
09-16 17:11:09.081  5023  5131 D IOP_DB_BT: db_close: free database
09-16 17:11:09.081  5023  5401 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
09-16 17:11:09.081  5023  5401 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
09-16 17:11:09.081  5023  5401 W bt_btif : bta_dm_acl_change(), event : 2
09-16 17:11:09.081  5023  5401 W bt_btif : bta_dm_acl_change(), event : 5
,09-16 17:11:09.091  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:09.091  3394  4149 V AlarmManager:  remove PendingIntent] PendingIntent{d6bcb7a: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:09.091  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:09.101  3394  3861 D WifiP2pService: InactiveState{ what=143375 }
09-16 17:11:09.101  3394  3861 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  9610  9610 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  3394  4623 V AlarmManager:  remove PendingIntent] PendingIntent{940ff2b: PendingIntentRecord{91c2207 android broadcastIntent}}
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  5023  5401 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 17:11:09.101  3152  3779 D CommandListener: Clearing all IP addresses on wlan0
,09-16 17:11:09.121  5023  5023 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
09-16 17:11:09.121  5023  5023 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
09-16 17:11:09.121  5023  5023 D ObexServerSockets: shutdown(block = true)
09-16 17:11:09.121  5023  5023 D ObexServerSockets: shutdown called from another thread - interrupt().
09-16 17:11:09.121  5023  5023 D ObexServerSockets: shutdown called from another thread - interrupt().
09-16 17:11:09.121  4336  5871 V NativeCrypto: Read error: ssl=0x7f6cb1ad00: I/O error during system call, Connection timed out
,09-16 17:11:09.121  3394  3871 E ConnectivityService: updateNetworkInfo()
09-16 17:11:09.131  3394  3871 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]
09-16 17:11:09.131  3394  3871 E ConnectivityService: updateNetworkInfo()
09-16 17:11:09.131  3394  3871 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
09-16 17:11:09.131  4336  5871 V NativeCrypto: SSL shutdown failed: ssl=0x7f6cb1ad00: I/O error during system call, Broken pipe
09-16 17:11:09.131  3394  3871 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 4
09-16 17:11:09.131  3394  3871 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 17:11:09.131  3394  3871 V NetworkStats: updateIfacesLocked()
09-16 17:11:09.131  3394  3871 V NetworkStats: performPollLocked(flags=0x1)
09-16 17:11:09.131  3394  4054 V AlarmManager:  remove PendingIntent] PendingIntent{4adef88: PendingIntentRecord{c4a55ce com.google.android.gms broadcastIntent}}
,09-16 17:11:09.131  5023  5023 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
,09-16 17:11:09.131  5023  5023 D BluetoothSdpJni: SDP Remove record success - handle: 1
09-16 17:11:09.131  5023  5023 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
09-16 17:11:09.131  5023  5023 D BluetoothSdpJni: SDP Remove record success - handle: 0
09-16 17:11:09.131  5023  5023 I BtOppRfcommListener: stopping Accept Thread
,09-16 17:11:09.131  5023  5516 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-16 17:11:09.141  3394  3871 D NetworkStatsRecorder: entry.iface is null
09-16 17:11:09.141  3394  3871 D NetworkStatsRecorder: entry.iface is null
09-16 17:11:09.141  3394  3871 D NetworkStatsRecorder: entry.iface is null
09-16 17:11:09.141  3394  3871 D NetworkStatsRecorder: entry.iface is null
,09-16 17:11:09.141  3394  3871 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 17:11:09.141  3394  3871 V NetworkStats: performPollLocked() took 13ms
,09-16 17:11:09.141  5023  5130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d280ab
09-16 17:11:09.141  5023  5134 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
09-16 17:11:09.141  3940  4203 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
09-16 17:11:09.141  3394  4984 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-16 17:11:09.141  3394  3871 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 17:11:09.141  3394  3871 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]
,09-16 17:11:09.151  3394  3862 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-16 17:11:09.151  3394  3871 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-16 17:11:09.151  3940  4129 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 17:11:09.151  3394  3871 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 17:11:09.151  3940  4129 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
09-16 17:11:09.151  3394  3871 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 17:11:09.151  4126  4126 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
09-16 17:11:09.151  3394  3861 D WifiP2pService: InactiveState{ what=131204 }
09-16 17:11:09.151  4126  4126 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
,09-16 17:11:09.151  3394  3871 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 17:11:09.151  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 17:11:09.151  3394  3861 D WifiP2pService: P2pEnabledState{ what=131204 }
09-16 17:11:09.151  3394  3871 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
09-16 17:11:09.151  3394  3871 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [] ]
09-16 17:11:09.151  3394  3861 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-16 17:11:09.151  3940  3940 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,09-16 17:11:09.151  3394  3871 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-16 17:11:09.151  3394  3871 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 17:11:09.151  3394  3394 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-16 17:11:09.151  3394  4619 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-16 17:11:09.151  3394  3871 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-16 17:11:09.151  3394  3896 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 17:11:09.151  3394  3896 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
09-16 17:11:09.151  3394  3862 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 17:11:09.151  3394  3896 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-16 17:11:09.151  3394  3896 D Ethernet: evalRequest
09-16 17:11:09.151  3394  3896 D Ethernet:   done
09-16 17:11:09.151  3394  3862 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 17:11:09.151  3394  3862 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-16 17:11:09.151  3394  3862 D WIFI    : evalRequest
09-16 17:11:09.151  3394  3862 D WIFI    :   needNetworkFor
09-16 17:11:09.151  3394  4984 D ConnectivityService: getVpnConfig > userId : 0
,09-16 17:11:09.151  9610  9610 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,09-16 17:11:09.161  3394  3862 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 17:11:09.161  3394  3862 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 17:11:09.161  3394  3862 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-16 17:11:09.161  3394  3862 D WIFI    : evalRequest
09-16 17:11:09.161  3394  3862 D WIFI    :   done
09-16 17:11:09.161  3394  3862 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 17:11:09.161  3394  3862 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 17:11:09.161  3394  3862 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-16 17:11:09.161  3394  3862 D WIFI_UT : evalRequest
09-16 17:11:09.161  3394  3862 D WIFI_UT :   done
,09-16 17:11:09.171  3394  3534 D EntConnectivity: Not allowed due to - mEnabled false
,09-16 17:11:09.171  3394  3394 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-16 17:11:09.171  3394  3394 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
,09-16 17:11:09.171  3394  3394 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
,09-16 17:11:09.181  3394  3394 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-16 17:11:09.181  3394  3869 I WifiHs20Service: Message received 5007
,09-16 17:11:09.181  3394  3394 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,09-16 17:11:09.181  9610  9610 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,09-16 17:11:09.181  9610  9610 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,09-16 17:11:09.181  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 17:11:09.181  3394  3860 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 17:11:09.181  3394  3860 D NtpTrustedTime: currentTimeMillis() cache hit
,09-16 17:11:09.181  4298  4298 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-16 17:11:09.201  3152  3779 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 17:11:09.201  4336  5871 E GCM     : Wifi connection closed with errorCode 20
,09-16 17:11:09.201  3394  4406 V AlarmManager:  remove PendingIntent] PendingIntent{302ea5d: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:09.201  5023  5134 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-16 17:11:09.201  5023  5134 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,09-16 17:11:09.201  3940  4129 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,09-16 17:11:09.211  3394  3536 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:09.211  3394  3536 I WifiDisplayAdapter: onP2pDisconnected
09-16 17:11:09.211  3394  3536 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-16 17:11:09.211  3394  3536 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-16 17:11:09.221  3394  3454 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2f1eba5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a366578 5051:com.samsung.android.providers.context/u0a9}
,09-16 17:11:09.221  3394  3861 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-16 17:11:09.231  3152  3779 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 17:11:09.231  3394  3871 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
09-16 17:11:09.231  3394  3871 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
09-16 17:11:09.231  3394  3871 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-16 17:11:09.241  9610  9610 D LocalBluetoothProfileManager: PANU : true
09-16 17:11:09.241  3394  3536 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-16 17:11:09.241  3394  3536 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
09-16 17:11:09.241  3394  3536 D WifiDisplayController: disconnect
09-16 17:11:09.241  3394  3536 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-16 17:11:09.241  3394  3394 D RttService: SCAN_AVAILABLE : 1
09-16 17:11:09.241  3394  3394 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-16 17:11:09.241  3394  3895 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-16 17:11:09.241  5023  5023 V BluetoothOppManager: cleanUp...
09-16 17:11:09.251  3394  3861 D SecContentProvider: insert(), uri = 2
,09-16 17:11:09.251  3394  3534 D EntConnectivity: Not allowed due to - mEnabled false
,09-16 17:11:09.251  3394  3861 D WifiP2pService: P2pDisablingState
,09-16 17:11:09.251  3394  3861 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 17:11:09.251  3394  3861 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 17:11:09.251  3394  3861 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-16 17:11:09.251  3394  3861 D WIFI_P2P: evalRequest
09-16 17:11:09.251  3394  3861 D WIFI_P2P:   done
09-16 17:11:09.251  3394  3861 D WifiP2pService: P2pDisablingState{ what=147458 }
,09-16 17:11:09.251  3394  3861 D WifiP2pService: p2p socket connection lost
09-16 17:11:09.251  3394  3861 D SecContentProvider: insert(), uri = 2
,09-16 17:11:09.251  3394  3862 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 17:11:09.251  3394  3861 D WifiP2pService: P2pDisabledState
09-16 17:11:09.251  3394  3862 E WifiNative-wlan0: do suspend true
,09-16 17:11:09.261  3394  3394 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
09-16 17:11:09.261  3394  3394 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,09-16 17:11:09.261  4166  4179 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
,09-16 17:11:09.261  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 17:11:09.261  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
,09-16 17:11:09.271  3394  3536 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
,09-16 17:11:09.271  3394  3561 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
09-16 17:11:09.271  3394  3536 I WifiDisplayAdapter: onP2pDisconnected
09-16 17:11:09.271  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,09-16 17:11:09.271  3394  3536 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-16 17:11:09.271  4166  4166 I PeopleDataManager: removeNotification
09-16 17:11:09.271  3394  3536 D IpRemoteDisplayController: WfdBridgeServer is already null
09-16 17:11:09.271  4166  4166 I NotificationParser: getNotiType:android,null
09-16 17:11:09.271  4166  4166 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 17:11:09.271  4166  4166 D PeopleDataManager: removeNotiInfo =null
,09-16 17:11:09.271  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:09.271  5023  5134 E BluetoothAdapterState: stateChangeCallback : 16
09-16 17:11:09.271  5023  5130 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
,09-16 17:11:09.281  3394  3861 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-16 17:11:09.281  3394  3861 D WifiP2pService: DefaultState{ what=143375 }
,09-16 17:11:09.281  3394  3561 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-16 17:11:09.291  3940  3940 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
09-16 17:11:09.291  3940  3940 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-16 17:11:09.291  3940  3940 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-16 17:11:09.291  3940  3940 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-16 17:11:09.291  3394  9986 I ApplicationPolicy: updateDataUsageMap
09-16 17:11:09.291  3940  3940 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-16 17:11:09.291  3394  3454 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-16 17:11:09.291  3394  3394 D Tethering: Tethering got CONNECTIVITY_ACTION
09-16 17:11:09.291  3394  3534 D Tethering: MasterInitialState.processMessage what=3
,09-16 17:11:09.291  3394  3394 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:09.291  3394  3394 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
09-16 17:11:09.291  3394  3394 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:09.291  3394  3394 I CLocInfoService: CLoinfo wifi false
,09-16 17:11:09.291  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 17:11:09.291  3394  3872 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-16 17:11:09.291  3394  3507 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-16 17:11:09.291  3394  3507 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:09.291  4298  4624 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-16 17:11:09.301  3940  3940 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-16 17:11:09.301  3940  3940 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-16 17:11:09.301  3394  3507 D GpsLocationProvider: updateNetworkState unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:09.301  4298  4624 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-16 17:11:09.301  3394  4251 V AlarmManager:  remove PendingIntent] PendingIntent{7c0961: PendingIntentRecord{1b1bc86 android broadcastIntent}}
,09-16 17:11:09.301  3394  3872 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-16 17:11:09.301  3394  4250 W SLocation: No Active Data Connection
09-16 17:11:09.301  3394  4250 W SLocation: No Active Data Connection
09-16 17:11:09.301  3394  4250 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:09.311  4298  4309 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-16 17:11:09.311  4298  4309 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-16 17:11:09.311  3394  3507 D TelephonyManager: getDataEnabled: retVal=true
,09-16 17:11:09.321  3394  3394 V MARsPolicyManager: DataConnection: false
,09-16 17:11:09.321  3394  3860 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 17:11:09.321  3394  3860 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 17:11:09.321  5063  5150 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
09-16 17:11:09.321  3394  3860 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-16 17:11:09.321  5063  5150 I CellLocationSupport: onCellLocationChanged
09-16 17:11:09.321  3394  3860 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 17:11:09.321  3394  3860 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 17:11:09.321  3394  3860 D NtpTrustedTime: currentTimeMillis() cache hit
,09-16 17:11:09.331  5063  5063 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
09-16 17:11:09.331  5063  5063 D PdnController: isSuspended [false] networktype [1]
09-16 17:11:09.331  3152  3779 E Netd    : netlink response contains error (No such file or directory)
,09-16 17:11:09.331  3394  3982 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:09.341  5063  5063 D PdnController: isPdnUp  [false] networktype [1]
09-16 17:11:09.341  5063  5063 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [false] 
09-16 17:11:09.341  3394  3871 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
09-16 17:11:09.341  3394  3871 D ConnectivityService: nai.networkMonitor.doQuit()
09-16 17:11:09.341  3394  3871 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 17:11:09.341  3394  3871 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
09-16 17:11:09.341  3394  3871 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
09-16 17:11:09.341  3394  3871 E ConnectivityService: updateNetworkInfo()
09-16 17:11:09.341  3394  3871 E ConnectivityService: updateNetworkInfo()
,09-16 17:11:09.341  4166  6338 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=84]
09-16 17:11:09.341  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 17:11:09.341  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 17:11:09.341  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 17:11:09.341  4166  4166 I PeopleDataManager: removeNotification
09-16 17:11:09.341  4166  4166 I NotificationParser: getNotiType:android,null
09-16 17:11:09.341  4166  4166 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 17:11:09.341  4166  4166 D PeopleDataManager: removeNotiInfo =null
,09-16 17:11:09.341  5063  5150 I CellLocationSupport: Block to update PANI information in non VoWIFI
09-16 17:11:09.341  5404  5404 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9f204c8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 17:11:09.341  5063  5150 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,09-16 17:11:09.341  3394  3857 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:09.351  5063  5150 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
09-16 17:11:09.351  5063  5150 D PdnController: isPdnUp  [false] networktype [0]
09-16 17:11:09.351  5063  5150 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,09-16 17:11:09.351  7270  7270 D SamsungIME: EngineType = SWIFTKEY
,09-16 17:11:09.351  9907  9907 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-16 17:11:09.351  5063  5150 D RegistrationManager: handleMessage(): 5
,09-16 17:11:09.351  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:09.351  5063  5150 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
09-16 17:11:09.351  5063  5150 D PdnController: isPdnUp  [false] networktype [11]
09-16 17:11:09.351  5063  5150 D RegistrationManager: setEPDGIPSecConnected [false]
09-16 17:11:09.351  5063  5150 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [false] IPAddresses [[]] DNSAddresses [[]] 
09-16 17:11:09.351  5063  5150 D RegistrationManager: isEPDGAvailable [false]
09-16 17:11:09.351  5063  5150 D CoreController: setState [DEREGISTERED]
,09-16 17:11:09.371  7270  7270 D SamsungIME: mNetworkChangeReceiver isWLANConnected : false
,09-16 17:11:09.371  9907  9907 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-16 17:11:09.371  3394  4255 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2f1eba5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{55ec69e 4336:com.google.android.gms.persistent/u0a21}
,09-16 17:11:09.371  4336  4336 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,09-16 17:11:09.381  3152  3779 D CommandListener: Clearing all IP addresses on wlan0
,09-16 17:11:09.381  5023  5130 D BtConfig.SecureMode: isSecureModeOn:false
,09-16 17:11:09.381  5023  5130 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-16 17:11:09.381  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:09.381  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 17:11:09.381  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:09.381  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:09.381  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 17:11:09.381  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 17:11:09.381  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 17:11:09.381  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 17:11:09.381  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 17:11:09.381  3152  3775 D EnterpriseController: netId is 0
09-16 17:11:09.381  3152  3775 D Netd    : getNetworkForDns: using netid 0 for uid 10002
,09-16 17:11:09.391  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:09.391  9907  9907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 17:11:09.391  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 17:11:09.391  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 17:11:09.391  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 17:11:09.391  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:09.391  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:09.391  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 17:11:09.391  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 17:11:09.391  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 17:11:09.391  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 17:11:09.391  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 17:11:09.391  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:09.391  9907  9907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 17:11:09.401  5063  5150 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
09-16 17:11:09.401  5063  5150 D RegistrationManager: getNetworkType [0]
09-16 17:11:09.401  5063  5150 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [false] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
,09-16 17:11:09.401  5063  5150 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
09-16 17:11:09.401  5063  5150 D CoreStackAdaptor2: ipList =  Null
09-16 17:11:09.401  4298  4624 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@c6acda5, selection=nullselectionArgs=null, sort=name ASC
09-16 17:11:09.401  5063  5150 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
09-16 17:11:09.401  5063  5150 D RegistrationManager: isPreconditionProperToGoOn
09-16 17:11:09.401  5063  5150 D RegistrationManager: isDeviceShutdown [false]
09-16 17:11:09.401  5063  5150 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
09-16 17:11:09.401  5063  5150 D RegistrationManager: isDmVoLTEUpdated [false]
09-16 17:11:09.401  5063  5150 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
09-16 17:11:09.401  5063  5150 D RegistrationManager: tryRegister : Not all preconditions are met!
,09-16 17:11:09.401  3394  3862 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-16 17:11:09.401  5023  5130 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-16 17:11:09.401  4126  4126 I wpa_supplicant: Blacklist: Clear (all) 
09-16 17:11:09.401  4126  4126 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,09-16 17:11:09.401  5023  5023 D HeadsetService: Received stop request...Stopping profile...
,09-16 17:11:09.411  3394  3394 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-16 17:11:09.411  4298  4624 D TelephonyProvider: query: match = 5
09-16 17:11:09.411  4298  4624 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
09-16 17:11:09.411  4563  9990 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
09-16 17:11:09.411  4563  9990 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
09-16 17:11:09.411  4563  9990 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-16 17:11:09.411  4563  9990 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-16 17:11:09.411  4563  9990 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-16 17:11:09.411  4563  9990 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
09-16 17:11:09.411  4563  9990 E         : 	at java.lang.Thread.run(Thread.java:818)
09-16 17:11:09.411  4563  9990 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 17:11:09.411  4563  9990 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
09-16 17:11:09.411  4563  9990 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
09-16 17:11:09.411  4563  9990 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
09-16 17:11:09.411  4563  9990 E         : 	... 9 more
09-16 17:11:09.411  4563  9990 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
09-16 17:11:09.411  4563  9990 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
09-16 17:11:09.411  4563  9990 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
09-16 17:11:09.411,  4563  9990 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
09-16 17:11:09.411  4563  9990 E         : 	... 24 more
09-16 17:11:09.411  4563  9990 E         : 
09-16 17:11:09.411  3394  3405 I art     : Background sticky concurrent mark sweep GC freed 152263(12MB) AllocSpace objects, 101(2MB) LOS objects, 23% free, 45MB/59MB, paused 2.406ms total 101.981ms
09-16 17:11:09.411  9610  9610 D BluetoothSap: Create BluetoothSap proxy object
09-16 17:11:09.411  4563  9990 E         : Unable to fetch advertisement frequency.
09-16 17:11:09.411  4563  9990 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
09-16 17:11:09.411  4563  9990 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-16 17:11:09.411  4563  9990 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-16 17:11:09.411  4563  9990 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-16 17:11:09.411  4563  9990 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
09-16 17:11:09.411  4563  9990 E         : 	at java.lang.Thread.run(Thread.java:818)
09-16 17:11:09.411  4563  9990 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 17:11:09.411  4563  9990 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
09-16 17:11:09.411  4563  9990 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
09-16 17:11:09.411  4563  9990 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
09-16 17:11:09.411  4563  9990 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
09-16 17:11:09.411  4563  9990 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
09-16 17:11:09.411  4563  9990 E         : 	... 9 more
09-16 17:11:09.411  4563  9990 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
09-16 17:11:0,9.411  4563  9990 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
09-16 17:11:09.411  4563  9990 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
09-16 17:11:09.411  4563  9990 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
09-16 17:11:09.411  4563  9990 E         : 	... 24 more
09-16 17:11:09.411  4563  9990 E         : 
09-16 17:11:09.411  3394  3394 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-16 17:11:09.411  3394  3394 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
09-16 17:11:09.411  3394  3394 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-16 17:11:09.411  3394  3869 I WifiHs20Service: Message received 5007
09-16 17:11:09.411  3394  3394 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
09-16 17:11:09.421  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 17:11:09.421  4298  4298 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
09-16 17:11:09.431  3394  3454 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2f1eba5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5e51b20 9523:com.sec.android.app.shealth:remote/u0a39}
09-16 17:11:09.451  5023  5130 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-16 17:11:09.451  3394  4196 V AlarmManager:  remove PendingIntent] PendingIntent{6701bf7: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:09.451  5023  5023 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
09-16 17:11:09.451  5023  5023 E HeadsetService: notifyProfileServiceStateChanged
,09-16 17:11:09.451  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:09.451  9610  9610 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-16 17:11:09.451  9610  9610 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,09-16 17:11:09.461  3152  3772 D Netd    : Iface p2p0 link up
,09-16 17:11:09.461  3394  3514 D Tethering: interfaceLinkStateChanged p2p0, true
,09-16 17:11:09.461  3394  3514 D Tethering: interfaceStatusChanged p2p0, true
,09-16 17:11:09.461  5063  5075 D PdnController: Interface Changed p2p0 link up
,09-16 17:11:09.471  3394  3394 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,09-16 17:11:09.471  3394  3394 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-16 17:11:09.471  3394  3869 I WifiHs20Service: Message received 5011
,09-16 17:11:09.471  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 17:11:09.471  3394  3872 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-16 17:11:09.471  3394  3394 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,09-16 17:11:09.471  4298  4606 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-16 17:11:09.471  4298  4606 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-16 17:11:09.481  3940  3940 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,09-16 17:11:09.481  3940  3940 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-16 17:11:09.481  3940  3940 I HotspotTile: Provider is not defined returning false
,09-16 17:11:09.481  3394  3872 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-16 17:11:09.481  3940  3940 D HotspotTile: onReceive : 0, 0
,09-16 17:11:09.481  3394  3394 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
,09-16 17:11:09.481  4166  4176 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
09-16 17:11:09.481  3394  3394 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
09-16 17:11:09.491  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 17:11:09.491  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 17:11:09.491  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 17:11:09.491  4166  4166 I PeopleDataManager: removeNotification
,09-16 17:11:09.491  4166  4166 I NotificationParser: getNotiType:android,null
09-16 17:11:09.491  4166  4166 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 17:11:09.491  4166  4166 D PeopleDataManager: removeNotiInfo =null
,09-16 17:11:09.491  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 17:11:09.491  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 17:11:09.491  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:09.491  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:09.491  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 17:11:09.491  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 17:11:09.491  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 17:11:09.491  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 17:11:09.491  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 17:11:09.491  3394  3454 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2f1eba5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d91327b 9610:com.android.settings/1000}
,09-16 17:11:09.501  4126  4126 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-16 17:11:09.501  4126  4126 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-16 17:11:09.501  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:09.501  9907  9907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 17:11:09.501  3152  3772 D Netd    : Iface wlan0 link up
,09-16 17:11:09.501  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 17:11:09.501  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
,09-16 17:11:09.511  5063  5350 D PdnController: Interface Changed wlan0 link up
,09-16 17:11:09.511  3394  3394 D BluetoothHeadset: unRegisterMessageListener : 11
,09-16 17:11:09.511  3394  3394 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
09-16 17:11:09.511  3394  3394 W BluetoothHeadset: Proxy not attached to service
09-16 17:11:09.511  3394  3394 I Telecom : BluetoothManager : unregister MessageListener
,09-16 17:11:09.511  3394  3862 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 17:11:09.511  9610  9610 D DockEventReceiver: finishStartingService: stopping service
,09-16 17:11:09.511  3394  3507 E GpsLocationProvider: No APN found to select.
,09-16 17:11:09.521  5023  5023 D A2dpService: Received stop request...Stopping profile...
,09-16 17:11:09.521  5023  5130 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-16 17:11:09.521  3940  3940 D HeadsetProfile: Bluetooth service disconnected
,09-16 17:11:09.521  5023  5473 D A2dpStateMachine: Exit Disconnected: -1
,09-16 17:11:09.531  5023  5130 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-16 17:11:09.531  9610  9610 D BluetoothPan: BluetoothPAN Proxy object connected
,09-16 17:11:09.531  9610  9610 D PanProfile: Bluetooth service connected
,09-16 17:11:09.541  5023  5023 D Avrcp   : unregisterContentObserver
09-16 17:11:09.541  5023  5023 D Avrcp   : removeOnActiveSessionsChangedListener
,09-16 17:11:09.541  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:09.541  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 17:11:09.541  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:09.541  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:09.541  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 17:11:09.541  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 17:11:09.541  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 17:11:09.541  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 17:11:09.541  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 17:11:09.541  5023  5130 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-16 17:11:09.541  5023  5023 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
09-16 17:11:09.541  5023  5023 E A2dpService: notifyProfileServiceStateChanged
,09-16 17:11:09.541  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:09.541  9610  9610 D BluetoothSap: Proxy object connected
09-16 17:11:09.541  9907  9907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 17:11:09.541  3394  3394 D BluetoothA2dp: Proxy object disconnected
09-16 17:11:09.541  5051  5051 D BluetoothA2dp: Proxy object disconnected
09-16 17:11:09.541  5023  5023 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 17:11:09.541  5023  5023 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
09-16 17:11:09.541  3940  3940 D BluetoothA2dp: Proxy object disconnected
09-16 17:11:09.541  3940  3940 D A2dpProfile: Bluetooth service disconnected
09-16 17:11:09.541  9610  9610 D SapProfile: Bluetooth service connected
09-16 17:11:09.541  5023  5023 V BluetoothAdapterState: isTurningOff()=true
09-16 17:11:09.541  5023  5023 V BluetoothAdapterState: isTurningOn()=false
09-16 17:11:09.541  5023  5023 V BluetoothAdapterState: isBleTurningOn()=false
09-16 17:11:09.541  5023  5023 V BluetoothAdapterState: isBleTurningOff()=false
09-16 17:11:09.541  5023  5130 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,09-16 17:11:09.541  9610  9610 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 17:11:09.541  9610  9610 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
09-16 17:11:09.541  5023  5130 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-16 17:11:09.541  5023  5130 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-16 17:11:09.551  5023  5130 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-16 17:11:09.551  5023  5130 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-16 17:11:09.551  5023  5130 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,09-16 17:11:09.561  9998  9998 E Zygote  : v2
09-16 17:11:09.561  9998  9998 I libpersona: KNOX_SDCARD checking this for 5010
09-16 17:11:09.561  9998  9998 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:09.561  9998  9998 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:09.561  9998  9998 E Zygote  : accessInfo : 0
09-16 17:11:09.561  9998  9998 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.intelligenceservice2 
,09-16 17:11:09.571  3394  4255 I ActivityManager: Start proc 9998:com.samsung.android.intelligenceservice2/5010 for broadcast-3 com.samsung.android.intelligenceservice2/com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor$BtConnectionReceiver
,09-16 17:11:09.581  3394  3507 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,09-16 17:11:09.581  5023  5023 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-16 17:11:09.581  5023  5023 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-16 17:11:09.581  5023  5023 D HeadsetProvider: cleanup
09-16 17:11:09.581  5023  5023 I HeadsetProvider: clearAllHeadsetSettings(0)
,09-16 17:11:09.591  9998  9998 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:09.591  9998  9998 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:09.601  5023  5023 D HidService: Received stop request...Stopping profile...
09-16 17:11:09.601  5023  5023 D HidService: Stopping Bluetooth HidService
09-16 17:11:09.601  5023  5023 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-16 17:11:09.601  5023  5023 W bt_btif : cleanup: HH disabling or disabled already, status = 0
09-16 17:11:09.601  5023  5023 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-16 17:11:09.601  5023  5023 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
09-16 17:11:09.601  5023  5023 E HidService: notifyProfileServiceStateChanged
,09-16 17:11:09.601  3394  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2f1eba5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e4b5a64 9998:com.samsung.android.intelligenceservice2/5010}
,09-16 17:11:09.601  3940  3940 D BluetoothInputDevice: Proxy object disconnected
09-16 17:11:09.601  3940  3940 D HidProfile: Bluetooth service disconnected
,09-16 17:11:09.611  4126  4126 I wpa_supplicant: Blacklist: Clear (all) 
09-16 17:11:09.611  4126  4126 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
09-16 17:11:09.611  5023  5023 D HealthService: Received stop request...Stopping profile...
09-16 17:11:09.611  5023  5023 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
09-16 17:11:09.611  5023  5023 E HealthService: notifyProfileServiceStateChanged
,09-16 17:11:09.611  5023  5023 D PanService: Received stop request...Stopping profile...
,09-16 17:11:09.611  5023  5023 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
09-16 17:11:09.611  5023  5023 E PanService: notifyProfileServiceStateChanged
09-16 17:11:09.611  3394  3394 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 17:11:09.611  3940  3940 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-16 17:11:09.611  3940  3940 D PanProfile: Bluetooth service disconnected
09-16 17:11:09.611  9610  9610 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 17:11:09.611  9610  9610 D PanProfile: Bluetooth service disconnected
09-16 17:11:09.611  5023  5023 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 17:11:09.611  5023  5023 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
09-16 17:11:09.611  5023  5023 V BluetoothAdapterState: isTurningOff()=true
,09-16 17:11:09.611  5023  5023 V BluetoothAdapterState: isTurningOn()=false
09-16 17:11:09.611  5023  5023 V BluetoothAdapterState: isBleTurningOn()=false
09-16 17:11:09.611  5023  5023 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 17:11:09.611  5023  5023 D BluetoothMapService: Received stop request...Stopping profile...
,09-16 17:11:09.611  9998  9998 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:09.621  9998  9998 D RelationGraph: garbageCollect()
,09-16 17:11:09.621  5023  5023 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
09-16 17:11:09.621  9998  9998 W ResourcesManager: getTopLevelResources: /system/priv-app/intelligenceservice2/intelligenceservice2.apk / 1.0 running in com.samsung.android.intelligenceservice2 rsrc of package com.samsung.android.intelligenceservice2
09-16 17:11:09.621  5023  5023 E BluetoothMapService: notifyProfileServiceStateChanged
,09-16 17:11:09.621  3940  3940 D BluetoothMap: Proxy object disconnected
09-16 17:11:09.621  3940  3940 D MapProfile: Bluetooth service disconnected
,09-16 17:11:09.621  5023  5023 D SapService: Received stop request...Stopping profile...
,09-16 17:11:09.621  5023  5023 V SapService: stop()
09-16 17:11:09.621  3394  3454 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:11:09.621  9998  9998 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-16 17:11:09.621  5023  5023 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
,09-16 17:11:09.621  5023  5023 E SapService: notifyProfileServiceStateChanged
09-16 17:11:09.621  3940  3940 D BluetoothSap: Proxy object disconnected
,09-16 17:11:09.621  3940  3940 D SapProfile: Bluetooth service disconnected
09-16 17:11:09.621  9610  9610 D BluetoothSap: Proxy object disconnected
09-16 17:11:09.621  9610  9610 D SapProfile: Bluetooth service disconnected
09-16 17:11:09.621  9998  9998 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:09.621  5023  5023 D BleAudioService: Received stop request...Stopping profile...
09-16 17:11:09.621  5023  5023 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
,09-16 17:11:09.621  5023  5495 E BleAudioStateMachine_R: Exit Disconnected: -1
09-16 17:11:09.621  5023  5494 E BleAudioStateMachine_L: Exit Disconnected: -1
09-16 17:11:09.621  5023  5023 E BleAudioService: notifyProfileServiceStateChanged
,09-16 17:11:09.631  3940  3940 D BluetoothLeAudio: Proxy object disconnected
09-16 17:11:09.631  3940  3940 D BleAudioProfile: Bluetooth service disconnected
09-16 17:11:09.631  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:09.631  5023  5023 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 17:11:09.631  5023  5023 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
,09-16 17:11:09.631  5023  5023 V BluetoothAdapterState: isTurningOff()=true
09-16 17:11:09.631  5023  5023 V BluetoothAdapterState: isTurningOn()=false
09-16 17:11:09.631  5023  5023 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 17:11:09.631  5023  5023 V BluetoothAdapterState: isBleTurningOff()=false
09-16 17:11:09.631  5023  5023 D BluetoothAdapterService: HID Host service will be diabled
09-16 17:11:09.631  9998  9998 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:09.631  5023  5023 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-16 17:11:09.631  5023  5023 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 17:11:09.631  5023  5023 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
,09-16 17:11:09.631  5023  5023 V BluetoothAdapterState: isTurningOff()=true
09-16 17:11:09.631  5023  5023 V BluetoothAdapterState: isTurningOn()=false
09-16 17:11:09.631  5023  5023 V BluetoothAdapterState: isBleTurningOn()=false
09-16 17:11:09.631  5023  5023 V BluetoothAdapterState: isBleTurningOff()=false
09-16 17:11:09.631  5023  5023 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-16 17:11:09.631  5023  5023 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-16 17:11:09.631  5023  5023 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 17:11:09.631  5023  5023 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
,09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isTurningOff()=true
09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isTurningOn()=false
09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isBleTurningOn()=false
09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isBleTurningOff()=false
09-16 17:11:09.641  5023  5023 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-16 17:11:09.641  5023  5023 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-16 17:11:09.641  5023  5023 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 17:11:09.641  5023  5023 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
09-16 17:11:09.641  9998  9998 W System  : ClassLoader referenced unknown path: /system/priv-app/intelligenceservice2/lib/arm64
09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isTurningOff()=true
09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isTurningOn()=false
,09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isBleTurningOn()=false
09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isBleTurningOff()=false
09-16 17:11:09.641  5023  5023 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 17:11:09.641  5023  5023 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
,09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isTurningOff()=true
09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isTurningOn()=false
09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isBleTurningOn()=false
09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isBleTurningOff()=false
09-16 17:11:09.641  5023  5023 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 17:11:09.641  5023  5023 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isTurningOff()=true
,09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isTurningOn()=false
09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isBleTurningOn()=false
09-16 17:11:09.641  5023  5023 V BluetoothAdapterState: isBleTurningOff()=false
09-16 17:11:09.641  5023  5023 V BleAudioService: [unregisterCallStateListener]
,09-16 17:11:09.641  9998  9998 D UserAnalysis.Provider: PlaceProvider onCreate()
09-16 17:11:09.641  5023  5023 W BtBleAudio.JNI: WARNING: cleanupNative(L364): Cleaning up  Ble audio left callback object##
09-16 17:11:09.641  5023  5023 W BtBleAudio.JNI: WARNING: cleanupNative(L382): Cleaning up Ble audio Interface...##
09-16 17:11:09.641  5023  5023 W BtBleAudio.JNI: WARNING: cleanupNative(L370): Cleaning up  Ble audio right callback object##
09-16 17:11:09.641  5023  5023 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
,09-16 17:11:09.651  5023  5130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d280ab
,09-16 17:11:09.651  3152  3772 D Netd    : Iface wlan0 link up
,09-16 17:11:09.651  3152  3772 D Netd    : Iface wlan0 link up
09-16 17:11:09.651  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
,09-16 17:11:09.651  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
09-16 17:11:09.651  5063  5075 D PdnController: Interface Changed wlan0 link up
09-16 17:11:09.651  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
,09-16 17:11:09.651  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
09-16 17:11:09.651  5023  5130 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
09-16 17:11:09.651  5063  5073 D PdnController: Interface Changed wlan0 link up
09-16 17:11:09.651  5023  5130 D BluetoothAdapterProperties: Setting state to 15
09-16 17:11:09.651  5023  5130 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-16 17:11:09.661  5023  5130 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-16 17:11:09.661  5023  5130 D BluetoothAdapterService: updateAdapterState state is 15
09-16 17:11:09.661  3152  3772 D Netd    : Iface p2p0 link down
,09-16 17:11:09.661  3394  3514 D Tethering: interfaceLinkStateChanged p2p0, false
09-16 17:11:09.661  3394  3514 D Tethering: interfaceStatusChanged p2p0, false
,09-16 17:11:09.661  9610  9621 D BluetoothPan: onBluetoothStateChange on: false
09-16 17:11:09.661  5023  5130 D BluetoothAdapterService: Autoconnection is available 
09-16 17:11:09.661  5023  5130 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
09-16 17:11:09.661  5023  5130 I BluetoothAdapterState: Entering BleOnState
,09-16 17:11:09.661  5063  5350 D PdnController: Interface Changed p2p0 link down
,09-16 17:11:09.671  9907  9917 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-16 17:11:09.671  9907  9917 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 17:11:09.671  9907  9917 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-16 17:11:09.671  9907  9917 D BluetoothLeAdvertiser: Exit stop advertising
,09-16 17:11:09.671  9907  9917 D BluetoothAdapter: There are no active google scan apps, stop scan
09-16 17:11:09.671  9907  9917 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-16 17:11:09.671  9907  9917 D BluetoothLeScanner: Exiting stopAllScan
09-16 17:11:09.671  3394  3534 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 17:11:09.671  3394  3534 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 17:11:09.671  3394  3534 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 17:11:09.671  3394  3534 D BluetoothPan: onBluetoothStateChange on: false
,09-16 17:11:09.671  4286  4296 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 17:11:09.671  4286  4296 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 17:11:09.671  4286  4296 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 17:11:09.671  5023  5179 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-16 17:11:09.671  9998  9998 D UserAnalysis.Secu: Key for secure DB is newly created
09-16 17:11:09.671  4298  4309 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 17:11:09.671  4298  4309 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 17:11:09.671  9998  9998 D UserAnalysis.SDBH: SecurePlaceDbHelper() 
09-16 17:11:09.671  9998  9998 D UserAnalysis: Create SecureDbHelper
09-16 17:11:09.671  4298  4309 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 17:11:09.671  3940  4414 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-16 17:11:09.671  5051  5062 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-16 17:11:09.681  9523  9534 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 17:11:09.681  9523  9534 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 17:11:09.681  9523  9534 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 17:11:09.681  9610  9622 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 17:11:09.681  9610  9622 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 17:11:09.681  9610  9622 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 17:11:09.681  3940  6548 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 17:11:09.681  3940  6548 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 17:11:09.681  3940  6548 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 17:11:09.681  3940  4822 D BluetoothSap: onBluetoothStateChange: up=false
,09-16 17:11:09.681  5051  5061 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 17:11:09.681  5051  5061 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 17:11:09.681  5051  5061 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 17:11:09.681  3940  3958 D BluetoothPan: onBluetoothStateChange on: false
,09-16 17:11:09.681  9610  9621 D BluetoothSap: onBluetoothStateChange: up=false
,09-16 17:11:09.681  9998  9998 D UserAnalysis.App: onCreate()
09-16 17:11:09.681  9998  9998 D InjectionManager: InjectionManager
,09-16 17:11:09.681  9998  9998 D InjectionManager: fillFeatureStoreMap com.samsung.android.intelligenceservice2
09-16 17:11:09.681  9998  9998 I InjectionManager: Constructor com.samsung.android.intelligenceservice2, Feature store :{}
,09-16 17:11:09.681  9998  9998 I InjectionManager: featureStore :{}
09-16 17:11:09.681  3394  3534 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 17:11:09.681  4336  4372 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 17:11:09.681  4336  4372 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 17:11:09.691  9998  9998 D UserAnalysis.App: no applications having user consent for prediction
09-16 17:11:09.691  4336  4372 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 17:11:09.691  4336  4372 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-16 17:11:09.691  4336  4372 D BluetoothLeScanner: Exiting stopAllScan
09-16 17:11:09.691  3394  3844 I ActivityManager: Killing 9287:com.samsung.android.sm/1000 (adj 15): DHA:empty #33
09-16 17:11:09.691  3940  3951 D BluetoothLeAudio: onBluetoothStateChange: up=false
,09-16 17:11:09.691  3940  3951 D BluetoothLeAudio: Unbinding service...
09-16 17:11:09.691  3940  4414 D BluetoothMap: onBluetoothStateChange: up=false
,09-16 17:11:09.691  3394  3844 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2f1eba5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6155d38 5023:com.android.bluetooth/1002}
,09-16 17:11:09.701  9998  9998 V PlaceDetection v1.0.29 : [PlaceDetection::stopService] Service stopped.
,09-16 17:11:09.711  9998  9998 V PlaceDetection v1.0.29 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-16 17:11:09.731 10012 10012 E Zygote  : v2
09-16 17:11:09.731 10012 10012 I libpersona: KNOX_SDCARD checking this for 10125
09-16 17:11:09.731 10012 10012 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:09.731 10012 10012 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 17:11:09.731  3394  4445 I ActivityManager: Start proc 10012:com.google.android.apps.maps/u0a125 for broadcast-3 com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-16 17:11:09.731 10012 10012 E Zygote  : accessInfo : 0
09-16 17:11:09.731 10012 10012 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.maps 
,09-16 17:11:09.741  3940  6548 D BluetoothPbap: onBluetoothStateChange: up=false
,09-16 17:11:09.741  3394  4397 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm, Auto Run ON
,09-16 17:11:09.751  3394  4716 V AlarmManager:  remove PendingIntent] PendingIntent{8f824cd: PendingIntentRecord{6c5182 com.samsung.android.intelligenceservice2 broadcastIntent}}
,09-16 17:11:09.751  3940  4415 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-16 17:11:09.751  5023  5130 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
09-16 17:11:09.761  3394  3394 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-16 17:11:09.761  5023  5130 D BluetoothAdapterProperties: Setting state to 16
09-16 17:11:09.761  3394  3394 I InputMethodManagerService: [BT Setting State] State =10
09-16 17:11:09.761  5023  5130 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-16 17:11:09.761  3394  3394 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
09-16 17:11:09.761  5023  5130 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-16 17:11:09.761  5023  5130 D BluetoothAdapterService: updateAdapterState state is 16
09-16 17:11:09.761  5023  5130 D BluetoothAdapterService: Autoconnection is available 
09-16 17:11:09.761  5023  5130 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
09-16 17:11:09.761  5023  5130 D BluetoothAdapterProperties: onBleDisable
09-16 17:11:09.761  3394  3534 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
,09-16 17:11:09.761  3940  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,09-16 17:11:09.761  3940  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
09-16 17:11:09.761  3394  3455 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,09-16 17:11:09.761  3394  4149 D SecContentProvider: insert(), uri = 2
,09-16 17:11:09.761  4345  4345 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,09-16 17:11:09.771  5023  5131 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-16 17:11:09.771  3394  4985 V AlarmManager:  remove PendingIntent] PendingIntent{b808093: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:09.771  5023  5131 E bt_btif : btif_vhci_sock_cleanup
09-16 17:11:09.771  5023  5130 I BluetoothAdapterState: Entering PendingCommandState
09-16 17:11:09.771  5023  5401 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-16 17:11:09.771  3394  3394 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-16 17:11:09.771  3394  3394 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
,09-16 17:11:09.771  3394  3394 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
09-16 17:11:09.771 10012 10012 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:09.771 10012 10012 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:09.771  7270  7270 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-16 17:11:09.781  9610  9610 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,09-16 17:11:09.781  9610  9610 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-16 17:11:09.791  5023  5134 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-16 17:11:09.791  5023  5134 D BluetoothAdapterProperties: Scan Mode:20
,09-16 17:11:09.801  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:09.801  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:09.801  3394  4445 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2f1eba5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{195b8d0 10012:com.google.android.apps.maps/u0a125}
,09-16 17:11:09.801  3940  4203 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
09-16 17:11:09.801  3394  3455 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-16 17:11:09.811  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:09.811  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:09.811  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:09.811 10012 10012 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:09.821 10012 10012 D RelationGraph: garbageCollect()
,09-16 17:11:09.821 10012 10012 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.google.android.apps.maps rsrc of package com.google.android.apps.maps
,09-16 17:11:09.821  3394  4255 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 17:11:09.821 10012 10012 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:09.831 10012 10012 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:09.831 10012 10012 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:09.841 10012 10012 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-16 17:11:09.961 10012 10024 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/testdata
09-16 17:11:09.961 10012 10024 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.maps/app_/testdata
,09-16 17:11:09.961 10012 10012 D InjectionManager: InjectionManager
09-16 17:11:09.961 10012 10012 D InjectionManager: fillFeatureStoreMap com.google.android.apps.maps
,09-16 17:11:09.961 10012 10012 I InjectionManager: Constructor com.google.android.apps.maps, Feature store :{}
09-16 17:11:09.961 10012 10012 I InjectionManager: featureStore :{}
,09-16 17:11:09.971  3394  4500 V AlarmManager:  remove PendingIntent] PendingIntent{bef40c9: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:09.971  5023  5134 I bt_hci  : shut_down
09-16 17:11:09.971  5023  5202 D bt_hwcfg: hw_epilog_process
,09-16 17:11:09.971  5023  5202 I bt_vendor: low_power_mode_cb
09-16 17:11:09.971 10012 10024 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/cache
,09-16 17:11:09.971  5023  5202 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-16 17:11:09.971  5023  5202 I bt_vendor: epilog_cb
09-16 17:11:09.971  5023  5202 I bt_hci  : epilog_finished_callback
,09-16 17:11:09.971  5023  5134 I bt_hci_h4: hal_close
,09-16 17:11:09.981  5023  5134 I bt_userial_vendor: device fd = 60 close
,09-16 17:11:09.981  3394  4406 V AlarmManager:  remove PendingIntent] PendingIntent{f1203ce: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:09.981  5023  5134 I bt_upio : upio_set_bluetooth_power(on: 0)
,09-16 17:11:09.991  3394  3982 V AlarmManager:  remove PendingIntent] PendingIntent{72892ef: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:09.991  5023  5131 D bt_stack_manager: event_shut_down_stack finished.
,09-16 17:11:09.991  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:09.991  5023  5134 E BluetoothAdapterState: stateChangeCallback : 0
09-16 17:11:09.991  5023  5130 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
09-16 17:11:09.991  5023  5130 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-16 17:11:10.001  5023  5023 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 17:11:10.001  3394  4196 V AlarmManager:  remove PendingIntent] PendingIntent{ce591fc: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:10.001  5023  5023 D BtGatt.GattService: Received stop request...Stopping profile...
09-16 17:11:10.001  5023  5023 D BtGatt.GattService: stop()
,09-16 17:11:10.001  5023  5023 D BtGatt.GattService: [GSIM LOG]: saveLogPref
09-16 17:11:10.001  5023  5023 D BtGatt.GattService: [GSIM LOG]: saveLogPref END
09-16 17:11:10.001  5023  5023 D BtGatt.GattService: cleanup binder
09-16 17:11:10.001  5023  5023 D BtGatt.AdvertiseManager: advertise clients cleared
,09-16 17:11:10.001  5023  5023 D BtGatt.ScanManager: cleanup
09-16 17:11:10.001  3394  4445 V AlarmManager:  remove PendingIntent] PendingIntent{5222085: PendingIntentRecord{9de9fc6 com.android.bluetooth broadcastIntent}}
,09-16 17:11:10.001  5023  5023 D BtGatt.ScanManager: cleanup handler
,09-16 17:11:10.001  5023  5023 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
,09-16 17:11:10.011  3394  4255 V AlarmManager:  remove PendingIntent] PendingIntent{14e8eda: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
09-16 17:11:10.001  5023  5023 E BtGatt.GattService: notifyProfileServiceStateChanged
09-16 17:11:10.011  3394  4397 V AlarmManager:  remove PendingIntent] PendingIntent{4956f0b: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:10.001  5023  5023 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 17:11:10.011  5023  5023 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
,09-16 17:11:10.011  5023  5023 V BluetoothAdapterState: isTurningOff()=false
09-16 17:11:10.011  5023  5023 V BluetoothAdapterState: isTurningOn()=false
,09-16 17:11:10.011  5023  5023 V BluetoothAdapterState: isBleTurningOn()=false
09-16 17:11:10.011  5023  5023 V BluetoothAdapterState: isBleTurningOff()=true
09-16 17:11:10.011  5023  5130 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
,09-16 17:11:10.011  5023  5130 D BluetoothAdapterProperties: Setting state to 10
09-16 17:11:10.011  5023  5130 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-16 17:11:10.011  5023  5130 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-16 17:11:10.011  5023  5130 D BluetoothAdapterService: updateAdapterState state is 10
09-16 17:11:10.011  5023  5130 D BluetoothAdapterService: Autoconnection is available 
09-16 17:11:10.011  5023  5130 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
,09-16 17:11:10.011  5023  5130 D BluetoothAdapterService: BT on, init HID DEV count : 0
09-16 17:11:10.011  5023  5130 I BluetoothAdapterState: Entering OffState
09-16 17:11:10.021  3394  3534 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-16 17:11:10.031  3394  4406 V AlarmManager:  remove PendingIntent] PendingIntent{8f7d1e8: PendingIntentRecord{7f4f05f com.android.bluetooth broadcastIntent}}
,09-16 17:11:10.031  5023  5023 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-16 17:11:10.031  5023  5023 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-16 17:11:10.031  5023  5023 I BluetoothServiceJni: cleanupNative: return from cleanup
09-16 17:11:10.031  5023  5131 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-16 17:11:10.041  5023  5023 I art     : System.exit called, status: 0
,09-16 17:11:10.041  5023  5023 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-16 17:11:10.061  3394  4397 I ActivityManager: Killing 9302:com.samsung.android.app.aodservice:settingui/u0a0 (adj 15): DHA:empty #33
,09-16 17:11:10.081  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e94001 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b0f4621 9754:com.enhance.gameservice/u0a111}
,09-16 17:11:10.081  3394  4054 I ActivityManager: Process com.android.bluetooth (pid 5023)(adj 0) has died(69,1745)
,09-16 17:11:10.081  3394  4054 D ActivityManager: isAutoRunBlockedApp:: com.android.bluetooth, Auto Run ON
,09-16 17:11:10.101 10012 10027 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-16 17:11:10.101  3394  3982 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.aodservice, Auto Run ON
,09-16 17:11:10.131 10040 10040 E Zygote  : v2
09-16 17:11:10.131 10040 10040 I libpersona: KNOX_SDCARD checking this for 1000
09-16 17:11:10.131 10040 10040 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:10.131 10040 10040 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 17:11:10.131  3394  3511 I ActivityManager: Start proc 10040:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,09-16 17:11:10.131 10040 10040 E Zygote  : accessInfo : 0
,09-16 17:11:10.141  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ea8db3d u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2933332 8624:com.google.android.talk/u0a117}
,09-16 17:11:10.151  3394  4054 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dccee39 9907:com.test.thalitest/u0a177}
,09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.151  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:10.161  4166  4179 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.apps.maps,id=10436,extra=Bundle[mParcelledData.dataSize=84]
09-16 17:11:10.161  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.apps.maps}]
09-16 17:11:10.161  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
,09-16 17:11:10.161  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 17:11:10.161  4166  4166 I PeopleDataManager: removeNotification
09-16 17:11:10.161  4166  4166 I NotificationParser: getNotiType:com.google.android.apps.maps,null
09-16 17:11:10.161  4166  4166 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.apps.maps,isEdgeNotification=false,key=null,removeAll=false
09-16 17:11:10.161  3394  4054 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6d6d19f 3394:system/1000}
09-16 17:11:10.161  4166  4166 D PeopleDataManager: removeNotiInfo =null
,09-16 17:11:10.171 10040 10040 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-16 17:11:10.171  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:10.171 10040 10040 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:10.181  3394  3394 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{feb86f6 4630:com.google.android.gms/u0a21}
,09-16 17:11:10.191  3394  4716 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{4e94001 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e8534f5 10040:com.sec.android.diagmonagent/1000}
,09-16 17:11:10.201  3394  3455 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{feb86f6 4630:com.google.android.gms/u0a21}
,09-16 17:11:10.201  4630  4630 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-16 17:11:10.201  4630  5582 I iu.UploadsManager: num queued entries: 0
,09-16 17:11:10.201  4630  5582 I iu.UploadsManager: num updated entries: 0
,09-16 17:11:10.201  4630  5582 I iu.SyncManager: NEXT; no task
09-16 17:11:10.201 10040 10040 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:10.211 10040 10040 D RelationGraph: garbageCollect()
,09-16 17:11:10.211 10040 10040 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package com.sec.android.diagmonagent
,09-16 17:11:10.211  3394  4985 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{feb86f6 4630:com.google.android.gms/u0a21}
09-16 17:11:10.211  3394  4984 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:11:10.211 10040 10040 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:10.211 10040 10040 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:10.221 10040 10040 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:10.221  3394  4985 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{55ec69e 4336:com.google.android.gms.persistent/u0a21}
,09-16 17:11:10.231 10040 10040 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,09-16 17:11:10.251  3152  3772 D Netd    : Iface wlan0 link down
,09-16 17:11:10.251  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, false
09-16 17:11:10.251  3394  3514 D Tethering: interfaceStatusChanged wlan0, false
09-16 17:11:10.251  5063  5073 D PdnController: Interface Changed wlan0 link down
09-16 17:11:10.251  5063  5073 D PdnController: Removed Interface [wlan0] For Network [1]
09-16 17:11:10.251  3394  3514 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.251 10040 10040 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-16 17:11:10.251  5063  5073 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
09-16 17:11:10.251  5063  5073 D PdnController: isSuspended [false] networktype [1]
09-16 17:11:10.251  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f58628a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e8534f5 10040:com.sec.android.diagmonagent/1000}
,09-16 17:11:10.251  3394  3514 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.251  5063  5073 D PdnController: isPdnUp  [false] networktype [1]
09-16 17:11:10.251  5063  5073 D PdnController: Ignore Notifying Same Result to LocalIP Registrants!
,09-16 17:11:10.311  4126  4126 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 17:11:10.341 10040 10040 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-16 17:11:10.351 10040 10040 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
09-16 17:11:10.351 10040 10040 D InjectionManager: InjectionManager
09-16 17:11:10.351 10040 10040 D InjectionManager: fillFeatureStoreMap com.sec.android.diagmonagent
09-16 17:11:10.351 10040 10040 I InjectionManager: Constructor com.sec.android.diagmonagent, Feature store :{}
09-16 17:11:10.351 10040 10040 I InjectionManager: featureStore :{}
09-16 17:11:10.351  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:10.351 10040 10040 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-16 17:11:10.351 10040 10040 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-16 17:11:10.351 10040 10040 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-16 17:11:10.351 10040 10040 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
09-16 17:11:10.351 10040 10040 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-16 17:11:10.351 10040 10040 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-16 17:11:10.351 10040 10040 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-16 17:11:10.381 10053 10053 E Zygote  : v2
09-16 17:11:10.381 10053 10053 I libpersona: KNOX_SDCARD checking this for 1000
09-16 17:11:10.381 10053 10053 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 17:11:10.381 10053 10053 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:10.381 10053 10053 E Zygote  : accessInfo : 0
09-16 17:11:10.381  3394  4445 I ActivityManager: Start proc 10053:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,09-16 17:11:10.401 10053 10053 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:10.401 10053 10053 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:10.401  3394  4445 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f58628a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b0f4621 9754:com.enhance.gameservice/u0a111}
,09-16 17:11:10.421  3394  4397 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{4e94001 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{76430fb 10053:com.sec.knox.switcher/1000}
,09-16 17:11:10.421  3394  4445 I ActivityManager: Killing 9344:com.samsung.android.scloud:contentsync/5009 (adj 15): DHA:empty #33
,09-16 17:11:10.431 10053 10053 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:10.431 10053 10053 D RelationGraph: garbageCollect()
,09-16 17:11:10.431 10053 10053 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package com.sec.knox.switcher
,09-16 17:11:10.431  3394  4445 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f58628a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{76430fb 10053:com.sec.knox.switcher/1000}
09-16 17:11:10.431  3394  3862 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-16 17:11:10.431  3394  3844 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:11:10.431 10053 10053 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:10.441 10053 10053 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:10.441  3394  3394 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,09-16 17:11:10.441  4166  6338 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
09-16 17:11:10.441  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 17:11:10.441  3394  3394 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
09-16 17:11:10.441  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 17:11:10.441  3394  3394 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
09-16 17:11:10.441  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 17:11:10.441  4166  4166 I PeopleDataManager: removeNotification
09-16 17:11:10.441  4166  4166 I NotificationParser: getNotiType:android,null
09-16 17:11:10.441  4166  4166 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 17:11:10.441  4166  4166 D PeopleDataManager: removeNotiInfo =null
,09-16 17:11:10.441  4166  6338 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041473,extra=Bundle[mParcelledData.dataSize=84]
09-16 17:11:10.441  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041473, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 17:11:10.441  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 17:11:10.441  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 17:11:10.441  4166  4166 I PeopleDataManager: removeNotification
09-16 17:11:10.441  4166  4166 I NotificationParser: getNotiType:android,null
09-16 17:11:10.441  4166  4166 D PeopleDataManager: removeNotiInfo: id =17041473,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 17:11:10.441  4166  4166 D PeopleDataManager: removeNotiInfo =null
,09-16 17:11:10.441 10053 10053 I InjectionManager: Inside getClassLibPath caller 
09-16 17:11:10.441  3394  3394 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-16 17:11:10.441  3394  3866 D HS20StateMachine: WIFI_STATE_DISABLED
09-16 17:11:10.441  3394  3394 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-16 17:11:10.441  3394  3866 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
09-16 17:11:10.441  3394  3869 I WifiHs20Service: Message received 5011
09-16 17:11:10.441  3394  3866 D HS20StateMachine: enter : DisablingState
09-16 17:11:10.451  3394  3868 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
09-16 17:11:10.451  3394  3866 D HS20StateMachine: enter : DisabledState
,09-16 17:11:10.451  3394  3394 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,09-16 17:11:10.451  3394  3872 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-16 17:11:10.451  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 17:11:10.451  3940  3940 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-16 17:11:10.451 10053 10053 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
09-16 17:11:10.451  3940  3940 I HotspotTile: Provider is not defined returning false
,09-16 17:11:10.451  3940  3940 D HotspotTile: onReceive : 1, 0
09-16 17:11:10.451  4298  4606 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-16 17:11:10.451  4298  4606 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-16 17:11:10.451  3394  3872 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-16 17:11:10.451 10053 10053 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
,09-16 17:11:10.451 10053 10053 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,09-16 17:11:10.451  4336  5107 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 17:11:10.461  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:10.461  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:10.471  3394  3455 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,09-16 17:11:10.471 10053 10053 D InjectionManager: InjectionManager
09-16 17:11:10.471 10053 10053 D InjectionManager: fillFeatureStoreMap com.sec.knox.switcher
,09-16 17:11:10.481 10053 10053 I InjectionManager: Constructor com.sec.knox.switcher, Feature store :{}
09-16 17:11:10.481 10053 10053 I InjectionManager: featureStore :{}
09-16 17:11:10.481 10053 10053 I usagelog: received in receiver
09-16 17:11:10.481 10053 10053 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,09-16 17:11:10.481 10053 10053 I KnoxUsageLogPro: premStatus:2
,09-16 17:11:10.481 10053 10053 I KnoxUsageLogPro: isEulaShown : false
,09-16 17:11:10.481 10053 10053 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
09-16 17:11:10.481 10053 10053 I usagelog: received in receiver
09-16 17:11:10.481 10053 10053 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-16 17:11:10.481 10053 10053 I KnoxUsageLogPro: premStatus:2
,09-16 17:11:10.491 10053 10053 I KnoxUsageLogPro: isEulaShown : false
09-16 17:11:10.491 10053 10053 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-16 17:11:10.501 10065 10065 E Zygote  : v2
09-16 17:11:10.501 10065 10065 I libpersona: KNOX_SDCARD checking this for 10012
09-16 17:11:10.501 10065 10065 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:10.501 10065 10065 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:10.501 10065 10065 E Zygote  : accessInfo : 0
,09-16 17:11:10.501 10065 10065 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.microsoft.office.onenote.connectionReceiverProcess 
,09-16 17:11:10.511  3394  3454 I ActivityManager: Start proc 10065:com.microsoft.office.onenote.connectionReceiverProcess/u0a12 for broadcast-5 com.microsoft.office.onenote/com.microsoft.bing.datamining.quasar.api.ConnectionChangeReceiver
,09-16 17:11:10.521  3394  3454 I ActivityManager: Killing 9357:com.osp.app.signin/u0a44 (adj 15): DHA:empty #33
,09-16 17:11:10.531  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:10.531 10065 10065 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:10.531 10065 10065 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:10.541  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9b78518 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dccee39 9907:com.test.thalitest/u0a177}
,09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:10.541  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:10.551  3394  3455 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{4e94001 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6412b71 10065:com.microsoft.office.onenote.connectionReceiverProcess/u0a12}
,09-16 17:11:10.551  3394  3982 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,09-16 17:11:10.561 10065 10065 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 17:11:10.561 10065 10065 D RelationGraph: garbageCollect()
,09-16 17:11:10.561 10065 10065 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.microsoft.office.onenote rsrc of package com.microsoft.office.onenote
,09-16 17:11:10.561  3394  4255 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 17:11:10.561 10065 10065 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:10.561 10065 10065 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:10.571 10065 10065 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:10.571  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f621d56 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a366578 5051:com.samsung.android.providers.context/u0a9}
,09-16 17:11:10.581 10065 10065 W System  : ClassLoader referenced unknown path: /system/app/OneNote/lib/arm
,09-16 17:11:10.581  3394  3507 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
,09-16 17:11:10.581  3394  3507 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
09-16 17:11:10.581  3394  3507 E libgps  : IPC Communication Error, ../../../../tmp/14804949_263294/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
09-16 17:11:10.581  3394  3507 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,09-16 17:11:10.581  3394  4397 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{83ae1d7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d91327b 9610:com.android.settings/1000}
,09-16 17:11:10.591  9610  9610 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 17:11:10.601 10065 10065 D InjectionManager: InjectionManager
,09-16 17:11:10.601 10065 10065 D InjectionManager: fillFeatureStoreMap com.microsoft.office.onenote
,09-16 17:11:10.601 10065 10065 I InjectionManager: Constructor com.microsoft.office.onenote, Feature store :{}
09-16 17:11:10.601 10065 10065 I InjectionManager: featureStore :{}
,09-16 17:11:10.611  3394  3982 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:10.611  3394  4406 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{83ae1d7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a366578 5051:com.samsung.android.providers.context/u0a9}
,09-16 17:11:10.621 10065 10065 I Process : Sending signal. PID: 10065 SIG: 9
09-16 17:11:10.621  9610  9610 D DockEventReceiver: finishStartingService: stopping service
,09-16 17:11:10.631  3394  4406 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{83ae1d7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{55ec69e 4336:com.google.android.gms.persistent/u0a21}
,09-16 17:11:10.631  4336  4336 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,09-16 17:11:10.641  3394  4716 I ActivityManager: Process com.microsoft.office.onenote.connectionReceiverProcess (pid 10065)(adj 0) has died(71,1745)
09-16 17:11:10.641  3394  3862 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-16 17:11:10.641  3394  4716 D ActivityManager: isAutoRunBlockedApp:: com.microsoft.office.onenote, Auto Run ON
,09-16 17:11:10.661 10079 10079 E Zygote  : v2
09-16 17:11:10.661 10079 10079 I libpersona: KNOX_SDCARD checking this for 10142
09-16 17:11:10.661 10079 10079 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:10.661 10079 10079 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:10.661  3394  3511 I ActivityManager: Start proc 10079:com.samsung.android.sm.policy/u0a142 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
,09-16 17:11:10.671  3394  3860 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-16 17:11:10.671 10079 10079 E Zygote  : accessInfo : 0
,09-16 17:11:10.671 10079 10079 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,09-16 17:11:10.681  3394  4149 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{83ae1d7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5e51b20 9523:com.sec.android.app.shealth:remote/u0a39}
,09-16 17:11:10.691  3394  3860 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-16 17:11:10.701 10079 10079 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:10.701 10079 10079 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:10.701  3394  4149 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{83ae1d7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d91327b 9610:com.android.settings/1000}
,09-16 17:11:10.701  9610  9610 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 17:11:10.701  9610  9610 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,09-16 17:11:10.711  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:10.721  3394  3982 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{4e94001 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c7ab8e2 10079:com.samsung.android.sm.policy/u0a142}
,09-16 17:11:10.731  3394  4149 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{83ae1d7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e4b5a64 9998:com.samsung.android.intelligenceservice2/5010}
,09-16 17:11:10.731 10079 10079 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:10.731 10079 10079 D RelationGraph: garbageCollect()
,09-16 17:11:10.731 10079 10079 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package com.samsung.android.sm.policy
,09-16 17:11:10.741  3394  4397 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:11:10.741 10079 10079 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:10.741 10079 10079 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:10.741 10079 10079 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:10.751 10092 10092 E Zygote  : v2
09-16 17:11:10.751 10092 10092 I libpersona: KNOX_SDCARD checking this for 1002
,09-16 17:11:10.751 10092 10092 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:10.751 10092 10092 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:10.751 10092 10092 E Zygote  : accessInfo : 0
,09-16 17:11:10.751 10079 10079 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm64
,09-16 17:11:10.761  3394  4149 I ActivityManager: Start proc 10092:com.android.bluetooth/1002 for broadcast-3 com.android.bluetooth/.opp.BluetoothOppReceiver
,09-16 17:11:10.771 10079 10079 D InjectionManager: InjectionManager
09-16 17:11:10.771 10079 10079 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.policy
,09-16 17:11:10.771 10079 10079 I InjectionManager: Constructor com.samsung.android.sm.policy, Feature store :{}
09-16 17:11:10.771 10079 10079 I InjectionManager: featureStore :{}
,09-16 17:11:10.781 10092 10092 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:10.781 10092 10092 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:10.791 10104 10104 E Zygote  : v2
09-16 17:11:10.791 10104 10104 I libpersona: KNOX_SDCARD checking this for 5005
,09-16 17:11:10.791 10104 10104 I libpersona: KNOX_SDCARD not a persona
09-16 17:11:10.791 10104 10104 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:10.791 10104 10104 E Zygote  : accessInfo : 0
,09-16 17:11:10.791 10104 10104 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
09-16 17:11:10.791  3394  4445 I ActivityManager: Start proc 10104:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,09-16 17:11:10.791  3394  4445 I ActivityManager: Killing 9392:com.android.defcontainer/u0a10 (adj 15): DHA:empty #33
,09-16 17:11:10.811  3394  4196 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{83ae1d7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{561c473 10092:com.android.bluetooth/1002}
,09-16 17:11:10.811 10104 10104 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-16 17:11:10.811 10104 10104 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:10.821  3394  4716 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,09-16 17:11:10.831 10092 10092 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:10.831 10092 10092 D RelationGraph: garbageCollect()
,09-16 17:11:10.831 10092 10092 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in com.android.bluetooth rsrc of package com.android.bluetooth
,09-16 17:11:10.831  3394  4984 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 17:11:10.831 10092 10092 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:10.831  3394  3857 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86ddf30 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe8d7a9 10104:com.samsung.android.app.FileShareClient/5005}
,09-16 17:11:10.831 10092 10092 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:10.841 10092 10092 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:10.851 10104 10104 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 17:11:10.851 10104 10104 D RelationGraph: garbageCollect()
,09-16 17:11:10.851 10104 10104 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,09-16 17:11:10.851  3394  3455 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:11:10.851 10104 10104 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:10.851 10104 10104 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:10.861 10104 10104 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:10.871 10104 10104 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,09-16 17:11:10.871 10092 10092 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-16 17:11:10.871 10104 10104 D InjectionManager: InjectionManager
09-16 17:11:10.871 10104 10104 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
,09-16 17:11:10.871 10104 10104 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{}
09-16 17:11:10.871 10104 10104 I InjectionManager: featureStore :{}
,09-16 17:11:10.871 10104 10104 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-16 17:11:10.871 10104 10104 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-16 17:11:10.891 10092 10092 D BtSettings.ProfileConfig: Adding GattService
,09-16 17:11:10.891 10092 10092 D BtSettings.ProfileConfig: Adding HeadsetService
09-16 17:11:10.891 10092 10092 D BtSettings.ProfileConfig: Adding A2dpService
09-16 17:11:10.891 10092 10092 D BtSettings.ProfileConfig: Adding HidService
09-16 17:11:10.891  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:10.891 10092 10092 D BtSettings.ProfileConfig: Adding HealthService
09-16 17:11:10.891 10092 10092 D BtSettings.ProfileConfig: Adding PanService
,09-16 17:11:10.891 10092 10092 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-16 17:11:10.891 10092 10092 D BtSettings.ProfileConfig: Adding SapService
09-16 17:11:10.891 10092 10092 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-16 17:11:10.891 10092 10092 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-16 17:11:10.891 10092 10092 D BtSettings.ProfileConfig: Adding BleAudioService
09-16 17:11:10.891 10092 10092 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-16 17:11:10.901  3394  4054 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.gatt.GattService
09-16 17:11:10.901  3394  4054 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,09-16 17:11:10.901  3394  4054 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 17:11:10.901  3394  4054 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 17:11:10.901  3394  4054 D SettingsProvider: selectionArgs: false
09-16 17:11:10.901  3394  4054 D SettingsProvider: selectionArgs: 1002
,09-16 17:11:10.901  3394  4054 D SettingsProvider: ret = -1
,09-16 17:11:10.901  3394  3982 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-16 17:11:10.901 10104 10104 D FileShare-Client: Outbound.stopDelayTimer - 
,09-16 17:11:10.901  3394  3982 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 17:11:10.901  3394  3982 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,09-16 17:11:10.901  3394  3982 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 17:11:10.901  3394  3982 D SettingsProvider: selectionArgs: false
,09-16 17:11:10.901  3394  3982 D SettingsProvider: selectionArgs: 1002
09-16 17:11:10.901  3394  3982 D SettingsProvider: ret = -1
,09-16 17:11:10.911  3394  4716 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-16 17:11:10.911  3394  4716 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 17:11:10.911  3394  4716 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 17:11:10.911  3394  4716 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 17:11:10.911  3394  4716 D SettingsProvider: selectionArgs: false
09-16 17:11:10.911  3394  4716 D SettingsProvider: selectionArgs: 1002
,09-16 17:11:10.911  3394  4716 D SettingsProvider: ret = -1
,09-16 17:11:10.911  3394  4500 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hid.HidService
09-16 17:11:10.911  3394  4500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 17:11:10.911  3394  4500 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 17:11:10.911  3394  4500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 17:11:10.911  3394  4500 D SettingsProvider: selectionArgs: false
,09-16 17:11:10.911  3394  4500 D SettingsProvider: selectionArgs: 1002
09-16 17:11:10.911  3394  4500 D SettingsProvider: ret = -1
,09-16 17:11:10.911  3394  4445 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-16 17:11:10.911  3394  4445 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 17:11:10.921  3394  4445 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,09-16 17:11:10.911  3394  4445 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 17:11:10.911  3394  4445 D SettingsProvider: selectionArgs: false
09-16 17:11:10.911  3394  4445 D SettingsProvider: selectionArgs: 1002
09-16 17:11:10.921  3394  4445 D SettingsProvider: ret = -1
,09-16 17:11:10.921  3394  3844 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.pan.PanService
09-16 17:11:10.921  3394  3844 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-16 17:11:10.921  3394  3844 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 17:11:10.921  3394  3844 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 17:11:10.921  3394  3844 D SettingsProvider: selectionArgs: false
,09-16 17:11:10.921  3394  3844 D SettingsProvider: selectionArgs: 1002
09-16 17:11:10.921  3394  3844 D SettingsProvider: ret = -1
,09-16 17:11:10.921  3394  4984 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,09-16 17:11:10.921  3394  4984 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 17:11:10.921  3394  4984 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 17:11:10.921  3394  4984 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 17:11:10.921  3394  4984 D SettingsProvider: selectionArgs: false
09-16 17:11:10.921  3394  4984 D SettingsProvider: selectionArgs: 1002
09-16 17:11:10.921  3394  4984 D SettingsProvider: ret = -1
,09-16 17:11:10.931  3394  4397 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.sap.SapService
,09-16 17:11:10.931  3394  4397 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,09-16 17:11:10.931  3394  4397 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 17:11:10.931  3394  4397 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 17:11:10.931  3394  4397 D SettingsProvider: selectionArgs: false
,09-16 17:11:10.931 10116 10116 E Zygote  : v2
09-16 17:11:10.931  3394  4397 D SettingsProvider: selectionArgs: 1002
09-16 17:11:10.931  3394  4397 D SettingsProvider: ret = -1
09-16 17:11:10.931 10116 10116 I libpersona: KNOX_SDCARD checking this for 5005
,09-16 17:11:10.931 10116 10116 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 17:11:10.931 10116 10116 I libpersona: KNOX_SDCARD not a persona
09-16 17:11:10.931  3394  3857 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 17:11:10.931  3394  3857 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-16 17:11:10.931  3394  3857 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 17:11:10.931  3394  3857 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-16 17:11:10.931  3394  3857 D SettingsProvider: selectionArgs: false
09-16 17:11:10.931 10116 10116 E Zygote  : accessInfo : 0
09-16 17:11:10.931  3394  3857 D SettingsProvider: selectionArgs: 1002
09-16 17:11:10.931 10116 10116 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
09-16 17:11:10.931  3394  3857 D SettingsProvider: ret = -1
,09-16 17:11:10.931  3394  4406 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-16 17:11:10.931  3394  4406 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 17:11:10.931  3394  4406 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 17:11:10.931  3394  4406 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-16 17:11:10.931  3394  4406 D SettingsProvider: selectionArgs: false
09-16 17:11:10.931  3394  4406 D SettingsProvider: selectionArgs: 1002
,09-16 17:11:10.931  3394  4406 D SettingsProvider: ret = -1
,09-16 17:11:10.941  3394  4255 I ActivityManager: Start proc 10116:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
09-16 17:11:10.941  3394  4196 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.broadcom.bt.service.bleaudio.BleAudioService
09-16 17:11:10.941  3394  4196 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 17:11:10.941  3394  4196 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 17:11:10.941  3394  4196 D SettingsProvider: selectionArgs: false
09-16 17:11:10.941  3394  4196 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 17:11:10.941  3394  4196 D SettingsProvider: selectionArgs: 1002
09-16 17:11:10.941  3394  4255 I ActivityManager: Killing 8974:com.samsung.android.app.appsedge/u0a1 (adj 15): DHA:empty #33
09-16 17:11:10.941  3394  4196 D SettingsProvider: ret = -1
09-16 17:11:10.941 10092 10092 D InjectionManager: InjectionManager
09-16 17:11:10.941 10092 10092 D InjectionManager: fillFeatureStoreMap com.android.bluetooth
09-16 17:11:10.941 10092 10092 I InjectionManager: Constructor com.android.bluetooth, Feature store :{}
09-16 17:11:10.941 10092 10092 I InjectionManager: featureStore :{}
,09-16 17:11:10.961 10116 10116 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:10.961 10116 10116 D ActivityThread: Added TimaKeyStore provider
09-16 17:11:10.961  3394  4985 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{83ae1d7 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{195b8d0 10012:com.google.android.apps.maps/u0a125}
,09-16 17:11:10.971 10092 10128 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-16 17:11:10.971 10092 10128 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-16 17:11:10.981  3394  3455 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.appsedge, Auto Run ON
,09-16 17:11:11.001  3394  4397 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{86ddf30 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d8f812e 10116:com.samsung.android.app.FileShareServer/5005}
,09-16 17:11:11.001  3394  4985 I ActivityManager: Killing 9486:com.samsung.android.app.galaxylabs/u0a17 (adj 15): DHA:empty #33
,09-16 17:11:11.011  3394  4985 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{70a34cf u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dccee39 9907:com.test.thalitest/u0a177}
,09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:11.011  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:11.021 10116 10116 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:11.021 10116 10116 D RelationGraph: garbageCollect()
,09-16 17:11:11.021 10116 10116 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareServer/AllshareFileShareServer.apk / 1.0 running in com.samsung.android.app.FileShareServer rsrc of package com.samsung.android.app.FileShareServer
,09-16 17:11:11.031  3394  4500 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 17:11:11.031 10116 10116 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:11.031 10116 10116 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:11.031  3394  4255 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.galaxylabs, Auto Run ON
,09-16 17:11:11.031 10116 10116 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:11.041 10116 10116 D InjectionManager: InjectionManager
,09-16 17:11:11.041 10116 10116 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareServer
09-16 17:11:11.051 10116 10116 I InjectionManager: Constructor com.samsung.android.app.FileShareServer, Feature store :{}
09-16 17:11:11.051 10116 10116 I InjectionManager: featureStore :{}
,09-16 17:11:11.051 10116 10116 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-16 17:11:11.051 10116 10116 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-16 17:11:11.051 10116 10116 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-16 17:11:11.071  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:11.081 10129 10129 E Zygote  : v2
09-16 17:11:11.081 10129 10129 I libpersona: KNOX_SDCARD checking this for 1000
09-16 17:11:11.081 10129 10129 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:11.081 10129 10129 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:11.081 10129 10129 E Zygote  : accessInfo : 0
,09-16 17:11:11.081  3394  4716 I ActivityManager: Start proc 10129:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
,09-16 17:11:11.081  3394  4716 I ActivityManager: Killing 9503:com.google.android.partnersetup/u0a25 (adj 15): DHA:empty #33
,09-16 17:11:11.101  3394  4054 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,09-16 17:11:11.121 10129 10129 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:11.121 10129 10129 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:11.131  3394  4397 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{289be5c 10129:com.policydm/1000}
,09-16 17:11:11.141 10129 10129 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 17:11:11.141 10129 10129 D RelationGraph: garbageCollect()
,09-16 17:11:11.141 10129 10129 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package com.policydm
,09-16 17:11:11.141  3394  3982 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 17:11:11.141 10129 10129 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:11.141 10129 10129 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:11.151 10129 10129 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:11.161 10129 10129 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,09-16 17:11:11.171 10129 10129 I FOTA    : [lIlIIlIIlIlllIIIIlll(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
09-16 17:11:11.171 10129 10129 I FOTA    : [lIlIIlIIlIlllIIIIlll(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,09-16 17:11:11.191 10129 10129 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,09-16 17:11:11.201 10129 10129 I DBG_POLICYDM: [com.policydm.db.XDB(1548/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,09-16 17:11:11.211 10129 10129 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(142/llIIIIlllllIIllIIllI)] try read dbString
,09-16 17:11:11.251  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:11.271 10129 10129 I DBG_POLICYDM: [com.policydm.XDMService(161/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,09-16 17:11:11.281 10129 10129 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(51/<init>)] 
,09-16 17:11:11.281 10129 10129 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:55 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:17 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:23 
,09-16 17:11:11.311 10145 10145 E Zygote  : v2
09-16 17:11:11.311 10145 10145 I libpersona: KNOX_SDCARD checking this for 10078
09-16 17:11:11.311 10145 10145 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 17:11:11.311 10145 10145 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:11.311 10145 10145 E Zygote  : accessInfo : 0
09-16 17:11:11.311 10145 10145 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,09-16 17:11:11.311  3394  4406 I ActivityManager: Start proc 10145:com.samsung.aasaservice/u0a78 for service com.samsung.aasaservice/.AASAService
,09-16 17:11:11.321 10129 10129 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(26/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,09-16 17:11:11.331 10129 10129 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,09-16 17:11:11.341 10129 10129 I DBG_POLICYDM: [com.policydm.XDMService(570/llIlIllllllllllllllI)] get NotibarState : 0
,09-16 17:11:11.341 10129 10129 D InjectionManager: InjectionManager
,09-16 17:11:11.341 10129 10129 D InjectionManager: fillFeatureStoreMap com.policydm
,09-16 17:11:11.341 10129 10129 I InjectionManager: Constructor com.policydm, Feature store :{}
09-16 17:11:11.341 10129 10129 I InjectionManager: featureStore :{}
,09-16 17:11:11.351 10145 10145 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-16 17:11:11.351 10145 10145 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:11.381 10129 10129 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
09-16 17:11:11.381 10145 10145 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:11.381 10145 10145 D RelationGraph: garbageCollect()
,09-16 17:11:11.381 10145 10145 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package com.samsung.aasaservice
,09-16 17:11:11.381  3394  4406 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 17:11:11.381 10145 10145 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:11.381 10145 10145 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:11.391 10145 10145 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:11.391 10129 10129 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,09-16 17:11:11.391 10129 10129 I DBG_POLICYDM: [com.policydm.XDMService(570/llIlIllllllllllllllI)] get NotibarState : 0
,09-16 17:11:11.391 10145 10145 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm64
,09-16 17:11:11.391 10145 10145 D InjectionManager: InjectionManager
,09-16 17:11:11.391 10145 10145 D InjectionManager: fillFeatureStoreMap com.samsung.aasaservice
09-16 17:11:11.391 10145 10145 I InjectionManager: Constructor com.samsung.aasaservice, Feature store :{}
09-16 17:11:11.391 10145 10145 I InjectionManager: featureStore :{}
,09-16 17:11:11.401 10145 10145 D AASAservice: onCreate()
,09-16 17:11:11.401  3394  4500 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{289be5c 10129:com.policydm/1000}
,09-16 17:11:11.401 10129 10129 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,09-16 17:11:11.411 10129 10129 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(37/onServiceConnected)] AASA: onServiceConnected
,09-16 17:11:11.421 10158 10158 E Zygote  : v2
09-16 17:11:11.421 10158 10158 I libpersona: KNOX_SDCARD checking this for 10044
09-16 17:11:11.421 10158 10158 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:11.421 10158 10158 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:11.421  3394  4984 I ActivityManager: Start proc 10158:com.osp.app.signin/u0a44 for broadcast-5 com.osp.app.signin/.OspReceiver
09-16 17:11:11.421 10158 10158 E Zygote  : accessInfo : 0
,09-16 17:11:11.421 10158 10158 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.osp.app.signin 
09-16 17:11:11.421  3394  4984 I ActivityManager: Killing 9574:com.samsung.svoice.sync/u0a43 (adj 15): DHA:empty #33
,09-16 17:11:11.421  3394  4984 I ActivityManager: Killing 9560:com.sec.android.service.health/u0a26 (adj 15): DHA:empty #33
,09-16 17:11:11.431  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:11.441  3394  4255 D ActivityManager: isAutoRunBlockedApp:: com.samsung.svoice.sync, Auto Run ON
,09-16 17:11:11.451 10158 10158 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:11.451 10158 10158 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:11.461  3394  4985 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.service.health, Auto Run ON
,09-16 17:11:11.471  3394  4149 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5226448 10158:com.osp.app.signin/u0a44}
,09-16 17:11:11.481 10158 10158 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 17:11:11.491 10158 10158 D RelationGraph: garbageCollect()
,09-16 17:11:11.491 10158 10158 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in com.osp.app.signin rsrc of package com.osp.app.signin
,09-16 17:11:11.491  3394  3844 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:11:11.491 10158 10158 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:11.501 10158 10158 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:11.501 10158 10158 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:11.521 10158 10158 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungAccount_Hero/lib/arm64
,09-16 17:11:11.541 10158 10158 I SA      : [SSP] onCreated
,09-16 17:11:11.581 10158 10158 D SamsungAnalytics: [Tracker] Tracker start:1.2.00
,09-16 17:11:11.591  3394  3507 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
09-16 17:11:11.591  3394  3507 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
09-16 17:11:11.591  3394  3507 E libgps  : IPC Communication Error, ../../../../tmp/14804949_263294/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,09-16 17:11:11.601 10158 10158 I SA      : [TPM] There is no property file
,09-16 17:11:11.611  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:11.611 10158 10158 I SA      : [SCU] isHaveSA() - false
,09-16 17:11:11.621 10158 10158 I SA      : [TPM] getModelProperty : null
09-16 17:11:11.621 10158 10158 I SA      : [TPM] getCSCProperty : null
,09-16 17:11:11.621 10158 10158 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-16 17:11:11.621 10158 10158 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-16 17:11:11.621 10158 10158 I SA      : [DM] TFT FEATURE: false
,09-16 17:11:11.631 10158 10158 I SA      : [SCU] isHaveSA() - false
,09-16 17:11:11.631 10158 10158 I SA      : [SCU] == networkStateCheck == false
,09-16 17:11:11.631 10158 10158 I SA      : [SS] network off, couldn't connect to DIR
09-16 17:11:11.631 10158 10158 D InjectionManager: InjectionManager
09-16 17:11:11.631 10158 10158 D InjectionManager: fillFeatureStoreMap com.osp.app.signin
09-16 17:11:11.631 10158 10158 I InjectionManager: Constructor com.osp.app.signin, Feature store :{}
,09-16 17:11:11.631 10158 10158 I InjectionManager: featureStore :{}
,09-16 17:11:11.631 10158 10158 I SA      : [DM] init START
,09-16 17:11:11.651 10158 10158 I SA      : [DM] This device is not a Vodafone
,09-16 17:11:11.661 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.661 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.661 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.661 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.661 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.661 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.671 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.671 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.671 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.671 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.671 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.671 10158 10158 W ResourceType: Failure getting entry for 0x7f0a0002 (t=9 e=2) (error -75)
,09-16 17:11:11.671 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.681 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.681 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.681 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.681 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.681 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 17:11:11.681 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.681 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.681 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.681 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.681 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.691 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.691 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.691 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.691 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.691 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.691 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 17:11:11.691 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.691 10158 10158 W ResourceType: Failure getting entry for 0x7f0a0005 (t=9 e=5) (error -75)
,09-16 17:11:11.691 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.691 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.691 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.691 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.701 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 17:11:11.701 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.701 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.701 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.701 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.701 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 17:11:11.701 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.701 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.701 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 17:11:11.701 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.701 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.701 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.701 10158 10158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 17:11:11.711 10158 10158 I SA      : support phone number id : true
,09-16 17:11:11.711 10158 10158 I SA      : [DM] Supports Ref Jpn : true
09-16 17:11:11.711 10158 10158 I SA      : [DM] init END
,09-16 17:11:11.711 10158 10158 I SA      : [OR] onReceive log=[SA = 2.2.01-90 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hero2lte P = hero2ltexx I = MMB29K M = SM-G935F OKLEFT false DIS MMB29K.G935FXXU1BPH6 PSS = 5.460694751064798  ]
,09-16 17:11:11.711 10158 10158 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,09-16 17:11:11.711 10158 10158 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-16 17:11:11.711 10158 10158 I SA      : [SLFUCHKMGR] constructor called
,09-16 17:11:11.721 10158 10158 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-16 17:11:11.721 10158 10158 I SA      : [OR] == isSIMCardReady false ==
,09-16 17:11:11.731 10158 10158 I SA      : [SCU] == networkStateCheck == false
09-16 17:11:11.731 10158 10158 I SA      : [OR] onReceive END
,09-16 17:11:11.741 10175 10175 E Zygote  : v2
09-16 17:11:11.741 10175 10175 I libpersona: KNOX_SDCARD checking this for 1000
09-16 17:11:11.741 10175 10175 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:11.751 10175 10175 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:11.751  3394  3844 I ActivityManager: Start proc 10175:com.wssyncmldm/1000 for broadcast-5 com.wssyncmldm/com.samsung.android.app.fotaclient.NetworkReceiver
,09-16 17:11:11.751 10175 10175 E Zygote  : accessInfo : 0
,09-16 17:11:11.751  3394  3844 I ActivityManager: Killing 9630:com.samsung.android.provider.shootingmodeprovider/u0a60 (adj 15): DHA:empty #33
,09-16 17:11:11.771  3394  4397 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,09-16 17:11:11.781 10175 10175 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:11.781 10175 10175 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:11.791  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:11.791  3394  4985 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1e2d2e1 10175:com.wssyncmldm/1000}
,09-16 17:11:11.801 10175 10175 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 17:11:11.801 10175 10175 D RelationGraph: garbageCollect()
,09-16 17:11:11.811 10175 10175 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.wssyncmldm rsrc of package com.wssyncmldm
,09-16 17:11:11.811  3394  4984 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:11:11.811 10175 10175 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:11.811 10175 10175 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:11.811 10175 10175 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:11.821 10175 10175 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm64
,09-16 17:11:11.831 10175 10175 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,09-16 17:11:11.901 10175 10175 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(2021/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,09-16 17:11:11.951 10175 10175 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(271/llIlIIIIlIIIIIlIlIII)] Voice : true
,09-16 17:11:11.951 10175 10175 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(272/llIlIIIIlIIIIIlIlIII)] SMS : true
09-16 17:11:11.961 10175 10175 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(273/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,09-16 17:11:11.971  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:11.971 10175 10175 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3216/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,09-16 17:11:11.971 10175 10175 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3268/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,09-16 17:11:11.981 10175 10175 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(102/onCreate)] DMApplication NOT Start !
,09-16 17:11:11.981 10175 10175 D InjectionManager: InjectionManager
09-16 17:11:11.981 10175 10175 D InjectionManager: fillFeatureStoreMap com.wssyncmldm
,09-16 17:11:11.981 10175 10175 I InjectionManager: Constructor com.wssyncmldm, Feature store :{}
09-16 17:11:11.981 10175 10175 I InjectionManager: featureStore :{}
,09-16 17:11:11.991  3394  3982 I ActivityManager: Killing 9411:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #33
,09-16 17:11:12.001  9907  9971 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-16 17:11:12.011  3394  4149 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-16 17:11:12.011  3394  4149 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
09-16 17:11:12.011  3394  3982 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78aec4e 7390:com.samsung.fresco.logging/5015}
,09-16 17:11:12.021  3394  4149 D WifiService: setWifiEnabled: true pid=9907, uid=10177
,09-16 17:11:12.031  3394  4149 W ActivityManager: Permission Denial: getCurrentUser() from pid=9907, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
,09-16 17:11:12.031  3394  4149 W WifiService: Failed getting userId using ActivityManagerNative
09-16 17:11:12.031  3394  4149 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9907, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
09-16 17:11:12.031  3394  4149 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28247)
09-16 17:11:12.031  3394  4149 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
09-16 17:11:12.031  3394  4149 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
09-16 17:11:12.031  3394  4149 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-16 17:11:12.031  3394  4149 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
09-16 17:11:12.031  3394  4149 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
09-16 17:11:12.031  3394  4149 D SettingsProvider: isChangeAllowed() : name = wifi_on
09-16 17:11:12.031  3394  3862 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-16 17:11:12.031  3394  3862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
09-16 17:11:12.031  3394  3865 D WifiStateMachine: setFccChannel: channel = 0
09-16 17:11:12.031  3394  3865 D WifiController: [FCC]setFccChannel() is called !!!
09-16 17:11:12.031  3394  3865 D SecContentProvider: insert(), uri = 2
09-16 17:11:12.031  3394  3865 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,09-16 17:11:12.041  3394  3857 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,09-16 17:11:12.051  3394  3862 D WifiBigDataLog: init : 
,09-16 17:11:12.061  3394  3862 E WifiHW  : ##################### set firmware type 0 #####################
,09-16 17:11:12.061  3394  4500 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:12.061  3394  4984 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:12.061  3152  3779 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,09-16 17:11:12.061  3152  3779 I WifiHW  : module is semco
09-16 17:11:12.061  3152  3779 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
09-16 17:11:12.061  3152  3779 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
09-16 17:11:12.061  3152  3779 E WifiHW  : TEMP_FAILURE_RETRY complete
09-16 17:11:12.061  3152  3779 D SoftapController: Softap fwReload - Ok
,09-16 17:11:12.071  3152  3779 D CommandListener: Setting iface cfg
,09-16 17:11:12.071  3152  3779 D CommandListener: Trying to bring down wlan0
09-16 17:11:12.071  3152  3779 D CommandListener: Clearing all IP addresses on wlan0
,09-16 17:11:12.071  3394  3862 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 17:11:12.071  3394  3862 D wifi    : Can not initialize the vendor function pointer table
09-16 17:11:12.071  3394  3862 E WifiNative-HAL: Could not start hal
09-16 17:11:12.071  3394  3862 E WifiStateMachine: Failed to start HAL
,09-16 17:11:12.081  3394  3862 E WifiHW  : supplicant_name : p2p_supplicant
,09-16 17:11:12.081  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c58bc1d u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a366578 5051:com.samsung.android.providers.context/u0a9}
,09-16 17:11:12.081  7390  7390 D DeviceInterfaceImpl: Battery Connected: true
,09-16 17:11:12.081  3394  4406 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:12.081  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:12.101  3394  3454 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{122783d 7966:com.sec.spp.push/u0a42}
,09-16 17:11:12.101  7966  7966 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
09-16 17:11:12.111  7966  7966 E SPPClientService: [SystemStateMoniter] Current Time : 249389
,09-16 17:11:12.111  7966  7966 E SPPClientService: [SystemStateMoniter] No Connect : true
,09-16 17:11:12.121  7966 10191 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-16 17:11:12.131  3394  3454 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3a9825a 4895:android.process.media/u0a51}
,09-16 17:11:12.131  4895  4895 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-16 17:11:12.151  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:12.151 10192 10192 E Zygote  : v2
09-16 17:11:12.151 10192 10192 I libpersona: KNOX_SDCARD checking this for 1000
09-16 17:11:12.151 10192 10192 I libpersona: KNOX_SDCARD not a persona
09-16 17:11:12.151 10192 10192 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:12.151 10192 10192 E Zygote  : accessInfo : 0
,09-16 17:11:12.161  3394  4500 I ActivityManager: Start proc 10192:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
,09-16 17:11:12.171 10192 10192 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:12.171 10192 10192 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:12.191  3394  4196 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9c4b063 10192:com.samsung.android.SettingsReceiver/1000}
,09-16 17:11:12.191  3394  3862 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-16 17:11:12.191  3394  3394 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,09-16 17:11:12.191  3394  3394 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,09-16 17:11:12.191  3394  3869 I WifiHs20Service: Message received 5011
,09-16 17:11:12.191 10192 10192 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:12.201 10192 10192 D RelationGraph: garbageCollect()
09-16 17:11:12.201  3394  3394 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
09-16 17:11:12.201  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 17:11:12.201  3940  3940 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-16 17:11:12.201  3940  3940 I HotspotTile: Provider is not defined returning false
09-16 17:11:12.201  3394  3872 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-16 17:11:12.201  3940  3940 D HotspotTile: onReceive : 2, 0
,09-16 17:11:12.201 10192 10192 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
09-16 17:11:12.201  4298  4308 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-16 17:11:12.201  4298  4308 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-16 17:11:12.201  3394  3872 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-16 17:11:12.211  3394  4406 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:11:12.211 10192 10192 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:12.211 10192 10192 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:12.211  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:12.211  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:12.211 10192 10192 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:12.221 10192 10192 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
09-16 17:11:12.221  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{60f7460 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dccee39 9907:com.test.thalitest/u0a177}
,09-16 17:11:12.221 10192 10192 D InjectionManager: InjectionManager
,09-16 17:11:12.221 10192 10192 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
09-16 17:11:12.221 10192 10192 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
09-16 17:11:12.221 10192 10192 I InjectionManager: featureStore :{}
,09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:12.221 10192 10192 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.android.settings
,09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:12.221  3394  3844 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:12.221 10192 10192 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:12.241 10192 10192 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,09-16 17:11:12.251 10190 10190 I FIPS_bssl: FIPS approved mode (1) | 10190 | /system/bin/wpa_supplicant
,09-16 17:11:12.261 10205 10205 E Zygote  : v2
09-16 17:11:12.261 10205 10205 I libpersona: KNOX_SDCARD checking this for 10068
09-16 17:11:12.261 10205 10205 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 17:11:12.261 10205 10205 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:12.261 10190 10190 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-16 17:11:12.261 10190 10190 I wpa_supplicant: Successfully initialized wpa_supplicant
09-16 17:11:12.261 10190 10190 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
09-16 17:11:12.261 10205 10205 E Zygote  : accessInfo : 0
09-16 17:11:12.261 10205 10205 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
09-16 17:11:12.261 10190 10190 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-16 17:11:12.261  3394  4985 I ActivityManager: Start proc 10205:com.samsung.android.themestore/u0a68 for broadcast-5 com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,09-16 17:11:12.261  3394  4985 I ActivityManager: Killing 9644:com.samsung.android.app.taskedge/u0a67 (adj 15): DHA:empty #33
,09-16 17:11:12.281 10190 10190 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-16 17:11:12.281  3012  3012 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10190
,09-16 17:11:12.281  3012  3012 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-16 17:11:12.281 10190 10190 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-16 17:11:12.281 10190 10190 I wpa_supplicant: ssSupport state is = 1
09-16 17:11:12.281 10190 10190 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-16 17:11:12.281 10190 10190 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-16 17:11:12.281  3012  3012 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10190
09-16 17:11:12.281  3012  3012 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,09-16 17:11:12.291 10190 10190 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,09-16 17:11:12.291 10205 10205 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-16 17:11:12.291 10205 10205 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:12.301  3394  3982 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.taskedge, Auto Run ON
,09-16 17:11:12.321  3394  3454 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c49fd19 10205:com.samsung.android.themestore/u0a68}
,09-16 17:11:12.331  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:12.331 10205 10205 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 17:11:12.331 10205 10205 D RelationGraph: garbageCollect()
,09-16 17:11:12.331 10205 10205 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeStore_3xh/ThemeStore_3xh.apk / 1.0 running in com.samsung.android.themestore rsrc of package com.samsung.android.themestore
,09-16 17:11:12.331  3394  4984 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 17:11:12.331 10205 10205 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:12.341 10205 10205 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:12.341 10205 10205 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:12.351 10205 10205 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeStore_3xh/lib/arm64
,09-16 17:11:12.361 10205 10205 D a       : Exist Config : false
,09-16 17:11:12.361 10205 10205 D a       : getMcc
09-16 17:11:12.361 10205 10205 D ai      : isQaMode
,09-16 17:11:12.371 10205 10205 D a       : getMnc
,09-16 17:11:12.371 10205 10205 D a       : getCsc
09-16 17:11:12.371 10205 10205 D a       : getSystemCountryCode
09-16 17:11:12.371 10205 10205 D a       : getImei
,09-16 17:11:12.371 10205 10205 D ai      : getMd5HashString
,09-16 17:11:12.381 10205 10205 D ai      : getSha256HashString
,09-16 17:11:12.381 10205 10205 D a       : getMsisdn
,09-16 17:11:12.381  4298  4606 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,09-16 17:11:12.401 10205 10205 D a       : getModelName
,09-16 17:11:12.401 10205 10205 D a       : getVirtualModelName
09-16 17:11:12.411 10205 10205 D a       : getAndroidSDKVersion
,09-16 17:11:12.411 10205 10205 D a       : getLanguageCode
09-16 17:11:12.411 10205 10205 D a       : getCountryCode
,09-16 17:11:12.411 10205 10205 D a       : getNetworkType
,09-16 17:11:12.421 10205 10205 D t       : isSupportedAodSystemFeature
,09-16 17:11:12.421 10205 10205 D a       : isLogPrintMode
,09-16 17:11:12.421 10205 10205 D ai      : isQaMode
,09-16 17:11:12.431 10205 10205 D a       : getVerName
,09-16 17:11:12.431 10205 10205 D a       : getVerCode
,09-16 17:11:12.431 10205 10205 D a       : getPackageName
09-16 17:11:12.431 10205 10205 D a       : getAutoUpgradeInterval
,09-16 17:11:12.431 10205 10205 D a       : loadCountrySearchEx
,09-16 17:11:12.451 10205 10205 I a       : voCountrySearchEx loaded.
,09-16 17:11:12.451 10205 10205 I a       : # initConfig Time : 94
,09-16 17:11:12.451 10205 10205 I a       : ● MCCNNC : 260 0
09-16 17:11:12.451 10205 10205 I a       : ● Model : SM-G935F_TM
09-16 17:11:12.451 10205 10205 I a       : ● MyApp Vertion : 1.03.22(20160524)
,09-16 17:11:12.451 10205 10205 I a       : ● OS Vertion : 23
,09-16 17:11:12.471 10205 10205 D InjectionManager: InjectionManager
,09-16 17:11:12.471 10205 10205 D InjectionManager: fillFeatureStoreMap com.samsung.android.themestore
09-16 17:11:12.471 10205 10205 I InjectionManager: Constructor com.samsung.android.themestore, Feature store :{}
09-16 17:11:12.471 10205 10205 I InjectionManager: featureStore :{}
,09-16 17:11:12.471 10205 10205 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,09-16 17:11:12.491 10225 10225 E Zygote  : v2
09-16 17:11:12.491 10225 10225 I libpersona: KNOX_SDCARD checking this for 5009
09-16 17:11:12.491 10225 10225 I libpersona: KNOX_SDCARD not a persona
09-16 17:11:12.491 10225 10225 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:12.491  3394  4397 I ActivityManager: Start proc 10225:com.samsung.android.scloud:contentsync/5009 for broadcast-5 com.samsung.android.scloud/.cloudagent.detector.DetectorReceiver
09-16 17:11:12.491 10225 10225 E Zygote  : accessInfo : 0
,09-16 17:11:12.491 10225 10225 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud:contentsync 
,09-16 17:11:12.501  3394  4397 I ActivityManager: Killing 9656:com.samsung.android.themecenter/1000 (adj 15): DHA:empty #33
,09-16 17:11:12.511  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:12.531  3394  4445 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themecenter, Auto Run ON
,09-16 17:11:12.531 10225 10225 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:12.531 10225 10225 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:12.551  3394  4716 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f491de 10225:com.samsung.android.scloud:contentsync/5009}
,09-16 17:11:12.571 10225 10225 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:12.571 10225 10225 D RelationGraph: garbageCollect()
,09-16 17:11:12.571 10225 10225 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.scloud
,09-16 17:11:12.581  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,09-16 17:11:12.581 10190 10190 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
09-16 17:11:12.581  3394  4255 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:11:12.581 10225 10225 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:12.581 10225 10225 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:12.581 10225 10225 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:12.591 10225 10225 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungCloud/lib/arm64
,09-16 17:11:12.601 10190 10190 I wpa_supplicant: Ctrl_iface: loading system cred
09-16 17:11:12.601 10190 10190 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,09-16 17:11:12.621 10225 10225 I [SC]CloudManager: requestInit
,09-16 17:11:12.621 10190 10190 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,09-16 17:11:12.621  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10190
09-16 17:11:12.621  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
09-16 17:11:12.621 10190 10190 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
09-16 17:11:12.621 10190 10190 I wpa_supplicant: ssSupport state is = 1
,09-16 17:11:12.621 10190 10190 I wpa_supplicant: Blacklist: Clear (all) 
,09-16 17:11:12.631 10190 10190 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-16 17:11:12.631 10190 10190 I wpa_supplicant: [getIMSI]: sim_num 0
,09-16 17:11:12.641 10190 10190 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 17:11:12.651 10225 10225 I [SC]Utils: folder : cachecreate fail, try again.
09-16 17:11:12.651 10225 10225 I [SC]Utils: folder : cache create fail.
,09-16 17:11:12.651 10225 10225 I [SC]Utils: folder : thumbnailcreate fail, try again.
09-16 17:11:12.651 10225 10225 I [SC]Utils: folder : thumbnail create fail.
09-16 17:11:12.651 10225 10225 I [SC]Utils: folder : sharecreate fail, try again.
09-16 17:11:12.651 10225 10225 I [SC]Utils: folder : share create fail.
09-16 17:11:12.651 10225 10225 I [SC]Utils: folder : scratchcreate fail, try again.
09-16 17:11:12.651 10225 10225 I [SC]Utils: folder : scratch create fail.
09-16 17:11:12.651 10225 10225 I [SC]Utils: folder : eventSynccreate fail, try again.
09-16 17:11:12.651 10225 10225 I [SC]Utils: folder : eventSync create fail.
,09-16 17:11:12.671 10225 10225 V SamsungCloudLogs:  set Log level [4->4]act[false]
,09-16 17:11:12.681 10225 10225 I [SC]CommonUtil: isSemAvailable:0
,09-16 17:11:12.681 10225 10225 I [SC]SamsungCloudApp: AppVer[2.1.11][L:4]Sem[false]V2DEV_R slog[false]com.samsung.android.scloud:contentsync
,09-16 17:11:12.681 10225 10225 D InjectionManager: InjectionManager
09-16 17:11:12.681 10225 10225 D InjectionManager: fillFeatureStoreMap com.samsung.android.scloud
09-16 17:11:12.681 10225 10225 I InjectionManager: Constructor com.samsung.android.scloud, Feature store :{}
09-16 17:11:12.681 10225 10225 I InjectionManager: featureStore :{}
,09-16 17:11:12.691 10225 10225 I [SC]FeatureManager: FeatureManager 
09-16 17:11:12.691 10225 10225 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_CONFIG_CLOUD_USAGE_MENU_TREE]str 
09-16 17:11:12.691 10225 10225 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_ENABLE_SETTING_MENU]bln true
,09-16 17:11:12.691  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:12.691 10225 10225 E [SC]SCLOUD_ERR-Utils: isShipMode : 1 
,09-16 17:11:12.701 10225 10225 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
09-16 17:11:12.701 10225 10225 I [SC]CloudManager: requestInit
,09-16 17:11:12.701 10225 10225 I [SC]Utils: folder : cachecreate fail, try again.
09-16 17:11:12.701 10225 10225 I [SC]Utils: folder : cache create fail.
09-16 17:11:12.701 10225 10225 I [SC]Utils: folder : thumbnailcreate fail, try again.
,09-16 17:11:12.701 10225 10225 I [SC]Utils: folder : thumbnail create fail.
09-16 17:11:12.701 10225 10225 I [SC]Utils: folder : sharecreate fail, try again.
09-16 17:11:12.701 10225 10225 I [SC]Utils: folder : share create fail.
09-16 17:11:12.701 10225 10225 I [SC]Utils: folder : scratchcreate fail, try again.
,09-16 17:11:12.701 10225 10225 I [SC]Utils: folder : scratch create fail.
09-16 17:11:12.701 10225 10225 I [SC]Utils: folder : eventSynccreate fail, try again.
,09-16 17:11:12.701 10225 10225 I [SC]Utils: folder : eventSync create fail.
,09-16 17:11:12.711 10158 10169 I SA      : [SCU] isHaveSA() - false
,09-16 17:11:12.721 10158 10169 I SA      : [OCP] Samsung account is not Signed-in
,09-16 17:11:12.721 10158 10169 I SA      : [OCP] Delete DB (TNC data)
,09-16 17:11:12.721 10225 10225 I [SC]CommonUtil: Samsung Account Not Logged in
,09-16 17:11:12.731  3394  3455 I ActivityManager: Killing 9669:com.samsung.android.scloud/5009 (adj 15): DHA:empty #33
,09-16 17:11:12.771 10240 10240 E Zygote  : v2
09-16 17:11:12.771 10240 10240 I libpersona: KNOX_SDCARD checking this for 5011
09-16 17:11:12.771 10240 10240 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:12.771 10240 10240 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:12.771  3394  4716 I ActivityManager: Start proc 10240:com.samsung.android.coreapps/5011 for broadcast-5 com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener
,09-16 17:11:12.771 10240 10240 E Zygote  : accessInfo : 0
09-16 17:11:12.771 10240 10240 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.coreapps 
,09-16 17:11:12.781  3394  4500 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,09-16 17:11:12.801 10240 10240 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:12.801 10240 10240 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:12.821  3394  4985 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a33edea 10240:com.samsung.android.coreapps/5011}
,09-16 17:11:12.831 10240 10240 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 17:11:12.831 10240 10240 D RelationGraph: garbageCollect()
,09-16 17:11:12.831 10240 10240 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.samsung.android.coreapps
,09-16 17:11:12.841  3394  4406 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 17:11:12.841 10240 10240 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:12.841 10240 10240 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:12.841 10240 10240 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:12.851 10240 10240 W System  : ClassLoader referenced unknown path: /system/app/CoreApps/lib/arm64
,09-16 17:11:12.861 10240 10240 D CoreApps: SEC_LOG - true
,09-16 17:11:12.871  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:12.911 10240 10240 E GooglePlayServicesUtil: The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,09-16 17:11:13.051  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:13.121 10240 10240 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.android.mms
,09-16 17:11:13.131 10240 10240 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:13.131 10240 10240 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.google.android.talk
,09-16 17:11:13.141 10240 10240 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:13.141 10240 10240 D InjectionManager: InjectionManager
,09-16 17:11:13.151 10240 10240 D InjectionManager: fillFeatureStoreMap com.samsung.android.coreapps
09-16 17:11:13.151 10240 10240 I InjectionManager: Constructor com.samsung.android.coreapps, Feature store :{}
09-16 17:11:13.151 10240 10240 I InjectionManager: featureStore :{}
,09-16 17:11:13.161  3394  4406 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a33edea 10240:com.samsung.android.coreapps/5011}
,09-16 17:11:13.181  3394  3857 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a33edea 10240:com.samsung.android.coreapps/5011}
,09-16 17:11:13.191  3394  3857 I ActivityManager: Killing 9691:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #33
,09-16 17:11:13.201  3394  3857 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1103e2 4882:com.microsoft.skydrive/u0a130}
,09-16 17:11:13.201  3394  4255 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:13.221  3394  4445 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,09-16 17:11:13.231  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:13.251  3394  4054 I ActivityManager: Start proc 10266:com.microsoft.office.onenote.connectionReceiverProcess/u0a12 for broadcast-5 com.microsoft.office.onenote/com.microsoft.bing.datamining.quasar.api.ConnectionChangeReceiver
,09-16 17:11:13.261  3394  4445 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,09-16 17:11:13.311 10266 10266 E Zygote  : v2
09-16 17:11:13.311 10266 10266 I libpersona: KNOX_SDCARD checking this for 10012
09-16 17:11:13.311 10266 10266 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:13.311 10266 10266 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:13.311 10266 10266 E Zygote  : accessInfo : 0
,09-16 17:11:13.311 10266 10266 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.microsoft.office.onenote.connectionReceiverProcess 
,09-16 17:11:13.361 10266 10266 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:13.361 10266 10266 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:13.371  3394  4196 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb53651 10266:com.microsoft.office.onenote.connectionReceiverProcess/u0a12}
,09-16 17:11:13.391 10266 10266 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:13.391 10266 10266 D RelationGraph: garbageCollect()
,09-16 17:11:13.401  3152  3772 D Netd    : Iface wlan0 link up
,09-16 17:11:13.401  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 17:11:13.401  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
09-16 17:11:13.401 10266 10266 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.microsoft.office.onenote rsrc of package com.microsoft.office.onenote
09-16 17:11:13.401  3152  3772 D Netd    : Iface wlan0 link up
09-16 17:11:13.401  5063  5075 D PdnController: Interface Changed wlan0 link up
,09-16 17:11:13.401  3152  3772 D Netd    : Iface wlan0 link up
,09-16 17:11:13.401  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 17:11:13.401  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
09-16 17:11:13.401  3394  4500 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:11:13.401  5063  5073 D PdnController: Interface Changed wlan0 link up
,09-16 17:11:13.401 10266 10266 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:13.401  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 17:11:13.401  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
09-16 17:11:13.401  5063  5350 D PdnController: Interface Changed wlan0 link up
,09-16 17:11:13.411 10266 10266 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:13.411  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:13.411 10266 10266 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:13.421 10266 10266 W System  : ClassLoader referenced unknown path: /system/app/OneNote/lib/arm
,09-16 17:11:13.431 10266 10266 D InjectionManager: InjectionManager
09-16 17:11:13.431 10266 10266 D InjectionManager: fillFeatureStoreMap com.microsoft.office.onenote
,09-16 17:11:13.431 10266 10266 I InjectionManager: Constructor com.microsoft.office.onenote, Feature store :{}
09-16 17:11:13.431 10266 10266 I InjectionManager: featureStore :{}
,09-16 17:11:13.441  3394  4196 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:13.441 10266 10266 I Quasar  : Wifi detected off:  1474038673449
,09-16 17:11:13.451 10266 10266 I Process : Sending signal. PID: 10266 SIG: 9
,09-16 17:11:13.491  3394  3982 I ActivityManager: Process com.microsoft.office.onenote.connectionReceiverProcess (pid 10266)(adj 0) has died(54,1747)
,09-16 17:11:13.491  3394  3982 D ActivityManager: isAutoRunBlockedApp:: com.microsoft.office.onenote, Auto Run ON
,09-16 17:11:13.491 10190 10190 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
09-16 17:11:13.491 10190 10190 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,09-16 17:11:13.521 10283 10283 E Zygote  : v2
09-16 17:11:13.521 10283 10283 I libpersona: KNOX_SDCARD checking this for 10135
09-16 17:11:13.521 10283 10283 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:13.521 10283 10283 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:13.521 10283 10283 E Zygote  : accessInfo : 0
09-16 17:11:13.521 10190 10190 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
09-16 17:11:13.521 10283 10283 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,09-16 17:11:13.521  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10190
09-16 17:11:13.521  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
09-16 17:11:13.521 10190 10190 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
09-16 17:11:13.521 10190 10190 I wpa_supplicant: ssSupport state is = 1
,09-16 17:11:13.531 10190 10190 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 17:11:13.531 10190 10190 E wpa_supplicant: nl80211: Could not configure driver mode
09-16 17:11:13.531 10190 10190 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,09-16 17:11:13.531 10190 10190 E wpa_supplicant: p2p0: Failed to initialize driver interface
09-16 17:11:13.531 10190 10190 I wpa_supplicant: Blacklist: Clear (all) 
,09-16 17:11:13.531 10190 10190 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
09-16 17:11:13.531 10190 10190 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,09-16 17:11:13.541  3394  3511 I ActivityManager: Start proc 10283:com.google.android.apps.photos/u0a135 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-16 17:11:13.541  3394  3860 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,09-16 17:11:13.571 10190 10190 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,09-16 17:11:13.571  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10190
09-16 17:11:13.571  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
09-16 17:11:13.571 10190 10190 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
09-16 17:11:13.571 10190 10190 I wpa_supplicant: ssSupport state is = 1
09-16 17:11:13.571 10190 10190 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 17:11:13.581 10283 10283 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-16 17:11:13.581 10283 10283 D ActivityThread: Added TimaKeyStore provider
09-16 17:11:13.581 10190 10190 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,09-16 17:11:13.591  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:13.591  3394  3862 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-16 17:11:13.591  3394  3862 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,09-16 17:11:13.601  3394  3862 D WifiNative-wlan0: callSECApiBoolean - ID [301]
09-16 17:11:13.601 10190 10190 I wpa_supplicant: HOTSPOT20_ENABLE called ON
09-16 17:11:13.601 10190 10190 I wpa_supplicant: Blacklist: Clear (all) 
,09-16 17:11:13.601  3394  4500 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51e17b7 10283:com.google.android.apps.photos/u0a135}
,09-16 17:11:13.611  3394  3860 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,09-16 17:11:13.611 10190 10190 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-16 17:11:13.611 10190 10190 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,09-16 17:11:13.611  3394  3862 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-16 17:11:13.621  3394  3394 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,09-16 17:11:13.621  3394  3866 D HS20StateMachine: WIFI_STATE_ENABLED
09-16 17:11:13.621  3394  3394 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-16 17:11:13.621  3394  3866 D HS20StateMachine: reloadCredentialsToSupplicant
09-16 17:11:13.621  3394  3866 D HotspotDBHandler: getCredentialIds
,09-16 17:11:13.621  3394  3869 I WifiHs20Service: Message received 5011
,09-16 17:11:13.631  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 17:11:13.631 10283 10283 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:13.631  3394  3394 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
09-16 17:11:13.631 10283 10283 D RelationGraph: garbageCollect()
09-16 17:11:13.631  3394  3872 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-16 17:11:13.631  3394  4250 W SLocation: No Active Data Connection
,09-16 17:11:13.641  3940  3940 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,09-16 17:11:13.641  4298  4308 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-16 17:11:13.641 10283 10283 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
09-16 17:11:13.641  4298  4308 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-16 17:11:13.641  3394  3872 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-16 17:11:13.651  3394  4406 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 17:11:13.651 10283 10283 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:13.651  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 17:11:13.651  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:13.651  9907  9907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 17:11:13.651  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 17:11:13.651  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 17:11:13.651  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:13.651  9907  9907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 17:11:13.651  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7940b24 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dccee39 9907:com.test.thalitest/u0a177}
,09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:13.661  3394  3454 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:13.671 10190 10190 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-16 17:11:13.671  3394  3862 D WifiConfigStore: Loading config and enabling all networks 
,09-16 17:11:13.671 10298 10298 E Zygote  : v2
,09-16 17:11:13.671  3394  3866 I ActivityManager: Start proc 10298:com.samsung.hs20provider/u0a119 for content provider com.samsung.hs20provider/.Hs20Provider
09-16 17:11:13.671 10298 10298 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:13.671 10298 10298 I libpersona: KNOX_SDCARD checking this for 10119
09-16 17:11:13.671 10298 10298 I libpersona: KNOX_SDCARD not a persona
09-16 17:11:13.681 10298 10298 E Zygote  : accessInfo : 0
09-16 17:11:13.681 10298 10298 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,09-16 17:11:13.691  3940  3940 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-16 17:11:13.691  3940  3940 I HotspotTile: Provider is not defined returning false
,09-16 17:11:13.691  3940  3940 D HotspotTile: onReceive : 3, 0
,09-16 17:11:13.691  3394  3862 I WifiConfigStore: "NG700" is a verified password AP: true
,09-16 17:11:13.691  3394  3862 E WifiConfigStore: Not a HS20
,09-16 17:11:13.691  3394  3862 D WifiConfigStore: loaded 0 passpoint configs
,09-16 17:11:13.691  3394  3862 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-16 17:11:13.701  3394  3862 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-16 17:11:13.701  3394  3862 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
09-16 17:11:13.701  3394  3862 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 17:11:13.701  3394  3862 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
09-16 17:11:13.701  3394  3394 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
,09-16 17:11:13.701  3394  3394 D WifiHs20Service: reason: 2
09-16 17:11:13.701  3394  3869 I WifiHs20Service: Message received 5014
09-16 17:11:13.701  3394  3869 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
09-16 17:11:13.701  3394  3869 E WifiHs20Service: The changed config is NULL
09-16 17:11:13.701  3394  3862 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-16 17:11:13.701  3394  3862 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-16 17:11:13.701 10190 10190 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-16 17:11:13.701 10190 10190 I wpa_supplicant: resume autoscan
09-16 17:11:13.701 10190 10190 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
,09-16 17:11:13.701 10190 10190 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
,09-16 17:11:13.701 10190 10190 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-16 17:11:13.711 10190 10190 I wpa_supplicant: reset timer : RESET_TIMER 0
,09-16 17:11:13.711 10190 10190 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-16 17:11:13.711 10190 10190 I wpa_supplicant: First Scan Start
09-16 17:11:13.711 10298 10298 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:13.711 10298 10298 D ActivityThread: Added TimaKeyStore provider
09-16 17:11:13.711 10190 10190 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-16 17:11:13.711  3394  3862 D WifiNative-wlan0: Setting external_sim to 1
,09-16 17:11:13.721  3394  3862 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
,09-16 17:11:13.721  3394  3862 D WifiStateMachine: Setting OUI to DA-A1-19
,09-16 17:11:13.721 10190 10190 I wpa_supplicant: bt_status is set be DISCONNECTED
,09-16 17:11:13.741 10298 10298 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:13.741 10298 10298 D RelationGraph: garbageCollect()
,09-16 17:11:13.751  3394  3862 E WifiNative-wlan0: do suspend true
,09-16 17:11:13.751 10298 10298 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
,09-16 17:11:13.761  3394  4716 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 17:11:13.761 10298 10298 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:13.761 10298 10298 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:13.761  3394  3862 D WifiStateMachine:  p2p Needed be enabled 
09-16 17:11:13.771  3394  3861 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-16 17:11:13.771  3394  3862 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
09-16 17:11:13.771  3394  3862 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-16 17:11:13.771  3394  3862 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
09-16 17:11:13.771  3394  3862 D WifiStateMachine: setFccChannelNative: channel = 0
09-16 17:11:13.771  3394  3862 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-16 17:11:13.771  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:13.771 10283 10283 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:13.771  3152  3779 D CommandListener: Setting iface cfg
09-16 17:11:13.771  3152  3779 D CommandListener: Trying to bring up p2p0
09-16 17:11:13.771  3394  3894 E WifiScanningService: could not start HAL
09-16 17:11:13.771  3152  3772 D Netd    : Iface p2p0 link up
09-16 17:11:13.771  3394  3514 D Tethering: interfaceLinkStateChanged p2p0, true
09-16 17:11:13.771  3394  3514 D Tethering: interfaceStatusChanged p2p0, true
,09-16 17:11:13.771  3394  3861 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-16 17:11:13.781  3394  3861 D SecContentProvider: insert(), uri = 2
,09-16 17:11:13.781  3394  3394 D RttService: SCAN_AVAILABLE : 3
09-16 17:11:13.781  5063  5352 D PdnController: Interface Changed p2p0 link up
,09-16 17:11:13.781  3394  3895 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-16 17:11:13.791  3394  3862 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 17:11:13.791 10298 10298 I InjectionManager: Inside getClassLibPath caller 
09-16 17:11:13.791  3394  3861 D WifiP2pService: P2pEnablingState
,09-16 17:11:13.791  3394  3861 D WifiP2pService: P2pEnablingState{ what=147457 }
09-16 17:11:13.791  3394  3861 D WifiP2pService: P2p socket connection successful
09-16 17:11:13.791  3394  3861 D WifiP2pService: P2pEnabledState
09-16 17:11:13.791  3394  3861 D SecContentProvider: insert(), uri = 2
,09-16 17:11:13.791 10283 10283 I InjectionManager: Inside getClassLibPath caller 
09-16 17:11:13.791  3394  3861 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-16 17:11:13.791 10298 10298 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
09-16 17:11:13.791  3394  3871 E ConnectivityService: updateNetworkInfo()
09-16 17:11:13.791  3394  3871 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
09-16 17:11:13.791  3394  3394 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-16 17:11:13.791  3394  3536 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-16 17:11:13.791  3394  3536 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
09-16 17:11:13.791  3394  3536 D WifiDisplayController: disconnect
09-16 17:11:13.791  3394  3536 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-16 17:11:13.801  3394  3862 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 17:11:13.801 10190 10190 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,09-16 17:11:13.801 10190 10190 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,09-16 17:11:13.801  3394  3536 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:13.801  3394  3536 I WifiDisplayAdapter: onP2pDisconnected
09-16 17:11:13.801  3394  3536 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-16 17:11:13.801  3394  3536 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-16 17:11:13.801 10283 10283 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
09-16 17:11:13.801  3940  3940 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-16 17:11:13.811  3940  3940 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-16 17:11:13.811  3940  3940 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-16 17:11:13.811  3394  3982 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-16 17:11:13.811  3940  3940 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-16 17:11:13.811  4298  4606 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
09-16 17:11:13.811  3940  3940 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-16 17:11:13.821  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{745e68d u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe8d7a9 10104:com.samsung.android.app.FileShareClient/5005}
,09-16 17:11:13.821 10104 10104 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-16 17:11:13.821 10298 10298 D InjectionManager: InjectionManager
,09-16 17:11:13.821 10298 10298 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
,09-16 17:11:13.831 10104 10104 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-16 17:11:13.831 10298 10298 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
09-16 17:11:13.831 10298 10298 I InjectionManager: featureStore :{}
09-16 17:11:13.831 10104 10104 D FileShare-Client: Outbound.stopDelayTimer - 
,09-16 17:11:13.831 10298 10309 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
09-16 17:11:13.831 10298 10309 D HotspotProvider: CREDENTIAL
09-16 17:11:13.831 10298 10309 D HotspotProvider: No prepend tags
,09-16 17:11:13.841  3394  4196 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{745e68d u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d8f812e 10116:com.samsung.android.app.FileShareServer/5005}
,09-16 17:11:13.851  3394  3866 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
09-16 17:11:13.851 10116 10116 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-16 17:11:13.851  3394  3866 D HS20StateMachine: enter : DiscoveringState
,09-16 17:11:13.851 10116 10116 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-16 17:11:13.851 10116 10116 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-16 17:11:13.851  3394  3861 E WifiP2pService: Failed to set my phone number info into probe response
,09-16 17:11:13.861  3394  3861 D WifiNative-p2p0: p2pGetDeviceAddress
,09-16 17:11:13.861  3394  3861 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a6:c7:2d
,09-16 17:11:13.861  3394  4716 I ActivityManager: Killing 9703:com.google.android.apps.docs/u0a98 (adj 15): DHA:empty #33
,09-16 17:11:13.881  3394  3861 D WifiP2pService: DeviceAddress: 4e:c7:2d
,09-16 17:11:13.881  3394  3536 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7 edge
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  deviceAddress: 4e:66:41:a6:c7:2d
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  primary type: 10-0050F204-5
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  secondary type: null
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  wps: 0
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  grpcapab: 0
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  devcapab: 0
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  status: 3
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  wfdInfo: null
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  groupownerAddress: null
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  GOdeviceName: null
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  interfaceAddress: 
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  SConnectInfo : null
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  contactInfoHash : null
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  ssDevInfo : 0
09-16 17:11:13.881  3394  3536 D WifiDisplayController:  iconIdx : 0
,09-16 17:11:13.891  3394  3861 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-16 17:11:13.891  3394  3861 D WifiP2pService: InactiveState
09-16 17:11:13.891  3394  3861 D WifiP2pService: InactiveState{ what=143376 }
,09-16 17:11:13.891  3394  3861 D WifiP2pService: P2pEnabledState{ what=143376 }
09-16 17:11:13.891  3394  3861 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,09-16 17:11:13.921  3394  4500 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,09-16 17:11:13.951  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:14.131  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:14.131 10283 10283 W Primes  : Memory instrumentations are turned off.
,09-16 17:11:14.141 10283 10283 W Primes  : Timer instrumentations are turned off.
,09-16 17:11:14.151 10283 10283 W Primes  : Crash monitoring is turned off.
,09-16 17:11:14.171 10283 10283 W Primes  : Network monitoring is turned off.
09-16 17:11:14.171 10283 10283 W Primes  : Package metrics are turned off by default
,09-16 17:11:14.211 10283 10283 D InjectionManager: InjectionManager
09-16 17:11:14.211 10283 10283 D InjectionManager: fillFeatureStoreMap com.google.android.apps.photos
,09-16 17:11:14.211 10283 10283 I InjectionManager: Constructor com.google.android.apps.photos, Feature store :{}
09-16 17:11:14.211 10283 10283 I InjectionManager: featureStore :{}
,09-16 17:11:14.231  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{745a6a8 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51e17b7 10283:com.google.android.apps.photos/u0a135}
,09-16 17:11:14.251  3394  4984 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51e17b7 10283:com.google.android.apps.photos/u0a135}
,09-16 17:11:14.291  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f5f55c1 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51e17b7 10283:com.google.android.apps.photos/u0a135}
,09-16 17:11:14.301  3152  3772 D Netd    : Iface wlan0 link up
09-16 17:11:14.301 10190 10190 I wpa_supplicant: nl80211: Received scan results (31 BSSes)
09-16 17:11:14.301  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 17:11:14.301  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
,09-16 17:11:14.301  5063  5350 D PdnController: Interface Changed wlan0 link up
,09-16 17:11:14.301 10190 10190 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
09-16 17:11:14.301 10190 10190 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
09-16 17:11:14.301 10190 10190 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-16 17:11:14.301 10190 10190 I wpa_supplicant:    allow  - level is under -85dBm [-48] or selected nid [-1] [0]
,09-16 17:11:14.301 10190 10190 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
,09-16 17:11:14.301 10190 10190 I wpa_supplicant:    allow  - level is under -85dBm [-48] or selected nid [-1] [0]
,09-16 17:11:14.301 10190 10190 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz level=-48) 
,09-16 17:11:14.301  3394  3455 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c3a708 7850:com.sec.android.daemonapp/u0a166}
,09-16 17:11:14.311  7850  7850 D [WeatherWidget(1240)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,09-16 17:11:14.311  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:14.311  7850  7850 D [WeatherWidget(1240)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,09-16 17:11:14.331  3394  3455 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{230f600 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8f9235d 9796:com.sec.android.app.samsungapps/u0a16}
,09-16 17:11:14.361 10321 10321 E Zygote  : v2
09-16 17:11:14.361 10321 10321 I libpersona: KNOX_SDCARD checking this for 10012
09-16 17:11:14.361 10321 10321 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:14.361 10321 10321 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:14.361 10321 10321 E Zygote  : accessInfo : 0
09-16 17:11:14.361  3394  4196 I ActivityManager: Start proc 10321:com.microsoft.office.onenote.connectionReceiverProcess/u0a12 for broadcast-5 com.microsoft.office.onenote/com.microsoft.bing.datamining.quasar.api.ConnectionChangeReceiver
09-16 17:11:14.361 10321 10321 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.microsoft.office.onenote.connectionReceiverProcess 
,09-16 17:11:14.381  3394  3862 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 17:11:14.381  3394  3394 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,09-16 17:11:14.381  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ae5ca7 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c0ab582 3940:com.android.systemui/u0a65}
,09-16 17:11:14.391  3394  4196 I ActivityManager: Killing 9726:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #33
,09-16 17:11:14.401 10321 10321 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:14.401 10321 10321 D ActivityThread: Added TimaKeyStore provider
,09-16 17:11:14.411  3394  4406 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,09-16 17:11:14.421  3394  4984 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f58628a u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a28554 10321:com.microsoft.office.onenote.connectionReceiverProcess/u0a12}
,09-16 17:11:14.431 10321 10321 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 17:11:14.431 10321 10321 D RelationGraph: garbageCollect()
,09-16 17:11:14.431 10321 10321 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.microsoft.office.onenote rsrc of package com.microsoft.office.onenote
,09-16 17:11:14.431 10190 10190 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-16 17:11:14.441  3394  4196 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:11:14.441 10321 10321 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:14.441  3152  3772 D Netd    : Iface wlan0 link up
09-16 17:11:14.441  3152  3772 D Netd    : Iface wlan0 link up
,09-16 17:11:14.441  3152  3772 D Netd    : Iface wlan0 link up
09-16 17:11:14.441 10321 10321 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:14.441  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 17:11:14.441  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
09-16 17:11:14.441  5063  5352 D PdnController: Interface Changed wlan0 link up
,09-16 17:11:14.441  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
,09-16 17:11:14.441  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
,09-16 17:11:14.451  5063  5075 D PdnController: Interface Changed wlan0 link up
09-16 17:11:14.451 10321 10321 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:14.451  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 17:11:14.451  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
09-16 17:11:14.451 10190 10190 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-16 17:11:14.451  5063  5073 D PdnController: Interface Changed wlan0 link up
,09-16 17:11:14.451 10190 10190 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,09-16 17:11:14.451 10190 10190 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,09-16 17:11:14.451 10321 10321 W System  : ClassLoader referenced unknown path: /system/app/OneNote/lib/arm
,09-16 17:11:14.461  3394  3862 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 17:11:14.461  3394  3862 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 17:11:14.461 10321 10321 D InjectionManager: InjectionManager
,09-16 17:11:14.461 10321 10321 D InjectionManager: fillFeatureStoreMap com.microsoft.office.onenote
09-16 17:11:14.461 10190 10190 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
09-16 17:11:14.461 10321 10321 I InjectionManager: Constructor com.microsoft.office.onenote, Feature store :{}
09-16 17:11:14.461 10321 10321 I InjectionManager: featureStore :{}
,09-16 17:11:14.471  3394  4984 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:14.471 10321 10321 I Process : Sending signal. PID: 10321 SIG: 9
09-16 17:11:14.471 10190 10190 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,09-16 17:11:14.471 10190 10190 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-16 17:11:14.471 10190 10190 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-16 17:11:14.481  3152  3772 D Netd    : Iface wlan0 link up
09-16 17:11:14.481 10190 10190 I wpa_supplicant: Blacklist: Clear (temp) 
,09-16 17:11:14.481  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
,09-16 17:11:14.481  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
,09-16 17:11:14.481  5063  5350 D PdnController: Interface Changed wlan0 link up
,09-16 17:11:14.481  3394  3862 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-16 17:11:14.491  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:14.491  3394  4255 I ActivityManager: Process com.microsoft.office.onenote.connectionReceiverProcess (pid 10321)(adj 0) has died(58,1746)
,09-16 17:11:14.491  3394  4255 D ActivityManager: isAutoRunBlockedApp:: com.microsoft.office.onenote, Auto Run ON
,09-16 17:11:14.501  3394  3862 V AlarmManager:  remove PendingIntent] PendingIntent{8beffbf: PendingIntentRecord{7f9468c android broadcastIntent}}
,09-16 17:11:14.501  3394  3862 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,09-16 17:11:14.501  3394  3862 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-16 17:11:14.501  3394  3871 E ConnectivityService: updateNetworkInfo()
09-16 17:11:14.501  3394  3871 D ConnectivityService: Got NetworkAgent Messenger
09-16 17:11:14.501  3394  3871 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 17:11:14.501  3394  3871 D ConnectivityService: NetworkAgent connected
,09-16 17:11:14.511  3152  3779 D CommandListener: Setting iface cfg
,09-16 17:11:14.511  3394  3511 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f58628a u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c7ab8e2 10079:com.samsung.android.sm.policy/u0a142}
,09-16 17:11:14.511  3394  3394 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-16 17:11:14.511  3394  3394 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-16 17:11:14.511  3394  3394 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-16 17:11:14.511  3394  3869 I WifiHs20Service: Message received 5007
09-16 17:11:14.511  3394  3394 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,09-16 17:11:14.521  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 17:11:14.521  4298  4298 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-16 17:11:14.531  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{483131 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e8534f5 10040:com.sec.android.diagmonagent/1000}
,09-16 17:11:14.531 10040 10040 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-16 17:11:14.531 10040 10040 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-16 17:11:14.531 10040 10040 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-16 17:11:14.531 10040 10040 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-16 17:11:14.541 10336 10336 E Zygote  : v2
09-16 17:11:14.541 10336 10336 I libpersona: KNOX_SDCARD checking this for 1000
09-16 17:11:14.541 10336 10336 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:14.541 10336 10336 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:14.551  3394  3454 I ActivityManager: Start proc 10336:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,09-16 17:11:14.551 10336 10336 E Zygote  : accessInfo : 0
,09-16 17:11:14.551  3394  3862 D WifiStateMachine: Start Dhcp Watchdog 2
,09-16 17:11:14.561  3394  3862 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 17:11:14.561  3394  3454 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{483131 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b0f4621 9754:com.enhance.gameservice/u0a111}
,09-16 17:11:14.571  3394  3862 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,09-16 17:11:14.571  3394  3871 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,09-16 17:11:14.581 10336 10336 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:14.581 10336 10336 D ActivityThread: Added TimaKeyStore provider
09-16 17:11:14.581  3394  3871 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]
09-16 17:11:14.581  3394  3871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-16 17:11:14.581  3394  3454 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{483131 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{76430fb 10053:com.sec.knox.switcher/1000}
,09-16 17:11:14.581 10053 10053 I usagelog: received in receiver
09-16 17:11:14.581 10053 10053 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-16 17:11:14.581 10053 10053 I KnoxUsageLogPro: premStatus:2
,09-16 17:11:14.581 10053 10053 I KnoxUsageLogPro: isEulaShown : false
09-16 17:11:14.581 10053 10053 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-16 17:11:14.591  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 17:11:14.601  3394  4149 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7940b24 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d3271c 10336:com.samsung.android.securitylogagent/1000}
,09-16 17:11:14.611 10336 10336 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 17:11:14.611 10336 10336 D RelationGraph: garbageCollect()
,09-16 17:11:14.621 10336 10336 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package com.samsung.android.securitylogagent
,09-16 17:11:14.621  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{483131 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c7ab8e2 10079:com.samsung.android.sm.policy/u0a142}
,09-16 17:11:14.621  3394  4196 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:11:14.621 10336 10336 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:14.621 10336 10336 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:14.631 10336 10336 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:14.641 10336 10336 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,09-16 17:11:14.641 10336 10336 D InjectionManager: InjectionManager
09-16 17:11:14.641 10336 10336 D InjectionManager: fillFeatureStoreMap com.samsung.android.securitylogagent
,09-16 17:11:14.641 10336 10336 I InjectionManager: Constructor com.samsung.android.securitylogagent, Feature store :{}
09-16 17:11:14.641 10336 10336 I InjectionManager: featureStore :{}
,09-16 17:11:14.661 10349 10349 E Zygote  : v2
09-16 17:11:14.661 10349 10349 I libpersona: KNOX_SDCARD checking this for 10012
09-16 17:11:14.661 10349 10349 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:14.661 10349 10349 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 17:11:14.661  3394  3857 I ActivityManager: Start proc 10349:com.microsoft.office.onenote.connectionReceiverProcess/u0a12 for broadcast-5 com.microsoft.office.onenote/com.microsoft.bing.datamining.quasar.api.ConnectionChangeReceiver
,09-16 17:11:14.661  3394  3857 I ActivityManager: Killing 9741:com.sec.android.widgetapp.samsungapps/u0a110 (adj 15): DHA:empty #33
,09-16 17:11:14.661 10349 10349 E Zygote  : accessInfo : 0
,09-16 17:11:14.661 10349 10349 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.microsoft.office.onenote.connectionReceiverProcess 
,09-16 17:11:14.671  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:14.681  3394  3862 E WifiNative-wlan0: do suspend false
,09-16 17:11:14.691  3394  4984 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.samsungapps, Auto Run ON
,09-16 17:11:14.701 10349 10349 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:14.701  3394  6515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-16 17:11:14.701 10349 10349 D ActivityThread: Added TimaKeyStore provider
09-16 17:11:14.701  3394  3862 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
09-16 17:11:14.701  3394  3861 D WifiP2pService: InactiveState{ what=143375 }
,09-16 17:11:14.701  3394  3861 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-16 17:11:14.711  3394  4255 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{483131 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{57a5f25 10349:com.microsoft.office.onenote.connectionReceiverProcess/u0a12}
,09-16 17:11:14.721 10361 10361 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-16 17:11:14.721 10349 10349 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 17:11:14.721 10361 10361 I dhcpcd  : version 5.5.6 starting
09-16 17:11:14.721 10349 10349 D RelationGraph: garbageCollect()
,09-16 17:11:14.721 10349 10349 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.microsoft.office.onenote rsrc of package com.microsoft.office.onenote
09-16 17:11:14.721 10361 10361 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-16 17:11:14.721  3394  4406 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 17:11:14.721 10349 10349 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:14.731 10349 10349 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:14.731 10349 10349 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:14.741 10349 10349 W System  : ClassLoader referenced unknown path: /system/app/OneNote/lib/arm
,09-16 17:11:14.751 10349 10349 D InjectionManager: InjectionManager
,09-16 17:11:14.751 10349 10349 D InjectionManager: fillFeatureStoreMap com.microsoft.office.onenote
09-16 17:11:14.751 10349 10349 I InjectionManager: Constructor com.microsoft.office.onenote, Feature store :{}
09-16 17:11:14.751 10349 10349 I InjectionManager: featureStore :{}
,09-16 17:11:14.751  3394  4255 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:14.761 10349 10349 I Process : Sending signal. PID: 10349 SIG: 9
,09-16 17:11:14.791  3394  3455 I ActivityManager: Process com.microsoft.office.onenote.connectionReceiverProcess (pid 10349)(adj 0) has died(56,1746)
,09-16 17:11:14.791  3394  3455 D ActivityManager: isAutoRunBlockedApp:: com.microsoft.office.onenote, Auto Run ON
,09-16 17:11:14.791 10361 10361 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-16 17:11:14.801 10361 10361 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-16 17:11:14.801 10361 10361 I dhcpcd  : bssid match
,09-16 17:11:14.801 10361 10361 I dhcpcd  : wlan0: rebinding lease of 192.168.1.107
,09-16 17:11:14.851  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:14.871 10361 10361 I dhcpcd  : wlan0: acknowledged 192.168.1.107 from 192.168.1.1
,09-16 17:11:14.921 10361 10361 I dhcpcd  : wlan0: leased 192.168.1.107 for 172800 seconds
,09-16 17:11:14.931  3394  3871 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,09-16 17:11:15.031  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:15.041  3394  4406 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-16 17:11:15.041  3394  4406 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-16 17:11:15.051  3394  4406 D WifiService: setWifiEnabled: false pid=9907, uid=10177
,09-16 17:11:15.051  3394  4406 D SettingsProvider: isChangeAllowed() : name = wifi_on
,09-16 17:11:15.051  3394  3865 D WifiStateMachine: setFccChannel: channel = 0
,09-16 17:11:15.051  3394  3865 D WifiController: [FCC]setFccChannel() is called !!!
09-16 17:11:15.051  3394  3865 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
09-16 17:11:15.051  3394  3865 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
09-16 17:11:15.051  3394  3865 D SecContentProvider: insert(), uri = 2
09-16 17:11:15.051  3394  3862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
09-16 17:11:15.051  3394  3862 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-16 17:11:15.071  3394  3862 D WifiBigDataLog: init : 
,09-16 17:11:15.081  3394  3862 D WifiStateMachine: setFccChannelNative: channel = 0
09-16 17:11:15.081  3394  3862 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-16 17:11:15.091  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fb35eab u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a366578 5051:com.samsung.android.providers.context/u0a9}
,09-16 17:11:15.101  3394  3862 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 17:11:15.101  3394  3862 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 17:11:15.101  3394  3862 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,09-16 17:11:15.111  3394  3862 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 17:11:15.111  3394  3862 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 17:11:15.111  3940  4129 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 17:11:15.111  3940  4129 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
09-16 17:11:15.111  3394  3862 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 17:11:15.111  3394  3862 E WifiNative-wlan0: do suspend true
,09-16 17:11:15.121  3394  3861 D WifiP2pService: InactiveState{ what=143375 }
09-16 17:11:15.121  3394  3861 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-16 17:11:15.131  3152  3779 D CommandListener: Clearing all IP addresses on wlan0
,09-16 17:11:15.131  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 17:11:15.141  3394  3871 E ConnectivityService: updateNetworkInfo()
09-16 17:11:15.141  3394  3871 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]
09-16 17:11:15.141  3394  3871 E ConnectivityService: updateNetworkInfo()
09-16 17:11:15.141  3394  3871 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
09-16 17:11:15.141  3394  3871 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,09-16 17:11:15.141  3394  3871 D NtpTrustedTime: currentTimeMillis() cache hit
,09-16 17:11:15.141  3394  3871 V NetworkStats: updateIfacesLocked()
09-16 17:11:15.141  3394  3871 V NetworkStats: performPollLocked(flags=0x1)
,09-16 17:11:15.151  3394  3394 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-16 17:11:15.151  3394  3871 D NetworkStatsRecorder: entry.iface is null
,09-16 17:11:15.151  3394  3394 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-16 17:11:15.151  3394  3871 D NetworkStatsRecorder: entry.iface is null
09-16 17:11:15.151  3394  3871 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 17:11:15.151  3394  3871 D NetworkStatsRecorder: entry.iface is null
09-16 17:11:15.151  3394  3394 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
,09-16 17:11:15.151  3394  3871 D NetworkStatsRecorder: entry.iface is null
09-16 17:11:15.151  3394  3394 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid
09-16 17:11:15.151  3394  3871 V NetworkStats: performPollLocked() took 7ms
09-16 17:11:15.151  3394  3394 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-16 17:11:15.151  3394  3394 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
09-16 17:11:15.151  3394  3869 I WifiHs20Service: Message received 5007
,09-16 17:11:15.151  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 17:11:15.161  4298  4298 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-16 17:11:15.161  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9799908 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e8534f5 10040:com.sec.android.diagmonagent/1000}
,09-16 17:11:15.161 10040 10040 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
09-16 17:11:15.171  3394  3861 D WifiP2pService: InactiveState{ what=131204 }
09-16 17:11:15.171  3394  3394 D RttService: SCAN_AVAILABLE : 1
09-16 17:11:15.171  3394  3895 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-16 17:11:15.171 10190 10190 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
09-16 17:11:15.171  3394  3861 D WifiP2pService: P2pEnabledState{ what=131204 }
09-16 17:11:15.171 10190 10190 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
09-16 17:11:15.171  3394  3871 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 17:11:15.171  3394 10334 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-16 17:11:15.171  3394  3871 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]
09-16 17:11:15.171  3394 10334 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Disconnected - quitting
09-16 17:11:15.171  3394  3871 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-16 17:11:15.171 10040 10040 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-16 17:11:15.171 10040 10040 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-16 17:11:15.171  3394  3861 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-16 17:11:15.171  3394 10334 D NetworkMonitor: unregisterReceiver Captive portal receiver
09-16 17:11:15.171  3394  3871 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=false
09-16 17:11:15.171  3394 10334 E NetworkMonitor: IllegalArgumentException: java.lang.IllegalArgumentException: Receiver not registered: com.android.server.connectivity.NetworkMonitor$1@3daaac6
09-16 17:11:15.171  3394  3871 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '81 network destroy 503' failed with '400 81 destroyNetwork() failed (Machine is not on the network)'
09-16 17:11:15.171  3394 10334 W System.err: java.lang.IllegalArgumentException: Receiver not registered: com.android.server.connectivity.NetworkMonitor$1@3daaac6
,09-16 17:11:15.171  3394  3871 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
09-16 17:11:15.171 10040 10040 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
09-16 17:11:15.171  3394 10334 W System.err: 	at android.app.LoadedApk.forgetReceiverDispatcher(LoadedApk.java:878)
09-16 17:11:15.171  3394 10334 W System.err: 	at android.app.ContextImpl.unregisterReceiver(ContextImpl.java:1279)
09-16 17:11:15.171  3152  3779 E Netd    : no such netId 503
09-16 17:11:15.171  3394  3871 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
09-16 17:11:15.171  3394 10334 W System.err: 	at com.android.server.connectivity.NetworkMonitor$DefaultState.processMessage(NetworkMonitor.java:380)
09-16 17:11:15.171  3394 10334 W System.err: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:968)
09-16 17:11:15.171  3394 10334 W System.err: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:791)
09-16 17:11:15.171  3394 10334 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 17:11:15.171  3394 10334 W System.err: 	at android.os.Looper.loop(Looper.java:158)
,09-16 17:11:15.171  3394  3394 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
09-16 17:11:15.171  3394 10334 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 17:11:15.171  3394  3394 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
09-16 17:11:15.171  3394  3862 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-16 17:11:15.171  4166  4179 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=84]
09-16 17:11:15.171  3394  3871 D ConnectivityService: nai.networkMonitor.doQuit()
,09-16 17:11:15.171  3394  3871 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: doQuit - quitNow()
09-16 17:11:15.171  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 17:11:15.171  3394  3871 E ConnectivityService: updateNetworkInfo()
09-16 17:11:15.171  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 17:11:15.171  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,09-16 17:11:15.171  4166  4166 I PeopleDataManager: removeNotification
09-16 17:11:15.171  4166  4166 I NotificationParser: getNotiType:android,null
09-16 17:11:15.171  4166  4166 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 17:11:15.171  4166  4166 D PeopleDataManager: removeNotiInfo =null
09-16 17:11:15.171  4166  4176 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
,09-16 17:11:15.181  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 17:11:15.181  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 17:11:15.181  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 17:11:15.181  4166  4166 I PeopleDataManager: removeNotification
09-16 17:11:15.181  4166  4166 I NotificationParser: getNotiType:android,null
,09-16 17:11:15.181  4166  4166 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 17:11:15.181  4166  4166 D PeopleDataManager: removeNotiInfo =null
09-16 17:11:15.181  3394  3860 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 17:11:15.181  3394  3860 D NtpTrustedTime: currentTimeMillis() cache hit
,09-16 17:11:15.181  3394  3536 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:15.181  3940  3940 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-16 17:11:15.181  3394  3536 I WifiDisplayAdapter: onP2pDisconnected
09-16 17:11:15.181  3394  3536 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-16 17:11:15.181  3394  3536 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-16 17:11:15.191  3394  4397 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9799908 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b0f4621 9754:com.enhance.gameservice/u0a111}
,09-16 17:11:15.201  3394  3861 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-16 17:11:15.201  3394  3871 E ConnectivityService: updateNetworkInfo()
09-16 17:11:15.201  3394  3871 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,09-16 17:11:15.201  3394  3394 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-16 17:11:15.201  3394  3536 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
09-16 17:11:15.201  3394  3536 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-16 17:11:15.201  3394  3536 D WifiDisplayController: disconnect
09-16 17:11:15.201  3394  3536 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-16 17:11:15.211  3394  4397 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9799908 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{76430fb 10053:com.sec.knox.switcher/1000}
,09-16 17:11:15.211 10053 10053 I usagelog: received in receiver
,09-16 17:11:15.211 10053 10053 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-16 17:11:15.211  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:15.211 10053 10053 I KnoxUsageLogPro: premStatus:2
,09-16 17:11:15.211 10053 10053 I KnoxUsageLogPro: isEulaShown : false
09-16 17:11:15.211 10053 10053 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-16 17:11:15.221  3394  3861 D SecContentProvider: insert(), uri = 2
,09-16 17:11:15.221  3394  3861 D WifiP2pService: P2pDisablingState
09-16 17:11:15.221  3394  3861 D WifiP2pService: P2pDisablingState{ what=147458 }
,09-16 17:11:15.221  3394  3861 D WifiP2pService: p2p socket connection lost
09-16 17:11:15.221  3394  3861 D SecContentProvider: insert(), uri = 2
,09-16 17:11:15.221  3394  3862 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 17:11:15.221  3394  3861 D WifiP2pService: P2pDisabledState
,09-16 17:11:15.221  3394  3862 E WifiNative-wlan0: do suspend true
09-16 17:11:15.221  3940  3940 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-16 17:11:15.221  3940  3940 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-16 17:11:15.221  3940  3940 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-16 17:11:15.221  3394  4196 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-16 17:11:15.221  3940  3940 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-16 17:11:15.231  3394  3536 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 17:11:15.231  3394  3536 I WifiDisplayAdapter: onP2pDisconnected
09-16 17:11:15.231  3394  3536 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-16 17:11:15.231  3394  3536 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-16 17:11:15.231  3394  3861 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-16 17:11:15.231  3394  3861 D WifiP2pService: DefaultState{ what=143375 }
09-16 17:11:15.231  3940  3940 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-16 17:11:15.251  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9799908 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c7ab8e2 10079:com.samsung.android.sm.policy/u0a142}
,09-16 17:11:15.251  3152  3779 D CommandListener: Clearing all IP addresses on wlan0
,09-16 17:11:15.251  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 17:11:15.261  3394  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f473a87 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe8d7a9 10104:com.samsung.android.app.FileShareClient/5005}
,09-16 17:11:15.261 10104 10104 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-16 17:11:15.261 10104 10104 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-16 17:11:15.261 10104 10104 D FileShare-Client: Outbound.stopDelayTimer - 
,09-16 17:11:15.271  3394  3862 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-16 17:11:15.271 10190 10190 I wpa_supplicant: Blacklist: Clear (all) 
09-16 17:11:15.271 10190 10190 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,09-16 17:11:15.281 10390 10390 E Zygote  : v2
09-16 17:11:15.281 10390 10390 I libpersona: KNOX_SDCARD checking this for 10012
09-16 17:11:15.281 10390 10390 I libpersona: KNOX_SDCARD not a persona
,09-16 17:11:15.281 10390 10390 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 17:11:15.281 10390 10390 E Zygote  : accessInfo : 0
09-16 17:11:15.281 10390 10390 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.microsoft.office.onenote.connectionReceiverProcess 
,09-16 17:11:15.301  3394  3511 I ActivityManager: Start proc 10390:com.microsoft.office.onenote.connectionReceiverProcess/u0a12 for broadcast-5 com.microsoft.office.onenote/com.microsoft.bing.datamining.quasar.api.ConnectionChangeReceiver
,09-16 17:11:15.301  3394  3394 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-16 17:11:15.301  3394  3394 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-16 17:11:15.301  3394  3394 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
09-16 17:11:15.301  3394  3394 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-16 17:11:15.301  3394  3869 I WifiHs20Service: Message received 5007
,09-16 17:11:15.301  3394  3394 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,09-16 17:11:15.301  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 17:11:15.301  4298  4298 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-16 17:11:15.301  3394  3860 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,09-16 17:11:15.311  3394  3862 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 17:11:15.321 10390 10390 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 17:11:15.321 10390 10390 D ActivityThread: Added TimaKeyStore provider
09-16 17:11:15.321  3152  3772 D Netd    : Iface p2p0 link up
09-16 17:11:15.321  3394  3514 D Tethering: interfaceLinkStateChanged p2p0, true
09-16 17:11:15.321  3394  3514 D Tethering: interfaceStatusChanged p2p0, true
09-16 17:11:15.321  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 17:11:15.321  5063  5075 D PdnController: Interface Changed p2p0 link up
,09-16 17:11:15.321  3940  3940 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,09-16 17:11:15.321 10190 10190 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-16 17:11:15.331  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 17:11:15.331 10190 10190 I wpa_supplicant: wlan0: CTRL-EVENT-BIGDATA-DISCONNECT 2 31 6 3 f4:f2:6d 2437 20 -48 130 2 1 0 0 35 -91 0 0
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 17:11:15.331  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:15.331  9907  9907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 17:11:15.331 10190 10190 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-16 17:11:15.331  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 17:11:15.331  9907  9907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 17:11:15.331  9907  9907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 17:11:15.331  9907  9907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 17:11:15.331  3152  3772 D Netd    : Iface wlan0 link up
,09-16 17:11:15.331  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 17:11:15.331  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
,09-16 17:11:15.341  5063  5073 D PdnController: Interface Changed wlan0 link up
09-16 17:11:15.341  3940  3940 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-16 17:11:15.341  3940  3940 I HotspotTile: Provider is not defined returning false
09-16 17:11:15.341  3940  3940 D HotspotTile: onReceive : 0, 0
,09-16 17:11:15.341  3394  3982 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f473a87 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d8f812e 10116:com.samsung.android.app.FileShareServer/5005}
,09-16 17:11:15.351  3394  3394 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,09-16 17:11:15.351  3394  3394 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-16 17:11:15.351  3394  3394 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
09-16 17:11:15.351  3394  3869 I WifiHs20Service: Message received 5011
,09-16 17:11:15.351  3394  3862 D WifiBigDataLog: getJsonFormat() - feature : DISC
,09-16 17:11:15.351  3394  3862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-16 17:11:15.361  3394  3872 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-16 17:11:15.361  3394  4149 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{9799908 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{933db4 10390:com.microsoft.office.onenote.connectionReceiverProcess/u0a12}
,09-16 17:11:15.361  3394 10335 V AlarmManager:  remove PendingIntent] PendingIntent{8b64ddd: PendingIntentRecord{91c2207 android broadcastIntent}}
,09-16 17:11:15.371  3394  3394 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
,09-16 17:11:15.371 10116 10116 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-16 17:11:15.371  3394  3394 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,09-16 17:11:15.371  4166  6338 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
,09-16 17:11:15.371  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 17:11:15.371  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 17:11:15.371  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 17:11:15.371  4166  4166 I PeopleDataManager: removeNotification
09-16 17:11:15.371  4166  4166 I NotificationParser: getNotiType:android,null
09-16 17:11:15.371  4166  4166 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 17:11:15.371  4298  4624 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-16 17:11:15.371  4166  4166 D PeopleDataManager: removeNotiInfo =null
,09-16 17:11:15.371 10116 10116 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-16 17:11:15.371  4298  4624 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-16 17:11:15.371  3394  3872 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-16 17:11:15.381  3394  3862 D WifiBigDataLog: init : 
09-16 17:11:15.381 10116 10116 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-16 17:11:15.381  3394  3860 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,09-16 17:11:15.381  3394  4255 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{746ad52 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e8534f5 10040:com.sec.android.diagmonagent/1000}
,09-16 17:11:15.391 10040 10040 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-16 17:11:15.391  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 17:11:15.391 10040 10040 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,09-16 17:11:15.391 10040 10040 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-16 17:11:15.391 10390 10390 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 17:11:15.401 10390 10390 D RelationGraph: garbageCollect()
,09-16 17:11:15.401 10390 10390 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.microsoft.office.onenote rsrc of package com.microsoft.office.onenote
09-16 17:11:15.401  3394  4255 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{746ad52 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b0f4621 9754:com.enhance.gameservice/u0a111}
,09-16 17:11:15.401  3394  4149 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 17:11:15.401 10390 10390 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 17:11:15.411 10390 10390 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 17:11:15.411  3394  4255 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{746ad52 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{76430fb 10053:com.sec.knox.switcher/1000}
,09-16 17:11:15.411 10053 10053 I usagelog: received in receiver
09-16 17:11:15.411 10053 10053 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-16 17:11:15.411 10053 10053 I KnoxUsageLogPro: premStatus:2
,09-16 17:11:15.411 10053 10053 I KnoxUsageLogPro: isEulaShown : false
,09-16 17:11:15.411 10053 10053 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-16 17:11:15.411 10390 10390 I InjectionManager: Inside getClassLibPath caller 
,09-16 17:11:15.421 10390 10390 W System  : ClassLoader referenced unknown path: /system/app/OneNote/lib/arm
,09-16 17:11:15.421  3394  4445 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{746ad52 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{933db4 10390:com.microsoft.office.onenote.connectionReceiverProcess/u0a12}
,09-16 17:11:15.431 10390 10390 D InjectionManager: InjectionManager
,09-16 17:11:15.431 10390 10390 D InjectionManager: fillFeatureStoreMap com.microsoft.office.onenote
09-16 17:11:15.431 10390 10390 I InjectionManager: Constructor com.microsoft.office.onenote, Feature store :{}
09-16 17:11:15.431 10390 10390 I InjectionManager: featureStore :{}
,09-16 17:11:15.441  3394  4984 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:15.441 10390 10390 I Process : Sending signal. PID: 10390 SIG: 9
,09-16 17:11:15.451  3394  4149 I ActivityManager: Process com.microsoft.office.onenote.connectionReceiverProcess (pid 10390)(adj 0) has died(59,1746)
,09-16 17:11:15.451  3394  4149 D ActivityManager: isAutoRunBlockedApp:: com.microsoft.office.onenote, Auto Run ON
,09-16 17:11:15.461 10190 10190 I wpa_supplicant: Blacklist: Clear (all) 
,09-16 17:11:15.461 10190 10190 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-16 17:11:15.471  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{746ad52 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c7ab8e2 10079:com.samsung.android.sm.policy/u0a142}
,09-16 17:11:15.481  3394  4500 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{44eead9 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dccee39 9907:com.test.thalitest/u0a177}
,09-16 17:11:15.481  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:15.481  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:15.481  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:15.491  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:15.491  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:15.491  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:15.491  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:15.491  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:15.491  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:15.491  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:15.491  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:15.491  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 17:11:15.491  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:15.491  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:15.491  3394  4397 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:15.501  3394  4054 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{44eead9 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d3271c 10336:com.samsung.android.securitylogagent/1000}
,09-16 17:11:15.511  3152  3772 D Netd    : Iface wlan0 link up
,09-16 17:11:15.511  3152  3772 D Netd    : Iface wlan0 link up
09-16 17:11:15.511  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 17:11:15.511  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
09-16 17:11:15.511  5063  5350 D PdnController: Interface Changed wlan0 link up
09-16 17:11:15.511  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 17:11:15.511  3394  3514 D Tethering: interfaceStatusChanged wlan0, true
,09-16 17:11:15.511  5063  5352 D PdnController: Interface Changed wlan0 link up
,09-16 17:11:15.511  3394  4054 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dfe4c9e u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a366578 5051:com.samsung.android.providers.context/u0a9}
09-16 17:11:15.511  3152  3772 D Netd    : Iface p2p0 link down
09-16 17:11:15.511  3394  3514 D Tethering: interfaceLinkStateChanged p2p0, false
09-16 17:11:15.511  3394  3514 D Tethering: interfaceStatusChanged p2p0, false
,09-16 17:11:15.521  5063  5075 D PdnController: Interface Changed p2p0 link down
,09-16 17:11:15.571  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:15.751  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:15.931  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:16.041  3152  3772 D Netd    : Iface wlan0 link down
,09-16 17:11:16.041  3394  3514 D Tethering: interfaceLinkStateChanged wlan0, false
09-16 17:11:16.041  3394  3514 D Tethering: interfaceStatusChanged wlan0, false
,09-16 17:11:16.041  5063  5352 D PdnController: Interface Changed wlan0 link down
,09-16 17:11:16.041 10190 10190 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 17:11:16.111  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:16.141  3394  3862 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-16 17:11:16.151  3394  3394 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,09-16 17:11:16.151  4166  4179 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
09-16 17:11:16.151  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 17:11:16.151  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 17:11:16.151  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,09-16 17:11:16.151  3394  3394 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
09-16 17:11:16.151  4166  4166 I PeopleDataManager: removeNotification
09-16 17:11:16.151  3394  3394 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
09-16 17:11:16.151  4166  4166 I NotificationParser: getNotiType:android,null
09-16 17:11:16.151  4166  4166 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
,09-16 17:11:16.151  4166  4166 D PeopleDataManager: removeNotiInfo =null
09-16 17:11:16.151  4166  4176 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041473,extra=Bundle[mParcelledData.dataSize=84]
09-16 17:11:16.151  4166  4166 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041473, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 17:11:16.151  4166  4166 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 17:11:16.151  4166  4166 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 17:11:16.151  4166  4166 I PeopleDataManager: removeNotification
09-16 17:11:16.151  4166  4166 I NotificationParser: getNotiType:android,null
09-16 17:11:16.151  4166  4166 D PeopleDataManager: removeNotiInfo: id =17041473,packageName=android,isEdgeNotification=false,key=null,removeAll=false
,09-16 17:11:16.151  4166  4166 D PeopleDataManager: removeNotiInfo =null
,09-16 17:11:16.151  3394  3394 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-16 17:11:16.151  3394  3866 D HS20StateMachine: WIFI_STATE_DISABLED
,09-16 17:11:16.151  3394  3866 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
09-16 17:11:16.151  3394  3866 D HS20StateMachine: enter : DisablingState
09-16 17:11:16.151  3394  3868 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
09-16 17:11:16.151  3394  3394 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-16 17:11:16.151  3394  3866 D HS20StateMachine: enter : DisabledState
09-16 17:11:16.151  3394  3869 I WifiHs20Service: Message received 5011
,09-16 17:11:16.161  3394  3872 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-16 17:11:16.161  3394  3394 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
09-16 17:11:16.161  3940  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 17:11:16.161  3940  3940 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-16 17:11:16.161  3940  3940 I HotspotTile: Provider is not defined returning false
09-16 17:11:16.161  4298  4624 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-16 17:11:16.161  4298  4624 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-16 17:11:16.161  3394  3872 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-16 17:11:16.161  3940  3940 D HotspotTile: onReceive : 1, 0
,09-16 17:11:16.161  4336  5107 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 17:11:16.161  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:16.171  9907  9907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 17:11:16.171  3394  3511 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d2f37f u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dccee39 9907:com.test.thalitest/u0a177}
,09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 17:11:16.171  3394  3455 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 17:11:16.181  3394  4445 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d2f37f u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d3271c 10336:com.samsung.android.securitylogagent/1000}
,09-16 17:11:16.241  3394  4151 E Watchdog: !@Sync 8 [09-16 17:11:16.253]
,09-16 17:11:16.291  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:16.351  3394  3862 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-16 17:11:16.471  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:16.541  3394  6478 D SSRM:n  : SIOP:: AP = 350, PST = 318 (W:6), CP = 275, LCD = 1
,09-16 17:11:16.651  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:16.831  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:17.011  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:17.191  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:17.371  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:17.551  3394  3794 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 17:11:17.671  4398  4452 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-16 17:11:17.671  4398  4452 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]

```
