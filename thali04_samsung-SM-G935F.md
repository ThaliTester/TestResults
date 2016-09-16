#### Test 84500654d9ce31e_thali04_samsung-SM-G935F Logs


```
--------- beginning of main
,09-16 11:35:53.242  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:53.422  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:53.602  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:53.722  9688  9688 I FIPS_bssl: FIPS approved mode (1) | 9688 | app_process
09-16 11:35:53.732  9688  9688 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 11:35:53.732  9688  9688 D AndroidRuntime: CheckJNI is OFF
09-16 11:35:53.732  9688  9688 D AndroidRuntime: readGMSProperty: start
09-16 11:35:53.732  9688  9688 D AndroidRuntime: readGMSProperty: already setted!!
09-16 11:35:53.732  9688  9688 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-16 11:35:53.732  9688  9688 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-16 11:35:53.732  9688  9688 D AndroidRuntime: readGMSProperty: end
09-16 11:35:53.732  9688  9688 D AndroidRuntime: addProductProperty: start
09-16 11:35:53.752  9688  9688 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 11:35:53.772  9688  9688 I Radio-JNI: register_android_hardware_Radio DONE
09-16 11:35:53.772  9688  9688 E AffinityControl: AffinityControl: registerfunction enter
09-16 11:35:53.782  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:53.782  9688  9688 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-16 11:35:53.812  3459  4208 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-16 11:35:53.822  3459  4208 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-16 11:35:53.842  3459  4208 D ResourcesManager: For user 0 new overlays fetched Null
09-16 11:35:53.842  3459  4208 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 11:35:53.842  3459  4208 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-16 11:35:53.852  3459  4208 D ActivityManager: mDVFSHelper.acquire()
09-16 11:35:53.852  3459  4208 V WindowManager: addAppToken: AppWindowToken{d07c2647 token=Token{fe4ed86 ActivityRecord{1a95e61 u0 com.test.thalitest/.MainActivity t75}}} to stack=2 task=75 at 0
09-16 11:35:53.862  3459  3571 I InjectionManager: Inside getClassLibPath caller 
09-16 11:35:53.872  3459  3571 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-16 11:35:53.872  3459  3571 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6c1973f V.E...... R.....ID 0,0-0,0}
09-16 11:35:53.872  9697  9697 E Zygote  : v2
09-16 11:35:53.872  9697  9697 I libpersona: KNOX_SDCARD checking this for 10177
09-16 11:35:53.872  9697  9697 I libpersona: KNOX_SDCARD not a persona
09-16 11:35:53.872  9697  9697 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 11:35:53.872  3459  3571 W WindowManager: Failed looking up window
09-16 11:35:53.872  3459  3571 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@63cc80c does not exist
09-16 11:35:53.872  3459  3571 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 11:35:53.872  3459  3571 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 11:35:53.872  9697  9697 E Zygote  : accessInfo : 0
09-16 11:35:53.872  3459  3571 D ISSUE_DEBUG: InputChannelName : 21d0555 Starting com.test.thalitest
09-16 11:35:53.872  9697  9697 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-16 11:35:53.882  3459  4208 I ActivityManager: Start proc 9697:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-16 11:35:53.882  3459  4208 D InputDispatcher: Focused application set to: xxxx
09-16 11:35:53.882  9688  9688 D AndroidRuntime: Shutting down VM
09-16 11:35:53.882  3459  3856 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-16 11:35:53.892  3009  3009 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-16 11:35:53.902  9697  9697 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:35:53.902  9697  9697 D ActivityThread: Added TimaKeyStore provider
09-16 11:35:53.912  6221  6221 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 11:35:53.922  3459  4412 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3459
09-16 11:35:53.922  3459  4412 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 11:35:53.922  3459  4412 D PowerManagerService: mDisplayReady: false
09-16 11:35:53.922  3459  4412 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 11:35:53.922  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 11:35:53.922  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 11:35:53.922  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb4f43c00
09-16 11:35:53.922  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:35:53.922  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-16 11:35:53.922  3459  4412 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 11:35:53.922  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:35:53.922  3459  3587 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-16 11:35:53.932  6221  6221 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 11:35:53.932  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 11:35:53.932  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 11:35:53.932  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:35:53.932  3459  3483 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 11:35:53.932  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:35:53.932  3459  3483 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 11:35:53.932  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 11:35:53.932  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 11:35:53.932  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:35:53.932  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:35:53.932  3459  3483 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3459
09-16 11:35:53.932  3459  3483 D PowerManagerService: mDisplayReady: true
09-16 11:35:53.932  3459  3576 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 11:35:53.932  3459  3576 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-16 11:35:53.932  3459  4049 D ActivityManager:  Launching com.test.thalitest, updated priority
09-16 11:35:53.942  3459  4380 V WindowStateAnimator: Finishing drawing window Window{b1fa608 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-16 11:35:53.952  3009  3020 D libEGL  : eglTerminate EGLDisplay = 0x7fb4a3ee78
09-16 11:35:53.952  3009  3020 D libEGL  : eglTerminate EGLDisplay = 0x7fb4a3ee78
09-16 11:35:53.962  5818  6680 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-16 11:35:53.962  3459  3543 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-16 11:35:53.962  3459  3459 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-16 11:35:53.962  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:53.962  3009  4126 I SurfaceFlinger: id=10 Removed MauncherAct (4/13)
09-16 11:35:53.962  3009  3018 I SurfaceFlinger: id=10 Removed MauncherAct (-2/13)
09-16 11:35:53.962  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc462dd78
09-16 11:35:53.982  4323  4323 V ActivityThread: updateVisibility : ActivityRecord{d58a6ae token=android.os.BinderProxy@7aa96ad {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-16 11:35:53.982  4323  4323 D Launcher: onTrimMemory. Level: 20
09-16 11:35:53.992  3459  4416 V WindowStateAnimator: Finishing drawing window Window{107fdfa u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-16 11:35:53.992  6221  6221 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 11:35:53.992  6221  6221 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 11:35:53.992  6221  6221 V ActivityThread: updateVisibility : ActivityRecord{418c926 token=android.os.BinderProxy@f5178a {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-16 11:35:53.992  3009  4463 I SurfaceFlinger: id=18 Removed VSBConnecti (7/12)
09-16 11:35:53.992  3009  4126 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/12)
09-16 11:35:53.992  3009  4126 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
09-16 11:35:53.992  3009  3018 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
09-16 11:35:54.002  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc462dd78
09-16 11:35:54.002  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc462dd48
09-16 11:35:54.002  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc462dd48
09-16 11:35:54.072  3459  3459 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3459 (0x0)
09-16 11:35:54.082  3459  3459 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3459 (0x0)
09-16 11:35:54.082  3459  3459 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 11:35:54.082  3459  3459 D PowerManagerService: mDisplayReady: false
09-16 11:35:54.082  3459  3459 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 11:35:54.082  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 11:35:54.082  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 11:35:54.082  3459  3459 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 11:35:54.082  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:35:54.082  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:35:54.082  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb4f43c00
09-16 11:35:54.082  3459  3587 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-16 11:35:54.082  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-16 11:35:54.092  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 11:35:54.092  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 11:35:54.092  3459  3576 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 11:35:54.092  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:35:54.092  3459  3576 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 11:35:54.092  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:35:54.092  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 11:35:54.092  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 11:35:54.092  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:35:54.092  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:35:54.092  3459  3576 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 11:35:54.092  3459  3576 D PowerManagerService: mDisplayReady: true
09-16 11:35:54.092  3459  3576 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-16 11:35:54.142  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:54.262  5818  5818 I TrayVisibilityController: handleMessage : msg.what = 1
09-16 11:35:54.282  3459  4049 I WindowManager: Screenshot max retries 4 of Token{fe4ed86 ActivityRecord{1a95e61 u0 com.test.thalitest/.MainActivity t75}} appWin=Window{21d0555 u0 d0 Starting com.test.thalitest} drawState=1
09-16 11:35:54.292  3459  3571 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 11:35:54.292  5818  5829 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-16 11:35:54.292  3459  3571 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-16 11:35:54.292  3459  3459 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 11:35:54.292  3459  3459 I KnoxTimeoutHandler: SD activityfalse
09-16 11:35:54.302  5818  5818 I Utils   : isCurrentUser current = 0, ownerId = 0
09-16 11:35:54.302  3459  6141 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 11:35:54.302  5818  5818 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-16 11:35:54.302  3459  6141 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 11:35:54.302  5818  5818 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-16 11:35:54.302  3459  3856 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-16 11:35:54.322  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:54.332  9697  9697 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:35:54.332  9697  9697 D RelationGraph: garbageCollect()
09-16 11:35:54.332  9697  9697 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-16 11:35:54.332  3459  6141 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-16 11:35:54.332  3459  3571 V WindowStateAnimator: Finishing drawing window Window{21d0555 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-16 11:35:54.332  3459  4424 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 11:35:54.332  3459  3571 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 11:35:54.332  3459  3459 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 11:35:54.332  9697  9697 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-16 11:35:54.332  3459  6141 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 11:35:54.342  3459  3459 I KnoxTimeoutHandler: SD activityfalse
09-16 11:35:54.342  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fc462dc58
09-16 11:35:54.352  3459  3571 D ActivityManager: mDVFSHelper.release()
09-16 11:35:54.352  3459  3571 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3b48884 u0 com.samsung.android.MtpApplication/.USBConnection t74} time:234963
09-16 11:35:54.352  9697  9697 D ResourcesManager: For user 0 new overlays fetched Null
09-16 11:35:54.352  3459  6141 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-16 11:35:54.362  3459  6141 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 11:35:54.362  3459  6141 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 11:35:54.362  9697  9697 I InjectionManager: Inside getClassLibPath caller 
09-16 11:35:54.372  9697  9697 D InjectionManager: InjectionManager
09-16 11:35:54.372  9697  9697 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-16 11:35:54.372  9697  9697 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-16 11:35:54.372  9697  9697 I InjectionManager: featureStore :{}
09-16 11:35:54.382  9697  9697 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-16 11:35:54.382  9697  9697 D RelationGraph: garbageCollect()
09-16 11:35:54.382  9697  9697 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-16 11:35:54.412  9697  9697 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-16 11:35:54.472  9697  9697 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-16 11:35:54.472  9697  9697 D ResourcesManager: For user 0 new overlays fetched Null
09-16 11:35:54.472  9697  9697 I InjectionManager: Inside getClassLibPath caller 
09-16 11:35:54.482  9697  9697 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-16 11:35:54.502  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:54.532  9697  9697 I cr_LibraryLoader: Time to load native libraries: 32 ms (timestamps 5106-5138)
09-16 11:35:54.532  9697  9697 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-16 11:35:54.542  3459  3879 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-16 11:35:54.592  9697  9713 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-16 11:35:54.612  9697  9697 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {11e400b}
09-16 11:35:54.612  9697  9697 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-16 11:35:54.632  9697  9697 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-16 11:35:54.642  3459  3879 I MdnieScenarioControlService: mGameModeLauncher : false
09-16 11:35:54.642  3459  3879 I MdnieScenarioControlService: setUIMode
09-16 11:35:54.682  9697  9697 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-16 11:35:54.682  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:54.792  3459  3543 W ActivityManager: Activity pause timeout for ActivityRecord{1a95e61 u0 com.test.thalitest/.MainActivity t75}
09-16 11:35:54.862  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:54.872  9697  9697 D libEGL  : eglInitialize EGLDisplay = 0xffd8931c
09-16 11:35:54.952  3459  4412 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
09-16 11:35:54.952  3459  4412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-16 11:35:55.022  9697  9697 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-16 11:35:55.042  9697  9697 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-16 11:35:55.042  9697  9697 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-16 11:35:55.042  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:55.072  9697  9697 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-16 11:35:55.122  9697  9697 D Activity: performCreate Call Injection manager
09-16 11:35:55.122  9697  9697 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
09-16 11:35:55.132  9697  9697 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-16 11:35:55.142  9697  9697 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{558cd06 I.E...... R.....ID 0,0-0,0}
09-16 11:35:55.142  9697  9750 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-16 11:35:55.152  3459  4380 W WindowManager: Failed looking up window
09-16 11:35:55.152  3459  4380 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@e953c6c does not exist
09-16 11:35:55.152  3459  4380 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-16 11:35:55.152  3459  4380 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-16 11:35:55.152  3459  4380 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-16 11:35:55.152  3459  4380 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-16 11:35:55.152  3459  4380 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-16 11:35:55.152  3459  4380 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-16 11:35:55.152  3459  4424 D ISSUE_DEBUG: InputChannelName : 57bd235 com.test.thalitest/com.test.thalitest.MainActivity
09-16 11:35:55.152  3459  3979 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-16 11:35:55.152  3459  3979 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 11:35:55.152  3459  3459 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 11:35:55.152  3459  3459 I KnoxTimeoutHandler: Shared devices show user statefalse
09-16 11:35:55.162  9697  9697 V ActivityThread: updateVisibility : ActivityRecord{a69c9f4 token=android.os.BinderProxy@a0a28ce {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-16 11:35:55.172  9697  9713 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-16 11:35:55.182  9697  9697 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9697
09-16 11:35:55.182  3459  3979 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9697 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 11:35:55.192  3459  3867 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-16 11:35:55.192  3459  3867 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-16 11:35:55.192  3459  3867 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-16 11:35:55.192  3459  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-16 11:35:55.202  3459  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-16 11:35:55.202  3459  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-16 11:35:55.202  9697  9697 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-16 11:35:55.212  3459  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-16 11:35:55.212  3459  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-16 11:35:55.212  3459  3867 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 11:35:55.222  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:55.222  3009  3009 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
09-16 11:35:55.242  9697  9750 D libEGL  : eglInitialize EGLDisplay = 0xdc43f7c4
09-16 11:35:55.242  9697  9750 I OpenGLRenderer: Initialized EGL, version 1.4
09-16 11:35:55.242  9697  9750 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-16 11:35:55.242  3459  3484 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3459
09-16 11:35:55.242  3459  3484 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 11:35:55.242  3459  3484 D PowerManagerService: mDisplayReady: false
09-16 11:35:55.242  3459  3484 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 11:35:55.242  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 11:35:55.242  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb4f43c00
09-16 11:35:55.242  3459  3484 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 11:35:55.242  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-16 11:35:55.242  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 11:35:55.242  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:35:55.242  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:35:55.242  3459  3587 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-16 11:35:55.242  3459  3571 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-16 11:35:55.242  3459  3571 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-16 11:35:55.262  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 11:35:55.262  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 11:35:55.262  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:35:55.262  3459  3576 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 11:35:55.262  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:35:55.262  3459  3576 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 11:35:55.262  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 11:35:55.262  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 11:35:55.262  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:35:55.262  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:35:55.262  3459  3576 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 11:35:55.262  3459  3576 D PowerManagerService: mDisplayReady: true
09-16 11:35:55.262  3459  3576 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-16 11:35:55.272  5818  5818 E CocktailBarPositionManager: Window direction: 0
09-16 11:35:55.272  5818  5818 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-16 11:35:55.282  9697  9697 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-16 11:35:55.292  3459  6142 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-16 11:35:55.292  9697  9754 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-16 11:35:55.302  9697  9754 D libEGL  : eglInitialize EGLDisplay = 0xdab5f3f4
09-16 11:35:55.302  3459  3979 V WindowStateAnimator: Finishing drawing window Window{57bd235 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-16 11:35:55.302  9697  9697 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-16 11:35:55.312  3459  3571 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 11:35:55.312  3459  4049 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3459
09-16 11:35:55.312  3459  3459 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 11:35:55.312  3459  3571 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s23ms (total +1s454ms)
09-16 11:35:55.312  3459  3571 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1a95e61 u0 com.test.thalitest/.MainActivity t75} time:235923
09-16 11:35:55.312  3459  3571 D ViewRootImpl: #3 mView = null
09-16 11:35:55.312  3009  4463 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
09-16 11:35:55.312  3459  3459 I KnoxTimeoutHandler: SD activityfalse
09-16 11:35:55.312  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc462dd48
09-16 11:35:55.312  9697  9754 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-16 11:35:55.322  3459  4208 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3459
09-16 11:35:55.332  3459  4380 V WindowStateAnimator: Finishing drawing window Window{57bd235 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-16 11:35:55.332  9697  9697 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a0a28ce time:235942
09-16 11:35:55.362  9697  9697 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9697
09-16 11:35:55.402  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:55.472  3459  3459 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3459 (0x0)
09-16 11:35:55.472  3459  3459 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 11:35:55.472  3459  3459 D PowerManagerService: mDisplayReady: false
09-16 11:35:55.472  3459  3459 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 11:35:55.472  3459  3459 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 11:35:55.472  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 11:35:55.472  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 11:35:55.472  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:35:55.472  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:35:55.472  3459  3587 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-16 11:35:55.472  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb4f43c00
09-16 11:35:55.472  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-16 11:35:55.472  3459  3571 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-16 11:35:55.472  3459  3571 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-16 11:35:55.482  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 11:35:55.482  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 11:35:55.482  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:35:55.482  3459  3576 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 11:35:55.482  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:35:55.482  3459  3576 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 11:35:55.482  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 11:35:55.482  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 11:35:55.482  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:35:55.482  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:35:55.482  3459  3576 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 11:35:55.482  3459  3576 D PowerManagerService: mDisplayReady: true
09-16 11:35:55.482  3459  3576 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-16 11:35:55.492  5818  5818 E CocktailBarPositionManager: Window direction: 0
09-16 11:35:55.492  5818  5818 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-16 11:35:55.582  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:55.592  9697  9697 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-16 11:35:55.702  9697  9761 D jxcore_app_log: JniHelper::setJavaVM(0xf4b34000), pthread_self() = -649070288
09-16 11:35:55.702  9697  9761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-16 11:35:55.702  9697  9761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-16 11:35:55.702  9697  9761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-16 11:35:55.702  9697  9761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-16 11:35:55.702  9697  9761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-16 11:35:55.702  9697  9761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97483b6 added. We now have 1 listener(s)
09-16 11:35:55.702  9697  9761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
09-16 11:35:55.702  9697  9761 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-16 11:35:55.702  9697  9761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 11:35:55.702  9697  9761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-16 11:35:55.712  9697  9761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fcef8d added. We now have 1 listener(s)
09-16 11:35:55.712  9697  9761 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 11:35:55.712  9697  9761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 11:35:55.712  9697  9761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-16 11:35:55.712  9697  9761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-16 11:35:55.712  9697  9761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-16 11:35:55.712  9697  9761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-16 11:35:55.712  9697  9761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:35:55.712  9697  9761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
09-16 11:35:55.722  9697  9761 D BluetoothAdapter: STATE_ON
09-16 11:35:55.722  9697  9761 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-16 11:35:55.722  9697  9761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:35:55.722  9697  9761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:35:55.722  9697  9761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:35:55.722  9697  9761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:35:55.722  9697  9761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:35:55.722  9697  9761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:35:55.722  9697  9761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:35:55.722  9697  9761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 11:35:55.722  9697  9761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-16 11:35:55.722  9697  9761 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:35:55.732  9697  9761 I io.jxcore.node.LifeCycleMonitor: start: OK
09-16 11:35:55.732  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:35:55.732  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:35:55.752  9697  9697 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-16 11:35:55.762  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:35:55.792  4019  4019 D Recents : onTaskStackChanged
09-16 11:35:55.802  4019  4019 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-16 11:35:55.812  4019  4019 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:35:55.942  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:56.122  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:56.182  9697  9762 W jxcore-log: Initializing JXcore engine
09-16 11:35:56.182  9697  9762 W jxcore-log: JXcore engine is ready
,09-16 11:35:56.202  5019  5019 E audit   : type=1400 msg=audit(1474018556.202:264): avc:  denied  { ioctl } for  pid=9762 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2244 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-16 11:35:56.202  5019  5019 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-16 11:35:56.202  5019  5019 E audit   : type=1300 msg=audit(1474018556.202:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d80c43c8 items=0 ppid=3180 pid=9762 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-16 11:35:56.202  5019  5019 E audit   : type=1327 msg=audit(1474018556.202:264): proctitle="com.test.thalitest"
09-16 11:35:56.202  5019  5019 E audit   : type=1320 msg=audit(1474018556.202:264): 
09-16 11:35:56.202  5019  5019 E audit   : type=1400 msg=audit(1474018556.202:265): avc:  denied  { ioctl } for  pid=9762 comm="Thread-160" path="socket:[39954]" dev="sockfs" ino=39954 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-16 11:35:56.202  5019  5019 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-16 11:35:56.202  5019  5019 E audit   : type=1300 msg=audit(1474018556.202:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d80c43c8 items=0 ppid=3180 pid=9762 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-16 11:35:56.202  5019  5019 E audit   : type=1327 msg=audit(1474018556.202:265): proctitle="com.test.thalitest"
09-16 11:35:56.202  5019  5019 E audit   : type=1320 msg=audit(1474018556.202:265): 
,09-16 11:35:56.212  9697  9762 W jxcore-log: Starting JXcore engine
,09-16 11:35:56.242  9697  9762 W jxcore-log: Platform android
09-16 11:35:56.242  9697  9762 W jxcore-log: 
09-16 11:35:56.242  9697  9762 W jxcore-log: Process ARCH arm
09-16 11:35:56.242  9697  9762 W jxcore-log: 
,09-16 11:35:56.302  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:56.332  9697  9762 I jxcore-log: JXcore Cordova bridge is ready!
09-16 11:35:56.332  9697  9762 I jxcore-log: 
09-16 11:35:56.332  9697  9762 W jxcore-log: JXcore engine is started
,09-16 11:35:56.332  9697  9761 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-16 11:35:56.332  9697  9697 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-16 11:35:56.482  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:56.662  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:56.842  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:56.862  3459  3906 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/75_task.xml.bak
,09-16 11:35:57.022  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:57.202  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:57.302  3459  6141 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-16 11:35:57.382  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:57.562  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:57.742  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:57.922  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:58.102  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:58.282  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:58.462  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:58.642  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:58.822  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:59.002  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:59.182  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:59.362  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:59.542  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:59.722  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:59.902  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:35:59.992  3459  3816 V AlarmManager: Expired Alarm result :8
,09-16 11:36:00.082  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:00.262  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:00.372  3459  6141 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-16 11:36:00.442  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:00.622  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:00.802  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:00.932  3459  3816 V AlarmManager: Expired Alarm result :4
,09-16 11:36:00.932  3459  3816 V AlarmManager: Send whitelist package alarm :PendingIntent{5edc8: PendingIntentRecord{adbb78e com.samsung.android.app.aodservice broadcastIntent}}
,09-16 11:36:00.932  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-16 11:36:00.932  3949  3949 D KeyguardUpdateMonitor: handleTimeUpdate
,09-16 11:36:00.952  3949  3949 D Clock   : received broadcast android.intent.action.TIME_TICK
,09-16 11:36:00.982  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:01.032  3949  3949 D DateView: received broadcast android.intent.action.TIME_TICK
,09-16 11:36:01.062  7845  7845 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,09-16 11:36:01.062  7845  7845 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-16 11:36:01.072  4763  4763 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
09-16 11:36:01.072  4763  4763 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
09-16 11:36:01.072  3459  4424 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-16 11:36:01.072  3459  4424 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
09-16 11:36:01.072  3459  4424 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
09-16 11:36:01.072  3459  4424 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
,09-16 11:36:01.072  3170  3170 D Sensorhubs: sendContextData: -72, 56, 1, 1
,09-16 11:36:01.082  3459  4424 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-16 11:36:01.082  3459  4424 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-16 11:36:01.082  3459  4424 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
09-16 11:36:01.082  4763  4763 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@9b8617e, service=Device Physical Context Monitor
09-16 11:36:01.082  4763  4763 I AlpmModeManager: startAlpmMode : state  = BLANK
09-16 11:36:01.082  4763  4763 D DefaultClockView: Window showed. Time views updating
,09-16 11:36:01.082  3459  3979 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3459
,09-16 11:36:01.082  3459  3979 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 11:36:01.082  3459  3979 D PowerManagerService: mDisplayReady: false
09-16 11:36:01.082  3459  3979 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 11:36:01.082  3459  3979 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 11:36:01.092  4763  4763 D AODUpdatePositionController: updatePosition: direction[7] updatePosition: X[9] Y[870] NewPositionTimer[56]
09-16 11:36:01.092  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 11:36:01.092  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,09-16 11:36:01.092  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:36:01.092  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:36:01.092  3459  3587 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-16 11:36:01.092  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb4f43c00
09-16 11:36:01.092  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-16 11:36:01.092  3459  3571 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-16 11:36:01.092  3459  3571 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-16 11:36:01.092  4763  4763 D DefaultClockView: LocalTime Pattern : HH:mm
09-16 11:36:01.092  4763  4763 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 11:36 time02: null ampm: null
,09-16 11:36:01.102  3170  3208 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
,09-16 11:36:01.102  3459  3819 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
,09-16 11:36:01.102  3459  3818 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 9, 36, 1,
09-16 11:36:01.102  3459  3818 D SensorHubManager: SendSensorHubData: send data = -63, 14, 9, 36, 1
,09-16 11:36:01.102  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 11:36:01.102  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 11:36:01.102  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:36:01.102  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:36:01.102  3459  3576 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 11:36:01.102  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 11:36:01.102  3459  3576 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 11:36:01.102  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 11:36:01.102  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:36:01.102  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:36:01.102  3459  3576 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 11:36:01.102  3459  3576 D PowerManagerService: mDisplayReady: true
09-16 11:36:01.102  3459  3576 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-16 11:36:01.102  3170  3209 D Sensorhubs: sendContextData: -63, 14, 9, 36, 1
,09-16 11:36:01.112  5818  5818 E CocktailBarPositionManager: Window direction: 0
09-16 11:36:01.112  5818  5818 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-16 11:36:01.112  3459  3818 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,09-16 11:36:01.112  3459  3818 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
,09-16 11:36:01.112  3459  3818 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
09-16 11:36:01.112  3459  3818 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
,09-16 11:36:01.112  3459  3818 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
09-16 11:36:01.112  3459  3821 D SContextService: updateSContext() : event = Device Physical Context Monitor
,09-16 11:36:01.112  4763  4763 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
09-16 11:36:01.112  4763  4763 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,09-16 11:36:01.112  4763  4763 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:pt., 16 wrz 11:36
09-16 11:36:01.112  4763  4763 I AODService.ClockTimer: startAlarm : TICK
09-16 11:36:01.112  3459  4208 V AlarmManager: Add whitelist package alarm :PendingIntent{696989c: PendingIntentRecord{adbb78e com.samsung.android.app.aodservice broadcastIntent}}
,09-16 11:36:01.122  4763  4763 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
09-16 11:36:01.122  4763  4763 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
,09-16 11:36:01.122  3459  4049 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
09-16 11:36:01.122  3459  4049 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,09-16 11:36:01.122  4763  4763 I AODService: onSContextChanged: AODScreenShown state is already true
,09-16 11:36:01.122  4763  4763 D DefaultClockView: RootView invalidate()
09-16 11:36:01.122  3459  4412 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3459
,09-16 11:36:01.162  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:01.272  3459  3459 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3459 (0x0)
,09-16 11:36:01.272  3459  3459 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 11:36:01.272  3459  3459 D PowerManagerService: mDisplayReady: false
09-16 11:36:01.272  3459  3459 I libsuspend: !@autosuspend_wakeup_count_disable done
,09-16 11:36:01.272  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 11:36:01.272  3459  3459 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,09-16 11:36:01.272  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb4f43c00
09-16 11:36:01.272  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 11:36:01.272  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-16 11:36:01.272  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-16 11:36:01.272  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:36:01.272  3459  3587 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-16 11:36:01.272  3459  3571 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
,09-16 11:36:01.272  3459  3571 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-16 11:36:01.292  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 11:36:01.292  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 11:36:01.292  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:36:01.292  3459  3576 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 11:36:01.292  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:36:01.292  3459  3576 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 11:36:01.292  3459  3576 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 11:36:01.292  3459  3576 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 11:36:01.292  3459  3576 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 11:36:01.292  3459  3576 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 11:36:01.292  3459  3576 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 11:36:01.292  3459  3576 D PowerManagerService: mDisplayReady: true
09-16 11:36:01.292  3459  3576 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-16 11:36:01.312  5818  5818 E CocktailBarPositionManager: Window direction: 0
09-16 11:36:01.312  5818  5818 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-16 11:36:01.342  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:01.522  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:01.702  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:01.832  3459  6141 D SSRM:n  : SIOP:: AP = 350, PST = 306 (W:6), CP = 246, CUR = 9, LCD = 1
,09-16 11:36:01.882  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:02.062  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:02.242  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:02.312  8376  8399 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,09-16 11:36:02.372  9697  9762 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 11:36:02.372  9697  9762 I jxcore-log: 
,09-16 11:36:02.372  9697  9762 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 11:36:02.372  9697  9762 I jxcore-log: 
,09-16 11:36:02.382  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.382  9697  9762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:36:02.382  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:02.382  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:02.382  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:36:02.382  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:36:02.382  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:36:02.382  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:36:02.382  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:36:02.392  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.392  9697  9762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:36:02.392  9697  9762 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 11:36:02.392  9697  9762 I jxcore-log: 
09-16 11:36:02.392  9697  9762 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 11:36:02.392  9697  9762 I jxcore-log: 
,09-16 11:36:02.422  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:02.552  9697  9762 D ExecuteNativeTests: Running unit tests
,09-16 11:36:02.572  9697  9762 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 11:36:02.572  9697  9762 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 added. We now have 2 listener(s)
09-16 11:36:02.572  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-16 11:36:02.572  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 11:36:02.572  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 11:36:02.572  9697  9762 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 11:36:02.572  9697  9762 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d added. We now have 2 listener(s)
09-16 11:36:02.572  9697  9762 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 11:36:02.572  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 11:36:02.582  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:36:02.592  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.592  9697  9762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:36:02.592  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:02.592  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:02.592  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:36:02.592  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:36:02.592  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:36:02.592  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:36:02.592  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:36:02.592  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.602  9697  9762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:36:02.602  9697  9762 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:36:02.602  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 11:36:02.602  9697  9762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 11:36:02.602  9697  9762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 11:36:02.602  9697  9762 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-16 11:36:02.602  9697  9762 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 11:36:02.602  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 11:36:02.602  9697  9762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 11:36:02.602  9697  9762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 11:36:02.602  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:02.602  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:36:02.602  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:02.602  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:36:02.602  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:02.602  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:02.602  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:36:02.602  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-16 11:36:02.602  9697  9762 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 removed from the list
09-16 11:36:02.602  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:36:02.602  9697  9762 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d removed from the list
09-16 11:36:02.602  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:36:02.602  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:02.602  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:02.602  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:02.602  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:02.612  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:02.612  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:36:02.612  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:02.612  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-16 11:36:02.612  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:36:02.612  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:02.612  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:36:02.612  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:02.612  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:02.612  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:02.612  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:02.612  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:02.612  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:02.612  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:02.612  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:02.612  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:02.612  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:02.612  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:36:02.612  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:36:02.612  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:02.612  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 11:36:02.612  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:02.612  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:02.612  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:36:02.612  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:02.612  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:02.612  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:02.612  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:02.612  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:02.612  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:02.612  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:02.612  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:02.612  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:02.612  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:02.612  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:02.622  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:36:02.622  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:36:02.622  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:02.622  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:02.622  9697  9762 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 11:36:02.622  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:36:02.632  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:02.632  9697  9762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:36:02.632  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:02.632  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:02.632  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:36:02.632  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:36:02.632  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:36:02.632  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:36:02.632  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 11:36:02.632  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:02.632  9697  9762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 11:36:02.632  9697  9762 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:36:02.632  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 11:36:02.632  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 11:36:02.632  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 11:36:02.632  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:36:02.632  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 11:36:02.642  9697  9762 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 11:36:02.642  9697  9762 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 11:36:02.642  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:36:02.642  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:02.642  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:02.642  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:02.642  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:36:02.642  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 11:36:02.652  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.652  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.652  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 11:36:02.652  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 11:36:02.652  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.662  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.662  9697  9762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-16 11:36:02.662  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.662  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.672  9697  9762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-16 11:36:02.672  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 11:36:02.672  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 11:36:02.672  9697  9762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 11:36:02.672  9697  9762 D BluetoothLeScanner: Start Scan
,09-16 11:36:02.672  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.672  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.672  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.672  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.682  5010  5026 D BtGatt.GattService: registerClient() - UUID=d447ba8d-ce0d-4385-b24f-0680693a3da0
,09-16 11:36:02.732  5010  5141 D BtGatt.GattService: onClientRegistered() - UUID=d447ba8d-ce0d-4385-b24f-0680693a3da0, clientIf=7
,09-16 11:36:02.732  9697  9707 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-16 11:36:02.732  5010  5415 D BtGatt.GattService: start scan with filters
,09-16 11:36:02.742  5010  5415 D BtGatt.GattService: getScanSettings
,09-16 11:36:02.752  5010  5415 D BtGatt.GattService: Is it foreground application = true
,09-16 11:36:02.762  5010  5415 D BtGatt.GattService: not a background application
,09-16 11:36:02.772  5010  5415 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-16 11:36:02.782  5010  5415 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 11:36:02.782  5010  5415 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 11:36:02.782  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:36:02.782  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 11:36:02.782  5010  5206 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-16 11:36:02.782  5010  5206 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
,09-16 11:36:02.782  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 11:36:02.782  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-16 11:36:02.782  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 11:36:02.782  5010  5196 D BtGatt.ScanManager: handling starting scan
09-16 11:36:02.782  5010  5196 D BtGatt.ScanManager: isFilteringSupported
09-16 11:36:02.782  5010  5196 D BluetoothAdapter: enableStandAloneBleMode=
09-16 11:36:02.792  5010  5196 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.792  5010  5196 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.792  5010  5196 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.802  5010  5196 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.802  5010  5196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e400b
,09-16 11:36:02.802  5010  5206 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 13
,09-16 11:36:02.802  5010  5206 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-16 11:36:02.802  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 11:36:02.802  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-16 11:36:02.802  9697  9697 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 11:36:02.802  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{88b6ad2: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.802  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 11:36:02.812  5010  5141 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-16 11:36:02.812  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:02.812  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{e54a7a3: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:02.812  5010  5196 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
09-16 11:36:02.812  5010  5196 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-16 11:36:02.812  5010  5196 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-16 11:36:02.812  5010  5196 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-16 11:36:02.812  5010  5141 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-16 11:36:02.812  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:02.812  9697  9762 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 11:36:02.822  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{313aa0: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 7
09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24566976
09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
,09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
,09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-16 11:36:02.822  5010  5206 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24566976
,09-16 11:36:02.822  5010  5196 D BtGatt.ScanManager: Starting BLE batch scan
09-16 11:36:02.822  5010  5196 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-16 11:36:02.822  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{c92e659: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:02.822  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:02.832  5010  5141 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-16 11:36:02.832  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:02.832  5010  5141 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-16 11:36:02.832  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:02.832  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:02.832  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{e91621e: PendingIntentRecord{1001aff com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.832  9697  9762 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 11:36:02.832  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:02.832  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 11:36:02.832  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:02.832  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:36:02.832  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 11:36:02.832  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 11:36:02.832  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 11:36:02.832  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 11:36:02.832  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-16 11:36:02.832  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-16 11:36:02.832  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{57f60cc: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:02.832  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.842  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.842  9697  9762 D BluetoothLeScanner: Stop Scan
,09-16 11:36:02.842  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{828f15: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:02.842  5010  5415 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 11:36:02.842  5010  5415 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 11:36:02.842  5010  5415 D BtGatt.GattService: stopScan() - queue size =1
09-16 11:36:02.842  5010  5206 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-16 11:36:02.842  5010  5206 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
,09-16 11:36:02.842  5010  5206 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 11:36:02.842  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-16 11:36:02.842  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-16 11:36:02.842  5010  5206 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-16 11:36:02.842  5010  5206 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-16 11:36:02.842  5010  5416 D BtGatt.GattService: unregisterClient() - clientIf=7
,09-16 11:36:02.842  5010  5196 D BtGatt.ScanManager: filter size is 1
,09-16 11:36:02.842  5010  5196 D BtGatt.ScanManager: delete FilterIndex - 3
09-16 11:36:02.852  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:02.852  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{e6d822a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:02.852  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 11:36:02.852  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-16 11:36:02.852  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 11:36:02.852  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 11:36:02.852  5010  5141 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-16 11:36:02.852  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:02.852  5010  5196 D BtGatt.ScanManager: stopping BLe Batch
09-16 11:36:02.852  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:36:02.852  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.852  5010  5141 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-16 11:36:02.852  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:02.852  5010  5196 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-16 11:36:02.852  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{8c5681b: PendingIntentRecord{1001aff com.android.bluetooth broadcastIntent}}
09-16 11:36:02.852  5010  5141 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-16 11:36:02.852  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 11:36:02.852  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:02.852  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:02.852  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:02.852  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:02.852  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 11:36:02.852  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 11:36:02.852  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:36:02.862  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{1a7bdb8: PendingIntentRecord{1001aff com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.862  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{48a0791: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:02.862  9697  9697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:36:02.862  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:02.862  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:36:02.862  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 11:36:02.862  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:02.862  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 11:36:02.862  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:02.862  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:02.862  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:02.862  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:02.862  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:36:02.862  9697  9762 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-16 11:36:02.862  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:36:02.872  9697  9697 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 11:36:02.872  9697  9697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 11:36:02.872  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{1d88bd0: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.872  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.872  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{6ad17c9: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.872  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.882  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.882  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{3688ece: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.882  9697  9762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:36:02.882  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:02.882  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:02.882  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:36:02.882  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:36:02.882  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:36:02.882  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:36:02.882  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:36:02.882  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.882  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.882  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{5bc1ef: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.882  9697  9762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 11:36:02.882  9697  9762 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 11:36:02.882  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 11:36:02.882  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-16 11:36:02.892  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 11:36:02.892  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.892  9697  9697 D BluetoothAdapter: STATE_ON
09-16 11:36:02.892  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{a0294fc: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.892  9697  9697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 11:36:02.892  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 11:36:02.892  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 11:36:02.892  9697  9697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:36:02.892  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-16 11:36:02.892  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{3666785: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:02.892  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:36:02.892  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 11:36:02.902  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{aaf701: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:02.902  9697  9762 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 11:36:02.902  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.902  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.902  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{bd3a9a6: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.912  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:02.912  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{333ffe7: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.912  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:02.912  3459  4412 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-16 11:36:02.912  3459  4412 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-16 11:36:02.912  3459  4412 D BatteryService: online:4, current avg:-102, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
09-16 11:36:02.912  3459  4412 D BatteryService: stay LED for fully charged
09-16 11:36:02.912  3459  3459 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-16 11:36:02.912  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 11:36:02.912  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 11:36:02.912  9697  9762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 11:36:02.912  9697  9762 D BluetoothLeScanner: Start Scan
,09-16 11:36:02.922  3459  3459 I MotionRecognitionService: Plugged
,09-16 11:36:02.922  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:02.922  3459  3459 D MotionRecognitionService:   cableConnection= 1
09-16 11:36:02.922  3459  3459 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-16 11:36:02.922  3459  3459 D MotionRecognitionService: skip setTransmitPower. 
,09-16 11:36:02.922  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.922  3459  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-16 11:36:02.922  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:02.922  3949  3949 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-16 11:36:02.922  3949  3949 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-16 11:36:02.922  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:02.922  3949  3949 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-16 11:36:02.922  5010  5028 D BtGatt.GattService: registerClient() - UUID=fb7cc197-5dbb-4822-96b5-4779811784ba
,09-16 11:36:02.932  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-16 11:36:02.932  5051  5051 D CommonServiceConfiguration: getStringValueSetting
,09-16 11:36:02.932  5010  5010 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-16 11:36:02.932  5010  5414 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-16 11:36:02.932  4763  4763 D BatteryController: saveBatteryData : level[100], status[5]
,09-16 11:36:02.932  5051  5051 D BatteryMonitor: new battery level: 100
,09-16 11:36:02.942  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{8c68794: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.942  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{a4f023d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.942  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{e80ba32: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.952  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{a36b383: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.952  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{e4e8900: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.952  3949  3949 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-16 11:36:02.962  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:02.962  5010  5141 D BtGatt.GattService: onClientRegistered() - UUID=fb7cc197-5dbb-4822-96b5-4779811784ba, clientIf=7
,09-16 11:36:02.962  9697  9708 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-16 11:36:02.962  5010  5416 D BtGatt.GattService: start scan with filters
,09-16 11:36:02.972  5010  5416 D BtGatt.GattService: getScanSettings
,09-16 11:36:02.972  5010  5416 D BtGatt.GattService: Is it foreground application = true
09-16 11:36:02.972  5010  5416 D BtGatt.GattService: not a background application
,09-16 11:36:02.972  5010  5416 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-16 11:36:02.972  5010  5416 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 11:36:02.972  5010  5416 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 11:36:02.972  5010  5206 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-16 11:36:02.972  5010  5206 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
09-16 11:36:02.972  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 11:36:02.972  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 11:36:02.972  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 11:36:02.972  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 11:36:02.972  5010  5196 D BtGatt.ScanManager: handling starting scan
,09-16 11:36:02.972  5010  5196 D BluetoothAdapter: STATE_ON
,09-16 11:36:02.982  5010  5196 D BluetoothAdapter: STATE_ON
09-16 11:36:02.982  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 11:36:02.982  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{b2e8539: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.982  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 11:36:02.982  5010  5141 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-16 11:36:02.982  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:02.982  5010  5196 D BtGatt.ScanManager: set filter index= 4 for clientIf= 7
,09-16 11:36:02.982  5010  5196 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-16 11:36:02.982  5010  5196 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-16 11:36:02.982  5010  5196 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-16 11:36:02.982  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 11:36:02.982  5010  5206 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 14
,09-16 11:36:02.982  5010  5206 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-16 11:36:02.982  5010  5141 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-16 11:36:02.982  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:02.982  5010  5196 D BtGatt.ScanManager: Starting BLE batch scan
09-16 11:36:02.982  5010  5196 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,09-16 11:36:02.992  5010  5141 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-16 11:36:02.992  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 11:36:02.992  9697  9762 I io.jxcore.node.ConnectionHelper: start: OK
09-16 11:36:02.992  9697  9697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-16 11:36:02.992  5010  5141 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-16 11:36:02.992  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 11:36:02.992  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{27c477e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:02.992  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{62704df: PendingIntentRecord{1001aff com.android.bluetooth broadcastIntent}}
,09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 8
09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24566976
,09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-16 11:36:02.992  5010  5206 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24566976
09-16 11:36:02.992  9697  9697 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 11:36:03.002  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.002  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.002  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{593352c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.002  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:36:03.002  9697  9762 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 11:36:03.002  9697  9697 D BluetoothAdapter: STATE_ON
09-16 11:36:03.002  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.002  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 11:36:03.002  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:36:03.002  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:36:03.002  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-16 11:36:03.012  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.012  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{5e93bf5: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.012  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.012  9697  9697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
09-16 11:36:03.012  9697  9697 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-16 11:36:03.012  9697  9697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 11:36:03.012  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{9115d8a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.012  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-16 11:36:03.012  9697  9697 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:36:03.012  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 11:36:03.012  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 11:36:03.012  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 11:36:03.012  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-16 11:36:03.022  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{9a10ffb: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.022  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.022  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.022  9697  9762 D BluetoothLeScanner: Stop Scan
,09-16 11:36:03.022  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:36:03.022  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{3947818: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.022  5010  5028 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 11:36:03.022  5010  5028 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 11:36:03.022  5010  5028 D BtGatt.GattService: stopScan() - queue size =1
09-16 11:36:03.022  5010  5206 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-16 11:36:03.022  5010  5206 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
,09-16 11:36:03.022  5010  5206 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 11:36:03.022  5010  5196 D BtGatt.ScanManager: filter size is 1
09-16 11:36:03.022  5010  5196 D BtGatt.ScanManager: delete FilterIndex - 4
09-16 11:36:03.022  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-16 11:36:03.022  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-16 11:36:03.022  5010  5206 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-16 11:36:03.022  5010  5206 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-16 11:36:03.022  5010  5141 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-16 11:36:03.022  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:03.032  5010  5196 D BtGatt.ScanManager: stopping BLe Batch
09-16 11:36:03.032  5010  5415 D BtGatt.GattService: unregisterClient() - clientIf=7
,09-16 11:36:03.032  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.032  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 11:36:03.032  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 11:36:03.032  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-16 11:36:03.032  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 11:36:03.032  5010  5141 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-16 11:36:03.032  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{d5ea271: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.032  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:03.032  5010  5196 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-16 11:36:03.032  5010  5141 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-16 11:36:03.032  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:03.032  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 11:36:03.032  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{b2fc856: PendingIntentRecord{1001aff com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.032  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{ae6b0d7: PendingIntentRecord{1001aff com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.032  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:03.032  9697  9697 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 11:36:03.042  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.042  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.042  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.042  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.042  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.042  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-16 11:36:03.042  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 11:36:03.042  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{b64fdc4: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.042  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:36:03.042  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 11:36:03.042  9697  9697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:36:03.042  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:36:03.042  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 11:36:03.042  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.042  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:36:03.042  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.042  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.042  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.042  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 11:36:03.042  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:36:03.042  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{c963230: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.042  9697  9697 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 11:36:03.042  9697  9697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 11:36:03.052  9697  9697 D BluetoothAdapter: STATE_ON
09-16 11:36:03.052  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{5e2ea9: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.052  9697  9697 D BluetoothAdapter: STATE_ON
09-16 11:36:03.052  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.052  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{a078c2e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.052  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 11:36:03.052  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.052  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.052  9697  9697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 11:36:03.052  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 11:36:03.052  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 11:36:03.062  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{b80e3cf: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.052  9697  9697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.062  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:36:03.062  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.062  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{c64415c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.062  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.062  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.062  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.062  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.062  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.062  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.062  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:36:03.062  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.072  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{bc20c65: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.072  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.072  9697  9762 D BluetoothLeScanner: could not find callback wrapper
,09-16 11:36:03.072  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.072  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.072  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:03.072  9697  9762 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-16 11:36:03.072  9697  9697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:36:03.072  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:36:03.072  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 11:36:03.072  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:36:03.072  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{b655ff4: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.082  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.082  9697  9697 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 11:36:03.082  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 11:36:03.082  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{81e631d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.082  9697  9697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:36:03.082  9697  9762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:36:03.082  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:03.082  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:03.082  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:36:03.082  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:36:03.082  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:36:03.082  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:36:03.082  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:36:03.082  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.082  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{c913992: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.092  9697  9697 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 11:36:03.092  9697  9762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:36:03.092  9697  9762 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:36:03.092  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-16 11:36:03.092  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 11:36:03.092  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 11:36:03.092  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:36:03.092  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 11:36:03.092  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{24c2f63: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.092  9697  9762 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 11:36:03.092  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.102  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{f485ebf: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.102  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:03.102  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.102  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.102  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{568b98c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.102  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:36:03.102  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.102  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 11:36:03.102  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 11:36:03.102  9697  9762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 11:36:03.102  9697  9762 D BluetoothLeScanner: Start Scan
,09-16 11:36:03.102  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.112  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.112  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{467d8d5: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.112  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.112  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.112  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{e0668ea: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.112  5010  5028 D BtGatt.GattService: registerClient() - UUID=de5ea0fa-9798-4bb6-b0d9-d41013bf2c18
,09-16 11:36:03.142  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:03.152  5010  5141 D BtGatt.GattService: onClientRegistered() - UUID=de5ea0fa-9798-4bb6-b0d9-d41013bf2c18, clientIf=7
,09-16 11:36:03.152  9697  9707 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-16 11:36:03.152  5010  5415 D BtGatt.GattService: start scan with filters
,09-16 11:36:03.152  5010  5415 D BtGatt.GattService: getScanSettings
,09-16 11:36:03.162  5010  5415 D BtGatt.GattService: Is it foreground application = true
,09-16 11:36:03.162  5010  5415 D BtGatt.GattService: not a background application
,09-16 11:36:03.162  5010  5415 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-16 11:36:03.162  5010  5415 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 11:36:03.162  5010  5415 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 11:36:03.162  5010  5206 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-16 11:36:03.162  5010  5206 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
09-16 11:36:03.162  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 11:36:03.162  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 11:36:03.162  5010  5196 D BtGatt.ScanManager: handling starting scan
,09-16 11:36:03.162  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 11:36:03.162  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 11:36:03.162  5010  5196 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.172  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 11:36:03.172  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 11:36:03.172  9697  9697 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 11:36:03.172  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 11:36:03.172  5010  5196 D BluetoothAdapter: STATE_ON
09-16 11:36:03.172  5010  5206 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 15
09-16 11:36:03.172  5010  5206 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-16 11:36:03.172  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{bae27db: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.172  5010  5141 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-16 11:36:03.172  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:03.172  9697  9762 I io.jxcore.node.ConnectionHelper: start: OK
09-16 11:36:03.172  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:36:03.172  9697  9762 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 11:36:03.172  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.172  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 11:36:03.172  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.172  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:36:03.172  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 11:36:03.172  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-16 11:36:03.172  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 11:36:03.172  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 11:36:03.172  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 11:36:03.172  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 11:36:03.172  5010  5196 D BtGatt.ScanManager: set filter index= 5 for clientIf= 7
,09-16 11:36:03.172  5010  5196 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-16 11:36:03.172  5010  5196 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-16 11:36:03.172  5010  5196 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-16 11:36:03.182  5010  5141 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-16 11:36:03.182  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:03.182  5010  5196 D BtGatt.ScanManager: Starting BLE batch scan
09-16 11:36:03.182  5010  5196 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,09-16 11:36:03.182  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.182  5010  5141 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-16 11:36:03.182  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:03.182  5010  5206 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 9
09-16 11:36:03.182  5010  5206 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24566976
09-16 11:36:03.182  5010  5206 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-16 11:36:03.182  5010  5206 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 11:36:03.182  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.182  5010  5206 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 11:36:03.182  9697  9762 D BluetoothLeScanner: Stop Scan
09-16 11:36:03.182  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-16 11:36:03.182  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-16 11:36:03.182  5010  5206 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 11:36:03.182  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-16 11:36:03.182  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-16 11:36:03.182  5010  5206 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-16 11:36:03.182  5010  5141 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,09-16 11:36:03.182  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:03.182  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{7ade278: PendingIntentRecord{1001aff com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.182  5010  5206 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-16 11:36:03.192  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{da2d51: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.192  5010  5026 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-16 11:36:03.192  5010  5026 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-16 11:36:03.192  5010  5026 D BtGatt.GattService: stopScan() - queue size =1
09-16 11:36:03.192  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-16 11:36:03.192  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-16 11:36:03.192  5010  5206 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24566976
09-16 11:36:03.192  5010  5206 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
,09-16 11:36:03.192  5010  5206 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 16, currDate: 16
,09-16 11:36:03.192  5010  5206 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-16 11:36:03.192  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-16 11:36:03.192  5010  5206 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-16 11:36:03.192  5010  5206 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-16 11:36:03.192  5010  5206 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-16 11:36:03.192  5010  5415 D BtGatt.GattService: unregisterClient() - clientIf=7
09-16 11:36:03.192  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 11:36:03.192  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 11:36:03.192  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 11:36:03.192  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 11:36:03.192  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 11:36:03.192  5010  5196 D BtGatt.ScanManager: filter size is 1
,09-16 11:36:03.192  5010  5196 D BtGatt.ScanManager: delete FilterIndex - 5
09-16 11:36:03.192  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{45a29b6: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.192  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:36:03.192  5010  5141 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-16 11:36:03.192  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-16 11:36:03.192  5010  5196 D BtGatt.ScanManager: stopping BLe Batch
09-16 11:36:03.192  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.202  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.202  5010  5141 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-16 11:36:03.202  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.202  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 11:36:03.202  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.202  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.202  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 11:36:03.202  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 11:36:03.202  5010  5196 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-16 11:36:03.202  5010  5141 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-16 11:36:03.202  5010  5141 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-16 11:36:03.202  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{bdd66b7: PendingIntentRecord{1001aff com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.202  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:36:03.202  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{b1aae24: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.202  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{f434d8d: PendingIntentRecord{1001aff com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.202  9697  9697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:36:03.202  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:36:03.202  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 11:36:03.202  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:03.202  9697  9762 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 11:36:03.202  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.202  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:36:03.202  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.202  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.202  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:36:03.202  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
,09-16 11:36:03.202  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.202  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.202  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:03.202  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:36:03.212  9697  9697 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 11:36:03.212  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{4a43589: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.212  9697  9697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 11:36:03.212  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.212  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.212  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{330b98e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.212  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.212  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 11:36:03.212  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{61c75af: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.212  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.222  9697  9697 D BluetoothAdapter: STATE_ON
09-16 11:36:03.222  9697  9697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 11:36:03.222  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 11:36:03.222  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 11:36:03.222  9697  9697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.222  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{a539dbc: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.222  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:36:03.222  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.222  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.222  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.222  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{b11a145: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.222  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.222  9697  9762 D BluetoothLeAdvertiser: stop advertising
,09-16 11:36:03.222  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.222  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.222  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:36:03.232  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.232  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{602e09a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.232  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.232  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.232  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.232  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.232  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.232  9697  9697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:36:03.232  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:36:03.232  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 11:36:03.232  9697  9762 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-16 11:36:03.232  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:03.232  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.232  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:36:03.232  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.232  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.232  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:36:03.232  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.232  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.232  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.232  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 11:36:03.232  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.232  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:36:03.232  9697  9697 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 11:36:03.232  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 11:36:03.232  9697  9697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.232  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{99e6c66: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.242  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:36:03.242  9697  9697 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:36:03.242  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.242  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:36:03.242  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{a5f6ba7: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.242  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.242  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.242  9697  9762 D BluetoothLeAdvertiser: stop advertising
,09-16 11:36:03.242  9697  9762 D BluetoothLeAdvertiser: wrapper is null
,09-16 11:36:03.242  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.242  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:36:03.242  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.242  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.242  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.242  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 11:36:03.242  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.242  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:03.242  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{797e854: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.242  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-16 11:36:03.252  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:03.252  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.252  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:36:03.252  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.252  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.252  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.252  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.252  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.252  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.252  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:03.252  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.252  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.252  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.252  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.252  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:36:03.252  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.252  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{96fb3fd: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.252  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.252  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.252  9697  9762 D BluetoothLeAdvertiser: wrapper is null
,09-16 11:36:03.252  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.252  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:36:03.252  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.252  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.252  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.252  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.252  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.252  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.252  9697  9762 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-16 11:36:03.252  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:03.252  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.252  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:36:03.252  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.252  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.252  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{14e8f2: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.252  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.252  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.252  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.252  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:03.252  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:03.252  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.252  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.252  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.252  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.262  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.262  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.262  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.262  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{50d1b43: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.262  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.262  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.262  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.262  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:36:03.262  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.262  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.262  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.262  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.262  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.262  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:03.262  9697  9762 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-16 11:36:03.262  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:03.262  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{db535c0: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.262  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.262  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:36:03.262  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.262  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.262  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.262  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.262  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.262  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.262  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 11:36:03.262  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.262  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.262  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.262  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.262  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.272  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.272  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.272  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.272  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{f0892f9: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.272  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.272  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.272  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:36:03.272  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.272  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.272  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.272  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.272  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.272  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.272  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 11:36:03.272  9697  9762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 11:36:03.272  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-16 11:36:03.272  9697  9762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 11:36:03.272  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 11:36:03.272  9697  9762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 11:36:03.272  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:03.272  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.272  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:36:03.272  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.272  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.272  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.272  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.272  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.272  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:03.272  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:03.272  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.272  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.272  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.272  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.272  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.272  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.272  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{904a23e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.282  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.282  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.282  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.282  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.282  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:36:03.282  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.282  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.282  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.282  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.282  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.282  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:03.282  9697  9762 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 11:36:03.282  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{a5c289f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.282  9697  9762 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-16 11:36:03.282  9697  9762 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-16 11:36:03.282  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{797edec: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.282  9697  9762 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 11:36:03.292  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{6b665b5: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.282  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-16 11:36:03.282  9697  9762 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-16 11:36:03.282  9697  9762 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 11:36:03.292  9697  9762 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-16 11:36:03.292  9697  9762 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 11:36:03.292  9697  9762 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 11:36:03.292  9697  9762 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-16 11:36:03.292  9697  9762 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 11:36:03.292  9697  9762 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-16 11:36:03.292  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-16 11:36:03.292  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-16 11:36:03.292  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{da4a44a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.292  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-16 11:36:03.292  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-16 11:36:03.292  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-16 11:36:03.292  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-16 11:36:03.292  9697  9762 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-16 11:36:03.292  9697  9762 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 11:36:03.292  9697  9762 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-16 11:36:03.302  9697  9767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 224)
09-16 11:36:03.302  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:03.302  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.302  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:36:03.302  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.302  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.302  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.302  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-16 11:36:03.302  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
,09-16 11:36:03.302  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.302  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.302  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:03.302  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.302  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.302  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.302  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.302  9697  9768 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 224
,09-16 11:36:03.302  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.302  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.302  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.302  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.302  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.302  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.302  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:36:03.302  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.312  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.312  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.312  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.312  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.312  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:03.312  9697  9762 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-16 11:36:03.312  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:03.312  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.312  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:36:03.312  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.312  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.312  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.312  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.312  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.312  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.312  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:03.312  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.312  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.312  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.312  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.312  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.312  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.312  9697  9767 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,09-16 11:36:03.312  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.312  9697  9762 D BluetoothLeAdvertiser: stop advertising
,09-16 11:36:03.312  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.312  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.312  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:36:03.312  9697  9767 D BluetoothSocket: connect(): myUserId = 0
09-16 11:36:03.312  9697  9767 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:36:03.312  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.312  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.312  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.312  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.312  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.312  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:03.312  9697  9762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-16 11:36:03.312  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:03.312  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.312  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:36:03.312  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.312  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.312  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.312  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
,09-16 11:36:03.312  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.312  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.312  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:03.312  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.322  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.322  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.322  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.322  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:03.322  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.322  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.322  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.322  9697  9762 D BluetoothLeAdvertiser: stop advertising
,09-16 11:36:03.322  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.322  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.322  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:36:03.322  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.322  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.322  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.322  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.322  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.322  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.322  3459  3484 D SecContentProvider: insert(), uri = 2
,09-16 11:36:03.322  9697  9762 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-16 11:36:03.322  9697  9762 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-16 11:36:03.322  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 11:36:03.322  9697  9762 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-16 11:36:03.322  9697  9762 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 11:36:03.322  9697  9762 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-16 11:36:03.322  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-16 11:36:03.322  9697  9762 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-16 11:36:03.322  5010  5359 W bt_btif : bta_dm_acl_change(), event : 2
09-16 11:36:03.322  9697  9762 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 11:36:03.322  9697  9762 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 11:36:03.322  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 11:36:03.332  9697  9762 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-16 11:36:03.332  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:03.332  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 11:36:03.332  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:36:03.332  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.332  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.332  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.332  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.332  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.332  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.332  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 11:36:03.332  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.332  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.332  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{464afbb: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.332  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.332  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.332  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.332  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.332  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.332  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.332  9697  9762 D BluetoothLeAdvertiser: wrapper is null
,09-16 11:36:03.332  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.332  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:36:03.332  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{20bfcd8: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.332  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.332  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.332  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.332  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.332  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:36:03.332  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:03.332  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.332  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.332  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.332  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.332  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:36:03.332  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.332  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:03.342  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{d34a831: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.332  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.332  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.332  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:36:03.332  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.332  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.332  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.332  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.332  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
,09-16 11:36:03.332  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:36:03.332  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 11:36:03.332  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:36:03.342  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{190bb16: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.332  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 11:36:03.332  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.332  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.332  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.332  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.332  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:03.332  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:03.332  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.332  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.332  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.332  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.342  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.342  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.342  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.342  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.342  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.342  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 11:36:03.342  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:36:03.342  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.342  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.342  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.342  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 11:36:03.342  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.342  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.342  9697  9762 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 11:36:03.342  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:36:03.352  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-16 11:36:03.352  9697  9762 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-16 11:36:03.352  9697  9762 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 11:36:03.352  9697  9697 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-16 11:36:03.352  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 11:36:03.352  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 11:36:03.352  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 11:36:03.352  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 11:36:03.352  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 11:36:03.352  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-16 11:36:03.352  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.352  9697  9762 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-16 11:36:03.352  9697  9697 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 11:36:03.352  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
,09-16 11:36:03.352  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.352  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 11:36:03.352  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 11:36:03.352  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-16 11:36:03.352  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 11:36:03.352  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.352  9697  9769 D BluetoothSocket: bindListen(): myUserId = 0
09-16 11:36:03.352  9697  9769 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:36:03.352  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.352  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.352  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.352  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.352  9697  9769 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-16 11:36:03.352  9697  9769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-16 11:36:03.352  9697  9769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 11:36:03.352  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.352  9697  9762 D BluetoothLeAdvertiser: stop advertising
,09-16 11:36:03.352  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.352  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.352  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 11:36:03.352  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:36:03.352  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.362  9697  9762 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:36:03.362  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.362  9697  9697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:36:03.362  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:36:03.362  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 11:36:03.362  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:03.362  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.362  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:36:03.362  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.362  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.362  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:36:03.362  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.362  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.362  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.362  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:03.362  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.362  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:36:03.362  9697  9697 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 11:36:03.362  9697  9697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 11:36:03.362  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.362  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.362  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.372  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 11:36:03.372  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.372  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.372  9697  9697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 11:36:03.372  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 11:36:03.372  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 11:36:03.372  9697  9697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.372  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:36:03.372  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.372  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.372  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.372  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.372  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.372  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.372  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.372  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:36:03.372  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.382  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.382  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.382  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.382  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.382  9697  9697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 11:36:03.382  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:03.382  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:36:03.382  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 11:36:03.382  9697  9762 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-16 11:36:03.382  9697  9762 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 11:36:03.382  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 11:36:03.382  9697  9762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 11:36:03.382  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:36:03.382  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.382  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:36:03.382  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.382  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.382  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:36:03.382  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.382  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:36:03.382  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.382  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:03.382  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.382  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:36:03.382  9697  9697 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 11:36:03.382  9697  9697 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 11:36:03.382  9697  9697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.392  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:36:03.392  9697  9697 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 11:36:03.392  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.392  9697  9697 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 11:36:03.392  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.392  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.392  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.392  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.392  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.392  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.392  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:36:03.392  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.392  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.392  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.392  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.392  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.392  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:03.402  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:36:03.402  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.402  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:36:03.402  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.402  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.402  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.402  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.402  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.402  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.402  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:03.402  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.402  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.402  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.402  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.402  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.402  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.402  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.402  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.402  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.402  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:36:03.402  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:36:03.402  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.402  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.402  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.402  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.402  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:36:03.402  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.412  9697  9762 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:36:03.412  9697  9762 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:36:03.412  9697  9762 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:36:03.412  9697  9762 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:36:03.412  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:36:03.412  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.412  9697  9762 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bf4 not in the list
09-16 11:36:03.412  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:36:03.412  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
09-16 11:36:03.412  9697  9762 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:36:03.412  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.412  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 11:36:03.412  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:36:03.412  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 11:36:03.412  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:36:03.412  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.412  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.412  9697  9762 D BluetoothLeAdvertiser: stop advertising
09-16 11:36:03.412  9697  9762 D BluetoothLeAdvertiser: wrapper is null
09-16 11:36:03.412  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 11:36:03.412  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:36:03.412  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.412  9697  9762 D BluetoothAdapter: STATE_ON
09-16 11:36:03.412  9697  9762 D BluetoothLeScanner: could not find callback wrapper
09-16 11:36:03.412  9697  9762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:36:03.412  9697  9762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:36:03.412  9697  9762 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0f1d not in the list
,09-16 11:36:03.412  9697  9762 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-16 11:36:03.412  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 11:36:03.412  9697  9762 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-16 11:36:03.412  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 11:36:03.412  9697  9762 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-16 11:36:03.412  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-16 11:36:03.422  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-16 11:36:03.422  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-16 11:36:03.422  9697  9762 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-16 11:36:03.422  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 11:36:03.422  9697  9762 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-16 11:36:03.422  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 11:36:03.422  9697  9762 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-16 11:36:03.422  9697  9762 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-16 11:36:03.422  9697  9762 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-16 11:36:03.422  9697  9762 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-16 11:36:03.422  9697  9762 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-16 11:36:03.422  9697  9762 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-16 11:36:03.422  9697  9762 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-16 11:36:03.422  9697  9762 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-16 11:36:03.422  9697  9762 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 11:36:03.422  9697  9762 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@96c9c9a added. We now have 2 listener(s)
09-16 11:36:03.422  9697  9762 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 11:36:03.422  9697  9762 D BluetoothAdapter: enable()
,09-16 11:36:03.432  9697  9762 D BluetoothAdapter: enable(): BT is already enabled..!
,09-16 11:36:03.442  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b72c69 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
,09-16 11:36:03.442  9697  9762 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
09-16 11:36:03.442  3459  4380 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
09-16 11:36:03.442  3459  4380 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
09-16 11:36:03.442  3459  4380 D WifiService: setWifiEnabled: true pid=9697, uid=10177
,09-16 11:36:03.452  3459  4380 W ActivityManager: Permission Denial: getCurrentUser() from pid=9697, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
,09-16 11:36:03.452  3459  3858 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-16 11:36:03.452  3459  3858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-16 11:36:03.452  3459  4380 W WifiService: Failed getting userId using ActivityManagerNative
09-16 11:36:03.452  3459  4380 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9697, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
09-16 11:36:03.452  3459  4380 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28247)
09-16 11:36:03.452  3459  4380 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
09-16 11:36:03.452  3459  4380 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
09-16 11:36:03.452  3459  4380 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-16 11:36:03.452  3459  4380 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
09-16 11:36:03.452  3459  3858 D WifiBigDataLog: init : 
09-16 11:36:03.452  3459  4380 D SettingsProvider: isChangeAllowed() : name = wifi_on
09-16 11:36:03.452  3459  4380 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
09-16 11:36:03.452  3459  3861 D WifiController: [FCC]setFccChannel() is called !!!
,09-16 11:36:03.452  3459  3861 D WifiStateMachine: setFccChannel: channel = 0
09-16 11:36:03.452  3459  3861 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,09-16 11:36:03.452  9697  9762 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 11:36:03.452  9697  9762 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@411c9cb added. We now have 3 listener(s)
,09-16 11:36:03.452  9697  9762 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 11:36:03.452  3459  3858 D WifiStateMachine: setFccChannelNative: channel = 0
09-16 11:36:03.452  3459  3858 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-16 11:36:03.462  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.462  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fbc16ee u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
,09-16 11:36:03.462  9697  9762 D BluetoothAdapter: STATE_ON
,09-16 11:36:03.472  9697  9762 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 11:36:03.472  9697  9762 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@510f5a8 added. We now have 4 listener(s)
09-16 11:36:03.472  9697  9762 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 11:36:03.472  9697  9762 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 11:36:03.472  9697  9762 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b01f8c1 added. We now have 5 listener(s)
09-16 11:36:03.472  9697  9762 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 11:36:03.472  3459  4412 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-16 11:36:03.482  3459  4412 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-16 11:36:03.482  3459  4412 D WifiService: setWifiEnabled: false pid=9697, uid=10177
,09-16 11:36:03.482  3459  4412 D SettingsProvider: isChangeAllowed() : name = wifi_on
,09-16 11:36:03.482  3459  3861 D WifiController: [FCC]setFccChannel() is called !!!
,09-16 11:36:03.482  3459  3861 D WifiStateMachine: setFccChannel: channel = 0
09-16 11:36:03.482  3459  3861 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,09-16 11:36:03.482  3459  3861 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
09-16 11:36:03.482  9697  9762 D BluetoothAdapter: disable()
09-16 11:36:03.482  3459  3861 D SecContentProvider: insert(), uri = 2
,09-16 11:36:03.492  3459  3858 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-16 11:36:03.492  3459  3858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-16 11:36:03.492  3459  3858 D WifiBigDataLog: init : 
,09-16 11:36:03.502  3459  4416 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
09-16 11:36:03.502  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:03.502  3459  3570 D SecContentProvider: insert(), uri = 2
,09-16 11:36:03.502  5010  5137 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
09-16 11:36:03.502  3459  3858 D WifiStateMachine: setFccChannelNative: channel = 0
09-16 11:36:03.502  3459  3858 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-16 11:36:03.512  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c26778f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
,09-16 11:36:03.512  9697  9762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:36:03.512  5010  5137 D BluetoothAdapterProperties: Setting state to 13
09-16 11:36:03.512  5010  5137 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-16 11:36:03.512  5010  5137 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-16 11:36:03.512  5010  5137 D BluetoothAdapterService: updateAdapterState state is 13
,09-16 11:36:03.522  3459  3858 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-16 11:36:03.522  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:03.522  9697  9762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:36:03.522  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:03.522  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:03.522  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:36:03.522  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:36:03.522  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:36:03.522  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:36:03.522  9697  9762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 11:36:03.522  9697  9762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:03.522  9697  9762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 11:36:03.522  9697  9762 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:36:03.522  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:36:03.522  3459  4053 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{99cfdab u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
,09-16 11:36:03.532  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:03.532  3459  3858 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,09-16 11:36:03.532  3459  3858 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 11:36:03.532  5010  5010 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-16 11:36:03.532  3459  3858 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,09-16 11:36:03.532  5010  5137 D BluetoothAdapterService: Autoconnection is available 
09-16 11:36:03.532  5010  5137 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-16 11:36:03.532  5010  5137 D BluetoothAdapterService: terminating service from this receiver
,09-16 11:36:03.542  3459  3570 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
,09-16 11:36:03.552  3949  4129 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 11:36:03.552  3949  4129 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,09-16 11:36:03.552  3949  3949 D BluetoothPbap: Proxy object disconnected
09-16 11:36:03.552  3949  3949 D PbapServerProfile: Bluetooth service disconnected
,09-16 11:36:03.552  5010  5137 D BluetoothAdapterProperties: onBluetoothDisable()
09-16 11:36:03.552  3459  3459 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:03.552  3459  3459 I InputMethodManagerService: [BT Setting State] State =13
,09-16 11:36:03.552  5010  5137 W bt_btif : btif_dm_cancel_discovery
,09-16 11:36:03.552  3949  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,09-16 11:36:03.552  3949  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-16 11:36:03.552  3459  4834 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
09-16 11:36:03.562  4346  4346 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,09-16 11:36:03.562  3459  4049 D SecContentProvider: insert(), uri = 2
,09-16 11:36:03.562  5010  5137 I BluetoothAdapterState: Entering PendingCommandState
,09-16 11:36:03.562  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-16 11:36:03.562  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{a644c08: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.562  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:03.562  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
09-16 11:36:03.572  7545  7545 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-16 11:36:03.572  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:03.572  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:36:03.572  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:03.572  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:03.572  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:36:03.572  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:36:03.572  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:36:03.572  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:36:03.572  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:36:03.572  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:03.572  9697  9697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:36:03.572  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20effa1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf426af 9356:com.android.settings/1000}
,09-16 11:36:03.582  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:03.582  3459  3858 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 11:36:03.582  3459  3858 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 11:36:03.582  3459  3858 D SecContentProvider: insert(), uri = 2
,09-16 11:36:03.592  3459  3858 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 11:36:03.592  5010  5141 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-16 11:36:03.592  5010  5141 D BluetoothAdapterProperties: Scan Mode:20
09-16 11:36:03.592  3459  3858 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 11:36:03.592  3459  3858 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,09-16 11:36:03.592  5010  5137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,09-16 11:36:03.592  3459  3858 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,09-16 11:36:03.592  3459  3858 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 11:36:03.592  3459  3858 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 11:36:03.592  3459  3858 E WifiNative-wlan0: do suspend true
,09-16 11:36:03.602  9356  9356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 11:36:03.602  5010  5137 E BluetoothServiceJni: disableBrEdrNative:
09-16 11:36:03.602  5010  5137 E bt_bluedroid: disable_bredr
,09-16 11:36:03.612  5010  5138 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-16 11:36:03.612  5010  5138 E bt_btif : BTA_DisableBluetoothOnly
09-16 11:36:03.612  5010  5502 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-16 11:36:03.612  5010  5503 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-16 11:36:03.612  5010  5503 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-16 11:36:03.612  5010  5502 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-16 11:36:03.612  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{9cc15c6: PendingIntentRecord{7abc987 com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.612  5010  5485 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 11:36:03.612  5010  5359 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-16 11:36:03.612  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-16 11:36:03.622  5010  5138 D IOP_DB_BT: db_close: nbr users 0
09-16 11:36:03.622  5010  5138 D IOP_DB_BT: db_close: free database
,09-16 11:36:03.622  5010  5359 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
09-16 11:36:03.622  5010  5359 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
09-16 11:36:03.622  5010  5359 W bt_btif : bta_dm_acl_change(), event : 2
09-16 11:36:03.622  5010  5359 W bt_btif : bta_dm_acl_change(), event : 5
,09-16 11:36:03.622  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:36:03.622  3459  4412 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-16 11:36:03.622  3949  4176 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
09-16 11:36:03.622  3949  4129 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 11:36:03.622  3949  4129 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
09-16 11:36:03.622  3459  3857 D WifiP2pService: InactiveState{ what=143375 }
09-16 11:36:03.622  3459  3857 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-16 11:36:03.632  9697  9767 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 224)
,09-16 11:36:03.632  3459  4742 V AlarmManager:  remove PendingIntent] PendingIntent{5faf4dd: PendingIntentRecord{1c79ed7 android broadcastIntent}}
09-16 11:36:03.632  3155  3637 D CommandListener: Clearing all IP addresses on wlan0
,09-16 11:36:03.642  4271  5910 V NativeCrypto: Read error: ssl=0x7f96f74b00: I/O error during system call, Connection timed out
,09-16 11:36:03.652  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{263c852: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.662  4271  5910 V NativeCrypto: SSL shutdown failed: ssl=0x7f96f74b00: I/O error during system call, Broken pipe
,09-16 11:36:03.662  3459  3867 E ConnectivityService: updateNetworkInfo()
09-16 11:36:03.662  3459  3867 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]
09-16 11:36:03.662  3459  3867 E ConnectivityService: updateNetworkInfo()
09-16 11:36:03.662  3459  3867 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
09-16 11:36:03.662  3459  3867 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 5
,09-16 11:36:03.662  3459  3867 V NetworkStats: updateIfacesLocked()
09-16 11:36:03.662  3459  3867 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 11:36:03.662  3459  3867 V NetworkStats: performPollLocked(flags=0x1)
09-16 11:36:03.662  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{cf17723: PendingIntentRecord{b7b16da com.google.android.gms broadcastIntent}}
,09-16 11:36:03.662  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:03.672  9356  9356 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
09-16 11:36:03.672  4271  5910 E GCM     : Wifi connection closed with errorCode 20
,09-16 11:36:03.672  3459  3867 V NetworkStats: performPollLocked() took 6ms
09-16 11:36:03.672  3459  3867 D NtpTrustedTime: currentTimeMillis() cache hit
,09-16 11:36:03.682  3949  3949 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
09-16 11:36:03.682  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:36:03.682  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:03.692  3459  4856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20effa1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
,09-16 11:36:03.702  3459  3867 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 11:36:03.702  3459  3867 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]
09-16 11:36:03.702  3459  3867 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-16 11:36:03.702  3459  3867 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 11:36:03.702  3459  3867 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
09-16 11:36:03.702  3459  3867 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [] ]
,09-16 11:36:03.702  3459  3858 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-16 11:36:03.702  3459  3857 D WifiP2pService: InactiveState{ what=131204 }
09-16 11:36:03.702  4127  4127 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
09-16 11:36:03.702  3459  3857 D WifiP2pService: P2pEnabledState{ what=131204 }
09-16 11:36:03.702  4127  4127 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
09-16 11:36:03.702  9356  9356 D LocalBluetoothManager: LocalBluetoothManager :: constructor
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  5010  5359 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:03.702  3459  3867 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-16 11:36:03.702  9356  9356 D BluetoothEventManager: BluetoothEventManager Constructor :: 
09-16 11:36:03.702  3459  3867 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 11:36:03.702  3459  3867 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 11:36:03.702  3459  3857 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-16 11:36:03.702  3459  3867 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 11:36:03.712  3459  3856 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 11:36:03.712  3459  3867 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 11:36:03.712  3459  3856 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 11:36:03.712  3459  3867 D ConnectivityService: sending notification LOST for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 11:36:03.722  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{15a627f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:03.722  3459  4741 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-16 11:36:03.722  3459  3867 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 11:36:03.722  3459  3858 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 11:36:03.722  3459  3858 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 11:36:03.722  3459  3858 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-16 11:36:03.722  3459  3858 D WIFI    : evalRequest
09-16 11:36:03.722  3459  3858 D WIFI    :   needNetworkFor
09-16 11:36:03.722  3459  4864 D ConnectivityService: getVpnConfig > userId : 0
09-16 11:36:03.722  3459  3892 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 11:36:03.722  3459  3892 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
09-16 11:36:03.722  3459  3892 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-16 11:36:03.722  3459  3892 D Ethernet: evalRequest
09-16 11:36:03.722  3459  3892 D Ethernet:   done
09-16 11:36:03.732  3459  3858 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 11:36:03.732  3459  3858 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 11:36:03.732  3459  3858 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-16 11:36:03.732  3459  3858 D WIFI_UT : evalRequest
09-16 11:36:03.732  3459  3858 D WIFI_UT :   done
09-16 11:36:03.732  3459  3858 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 11:36:03.732  3459  3858 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 11:36:03.732  3459  3858 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-16 11:36:03.732  3459  3858 D WIFI    : evalRequest
09-16 11:36:03.732  3459  3858 D WIFI    :   done
09-16 11:36:03.732  3459  3459 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-16 11:36:03.732  3459  3570 D EntConnectivity: Not allowed due to - mEnabled false
09-16 11:36:03.732  3459  3459 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-16 11:36:03.732  3459  3459 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.732  3459  3459 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
09-16 11:36:03.742  3459  3459 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-16 11:36:03.742  3459  3459 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
09-16 11:36:03.742  3459  3865 I WifiHs20Service: Message received 5007
09-16 11:36:03.742  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 11:36:03.742  4305  4305 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-16 11:36:03.752  3459  4856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20effa1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5287a2d 4271:com.google.android.gms.persistent/u0a21}
09-16 11:36:03.752  4271  4271 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
09-16 11:36:03.752  3459  3459 D RttService: SCAN_AVAILABLE : 1
09-16 11:36:03.762  3459  3857 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-16 11:36:03.762  3459  3891 D RttService: EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-16 11:36:03.762  5010  5010 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:03.762  5010  5010 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
09-16 11:36:03.762  5010  5010 D ObexServerSockets: shutdown(block = true)
09-16 11:36:03.762  5010  5010 D ObexServerSockets: shutdown called from another thread - interrupt().
09-16 11:36:03.762  5010  5010 D ObexServerSockets: shutdown called from another thread - interrupt().
09-16 11:36:03.762  5010  5010 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
09-16 11:36:03.762  5010  5010 D BluetoothSdpJni: SDP Remove record success - handle: 1
09-16 11:36:03.762  5010  5010 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
09-16 11:36:03.762  5010  5010 D BluetoothSdpJni: SDP Remove record success - handle: 0
09-16 11:36:03.762  5010  5010 I BtOppRfcommListener: stopping Accept Thread
09-16 11:36:03.762  5010  5485 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-16 11:36:03.762  3155  3637 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-16 11:36:03.762  3459  3459 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
09-16 11:36:03.762  3459  3459 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
09-16 11:36:03.762  4165  4177 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
09-16 11:36:03.762  4165  4165 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 11:36:03.762  4165  4165 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 11:36:03.762  4165  4165 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 11:36:03.772  4165  4165 I PeopleDataManager: removeNotification
09-16 11:36:03.772  4165  4165 I NotificationParser: getNotiType:android,null
09-16 11:36:03.772  4165  4165 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 11:36:03.772  4165  4165 D PeopleDataManager: removeNotiInfo =null
09-16 11:36:03.772  9356  9356 D LocalBluetoothProfileManager: PANU : true
09-16 11:36:03.772  3459  3571 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.772  3459  3571 I WifiDisplayAdapter: onP2pDisconnected
09-16 11:36:03.772  5010  5137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e400b
09-16 11:36:03.772  3459  3571 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-16 11:36:03.772  3459  3571 D IpRemoteDisplayController: WfdBridgeServer is already null
09-16 11:36:03.772  5010  5141 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,09-16 11:36:03.782  3459  3459 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-16 11:36:03.782  3459  3571 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
,09-16 11:36:03.782  3459  3571 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-16 11:36:03.782  3459  3571 D WifiDisplayController: disconnect
,09-16 11:36:03.782  3459  3571 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-16 11:36:03.792  3155  3637 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 11:36:03.792  3459  3867 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
09-16 11:36:03.792  3459  3867 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
09-16 11:36:03.792  3459  3867 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-16 11:36:03.792  3459  3979 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20effa1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1de32d 8934:com.sec.android.app.shealth:remote/u0a39}
,09-16 11:36:03.802  3459  3570 D EntConnectivity: Not allowed due to - mEnabled false
,09-16 11:36:03.802  3459  3857 D SecContentProvider: insert(), uri = 2
,09-16 11:36:03.802  3459  3857 D WifiP2pService: P2pDisablingState
09-16 11:36:03.802  3459  3857 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-16 11:36:03.802  3459  3857 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 11:36:03.802  3459  3857 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-16 11:36:03.802  3459  3857 D WIFI_P2P: evalRequest
09-16 11:36:03.802  3459  3857 D WifiP2pService: P2pDisablingState{ what=147458 },
,09-16 11:36:03.802  3459  3857 D WIFI_P2P:   done
,09-16 11:36:03.802  3459  3857 D WifiP2pService: p2p socket connection lost
09-16 11:36:03.802  3459  3857 D SecContentProvider: insert(), uri = 2
,09-16 11:36:03.812  3459  3858 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-16 11:36:03.812  3459  3857 D WifiP2pService: P2pDisabledState
09-16 11:36:03.812  3459  3858 E WifiNative-wlan0: do suspend true
,09-16 11:36:03.812  5010  5141 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-16 11:36:03.812  5010  5141 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,09-16 11:36:03.812  5010  5141 E BluetoothAdapterState: stateChangeCallback : 16
09-16 11:36:03.822  5010  5137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
09-16 11:36:03.822  3949  4129 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,09-16 11:36:03.822  5010  5010 V BluetoothOppManager: cleanUp...
,09-16 11:36:03.822  3459  3571 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 11:36:03.822  3459  3571 I WifiDisplayAdapter: onP2pDisconnected
09-16 11:36:03.822  3459  3571 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-16 11:36:03.822  3459  3571 D IpRemoteDisplayController: WfdBridgeServer is already null
09-16 11:36:03.832  3459  3857 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-16 11:36:03.832  5010  5137 D BtConfig.SecureMode: isSecureModeOn:false
,09-16 11:36:03.832  3459  3857 D WifiP2pService: DefaultState{ what=143375 }
09-16 11:36:03.832  5010  5137 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-16 11:36:03.832  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{147cf4d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:03.832  9356  9356 D BluetoothSap: Create BluetoothSap proxy object
,09-16 11:36:03.842  3459  3459 D Tethering: Tethering got CONNECTIVITY_ACTION
,09-16 11:36:03.842  3459  9778 I ApplicationPolicy: updateDataUsageMap
09-16 11:36:03.842  3459  3570 D Tethering: MasterInitialState.processMessage what=3
09-16 11:36:03.842  3459  3459 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:03.842  3459  3459 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,09-16 11:36:03.842  3459  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-16 11:36:03.842  3459  3459 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:03.842  3459  3459 I CLocInfoService: CLoinfo wifi false
,09-16 11:36:03.842  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:03.842  3459  3537 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-16 11:36:03.842  4305  4627 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-16 11:36:03.842  3459  3537 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:03.852  3459  3537 D GpsLocationProvider: updateNetworkState unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:03.852  4305  4627 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-16 11:36:03.852  3459  4252 V AlarmManager:  remove PendingIntent] PendingIntent{1c8c1bb: PendingIntentRecord{f23a6d8 android broadcastIntent}}
09-16 11:36:03.852  3459  4250 W SLocation: No Active Data Connection
09-16 11:36:03.852  3459  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-16 11:36:03.852  3459  4250 W SLocation: No Active Data Connection
09-16 11:36:03.852  3459  4250 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:03.852  3949  3949 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
09-16 11:36:03.852  3949  3949 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-16 11:36:03.852  3949  3949 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-16 11:36:03.862  3459  3459 V MARsPolicyManager: DataConnection: false
09-16 11:36:03.862  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:03.862  5051  5165 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
09-16 11:36:03.862  5051  5165 I CellLocationSupport: onCellLocationChanged
09-16 11:36:03.862  4305  4632 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-16 11:36:03.862  4305  4632 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-16 11:36:03.862  5051  5051 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
09-16 11:36:03.862  5051  5051 D PdnController: isSuspended [false] networktype [1]
,09-16 11:36:03.862  3459  3484 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:03.872  5051  5051 D PdnController: isPdnUp  [false] networktype [1]
09-16 11:36:03.872  5051  5051 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [false] 
09-16 11:36:03.872  5373  5373 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ae33fc0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:03.872  3459  3537 D TelephonyManager: getDataEnabled: retVal=true
,09-16 11:36:03.882  3459  3856 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 11:36:03.882  3459  3856 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 11:36:03.882  3459  3856 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 11:36:03.882  3459  3856 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 11:36:03.882  3459  3856 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-16 11:36:03.882  7545  7545 D SamsungIME: EngineType = SWIFTKEY
09-16 11:36:03.882  3459  3856 D NtpTrustedTime: currentTimeMillis() cache hit
,09-16 11:36:03.882  5051  5165 I CellLocationSupport: Block to update PANI information in non VoWIFI
09-16 11:36:03.882  5051  5165 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,09-16 11:36:03.882  8376  8395 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
09-16 11:36:03.882  8376  8395 I SystemBroadcastReceiver: [#CMH#] No one is registered with Event Id EVENT_NETWORK_CHANGED
09-16 11:36:03.882  3459  3974 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:03.882  8376  8395 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,09-16 11:36:03.892  5051  5165 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
09-16 11:36:03.892  5051  5165 D PdnController: isPdnUp  [false] networktype [0]
09-16 11:36:03.892  5051  5165 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
09-16 11:36:03.892  3155  3637 E Netd    : netlink response contains error (No such file or directory)
09-16 11:36:03.892  9697  9697 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 11:36:03.892  5051  5165 D RegistrationManager: handleMessage(): 5
,09-16 11:36:03.892  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.892  3459  3867 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
09-16 11:36:03.892  3459  3867 D ConnectivityService: nai.networkMonitor.doQuit()
,09-16 11:36:03.892  3459  3867 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
,09-16 11:36:03.892  3459  3867 E ConnectivityService: updateNetworkInfo()
09-16 11:36:03.892  3459  3867 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 11:36:03.892  3459  3867 E ConnectivityService: updateNetworkInfo()
09-16 11:36:03.892  3459  3867 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
09-16 11:36:03.902  3459  3595 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-16 11:36:03.902  4165  7324 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=84]
09-16 11:36:03.902  4165  4165 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 11:36:03.902  4165  4165 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 11:36:03.902  4165  4165 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 11:36:03.902  4165  4165 I PeopleDataManager: removeNotification
09-16 11:36:03.902  4165  4165 I NotificationParser: getNotiType:android,null
09-16 11:36:03.902  4165  4165 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 11:36:03.902  4165  4165 D PeopleDataManager: removeNotiInfo =null
,09-16 11:36:03.902  5051  5165 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
09-16 11:36:03.902  5051  5165 D PdnController: isPdnUp  [false] networktype [11]
09-16 11:36:03.902  5051  5165 D RegistrationManager: setEPDGIPSecConnected [false]
09-16 11:36:03.902  5051  5165 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [false] IPAddresses [[]] DNSAddresses [[]] 
09-16 11:36:03.902  5051  5165 D RegistrationManager: isEPDGAvailable [false]
09-16 11:36:03.902  5051  5165 D CoreController: setState [DEREGISTERED]
,09-16 11:36:03.912  3949  3949 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-16 11:36:03.912  3949  3949 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-16 11:36:03.912  3949  3949 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-16 11:36:03.922  7545  7545 D SamsungIME: mNetworkChangeReceiver isWLANConnected : false
,09-16 11:36:03.922  3459  4864 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-16 11:36:03.922  3949  3949 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-16 11:36:03.922  3459  3595 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.932  3155  3637 D CommandListener: Clearing all IP addresses on wlan0
09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.932  5010  5137 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-16 11:36:03.932  4437  4437 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.932  5010  5010 D HeadsetService: Received stop request...Stopping profile...
09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.932  9697  9697 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
,09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:03.932  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:03.942  9356  9356 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-16 11:36:03.942  9356  9356 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,09-16 11:36:03.952  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:03.952  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:36:03.952  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:03.952  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:03.952  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:36:03.952  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:36:03.952  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:36:03.952  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:36:03.952  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:36:03.952  4305  4632 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@2b851b2, selection=nullselectionArgs=null, sort=name ASC
09-16 11:36:03.952  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:03.952  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:03.952  9697  9697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:36:03.962  5010  5010 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
09-16 11:36:03.962  5010  5010 E HeadsetService: notifyProfileServiceStateChanged
,09-16 11:36:03.962  3155  3633 D EnterpriseController: netId is 0
09-16 11:36:03.962  3155  3633 D Netd    : getNetworkForDns: using netid 0 for uid 10002
,09-16 11:36:03.962  5010  5137 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-16 11:36:03.972  4569  9786 D MdnsClient: Multicast lock held. Releasing
09-16 11:36:03.972  4644  9784 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
09-16 11:36:03.972  4644  9784 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
09-16 11:36:03.972  4644  9784 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-16 11:36:03.972  4644  9784 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-16 11:36:03.972  4644  9784 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-16 11:36:03.972  4644  9784 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
09-16 11:36:03.972  4644  9784 E         : 	at java.lang.Thread.run(Thread.java:818)
09-16 11:36:03.972  4644  9784 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 11:36:03.972  4644  9784 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
09-16 11:36:03.972  4644  9784 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
09-16 11:36:03.972  4644  9784 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
09-16 11:36:03.972  4644  9784 E         : 	... 9 more
09-16 11:36:03.972  4644  9784 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
09-16 11:36:03.972  4644  9784 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
09-16 11:36:03.972  4644  9784 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
09-16 11:36:03.972  4644  9784 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
09-16 11:36:03.972  4644  9784 E     ,    : 	... 24 more
09-16 11:36:03.972  4644  9784 E         : 
09-16 11:36:03.972  4644  9784 E         : Unable to fetch advertisement frequency.
09-16 11:36:03.972  4644  9784 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
09-16 11:36:03.972  4644  9784 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-16 11:36:03.972  4644  9784 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-16 11:36:03.972  4644  9784 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-16 11:36:03.972  4644  9784 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
09-16 11:36:03.972  4644  9784 E         : 	at java.lang.Thread.run(Thread.java:818)
09-16 11:36:03.972  4644  9784 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 11:36:03.972  4644  9784 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
09-16 11:36:03.972  4644  9784 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
09-16 11:36:03.972  4644  9784 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
09-16 11:36:03.972  4644  9784 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
09-16 11:36:03.972  4644  9784 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
09-16 11:36:03.972  4644  9784 E         : 	... 9 more
09-16 11:36:03.972  4644  9784 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
09-16 11:36:03.972  4644  9784 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
09-16 11:36:03.972  4644  9784 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
09-16 11:36:03.972  4644  9784 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
09-16 11:36:03.972  4644  9784 E         : 	... 24 more
09-16 11:36:03.972  4644  9784 E         :, 
09-16 11:36:03.972  3459  3979 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20effa1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf426af 9356:com.android.settings/1000}
09-16 11:36:03.972  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:03.972  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:36:03.972  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:03.972  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:03.972  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:36:03.972  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:36:03.972  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:36:03.972  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:36:03.972  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:36:03.982  4305  4632 D TelephonyProvider: query: match = 5
09-16 11:36:03.982  4305  4632 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
09-16 11:36:03.982  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:03.982  9697  9697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:36:03.982  5051  5165 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
09-16 11:36:03.982  5051  5165 D RegistrationManager: getNetworkType [0]
09-16 11:36:03.982  5051  5165 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [false] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
09-16 11:36:03.992  5051  5165 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
09-16 11:36:03.992  5051  5165 D CoreStackAdaptor2: ipList =  Null
09-16 11:36:03.992  5051  5165 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
09-16 11:36:03.992  5051  5165 D RegistrationManager: isPreconditionProperToGoOn
09-16 11:36:03.992  5051  5165 D RegistrationManager: isDeviceShutdown [false]
09-16 11:36:03.992  5051  5165 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
09-16 11:36:03.992  5051  5165 D RegistrationManager: isDmVoLTEUpdated [false]
09-16 11:36:03.992  5051  5165 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
09-16 11:36:03.992  5051  5165 D RegistrationManager: tryRegister : Not all preconditions are met!
09-16 11:36:03.992  3459  3858 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-16 11:36:03.992  4127  4127 I wpa_supplicant: Blacklist: Clear (all) 
09-16 11:36:03.992  4127  4127 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
09-16 11:36:03.992  9356  9356 D DockEventReceiver: finishStartingService: stopping service
09-16 11:36:03.992  3949  3949 D HeadsetProfile: Bluetooth service disconnected
09-16 11:36:03.992  3459  3459 D BluetoothHeadset: unRegisterMessageListener : 11
09-16 11:36:03.992  3459  3459 W BluetoothHeadset: Proxy not attached to service
09-16 11:36:04.002  3459  3459 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
09-16 11:36:03.992  3459  3459 I Telecom : BluetoothManager : unregister MessageListener
09-16 11:36:04.002  5010  5010 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:04.002  5010  5010 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
09-16 11:36:04.002  5010  5137 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-16 11:36:04.002  9356  9356 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 11:36:04.002  5010  5010 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:04.002  5010  5010 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:04.002  5010  5010 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:04.002  5010  5010 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:04.002  9356  9356 D PanProfile: Bluetooth service connected
09-16 11:36:04.002  3459  3459 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-16 11:36:04.012  5010  5010 D A2dpService: Received stop request...Stopping profile...
09-16 11:36:04.012  9356  9356 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
09-16 11:36:04.012  3459  3459 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-16 11:36:04.012  3459  3459 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
09-16 11:36:04.012  3459  3459 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-16 11:36:04.012  3459  3865 I WifiHs20Service: Message received 5007
09-16 11:36:04.012  3459  3459 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
09-16 11:36:04.012  9356  9356 D BluetoothSap: Proxy object connected
09-16 11:36:04.022  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 11:36:04.022  9356  9356 D SapProfile: Bluetooth service connected
09-16 11:36:04.022  9356  9356 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:04.022  9356  9356 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
09-16 11:36:04.022  4305  4305 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
09-16 11:36:04.022  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{c81a44e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:04.022  5010  5137 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-16 11:36:04.032  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 11:36:04.032  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-16 11:36:04.032  3949  3949 I HotspotTile: Provider is not defined returning false
09-16 11:36:04.032  3949  3949 D HotspotTile: onReceive : 0, 0
09-16 11:36:04.042  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:36:04.042  3949  3949 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,09-16 11:36:04.042  5010  5431 D A2dpStateMachine: Exit Disconnected: -1
09-16 11:36:04.042  3459  3858 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 11:36:04.042  3459  3459 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,09-16 11:36:04.042  3459  3459 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-16 11:36:04.042  3459  3865 I WifiHs20Service: Message received 5011
,09-16 11:36:04.052  3155  3630 D Netd    : Iface p2p0 link up
,09-16 11:36:04.052  3459  3459 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,09-16 11:36:04.052  5010  5137 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-16 11:36:04.052  5051  5066 D PdnController: Interface Changed p2p0 link up
,09-16 11:36:04.062  3459  3546 D Tethering: interfaceLinkStateChanged p2p0, true
09-16 11:36:04.062  3459  3546 D Tethering: interfaceStatusChanged p2p0, true
09-16 11:36:04.062  3459  3537 E GpsLocationProvider: No APN found to select.
09-16 11:36:04.062  3459  3459 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
09-16 11:36:04.062  3459  3459 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,09-16 11:36:04.062  4165  4180 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
,09-16 11:36:04.062  4165  4165 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 11:36:04.062  4165  4165 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 11:36:04.062  5010  5010 D Avrcp   : unregisterContentObserver
09-16 11:36:04.062  5010  5010 D Avrcp   : removeOnActiveSessionsChangedListener
,09-16 11:36:04.062  4165  4165 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 11:36:04.062  4165  4165 I PeopleDataManager: removeNotification
09-16 11:36:04.062  4165  4165 I NotificationParser: getNotiType:android,null
09-16 11:36:04.062  4165  4165 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 11:36:04.062  4165  4165 D PeopleDataManager: removeNotiInfo =null
,09-16 11:36:04.062  5010  5137 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,09-16 11:36:04.062  5010  5010 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
,09-16 11:36:04.062  5010  5010 E A2dpService: notifyProfileServiceStateChanged
09-16 11:36:04.062  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:04.062  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:36:04.062  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:04.062  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:04.062  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:36:04.062  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:36:04.062  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:36:04.062  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:36:04.062  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:36:04.072  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:04.072  9697  9697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:36:04.072  5010  5137 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-16 11:36:04.072  5010  5137 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-16 11:36:04.072  5010  5137 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-16 11:36:04.072  5010  5137 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-16 11:36:04.072  5041  5041 D BluetoothA2dp: Proxy object disconnected
09-16 11:36:04.072  5010  5137 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
09-16 11:36:04.072  3459  3459 D BluetoothA2dp: Proxy object disconnected
,09-16 11:36:04.072  3459  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-16 11:36:04.082  3949  3949 D BluetoothA2dp: Proxy object disconnected
,09-16 11:36:04.082  3949  3949 D A2dpProfile: Bluetooth service disconnected
,09-16 11:36:04.082  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{596e96f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:04.082  4305  4632 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-16 11:36:04.082  4305  4632 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-16 11:36:04.092  3459  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-16 11:36:04.092  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 11:36:04.092  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:36:04.092  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:04.092  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:04.092  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:36:04.092  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:36:04.092  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:36:04.092  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:36:04.092  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:36:04.092  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:04.092  9697  9697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:36:04.102  4127  4127 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-16 11:36:04.102  4127  4127 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-16 11:36:04.102  3155  3630 D Netd    : Iface wlan0 link up
09-16 11:36:04.102  5051  5346 D PdnController: Interface Changed wlan0 link up
09-16 11:36:04.102  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 11:36:04.102  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
,09-16 11:36:04.112  9789  9789 E Zygote  : v2
09-16 11:36:04.112  9789  9789 I libpersona: KNOX_SDCARD checking this for 5010
09-16 11:36:04.112  9789  9789 I libpersona: KNOX_SDCARD not a persona
09-16 11:36:04.112  9789  9789 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 11:36:04.112  3459  3483 I ActivityManager: Start proc 9789:com.samsung.android.intelligenceservice2/5010 for broadcast-3 com.samsung.android.intelligenceservice2/com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor$BtConnectionReceiver
,09-16 11:36:04.112  9789  9789 E Zygote  : accessInfo : 0
09-16 11:36:04.112  9789  9789 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.intelligenceservice2 
,09-16 11:36:04.122  3459  3537 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,09-16 11:36:04.132  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{73b667c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:04.132  5010  5010 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-16 11:36:04.132  5010  5010 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-16 11:36:04.132  5010  5010 D HeadsetProvider: cleanup
09-16 11:36:04.132  5010  5010 I HeadsetProvider: clearAllHeadsetSettings(0)
,09-16 11:36:04.142  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{d6c9b05: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:04.142  9789  9789 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:04.142  9789  9789 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:04.152  5010  5010 D HidService: Received stop request...Stopping profile...
09-16 11:36:04.152  5010  5010 D HidService: Stopping Bluetooth HidService
09-16 11:36:04.152  5010  5010 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-16 11:36:04.152  5010  5010 W bt_btif : cleanup: HH disabling or disabled already, status = 0
09-16 11:36:04.152  5010  5010 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-16 11:36:04.152  5010  5010 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
09-16 11:36:04.152  5010  5010 E HidService: notifyProfileServiceStateChanged
,09-16 11:36:04.152  3459  4053 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20effa1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{957b75a 9789:com.samsung.android.intelligenceservice2/5010}
,09-16 11:36:04.162  3949  3949 D BluetoothInputDevice: Proxy object disconnected
09-16 11:36:04.162  3949  3949 D HidProfile: Bluetooth service disconnected
,09-16 11:36:04.162  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{dd2ad8b: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:04.162  5010  5010 D HealthService: Received stop request...Stopping profile...
09-16 11:36:04.162  5010  5010 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
09-16 11:36:04.162  5010  5010 E HealthService: notifyProfileServiceStateChanged
,09-16 11:36:04.172  5010  5010 D PanService: Received stop request...Stopping profile...
,09-16 11:36:04.172  5010  5010 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
09-16 11:36:04.172  5010  5010 E PanService: notifyProfileServiceStateChanged
09-16 11:36:04.172  3459  3459 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 11:36:04.172  3949  3949 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-16 11:36:04.172  3949  3949 D PanProfile: Bluetooth service disconnected
09-16 11:36:04.172  9789  9789 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:04.172  9789  9789 D RelationGraph: garbageCollect()
09-16 11:36:04.172  9356  9356 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 11:36:04.172  9356  9356 D PanProfile: Bluetooth service disconnected
09-16 11:36:04.172  5010  5010 D BluetoothMapService: Received stop request...Stopping profile...
09-16 11:36:04.172  9789  9789 W ResourcesManager: getTopLevelResources: /system/priv-app/intelligenceservice2/intelligenceservice2.apk / 1.0 running in com.samsung.android.intelligenceservice2 rsrc of package com.samsung.android.intelligenceservice2
09-16 11:36:04.172  3459  3979 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 11:36:04.172  9789  9789 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-16 11:36:04.172  5010  5010 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
09-16 11:36:04.172  5010  5010 E BluetoothMapService: notifyProfileServiceStateChanged
09-16 11:36:04.172  9789  9789 D ResourcesManager: For user 0 new overlays fetched Null
09-16 11:36:04.172  3949  3949 D BluetoothMap: Proxy object disconnected
09-16 11:36:04.172  3949  3949 D MapProfile: Bluetooth service disconnected
,09-16 11:36:04.172  5010  5010 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:04.172  5010  5010 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
09-16 11:36:04.182  5010  5010 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:04.182  5010  5010 V BluetoothAdapterState: isTurningOn()=false
,09-16 11:36:04.182  5010  5010 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:04.182  5010  5010 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:04.182  5010  5010 D SapService: Received stop request...Stopping profile...
09-16 11:36:04.182  5010  5010 V SapService: stop()
09-16 11:36:04.182  9789  9789 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:04.182  5010  5010 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
09-16 11:36:04.182  5010  5010 E SapService: notifyProfileServiceStateChanged
09-16 11:36:04.182  9356  9356 D BluetoothSap: Proxy object disconnected
09-16 11:36:04.182  9356  9356 D SapProfile: Bluetooth service disconnected
,09-16 11:36:04.182  3949  3949 D BluetoothSap: Proxy object disconnected
,09-16 11:36:04.182  3949  3949 D SapProfile: Bluetooth service disconnected
,09-16 11:36:04.182  5010  5010 D BleAudioService: Received stop request...Stopping profile...
,09-16 11:36:04.182  5010  5010 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
09-16 11:36:04.182  5010  5448 E BleAudioStateMachine_L: Exit Disconnected: -1
09-16 11:36:04.182  5010  5010 E BleAudioService: notifyProfileServiceStateChanged
09-16 11:36:04.182  5010  5449 E BleAudioStateMachine_R: Exit Disconnected: -1
,09-16 11:36:04.182  3949  3949 D BluetoothLeAudio: Proxy object disconnected
09-16 11:36:04.182  9789  9789 W System  : ClassLoader referenced unknown path: /system/priv-app/intelligenceservice2/lib/arm64
,09-16 11:36:04.182  3949  3949 D BleAudioProfile: Bluetooth service disconnected
,09-16 11:36:04.192  5010  5010 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 11:36:04.192  5010  5010 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isTurningOff()=true
,09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:04.192  5010  5010 D BluetoothAdapterService: HID Host service will be diabled
,09-16 11:36:04.192  5010  5010 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-16 11:36:04.192  5010  5010 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 11:36:04.192  5010  5010 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:04.192  9789  9789 D UserAnalysis.Provider: PlaceProvider onCreate()
09-16 11:36:04.192  5010  5010 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-16 11:36:04.192  5010  5010 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-16 11:36:04.192  5010  5010 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:04.192  5010  5010 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:04.192  5010  5010 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-16 11:36:04.192  5010  5010 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-16 11:36:04.192  5010  5010 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 11:36:04.192  5010  5010 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 11:36:04.192  5010  5010 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:04.202  5010  5010 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:04.202  5010  5010 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
09-16 11:36:04.202  5010  5010 V BluetoothAdapterState: isTurningOff()=true
,09-16 11:36:04.202  5010  5010 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:04.202  5010  5010 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:04.202  5010  5010 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:04.202  5010  5010 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:04.202  5010  5010 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
,09-16 11:36:04.202  5010  5010 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:04.202  5010  5010 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:04.202  5010  5010 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 11:36:04.202  5010  5010 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:04.202  5010  5137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
09-16 11:36:04.202  5010  5010 V BleAudioService: [unregisterCallStateListener]
,09-16 11:36:04.202  5010  5010 W BtBleAudio.JNI: WARNING: cleanupNative(L364): Cleaning up  Ble audio left callback object##
09-16 11:36:04.202  5010  5010 W BtBleAudio.JNI: WARNING: cleanupNative(L382): Cleaning up Ble audio Interface...##
09-16 11:36:04.202  5010  5010 W BtBleAudio.JNI: WARNING: cleanupNative(L370): Cleaning up  Ble audio right callback object##
09-16 11:36:04.202  5010  5137 D BluetoothAdapterProperties: Setting state to 15
09-16 11:36:04.202  5010  5137 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-16 11:36:04.202  5010  5010 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
,09-16 11:36:04.202  5010  5137 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-16 11:36:04.202  5010  5137 D BluetoothAdapterService: updateAdapterState state is 15
09-16 11:36:04.202  5010  5137 D BluetoothAdapterService: Autoconnection is available 
09-16 11:36:04.202  5010  5137 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
09-16 11:36:04.202  5010  5137 I BluetoothAdapterState: Entering BleOnState
,09-16 11:36:04.202  3949  4565 D BluetoothLeAudio: onBluetoothStateChange: up=false
09-16 11:36:04.202  3949  4565 D BluetoothLeAudio: Unbinding service...
09-16 11:36:04.202  3949  4385 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:04.202  3949  4385 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 11:36:04.202  3949  4385 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 11:36:04.202  4271  4281 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:04.202  4271  4281 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 11:36:04.212  4271  4281 D BluetoothAdapter: There are no active google scan apps, stop scan
09-16 11:36:04.212  4271  4281 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-16 11:36:04.212  4271  4281 D BluetoothLeScanner: Exiting stopAllScan
09-16 11:36:04.212  4305  4632 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-16 11:36:04.212  4305  4632 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 11:36:04.212  4305  4632 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 11:36:04.212  8934  8945 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:04.212  8934  8945 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 11:36:04.212  8934  8945 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 11:36:04.212  3949  3971 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 11:36:04.212  5041  5060 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-16 11:36:04.212  3949  3961 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-16 11:36:04.222  3459  3570 D BluetoothPan: onBluetoothStateChange on: false
,09-16 11:36:04.222  4299  4318 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:04.222  4299  4318 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 11:36:04.222  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:36:04.222  9789  9789 D UserAnalysis.Secu: Key for secure DB is newly created
,09-16 11:36:04.222  9789  9789 D UserAnalysis.SDBH: SecurePlaceDbHelper() 
09-16 11:36:04.222  9789  9789 D UserAnalysis: Create SecureDbHelper
,09-16 11:36:04.222  4299  4318 D BluetoothAdapter: There are no active google scan apps, stop scan
09-16 11:36:04.222  9356  9366 D BluetoothPan: onBluetoothStateChange on: false
,09-16 11:36:04.222  3949  4565 D BluetoothSap: onBluetoothStateChange: up=false
,09-16 11:36:04.222  3949  4385 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 11:36:04.222  5010  5416 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-16 11:36:04.222  3949  3971 D BluetoothMap: onBluetoothStateChange: up=false
09-16 11:36:04.222  3459  3570 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:04.222  3459  3570 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 11:36:04.222  3459  3570 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 11:36:04.222  9697  9707 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:04.222  9697  9707 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 11:36:04.222  9697  9707 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-16 11:36:04.222  9697  9707 D BluetoothLeAdvertiser: Exit stop advertising
09-16 11:36:04.232  9697  9707 D BluetoothAdapter: There are no active google scan apps, stop scan
09-16 11:36:04.232  9697  9707 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-16 11:36:04.232  9697  9707 D BluetoothLeScanner: Exiting stopAllScan
,09-16 11:36:04.232  3459  3570 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 11:36:04.232  3949  3961 D BluetoothPan: onBluetoothStateChange on: false
,09-16 11:36:04.232  9789  9789 D UserAnalysis.App: onCreate()
09-16 11:36:04.232  9789  9789 D InjectionManager: InjectionManager
,09-16 11:36:04.232  9789  9789 D InjectionManager: fillFeatureStoreMap com.samsung.android.intelligenceservice2
09-16 11:36:04.232  5041  5061 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:04.232  5041  5061 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 11:36:04.232  9789  9789 I InjectionManager: Constructor com.samsung.android.intelligenceservice2, Feature store :{}
09-16 11:36:04.232  9789  9789 I InjectionManager: featureStore :{}
09-16 11:36:04.232  5041  5061 D BluetoothAdapter: There are no active google scan apps, stop scan
09-16 11:36:04.232  9356  9367 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-16 11:36:04.232  9356  9367 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 11:36:04.232  9356  9367 D BluetoothAdapter: There are no active google scan apps, stop scan
09-16 11:36:04.232  9789  9789 D UserAnalysis.App: no applications having user consent for prediction
09-16 11:36:04.232  3459  4208 I ActivityManager: Killing 8841:com.samsung.android.app.appsedge/u0a1 (adj 15): DHA:empty #33
09-16 11:36:04.232  9356  9366 D BluetoothSap: onBluetoothStateChange: up=false
,09-16 11:36:04.242  3459  4208 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20effa1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f8986c 5010:com.android.bluetooth/1002}
,09-16 11:36:04.252  9789  9789 V PlaceDetection v1.0.29 : [PlaceDetection::stopService] Service stopped.
,09-16 11:36:04.252  4127  4127 I wpa_supplicant: Blacklist: Clear (all) 
09-16 11:36:04.252  4127  4127 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
09-16 11:36:04.252  5010  5137 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,09-16 11:36:04.252  9789  9789 V PlaceDetection v1.0.29 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-16 11:36:04.262  9803  9803 E Zygote  : v2
,09-16 11:36:04.262  9803  9803 I libpersona: KNOX_SDCARD checking this for 10125
09-16 11:36:04.262  9803  9803 I libpersona: KNOX_SDCARD not a persona
09-16 11:36:04.262  9803  9803 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 11:36:04.262  3459  4208 I ActivityManager: Start proc 9803:com.google.android.apps.maps/u0a125 for broadcast-3 com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-16 11:36:04.272  9803  9803 E Zygote  : accessInfo : 0
09-16 11:36:04.272  9803  9803 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.maps 
,09-16 11:36:04.272  5010  5137 D BluetoothAdapterProperties: Setting state to 16
09-16 11:36:04.272  5010  5137 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-16 11:36:04.272  5010  5137 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-16 11:36:04.272  5010  5137 D BluetoothAdapterService: updateAdapterState state is 16
,09-16 11:36:04.272  3459  3570 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
09-16 11:36:04.272  5010  5137 D BluetoothAdapterService: Autoconnection is available 
09-16 11:36:04.272  5010  5137 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
09-16 11:36:04.272  5010  5137 D BluetoothAdapterProperties: onBleDisable
,09-16 11:36:04.272  3459  3459 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:04.272  3459  4049 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
09-16 11:36:04.272  3459  3459 I InputMethodManagerService: [BT Setting State] State =10
09-16 11:36:04.272  3459  3459 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-16 11:36:04.282  3459  4053 D SecContentProvider: insert(), uri = 2
,09-16 11:36:04.282  3949  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:04.282  3949  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-16 11:36:04.282  4346  4346 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:04.282  5010  5137 I BluetoothAdapterState: Entering PendingCommandState
09-16 11:36:04.282  5010  5138 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-16 11:36:04.282  5010  5138 E bt_btif : btif_vhci_sock_cleanup
09-16 11:36:04.282  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{8166e68: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:04.282  5010  5359 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-16 11:36:04.292  3155  3630 D Netd    : Iface wlan0 link up
,09-16 11:36:04.292  3155  3630 D Netd    : Iface wlan0 link up
,09-16 11:36:04.292  5051  5067 D PdnController: Interface Changed wlan0 link up
,09-16 11:36:04.292  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 11:36:04.292  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
,09-16 11:36:04.292  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-16 11:36:04.292  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:04.292  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
09-16 11:36:04.292  5051  5344 D PdnController: Interface Changed wlan0 link up
09-16 11:36:04.292  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 11:36:04.292  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
,09-16 11:36:04.302  7545  7545 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-16 11:36:04.302  3155  3630 D Netd    : Iface p2p0 link down
,09-16 11:36:04.302  5051  5066 D PdnController: Interface Changed p2p0 link down
,09-16 11:36:04.302  9356  9356 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:04.302  9356  9356 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-16 11:36:04.312  3459  3546 D Tethering: interfaceLinkStateChanged p2p0, false
09-16 11:36:04.312  3459  3546 D Tethering: interfaceStatusChanged p2p0, false
,09-16 11:36:04.312  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{3a0e281: PendingIntentRecord{149ef26 com.samsung.android.intelligenceservice2 broadcastIntent}}
,09-16 11:36:04.312  3459  4424 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.appsedge, Auto Run ON
,09-16 11:36:04.322  9803  9803 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:04.322  9803  9803 D ActivityThread: Added TimaKeyStore provider
09-16 11:36:04.322  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:04.322  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:04.322  5010  5141 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-16 11:36:04.322  5010  5141 D BluetoothAdapterProperties: Scan Mode:20
,09-16 11:36:04.332  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:04.332  3949  4176 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
09-16 11:36:04.332  3459  4053 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-16 11:36:04.332  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:04.332  3459  3483 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20effa1 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc9767 9803:com.google.android.apps.maps/u0a125}
,09-16 11:36:04.342  5010  5137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e400b
,09-16 11:36:04.342  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{7180914: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:04.352  9803  9803 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:04.352  9803  9803 D RelationGraph: garbageCollect()
,09-16 11:36:04.352  9803  9803 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.google.android.apps.maps rsrc of package com.google.android.apps.maps
,09-16 11:36:04.362  3459  4416 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 11:36:04.362  9803  9803 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:04.362  9803  9803 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:04.362  9803  9803 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:04.372  9803  9803 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-16 11:36:04.402  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:04.482  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{17825bd: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:04.482  5010  5141 I bt_hci  : shut_down
,09-16 11:36:04.482  5010  5228 D bt_hwcfg: hw_epilog_process
09-16 11:36:04.482  5010  5228 I bt_vendor: low_power_mode_cb
,09-16 11:36:04.492  5010  5228 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-16 11:36:04.492  5010  5228 I bt_vendor: epilog_cb
,09-16 11:36:04.492  5010  5228 I bt_hci  : epilog_finished_callback
09-16 11:36:04.492  5010  5141 I bt_hci_h4: hal_close
09-16 11:36:04.492  5010  5141 I bt_userial_vendor: device fd = 60 close
09-16 11:36:04.492  5010  5141 I bt_upio : upio_set_bluetooth_power(on: 0)
,09-16 11:36:04.492  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{8d5d7b2: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:04.502  5010  5138 D bt_stack_manager: event_shut_down_stack finished.
,09-16 11:36:04.502  5010  5141 E BluetoothAdapterState: stateChangeCallback : 0
09-16 11:36:04.502  5010  5137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
,09-16 11:36:04.512  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{714303: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:04.512  5010  5010 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 11:36:04.512  5010  5137 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-16 11:36:04.522  5010  5010 D BtGatt.GattService: Received stop request...Stopping profile...
09-16 11:36:04.522  5010  5010 D BtGatt.GattService: stop()
09-16 11:36:04.522  5010  5010 D BtGatt.GattService: [GSIM LOG]: saveLogPref
09-16 11:36:04.522  5010  5010 D BtGatt.GattService: [GSIM LOG]: saveLogPref END
09-16 11:36:04.522  5010  5010 D BtGatt.GattService: cleanup binder
09-16 11:36:04.522  5010  5010 D BtGatt.AdvertiseManager: advertise clients cleared
09-16 11:36:04.522  5010  5010 D BtGatt.ScanManager: cleanup
,09-16 11:36:04.522  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{9f6a280: PendingIntentRecord{1001aff com.android.bluetooth broadcastIntent}}
,09-16 11:36:04.522  5010  5010 D BtGatt.ScanManager: cleanup handler
,09-16 11:36:04.522  5010  5010 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
09-16 11:36:04.522  5010  5010 E BtGatt.GattService: notifyProfileServiceStateChanged
09-16 11:36:04.522  5010  5010 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:04.522  5010  5010 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
09-16 11:36:04.522  5010  5010 V BluetoothAdapterState: isTurningOff()=false
09-16 11:36:04.522  5010  5010 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:04.522  5010  5010 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 11:36:04.522  5010  5010 V BluetoothAdapterState: isBleTurningOff()=true
09-16 11:36:04.522  5010  5137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
,09-16 11:36:04.532  5010  5137 D BluetoothAdapterProperties: Setting state to 10
,09-16 11:36:04.532  5010  5137 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-16 11:36:04.532  5010  5137 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-16 11:36:04.532  5010  5137 D BluetoothAdapterService: updateAdapterState state is 10
09-16 11:36:04.532  5010  5137 D BluetoothAdapterService: Autoconnection is available 
09-16 11:36:04.532  5010  5137 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
,09-16 11:36:04.532  5010  5137 D BluetoothAdapterService: BT on, init HID DEV count : 0
09-16 11:36:04.532  5010  5137 I BluetoothAdapterState: Entering OffState
09-16 11:36:04.532  3459  3570 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-16 11:36:04.542  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{28660b9: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:04.542  5010  5010 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-16 11:36:04.542  5010  5010 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-16 11:36:04.542  5010  5010 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-16 11:36:04.552  5010  5138 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-16 11:36:04.552  5010  5010 I art     : System.exit called, status: 0
09-16 11:36:04.552  5010  5010 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-16 11:36:04.552  9803  9803 D InjectionManager: InjectionManager
09-16 11:36:04.552  9803  9803 D InjectionManager: fillFeatureStoreMap com.google.android.apps.maps
,09-16 11:36:04.552  9803  9803 I InjectionManager: Constructor com.google.android.apps.maps, Feature store :{}
09-16 11:36:04.552  9803  9803 I InjectionManager: featureStore :{}
,09-16 11:36:04.582  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:04.592  3459  4208 I ActivityManager: Process com.android.bluetooth (pid 5010)(adj 0) has died(67,1772)
,09-16 11:36:04.592  3459  4208 D ActivityManager: isAutoRunBlockedApp:: com.android.bluetooth, Auto Run ON
,09-16 11:36:04.602  9803  9818 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/testdata
,09-16 11:36:04.602  9803  9818 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.maps/app_/testdata
,09-16 11:36:04.602  9803  9818 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/cache
,09-16 11:36:04.652  3459  4412 I ActivityManager: Killing 9268:com.samsung.android.app.galaxylabs/u0a17 (adj 15): DHA:empty #33
,09-16 11:36:04.672  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cc5bcfe u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{58b9db4 9489:com.enhance.gameservice/u0a111}
,09-16 11:36:04.672  3459  4536 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.galaxylabs, Auto Run ON
,09-16 11:36:04.692  9803  9821 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-16 11:36:04.712  9831  9831 E Zygote  : v2
09-16 11:36:04.712  9831  9831 I libpersona: KNOX_SDCARD checking this for 1000
09-16 11:36:04.712  9831  9831 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:04.712  9831  9831 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 11:36:04.712  3459  3543 I ActivityManager: Start proc 9831:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,09-16 11:36:04.712  9831  9831 E Zygote  : accessInfo : 0
,09-16 11:36:04.722  9843  9843 E Zygote  : v2
09-16 11:36:04.722  9843  9843 I libpersona: KNOX_SDCARD checking this for 10117
09-16 11:36:04.722  9843  9843 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:04.722  9843  9843 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:04.732  9843  9843 E Zygote  : accessInfo : 0
09-16 11:36:04.732  9843  9843 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
09-16 11:36:04.732  3459  3543 I ActivityManager: Start proc 9843:com.google.android.talk/u0a117 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,09-16 11:36:04.732  3459  3856 D NetworkPolicy: isUidForegroundLocked: 10117, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,09-16 11:36:04.732  9831  9831 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:04.732  9831  9831 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:04.752  3459  4053 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cc5bcfe u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f64198 9831:com.sec.android.diagmonagent/1000}
,09-16 11:36:04.762  3459  3856 D NetworkPolicy: isUidForegroundLocked: 10117, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-16 11:36:04.762  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:04.762  4165  4177 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.apps.maps,id=10436,extra=Bundle[mParcelledData.dataSize=84]
09-16 11:36:04.762  4165  4165 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.apps.maps}]
09-16 11:36:04.762  4165  4165 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 11:36:04.762  4165  4165 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 11:36:04.762  4165  4165 I PeopleDataManager: removeNotification
09-16 11:36:04.762  4165  4165 I NotificationParser: getNotiType:com.google.android.apps.maps,null
09-16 11:36:04.762  4165  4165 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.apps.maps,isEdgeNotification=false,key=null,removeAll=false
09-16 11:36:04.762  4165  4165 D PeopleDataManager: removeNotiInfo =null
,09-16 11:36:04.762  9843  9843 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:04.762  9843  9843 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:04.772  9831  9831 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true,
09-16 11:36:04.772  9831  9831 D RelationGraph: garbageCollect()
,09-16 11:36:04.772  9831  9831 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package com.sec.android.diagmonagent
,09-16 11:36:04.772  3459  3979 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 11:36:04.772  9831  9831 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:04.772  9831  9831 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:04.782  9831  9831 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:04.782  3459  4424 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fd9df44 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{462f82d 9843:com.google.android.talk/u0a117}
,09-16 11:36:04.792  9831  9831 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,09-16 11:36:04.792  9843  9843 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:04.792  9843  9843 D RelationGraph: garbageCollect()
,09-16 11:36:04.792  9843  9843 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,09-16 11:36:04.792  3459  3974 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:04.792  9843  9843 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:04.802  9843  9843 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:04.802  9843  9843 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:04.802  9831  9831 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-16 11:36:04.812  3155  3630 D Netd    : Iface wlan0 link down
,09-16 11:36:04.812  5051  5344 D PdnController: Interface Changed wlan0 link down
09-16 11:36:04.812  5051  5344 D PdnController: Removed Interface [wlan0] For Network [1]
09-16 11:36:04.812  3459  3546 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:04.812  5051  5344 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
09-16 11:36:04.812  5051  5344 D PdnController: isSuspended [false] networktype [1]
,09-16 11:36:04.812  3459  3546 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:04.812  9843  9843 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,09-16 11:36:04.812  5051  5344 D PdnController: isPdnUp  [false] networktype [1]
,09-16 11:36:04.812  5051  5344 D PdnController: Ignore Notifying Same Result to LocalIP Registrants!
09-16 11:36:04.812  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, false
09-16 11:36:04.812  3459  3546 D Tethering: interfaceStatusChanged wlan0, false
,09-16 11:36:04.842  9843  9843 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,09-16 11:36:04.872  4127  4127 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 11:36:04.902  9831  9831 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-16 11:36:04.912  9831  9831 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
,09-16 11:36:04.912  9831  9831 D InjectionManager: InjectionManager
09-16 11:36:04.912  9831  9831 D InjectionManager: fillFeatureStoreMap com.sec.android.diagmonagent
09-16 11:36:04.912  9831  9831 I InjectionManager: Constructor com.sec.android.diagmonagent, Feature store :{}
09-16 11:36:04.912  9831  9831 I InjectionManager: featureStore :{}
09-16 11:36:04.912  9831  9831 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-16 11:36:04.912  9831  9831 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-16 11:36:04.912  9831  9831 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-16 11:36:04.912  9831  9831 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-16 11:36:04.942  9859  9859 E Zygote  : v2
09-16 11:36:04.942  9859  9859 I libpersona: KNOX_SDCARD checking this for 1000
09-16 11:36:04.942  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:36:04.942  9859  9859 I libpersona: KNOX_SDCARD not a persona
09-16 11:36:04.942  9859  9859 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:04.942  9859  9859 E Zygote  : accessInfo : 0
,09-16 11:36:04.942  3459  4856 I ActivityManager: Start proc 9859:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,09-16 11:36:04.942  3459  4856 I ActivityManager: Killing 9285:com.google.android.partnersetup/u0a25 (adj 15): DHA:empty #33
,09-16 11:36:04.972  9859  9859 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:04.972  9859  9859 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:04.972  3459  3483 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,09-16 11:36:04.992  3459  4208 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cc5bcfe u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{123ea29 9859:com.sec.knox.switcher/1000}
,09-16 11:36:05.002  9859  9859 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:05.012  9859  9859 D RelationGraph: garbageCollect()
,09-16 11:36:05.012  9859  9859 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package com.sec.knox.switcher
,09-16 11:36:05.012  9843  9843 I Babel_telephony: TeleModule.onApplicationCreate
,09-16 11:36:05.012  3459  4049 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 11:36:05.012  9859  9859 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:05.012  9859  9859 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:05.022  9859  9859 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:05.022  9859  9859 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,09-16 11:36:05.022  9859  9859 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
,09-16 11:36:05.022  9859  9859 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,09-16 11:36:05.032  9859  9859 D InjectionManager: InjectionManager
09-16 11:36:05.032  9859  9859 D InjectionManager: fillFeatureStoreMap com.sec.knox.switcher
,09-16 11:36:05.032  9859  9859 I InjectionManager: Constructor com.sec.knox.switcher, Feature store :{}
09-16 11:36:05.032  9859  9859 I InjectionManager: featureStore :{}
09-16 11:36:05.032  9859  9859 I usagelog: received in receiver
09-16 11:36:05.032  9859  9859 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,09-16 11:36:05.032  9859  9859 I KnoxUsageLogPro: premStatus:2
,09-16 11:36:05.032  9859  9859 I KnoxUsageLogPro: isEulaShown : false
09-16 11:36:05.032  9859  9859 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-16 11:36:05.032  9843  9877 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-16 11:36:05.032  9843  9877 I Babel_SMS: MmsConfig.loadMmsSettings
,09-16 11:36:05.042  9843  9877 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,09-16 11:36:05.042  9843  9877 I Babel_SMS: MmsConfig.loadFromDatabase
,09-16 11:36:05.052  3459  4049 I ActivityManager: Start proc 9878:com.microsoft.office.onenote.connectionReceiverProcess/u0a12 for broadcast-5 com.microsoft.office.onenote/com.microsoft.bing.datamining.quasar.api.ConnectionChangeReceiver
,09-16 11:36:05.052  9878  9878 E Zygote  : v2
09-16 11:36:05.052  9878  9878 I libpersona: KNOX_SDCARD checking this for 10012
09-16 11:36:05.052  9878  9878 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 11:36:05.052  9878  9878 I libpersona: KNOX_SDCARD not a persona
09-16 11:36:05.052  9878  9878 E Zygote  : accessInfo : 0
,09-16 11:36:05.052  9878  9878 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.microsoft.office.onenote.connectionReceiverProcess 
,09-16 11:36:05.072  9843  9877 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-16 11:36:05.072  9843  9877 I Babel_SMS: MmsConfig.loadFromResources
,09-16 11:36:05.072  9843  9877 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-16 11:36:05.072  9843  9877 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,09-16 11:36:05.072  3459  3858 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-16 11:36:05.072  3459  3459 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,09-16 11:36:05.082  4165  7324 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
09-16 11:36:05.082  4165  4165 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 11:36:05.082  4165  4165 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 11:36:05.082  4165  4165 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 11:36:05.082  4165  4165 I PeopleDataManager: removeNotification
09-16 11:36:05.082  4165  4165 I NotificationParser: getNotiType:android,null
09-16 11:36:05.082  4165  4165 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 11:36:05.082  4165  4165 D PeopleDataManager: removeNotiInfo =null
,09-16 11:36:05.082  3459  3459 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
09-16 11:36:05.082  3459  3459 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,09-16 11:36:05.082  4165  4180 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041473,extra=Bundle[mParcelledData.dataSize=84]
09-16 11:36:05.082  4165  4165 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041473, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 11:36:05.082  4165  4165 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 11:36:05.082  4165  4165 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 11:36:05.082  4165  4165 I PeopleDataManager: removeNotification
09-16 11:36:05.082  4165  4165 I NotificationParser: getNotiType:android,null
09-16 11:36:05.082  4165  4165 D PeopleDataManager: removeNotiInfo: id =17041473,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 11:36:05.082  4165  4165 D PeopleDataManager: removeNotiInfo =null
,09-16 11:36:05.082  3459  3459 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-16 11:36:05.082  3459  3459 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-16 11:36:05.082  3459  3862 D HS20StateMachine: WIFI_STATE_DISABLED
09-16 11:36:05.082  3459  3865 I WifiHs20Service: Message received 5011
09-16 11:36:05.082  3459  3862 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
09-16 11:36:05.082  3459  3862 D HS20StateMachine: enter : DisablingState
,09-16 11:36:05.082  3459  3864 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
09-16 11:36:05.082  3459  3862 D HS20StateMachine: enter : DisabledState
,09-16 11:36:05.082  9878  9878 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-16 11:36:05.082  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:05.082  9878  9878 D ActivityThread: Added TimaKeyStore provider
09-16 11:36:05.092  3459  3459 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,09-16 11:36:05.092  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-16 11:36:05.092  3949  3949 I HotspotTile: Provider is not defined returning false
,09-16 11:36:05.092  3459  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-16 11:36:05.092  3949  3949 D HotspotTile: onReceive : 1, 0
,09-16 11:36:05.092  4305  4632 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-16 11:36:05.092  4305  4632 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-16 11:36:05.102  3459  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-16 11:36:05.102  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:05.102  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:36:05.102  4271  4923 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 11:36:05.102  3459  3484 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cc5bcfe u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{25961ae 9878:com.microsoft.office.onenote.connectionReceiverProcess/u0a12}
,09-16 11:36:05.112  9878  9878 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:05.112  9878  9878 D RelationGraph: garbageCollect()
,09-16 11:36:05.112  9878  9878 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.microsoft.office.onenote rsrc of package com.microsoft.office.onenote
,09-16 11:36:05.122  3459  4856 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 11:36:05.122  9878  9878 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-16 11:36:05.122  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:05.122  9843  9843 I Babel_Crash: Startup - clean
,09-16 11:36:05.122  9878  9878 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:05.122  9878  9878 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:05.122  3459  4380 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10117
09-16 11:36:05.122  3459  3537 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
09-16 11:36:05.122  3459  3537 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
09-16 11:36:05.122  3459  3537 E libgps  : IPC Communication Error, ../../../../tmp/14804949_263294/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
09-16 11:36:05.122  3459  3537 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,09-16 11:36:05.132  3459  3483 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10117
,09-16 11:36:05.132  9878  9878 W System  : ClassLoader referenced unknown path: /system/app/OneNote/lib/arm
,09-16 11:36:05.132  3459  3974 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10117
,09-16 11:36:05.142  9878  9878 D InjectionManager: InjectionManager
,09-16 11:36:05.142  9878  9878 D InjectionManager: fillFeatureStoreMap com.microsoft.office.onenote
09-16 11:36:05.142  9878  9878 I InjectionManager: Constructor com.microsoft.office.onenote, Feature store :{}
09-16 11:36:05.142  9878  9878 I InjectionManager: featureStore :{}
09-16 11:36:05.142  3459  4424 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10117
,09-16 11:36:05.142  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:05.142  9878  9878 I Process : Sending signal. PID: 9878 SIG: 9
,09-16 11:36:05.142  3459  4864 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10117
,09-16 11:36:05.162  3459  4834 I ActivityManager: Process com.microsoft.office.onenote.connectionReceiverProcess (pid 9878)(adj 0) has died(50,1773)
,09-16 11:36:05.162  3459  4834 D ActivityManager: isAutoRunBlockedApp:: com.microsoft.office.onenote, Auto Run ON
,09-16 11:36:05.182  9894  9894 E Zygote  : v2
09-16 11:36:05.182  9894  9894 I libpersona: KNOX_SDCARD checking this for 10142
09-16 11:36:05.182  9894  9894 I libpersona: KNOX_SDCARD not a persona
09-16 11:36:05.182  9894  9894 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:05.182  9894  9894 E Zygote  : accessInfo : 0
,09-16 11:36:05.182  9894  9894 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,09-16 11:36:05.182  3459  3543 I ActivityManager: Start proc 9894:com.samsung.android.sm.policy/u0a142 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
09-16 11:36:05.192  3459  3856 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,09-16 11:36:05.192  9843  9843 D InjectionManager: InjectionManager
09-16 11:36:05.192  9843  9843 D InjectionManager: fillFeatureStoreMap com.google.android.talk
,09-16 11:36:05.192  9843  9843 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
09-16 11:36:05.192  9843  9843 I InjectionManager: featureStore :{}
,09-16 11:36:05.192  3459  3484 I ActivityManager: Killing 9320:com.samsung.svoice.sync/u0a43 (adj 15): DHA:empty #33
,09-16 11:36:05.202  9894  9894 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:05.202  9894  9894 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:05.212  3459  4380 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ddeaba 9697:com.test.thalitest/u0a177}
,09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.212  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:05.222  3459  4386 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cc5bcfe u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ddcd6b 9894:com.samsung.android.sm.policy/u0a142}
,09-16 11:36:05.232  3459  4208 D ActivityManager: isAutoRunBlockedApp:: com.samsung.svoice.sync, Auto Run ON
,09-16 11:36:05.232  9894  9894 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:05.232  9894  9894 D RelationGraph: garbageCollect()
,09-16 11:36:05.232  9894  9894 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package com.samsung.android.sm.policy
,09-16 11:36:05.232  3459  3974 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:05.232  9894  9894 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:05.242  9894  9894 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:05.242  9894  9894 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:05.242  3459  4856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cfc71f7 3459:system/1000}
,09-16 11:36:05.242  9894  9894 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm64
,09-16 11:36:05.252  3459  3856 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,09-16 11:36:05.252  3459  3459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a118d93 4569:com.google.android.gms/u0a21}
,09-16 11:36:05.262  9894  9894 D InjectionManager: InjectionManager
,09-16 11:36:05.262  9894  9894 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.policy
09-16 11:36:05.262  9894  9894 I InjectionManager: Constructor com.samsung.android.sm.policy, Feature store :{}
09-16 11:36:05.262  9894  9894 I InjectionManager: featureStore :{}
,09-16 11:36:05.272  3459  4536 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a118d93 4569:com.google.android.gms/u0a21}
,09-16 11:36:05.282  4569  4569 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-16 11:36:05.282  4569  5574 I iu.UploadsManager: num queued entries: 0
09-16 11:36:05.282  3459  3858 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-16 11:36:05.282  4569  5574 I iu.UploadsManager: num updated entries: 0
09-16 11:36:05.282  3459  3858 E WifiStateMachine: Error! unhandled message{ when=-4m5s893ms what=131156 target=com.android.internal.util.StateMachine$SmHandler }
09-16 11:36:05.282  4569  5574 I iu.SyncManager: NEXT; no task
,09-16 11:36:05.282  9843  9843 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,09-16 11:36:05.292  9843  9843 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,09-16 11:36:05.292  9910  9910 E Zygote  : v2
09-16 11:36:05.292  9910  9910 I libpersona: KNOX_SDCARD checking this for 5005
09-16 11:36:05.292  9910  9910 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:05.292  9910  9910 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:05.302  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:05.302  9910  9910 E Zygote  : accessInfo : 0
,09-16 11:36:05.302  9910  9910 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
09-16 11:36:05.302  3459  4536 I ActivityManager: Start proc 9910:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,09-16 11:36:05.302  3459  4536 I ActivityManager: Killing 9376:com.samsung.android.provider.shootingmodeprovider/u0a60 (adj 15): DHA:empty #33
,09-16 11:36:05.302  9843  9843 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:05.302  9843  9843 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:05.312  3459  4536 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a118d93 4569:com.google.android.gms/u0a21}
,09-16 11:36:05.322  9843  9843 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,09-16 11:36:05.332  3459  4208 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5287a2d 4271:com.google.android.gms.persistent/u0a21}
,09-16 11:36:05.332  9910  9910 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:05.332  9910  9910 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:05.342  3459  4416 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,09-16 11:36:05.352  3459  4208 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{89d547 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{595a174 9910:com.samsung.android.app.FileShareClient/5005}
,09-16 11:36:05.362  9910  9910 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:05.362  9910  9910 D RelationGraph: garbageCollect()
,09-16 11:36:05.362  9910  9910 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,09-16 11:36:05.362  3459  4386 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:05.362  9910  9910 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:05.372  9910  9910 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:05.372  9910  9910 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:05.382  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b9f469d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f64198 9831:com.sec.android.diagmonagent/1000}
09-16 11:36:05.382  9910  9910 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,09-16 11:36:05.382  9831  9831 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
09-16 11:36:05.382  9831  9831 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-16 11:36:05.382  9831  9831 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-16 11:36:05.382  9910  9910 D InjectionManager: InjectionManager
09-16 11:36:05.382  9910  9910 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
,09-16 11:36:05.382  9910  9910 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{}
09-16 11:36:05.382  9910  9910 I InjectionManager: featureStore :{}
,09-16 11:36:05.382  9910  9910 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-16 11:36:05.382  9910  9910 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-16 11:36:05.392  3459  4380 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b9f469d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{58b9db4 9489:com.enhance.gameservice/u0a111}
,09-16 11:36:05.402  3459  3974 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b9f469d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{123ea29 9859:com.sec.knox.switcher/1000}
09-16 11:36:05.402  9859  9859 I usagelog: received in receiver
,09-16 11:36:05.402  9859  9859 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-16 11:36:05.402  9859  9859 I KnoxUsageLogPro: premStatus:2
,09-16 11:36:05.402  9859  9859 I KnoxUsageLogPro: isEulaShown : false
09-16 11:36:05.402  9859  9859 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-16 11:36:05.412  9843  9843 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-16 11:36:05.412  9910  9910 D FileShare-Client: Outbound.stopDelayTimer - 
,09-16 11:36:05.422  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b9f469d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ddcd6b 9894:com.samsung.android.sm.policy/u0a142}
,09-16 11:36:05.432  9843  9843 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-16 11:36:05.432  9922  9922 E Zygote  : v2
09-16 11:36:05.432  9922  9922 I libpersona: KNOX_SDCARD checking this for 5005
09-16 11:36:05.432  9922  9922 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:05.432  9922  9922 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:05.442  9922  9922 E Zygote  : accessInfo : 0
09-16 11:36:05.442  9922  9922 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
,09-16 11:36:05.442  3459  4412 I ActivityManager: Start proc 9922:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
,09-16 11:36:05.452  3459  4412 I ActivityManager: Killing 9194:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #33
,09-16 11:36:05.462  3459  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{daeaf99 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ddeaba 9697:com.test.thalitest/u0a177}
,09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.462  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:05.462  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{637925e: PendingIntentRecord{6f6263f com.google.android.talk startService}}
,09-16 11:36:05.472  9922  9922 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-16 11:36:05.472  9922  9922 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:05.482  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a2fab0c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf426af 9356:com.android.settings/1000}
,09-16 11:36:05.482  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:05.482  9356  9356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 11:36:05.482  3459  3974 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,09-16 11:36:05.502  3459  4834 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{89d547 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b1ac55 9922:com.samsung.android.app.FileShareServer/5005}
,09-16 11:36:05.502  9843  9843 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,09-16 11:36:05.512  9922  9922 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:05.512  9922  9922 D RelationGraph: garbageCollect()
,09-16 11:36:05.512  9922  9922 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareServer/AllshareFileShareServer.apk / 1.0 running in com.samsung.android.app.FileShareServer rsrc of package com.samsung.android.app.FileShareServer
09-16 11:36:05.512  3459  3484 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 11:36:05.512  9922  9922 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-16 11:36:05.512  9922  9922 D ResourcesManager: For user 0 new overlays fetched Null
09-16 11:36:05.512  3459  4053 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a2fab0c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
,09-16 11:36:05.522  9922  9922 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:05.522  9356  9356 D DockEventReceiver: finishStartingService: stopping service
,09-16 11:36:05.522  9922  9922 D InjectionManager: InjectionManager
09-16 11:36:05.522  9922  9922 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareServer
09-16 11:36:05.522  9922  9922 I InjectionManager: Constructor com.samsung.android.app.FileShareServer, Feature store :{}
09-16 11:36:05.522  9922  9922 I InjectionManager: featureStore :{}
,09-16 11:36:05.532  3459  4053 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a2fab0c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5287a2d 4271:com.google.android.gms.persistent/u0a21}
,09-16 11:36:05.532  4271  4271 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,09-16 11:36:05.532  9922  9922 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-16 11:36:05.532  9922  9922 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-16 11:36:05.532  9922  9922 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-16 11:36:05.552  3459  3979 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a2fab0c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1de32d 8934:com.sec.android.app.shealth:remote/u0a39}
,09-16 11:36:05.572  9937  9937 E Zygote  : v2
09-16 11:36:05.572  9937  9937 I libpersona: KNOX_SDCARD checking this for 1000
09-16 11:36:05.572  9937  9937 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:05.572  9937  9937 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:05.572  3459  3979 I ActivityManager: Start proc 9937:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
09-16 11:36:05.572  9937  9937 E Zygote  : accessInfo : 0
,09-16 11:36:05.592  3459  3979 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a2fab0c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf426af 9356:com.android.settings/1000}
,09-16 11:36:05.592  9356  9356 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:05.592  9356  9356 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,09-16 11:36:05.602  3459  3979 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a2fab0c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{957b75a 9789:com.samsung.android.intelligenceservice2/5010}
,09-16 11:36:05.612  9937  9937 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-16 11:36:05.612  9937  9937 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:05.632  9949  9949 E Zygote  : v2
09-16 11:36:05.632  9949  9949 I libpersona: KNOX_SDCARD checking this for 1002
,09-16 11:36:05.632  9949  9949 I libpersona: KNOX_SDCARD not a persona
09-16 11:36:05.632  9949  9949 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 11:36:05.632  3459  3979 I ActivityManager: Start proc 9949:com.android.bluetooth/1002 for broadcast-3 com.android.bluetooth/.opp.BluetoothOppReceiver
,09-16 11:36:05.632  3459  3979 I ActivityManager: Killing 8948:com.samsung.android.app.taskedge/u0a67 (adj 15): DHA:empty #33
,09-16 11:36:05.642  9949  9949 E Zygote  : accessInfo : 0
,09-16 11:36:05.662  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:05.662  3459  4416 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{130e75b 9937:com.policydm/1000}
,09-16 11:36:05.672  3459  4053 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.taskedge, Auto Run ON
,09-16 11:36:05.672  9949  9949 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:05.672  9949  9949 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:05.682  9937  9937 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:05.682  9937  9937 D RelationGraph: garbageCollect()
,09-16 11:36:05.682  9937  9937 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package com.policydm
,09-16 11:36:05.682  3459  3974 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:05.692  9937  9937 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:05.692  9937  9937 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:05.692  3459  4208 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a2fab0c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b26bf8 9949:com.android.bluetooth/1002}
,09-16 11:36:05.702  9937  9937 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:05.702  9949  9949 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:05.702  9949  9949 D RelationGraph: garbageCollect()
,09-16 11:36:05.702  9949  9949 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in com.android.bluetooth rsrc of package com.android.bluetooth
,09-16 11:36:05.702  3459  3979 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:05.702  9949  9949 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:05.712  9937  9937 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,09-16 11:36:05.712  9949  9949 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:05.712  9949  9949 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:05.732  9937  9937 I FOTA    : [lIlIIlIIlIlllIIIIlll(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
,09-16 11:36:05.732  9937  9937 I FOTA    : [lIlIIlIIlIlllIIIIlll(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,09-16 11:36:05.742  9949  9949 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-16 11:36:05.752  9937  9937 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,09-16 11:36:05.752  9949  9949 D BtSettings.ProfileConfig: Adding GattService
09-16 11:36:05.752  9949  9949 D BtSettings.ProfileConfig: Adding HeadsetService
,09-16 11:36:05.752  9949  9949 D BtSettings.ProfileConfig: Adding A2dpService
09-16 11:36:05.752  9949  9949 D BtSettings.ProfileConfig: Adding HidService
09-16 11:36:05.752  9949  9949 D BtSettings.ProfileConfig: Adding HealthService
09-16 11:36:05.752  9949  9949 D BtSettings.ProfileConfig: Adding PanService
09-16 11:36:05.752  9949  9949 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-16 11:36:05.752  9949  9949 D BtSettings.ProfileConfig: Adding SapService
09-16 11:36:05.752  9949  9949 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-16 11:36:05.752  9949  9949 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-16 11:36:05.752  9949  9949 D BtSettings.ProfileConfig: Adding BleAudioService
09-16 11:36:05.752  9949  9949 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-16 11:36:05.762  3459  4834 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-16 11:36:05.762  3459  4834 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 11:36:05.762  3459  4834 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 11:36:05.762  3459  4834 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 11:36:05.762  3459  4834 D SettingsProvider: selectionArgs: false
09-16 11:36:05.762  3459  4834 D SettingsProvider: selectionArgs: 1002
,09-16 11:36:05.762  3459  4834 D SettingsProvider: ret = -1
,09-16 11:36:05.762  3459  4416 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-16 11:36:05.762  3459  4416 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 11:36:05.762  3459  4416 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-16 11:36:05.762  9937  9937 I DBG_POLICYDM: [com.policydm.db.XDB(1548/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
09-16 11:36:05.762  3459  4416 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 11:36:05.762  3459  4416 D SettingsProvider: selectionArgs: false
09-16 11:36:05.762  3459  4416 D SettingsProvider: selectionArgs: 1002
09-16 11:36:05.762  3459  4416 D SettingsProvider: ret = -1
,09-16 11:36:05.762  3459  4386 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-16 11:36:05.762  3459  4386 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 11:36:05.762  3459  4386 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 11:36:05.762  3459  4386 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 11:36:05.762  3459  4386 D SettingsProvider: selectionArgs: false
09-16 11:36:05.762  3459  4386 D SettingsProvider: selectionArgs: 1002
,09-16 11:36:05.762  3459  4386 D SettingsProvider: ret = -1
09-16 11:36:05.772  3459  4208 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hid.HidService
09-16 11:36:05.772  3459  4208 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 11:36:05.772  3459  4208 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-16 11:36:05.772  3459  4208 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 11:36:05.772  3459  4208 D SettingsProvider: selectionArgs: false
09-16 11:36:05.772  3459  4208 D SettingsProvider: selectionArgs: 1002
09-16 11:36:05.772  3459  4208 D SettingsProvider: ret = -1
,09-16 11:36:05.772  3459  4424 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-16 11:36:05.772  3459  4424 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,09-16 11:36:05.772  3459  4424 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 11:36:05.772  3459  4424 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 11:36:05.772  3459  4424 D SettingsProvider: selectionArgs: false
09-16 11:36:05.772  3459  4424 D SettingsProvider: selectionArgs: 1002
09-16 11:36:05.772  3459  4424 D SettingsProvider: ret = -1
,09-16 11:36:05.772  3459  3484 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.pan.PanService
09-16 11:36:05.772  3459  3484 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 11:36:05.772  3459  3484 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 11:36:05.772  3459  3484 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-16 11:36:05.772  3459  3484 D SettingsProvider: selectionArgs: false
09-16 11:36:05.772  3459  3484 D SettingsProvider: selectionArgs: 1002
09-16 11:36:05.772  3459  3484 D SettingsProvider: ret = -1
,09-16 11:36:05.772  3459  4864 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-16 11:36:05.772  3459  4864 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 11:36:05.772  3459  4864 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 11:36:05.772  9937  9937 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(142/llIIIIlllllIIllIIllI)] try read dbString
,09-16 11:36:05.772  3459  4864 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 11:36:05.772  3459  4864 D SettingsProvider: selectionArgs: false
09-16 11:36:05.772  3459  4864 D SettingsProvider: selectionArgs: 1002
09-16 11:36:05.772  3459  4864 D SettingsProvider: ret = -1
,09-16 11:36:05.772  3459  4536 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.sap.SapService
09-16 11:36:05.772  3459  4536 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 11:36:05.772  3459  4536 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-16 11:36:05.772  3459  4536 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 11:36:05.772  3459  4536 D SettingsProvider: selectionArgs: false
09-16 11:36:05.772  3459  4536 D SettingsProvider: selectionArgs: 1002
09-16 11:36:05.772  3459  4536 D SettingsProvider: ret = -1
,09-16 11:36:05.772  3459  4380 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-16 11:36:05.772  3459  4380 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 11:36:05.772  3459  4380 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-16 11:36:05.772  3459  4380 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 11:36:05.772  3459  4380 D SettingsProvider: selectionArgs: false
09-16 11:36:05.772  3459  4380 D SettingsProvider: selectionArgs: 1002
09-16 11:36:05.782  3459  4380 D SettingsProvider: ret = -1
09-16 11:36:05.782  3459  4412 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-16 11:36:05.782  3459  4412 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
09-16 11:36:05.782  3459  4412 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 11:36:05.782  3459  4412 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 11:36:05.782  3459  4412 D SettingsProvider: selectionArgs: false
,09-16 11:36:05.782  3459  4412 D SettingsProvider: selectionArgs: 1002
09-16 11:36:05.782  3459  4412 D SettingsProvider: ret = -1
,09-16 11:36:05.782  3459  4049 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.broadcom.bt.service.bleaudio.BleAudioService
09-16 11:36:05.782  3459  4049 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,09-16 11:36:05.782  3459  4049 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-16 11:36:05.782  3459  4049 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-16 11:36:05.782  3459  4049 D SettingsProvider: selectionArgs: false
09-16 11:36:05.782  3459  4049 D SettingsProvider: selectionArgs: 1002
,09-16 11:36:05.782  3459  4049 D SettingsProvider: ret = -1
,09-16 11:36:05.782  9949  9949 D InjectionManager: InjectionManager
09-16 11:36:05.782  9949  9949 D InjectionManager: fillFeatureStoreMap com.android.bluetooth
09-16 11:36:05.782  9949  9949 I InjectionManager: Constructor com.android.bluetooth, Feature store :{}
,09-16 11:36:05.782  9949  9949 I InjectionManager: featureStore :{}
,09-16 11:36:05.792  3459  4053 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a2fab0c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc9767 9803:com.google.android.apps.maps/u0a125}
,09-16 11:36:05.802  9949  9962 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-16 11:36:05.802  9949  9962 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-16 11:36:05.812  3459  4053 I ActivityManager: Killing 9390:com.samsung.android.themecenter/1000 (adj 15): DHA:empty #33
,09-16 11:36:05.812  3459  4053 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9adb8d1 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
,09-16 11:36:05.832  3459  4856 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themecenter, Auto Run ON
,09-16 11:36:05.832  9937  9937 I DBG_POLICYDM: [com.policydm.XDMService(161/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,09-16 11:36:05.842  9937  9937 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(51/<init>)] 
09-16 11:36:05.842  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:05.842  9937  9937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:55 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:17 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:23 
,09-16 11:36:05.852  3459  3483 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fed8f36 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ddeaba 9697:com.test.thalitest/u0a177}
,09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:05.852  3459  4416 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:05.872  9966  9966 E Zygote  : v2
09-16 11:36:05.872  9966  9966 I libpersona: KNOX_SDCARD checking this for 10078
09-16 11:36:05.872  9966  9966 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:05.872  9966  9966 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:05.872  3459  3974 I ActivityManager: Start proc 9966:com.samsung.aasaservice/u0a78 for service com.samsung.aasaservice/.AASAService
,09-16 11:36:05.872  9966  9966 E Zygote  : accessInfo : 0
09-16 11:36:05.872  9966  9966 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,09-16 11:36:05.882  9937  9937 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(26/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,09-16 11:36:05.902  9937  9937 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,09-16 11:36:05.902  9937  9937 I DBG_POLICYDM: [com.policydm.XDMService(570/llIlIllllllllllllllI)] get NotibarState : 0
,09-16 11:36:05.912  9937  9937 D InjectionManager: InjectionManager
09-16 11:36:05.912  9937  9937 D InjectionManager: fillFeatureStoreMap com.policydm
,09-16 11:36:05.912  9937  9937 I InjectionManager: Constructor com.policydm, Feature store :{}
09-16 11:36:05.912  9937  9937 I InjectionManager: featureStore :{}
,09-16 11:36:05.912  9966  9966 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:05.912  9966  9966 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:05.952  9937  9937 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,09-16 11:36:05.952  9966  9966 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:05.952  9966  9966 D RelationGraph: garbageCollect()
,09-16 11:36:05.962  9966  9966 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package com.samsung.aasaservice
,09-16 11:36:05.962  3459  3974 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:05.962  9966  9966 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:05.962  9937  9937 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,09-16 11:36:05.972  9966  9966 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:05.972  9937  9937 I DBG_POLICYDM: [com.policydm.XDMService(570/llIlIllllllllllllllI)] get NotibarState : 0
,09-16 11:36:05.972  9966  9966 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:05.982  3459  3484 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{130e75b 9937:com.policydm/1000}
09-16 11:36:05.982  9966  9966 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm64
,09-16 11:36:05.982  9937  9937 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,09-16 11:36:05.982  9966  9966 D InjectionManager: InjectionManager
09-16 11:36:05.982  9966  9966 D InjectionManager: fillFeatureStoreMap com.samsung.aasaservice
,09-16 11:36:05.982  9966  9966 I InjectionManager: Constructor com.samsung.aasaservice, Feature store :{}
09-16 11:36:05.982  9966  9966 I InjectionManager: featureStore :{}
,09-16 11:36:05.992  9966  9966 D AASAservice: onCreate()
,09-16 11:36:06.002  9979  9979 E Zygote  : v2
,09-16 11:36:06.002  9979  9979 I libpersona: KNOX_SDCARD checking this for 10044
09-16 11:36:06.002  9979  9979 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:06.012  9979  9979 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:06.012  3459  3484 I ActivityManager: Start proc 9979:com.osp.app.signin/u0a44 for broadcast-5 com.osp.app.signin/.OspReceiver
,09-16 11:36:06.012  3459  3484 I ActivityManager: Killing 9403:com.samsung.android.scloud/5009 (adj 15): DHA:empty #33
09-16 11:36:06.012  9979  9979 E Zygote  : accessInfo : 0
09-16 11:36:06.012  9979  9979 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.osp.app.signin 
,09-16 11:36:06.022  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:36:06.022  3459  3484 I ActivityManager: Killing 9426:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #33
09-16 11:36:06.022  9937  9937 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(37/onServiceConnected)] AASA: onServiceConnected
,09-16 11:36:06.042  3459  4049 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,09-16 11:36:06.042  9979  9979 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:06.042  9979  9979 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:06.052  3459  4416 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,09-16 11:36:06.072  3459  4380 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e7b68c2 9979:com.osp.app.signin/u0a44}
,09-16 11:36:06.082  9979  9979 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:06.082  9979  9979 D RelationGraph: garbageCollect()
,09-16 11:36:06.092  9979  9979 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in com.osp.app.signin rsrc of package com.osp.app.signin
,09-16 11:36:06.092  3459  4386 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:06.092  9979  9979 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:06.102  9979  9979 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:06.102  9979  9979 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:06.122  9979  9979 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungAccount_Hero/lib/arm64
,09-16 11:36:06.132  9979  9979 I SA      : [SSP] onCreated
,09-16 11:36:06.132  3459  3537 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
09-16 11:36:06.132  3459  3537 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
09-16 11:36:06.132  3459  3537 E libgps  : IPC Communication Error, ../../../../tmp/14804949_263294/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,09-16 11:36:06.162  9979  9979 D SamsungAnalytics: [Tracker] Tracker start:1.2.00
,09-16 11:36:06.182  9979  9979 I SA      : [TPM] There is no property file
,09-16 11:36:06.182  9979  9979 I SA      : [SCU] isHaveSA() - false
,09-16 11:36:06.182  9979  9979 I SA      : [TPM] getModelProperty : null
09-16 11:36:06.182  9979  9979 I SA      : [TPM] getCSCProperty : null
,09-16 11:36:06.182  9979  9979 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-16 11:36:06.182  9979  9979 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-16 11:36:06.182  9979  9979 I SA      : [DM] TFT FEATURE: false
,09-16 11:36:06.182  9979  9979 I SA      : [SCU] isHaveSA() - false
,09-16 11:36:06.192  9979  9979 I SA      : [SCU] == networkStateCheck == false
09-16 11:36:06.192  9979  9979 I SA      : [SS] network off, couldn't connect to DIR
,09-16 11:36:06.192  9979  9979 D InjectionManager: InjectionManager
09-16 11:36:06.192  9979  9979 D InjectionManager: fillFeatureStoreMap com.osp.app.signin
09-16 11:36:06.192  9979  9979 I InjectionManager: Constructor com.osp.app.signin, Feature store :{}
09-16 11:36:06.192  9979  9979 I InjectionManager: featureStore :{}
,09-16 11:36:06.192  9979  9979 I SA      : [DM] init START
,09-16 11:36:06.192  9979  9979 I SA      : [DM] This device is not a Vodafone
,09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: Failure getting entry for 0x7f0a0002 (t=9 e=2) (error -75)
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.202  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.212  9979  9979 W ResourceType: Failure getting entry for 0x7f0a0005 (t=9 e=5) (error -75)
,09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.212  9979  9979 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-16 11:36:06.222  9979  9979 I SA      : support phone number id : true
09-16 11:36:06.222  9979  9979 I SA      : [DM] Supports Ref Jpn : true
,09-16 11:36:06.222  9979  9979 I SA      : [DM] init END
09-16 11:36:06.222  9979  9979 I SA      : [OR] onReceive log=[SA = 2.2.01-90 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hero2lte P = hero2ltexx I = MMB29K M = SM-G935F OKLEFT false DIS MMB29K.G935FXXU1BPH6 PSS = 5.460694751064798  ]
,09-16 11:36:06.222  9979  9979 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-16 11:36:06.222  9979  9979 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-16 11:36:06.222  9979  9979 I SA      : [SLFUCHKMGR] constructor called
,09-16 11:36:06.232  9979  9979 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-16 11:36:06.232  9979  9979 I SA      : [OR] == isSIMCardReady false ==
09-16 11:36:06.232  9979  9979 I SA      : [SCU] == networkStateCheck == false
09-16 11:36:06.232  9979  9979 I SA      : [OR] onReceive END
,09-16 11:36:06.252  9996  9996 E Zygote  : v2
09-16 11:36:06.252  9996  9996 I libpersona: KNOX_SDCARD checking this for 1000
09-16 11:36:06.252  9996  9996 I libpersona: KNOX_SDCARD not a persona
09-16 11:36:06.252  9996  9996 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:06.252  3459  4386 I ActivityManager: Start proc 9996:com.wssyncmldm/1000 for broadcast-5 com.wssyncmldm/com.samsung.android.app.fotaclient.NetworkReceiver
,09-16 11:36:06.262  9996  9996 E Zygote  : accessInfo : 0
09-16 11:36:06.262  3459  4386 I ActivityManager: Killing 9438:com.google.android.apps.docs/u0a98 (adj 15): DHA:empty #33
,09-16 11:36:06.302  9996  9996 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:06.302  9996  9996 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:06.302  3459  3483 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,09-16 11:36:06.322  3459  4049 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c82e6d3 9996:com.wssyncmldm/1000}
,09-16 11:36:06.332  9996  9996 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:06.332  9996  9996 D RelationGraph: garbageCollect()
,09-16 11:36:06.342  9996  9996 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.wssyncmldm rsrc of package com.wssyncmldm
,09-16 11:36:06.342  3459  4053 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:06.342  9996  9996 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:06.342  9996  9996 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:06.352  9996  9996 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:06.362  9996  9996 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm64
,09-16 11:36:06.372  9996  9996 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,09-16 11:36:06.382  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:06.462  9996  9996 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(2021/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,09-16 11:36:06.522  9697  9762 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-16 11:36:06.522  3459  4208 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-16 11:36:06.532  9996  9996 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(271/llIlIIIIlIIIIIlIlIII)] Voice : true
09-16 11:36:06.532  9996  9996 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(272/llIlIIIIlIIIIIlIlIII)] SMS : true
09-16 11:36:06.532  9996  9996 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(273/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,09-16 11:36:06.532  3459  4208 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-16 11:36:06.532  3459  4208 D WifiService: setWifiEnabled: true pid=9697, uid=10177
09-16 11:36:06.532  3459  4208 W ActivityManager: Permission Denial: getCurrentUser() from pid=9697, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
09-16 11:36:06.532  3459  4208 W WifiService: Failed getting userId using ActivityManagerNative
09-16 11:36:06.532  3459  4208 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9697, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
09-16 11:36:06.532  3459  4208 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28247)
09-16 11:36:06.532  3459  4208 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
09-16 11:36:06.532  3459  4208 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
09-16 11:36:06.532  3459  4208 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-16 11:36:06.532  3459  4208 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
09-16 11:36:06.532  3459  4208 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,09-16 11:36:06.532  3459  4208 D SettingsProvider: isChangeAllowed() : name = wifi_on
09-16 11:36:06.542  3459  3858 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-16 11:36:06.542  3459  3858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
09-16 11:36:06.542  3459  3861 D WifiStateMachine: setFccChannel: channel = 0
09-16 11:36:06.542  3459  3861 D WifiController: [FCC]setFccChannel() is called !!!
09-16 11:36:06.542  3459  3861 D SecContentProvider: insert(), uri = 2
09-16 11:36:06.542  3459  3861 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
09-16 11:36:06.542  3459  3858 D WifiBigDataLog: init : 
,09-16 11:36:06.542  9996  9996 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3216/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
09-16 11:36:06.542  3459  3858 E WifiHW  : ##################### set firmware type 0 #####################
,09-16 11:36:06.552  3155  3637 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,09-16 11:36:06.552  9996  9996 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3268/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,09-16 11:36:06.552  3155  3637 I WifiHW  : module is semco
,09-16 11:36:06.552  3155  3637 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
09-16 11:36:06.552  3155  3637 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
09-16 11:36:06.552  3155  3637 E WifiHW  : TEMP_FAILURE_RETRY complete
,09-16 11:36:06.552  3155  3637 D SoftapController: Softap fwReload - Ok
,09-16 11:36:06.562  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:06.562  9996  9996 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(102/onCreate)] DMApplication NOT Start !
09-16 11:36:06.562  9996  9996 D InjectionManager: InjectionManager
,09-16 11:36:06.562  9996  9996 D InjectionManager: fillFeatureStoreMap com.wssyncmldm
09-16 11:36:06.562  3155  3637 D CommandListener: Setting iface cfg
09-16 11:36:06.562  3155  3637 D CommandListener: Trying to bring down wlan0
,09-16 11:36:06.562  9996  9996 I InjectionManager: Constructor com.wssyncmldm, Feature store :{}
09-16 11:36:06.562  9996  9996 I InjectionManager: featureStore :{}
09-16 11:36:06.562  3155  3637 D CommandListener: Clearing all IP addresses on wlan0
,09-16 11:36:06.572  3459  3858 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 11:36:06.572  3459  3858 D wifi    : Can not initialize the vendor function pointer table
09-16 11:36:06.572  3459  3858 E WifiNative-HAL: Could not start hal
09-16 11:36:06.572  3459  3858 E WifiStateMachine: Failed to start HAL
,09-16 11:36:06.572  3459  3858 E WifiHW  : supplicant_name : p2p_supplicant
,09-16 11:36:06.572  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{42c210 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
,09-16 11:36:06.592  3459  4049 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f090087 6861:com.samsung.fresco.logging/5015}
,09-16 11:36:06.592  3459  4412 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:06.592  3459  4380 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:06.602  3459  3459 I ActivityManager: Killing 9461:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #33
,09-16 11:36:06.632  3459  4049 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e75ed01 7311:com.sec.spp.push/u0a42}
,09-16 11:36:06.632  7311  7311 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,09-16 11:36:06.632  7311  7311 E SPPClientService: [SystemStateMoniter] Current Time : 247242
,09-16 11:36:06.632  7311  7311 E SPPClientService: [SystemStateMoniter] No Connect : true
,09-16 11:36:06.642  3459  3979 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,09-16 11:36:06.662  7311 10012 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-16 11:36:06.662  3459  3974 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c1741df 4838:android.process.media/u0a51}
,09-16 11:36:06.672  4838  4838 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-16 11:36:06.672  3459  3858 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-16 11:36:06.672  3459  3459 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,09-16 11:36:06.682  3459  3459 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-16 11:36:06.682  3459  3865 I WifiHs20Service: Message received 5011
,09-16 11:36:06.682  3459  3459 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,09-16 11:36:06.682  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:06.682  3459  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
09-16 11:36:06.682  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-16 11:36:06.682  3949  3949 I HotspotTile: Provider is not defined returning false
,09-16 11:36:06.682  4305  4627 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-16 11:36:06.682  3949  3949 D HotspotTile: onReceive : 2, 0
,09-16 11:36:06.682  4305  4627 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-16 11:36:06.682  3459  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-16 11:36:06.692  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:06.692  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:06.692  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61b4f0e u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ddeaba 9697:com.test.thalitest/u0a177}
,09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:06.692  3459  4049 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:06.712 10013 10013 E Zygote  : v2
09-16 11:36:06.712 10013 10013 I libpersona: KNOX_SDCARD checking this for 1000
09-16 11:36:06.712 10013 10013 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:06.712 10013 10013 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:06.712 10013 10013 E Zygote  : accessInfo : 0
,09-16 11:36:06.722  3459  4208 I ActivityManager: Start proc 10013:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
,09-16 11:36:06.732 10013 10013 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:06.732 10013 10013 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:06.742  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:06.752  3459  3483 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e8b1d2f 10013:com.samsung.android.SettingsReceiver/1000}
,09-16 11:36:06.752 10011 10011 I FIPS_bssl: FIPS approved mode (1) | 10011 | /system/bin/wpa_supplicant
,09-16 11:36:06.762 10011 10011 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-16 11:36:06.762 10013 10013 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:06.762 10011 10011 I wpa_supplicant: Successfully initialized wpa_supplicant
09-16 11:36:06.762 10011 10011 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
09-16 11:36:06.762 10013 10013 D RelationGraph: garbageCollect()
09-16 11:36:06.762 10011 10011 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-16 11:36:06.762 10013 10013 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
,09-16 11:36:06.762  3459  4834 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 11:36:06.762 10013 10013 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:06.762 10013 10013 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:06.762 10013 10013 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:06.772 10013 10013 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
,09-16 11:36:06.772 10013 10013 D InjectionManager: InjectionManager
,09-16 11:36:06.772 10013 10013 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
09-16 11:36:06.772 10013 10013 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
09-16 11:36:06.772 10013 10013 I InjectionManager: featureStore :{}
,09-16 11:36:06.772 10013 10013 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.android.settings
09-16 11:36:06.782 10011 10011 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-16 11:36:06.782  3013  3013 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10011
,09-16 11:36:06.782  3013  3013 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-16 11:36:06.782 10011 10011 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-16 11:36:06.782 10013 10013 D ResourcesManager: For user 0 new overlays fetched Null
09-16 11:36:06.782 10011 10011 I wpa_supplicant: ssSupport state is = 1
09-16 11:36:06.782 10011 10011 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,09-16 11:36:06.782 10011 10011 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-16 11:36:06.782  3013  3013 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10011
09-16 11:36:06.782  3013  3013 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,09-16 11:36:06.782 10013 10013 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,09-16 11:36:06.792 10011 10011 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,09-16 11:36:06.812 10027 10027 E Zygote  : v2
09-16 11:36:06.812 10027 10027 I libpersona: KNOX_SDCARD checking this for 10068
09-16 11:36:06.812 10027 10027 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 11:36:06.812 10027 10027 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:06.812 10027 10027 E Zygote  : accessInfo : 0
09-16 11:36:06.812 10027 10027 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,09-16 11:36:06.812  3459  4412 I ActivityManager: Start proc 10027:com.samsung.android.themestore/u0a68 for broadcast-5 com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,09-16 11:36:06.812  3459  4412 I ActivityManager: Killing 9476:com.sec.android.widgetapp.samsungapps/u0a110 (adj 15): DHA:empty #33
,09-16 11:36:06.832 10027 10027 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:06.832 10027 10027 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:06.852  3459  4536 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{579ef3c 10027:com.samsung.android.themestore/u0a68}
,09-16 11:36:06.862 10027 10027 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:06.862 10027 10027 D RelationGraph: garbageCollect()
,09-16 11:36:06.862  3459  4834 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.samsungapps, Auto Run ON,
09-16 11:36:06.862 10027 10027 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeStore_3xh/ThemeStore_3xh.apk / 1.0 running in com.samsung.android.themestore rsrc of package com.samsung.android.themestore
,09-16 11:36:06.862  3459  4380 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 11:36:06.862 10027 10027 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:06.862 10027 10027 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:06.872 10027 10027 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:06.872 10027 10027 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeStore_3xh/lib/arm64
,09-16 11:36:06.882 10027 10027 D a       : Exist Config : false
,09-16 11:36:06.882 10027 10027 D a       : getMcc
09-16 11:36:06.882 10027 10027 D ai      : isQaMode
,09-16 11:36:06.892 10027 10027 D a       : getMnc
,09-16 11:36:06.892 10027 10027 D a       : getCsc
09-16 11:36:06.892 10027 10027 D a       : getSystemCountryCode
09-16 11:36:06.892 10027 10027 D a       : getImei
,09-16 11:36:06.892 10027 10027 D ai      : getMd5HashString
,09-16 11:36:06.902 10027 10027 D ai      : getSha256HashString
,09-16 11:36:06.902 10027 10027 D a       : getMsisdn
,09-16 11:36:06.902  4305  4632 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,09-16 11:36:06.922  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:06.922 10027 10027 D a       : getModelName
,09-16 11:36:06.922 10027 10027 D a       : getVirtualModelName
09-16 11:36:06.922 10027 10027 D a       : getAndroidSDKVersion
09-16 11:36:06.922 10027 10027 D a       : getLanguageCode
09-16 11:36:06.922 10027 10027 D a       : getCountryCode
,09-16 11:36:06.922 10027 10027 D a       : getNetworkType
,09-16 11:36:06.932 10027 10027 D t       : isSupportedAodSystemFeature
,09-16 11:36:06.932 10027 10027 D a       : isLogPrintMode
,09-16 11:36:06.942 10027 10027 D ai      : isQaMode
,09-16 11:36:06.942 10027 10027 D a       : getVerName
,09-16 11:36:06.952 10027 10027 D a       : getVerCode
,09-16 11:36:06.952 10027 10027 D a       : getPackageName
,09-16 11:36:06.952 10027 10027 D a       : getAutoUpgradeInterval
,09-16 11:36:06.952 10027 10027 D a       : loadCountrySearchEx
,09-16 11:36:06.962 10027 10027 I a       : voCountrySearchEx loaded.
,09-16 11:36:06.962 10027 10027 I a       : # initConfig Time : 85
,09-16 11:36:06.962 10027 10027 I a       : ● MCCNNC : 260 0
09-16 11:36:06.962 10027 10027 I a       : ● Model : SM-G935F_TM
,09-16 11:36:06.962 10027 10027 I a       : ● MyApp Vertion : 1.03.22(20160524)
09-16 11:36:06.962 10027 10027 I a       : ● OS Vertion : 23
,09-16 11:36:06.982 10027 10027 D InjectionManager: InjectionManager
,09-16 11:36:06.982 10027 10027 D InjectionManager: fillFeatureStoreMap com.samsung.android.themestore
09-16 11:36:06.982 10027 10027 I InjectionManager: Constructor com.samsung.android.themestore, Feature store :{}
09-16 11:36:06.982 10027 10027 I InjectionManager: featureStore :{}
09-16 11:36:06.982 10027 10027 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,09-16 11:36:07.002 10046 10046 E Zygote  : v2
09-16 11:36:07.002 10046 10046 I libpersona: KNOX_SDCARD checking this for 5009
09-16 11:36:07.002 10046 10046 I libpersona: KNOX_SDCARD not a persona
09-16 11:36:07.002 10046 10046 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:07.012 10046 10046 E Zygote  : accessInfo : 0
,09-16 11:36:07.012 10046 10046 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud:contentsync 
09-16 11:36:07.012  3459  4412 I ActivityManager: Start proc 10046:com.samsung.android.scloud:contentsync/5009 for broadcast-5 com.samsung.android.scloud/.cloudagent.detector.DetectorReceiver
,09-16 11:36:07.012  3459  4412 I ActivityManager: Killing 9502:com.samsung.android.app.mirrorlink/1000 (adj 15): DHA:empty #33
,09-16 11:36:07.042  3459  3979 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.mirrorlink, Auto Run ON
,09-16 11:36:07.042 10046 10046 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:07.042 10046 10046 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:07.062  3459  4049 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3754c5 10046:com.samsung.android.scloud:contentsync/5009}
,09-16 11:36:07.082  3013  3013 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
09-16 11:36:07.082 10011 10011 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
,09-16 11:36:07.082 10046 10046 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:07.082 10046 10046 D RelationGraph: garbageCollect()
,09-16 11:36:07.082 10046 10046 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.scloud
,09-16 11:36:07.082  3459  3484 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:07.082 10046 10046 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:07.092 10046 10046 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:07.092 10046 10046 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:07.092 10046 10046 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungCloud/lib/arm64
,09-16 11:36:07.102  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:07.102 10011 10011 I wpa_supplicant: Ctrl_iface: loading system cred
09-16 11:36:07.102 10011 10011 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,09-16 11:36:07.132 10011 10011 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,09-16 11:36:07.132  3013  3013 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10011
09-16 11:36:07.132  3013  3013 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
09-16 11:36:07.132 10011 10011 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
09-16 11:36:07.132 10011 10011 I wpa_supplicant: ssSupport state is = 1
,09-16 11:36:07.132 10011 10011 I wpa_supplicant: Blacklist: Clear (all) 
,09-16 11:36:07.132 10011 10011 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-16 11:36:07.132 10011 10011 I wpa_supplicant: [getIMSI]: sim_num 0
,09-16 11:36:07.132 10011 10011 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 11:36:07.132 10046 10046 I [SC]CloudManager: requestInit
,09-16 11:36:07.162 10046 10046 I [SC]Utils: folder : cachecreate fail, try again.
09-16 11:36:07.162 10046 10046 I [SC]Utils: folder : cache create fail.
,09-16 11:36:07.162 10046 10046 I [SC]Utils: folder : thumbnailcreate fail, try again.
09-16 11:36:07.162 10046 10046 I [SC]Utils: folder : thumbnail create fail.
09-16 11:36:07.162 10046 10046 I [SC]Utils: folder : sharecreate fail, try again.
09-16 11:36:07.162 10046 10046 I [SC]Utils: folder : share create fail.
09-16 11:36:07.162 10046 10046 I [SC]Utils: folder : scratchcreate fail, try again.
09-16 11:36:07.162 10046 10046 I [SC]Utils: folder : scratch create fail.
09-16 11:36:07.162 10046 10046 I [SC]Utils: folder : eventSynccreate fail, try again.
,09-16 11:36:07.162 10046 10046 I [SC]Utils: folder : eventSync create fail.
,09-16 11:36:07.192 10046 10046 V SamsungCloudLogs:  set Log level [4->4]act[false]
,09-16 11:36:07.202 10046 10046 I [SC]CommonUtil: isSemAvailable:0
,09-16 11:36:07.212 10046 10046 I [SC]SamsungCloudApp: AppVer[2.1.11][L:4]Sem[false]V2DEV_R slog[false]com.samsung.android.scloud:contentsync
,09-16 11:36:07.212 10046 10046 D InjectionManager: InjectionManager
09-16 11:36:07.212 10046 10046 D InjectionManager: fillFeatureStoreMap com.samsung.android.scloud
,09-16 11:36:07.212 10046 10046 I InjectionManager: Constructor com.samsung.android.scloud, Feature store :{}
09-16 11:36:07.212 10046 10046 I InjectionManager: featureStore :{}
,09-16 11:36:07.222 10046 10046 I [SC]FeatureManager: FeatureManager 
09-16 11:36:07.222 10046 10046 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_CONFIG_CLOUD_USAGE_MENU_TREE]str 
09-16 11:36:07.222 10046 10046 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_ENABLE_SETTING_MENU]bln true
,09-16 11:36:07.222 10046 10046 E [SC]SCLOUD_ERR-Utils: isShipMode : 1 
,09-16 11:36:07.232 10046 10046 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
,09-16 11:36:07.232 10046 10046 I [SC]CloudManager: requestInit
09-16 11:36:07.232 10046 10046 I [SC]Utils: folder : cachecreate fail, try again.
09-16 11:36:07.232 10046 10046 I [SC]Utils: folder : cache create fail.
09-16 11:36:07.232 10046 10046 I [SC]Utils: folder : thumbnailcreate fail, try again.
,09-16 11:36:07.232 10046 10046 I [SC]Utils: folder : thumbnail create fail.
09-16 11:36:07.232 10046 10046 I [SC]Utils: folder : sharecreate fail, try again.
09-16 11:36:07.232 10046 10046 I [SC]Utils: folder : share create fail.
,09-16 11:36:07.232 10046 10046 I [SC]Utils: folder : scratchcreate fail, try again.
09-16 11:36:07.242 10046 10046 I [SC]Utils: folder : scratch create fail.
,09-16 11:36:07.242 10046 10046 I [SC]Utils: folder : eventSynccreate fail, try again.
09-16 11:36:07.242 10046 10046 I [SC]Utils: folder : eventSync create fail.
,09-16 11:36:07.272  9979  9990 I SA      : [SCU] isHaveSA() - false
09-16 11:36:07.272  9979  9990 I SA      : [OCP] Samsung account is not Signed-in
,09-16 11:36:07.282  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:07.282  9979  9990 I SA      : [OCP] Delete DB (TNC data)
,09-16 11:36:07.282 10046 10046 I [SC]CommonUtil: Samsung Account Not Logged in
,09-16 11:36:07.302 10060 10060 E Zygote  : v2
09-16 11:36:07.302 10060 10060 I libpersona: KNOX_SDCARD checking this for 5011
09-16 11:36:07.302 10060 10060 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:07.312 10060 10060 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:07.312 10060 10060 E Zygote  : accessInfo : 0
09-16 11:36:07.312 10060 10060 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.coreapps 
09-16 11:36:07.312  3459  3974 I ActivityManager: Start proc 10060:com.samsung.android.coreapps/5011 for broadcast-5 com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener
,09-16 11:36:07.312  3459  3974 I ActivityManager: Killing 9516:com.sec.android.app.sbrowser/u0a141 (adj 15): DHA:empty #33
,09-16 11:36:07.342  3459  4424 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.sbrowser, Auto Run ON
,09-16 11:36:07.342 10060 10060 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:07.342 10060 10060 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:07.362  3459  3484 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fbd7841 10060:com.samsung.android.coreapps/5011}
,09-16 11:36:07.372 10060 10060 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:07.372 10060 10060 D RelationGraph: garbageCollect()
,09-16 11:36:07.372 10060 10060 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.samsung.android.coreapps
,09-16 11:36:07.382  3459  4208 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 11:36:07.382 10060 10060 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:07.382 10060 10060 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:07.392 10060 10060 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:07.392 10060 10060 W System  : ClassLoader referenced unknown path: /system/app/CoreApps/lib/arm64
,09-16 11:36:07.412 10060 10060 D CoreApps: SEC_LOG - true
,09-16 11:36:07.452 10060 10060 E GooglePlayServicesUtil: The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,09-16 11:36:07.462  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:07.642  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:07.662 10060 10060 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.android.mms
,09-16 11:36:07.662 10060 10060 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:07.662 10060 10060 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.google.android.talk
,09-16 11:36:07.672 10060 10060 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:07.682 10060 10060 D InjectionManager: InjectionManager
,09-16 11:36:07.682 10060 10060 D InjectionManager: fillFeatureStoreMap com.samsung.android.coreapps
09-16 11:36:07.682 10060 10060 I InjectionManager: Constructor com.samsung.android.coreapps, Feature store :{}
09-16 11:36:07.682 10060 10060 I InjectionManager: featureStore :{}
,09-16 11:36:07.692  3459  3974 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fbd7841 10060:com.samsung.android.coreapps/5011}
,09-16 11:36:07.722  3459  4386 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fbd7841 10060:com.samsung.android.coreapps/5011}
,09-16 11:36:07.732  3459  4386 I ActivityManager: Killing 9531:com.sec.android.app.samsungapps/u0a16 (adj 15): DHA:empty #33
,09-16 11:36:07.742  3459  4386 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9546ee9 4865:com.microsoft.skydrive/u0a130}
,09-16 11:36:07.742  3459  4380 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:07.762  3459  4536 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,09-16 11:36:07.782  3459  4049 I ActivityManager: Start proc 10086:com.microsoft.office.onenote.connectionReceiverProcess/u0a12 for broadcast-5 com.microsoft.office.onenote/com.microsoft.bing.datamining.quasar.api.ConnectionChangeReceiver
,09-16 11:36:07.802  3459  3483 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.samsungapps, Auto Run ON
,09-16 11:36:07.822  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:07.852 10086 10086 E Zygote  : v2
09-16 11:36:07.852 10086 10086 I libpersona: KNOX_SDCARD checking this for 10012
09-16 11:36:07.852 10086 10086 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:07.852 10086 10086 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:07.852 10086 10086 E Zygote  : accessInfo : 0
,09-16 11:36:07.852 10086 10086 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.microsoft.office.onenote.connectionReceiverProcess 
,09-16 11:36:07.892 10086 10086 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:07.892 10086 10086 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:07.912  3459  4536 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{406e9d4 10086:com.microsoft.office.onenote.connectionReceiverProcess/u0a12}
,09-16 11:36:07.922 10086 10086 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:07.922 10086 10086 D RelationGraph: garbageCollect()
,09-16 11:36:07.922 10086 10086 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.microsoft.office.onenote rsrc of package com.microsoft.office.onenote
,09-16 11:36:07.932  3459  4386 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:07.932 10086 10086 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:07.942 10086 10086 D ResourcesManager: For user 0 new overlays fetched Null
09-16 11:36:07.942  3155  3630 D Netd    : Iface wlan0 link up
,09-16 11:36:07.942  3155  3630 D Netd    : Iface wlan0 link up
,09-16 11:36:07.942  3155  3630 D Netd    : Iface wlan0 link up
09-16 11:36:07.942  5051  5067 D PdnController: Interface Changed wlan0 link up
09-16 11:36:07.942  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
,09-16 11:36:07.942  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
09-16 11:36:07.942  5051  5344 D PdnController: Interface Changed wlan0 link up
,09-16 11:36:07.942  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 11:36:07.942  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
,09-16 11:36:07.942  5051  5066 D PdnController: Interface Changed wlan0 link up
,09-16 11:36:07.942  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 11:36:07.942  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
,09-16 11:36:07.942 10086 10086 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:07.952 10086 10086 W System  : ClassLoader referenced unknown path: /system/app/OneNote/lib/arm
,09-16 11:36:07.962 10086 10086 D InjectionManager: InjectionManager
,09-16 11:36:07.962 10086 10086 D InjectionManager: fillFeatureStoreMap com.microsoft.office.onenote
09-16 11:36:07.972 10086 10086 I InjectionManager: Constructor com.microsoft.office.onenote, Feature store :{}
09-16 11:36:07.972 10086 10086 I InjectionManager: featureStore :{}
,09-16 11:36:07.972  3459  4536 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:07.972 10086 10086 I Quasar  : Wifi detected off:  1474018567978
,09-16 11:36:07.982 10086 10086 I Process : Sending signal. PID: 10086 SIG: 9
,09-16 11:36:08.002  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:08.012  3459  4834 I ActivityManager: Process com.microsoft.office.onenote.connectionReceiverProcess (pid 10086)(adj 0) has died(52,1773)
,09-16 11:36:08.012  3459  4834 D ActivityManager: isAutoRunBlockedApp:: com.microsoft.office.onenote, Auto Run ON
,09-16 11:36:08.062 10102 10102 E Zygote  : v2
09-16 11:36:08.062 10102 10102 I libpersona: KNOX_SDCARD checking this for 10135
09-16 11:36:08.062 10102 10102 I libpersona: KNOX_SDCARD not a persona
09-16 11:36:08.062 10102 10102 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:08.062 10011 10011 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
09-16 11:36:08.062 10011 10011 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,09-16 11:36:08.062 10102 10102 E Zygote  : accessInfo : 0
09-16 11:36:08.062 10102 10102 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,09-16 11:36:08.062  3459  3543 I ActivityManager: Start proc 10102:com.google.android.apps.photos/u0a135 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
09-16 11:36:08.072  3459  3856 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,09-16 11:36:08.122 10102 10102 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:08.122 10102 10102 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:08.122 10011 10011 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,09-16 11:36:08.122  3013  3013 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10011
,09-16 11:36:08.122  3013  3013 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
09-16 11:36:08.122 10011 10011 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
09-16 11:36:08.122 10011 10011 I wpa_supplicant: ssSupport state is = 1
,09-16 11:36:08.132 10011 10011 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 11:36:08.132 10011 10011 E wpa_supplicant: nl80211: Could not configure driver mode
,09-16 11:36:08.132 10011 10011 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
09-16 11:36:08.132 10011 10011 E wpa_supplicant: p2p0: Failed to initialize driver interface
09-16 11:36:08.132 10011 10011 I wpa_supplicant: Blacklist: Clear (all) 
,09-16 11:36:08.132 10011 10011 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
09-16 11:36:08.132 10011 10011 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,09-16 11:36:08.142  3459  4386 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3838672 10102:com.google.android.apps.photos/u0a135}
,09-16 11:36:08.142  3459  3856 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,09-16 11:36:08.162 10102 10102 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:08.162 10102 10102 D RelationGraph: garbageCollect()
,09-16 11:36:08.162 10102 10102 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,09-16 11:36:08.162 10011 10011 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,09-16 11:36:08.162  3013  3013 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10011
09-16 11:36:08.162  3013  3013 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
09-16 11:36:08.162 10011 10011 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
09-16 11:36:08.162 10011 10011 I wpa_supplicant: ssSupport state is = 1
09-16 11:36:08.162 10011 10011 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-16 11:36:08.162  3459  3979 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:08.162 10102 10102 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:08.172 10011 10011 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,09-16 11:36:08.182  3459  3858 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
09-16 11:36:08.182  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:36:08.182  3459  3858 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,09-16 11:36:08.182  3459  3858 D WifiNative-wlan0: callSECApiBoolean - ID [301]
09-16 11:36:08.182 10011 10011 I wpa_supplicant: HOTSPOT20_ENABLE called ON
09-16 11:36:08.182 10011 10011 I wpa_supplicant: Blacklist: Clear (all) 
,09-16 11:36:08.192 10011 10011 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-16 11:36:08.192 10011 10011 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,09-16 11:36:08.192  3459  3858 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-16 11:36:08.202  3459  3459 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,09-16 11:36:08.202  3459  3459 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-16 11:36:08.202  3459  3862 D HS20StateMachine: WIFI_STATE_ENABLED
09-16 11:36:08.202  3459  3862 D HS20StateMachine: reloadCredentialsToSupplicant
,09-16 11:36:08.202  3459  3862 D HotspotDBHandler: getCredentialIds
,09-16 11:36:08.202  3459  3865 I WifiHs20Service: Message received 5011
09-16 11:36:08.202  3459  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-16 11:36:08.202  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 11:36:08.202  3459  3459 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
09-16 11:36:08.202  3459  4250 W SLocation: No Active Data Connection
,09-16 11:36:08.202  4305  4627 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-16 11:36:08.202  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-16 11:36:08.202  4305  4627 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-16 11:36:08.202  3949  3949 I HotspotTile: Provider is not defined returning false
09-16 11:36:08.202  3459  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
09-16 11:36:08.202  3949  3949 D HotspotTile: onReceive : 3, 0
,09-16 11:36:08.212  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:36:08.212  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:08.212  9697  9697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:36:08.212  3949  3949 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,09-16 11:36:08.212  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:36:08.212  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:36:08.212  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:08.212  9697  9697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:36:08.222  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{232ac3 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ddeaba 9697:com.test.thalitest/u0a177}
,09-16 11:36:08.222  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:08.222  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:08.222  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:08.222  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:08.222  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:08.222  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:08.222  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:08.222  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:08.222  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:08.232  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:08.232  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:08.232  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 11:36:08.232  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:08.232  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:08.232  3459  4424 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:08.242 10011 10011 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
09-16 11:36:08.242 10118 10118 E Zygote  : v2
09-16 11:36:08.242 10118 10118 I libpersona: KNOX_SDCARD checking this for 10119
09-16 11:36:08.242 10118 10118 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:08.242 10118 10118 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:08.252 10118 10118 E Zygote  : accessInfo : 0
09-16 11:36:08.252 10118 10118 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,09-16 11:36:08.252  3459  3858 D WifiConfigStore: Loading config and enabling all networks 
,09-16 11:36:08.262  3459  3862 I ActivityManager: Start proc 10118:com.samsung.hs20provider/u0a119 for content provider com.samsung.hs20provider/.Hs20Provider
,09-16 11:36:08.272 10102 10102 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:08.272  3459  3858 I WifiConfigStore: "NG700" is a verified password AP: true
09-16 11:36:08.272  3459  3858 E WifiConfigStore: Not a HS20
,09-16 11:36:08.272 10118 10118 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:08.272 10118 10118 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:08.272  3459  3858 D WifiConfigStore: loaded 0 passpoint configs
,09-16 11:36:08.272  3459  3858 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-16 11:36:08.272  3459  3858 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-16 11:36:08.282  3459  3858 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
,09-16 11:36:08.282  3459  3858 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 11:36:08.282 10102 10102 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:08.282  3459  3858 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
,09-16 11:36:08.282  3459  3459 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
09-16 11:36:08.282  3459  3459 D WifiHs20Service: reason: 2
09-16 11:36:08.282  3459  3865 I WifiHs20Service: Message received 5014
09-16 11:36:08.282  3459  3865 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
09-16 11:36:08.282  3459  3865 E WifiHs20Service: The changed config is NULL
09-16 11:36:08.282  3459  3858 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-16 11:36:08.292 10102 10102 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-16 11:36:08.292  3459  3858 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-16 11:36:08.292 10011 10011 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-16 11:36:08.292 10011 10011 I wpa_supplicant: resume autoscan
09-16 11:36:08.292 10011 10011 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
09-16 11:36:08.292 10011 10011 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
,09-16 11:36:08.292 10011 10011 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-16 11:36:08.292 10011 10011 I wpa_supplicant: reset timer : RESET_TIMER 0
09-16 11:36:08.292 10011 10011 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-16 11:36:08.292 10011 10011 I wpa_supplicant: First Scan Start
,09-16 11:36:08.302 10118 10118 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:08.302 10011 10011 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-16 11:36:08.302 10118 10118 D RelationGraph: garbageCollect()
,09-16 11:36:08.302  3459  3858 D WifiNative-wlan0: Setting external_sim to 1
,09-16 11:36:08.302 10118 10118 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
09-16 11:36:08.302  3459  3858 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
09-16 11:36:08.302  3459  3858 D WifiStateMachine: Setting OUI to DA-A1-19
,09-16 11:36:08.302 10011 10011 I wpa_supplicant: bt_status is set be DISCONNECTED
,09-16 11:36:08.302  3459  3979 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 11:36:08.302 10118 10118 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:08.312 10118 10118 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:08.312 10118 10118 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:08.322 10118 10118 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,09-16 11:36:08.332  3459  3858 E WifiNative-wlan0: do suspend true
,09-16 11:36:08.332 10118 10118 D InjectionManager: InjectionManager
,09-16 11:36:08.332 10118 10118 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
,09-16 11:36:08.332 10118 10118 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
09-16 11:36:08.332 10118 10118 I InjectionManager: featureStore :{}
,09-16 11:36:08.342 10118 10129 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
09-16 11:36:08.342 10118 10129 D HotspotProvider: CREDENTIAL
09-16 11:36:08.342 10118 10129 D HotspotProvider: No prepend tags
,09-16 11:36:08.342  3459  3862 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
09-16 11:36:08.342  3459  3862 D HS20StateMachine: enter : DiscoveringState
,09-16 11:36:08.342  3459  3459 I ActivityManager: Killing 9545:com.facebook.system/u0a14 (adj 15): DHA:empty #33
,09-16 11:36:08.352  3459  3858 D WifiStateMachine:  p2p Needed be enabled 
09-16 11:36:08.352  3459  3857 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-16 11:36:08.352  3155  3637 D CommandListener: Setting iface cfg
09-16 11:36:08.352  3155  3637 D CommandListener: Trying to bring up p2p0
,09-16 11:36:08.352  3155  3630 D Netd    : Iface p2p0 link up
,09-16 11:36:08.352  3459  3858 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
09-16 11:36:08.352  3459  3858 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-16 11:36:08.352  3459  3858 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
09-16 11:36:08.352  3459  3858 D WifiStateMachine: setFccChannelNative: channel = 0
09-16 11:36:08.352  3459  3858 D WifiNative-wlan0: callSECApiInt - ID [230]
09-16 11:36:08.352  3459  3857 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-16 11:36:08.352  3459  3857 D SecContentProvider: insert(), uri = 2
,09-16 11:36:08.362  5051  5346 D PdnController: Interface Changed p2p0 link up
,09-16 11:36:08.362  3459  3890 E WifiScanningService: could not start HAL
,09-16 11:36:08.362  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:08.362  3459  3546 D Tethering: interfaceLinkStateChanged p2p0, true
09-16 11:36:08.362  3459  3546 D Tethering: interfaceStatusChanged p2p0, true
09-16 11:36:08.362  3459  3459 D RttService: SCAN_AVAILABLE : 3
,09-16 11:36:08.362  3459  3891 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-16 11:36:08.362  3459  3857 D WifiP2pService: P2pEnablingState
09-16 11:36:08.362  3459  3857 D WifiP2pService: P2pEnablingState{ what=147457 }
09-16 11:36:08.362  3459  3857 D WifiP2pService: P2p socket connection successful
,09-16 11:36:08.362  3459  3857 D WifiP2pService: P2pEnabledState
,09-16 11:36:08.372  3459  3857 D SecContentProvider: insert(), uri = 2
,09-16 11:36:08.372  3459  3858 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 11:36:08.372  3459  3857 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-16 11:36:08.372  3459  3867 E ConnectivityService: updateNetworkInfo()
09-16 11:36:08.372  3459  3867 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,09-16 11:36:08.372  3459  3459 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-16 11:36:08.372  3459  3571 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-16 11:36:08.372  3459  3571 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
09-16 11:36:08.372  3459  3571 D WifiDisplayController: disconnect
09-16 11:36:08.372  3459  3571 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-16 11:36:08.372  3459  3858 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
09-16 11:36:08.372 10011 10011 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,09-16 11:36:08.372 10011 10011 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,09-16 11:36:08.382  3459  3571 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:08.382  3459  3571 I WifiDisplayAdapter: onP2pDisconnected
09-16 11:36:08.382  3459  3571 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-16 11:36:08.382  3459  3571 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-16 11:36:08.382  3949  3949 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-16 11:36:08.382  3949  3949 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-16 11:36:08.382  3949  3949 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-16 11:36:08.382  3949  3949 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-16 11:36:08.382  3459  4412 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-16 11:36:08.382  3949  3949 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-16 11:36:08.382  4305  4632 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,09-16 11:36:08.392  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f67ee79 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{595a174 9910:com.samsung.android.app.FileShareClient/5005}
,09-16 11:36:08.392  9910  9910 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-16 11:36:08.392  9910  9910 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-16 11:36:08.392  9910  9910 D FileShare-Client: Outbound.stopDelayTimer - 
,09-16 11:36:08.402  3459  4386 D ActivityManager: isAutoRunBlockedApp:: com.facebook.system, Auto Run ON
,09-16 11:36:08.422  3459  4536 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f67ee79 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b1ac55 9922:com.samsung.android.app.FileShareServer/5005}
,09-16 11:36:08.422  9922  9922 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-16 11:36:08.432  9922  9922 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-16 11:36:08.432  9922  9922 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
09-16 11:36:08.432  3459  3857 E WifiP2pService: Failed to set my phone number info into probe response
,09-16 11:36:08.432  3459  3857 D WifiNative-p2p0: p2pGetDeviceAddress
09-16 11:36:08.432  3459  3857 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a6:c7:2d
,09-16 11:36:08.442  3459  3857 D WifiP2pService: DeviceAddress: 4e:c7:2d
,09-16 11:36:08.442  3459  3571 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7 edge
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  deviceAddress: 4e:66:41:a6:c7:2d
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  primary type: 10-0050F204-5
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  secondary type: null
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  wps: 0
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  grpcapab: 0
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  devcapab: 0
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  status: 3
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  wfdInfo: null
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  groupownerAddress: null
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  GOdeviceName: null
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  interfaceAddress: 
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  SConnectInfo : null
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  contactInfoHash : null
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  ssDevInfo : 0
09-16 11:36:08.442  3459  3571 D WifiDisplayController:  iconIdx : 0
,09-16 11:36:08.452  3459  3857 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-16 11:36:08.452  3459  3857 D WifiP2pService: InactiveState
09-16 11:36:08.452  3459  3857 D WifiP2pService: InactiveState{ what=143376 }
,09-16 11:36:08.452  3459  3857 D WifiP2pService: P2pEnabledState{ what=143376 }
09-16 11:36:08.452  3459  3857 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,09-16 11:36:08.542  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:08.652 10102 10102 W Primes  : Memory instrumentations are turned off.
,09-16 11:36:08.662 10102 10102 W Primes  : Timer instrumentations are turned off.
,09-16 11:36:08.672 10102 10102 W Primes  : Crash monitoring is turned off.
,09-16 11:36:08.692 10102 10102 W Primes  : Network monitoring is turned off.
,09-16 11:36:08.692 10102 10102 W Primes  : Package metrics are turned off by default
,09-16 11:36:08.722  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:08.752 10102 10102 D InjectionManager: InjectionManager
09-16 11:36:08.752 10102 10102 D InjectionManager: fillFeatureStoreMap com.google.android.apps.photos
,09-16 11:36:08.752 10102 10102 I InjectionManager: Constructor com.google.android.apps.photos, Feature store :{}
,09-16 11:36:08.752 10102 10102 I InjectionManager: featureStore :{}
,09-16 11:36:08.772  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5458417 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3838672 10102:com.google.android.apps.photos/u0a135}
,09-16 11:36:08.792  3459  4049 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3838672 10102:com.google.android.apps.photos/u0a135}
,09-16 11:36:08.822  3459  4049 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{da27004 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3838672 10102:com.google.android.apps.photos/u0a135}
,09-16 11:36:08.852  3459  4049 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ea0fb2a 7845:com.sec.android.daemonapp/u0a166}
,09-16 11:36:08.862  7845  7845 D [WeatherWidget(1240)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,09-16 11:36:08.862  7845  7845 D [WeatherWidget(1240)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,09-16 11:36:08.872  3155  3630 D Netd    : Iface wlan0 link up
09-16 11:36:08.872 10011 10011 I wpa_supplicant: nl80211: Received scan results (12 BSSes)
09-16 11:36:08.872 10011 10011 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
09-16 11:36:08.872 10011 10011 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
,09-16 11:36:08.872 10011 10011 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-16 11:36:08.872  5051  5066 D PdnController: Interface Changed wlan0 link up
09-16 11:36:08.872 10011 10011 I wpa_supplicant:    allow  - level is under -85dBm [-51] or selected nid [-1] [0]
09-16 11:36:08.872  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 11:36:08.872  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
,09-16 11:36:08.872 10011 10011 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
,09-16 11:36:08.872 10011 10011 I wpa_supplicant:    allow  - level is under -85dBm [-51] or selected nid [-1] [0]
09-16 11:36:08.872 10011 10011 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz level=-51) 
,09-16 11:36:08.902  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:08.902 10141 10141 E Zygote  : v2
09-16 11:36:08.902 10141 10141 I libpersona: KNOX_SDCARD checking this for 10016
09-16 11:36:08.902 10141 10141 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:08.902 10141 10141 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:08.902 10141 10141 E Zygote  : accessInfo : 0
,09-16 11:36:08.902 10141 10141 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.app.samsungapps 
,09-16 11:36:08.912  3459  4053 I ActivityManager: Start proc 10141:com.sec.android.app.samsungapps/u0a16 for broadcast-5 com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver
,09-16 11:36:08.922  3459  3858 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 11:36:08.922  3459  3459 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,09-16 11:36:08.932  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d667022 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{616e16b 3949:com.android.systemui/u0a65}
,09-16 11:36:08.932  3459  4053 I ActivityManager: Killing 9557:com.facebook.appmanager/u0a103 (adj 15): DHA:empty #33
,09-16 11:36:08.942 10141 10141 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:08.942 10141 10141 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:08.962  3459  4208 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e7ffe5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7144ab3 10141:com.sec.android.app.samsungapps/u0a16}
,09-16 11:36:08.972  3459  4412 D ActivityManager: isAutoRunBlockedApp:: com.facebook.appmanager, Auto Run ON
,09-16 11:36:08.972 10141 10141 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:08.972 10141 10141 D RelationGraph: garbageCollect()
,09-16 11:36:08.982 10141 10141 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-1/base.apk / 1.0 running in com.sec.android.app.samsungapps rsrc of package com.sec.android.app.samsungapps
,09-16 11:36:08.982  3459  4834 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:08.982 10141 10141 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:08.992 10141 10141 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:08.992 10141 10141 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:09.002 10141 10141 W System  : ClassLoader referenced unknown path: /data/app/com.sec.android.app.samsungapps-1/lib/arm64
,09-16 11:36:09.012 10011 10011 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-16 11:36:09.022  3155  3630 D Netd    : Iface wlan0 link up
09-16 11:36:09.022  3155  3630 D Netd    : Iface wlan0 link up
09-16 11:36:09.022  3155  3630 D Netd    : Iface wlan0 link up
,09-16 11:36:09.022  5051  5346 D PdnController: Interface Changed wlan0 link up
,09-16 11:36:09.022  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 11:36:09.022  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
,09-16 11:36:09.022  5051  5067 D PdnController: Interface Changed wlan0 link up
09-16 11:36:09.022  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 11:36:09.022  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
,09-16 11:36:09.022  5051  5344 D PdnController: Interface Changed wlan0 link up
,09-16 11:36:09.022  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 11:36:09.022  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
,09-16 11:36:09.032 10011 10011 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-16 11:36:09.032 10011 10011 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,09-16 11:36:09.032 10011 10011 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,09-16 11:36:09.032 10141 10141 D InjectionManager: InjectionManager
,09-16 11:36:09.032 10141 10141 D InjectionManager: fillFeatureStoreMap com.sec.android.app.samsungapps
09-16 11:36:09.032 10141 10141 I InjectionManager: Constructor com.sec.android.app.samsungapps, Feature store :{}
09-16 11:36:09.032 10141 10141 I InjectionManager: featureStore :{}
,09-16 11:36:09.042  3459  3858 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 11:36:09.042 10011 10011 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,09-16 11:36:09.052 10011 10011 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,09-16 11:36:09.052 10154 10154 E Zygote  : v2
09-16 11:36:09.052 10154 10154 I libpersona: KNOX_SDCARD checking this for 10012
09-16 11:36:09.052 10154 10154 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:09.052 10011 10011 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-16 11:36:09.052 10011 10011 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-16 11:36:09.052 10154 10154 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:09.052 10011 10011 I wpa_supplicant: Blacklist: Clear (temp) 
09-16 11:36:09.052  3155  3630 D Netd    : Iface wlan0 link up
,09-16 11:36:09.062  5051  5066 D PdnController: Interface Changed wlan0 link up
09-16 11:36:09.062  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 11:36:09.062 10154 10154 E Zygote  : accessInfo : 0
09-16 11:36:09.062  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
09-16 11:36:09.062 10154 10154 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.microsoft.office.onenote.connectionReceiverProcess 
,09-16 11:36:09.062  3459  3979 I ActivityManager: Start proc 10154:com.microsoft.office.onenote.connectionReceiverProcess/u0a12 for broadcast-5 com.microsoft.office.onenote/com.microsoft.bing.datamining.quasar.api.ConnectionChangeReceiver
,09-16 11:36:09.062  3459  3979 I ActivityManager: Killing 9575:com.sec.android.app.shealth/u0a39 (adj 15): DHA:empty #33
,09-16 11:36:09.072  3459  3858 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 11:36:09.072  3459  6177 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-16 11:36:09.082  3459  3858 D WifiNative-wlan0: callSECApiVoid - ID [50]
09-16 11:36:09.082  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:09.092  3459  4386 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,09-16 11:36:09.092 10154 10154 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:09.092 10154 10154 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:09.102  3459  3858 V AlarmManager:  remove PendingIntent] PendingIntent{8ec5fd8: PendingIntentRecord{ae8cf31 android broadcastIntent}}
,09-16 11:36:09.102  3459  3858 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,09-16 11:36:09.102  3459  3459 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-16 11:36:09.102  3459  3459 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-16 11:36:09.102  3459  3858 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-16 11:36:09.102  3459  3867 E ConnectivityService: updateNetworkInfo()
09-16 11:36:09.102  3459  3867 D ConnectivityService: Got NetworkAgent Messenger
09-16 11:36:09.102  3459  3867 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 11:36:09.102  3459  3867 D ConnectivityService: NetworkAgent connected
,09-16 11:36:09.102  3155  3637 D CommandListener: Setting iface cfg
,09-16 11:36:09.102  3459  3459 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-16 11:36:09.102  3459  3865 I WifiHs20Service: Message received 5007
09-16 11:36:09.102  3459  3459 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,09-16 11:36:09.112  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:09.112  4305  4305 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-16 11:36:09.122  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c39a107 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f64198 9831:com.sec.android.diagmonagent/1000}
,09-16 11:36:09.122  9831  9831 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-16 11:36:09.122  9831  9831 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-16 11:36:09.122  9831  9831 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-16 11:36:09.122  9831  9831 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-16 11:36:09.132  3459  4424 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b9f469d u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{603e234 10154:com.microsoft.office.onenote.connectionReceiverProcess/u0a12}
,09-16 11:36:09.142  3459  4380 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c39a107 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{58b9db4 9489:com.enhance.gameservice/u0a111}
,09-16 11:36:09.142  3459  3858 D WifiStateMachine: Start Dhcp Watchdog 2
09-16 11:36:09.142 10154 10154 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:09.142 10154 10154 D RelationGraph: garbageCollect()
09-16 11:36:09.142  3459  3858 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 11:36:09.142 10154 10154 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.microsoft.office.onenote rsrc of package com.microsoft.office.onenote
,09-16 11:36:09.152  3459  3484 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:09.152 10154 10154 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:09.152  3459  3858 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,09-16 11:36:09.152  3459  3867 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
09-16 11:36:09.152 10154 10154 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:09.162  3459  3867 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]
09-16 11:36:09.162  3459  3867 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-16 11:36:09.162 10154 10154 I InjectionManager: Inside getClassLibPath caller 
09-16 11:36:09.162  3459  3974 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c39a107 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{123ea29 9859:com.sec.knox.switcher/1000}
09-16 11:36:09.162  9859  9859 I usagelog: received in receiver
09-16 11:36:09.162  9859  9859 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-16 11:36:09.162  9859  9859 I KnoxUsageLogPro: premStatus:2
,09-16 11:36:09.172 10154 10154 W System  : ClassLoader referenced unknown path: /system/app/OneNote/lib/arm
,09-16 11:36:09.172  9859  9859 I KnoxUsageLogPro: isEulaShown : false
09-16 11:36:09.172  9859  9859 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-16 11:36:09.172  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:09.182  3459  4864 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c39a107 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{603e234 10154:com.microsoft.office.onenote.connectionReceiverProcess/u0a12}
,09-16 11:36:09.192 10154 10154 D InjectionManager: InjectionManager
09-16 11:36:09.192 10154 10154 D InjectionManager: fillFeatureStoreMap com.microsoft.office.onenote
,09-16 11:36:09.192 10154 10154 I InjectionManager: Constructor com.microsoft.office.onenote, Feature store :{}
09-16 11:36:09.192 10154 10154 I InjectionManager: featureStore :{}
,09-16 11:36:09.192  3459  4856 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:09.192 10154 10154 I Process : Sending signal. PID: 10154 SIG: 9
,09-16 11:36:09.212  3459  4536 I ActivityManager: Process com.microsoft.office.onenote.connectionReceiverProcess (pid 10154)(adj 0) has died(60,1769)
,09-16 11:36:09.212  3459  4536 D ActivityManager: isAutoRunBlockedApp:: com.microsoft.office.onenote, Auto Run ON
,09-16 11:36:09.232 10169 10169 E Zygote  : v2
09-16 11:36:09.232 10169 10169 I libpersona: KNOX_SDCARD checking this for 1000
09-16 11:36:09.232 10169 10169 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:09.242 10169 10169 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:09.242 10169 10169 E Zygote  : accessInfo : 0
,09-16 11:36:09.242  3459  3543 I ActivityManager: Start proc 10169:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,09-16 11:36:09.252  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c39a107 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ddcd6b 9894:com.samsung.android.sm.policy/u0a142}
,09-16 11:36:09.262  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:09.262  3459  3858 E WifiNative-wlan0: do suspend false
,09-16 11:36:09.272 10169 10169 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-16 11:36:09.272 10169 10169 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:09.282  3459  3858 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 11:36:09.282  3459  3857 D WifiP2pService: InactiveState{ what=143375 }
09-16 11:36:09.282  3459  3857 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-16 11:36:09.292  3459  4208 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{232ac3 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9b11e91 10169:com.samsung.android.securitylogagent/1000}
,09-16 11:36:09.312 10181 10181 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-16 11:36:09.312 10169 10169 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:09.312 10169 10169 D RelationGraph: garbageCollect()
09-16 11:36:09.312 10181 10181 I dhcpcd  : version 5.5.6 starting
,09-16 11:36:09.312 10169 10169 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package com.samsung.android.securitylogagent
,09-16 11:36:09.322 10181 10181 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-16 11:36:09.322  3459  4856 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:09.322 10169 10169 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:09.322 10169 10169 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:09.332 10169 10169 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:09.332 10169 10169 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,09-16 11:36:09.342 10169 10169 D InjectionManager: InjectionManager
,09-16 11:36:09.342 10169 10169 D InjectionManager: fillFeatureStoreMap com.samsung.android.securitylogagent
09-16 11:36:09.342 10169 10169 I InjectionManager: Constructor com.samsung.android.securitylogagent, Feature store :{}
09-16 11:36:09.342 10169 10169 I InjectionManager: featureStore :{}
,09-16 11:36:09.352  3459  4049 I ActivityManager: Killing 8439:com.samsung.storyservice/5004 (adj 15): DHA:empty #33
,09-16 11:36:09.362  8376  8376 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.storyservice.StoryService
,09-16 11:36:09.372  3459  3483 D ActivityManager: isAutoRunBlockedApp:: com.samsung.storyservice, Auto Run ON
09-16 11:36:09.372  3459  3483 W ActivityManager: Scheduling restart of crashed service com.samsung.storyservice/.StoryService in 1000ms
,09-16 11:36:09.392 10181 10181 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-16 11:36:09.392 10181 10181 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-16 11:36:09.392 10181 10181 I dhcpcd  : bssid match
,09-16 11:36:09.402 10181 10181 I dhcpcd  : wlan0: rebinding lease of 192.168.1.107
,09-16 11:36:09.442  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:09.452 10181 10181 I dhcpcd  : wlan0: acknowledged 192.168.1.107 from 192.168.1.1
,09-16 11:36:09.502 10181 10181 I dhcpcd  : wlan0: leased 192.168.1.107 for 172800 seconds
,09-16 11:36:09.512  3459  3867 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,09-16 11:36:09.542  3459  4834 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-16 11:36:09.552  3459  4834 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-16 11:36:09.552  3459  4834 D WifiService: setWifiEnabled: false pid=9697, uid=10177
,09-16 11:36:09.552  3459  4834 D SettingsProvider: isChangeAllowed() : name = wifi_on
,09-16 11:36:09.562  3459  3861 D WifiController: [FCC]setFccChannel() is called !!!
,09-16 11:36:09.562  3459  3861 D WifiStateMachine: setFccChannel: channel = 0
09-16 11:36:09.562  3459  3861 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
09-16 11:36:09.562  3459  3861 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
,09-16 11:36:09.562  3459  3861 D SecContentProvider: insert(), uri = 2
,09-16 11:36:09.562  3459  3858 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-16 11:36:09.562  3459  3858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-16 11:36:09.582  3459  3858 D WifiBigDataLog: init : 
,09-16 11:36:09.582  3459  3858 D WifiStateMachine: setFccChannelNative: channel = 0
,09-16 11:36:09.582  3459  3858 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-16 11:36:09.592  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ce061f6 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
09-16 11:36:09.592  3459  3858 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 11:36:09.592  3459  3858 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 11:36:09.592  3459  3858 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
09-16 11:36:09.592  3459  3858 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,09-16 11:36:09.592  3459  3858 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
09-16 11:36:09.592  3459  3858 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-16 11:36:09.592  3459  3858 E WifiNative-wlan0: do suspend true
09-16 11:36:09.592  3949  4129 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:09.602  3949  4129 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,09-16 11:36:09.612  3459  3857 D WifiP2pService: InactiveState{ what=143375 }
,09-16 11:36:09.612  3459  3857 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-16 11:36:09.612  3155  3637 D CommandListener: Clearing all IP addresses on wlan0
,09-16 11:36:09.622  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:09.622  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:09.632  3459  3867 E ConnectivityService: updateNetworkInfo()
09-16 11:36:09.632  3459  3867 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]
09-16 11:36:09.632  3459  3867 E ConnectivityService: updateNetworkInfo()
09-16 11:36:09.632  3459  3867 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
09-16 11:36:09.632  3459  3867 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 11:36:09.632  3459  3867 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-16 11:36:09.632  3459  3867 V NetworkStats: updateIfacesLocked()
09-16 11:36:09.632  3459  3867 V NetworkStats: performPollLocked(flags=0x1)
,09-16 11:36:09.632  3459  3459 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-16 11:36:09.632  3459  3867 V NetworkStats: performPollLocked() took 5ms
09-16 11:36:09.632  3459  3867 D NtpTrustedTime: currentTimeMillis() cache hit
,09-16 11:36:09.632  3459  3459 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-16 11:36:09.632  3459  3459 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
,09-16 11:36:09.632  3459  3459 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid
09-16 11:36:09.632  3459  3459 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
09-16 11:36:09.632  3459  3459 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-16 11:36:09.632  3459  3865 I WifiHs20Service: Message received 5007
,09-16 11:36:09.642  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:09.642  4305  4305 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-16 11:36:09.652  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a6d9f7 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f64198 9831:com.sec.android.diagmonagent/1000}
,09-16 11:36:09.652  9831  9831 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-16 11:36:09.652  3459  3867 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-16 11:36:09.652  9831  9831 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
09-16 11:36:09.652  9831  9831 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
09-16 11:36:09.652  3459  3867 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]
09-16 11:36:09.652  3459 10166 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-16 11:36:09.652  3459  3867 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-16 11:36:09.652  3459 10166 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Disconnected - quitting
09-16 11:36:09.652  3459  3857 D WifiP2pService: InactiveState{ what=131204 }
09-16 11:36:09.652  3459 10166 D NetworkMonitor: unregisterReceiver Captive portal receiver
,09-16 11:36:09.652  3459  3867 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=false
09-16 11:36:09.652  9831  9831 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
09-16 11:36:09.652  3459  3857 D WifiP2pService: P2pEnabledState{ what=131204 }
09-16 11:36:09.652  3459 10166 E NetworkMonitor: IllegalArgumentException: java.lang.IllegalArgumentException: Receiver not registered: com.android.server.connectivity.NetworkMonitor$1@eb812cd
09-16 11:36:09.652  3459  3857 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-16 11:36:09.652  3459 10166 W System.err: java.lang.IllegalArgumentException: Receiver not registered: com.android.server.connectivity.NetworkMonitor$1@eb812cd
09-16 11:36:09.652  3459  3867 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '77 network destroy 503' failed with '400 77 destroyNetwork() failed (Machine is not on the network)'
09-16 11:36:09.652  3459 10166 W System.err: 	at android.app.LoadedApk.forgetReceiverDispatcher(LoadedApk.java:878)
09-16 11:36:09.652  3459  3867 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
09-16 11:36:09.652  3459 10166 W System.err: 	at android.app.ContextImpl.unregisterReceiver(ContextImpl.java:1279)
09-16 11:36:09.652  3459  3867 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
09-16 11:36:09.652  3459 10166 W System.err: 	at com.android.server.connectivity.NetworkMonitor$DefaultState.processMessage(NetworkMonitor.java:380)
09-16 11:36:09.662  3459  3459 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
09-16 11:36:09.652 10011 10011 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
09-16 11:36:09.662  3459  3459 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,09-16 11:36:09.652  3459 10166 W System.err: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:968)
09-16 11:36:09.652 10011 10011 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
09-16 11:36:09.652  3459 10166 W System.err: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:791)
09-16 11:36:09.652  3459 10166 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:36:09.652  3459 10166 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-16 11:36:09.652  3459 10166 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 11:36:09.652  3155  3637 E Netd    : no such netId 503
09-16 11:36:09.652  3459  3867 D ConnectivityService: nai.networkMonitor.doQuit()
09-16 11:36:09.652  3459  3867 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: doQuit - quitNow()
09-16 11:36:09.652  3459  3867 E ConnectivityService: updateNetworkInfo()
,09-16 11:36:09.652  3459  3858 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-16 11:36:09.652  3459  3459 D RttService: SCAN_AVAILABLE : 1
09-16 11:36:09.652  4165  4177 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=84]
09-16 11:36:09.652  3459  3891 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-16 11:36:09.652  4165  4165 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 11:36:09.652  4165  4165 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 11:36:09.652  3459  3856 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 11:36:09.652  4165  4165 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,09-16 11:36:09.652  3459  3856 D NtpTrustedTime: currentTimeMillis() cache hit
09-16 11:36:09.652  4165  4165 I PeopleDataManager: removeNotification
09-16 11:36:09.652  4165  4165 I NotificationParser: getNotiType:android,null
09-16 11:36:09.652  4165  4165 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 11:36:09.652  4165  4165 D PeopleDataManager: removeNotiInfo =null
09-16 11:36:09.662  4165  7324 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
09-16 11:36:09.662  4165  4165 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 11:36:09.662  4165  4165 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 11:36:09.662  4165  4165 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 11:36:09.662  4165  4165 I PeopleDataManager: removeNotification
09-16 11:36:09.662  4165  4165 I NotificationParser: getNotiType:android,null
,09-16 11:36:09.662  4165  4165 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 11:36:09.662  4165  4165 D PeopleDataManager: removeNotiInfo =null
,09-16 11:36:09.672  3459  4424 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a6d9f7 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{58b9db4 9489:com.enhance.gameservice/u0a111}
,09-16 11:36:09.682  3459  3571 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:09.682  3459  3571 I WifiDisplayAdapter: onP2pDisconnected
09-16 11:36:09.682  3459  3571 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-16 11:36:09.682  3459  3571 D IpRemoteDisplayController: WfdBridgeServer is already null
09-16 11:36:09.682  3949  3949 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-16 11:36:09.682  3459  4424 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a6d9f7 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{123ea29 9859:com.sec.knox.switcher/1000}
,09-16 11:36:09.682  9859  9859 I usagelog: received in receiver
09-16 11:36:09.682  9859  9859 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-16 11:36:09.682  9859  9859 I KnoxUsageLogPro: premStatus:2
,09-16 11:36:09.692  9859  9859 I KnoxUsageLogPro: isEulaShown : false
,09-16 11:36:09.692  9859  9859 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-16 11:36:09.692  3459  3857 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-16 11:36:09.692  3459  3867 E ConnectivityService: updateNetworkInfo()
09-16 11:36:09.692  3459  3459 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-16 11:36:09.692  3459  3867 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
09-16 11:36:09.692  3459  3571 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-16 11:36:09.692  3459  3571 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
09-16 11:36:09.692  3459  3571 D WifiDisplayController: disconnect
,09-16 11:36:09.692  3459  3571 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-16 11:36:09.702  3459  3857 D SecContentProvider: insert(), uri = 2
09-16 11:36:09.702  3949  3949 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-16 11:36:09.702  3459  3857 D WifiP2pService: P2pDisablingState
09-16 11:36:09.702  3459  3857 D SecContentProvider: insert(), uri = 2
09-16 11:36:09.702  3459  3857 D WifiP2pService: P2pDisablingState{ what=147458 }
,09-16 11:36:09.702  3949  3949 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-16 11:36:09.702  3459  3857 D WifiP2pService: p2p socket connection lost
09-16 11:36:09.702  3459  3858 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-16 11:36:09.702  3459  3857 D WifiP2pService: P2pDisabledState
09-16 11:36:09.702  3459  3858 E WifiNative-wlan0: do suspend true
09-16 11:36:09.702  3949  3949 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-16 11:36:09.712  3459  4208 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-16 11:36:09.712  3949  3949 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-16 11:36:09.712  3459  3571 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
,09-16 11:36:09.712  3949  3949 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-16 11:36:09.712  3459  3571 I WifiDisplayAdapter: onP2pDisconnected
,09-16 11:36:09.712  3459  3571 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-16 11:36:09.712  3459  3571 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-16 11:36:09.722  3459  3857 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-16 11:36:09.732  3459  3857 D WifiP2pService: DefaultState{ what=143375 }
,09-16 11:36:09.732  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a6d9f7 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ddcd6b 9894:com.samsung.android.sm.policy/u0a142}
,09-16 11:36:09.732  3459  4416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1a8a782 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{595a174 9910:com.samsung.android.app.FileShareClient/5005}
,09-16 11:36:09.742  9910  9910 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-16 11:36:09.742  9910  9910 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-16 11:36:09.742  9910  9910 D FileShare-Client: Outbound.stopDelayTimer - 
,09-16 11:36:09.742  3155  3637 D CommandListener: Clearing all IP addresses on wlan0
,09-16 11:36:09.752 10205 10205 E Zygote  : v2
,09-16 11:36:09.752 10205 10205 I libpersona: KNOX_SDCARD checking this for 10012
09-16 11:36:09.752 10205 10205 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:09.752 10205 10205 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 11:36:09.752  3459  3543 I ActivityManager: Start proc 10205:com.microsoft.office.onenote.connectionReceiverProcess/u0a12 for broadcast-5 com.microsoft.office.onenote/com.microsoft.bing.datamining.quasar.api.ConnectionChangeReceiver
,09-16 11:36:09.762 10205 10205 E Zygote  : accessInfo : 0
,09-16 11:36:09.762 10205 10205 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.microsoft.office.onenote.connectionReceiverProcess 
,09-16 11:36:09.762  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:09.772  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1a8a782 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b1ac55 9922:com.samsung.android.app.FileShareServer/5005}
,09-16 11:36:09.772  3459  3858 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-16 11:36:09.772 10011 10011 I wpa_supplicant: Blacklist: Clear (all) 
09-16 11:36:09.772 10011 10011 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,09-16 11:36:09.772  3459  3459 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-16 11:36:09.772  3459  3459 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
09-16 11:36:09.772  3459  3459 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
09-16 11:36:09.772  3459  3459 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
09-16 11:36:09.772  3459  3459 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
09-16 11:36:09.772  3459  3865 I WifiHs20Service: Message received 5007
,09-16 11:36:09.782  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:09.782  4305  4305 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,09-16 11:36:09.782  9922  9922 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-16 11:36:09.782  9922  9922 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-16 11:36:09.792  3459  3858 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,09-16 11:36:09.792  9922  9922 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-16 11:36:09.802  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:09.802  3459  3459 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,09-16 11:36:09.802  3459  3459 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,09-16 11:36:09.802  3459  3865 I WifiHs20Service: Message received 5011
,09-16 11:36:09.802  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 11:36:09.802  3459  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-16 11:36:09.812  3949  3949 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,09-16 11:36:09.812  3459  3459 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,09-16 11:36:09.812  4305  4322 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,09-16 11:36:09.812 10205 10205 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:09.812 10205 10205 D ActivityThread: Added TimaKeyStore provider
09-16 11:36:09.812  4305  4322 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,09-16 11:36:09.822  3459  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-16 11:36:09.822  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:09.822  3459  3459 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
09-16 11:36:09.822  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:36:09.822  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:09.822  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:09.822  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:36:09.822  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:36:09.822  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:36:09.822  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:36:09.822  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:36:09.822  3459  3459 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
09-16 11:36:09.822  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:09.822  9697  9697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:36:09.832  4165  4180 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
09-16 11:36:09.832  4165  4165 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 11:36:09.832  4165  4165 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 11:36:09.832  4165  4165 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 11:36:09.832  4165  4165 I PeopleDataManager: removeNotification
09-16 11:36:09.832  4165  4165 I NotificationParser: getNotiType:android,null
09-16 11:36:09.832  4165  4165 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 11:36:09.832  4165  4165 D PeopleDataManager: removeNotiInfo =null
,09-16 11:36:09.832  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:09.832  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:36:09.832  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:09.832  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:09.832  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:36:09.832  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:36:09.832  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:36:09.832  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:36:09.832  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:36:09.832  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:09.832  9697  9697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:36:09.832  3155  3630 D Netd    : Iface p2p0 link up
09-16 11:36:09.832 10011 10011 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-16 11:36:09.832 10011 10011 I wpa_supplicant: wlan0: CTRL-EVENT-BIGDATA-DISCONNECT 2 12 3 3 f4:f2:6d 2437 20 -47 144 2 1 0 0 35 -92 0 0
09-16 11:36:09.832 10011 10011 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-16 11:36:09.842  5051  5067 D PdnController: Interface Changed p2p0 link up
09-16 11:36:09.842  3459  3546 D Tethering: interfaceLinkStateChanged p2p0, true
09-16 11:36:09.842  3459  3546 D Tethering: interfaceStatusChanged p2p0, true
,09-16 11:36:09.842  3459  3858 D WifiBigDataLog: getJsonFormat() - feature : DISC
,09-16 11:36:09.842  3459  3858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-16 11:36:09.842  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-16 11:36:09.842  3459  3484 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8651e93 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f64198 9831:com.sec.android.diagmonagent/1000}
,09-16 11:36:09.842  3949  3949 I HotspotTile: Provider is not defined returning false
09-16 11:36:09.842  3155  3630 D Netd    : Iface wlan0 link up
09-16 11:36:09.852  3949  3949 D HotspotTile: onReceive : 0, 0
,09-16 11:36:09.852  5051  5344 D PdnController: Interface Changed wlan0 link up
09-16 11:36:09.852  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 11:36:09.852  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
,09-16 11:36:09.852  9831  9831 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,09-16 11:36:09.852  3459  3858 D WifiBigDataLog: init : 
09-16 11:36:09.852  9831  9831 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,09-16 11:36:09.862  9831  9831 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-16 11:36:09.862  3459  3979 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{3a6d9f7 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b10fed0 10205:com.microsoft.office.onenote.connectionReceiverProcess/u0a12}
,09-16 11:36:09.872  3459  4208 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8651e93 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{58b9db4 9489:com.enhance.gameservice/u0a111}
,09-16 11:36:09.882 10205 10205 D RelationGraph: garbageCollect()
09-16 11:36:09.882 10205 10205 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:09.882 10205 10205 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in com.microsoft.office.onenote rsrc of package com.microsoft.office.onenote
,09-16 11:36:09.892  3459  3979 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:09.892 10205 10205 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:09.892  3459  4208 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8651e93 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{123ea29 9859:com.sec.knox.switcher/1000}
,09-16 11:36:09.892  9859  9859 I usagelog: received in receiver
09-16 11:36:09.892  9859  9859 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
09-16 11:36:09.892  9859  9859 I KnoxUsageLogPro: premStatus:2
09-16 11:36:09.892  9859  9859 I KnoxUsageLogPro: isEulaShown : false
09-16 11:36:09.892  9859  9859 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,09-16 11:36:09.892 10205 10205 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:09.892  3459 10167 V AlarmManager:  remove PendingIntent] PendingIntent{8c00ec9: PendingIntentRecord{1c79ed7 android broadcastIntent}}
,09-16 11:36:09.902  3459  4208 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8651e93 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b10fed0 10205:com.microsoft.office.onenote.connectionReceiverProcess/u0a12}
,09-16 11:36:09.912 10205 10205 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:09.912 10205 10205 W System  : ClassLoader referenced unknown path: /system/app/OneNote/lib/arm
,09-16 11:36:09.922 10205 10205 D InjectionManager: InjectionManager
09-16 11:36:09.922 10205 10205 D InjectionManager: fillFeatureStoreMap com.microsoft.office.onenote
09-16 11:36:09.922 10205 10205 I InjectionManager: Constructor com.microsoft.office.onenote, Feature store :{}
09-16 11:36:09.922 10205 10205 I InjectionManager: featureStore :{}
,09-16 11:36:09.932  3459  4536 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:09.932 10205 10205 I Process : Sending signal. PID: 10205 SIG: 9
,09-16 11:36:09.952 10011 10011 I wpa_supplicant: Blacklist: Clear (all) 
,09-16 11:36:09.952 10011 10011 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-16 11:36:09.952  3459  4386 I ActivityManager: Process com.microsoft.office.onenote.connectionReceiverProcess (pid 10205)(adj 0) has died(63,1769)
,09-16 11:36:09.952  3459  4386 D ActivityManager: isAutoRunBlockedApp:: com.microsoft.office.onenote, Auto Run ON
,09-16 11:36:09.972  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8651e93 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ddcd6b 9894:com.samsung.android.sm.policy/u0a142}
,09-16 11:36:09.982  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:09.982  3459  4049 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9cf37fc u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ddeaba 9697:com.test.thalitest/u0a177},
09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:09.982  3459  4834 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:09.992  3459  3483 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9cf37fc u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9b11e91 10169:com.samsung.android.securitylogagent/1000}
,09-16 11:36:10.002  3155  3630 D Netd    : Iface wlan0 link up
,09-16 11:36:10.002  3155  3630 D Netd    : Iface wlan0 link up
,09-16 11:36:10.002  5051  5066 D PdnController: Interface Changed wlan0 link up
,09-16 11:36:10.002  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 11:36:10.002  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
09-16 11:36:10.002  5051  5346 D PdnController: Interface Changed wlan0 link up
09-16 11:36:10.002  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, true
09-16 11:36:10.002  3459  3546 D Tethering: interfaceStatusChanged wlan0, true
,09-16 11:36:10.012  3155  3630 D Netd    : Iface p2p0 link down
,09-16 11:36:10.012  5051  5067 D PdnController: Interface Changed p2p0 link down
,09-16 11:36:10.012  3459  4864 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{931ce85 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
09-16 11:36:10.012  3459  3546 D Tethering: interfaceLinkStateChanged p2p0, false
09-16 11:36:10.012  3459  3546 D Tethering: interfaceStatusChanged p2p0, false
,09-16 11:36:10.162  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:10.342  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:10.392 10224 10224 E Zygote  : v2
09-16 11:36:10.392 10224 10224 I libpersona: KNOX_SDCARD checking this for 5004
09-16 11:36:10.392 10224 10224 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:10.392 10224 10224 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:10.402 10224 10224 E Zygote  : accessInfo : 0
09-16 11:36:10.402 10224 10224 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.storyservice 
09-16 11:36:10.402  3459  3543 I ActivityManager: Start proc 10224:com.samsung.storyservice/5004 for service com.samsung.storyservice/.StoryService
,09-16 11:36:10.432 10224 10224 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:10.432 10224 10224 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:10.462 10224 10224 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:10.462 10224 10224 D RelationGraph: garbageCollect()
,09-16 11:36:10.462 10224 10224 W ResourcesManager: getTopLevelResources: /system/priv-app/StoryService/StoryService.apk / 1.0 running in com.samsung.storyservice rsrc of package com.samsung.storyservice
,09-16 11:36:10.472  3459  4856 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:10.472 10224 10224 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:10.472 10224 10224 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:10.482 10224 10224 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:10.502 10224 10224 W System  : ClassLoader referenced unknown path: /system/priv-app/StoryService/lib/arm64
,09-16 11:36:10.512  9843  9843 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
09-16 11:36:10.512 10224 10224 I StoryServiceApplication: [#CMH#] StoryService started with context  com.samsung.storyservice.StoryServiceApplication@ceebefc
,09-16 11:36:10.522  3459  4864 I ActivityManager: Killing 8402:com.samsung.enhanceservice/5004 (adj 15): DHA:empty #33
,09-16 11:36:10.522  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:10.532 10224 10224 D InjectionManager: InjectionManager
,09-16 11:36:10.532 10224 10224 D InjectionManager: fillFeatureStoreMap com.samsung.storyservice
,09-16 11:36:10.542 10224 10224 I InjectionManager: Constructor com.samsung.storyservice, Feature store :{}
,09-16 11:36:10.542 10224 10224 I InjectionManager: featureStore :{}
,09-16 11:36:10.542 10224 10224 I StoryService: [StoryService] onBind() 
,09-16 11:36:10.542  8376  8376 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.enhanceservice.EnhanceService
,09-16 11:36:10.552  3459  3979 D ActivityManager: isAutoRunBlockedApp:: com.samsung.enhanceservice, Auto Run ON
09-16 11:36:10.552  3459  3979 W ActivityManager: Scheduling restart of crashed service com.samsung.enhanceservice/.EnhanceService in 1000ms
,09-16 11:36:10.562  3155  3630 D Netd    : Iface wlan0 link down
,09-16 11:36:10.562  5051  5346 D PdnController: Interface Changed wlan0 link down
09-16 11:36:10.562  3459  3546 D Tethering: interfaceLinkStateChanged wlan0, false
09-16 11:36:10.562  3459  3546 D Tethering: interfaceStatusChanged wlan0, false
,09-16 11:36:10.562 10011 10011 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 11:36:10.582  3459  3483 D RCPManagerService: exchangeData() failure , invalid userId
,09-16 11:36:10.592 10224 10224 I RelationshipCollage: [StoryService] Final selection statement for relationship collage creation  scene_names like '%People%'
,09-16 11:36:10.602 10224 10224 I SimilarityCollage: [StoryService] Final selection statement for Similarity collage creation  scene_names like '%People%'
,09-16 11:36:10.602 10224 10224 I ServiceController: [StoryService] initialize ContentObserver  
,09-16 11:36:10.632  3459  4412 I ActivityManager: Killing 9604:com.samsung.faceservice/5004 (adj 15): DHA:empty #33
,09-16 11:36:10.642  8376  8376 I ServiceManager: [#CMH#] Bound to Package  com.samsung.storyservice
,09-16 11:36:10.652 10224 10224 I ServiceController: [StoryService] Sending response for  31 with status 0
,09-16 11:36:10.662  3459  3858 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-16 11:36:10.672  3459  3459 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,09-16 11:36:10.672  3459  3459 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
09-16 11:36:10.672  3459  3459 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,09-16 11:36:10.672  4165  4177 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
09-16 11:36:10.672  8376  8376 I ServiceManager: [#CMH#] Disconnected to Service  com.samsung.faceservice.FaceService
09-16 11:36:10.672  4165  4165 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
09-16 11:36:10.672  4165  4165 I PeopleStripeService: PeopleNotificationReceiver:3
09-16 11:36:10.672  4165  4165 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 11:36:10.672  4165  4165 I PeopleDataManager: removeNotification
09-16 11:36:10.672  4165  4165 I NotificationParser: getNotiType:android,null
09-16 11:36:10.672  4165  4165 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 11:36:10.672  4165  4165 D PeopleDataManager: removeNotiInfo =null
,09-16 11:36:10.672  4165  7324 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041473,extra=Bundle[mParcelledData.dataSize=84]
,09-16 11:36:10.672  4165  4165 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041473, samsung.notification.type=normal, samsung.people.package_name=android}]
,09-16 11:36:10.672  4165  4165 I PeopleStripeService: PeopleNotificationReceiver:3
,09-16 11:36:10.672  4165  4165 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
09-16 11:36:10.672  4165  4165 I PeopleDataManager: removeNotification
09-16 11:36:10.672  4165  4165 I NotificationParser: getNotiType:android,null
,09-16 11:36:10.682  4165  4165 D PeopleDataManager: removeNotiInfo: id =17041473,packageName=android,isEdgeNotification=false,key=null,removeAll=false
09-16 11:36:10.682  4165  4165 D PeopleDataManager: removeNotiInfo =null
09-16 11:36:10.682  3459  3459 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
09-16 11:36:10.682  3459  3862 D HS20StateMachine: WIFI_STATE_DISABLED
09-16 11:36:10.682  3459  3459 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
09-16 11:36:10.682  3459  3862 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
09-16 11:36:10.682  3459  3862 D HS20StateMachine: enter : DisablingState
09-16 11:36:10.682  3459  3865 I WifiHs20Service: Message received 5011
09-16 11:36:10.682  3459  3864 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
09-16 11:36:10.682  3459  3862 D HS20StateMachine: enter : DisabledState
,09-16 11:36:10.682  3459  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,09-16 11:36:10.682  3459  3459 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,09-16 11:36:10.682  3949  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-16 11:36:10.682  4305  4632 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
09-16 11:36:10.682  4305  4632 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
09-16 11:36:10.682  3949  3949 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-16 11:36:10.682  3949  3949 I HotspotTile: Provider is not defined returning false
,09-16 11:36:10.692  3459  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,09-16 11:36:10.692  3949  3949 D HotspotTile: onReceive : 1, 0
,09-16 11:36:10.702  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:10.702  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:10.702  4271  4923 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 11:36:10.702  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:10.702  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{545ce01 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ddeaba 9697:com.test.thalitest/u0a177}
09-16 11:36:10.702  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:10.702  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:10.702  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:10.702  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:10.702  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:10.702  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:10.702  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:10.712  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:10.712  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:10.712  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:10.712  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:10.712  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 11:36:10.712  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:10.712  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:10.712  3459  4864 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:10.712  3459  4053 D ActivityManager: isAutoRunBlockedApp:: com.samsung.faceservice, Auto Run ON
,09-16 11:36:10.712  3459  4053 W ActivityManager: Scheduling restart of crashed service com.samsung.faceservice/.FaceService in 10841ms
,09-16 11:36:10.732  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{545ce01 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9b11e91 10169:com.samsung.android.securitylogagent/1000}
,09-16 11:36:10.872  3459  3858 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-16 11:36:10.882  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:11.062  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:11.242  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:11.422  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:11.592 10240 10240 E Zygote  : v2
09-16 11:36:11.592 10240 10240 I libpersona: KNOX_SDCARD checking this for 5004
09-16 11:36:11.592 10240 10240 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:11.592 10240 10240 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:11.592  3459  3543 I ActivityManager: Start proc 10240:com.samsung.enhanceservice/5004 for service com.samsung.enhanceservice/.EnhanceService
09-16 11:36:11.592 10240 10240 E Zygote  : accessInfo : 0
,09-16 11:36:11.592 10240 10240 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.enhanceservice 
,09-16 11:36:11.602  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:11.632 10240 10240 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:11.632 10240 10240 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:11.662 10240 10240 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:11.662 10240 10240 D RelationGraph: garbageCollect()
,09-16 11:36:11.662 10240 10240 W ResourcesManager: getTopLevelResources: /system/priv-app/EnhanceService/EnhanceService.apk / 1.0 running in com.samsung.enhanceservice rsrc of package com.samsung.enhanceservice
,09-16 11:36:11.672  3459  4834 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:11.672 10240 10240 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:11.672 10240 10240 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:11.682 10240 10240 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:11.692 10240 10240 W System  : ClassLoader referenced unknown path: /system/priv-app/EnhanceService/lib/arm64
,09-16 11:36:11.692 10240 10240 D InjectionManager: InjectionManager
,09-16 11:36:11.692 10240 10240 D InjectionManager: fillFeatureStoreMap com.samsung.enhanceservice
09-16 11:36:11.692 10240 10240 I InjectionManager: Constructor com.samsung.enhanceservice, Feature store :{}
09-16 11:36:11.692 10240 10240 I InjectionManager: featureStore :{}
,09-16 11:36:11.702 10240 10240 I EnhanceService: [EnhanceService] onbind () called 
,09-16 11:36:11.712  8376  8376 I ServiceManager: [#CMH#] Bound to Package  com.samsung.enhanceservice,
09-16 11:36:11.722  3459  3979 I ActivityManager: Killing 8376:com.samsung.cmh:CMH/5004 (adj 15): DHA:empty #33
,09-16 11:36:11.722 10240 10240 I EnhanceService: [EnhanceService] onSetResponseHandler () called 
,09-16 11:36:11.742  3459  4049 E GameManagerService: remoteCallback died, callback: com.samsung.android.game.IGameManagerCallback$Stub$Proxy@340493d, cookie: null
,09-16 11:36:11.752 10240 10240 I EnhanceService: [EnhanceService] onDestroy () called 
,09-16 11:36:11.762  9646  9646 I DCMServiceController: [#CMH#] shutdown () called 
,09-16 11:36:11.762 10224 10224 I StoryService: [StoryService] On destroy() 
09-16 11:36:11.762 10224 10224 I ServiceController: [StoryService] shutdown() 
,09-16 11:36:11.772  3459  3483 D ActivityManager: isAutoRunBlockedApp:: com.samsung.cmh, Auto Run ON
,09-16 11:36:11.772  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:11.852  3459  6141 D SSRM:n  : SIOP:: AP = 330, PST = 300 (W:14), CP = 257, CUR = -102, LCD = 1
,09-16 11:36:11.962  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:12.142  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:12.322  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:12.502  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:12.562  9697  9762 D BluetoothAdapter: enable()
,09-16 11:36:12.572  3459  4380 W ActivityManager: Permission Denial: getCurrentUser() from pid=9697, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
,09-16 11:36:12.572  3459  4380 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-16 11:36:12.572  3459  4380 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9697, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
09-16 11:36:12.572  3459  4380 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28247)
09-16 11:36:12.572  3459  4380 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
09-16 11:36:12.572  3459  4380 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
09-16 11:36:12.572  3459  4380 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
09-16 11:36:12.572  3459  4380 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
09-16 11:36:12.572  3459  4380 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
,09-16 11:36:12.572  3459  4380 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-16 11:36:12.572  3459  4380 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,09-16 11:36:12.582  3459  4380 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,09-16 11:36:12.672  9949  9949 D BluetoothAdapterState: make() - Creating AdapterState
,09-16 11:36:12.682  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:12.682  9949  9949 I bt_bluedroid: init
,09-16 11:36:12.682  9949 10254 I BluetoothAdapterState: Entering OffState
,09-16 11:36:12.692  9949 10255 E bt_core_counter: counter_init unable to open counter port
09-16 11:36:12.692  9949 10255 E bt_core_module: module_init failed to initialize "counter_module"
09-16 11:36:12.692  9949 10255 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-16 11:36:12.692  9949 10255 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-16 11:36:12.692  9949 10255 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-16 11:36:12.692  9949 10255 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-16 11:36:12.692  9949  9949 I bt_bluedroid: get_profile_interface socket
09-16 11:36:12.692  9949  9949 W bt_btif : btif_get_adapter_property 2
,09-16 11:36:12.692  9949  9949 W bt_btif : btif_get_adapter_property 1
,09-16 11:36:12.692  9949 10258 D BluetoothAdapterProperties: Address is:A8:81:95:E9:5F:6F
09-16 11:36:12.692  9949 10258 E BluetoothServiceJni: populateRssiValuesNative
,09-16 11:36:12.692  9949 10258 I bt_bluedroid: getModelRssiValues
09-16 11:36:12.692  9949 10258 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
09-16 11:36:12.692  9949 10258 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,09-16 11:36:12.702  9949  9949 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-16 11:36:12.702  9949 10258 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7 edge
,09-16 11:36:12.702  3459  3459 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,09-16 11:36:12.702  9949  9949 I bt_bluedroid: get_profile_interface sdp
,09-16 11:36:12.712  9949  9959 I bt_bluedroid: config_hci_snoop_log
,09-16 11:36:12.712  3459  3570 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-16 11:36:12.722  9949 10254 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,09-16 11:36:12.732  9949 10254 D BluetoothAdapterProperties: Setting state to 14
,09-16 11:36:12.732  9949 10254 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-16 11:36:12.732  9949 10254 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-16 11:36:12.732  9949 10254 D BluetoothAdapterService: updateAdapterState state is 14
09-16 11:36:12.732  9949 10254 D BluetoothAdapterService: Autoconnection is available 
09-16 11:36:12.732  3459  3570 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
09-16 11:36:12.732  9949 10254 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
,09-16 11:36:12.732  9949 10254 D BluetoothSecureManager: getInstant: null
,09-16 11:36:12.732  9949 10254 D BluetoothSecureManager: calling getMethod for getService
09-16 11:36:12.732  9949 10254 D BluetoothSecureManager: calling getService
09-16 11:36:12.732  9949 10254 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@e4f3432
,09-16 11:36:12.732  3459  4834 D BluetoothSecureManagerService: isSecureModeEnabled
,09-16 11:36:12.732  3459  4834 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-16 11:36:12.732  9949 10254 D BtConfig.SecureMode: isSecureModeOn:false
09-16 11:36:12.732  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-16 11:36:12.742  9949 10254 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-16 11:36:12.742  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-16 11:36:12.742  9949 10254 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-16 11:36:12.742  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-16 11:36:12.742  9949 10254 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,09-16 11:36:12.742  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-16 11:36:12.742  9949 10254 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-16 11:36:12.742  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-16 11:36:12.742  9949 10254 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-16 11:36:12.742  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-16 11:36:12.742  9949 10254 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,09-16 11:36:12.742  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-16 11:36:12.742  9949 10254 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-16 11:36:12.742  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,09-16 11:36:12.742  9949 10254 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
09-16 11:36:12.742  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-16 11:36:12.752  9949 10254 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,09-16 11:36:12.752  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-16 11:36:12.752  9949 10254 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,09-16 11:36:12.752  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,09-16 11:36:12.752  9949 10254 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.bleaudio.BleAudioService
,09-16 11:36:12.752  9949 10254 D BluetoothBondStateMachine: make
,09-16 11:36:12.752  9949 10259 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 11:36:12.772  9949 10254 I BluetoothAdapterState: Entering PendingCommandState
,09-16 11:36:12.772  9949  9949 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
,09-16 11:36:12.772  9949  9949 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 11:36:12.772  9949  9949 D BtGatt.GattService: Received start request. Starting profile...
,09-16 11:36:12.772  9949  9949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c0f901
09-16 11:36:12.772  9949  9949 D BtGatt.GattService: start()
09-16 11:36:12.772  9949  9949 I bt_bluedroid: get_profile_interface gatt
,09-16 11:36:12.782  9949  9949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c0f901
09-16 11:36:12.782  9949  9949 D BtGatt.AdvertiseManager: advertise manager created
,09-16 11:36:12.782  9949  9949 D BtGatt.AdvertiseManager: start
,09-16 11:36:12.792  9949  9949 D BtGatt.ScanManager: start
,09-16 11:36:12.792  9949  9949 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,09-16 11:36:12.812  9949  9949 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
,09-16 11:36:12.812  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
09-16 11:36:12.812  9949  9949 E BtGatt.GattService: notifyProfileServiceStateChanged
09-16 11:36:12.812  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 11:36:12.812  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
,09-16 11:36:12.812  9949  9949 V BluetoothAdapterState: isTurningOff()=false
09-16 11:36:12.812  9949  9949 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:12.812  9949  9949 V BluetoothAdapterState: isBleTurningOn()=true
09-16 11:36:12.812  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:12.812  9949 10254 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,09-16 11:36:12.822  9949 10254 I bt_bluedroid: bt_bluedroid
09-16 11:36:12.822  9949 10255 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-16 11:36:12.822  9949 10255 I bt_hci  : start_up
,09-16 11:36:12.832  9949 10255 I bt_vendor: alloc value 0xf36c9169
09-16 11:36:12.832  9949 10255 I bt_vendor: init
,09-16 11:36:12.832  9949 10255 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-16 11:36:12.832  9949 10255 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
09-16 11:36:12.832  9949 10255 I bt_upio : upio_set_bluetooth_power(on: 0)
,09-16 11:36:12.832  9949 10255 I bt_upio : upio_set_bluetooth_power(on: 1)
,09-16 11:36:12.832  3459  4152 E Watchdog: !@Sync 8 [09-16 11:36:12.839]
,09-16 11:36:12.852  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:12.942  9949 10255 D bt_hci  : start_up starting async portion
,09-16 11:36:12.942  9949 10271 I bt_hci  : event_finish_startup
09-16 11:36:12.942  9949 10271 I bt_hci_h4: hal_open
09-16 11:36:12.942  9949 10271 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
,09-16 11:36:12.942  9949 10271 I bt_userial_vendor: userial_vendor_open():UART is setup
,09-16 11:36:12.942  9949 10271 I bt_userial_vendor: device fd = 61 open
09-16 11:36:12.942  9949 10271 E bt_hwcfg: Start CFG HW, HCI reset
,09-16 11:36:12.952  9949 10271 E bt_hwcfg: Read Local Name after HCI reset
,09-16 11:36:12.952  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{97b6a48: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:12.982  9949 10271 D bt_hwcfg: Chipset BCM4359C0
,09-16 11:36:12.982  9949 10271 D bt_hwcfg: Target name = [BCM4359C0]
,09-16 11:36:12.982  9949 10271 I bt_hwcfg: module_type[semco_b90s_c0].
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG . BCM4359C0
,09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG .. BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0061_murata.hcd BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG companion_2l1_master_setfile.bin BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG companion_2l1_mode_setfile.bin BCM4359C0
,09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG companion_fw_2l1.bin BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG companion_fw_imx260.bin BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG companion_imx260_master_setfile.bin BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG companion_imx260_mode_setfile.bin BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG fimc_is_fw2_2l1.bin BCM4359C0
,09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG fimc_is_fw2_imx260.bin BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG mfc_fw.bin BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG ois_fw_dom.bin BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG ois_fw_sec.bin BCM4359C0
,09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG sec_s3nrn81_firmware.bin BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG seiren_fw_dram.bin BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG seiren_fw_sram.bin BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG setfile_2l1.bin BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG setfile_4e6.bin BCM4359C0
,09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG setfile_imx260.bin BCM4359C0
09-16 11:36:12.982  9949 10271 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0062_semco.hcd BCM4359C0
09-16 11:36:12.982  9949 10271 I bt_hwcfg: patch(org) : bcm4359C0_V0044.0062_semco.hcd
09-16 11:36:12.982  9949 10271 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
,09-16 11:36:12.982  9949 10271 E bt_hwcfg: ORG patchram base 0044
09-16 11:36:12.982  9949 10271 E bt_hwcfg: ORG patchram minor 0062
09-16 11:36:12.982  9949 10271 E bt_hwcfg: fw ver (org)44.62
09-16 11:36:12.982  9949 10271 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
,09-16 11:36:13.002  9949 10271 I bt_hwcfg: Axi patch failure or not include AXI patching
,09-16 11:36:13.002  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{f9e60e1: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.002  9949 10271 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,09-16 11:36:13.012  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{6f9fe06: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.042  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:13.102  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{27b2cc7: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.112  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{f00e2f4: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.162  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{53f2a1d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.172  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{a27f492: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.182  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{a73ce63: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.192  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{fc33a60: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.202  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{8294b19: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.212  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{cccc7de: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.222  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{bcaedbf: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.222  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:13.232  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{a919c8c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.232  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{dfa7fd5: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.242  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{a5983ea: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.252  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{f4aa6db: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.252  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{a01f578: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.262  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{e704451: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.272  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{243f4b6: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.282  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{642d5b7: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.282  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{a1cf124: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.292  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{5a3d48d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.302  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{392a642: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.302  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{d251653: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.312  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{cc9fb90: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.322  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{e062c89: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.322  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{528e48e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.332  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{be0c4af: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.342  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{8fb40bc: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.342  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{e1c0845: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.352  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{6d2bb9a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.352  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{ffefccb: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.362  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{99aca8: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.362  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{5f9e3c1: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.372  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{710f766: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.372  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{c7e9aa7: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.382  9949 10271 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-16 11:36:13.382  9949 10271 I bt_hwcfg: FW Download delta = 427391
09-16 11:36:13.382  9949 10271 D bt_hwcfg: Settlement delay -- 100 ms
09-16 11:36:13.382  9949 10271 I bt_hwcfg: Setting fw settlement delay to 100 
,09-16 11:36:13.382  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{930eb54: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.382  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{87ffafd: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.392  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{9a523f2: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.392  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{b703a43: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.392  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:13.402  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{35b68c0: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.402  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{c5649f9: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.402  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{add8d3e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.412  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{d52379f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.412  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{cee50ec: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.422  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{a88cb5: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.422  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{ba13f4a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.432  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{22caebb: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.432  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{9e58fd8: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.432  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{1a23f31: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.442  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{23c0616: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.442  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{86d7b97: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.452  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{fd184: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.452  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{8aa9d6d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.462  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{bea6da2: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.462  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{d843a33: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.462  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{17a81f0: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.472  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{460a369: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.472  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{b25c1ee: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.482  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{c3e468f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.482  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{19dcd1c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.482  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{4570d25: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.492  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{eb00efa: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.492  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{4e2bcab: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.502  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{1489f08: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.502  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{49056a1: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.512  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{d6020c6: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.512  9949 10271 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,09-16 11:36:13.512  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{b0e7887: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.512  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{d4ca3b4: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.522  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{4babbdd: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.522  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{2ad8352: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.532  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{5501623: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.532  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{bea4720: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.532  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{72c38d9: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.542  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{7fc829e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.542  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{a83f17f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.552  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{4fcb54c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.552  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{39e8995: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.562  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{6aa2aaa: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.562  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{8f0269b: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.562  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{e5da38: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.572  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{9ab2a11: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.572  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{ed84776: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.582  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:13.582  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{3209177: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.582  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{a3a61e4: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.592  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{f07564d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.592  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{ef96502: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.602  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{e82ce13: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.602  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{e2db850: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.602  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{5800a49: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.612  9949 10271 I bt_hwcfg: vendor lib fwcfg completed
,09-16 11:36:13.612  9949 10271 I bt_vendor: firmware callback
09-16 11:36:13.612  9949 10271 I bt_hci  : firmware_config_callback
09-16 11:36:13.612  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{81ccf4e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:13.612  9949 10275 I bt_btu_task: Bluetooth chip preload is complete
,09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_HCI
,09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_AVRC
09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_A2D
09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_BNEP
09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_BTM
09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_GAP
09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_PAN
09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_SDP
09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_GATT
09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_SMP
09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-16 11:36:13.612  9949 10275 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-16 11:36:13.612  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{fc2386f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.622  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{7be097c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.632  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{4b60205: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.632  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{afa925a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.642  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{e3ec8b: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.642  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{1a04168: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.652  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{399b981: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.652  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{9bf7a26: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.662  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{d22c667: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.662  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{aec0c14: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.672  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{da76cbd: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.672  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{a9912b2: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.682  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{e8b6203: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.682  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{a87d580: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.692  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{fe317b9: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.692  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{701a7fe: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.702  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{9581b5f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.702  9949 10275 W bt_l2cap: l2c_link_processs_ble_num_bufs 15
,09-16 11:36:13.702  9949 10275 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf36197a9
09-16 11:36:13.702  9949 10275 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf36197a9 
09-16 11:36:13.702  9949 10275 E bt_btm  : btm_ble_set_search_if search_if=4
09-16 11:36:13.702  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{d54c9ac: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.702  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{9947675: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.712  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{3cc460a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.712  9949 10258 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = false mAobleSupported = 1
,09-16 11:36:13.712  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{10d0e7b: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.722  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{b1ad498: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.722  9949 10258 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
09-16 11:36:13.722  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{cc304f1: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:13.732  9949 10258 D bt_hci  : do_postload posting postload work item
09-16 11:36:13.732  9949 10258 E bt_btif_sock: btif_sock_init: !vhci_init
09-16 11:36:13.732  9949 10271 I bt_hci  : event_postload
09-16 11:36:13.732  9949 10258 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
09-16 11:36:13.732  9949 10271 D bt_hwcfg: hw_sco_config
09-16 11:36:13.732  9949 10271 I bt_vendor: sco_config_cb
09-16 11:36:13.732  9949 10271 I bt_hci  : sco_config_callback postload finished.
09-16 11:36:13.732  9949 10258 D bt_bte_conf: Device ID record 1 : primary
09-16 11:36:13.732  9949 10258 D bt_bte_conf:   vendorId            = 0075
09-16 11:36:13.732  9949 10258 D bt_bte_conf:   vendorIdSource      = 0001
09-16 11:36:13.732  9949 10258 D bt_bte_conf:   product             = 0100
09-16 11:36:13.732  9949 10258 D bt_bte_conf:   version             = 0200
09-16 11:36:13.732  9949 10258 D bt_bte_conf:   clientExecutableURL = 
09-16 11:36:13.732  9949 10258 D bt_bte_conf:   serviceDescription  = 
09-16 11:36:13.732  9949 10258 D bt_bte_conf:   documentationURL    = 
09-16 11:36:13.732  9949 10258 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-16 11:36:13.732  9949 10255 D bt_stack_manager: event_start_up_stack finished
09-16 11:36:13.732  9949 10258 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
09-16 11:36:13.732  9949 10258 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
09-16 11:36:13.732  9949 10258 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
09-16 11:36:13.732  9949 10258 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Hero SWB-B90S eLNA-0044
,09-16 11:36:13.732  9949 10258 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0044.0062_semco.hcd
09-16 11:36:13.732  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{df0b8d6: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:13.732  9949 10258 E BluetoothAdapterState: stateChangeCallback : 1
09-16 11:36:13.732  9949 10254 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
,09-16 11:36:13.732  9949 10254 D BluetoothAdapterProperties: Setting state to 15
09-16 11:36:13.732  9949 10254 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-16 11:36:13.732  9949 10254 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-16 11:36:13.732  9949 10254 D BluetoothAdapterService: updateAdapterState state is 15
09-16 11:36:13.742  9949 10254 D BluetoothAdapterService: Autoconnection is available 
09-16 11:36:13.742  9949 10254 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
09-16 11:36:13.742  9949 10254 I BluetoothAdapterState: Entering BleOnState
,09-16 11:36:13.742  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{e34a244: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.742  3459  3570 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-16 11:36:13.742  3459  3570 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,09-16 11:36:13.752  9949 10254 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,09-16 11:36:13.752  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{a71ff2d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:13.752  9949 10254 D BluetoothAdapterProperties: Setting state to 11
,09-16 11:36:13.752  9949 10254 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-16 11:36:13.752  9949 10254 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-16 11:36:13.752  9949 10254 D BluetoothAdapterService: updateAdapterState state is 11
,09-16 11:36:13.752  9949 10254 D BluetoothAdapterService: Autoconnection is available 
09-16 11:36:13.752  9949 10254 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
,09-16 11:36:13.752  9949 10254 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-16 11:36:13.752  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{8178c62: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:13.752  9949 10254 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-16 11:36:13.752  9949 10271 I bt_vendor: low_power_mode_cb
09-16 11:36:13.752  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-16 11:36:13.752  3459  3570 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
09-16 11:36:13.752  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:13.772  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-16 11:36:13.772  9949  9949 D HeadsetService: Received start request. Starting profile...
,09-16 11:36:13.772  9949  9949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c0f901
09-16 11:36:13.772  9949  9949 D HeadsetProvider: make
09-16 11:36:13.772  9949  9949 D HeadsetProvider: HeadsetProvider
09-16 11:36:13.772  9949  9949 I HeadsetProvider: clearAllHeadsetSettings(0)
,09-16 11:36:13.782  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{69c6129: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:13.782  9949  9949 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-16 11:36:13.782  9949  9949 D HeadsetStateMachine: make
,09-16 11:36:13.782  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-16 11:36:13.782  3459  3459 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:13.782  3949  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:13.782  3459  3459 I InputMethodManagerService: [BT Setting State] State =11
09-16 11:36:13.782  3949  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
09-16 11:36:13.782  4346  4346 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:13.782  9949  9949 E HeadsetStateMachine: # of Max HF connection is 3
,09-16 11:36:13.792  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-16 11:36:13.792  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
,09-16 11:36:13.792  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,09-16 11:36:13.792  7545  7545 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-16 11:36:13.792  9356  9356 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:13.792  9356  9356 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-16 11:36:13.802  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:36:13.802  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e60cae u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf426af 9356:com.android.settings/1000}
,09-16 11:36:13.812  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:13.812  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-16 11:36:13.812  3949  4176 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
,09-16 11:36:13.812  3459  3974 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-16 11:36:13.812  3949  3949 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,09-16 11:36:13.822  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e60cae u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
,09-16 11:36:13.832  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-16 11:36:13.842  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{f7a8c6b: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.842  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e60cae u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5287a2d 4271:com.google.android.gms.persistent/u0a21}
,09-16 11:36:13.842  4271  4271 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,09-16 11:36:13.862  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e60cae u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1de32d 8934:com.sec.android.app.shealth:remote/u0a39}
,09-16 11:36:13.872  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-16 11:36:13.882  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e60cae u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf426af 9356:com.android.settings/1000}
,09-16 11:36:13.882  9356  9356 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:13.882  9356  9356 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,09-16 11:36:13.902  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e60cae u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{957b75a 9789:com.samsung.android.intelligenceservice2/5010}
,09-16 11:36:13.912  9949  9949 I bt_bluedroid: get_profile_interface handsfree
,09-16 11:36:13.922  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,09-16 11:36:13.922  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{da72474: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.932  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e60cae u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b26bf8 9949:com.android.bluetooth/1002}
,09-16 11:36:13.932  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:13.952  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-16 11:36:13.952  9949 10254 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-16 11:36:13.952  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-16 11:36:13.952  9949 10254 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-16 11:36:13.952  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,09-16 11:36:13.952  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{99a1de3: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.962  9949 10254 I BluetoothAdapterState: Entering PendingCommandState
,09-16 11:36:13.972  9949  9949 I DualScoManager: Instantiating Dual Sco Manager
09-16 11:36:13.972  9949  9949 I DualScoManager: Set HeadsetServiceHelper
,09-16 11:36:13.972  9949  9949 D BluetoothAtMessage: createCMTIContentObservers
,09-16 11:36:13.972  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{c4c13e0: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.982  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{9b2e699: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.982  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{6c4fd5e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.982  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{bc6b53f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.992  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{c8e8e0c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:13.992  9949  9949 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@9ca773a
,09-16 11:36:13.992  9949  9949 D HeadsetProvider: setHeadsetDB - Can't find 300 for A8:81:95:E9:5F:XX,
,09-16 11:36:13.992  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{1425355: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.002  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{75f916a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.002  9949  9949 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 300, 1, true
,09-16 11:36:14.002  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{3fb665b: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.012  9949  9949 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@a0b0be1
,09-16 11:36:14.012  9949  9949 D HeadsetProvider: setHeadsetDB - Can't find 400 for A8:81:95:E9:5F:XX
,09-16 11:36:14.022  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{9c7ef8: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.022  9949  9949 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 400, 1, true
,09-16 11:36:14.022  9949 10278 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,09-16 11:36:14.022  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{d21cfd1: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.022  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
,09-16 11:36:14.022  9949  9949 E HeadsetService: notifyProfileServiceStateChanged
,09-16 11:36:14.032  9949 10278 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-16 11:36:14.032  9949 10278 D HeadsetStateMachine: map size, before remove : 0
09-16 11:36:14.032  9949 10278 D HeadsetStateMachine: map size, after remove: 0
09-16 11:36:14.032  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{8a2980d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.032  9949  9949 D A2dpService: Received start request. Starting profile...
09-16 11:36:14.032  9949  9949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c0f901
,09-16 11:36:14.032  9949  9949 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-16 11:36:14.032  9949  9949 I bt_bluedroid: get_profile_interface avrcp
,09-16 11:36:14.032  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{e9ce3c2: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.032  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{3e45d3: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.042  9949  9949 I Avrcp   : No of Audio players :: 1
09-16 11:36:14.042  9949  9949 I Avrcp   : App Package name is GM
,09-16 11:36:14.042  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{c1d6c2f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.042  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{ad7923c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.042  9949  9949 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.music
,09-16 11:36:14.052  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{2bfbbc5: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.052  9949  9949 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:14.052  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{637291a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.052  9949  9949 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,09-16 11:36:14.052  9949  9949 I Avrcp   : No of Video players :: 2
09-16 11:36:14.052  9949  9949 I Avrcp   : Video App Package name is others
,09-16 11:36:14.062  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{81e9c4b: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.062  9949  9949 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.apps.photos
,09-16 11:36:14.062  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{5a99628: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.062  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{fe54f41: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.072  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{ebce6: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.072  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{3b8b227: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.072  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{d15ecd4: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.082  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{769e7d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.082  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{879c172: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.092  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{4f449c3: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.092  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{a4f0240: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.092  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{3d3a579: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.102  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{21e82be: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.102  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{fc7bf1f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.102  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{542026c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.112  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{5602035: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.112  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{1bc0cca: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.112  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:14.122  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{7332e3b: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.122  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{582d958: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.122  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{8ff8ab1: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.132  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{6f62b96: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.132  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{41c7317: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.142  9949  9949 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:14.142  9949  9949 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,09-16 11:36:14.142  9949  9949 I Avrcp   : Video App Package name is VP
,09-16 11:36:14.142  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{5f83304: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.142  9949  9949 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungVideoPlayer/SamsungVideoPlayer.apk / 1.0 running in com.android.bluetooth rsrc of package com.samsung.android.video
,09-16 11:36:14.142  9949  9949 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:14.142  9949  9949 V Avrcp   : MediaPlayerInfo: mPlayerId=3
09-16 11:36:14.142  9949  9949 I Avrcp   : Add tempPlayer
,09-16 11:36:14.142  9949  9949 V Avrcp   : MediaPlayerInfo: mPlayerId=4
09-16 11:36:14.142  9949  9949 V Avrcp   : no_of_players : 4
09-16 11:36:14.142  9949  9949 I Avrcp   : Total no of players: 4
09-16 11:36:14.142  9949  9949 V Avrcp   : Samsung player is the 1st player
,09-16 11:36:14.142  9949  9949 D Avrcp   : Compose Browsing Service Candidate
09-16 11:36:14.142  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{35120ed: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:14.142  9949  9949 D Avrcp   : ResolveInfo info ResolveInfo{124b392 com.google.android.music/.browse.MediaBrowserService m=0x108000}
09-16 11:36:14.142  9949  9949 D Avrcp   : Initialize Media Controller
,09-16 11:36:14.142  9949  9949 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-16 11:36:14.152  9949  9949 E Avrcp   : getActiveSessions
,09-16 11:36:14.152  9949  9949 D Avrcp   : pick active media Controller
09-16 11:36:14.152  9949  9949 D Avrcp   : Get the active Media Controller 
09-16 11:36:14.152  9949  9949 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-16 11:36:14.152  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{5e16b22: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:14.152  9949  9949 D A2dpStateMachine: make
,09-16 11:36:14.152  9949  9949 I bt_bluedroid: get_profile_interface a2dp
,09-16 11:36:14.152  9949  9949 E bt_btif : warning : media task started media_task_refcnt 1 
,09-16 11:36:14.152  9949 10282 D A2dpStateMachine: Enter Disconnected: -2
,09-16 11:36:14.152  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
,09-16 11:36:14.152  9949  9949 E A2dpService: notifyProfileServiceStateChanged
09-16 11:36:14.152  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{d4f176e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.162  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{e4ae0f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.162  9949  9949 I BluetoothHidServiceJni: classInitNative: succeeds
,09-16 11:36:14.162  9949  9949 D HidService: Received start request. Starting profile...
,09-16 11:36:14.162  9949  9949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c0f901
09-16 11:36:14.162  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{d00de9c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:14.162  9949  9949 I bt_bluedroid: get_profile_interface hidhost
09-16 11:36:14.162  9949  9949 D HidService: setHidService(): set to: null
09-16 11:36:14.162  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
,09-16 11:36:14.162  9949  9949 E HidService: notifyProfileServiceStateChanged
09-16 11:36:14.162  9949  9949 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-16 11:36:14.162  9949  9949 D HealthService: Received start request. Starting profile...
09-16 11:36:14.162  9949  9949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c0f901
,09-16 11:36:14.172  9949  9949 I bt_bluedroid: get_profile_interface health
,09-16 11:36:14.172  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
09-16 11:36:14.172  9949  9949 E HealthService: notifyProfileServiceStateChanged
09-16 11:36:14.172  9949  9949 D HeadsetStateMachine: Try to query the phonestate on bind
,09-16 11:36:14.172  3459  4416 I Telecom : BluetoothPhoneService: queryPhoneState
09-16 11:36:14.172  3459  4416 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
09-16 11:36:14.172  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{5da80a5: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.172  9949  9949 I BluetoothPanServiceJni: classInitNative(L113): succeeds
,09-16 11:36:14.172  9949  9949 D PanService: Received start request. Starting profile...
09-16 11:36:14.172  9949  9949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c0f901
09-16 11:36:14.172  9949  9949 D BluetoothPanServiceJni: initializeNative(L118): pan
,09-16 11:36:14.172  9949  9949 I bt_bluedroid: get_profile_interface pan
09-16 11:36:14.172  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
09-16 11:36:14.172  9949  9949 E PanService: notifyProfileServiceStateChanged
09-16 11:36:14.172  9949  9949 D HeadsetStateMachine: Proxy object connected
,09-16 11:36:14.172  9949  9949 D BluetoothMapService: Received start request. Starting profile...
,09-16 11:36:14.172  9949  9949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c0f901
09-16 11:36:14.172  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{5d93c7a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.172  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
,09-16 11:36:14.172  9949  9949 E BluetoothMapService: notifyProfileServiceStateChanged
,09-16 11:36:14.172  9949  9949 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-16 11:36:14.172  9949 10278 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-16 11:36:14.172  9949 10278 E HeadsetStateMachine: Unknown message: 11
09-16 11:36:14.182  9949  9949 V SapService: SapBinder()
,09-16 11:36:14.182  9949  9949 D SapService: Received start request. Starting profile...
09-16 11:36:14.182  9949  9949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c0f901
,09-16 11:36:14.182  9949  9949 V SapService: start()
09-16 11:36:14.182  9949  9949 D SapService: Disable sap : false
,09-16 11:36:14.182  3459  4416 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e60cae u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc9767 9803:com.google.android.apps.maps/u0a125}
,09-16 11:36:14.192  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
09-16 11:36:14.192  9949  9949 E SapService: notifyProfileServiceStateChanged
09-16 11:36:14.192  9949  9949 D HeadsetPhoneState: sendDeviceDataStateChanged
09-16 11:36:14.192  9949  9949 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-16 11:36:14.192  9949 10278 D HeadsetStateMachine: Disconnected process message: 19, size: 0
09-16 11:36:14.192  9949 10278 E HeadsetStateMachine: Unknown message: 19
,09-16 11:36:14.202  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{51ee0d2: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.202  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{b11e5a3: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.212  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{9a8a0a0: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.212  9949  9949 D BleAudioService: Received start request. Starting profile...
09-16 11:36:14.212  9949  9949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c0f901
09-16 11:36:14.212  9949  9949 E DualScoManager: Dual Sco Manager already instantiated
,09-16 11:36:14.212  9949  9949 I BtBleAudio.JNI: classInitNative(L304): succeeds
09-16 11:36:14.212  9949  9949 D BleAudioStateMachine: make
,09-16 11:36:14.212  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{97d5459: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.212  9949  9949 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
09-16 11:36:14.212  9949  9949 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 0
,09-16 11:36:14.212  9949  9949 I bt_bluedroid: get_profile_interface bleaudio_source
09-16 11:36:14.212  9949  9949 D BleAudioStateMachine: make
09-16 11:36:14.212  9949 10287 E BleAudioStateMachine_L: Enter Disconnected: -2
,09-16 11:36:14.212  9949  9949 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,09-16 11:36:14.212  9949  9949 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 1
09-16 11:36:14.212  9949  9949 V BleAudioService: [registerCallStateListener]
09-16 11:36:14.212  9949 10288 E BleAudioStateMachine_R: Enter Disconnected: -2
09-16 11:36:14.222  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{fe6381e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.222  9949  9949 V BleAudioService: [registerAobleStateChangeListener]
,09-16 11:36:14.222  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{f5338ff: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.222  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Message sending
,09-16 11:36:14.222  9949  9949 E BleAudioService: notifyProfileServiceStateChanged
09-16 11:36:14.222  9949  9949 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-16 11:36:14.222  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 11:36:14.222  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
09-16 11:36:14.222  9949 10278 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-16 11:36:14.222  9949 10278 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-16 11:36:14.222  9949 10278 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-16 11:36:14.222  9949 10278 E HeadsetStateMachine: Unknown message: 11
09-16 11:36:14.222  9949  9949 V BluetoothAdapterState: isTurningOff()=false
09-16 11:36:14.222  9949  9949 V BluetoothAdapterState: isTurningOn()=true
,09-16 11:36:14.222  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:14.222  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:14.222  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:14.222  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
09-16 11:36:14.232  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{c2c661b: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.232  9949  9949 V BluetoothAdapterState: isTurningOff()=false
09-16 11:36:14.232  9949  9949 V BluetoothAdapterState: isTurningOn()=true
09-16 11:36:14.232  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:14.232  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:14.232  9949  9949 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-16 11:36:14.232  9949  9949 D HeadsetPhoneState: sendDeviceDataStateChanged
09-16 11:36:14.232  9949  9949 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-16 11:36:14.232  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:14.232  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
09-16 11:36:14.232  9949 10278 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-16 11:36:14.232  9949 10278 E HeadsetStateMachine: Unknown message: 11
09-16 11:36:14.232  9949 10278 D HeadsetStateMachine: Disconnected process message: 19, size: 0
09-16 11:36:14.232  9949 10278 E HeadsetStateMachine: Unknown message: 19
09-16 11:36:14.232  9949  9949 V BluetoothAdapterState: isTurningOff()=false
,09-16 11:36:14.232  9949  9949 V BluetoothAdapterState: isTurningOn()=true
09-16 11:36:14.232  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:14.232  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:14.232  9949  9949 D BluetoothAdapterService: HID Host service started
,09-16 11:36:14.232  9356  9356 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,09-16 11:36:14.232  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{9e5e3b8: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:14.232  9356  9356 D BluetoothMap: Create BluetoothMap proxy object
,09-16 11:36:14.232  3949  4129 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
09-16 11:36:14.232  3949  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
09-16 11:36:14.232  3949  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
09-16 11:36:14.232  3949  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
09-16 11:36:14.232  3949  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
09-16 11:36:14.232  3949  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
09-16 11:36:14.232  3949  4129 D HidProfile: mService is null. need to get proxy again!!
,09-16 11:36:14.242  9949  9949 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-16 11:36:14.242  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:14.242  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
,09-16 11:36:14.242  9949  9949 V BluetoothAdapterState: isTurningOff()=false
,09-16 11:36:14.242  9949  9949 V BluetoothAdapterState: isTurningOn()=true
09-16 11:36:14.242  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:14.242  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:14.242  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:14.242  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
,09-16 11:36:14.242  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{3599cd: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.242  9949  9949 V BluetoothAdapterState: isTurningOff()=false
09-16 11:36:14.242  9949  9949 V BluetoothAdapterState: isTurningOn()=true
09-16 11:36:14.242  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:14.242  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 11:36:14.242  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:14.242  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
09-16 11:36:14.242  9949  9949 V BluetoothAdapterState: isTurningOff()=false
09-16 11:36:14.242  9949  9949 V BluetoothAdapterState: isTurningOn()=true
09-16 11:36:14.242  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:14.242  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 11:36:14.242  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:14.242  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,09-16 11:36:14.252  9949  9949 V BluetoothAdapterState: isTurningOff()=false
09-16 11:36:14.252  9949  9949 V BluetoothAdapterState: isTurningOn()=true
09-16 11:36:14.252  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:14.252  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:14.252  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{6177d93: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:14.252  9949  9949 D BleAudioService: [onCallStateChanged] ENTER -- State: (0)
09-16 11:36:14.252  9949  9949 D BleAudioService: [onCallStateChanged] No devices in connected state
,09-16 11:36:14.252  9949  9949 D BleAudioService: [onCallStateChanged][PHONECALL STATE Changed]: EXIT
09-16 11:36:14.252  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:14.252  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Before synchronized
,09-16 11:36:14.252  9949  9949 V BluetoothAdapterState: isTurningOff()=false
09-16 11:36:14.252  9949  9949 V BluetoothAdapterState: isTurningOn()=true
09-16 11:36:14.252  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 11:36:14.252  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:14.252  9949 10254 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,09-16 11:36:14.252  9949 10254 E BluetoothServiceJni: enableBrEdrNative:
09-16 11:36:14.252  9949 10254 I bt_bluedroid: enable_bredr
,09-16 11:36:14.252  9356  9356 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,09-16 11:36:14.252  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{69ee4ce: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.262  9949 10258 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf35eaf29
09-16 11:36:14.262  9949 10258 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
09-16 11:36:14.262  9949 10258 D BluetoothAdapterProperties: Address is:A8:81:95:E9:5F:6F
09-16 11:36:14.262  9949 10258 E BluetoothServiceJni: populateRssiValuesNative
09-16 11:36:14.262  9949 10258 I bt_bluedroid: getModelRssiValues
09-16 11:36:14.262  9949 10275 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
09-16 11:36:14.262  9949 10258 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
09-16 11:36:14.262  9949 10258 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,09-16 11:36:14.262  9949 10258 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7 edge
,09-16 11:36:14.262  3459  3459 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,09-16 11:36:14.262  9949 10258 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-16 11:36:14.262  9949 10258 D BluetoothAdapterProperties: Scan Mode:20
09-16 11:36:14.262  9949 10258 D BluetoothAdapterProperties: Discoverable Timeout:-1
09-16 11:36:14.262  9949 10258 E bt_btif : btif_handle_bluetooth_enable_evt
09-16 11:36:14.272  9949 10258 E bt_btif : ANT+ socket does not initialize.
,09-16 11:36:14.272  9356  9356 D LocalBluetoothProfileManager: Adding local BleAudio profile
09-16 11:36:14.272  9949 10258 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
09-16 11:36:14.272  9949 10258 D IOP_DB_BT: db_open: db_open : handle 4082556944l, read 18483 bytes onto local cache
09-16 11:36:14.272  9949 10258 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
09-16 11:36:14.272  9949 10258 D IOP_DB_BT: db_query: result 1
09-16 11:36:14.272  9949 10258 I         : iop_db_open: iop_db_open status 0
09-16 11:36:14.272  9949 10258 E BluetoothAdapterState: stateChangeCallback : 17
09-16 11:36:14.272  9949 10258 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
09-16 11:36:14.272  9949 10254 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
09-16 11:36:14.272  9949 10258 E bt_btif : btif_sm_dispatch : Invalid handle
09-16 11:36:14.272  9949 10275 D CODEC_IF_MOD: codec_open: codec_open
09-16 11:36:14.272  9949 10275 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
09-16 11:36:14.272  9949 10275 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
09-16 11:36:14.272  9949 10275 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
09-16 11:36:14.272  9949 10275 D CODEC_IF: codec_if_open: codec module opened (v0.1
09-16 11:36:14.272  9949 10275 D CODEC_IF: codec_if_close: codec_if_close hdl -294371324
09-16 11:36:14.272  9949 10275 D CODEC_IF_MOD: codec_close: codec_close
09-16 11:36:14.272  9949 10275 D CODEC_IF_MOD: codec_close: freed apt-x encoder
09-16 11:36:14.272  9949 10275 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
09-16 11:36:14.272  9949 10275 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,09-16 11:36:14.272  9356  9356 D BluetoothLeAudio: getProfileProxy()
,09-16 11:36:14.272  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{b487fda: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.282  9949 10254 D BluetoothAdapterProperties: ScanMode =  20
,09-16 11:36:14.282  9949 10254 D BluetoothAdapterProperties: State =  11
,09-16 11:36:14.282  9949 10275 D CODEC_IF_SSHD: codec_open: codec_open
,09-16 11:36:14.282  9949 10275 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
09-16 11:36:14.282  9949 10275 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
,09-16 11:36:14.282  9949 10275 D CODEC_IF: codec_if_open: codec module opened (v0.1
,09-16 11:36:14.282  9949 10275 D CODEC_IF: codec_if_close: codec_if_close hdl -396374656
09-16 11:36:14.282  9949 10275 D CODEC_IF_SSHD: codec_close: codec_close
09-16 11:36:14.282  9949 10275 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
09-16 11:36:14.282  9949 10275 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
09-16 11:36:14.282  9949 10258 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
,09-16 11:36:14.282  9949 10258 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
09-16 11:36:14.282  9949 10258 E bt_btif : no av control block available at state:3
09-16 11:36:14.282  9949 10258 E bt_btif : no av control block available at state:3
,09-16 11:36:14.282  9949 10258 E bt_btif : no av control block available at state:2
09-16 11:36:14.282  9949 10258 E bt_btif : warning : no command pending, ignore ack
09-16 11:36:14.282  9949 10258 E bt_btif : no av control block available at state:3
09-16 11:36:14.282  9949 10258 E bt_btif : no av control block available at state:2
09-16 11:36:14.282  9949 10258 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
09-16 11:36:14.282  9949 10258 E bt_btif : btif_sm_dispatch : Invalid handle
09-16 11:36:14.282  9949 10275 D CODEC_IF_MOD: codec_open: codec_open
09-16 11:36:14.282  9949 10275 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
,09-16 11:36:14.282  9949 10275 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
09-16 11:36:14.282  9949 10275 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
09-16 11:36:14.282  9949 10275 D CODEC_IF: codec_if_open: codec module opened (v0.1
09-16 11:36:14.282  9949 10275 D CODEC_IF: codec_if_close: codec_if_close hdl -294371324
09-16 11:36:14.282  9949 10275 D CODEC_IF_MOD: codec_close: codec_close
09-16 11:36:14.282  9949 10275 D CODEC_IF_MOD: codec_close: freed apt-x encoder
09-16 11:36:14.282  9949 10275 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
09-16 11:36:14.282  9949 10275 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
09-16 11:36:14.282  9949 10275 D CODEC_IF_SSHD: codec_open: codec_open
09-16 11:36:14.282  9949 10275 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
,09-16 11:36:14.282  9949 10275 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
09-16 11:36:14.282  9949 10275 D CODEC_IF: codec_if_open: codec module opened (v0.1
09-16 11:36:14.282  9949 10275 D CODEC_IF: codec_if_close: codec_if_close hdl -396374656
09-16 11:36:14.282  9949 10275 D CODEC_IF_SSHD: codec_close: codec_close
09-16 11:36:14.282  9949 10275 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
09-16 11:36:14.282  9949 10258 E bt_btif : BTA got event 0x518
09-16 11:36:14.282  9949 10258 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
09-16 11:36:14.282  9949 10258 E bt_btif : no av control block available at state:3
09-16 11:36:14.282  9949 10258 E bt_btif : no av control block available at state:3
,09-16 11:36:14.282  9949 10258 E bt_btif : no av control block available at state:2
09-16 11:36:14.282  9949 10258 E bt_btif : warning : no command pending, ignore ack
09-16 11:36:14.282  9949 10258 E bt_btif : no av control block available at state:3
09-16 11:36:14.282  9949 10258 E bt_btif : no av control block available at state:2
09-16 11:36:14.282  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:36:14.282  9949 10258 W bt_btif : Write Extended Inquiry Response to controller
09-16 11:36:14.282  9949 10258 E bt_btif : btif_sm_dispatch : Invalid handle
09-16 11:36:14.282  3459  3979 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,09-16 11:36:14.292  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{d75aae8: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.292  3459  4380 D SecContentProvider: insert(), uri = 2
,09-16 11:36:14.292  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:36:14.292  9356  9356 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,09-16 11:36:14.302  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:14.302  9356  9356 D BluetoothMap: Proxy object connected
,09-16 11:36:14.302  9949 10258 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-16 11:36:14.302  9356  9356 D MapProfile: Bluetooth service connected
09-16 11:36:14.302  9949 10258 D BluetoothAdapterProperties: Scan Mode:21
,09-16 11:36:14.312  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{c6e8d94: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:14.302  9949 10254 D BluetoothAdapterProperties: Setting state to 12
,09-16 11:36:14.302  9949 10254 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-16 11:36:14.302  9949 10258 D BluetoothAdapterProperties: Discoverable Timeout:-1
09-16 11:36:14.302  9949 10254 D HeadsetService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@ae33fc0
09-16 11:36:14.302  9949 10254 D A2dpService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@ae33fc0
09-16 11:36:14.302  9949 10254 D BleAudioService: setHeadsetService: setting HeadsetService
09-16 11:36:14.302  9949 10254 D BleAudioService: setA2dpService: setting A2dpService
,09-16 11:36:14.312  9356  9356 D BluetoothMap: getConnectedDevices()
09-16 11:36:14.312  9949 10254 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-16 11:36:14.312  9949 10254 D BluetoothAdapterService: updateAdapterState state is 12
09-16 11:36:14.312  9949 10258 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-16 11:36:14.322  3949  3949 D BluetoothInputDevice: Proxy object connected
09-16 11:36:14.322  3949  3949 D HidProfile: Bluetooth service connected
,09-16 11:36:14.332  4341  4470 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-16 11:36:14.332  4341  4470 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-16 11:36:14.332  3949  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,09-16 11:36:14.342  9949 10254 V BluetoothAdapterService: start opp service
,09-16 11:36:14.342  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{b70ef00: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.342  9356  9356 D BluetoothInputDevice: Proxy object connected
,09-16 11:36:14.342  9697  9697 D BluetoothAdapter: STATE_ON
09-16 11:36:14.342  9356  9356 D HidProfile: Bluetooth service connected
,09-16 11:36:14.352  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:36:14.352  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:14.352  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:14.352  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:36:14.352  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:36:14.352  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:36:14.352  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:36:14.352  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:36:14.352  9949  9949 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-16 11:36:14.352  9949 10254 D BluetoothAdapterService: Autoconnection is available 
09-16 11:36:14.352  9949 10254 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-16 11:36:14.352  9949 10254 D BluetoothAdapterService: starting service from this receiver
09-16 11:36:14.352  3949  4565 D BluetoothLeAudio: onBluetoothStateChange: up=true
09-16 11:36:14.352  3949  4565 D BluetoothLeAudio: Binding service...
09-16 11:36:14.352  9949  9949 I BluetoothPbapService: Handler(): got msg=1
,09-16 11:36:14.362  9356  9356 D BluetoothLeAudio: Proxy object connected
,09-16 11:36:14.372  9356  9356 D BleAudioProfile: Bluetooth service connected
09-16 11:36:14.372  9356  9356 D BluetoothLeAudio: getConnectedDevices()
,09-16 11:36:14.372  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{975fb2c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.372  3459  4834 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-16 11:36:14.372  9949 10254 D BluetoothAdapterService: BT on, init HID DEV count : 0
09-16 11:36:14.372  9949 10254 I BluetoothAdapterState: Entering OnState
,09-16 11:36:14.372  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:14.372  3949  3949 D BluetoothLeAudio: Proxy object connected
09-16 11:36:14.372  3949  3949 D BleAudioProfile: Bluetooth service connected
09-16 11:36:14.372  3949  3949 D BluetoothLeAudio: getConnectedDevices()
,09-16 11:36:14.372  9356  9356 D BluetoothPbap: Proxy object connected
,09-16 11:36:14.372  9356  9356 D PbapServerProfile: Bluetooth service connected
09-16 11:36:14.372  3949  4565 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,09-16 11:36:14.372  3949  3961 D BluetoothAdapter: onBluetoothStateChange: up=true
09-16 11:36:14.372  3949  3961 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-16 11:36:14.382  9356  9367 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-16 11:36:14.382  4271  7289 D BluetoothAdapter: onBluetoothStateChange: up=true
09-16 11:36:14.382  4271  7289 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-16 11:36:14.382  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{830938a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.382  9356  9366 D BluetoothLeAudio: onBluetoothStateChange: up=true
09-16 11:36:14.382  9697  9697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:36:14.382  9949 10295 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-16 11:36:14.382  4305  4322 D BluetoothAdapter: onBluetoothStateChange: up=true
09-16 11:36:14.382  4305  4322 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-16 11:36:14.382  8934  8944 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-16 11:36:14.392  8934  8944 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-16 11:36:14.392  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{5f0dfb: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.392  3949  4836 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 11:36:14.392  3949  4836 D BluetoothA2dp: Binding service...
,09-16 11:36:14.392  3949  4836 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-16 11:36:14.392  9949 10295 D BluetoothSocket: bindListen(): myUserId = 0
09-16 11:36:14.392  9949 10295 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:36:14.402  9949  9949 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-16 11:36:14.402  5041  5133 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 11:36:14.402  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{c0c5e56: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:14.402  5041  5133 D BluetoothA2dp: Binding service...
,09-16 11:36:14.402  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:14.402  9949  9949 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-16 11:36:14.402  5041  5133 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-16 11:36:14.412  9949  9949 V BtOppService: isOwner == true
,09-16 11:36:14.412  9949 10295 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-16 11:36:14.412  3949  4385 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-16 11:36:14.412  3949  4385 D BluetoothInputDevice: Binding service...
,09-16 11:36:14.412  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:36:14.412  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:14.412  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:14.412  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:36:14.412  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:36:14.412  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:36:14.412  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:36:14.412  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:36:14.412  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{10802ad: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.412  3949  3949 D BluetoothInputDevice: Proxy object connected
,09-16 11:36:14.412  3949  3949 D HidProfile: Bluetooth service connected
,09-16 11:36:14.422  3459  3570 D BluetoothPan: onBluetoothStateChange on: true
09-16 11:36:14.422  3459  3570 D BluetoothPan: onBluetoothStateChange calling doBind()
,09-16 11:36:14.422  4165  4180 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.android.bluetooth,id=0,extra=Bundle[mParcelledData.dataSize=160]
09-16 11:36:14.422  4165  4165 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=com.android.bluetooth, samsung.notification.remove_all=true}]
09-16 11:36:14.422  4165  4165 I PeopleStripeService: PeopleNotificationReceiver:3
,09-16 11:36:14.422  4299  7648 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-16 11:36:14.422  4299  7648 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-16 11:36:14.422  9697  9697 D BluetoothAdapter: STATE_ON
,09-16 11:36:14.422  4165  4165 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,09-16 11:36:14.422  4165  4165 I PeopleDataManager: removeNotification
09-16 11:36:14.422  4165  4165 I NotificationParser: getNotiType:com.android.bluetooth,null
09-16 11:36:14.422  4165  4165 D PeopleDataManager: removeNotiInfo: id =0,packageName=com.android.bluetooth,isEdgeNotification=false,key=null,removeAll=true
09-16 11:36:14.422  4165  4165 D PeopleDataManager: removeNotiInfo =null
,09-16 11:36:14.422  9356  9367 D BluetoothPan: onBluetoothStateChange on: true
,09-16 11:36:14.422  9356  9367 D BluetoothPan: onBluetoothStateChange calling doBind()
09-16 11:36:14.422  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{bd3da65: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.432  3949  3961 D BluetoothSap: onBluetoothStateChange: up=true
09-16 11:36:14.432  3949  3961 D BluetoothSap: Binding service...
,09-16 11:36:14.442  3949  4836 D BluetoothPbap: onBluetoothStateChange: up=true
09-16 11:36:14.442  3949  4836 D BluetoothPbap: Binding service...
,09-16 11:36:14.442  3949  3949 D BluetoothPbap: Proxy object connected
09-16 11:36:14.442  3949  3949 D PbapServerProfile: Bluetooth service connected
,09-16 11:36:14.442  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{78865f4: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.442  9697  9697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:36:14.442  9949 10294 D BluetoothAdapter: onBluetoothStateChange: up=true
09-16 11:36:14.442  9949 10294 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-16 11:36:14.452  3949  4385 D BluetoothMap: onBluetoothStateChange: up=true
09-16 11:36:14.452  3949  4385 D BluetoothMap: Binding service...
,09-16 11:36:14.452  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{2dbf11d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.452  3949  3949 D BluetoothMap: Proxy object connected
09-16 11:36:14.452  3949  3949 D MapProfile: Bluetooth service connected
09-16 11:36:14.452  3949  3949 D BluetoothMap: getConnectedDevices()
,09-16 11:36:14.462  3949  3961 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-16 11:36:14.462  9803  9814 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-16 11:36:14.462  9803  9814 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-16 11:36:14.462  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{3c25b51: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:14.462  3459  3570 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-16 11:36:14.462  3459  3570 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-16 11:36:14.472  9697  9708 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-16 11:36:14.472  9697  9708 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-16 11:36:14.472  9356  9366 D BluetoothMap: onBluetoothStateChange: up=true
,09-16 11:36:14.472  3459  3570 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 11:36:14.472  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{3805b8d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:14.472  3459  3570 D BluetoothA2dp: Binding service...
09-16 11:36:14.472  3459  3570 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-16 11:36:14.472  3949  3971 D BluetoothPan: onBluetoothStateChange on: true
,09-16 11:36:14.472  3949  3971 D BluetoothPan: onBluetoothStateChange calling doBind()
,09-16 11:36:14.472  3459  3459 D BluetoothA2dp: Proxy object connected
,09-16 11:36:14.472  3949  3949 D BluetoothA2dp: Proxy object connected
09-16 11:36:14.472  3949  3949 D A2dpProfile: Bluetooth service connected
,09-16 11:36:14.472  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:14.482  5041  5041 D BluetoothA2dp: Proxy object connected
,09-16 11:36:14.482  9949 10293 D A2dpStateMachine: getConnectedDevices : size=0
09-16 11:36:14.482  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{fad0f8e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.482  9949 10279 D A2dpStateMachine: getConnectedDevices : size=0
,09-16 11:36:14.482  3949  3949 D BluetoothPan: BluetoothPAN Proxy object connected
,09-16 11:36:14.482  5041  5133 D BluetoothAdapter: onBluetoothStateChange: up=true
09-16 11:36:14.482  3949  3949 D PanProfile: Bluetooth service connected
09-16 11:36:14.482  5041  5133 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-16 11:36:14.482  3459  3459 D BluetoothPan: BluetoothPAN Proxy object connected
,09-16 11:36:14.482  9356  9356 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 11:36:14.482  9356  9356 D PanProfile: Bluetooth service connected
09-16 11:36:14.482  9356  9366 D BluetoothPbap: onBluetoothStateChange: up=true
,09-16 11:36:14.492  3459  4424 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-16 11:36:14.492  9356  9367 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-16 11:36:14.492  9356  9367 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-16 11:36:14.492  9356  9366 D BluetoothSap: onBluetoothStateChange: up=true
,09-16 11:36:14.492  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{d4113af: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:14.492  9356  9366 D BluetoothSap: Binding service...
,09-16 11:36:14.502  3459  3459 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-16 11:36:14.502  3459  3459 I InputMethodManagerService: [BT Setting State] State =12
09-16 11:36:14.502  3459  3459 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-16 11:36:14.502  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{cee969a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.502  3949  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:14.502  3949  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-16 11:36:14.512  4346  4346 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:14.512  3459  3459 I Telecom : BluetoothPhoneService: queryPhoneState
09-16 11:36:14.512  3459  3459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,09-16 11:36:14.512  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-16 11:36:14.512  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:14.512  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,09-16 11:36:14.512  9949 10298 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-16 11:36:14.512  7545  7545 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-16 11:36:14.512  9356  9356 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:14.512  9949 10298 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
09-16 11:36:14.512  9356  9356 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-16 11:36:14.522  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:14.522  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8953bcb u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf426af 9356:com.android.settings/1000}
,09-16 11:36:14.522  3949  3949 D BluetoothSap: Proxy object connected
09-16 11:36:14.522  3949  3949 D SapProfile: Bluetooth service connected
,09-16 11:36:14.532  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:14.532  9356  9356 D LocalBluetoothProfileManager: Adding local A2DP profile
09-16 11:36:14.532  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{b7fbac1: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.542  9949 10299 D BluetoothSocket: bindListen(): myUserId = 0
,09-16 11:36:14.542  9949 10299 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:36:14.542  9356  9356 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-16 11:36:14.552 10301 10301 E Zygote  : v2
09-16 11:36:14.552 10301 10301 I libpersona: KNOX_SDCARD checking this for 10052
09-16 11:36:14.552 10301 10301 E Zygote  : isSdpEnabledProcess - SDP enabled
09-16 11:36:14.552 10301 10301 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:14.552 10301 10301 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:14.552  3459  4536 I ActivityManager: Start proc 10301:com.samsung.android.email.provider/u0a52 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
,09-16 11:36:14.562 10301 10301 E Zygote  : accessInfo : 64
09-16 11:36:14.562  3459  3856 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-16 11:36:14.562 10301 10301 E Zygote  : isSdpEnabledProcess - SDP enabled
09-16 11:36:14.562 10301 10301 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
09-16 11:36:14.562 10301 10301 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,09-16 11:36:14.562  9356  9356 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-16 11:36:14.562  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{60c41fd: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.562  9949 10299 I BtOppRfcommListener: Accept thread started.
09-16 11:36:14.562  9356  9356 E BluetoothHeadset: BTStateChangeCB is registed
,09-16 11:36:14.562  9356  9356 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
09-16 11:36:14.562  9356  9356 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
,09-16 11:36:14.562  9356  9356 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
09-16 11:36:14.562  9356  9356 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
09-16 11:36:14.572  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{6ad9bc0: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:14.562  9356  9356 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,09-16 11:36:14.562  3949  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
,09-16 11:36:14.562  3949  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
09-16 11:36:14.572  3949  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
09-16 11:36:14.572  3949  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
09-16 11:36:14.572  3949  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,09-16 11:36:14.572  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{42783e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.572  9356  9356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 11:36:14.582  3459  3856 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,09-16 11:36:14.582  9356  9356 D BluetoothSap: Proxy object connected
09-16 11:36:14.582  9356  9356 D SapProfile: Bluetooth service connected
,09-16 11:36:14.582  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{eb0b3ec: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:14.582  9356  9356 D BluetoothA2dp: Proxy object connected
,09-16 11:36:14.582  9356  9356 D A2dpProfile: Bluetooth service connected
,09-16 11:36:14.592 10301 10301 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:14.592 10301 10301 D ActivityThread: Added TimaKeyStore provider
09-16 11:36:14.592  3949  4176 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,09-16 11:36:14.592  3459  4053 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f02049a) visible user=0 )
,09-16 11:36:14.592  3459  4864 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-16 11:36:14.592  3459  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8953bcb u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
,09-16 11:36:14.602  9949  9959 D A2dpStateMachine: getConnectedDevices : size=0
,09-16 11:36:14.612  3459  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8953bcb u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5287a2d 4271:com.google.android.gms.persistent/u0a21}
,09-16 11:36:14.612  4271  4271 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,09-16 11:36:14.632  3459  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8953bcb u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1de32d 8934:com.sec.android.app.shealth:remote/u0a39}
,09-16 11:36:14.642  9356  9356 D DockEventReceiver: finishStartingService: stopping service
,09-16 11:36:14.642 10301 10301 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:14.642 10301 10301 D RelationGraph: garbageCollect()
,09-16 11:36:14.642 10301 10301 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,09-16 11:36:14.652  3459  4380 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:14.652 10301 10301 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:14.652  3459  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8953bcb u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf426af 9356:com.android.settings/1000}
,09-16 11:36:14.652  9356  9356 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
,09-16 11:36:14.652  9356  9356 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
09-16 11:36:14.652 10301 10301 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:14.652  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 11:36:14.652 10301 10301 I InjectionManager: Inside getClassLibPath caller 
,09-16 11:36:14.662  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{c96b3b5: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}},
,09-16 11:36:14.672  3459  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8953bcb u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{957b75a 9789:com.samsung.android.intelligenceservice2/5010}
,09-16 11:36:14.682 10301 10301 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,09-16 11:36:14.692  3459  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8953bcb u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b26bf8 9949:com.android.bluetooth/1002}
,09-16 11:36:14.702  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{850adbb: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.702  3459  4049 D RCPManagerService: exchangeData() failure , invalid userId
,09-16 11:36:14.712  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{8eb22d8: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.722  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{bcbd631: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.732  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{bf35116: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.742  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{6526a97: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.742  3459  4424 D RCPManagerService: exchangeData() failure , invalid userId
,09-16 11:36:14.752 10301 10301 D InjectionManager: InjectionManager
09-16 11:36:14.752 10301 10301 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
09-16 11:36:14.752 10301 10301 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
09-16 11:36:14.752 10301 10301 I InjectionManager: featureStore :{}
,09-16 11:36:14.752  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{55b9484: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.772 10319 10319 E Zygote  : v2
09-16 11:36:14.772 10319 10319 I libpersona: KNOX_SDCARD checking this for 10052
09-16 11:36:14.772 10319 10319 E Zygote  : isSdpEnabledProcess - SDP enabled
09-16 11:36:14.772 10319 10319 I libpersona: KNOX_SDCARD not a persona
09-16 11:36:14.772 10319 10319 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:14.782 10319 10319 E Zygote  : accessInfo : 64
09-16 11:36:14.782 10319 10319 E Zygote  : isSdpEnabledProcess - SDP enabled
09-16 11:36:14.782 10319 10319 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
09-16 11:36:14.782 10319 10319 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,09-16 11:36:14.782  3459  4049 I ActivityManager: Start proc 10319:com.samsung.android.email.provider:service/u0a52 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
,09-16 11:36:14.782  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{156a46d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.792  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{14b68a2: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.792  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{6491933: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.802  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{33f74f0: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.802 10319 10319 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-16 11:36:14.802 10319 10319 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:14.802  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{9461a69: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}},
,09-16 11:36:14.822  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{5f2158f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.822  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{63ef01c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.822 10319 10319 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 11:36:14.822 10319 10319 D RelationGraph: garbageCollect()
,09-16 11:36:14.822 10319 10319 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
09-16 11:36:14.822  9949  9949 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:14.822  9949  9949 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is12
,09-16 11:36:14.822  9949 10287 D BleAudioStateMachine_L: [Disconnected] Disconnected process message: 41
09-16 11:36:14.822  9949 10288 D BleAudioStateMachine_R: [Disconnected] Disconnected process message: 41
09-16 11:36:14.822  9949 10287 D BleAudioStateMachine_L: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
09-16 11:36:14.822  9949 10288 D BleAudioStateMachine_R: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,09-16 11:36:14.832  3459  4386 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:14.832  9949 10288 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 2
09-16 11:36:14.832  9949 10288 D BleAudioService: NotifyEvents: n : 0
09-16 11:36:14.832  9949 10287 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 1
09-16 11:36:14.832  9949 10287 D BleAudioService: NotifyEvents: n : 0
09-16 11:36:14.832 10319 10319 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:14.832 10319 10319 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:14.832 10319 10319 I InjectionManager: Inside getClassLibPath caller 
09-16 11:36:14.832  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:14.842 10335 10335 E Zygote  : v2
09-16 11:36:14.842 10335 10335 I libpersona: KNOX_SDCARD checking this for 10004
09-16 11:36:14.842 10335 10335 I libpersona: KNOX_SDCARD not a persona
,09-16 11:36:14.842 10335 10335 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 11:36:14.842 10335 10335 E Zygote  : accessInfo : 0
,09-16 11:36:14.842 10335 10335 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,09-16 11:36:14.842  3459  4380 I ActivityManager: Start proc 10335:com.sec.android.provider.badge/u0a4 for content provider com.sec.android.provider.badge/.BadgeProvider
,09-16 11:36:14.842  9949  9949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8c0f901
09-16 11:36:14.842  9949  9949 D BtConfig.SecureMode: isSecureModeOn:false
,09-16 11:36:14.852 10319 10319 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,09-16 11:36:14.852  9356  9356 D HeadsetProfile: Bluetooth service connected
,09-16 11:36:14.852  3949  3949 D HeadsetProfile: Bluetooth service connected
,09-16 11:36:14.852  3459  3459 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@79cf425
09-16 11:36:14.852  3459  3459 D BluetoothHeadset: registerMessageListener
,09-16 11:36:14.862  3459  4053 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8953bcb u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc9767 9803:com.google.android.apps.maps/u0a125}
,09-16 11:36:14.862 10335 10335 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 11:36:14.862 10335 10335 D ActivityThread: Added TimaKeyStore provider
,09-16 11:36:14.872  9949  9959 D HeadsetService: registerMessageListener
,09-16 11:36:14.872  9949  9959 D HeadsetService: registerMessageListener
,09-16 11:36:14.872  9949 10278 D HeadsetStateMachine: Disconnected process message: 70, size: 0
09-16 11:36:14.872  3459  3459 I Telecom : BluetoothManager : register MessageListener
09-16 11:36:14.882  3459  3459 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
09-16 11:36:14.872  9949 10278 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@406ca2
,09-16 11:36:14.882  9949  9949 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,09-16 11:36:14.892  3459  4856 I ActivityManager: Killing 9618:com.samsung.ipservice/5004 (adj 15): DHA:empty #33
,09-16 11:36:14.892  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{9d569fa: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.902 10319 10319 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,09-16 11:36:14.902 10319 10319 I QBNRClientHelper: init SyncClientHelper : Email
,09-16 11:36:14.912  9949 10347 D BluetoothSocket: bindListen(): myUserId = 0
09-16 11:36:14.912  9949 10347 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:36:14.912  3459  4856 D ActivityManager: isAutoRunBlockedApp:: com.samsung.ipservice, Auto Run ON
,09-16 11:36:14.912  9949  9949 D BluetoothSocket: bindListen(): myUserId = 0
09-16 11:36:14.912  9949  9949 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:36:14.912 10335 10335 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 11:36:14.922 10335 10335 D RelationGraph: garbageCollect()
,09-16 11:36:14.922  9949  9959 D A2dpStateMachine: getConnectedDevices : size=0
,09-16 11:36:14.922  9949 10347 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-16 11:36:14.922  9949 10347 D BluetoothSdpJni: SDP Create record success - handle: 0
09-16 11:36:14.922  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{7847bab: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.922 10335 10335 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package com.sec.android.provider.badge
,09-16 11:36:14.922  9949  9949 D BluetoothSocket: bindListen(): myUserId = 0
09-16 11:36:14.922  9949  9949 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:36:14.922  3459  4424 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 11:36:14.922 10335 10335 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 11:36:14.932  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{258f208: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.932  9949  9949 D ObexServerSockets: Succeed to create listening sockets 
09-16 11:36:14.932  9949  9949 D ObexServerSockets: startAccept()
,09-16 11:36:14.932 10335 10335 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 11:36:14.932  9949 10348 D ObexServerSockets: Accepting socket connection for masId0
,09-16 11:36:14.932  9949 10349 D ObexServerSockets: Accepting socket connection for masId0
,09-16 11:36:14.942  9949  9949 D BluetoothMapMasInstance: set MAP SDP message type : 1
09-16 11:36:14.942 10335 10335 I InjectionManager: Inside getClassLibPath caller 
09-16 11:36:14.942  9949  9949 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-16 11:36:14.942  9949  9949 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-16 11:36:14.942  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{3cdada1: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.942 10335 10335 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
,09-16 11:36:14.942  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{5002bc6: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.952 10335 10335 D BadgeProvider: onCreate
,09-16 11:36:14.952 10335 10335 D BadgeProvider: DatabaseHelper
,09-16 11:36:14.952  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{f8d2787: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.952 10335 10335 D InjectionManager: InjectionManager
09-16 11:36:14.952 10335 10335 D InjectionManager: fillFeatureStoreMap com.sec.android.provider.badge
,09-16 11:36:14.952 10335 10335 I InjectionManager: Constructor com.sec.android.provider.badge, Feature store :{}
09-16 11:36:14.952 10335 10335 I InjectionManager: featureStore :{}
,09-16 11:36:14.952  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{a8f26b4: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.962  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{ff682dd: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.962  3459  4380 D RCPManagerService: exchangeData() failure , invalid userId
,09-16 11:36:14.962  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{bc33e52: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.962 10319 10319 D InjectionManager: InjectionManager
09-16 11:36:14.962 10319 10319 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
09-16 11:36:14.962 10319 10319 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
,09-16 11:36:14.962 10319 10319 I InjectionManager: featureStore :{}
,09-16 11:36:14.972  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{48ab523: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.972  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{e51fa20: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.972  3459  4536 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3459  pkgName : BADGE_UPDATE@CPU_MIN@1
,09-16 11:36:14.982  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{7dd6fd9: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.982  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{c32ed9e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.992 10335 10346 D BaseReflect: null getOwnClass TEST
,09-16 11:36:14.992 10335 10346 D MethodReflector: android.content.ContentResolver getClass TEST
09-16 11:36:14.992 10335 10346 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
09-16 11:36:14.992 10335 10346 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
09-16 11:36:14.992  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{c49807f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:14.992  4154  4154 D CatchNotificationsService: Update badge
,09-16 11:36:14.992  4323  4323 D Launcher.Model: reloadBadges entered.
,09-16 11:36:14.992  5818  5818 D BadgeManager: onChange
,09-16 11:36:15.002  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{1ac984c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.002 10335 10345 D BadgeProvider: query, [selection] : null
,09-16 11:36:15.002 10335 10355 D BadgeProvider: query, [selection] : null
,09-16 11:36:15.002  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{c30ed38: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:15.012 10335 10346 D MethodReflector: notifyChange is called
,09-16 11:36:15.012  3459  6141 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:15.012  4323  4323 D Launcher.Model: reloadBadges entered.
09-16 11:36:15.012  5818  5818 D BadgeManager: onChange
,09-16 11:36:15.012 10335 10346 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
09-16 11:36:15.012 10335 10346 D BadgeProvider: sendNotify, [notify] : null
09-16 11:36:15.012 10335 10346 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
09-16 11:36:15.012 10335 10346 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-16 11:36:15.012 10335 10346 D BadgeProvider: update, [uri.query] : null
09-16 11:36:15.012 10335 10346 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-16 11:36:15.012 10335 10346 D BadgeProvider: update, [UpdateCount] : 1
,09-16 11:36:15.012  4323  4476 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
09-16 11:36:15.012  4323  4476 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
09-16 11:36:15.012  4323  4476 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
09-16 11:36:15.012  4323  4476 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
09-16 11:36:15.012  4323  4476 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
,09-16 11:36:15.012  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:15.022  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{a6c4111: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.022  4154  4154 D CatchNotificationsService: Update badge
,09-16 11:36:15.042  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{111276: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.042 10335 10355 D BadgeProvider: query, [selection] : null
,09-16 11:36:15.042 10335 10345 D BadgeProvider: query, [selection] : null
,09-16 11:36:15.042  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{8290077: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.052  4323  4476 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
09-16 11:36:15.052  4323  4476 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
09-16 11:36:15.052  4323  4476 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
09-16 11:36:15.052  4323  4476 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
09-16 11:36:15.052  4323  4476 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
,09-16 11:36:15.052  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{aa3a4e4: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 11:36:15.062  3459  3979 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 11:36:15.082  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{42dd4d: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.082  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{273e002: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.082  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{d232d13: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.082  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{f682b50: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.082  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{c6d0149: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.092  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{843fa4e: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.092  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{189876f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.092  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{dacac7c: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.092  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{2fb6905: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.092  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{de96d5a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.092  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{9512b8b: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.102  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{b561468: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.102  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{e4e9081: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.102  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{c410526: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.102  3459  4053 V AlarmManager:  remove PendingIntent] PendingIntent{8a4f567: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.112  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{5ac0f14: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.112  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{452b3bd: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.112  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{b284db2: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.112  3459  3974 V AlarmManager:  remove PendingIntent] PendingIntent{1818103: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.122  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{4c50880: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.122  3459  4536 V AlarmManager:  remove PendingIntent] PendingIntent{37bceb9: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.122  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{c992fe: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.122  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{f112a5f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.132  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{9b22cac: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.132  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{3819d75: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.132  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{9a7e10a: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.132  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{ac80d7b: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.142  3459  4864 V AlarmManager:  remove PendingIntent] PendingIntent{36b6798: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.142  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{5db9bf1: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.142  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{56b03d6: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.202  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:15.372  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:15.482  9949 10358 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,09-16 11:36:15.482  9949 10358 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-16 11:36:15.522 10335 10357 D BadgeProvider: query, [selection] : null
,09-16 11:36:15.552  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:15.612  9697  9762 D BluetoothAdapter: disable()
,09-16 11:36:15.622  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7400657 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
,09-16 11:36:15.622  3459  3570 D SecContentProvider: insert(), uri = 2
09-16 11:36:15.622  3459  4536 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,09-16 11:36:15.632  9949 10254 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,09-16 11:36:15.632  9949 10254 D BluetoothAdapterProperties: Setting state to 13
09-16 11:36:15.632  9949 10254 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-16 11:36:15.632  9949 10254 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-16 11:36:15.632  9949 10254 D BluetoothAdapterService: updateAdapterState state is 13
,09-16 11:36:15.632  9949  9949 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-16 11:36:15.632  9949 10254 D BluetoothAdapterService: Autoconnection is available 
09-16 11:36:15.632  9949 10254 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-16 11:36:15.632  9949 10254 D BluetoothAdapterService: terminating service from this receiver
09-16 11:36:15.632  3459  3570 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
,09-16 11:36:15.642  9949 10254 D BluetoothAdapterProperties: onBluetoothDisable()
09-16 11:36:15.642  9356  9356 D BluetoothPbap: Proxy object disconnected
09-16 11:36:15.642  3949  3949 D BluetoothPbap: Proxy object disconnected
09-16 11:36:15.642  9356  9356 D PbapServerProfile: Bluetooth service disconnected
09-16 11:36:15.642  3949  3949 D PbapServerProfile: Bluetooth service disconnected
,09-16 11:36:15.642  3459  3459 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:15.642  3459  3459 I InputMethodManagerService: [BT Setting State] State =13
,09-16 11:36:15.642  9949 10254 W bt_btif : btif_dm_cancel_discovery
,09-16 11:36:15.642  3459  4412 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,09-16 11:36:15.642  3949  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:15.642  3949  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-16 11:36:15.642  3459  4424 D SecContentProvider: insert(), uri = 2
09-16 11:36:15.642  4346  4346 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,09-16 11:36:15.652  9949 10254 I BluetoothAdapterState: Entering PendingCommandState
,09-16 11:36:15.652  3459  4049 V AlarmManager:  remove PendingIntent] PendingIntent{67b6544: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.652  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-16 11:36:15.652  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:15.652  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,09-16 11:36:15.652  7545  7545 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-16 11:36:15.652  9356  9356 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:15.652  9356  9356 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-16 11:36:15.662  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:36:15.662  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:15.662  9697  9697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:36:15.662  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:36:15.662  9697  9697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:36:15.662  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1fd062d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf426af 9356:com.android.settings/1000}
09-16 11:36:15.662  9697  9697 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:36:15.662  9697  9697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:36:15.672  9949 10258 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-16 11:36:15.672  9949 10258 D BluetoothAdapterProperties: Scan Mode:20
,09-16 11:36:15.672  9949 10254 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,09-16 11:36:15.672  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{46b8762: PendingIntentRecord{cd4b0f3 com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.682  9949 10254 E BluetoothServiceJni: disableBrEdrNative:
09-16 11:36:15.682  9949 10254 E bt_bluedroid: disable_bredr
09-16 11:36:15.682  9356  9356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 11:36:15.682  9949 10299 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 11:36:15.682  9949 10255 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-16 11:36:15.682  9949 10348 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 11:36:15.682  9949 10348 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-16 11:36:15.682  9949 10255 E bt_btif : BTA_DisableBluetoothOnly
09-16 11:36:15.682  9949 10349 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 11:36:15.682  9949 10349 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-16 11:36:15.682  9949 10275 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-16 11:36:15.682  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.682  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:36:15.692  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{950d829: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:15.692  9949 10255 D IOP_DB_BT: db_close: nbr users 0
09-16 11:36:15.692  9949 10255 D IOP_DB_BT: db_close: free database
09-16 11:36:15.692  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:36:15.692  3949  4176 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
09-16 11:36:15.692  3459  4424 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-16 11:36:15.692  3949  3949 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
09-16 11:36:15.702  3459  4834 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1fd062d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
09-16 11:36:15.712  3459  4834 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1fd062d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5287a2d 4271:com.google.android.gms.persistent/u0a21}
09-16 11:36:15.722  4271  4271 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.722  9949 10275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:36:15.732  9356  9356 D DockEventReceiver: finishStartingService: stopping service
09-16 11:36:15.732  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{1feb7ae: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:15.732  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:15.742  3459  4834 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1fd062d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1de32d 8934:com.sec.android.app.shealth:remote/u0a39}
,09-16 11:36:15.752  9949  9949 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:15.752  9949  9949 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
,09-16 11:36:15.752  9949  9949 D ObexServerSockets: shutdown(block = true)
09-16 11:36:15.752  9949  9949 D ObexServerSockets: shutdown called from another thread - interrupt().
09-16 11:36:15.752  9949  9949 D ObexServerSockets: shutdown called from another thread - interrupt().
09-16 11:36:15.752  9949  9949 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
,09-16 11:36:15.752  9949  9949 D BluetoothSdpJni: SDP Remove record success - handle: 1
09-16 11:36:15.752  9949  9949 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
09-16 11:36:15.752  9949  9949 D BluetoothSdpJni: SDP Remove record success - handle: 0
,09-16 11:36:15.752  9949  9949 I BtOppRfcommListener: stopping Accept Thread
09-16 11:36:15.752  9949 10299 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-16 11:36:15.762  3459  4834 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1fd062d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf426af 9356:com.android.settings/1000}
,09-16 11:36:15.762  9356  9356 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:15.762  9356  9356 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
,09-16 11:36:15.762  3459  4412 V AlarmManager:  remove PendingIntent] PendingIntent{3ff694f: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.772  3459  3979 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1fd062d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{957b75a 9789:com.samsung.android.intelligenceservice2/5010}
,09-16 11:36:15.782  3459  3979 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1fd062d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b26bf8 9949:com.android.bluetooth/1002}
,09-16 11:36:15.792  9949  9949 V BluetoothOppManager: cleanUp...
,09-16 11:36:15.802  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1fd062d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc9767 9803:com.google.android.apps.maps/u0a125}
,09-16 11:36:15.882  9949 10258 E BluetoothAdapterState: stateChangeCallback : 16
09-16 11:36:15.882  3459  3483 V AlarmManager:  remove PendingIntent] PendingIntent{7f018dc: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:15.882  9949 10254 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
,09-16 11:36:15.882  9949 10254 D BtConfig.SecureMode: isSecureModeOn:false
09-16 11:36:15.882  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-16 11:36:15.892  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-16 11:36:15.892  9949  9949 D HeadsetService: Received stop request...Stopping profile...
,09-16 11:36:15.892  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-16 11:36:15.892  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
09-16 11:36:15.892  9949  9949 E HeadsetService: notifyProfileServiceStateChanged
,09-16 11:36:15.892  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-16 11:36:15.892  9356  9356 D HeadsetProfile: Bluetooth service disconnected
,09-16 11:36:15.902  3949  3949 D HeadsetProfile: Bluetooth service disconnected
,09-16 11:36:15.902  3459  3459 D BluetoothHeadset: unRegisterMessageListener : 11
09-16 11:36:15.902  3459  3459 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
09-16 11:36:15.902  3459  3459 W BluetoothHeadset: Proxy not attached to service
,09-16 11:36:15.902  3459  3459 I Telecom : BluetoothManager : unregister MessageListener
09-16 11:36:15.902  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-16 11:36:15.902  9949  9949 D A2dpService: Received stop request...Stopping profile...
09-16 11:36:15.902  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-16 11:36:15.902  9949 10282 D A2dpStateMachine: Exit Disconnected: -1
,09-16 11:36:15.902  9949  9949 D Avrcp   : unregisterContentObserver
09-16 11:36:15.902  9949  9949 D Avrcp   : removeOnActiveSessionsChangedListener
09-16 11:36:15.902  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
09-16 11:36:15.902  9949  9949 E A2dpService: notifyProfileServiceStateChanged
,09-16 11:36:15.902  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
09-16 11:36:15.902  3459  3459 D BluetoothA2dp: Proxy object disconnected
09-16 11:36:15.902  3949  3949 D BluetoothA2dp: Proxy object disconnected
,09-16 11:36:15.902  3949  3949 D A2dpProfile: Bluetooth service disconnected
09-16 11:36:15.902  9356  9356 D BluetoothA2dp: Proxy object disconnected
09-16 11:36:15.902  9356  9356 D A2dpProfile: Bluetooth service disconnected
09-16 11:36:15.902  5041  5041 D BluetoothA2dp: Proxy object disconnected
09-16 11:36:15.902  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:15.902  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
,09-16 11:36:15.902  9949  9949 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:15.902  9949  9949 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:15.902  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:15.902  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:15.902  9949  9949 D HidService: Received stop request...Stopping profile...
,09-16 11:36:15.902  9949  9949 D HidService: Stopping Bluetooth HidService
09-16 11:36:15.902  9949  9949 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-16 11:36:15.902  9949  9949 W bt_btif : cleanup: HH disabling or disabled already, status = 0
09-16 11:36:15.902  9949  9949 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-16 11:36:15.902  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
09-16 11:36:15.912  9949  9949 E HidService: notifyProfileServiceStateChanged
,09-16 11:36:15.912  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-16 11:36:15.912  9949 10254 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-16 11:36:15.912  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-16 11:36:15.912  9949 10254 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-16 11:36:15.912  9949 10254 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
09-16 11:36:15.912  3949  3949 D BluetoothInputDevice: Proxy object disconnected
09-16 11:36:15.912  3949  3949 D HidProfile: Bluetooth service disconnected
,09-16 11:36:15.912  3949  3949 D BluetoothInputDevice: Proxy object disconnected
09-16 11:36:15.912  3949  3949 D HidProfile: Bluetooth service disconnected
09-16 11:36:15.912  9356  9356 D BluetoothInputDevice: Proxy object disconnected
09-16 11:36:15.912  9356  9356 D HidProfile: Bluetooth service disconnected
,09-16 11:36:15.912  9949  9949 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-16 11:36:15.912  9949  9949 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-16 11:36:15.912  9949  9949 D HeadsetProvider: cleanup
09-16 11:36:15.912  9949  9949 I HeadsetProvider: clearAllHeadsetSettings(0)
,09-16 11:36:15.912  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:15.922  9949  9949 D HealthService: Received stop request...Stopping profile...
,09-16 11:36:15.922  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
09-16 11:36:15.922  9949  9949 E HealthService: notifyProfileServiceStateChanged
,09-16 11:36:15.922  9949  9949 D PanService: Received stop request...Stopping profile...
09-16 11:36:15.922  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
09-16 11:36:15.922  9949  9949 E PanService: notifyProfileServiceStateChanged
,09-16 11:36:15.932  3459  3459 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 11:36:15.932  3949  3949 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-16 11:36:15.932  3949  3949 D PanProfile: Bluetooth service disconnected
09-16 11:36:15.932  9356  9356 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-16 11:36:15.932  9356  9356 D PanProfile: Bluetooth service disconnected
09-16 11:36:15.932  9949  9949 D BluetoothMapService: Received stop request...Stopping profile...
,09-16 11:36:15.932  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
,09-16 11:36:15.932  9949  9949 E BluetoothMapService: notifyProfileServiceStateChanged
,09-16 11:36:15.932  3949  3949 D BluetoothMap: Proxy object disconnected
09-16 11:36:15.932  3949  3949 D MapProfile: Bluetooth service disconnected
09-16 11:36:15.932  9356  9356 D BluetoothMap: Proxy object disconnected
09-16 11:36:15.932  9356  9356 D MapProfile: Bluetooth service disconnected
,09-16 11:36:15.932  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 11:36:15.932  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
09-16 11:36:15.932  9949  9949 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:15.932  9949  9949 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:15.932  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:15.932  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 11:36:15.932  9949  9949 D SapService: Received stop request...Stopping profile...
09-16 11:36:15.932  9949  9949 V SapService: stop()
09-16 11:36:15.942  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
09-16 11:36:15.942  9949  9949 E SapService: notifyProfileServiceStateChanged
,09-16 11:36:15.942  9356  9356 D BluetoothSap: Proxy object disconnected
09-16 11:36:15.942  9356  9356 D SapProfile: Bluetooth service disconnected
,09-16 11:36:15.942  3949  3949 D BluetoothSap: Proxy object disconnected
09-16 11:36:15.942  3949  3949 D SapProfile: Bluetooth service disconnected
09-16 11:36:15.942  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 11:36:15.942  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
09-16 11:36:15.942  9949  9949 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:15.942  9949  9949 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:15.942  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:15.942  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:15.942  9949  9949 D BluetoothAdapterService: HID Host service will be diabled
09-16 11:36:15.942  9949  9949 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-16 11:36:15.942  9949  9949 D BleAudioService: Received stop request...Stopping profile...
,09-16 11:36:15.942  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
09-16 11:36:15.942  9949 10288 E BleAudioStateMachine_R: Exit Disconnected: -1
09-16 11:36:15.942  9949  9949 E BleAudioService: notifyProfileServiceStateChanged
09-16 11:36:15.942  9949 10287 E BleAudioStateMachine_L: Exit Disconnected: -1
,09-16 11:36:15.942  9356  9356 D BluetoothLeAudio: Proxy object disconnected
,09-16 11:36:15.942  3949  3949 D BluetoothLeAudio: Proxy object disconnected
09-16 11:36:15.942  3949  3949 D BleAudioProfile: Bluetooth service disconnected
09-16 11:36:15.942  9356  9356 D BleAudioProfile: Bluetooth service disconnected
,09-16 11:36:15.942  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:15.942  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
,09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isTurningOn()=false
,09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:15.952  9949  9949 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-16 11:36:15.952  9949  9949 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-16 11:36:15.952  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:15.952  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
,09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:15.952  9949  9949 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-16 11:36:15.952  9949  9949 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-16 11:36:15.952  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 11:36:15.952  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:15.952  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 11:36:15.952  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:15.952  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
,09-16 11:36:15.952  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isTurningOff()=true
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:36:15.952  9949  9949 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:36:15.952  9949 10254 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
09-16 11:36:15.952  9949  9949 V BleAudioService: [unregisterCallStateListener]
09-16 11:36:15.952  9949 10254 D BluetoothAdapterProperties: Setting state to 15
09-16 11:36:15.952  9949 10254 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-16 11:36:15.952  9949  9949 W BtBleAudio.JNI: WARNING: cleanupNative(L364): Cleaning up  Ble audio left callback object##
09-16 11:36:15.952  9949  9949 W BtBleAudio.JNI: WARNING: cleanupNative(L382): Cleaning up Ble audio Interface...##
09-16 11:36:15.952  9949  9949 W BtBleAudio.JNI: WARNING: cleanupNative(L370): Cleaning up  Ble audio right callback object##
09-16 11:36:15.952  9949 10254 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-16 11:36:15.952  9949 10254 D BluetoothAdapterService: updateAdapterState state is 15
09-16 11:36:15.952  9949  9949 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
09-16 11:36:15.952  9949 10254 D BluetoothAdapterService: Autoconnection is available 
09-16 11:36:15.952  9949 10254 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
,09-16 11:36:15.952  3949  4836 D BluetoothLeAudio: onBluetoothStateChange: up=false
09-16 11:36:15.952  9949 10254 I BluetoothAdapterState: Entering BleOnState
,09-16 11:36:15.952  3949  4836 D BluetoothLeAudio: Unbinding service...
09-16 11:36:15.952  3949  4385 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:15.952  3949  4385 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 11:36:15.962  3949  4385 D BluetoothAdapter: There are no active google scan apps, stop scan
09-16 11:36:15.962  9356  9366 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-16 11:36:15.962  4271  4869 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:15.962  4271  4869 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 11:36:15.962  4271  4869 D BluetoothAdapter: There are no active google scan apps, stop scan
09-16 11:36:15.962  4271  4869 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-16 11:36:15.962  4271  4869 D BluetoothLeScanner: Exiting stopAllScan
,09-16 11:36:15.962  9356  9367 D BluetoothLeAudio: onBluetoothStateChange: up=false
09-16 11:36:15.962  9356  9367 D BluetoothLeAudio: Unbinding service...
09-16 11:36:15.962  4305  4627 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:15.962  4305  4627 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 11:36:15.962  4305  4627 D BluetoothAdapter: There are no active google scan apps, stop scan
09-16 11:36:15.962  9356  9366 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-16 11:36:15.962  8934  8945 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-16 11:36:15.962  8934  8945 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 11:36:15.962  8934  8945 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 11:36:15.962  3949  3971 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 11:36:15.962  5041  5061 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-16 11:36:15.962  3949  4565 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-16 11:36:15.972  3459  3570 D BluetoothPan: onBluetoothStateChange on: false
09-16 11:36:15.972  4299  7648 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:15.972  4299  7648 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 11:36:15.972  4299  7648 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 11:36:15.972  9356  9367 D BluetoothPan: onBluetoothStateChange on: false
,09-16 11:36:15.972  3949  4836 D BluetoothSap: onBluetoothStateChange: up=false
,09-16 11:36:15.972  3949  4385 D BluetoothPbap: onBluetoothStateChange: up=false
,09-16 11:36:15.972  9949 10293 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:15.972  9949 10293 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 11:36:15.972  9949 10293 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 11:36:15.972  3949  3971 D BluetoothMap: onBluetoothStateChange: up=false
,09-16 11:36:15.982  3949  4565 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-16 11:36:15.982  9803  9813 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:15.982  9803  9813 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 11:36:15.982  9803  9813 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 11:36:15.982  3459  3570 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:15.982  3459  3570 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 11:36:15.982  3459  3570 D BluetoothAdapter: There are no active google scan apps, stop scan
09-16 11:36:15.982  9697  9707 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:15.982  9697  9707 D BluetoothAdapter: Bluetooth is turned off, stop adv
09-16 11:36:15.982  9697  9707 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-16 11:36:15.982  9697  9707 D BluetoothLeAdvertiser: Exit stop advertising
,09-16 11:36:15.982  9697  9707 D BluetoothAdapter: There are no active google scan apps, stop scan
09-16 11:36:15.982  9697  9707 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-16 11:36:15.982  9697  9707 D BluetoothLeScanner: Exiting stopAllScan
09-16 11:36:15.982  9356  9367 D BluetoothMap: onBluetoothStateChange: up=false
,09-16 11:36:15.982  3459  3570 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-16 11:36:15.982  3949  3961 D BluetoothPan: onBluetoothStateChange on: false
,09-16 11:36:15.982  5041  5133 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:15.982  5041  5133 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 11:36:15.982  5041  5133 D BluetoothAdapter: There are no active google scan apps, stop scan
09-16 11:36:15.982  9356  9366 D BluetoothPbap: onBluetoothStateChange: up=false
,09-16 11:36:15.982  9356  9367 D BluetoothAdapter: onBluetoothStateChange: up=false
09-16 11:36:15.982  9356  9367 D BluetoothAdapter: Bluetooth is turned off, stop adv
,09-16 11:36:15.982  9356  9367 D BluetoothAdapter: There are no active google scan apps, stop scan
,09-16 11:36:15.992  9356  9366 D BluetoothSap: onBluetoothStateChange: up=false
,09-16 11:36:15.992  9949 10254 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,09-16 11:36:15.992  3459  3459 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:15.992  3459  3459 I InputMethodManagerService: [BT Setting State] State =10
09-16 11:36:15.992  3459  3459 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-16 11:36:15.992  3949  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,09-16 11:36:15.992  4346  4346 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:15.992  3949  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-16 11:36:15.992  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
09-16 11:36:15.992  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:15.992  3459  3459 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,09-16 11:36:16.002  7545  7545 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-16 11:36:16.002  9356  9356 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:16.002  9356  9356 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-16 11:36:16.002  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:16.002  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:16.012  3459  3543 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef5cde5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf426af 9356:com.android.settings/1000}
,09-16 11:36:16.012  9949 10254 D BluetoothAdapterProperties: Setting state to 16
09-16 11:36:16.012  9949 10254 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-16 11:36:16.012  9949 10254 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-16 11:36:16.012  9949 10254 D BluetoothAdapterService: updateAdapterState state is 16
09-16 11:36:16.012  3459  3570 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
09-16 11:36:16.012  9949 10254 D BluetoothAdapterService: Autoconnection is available 
09-16 11:36:16.012  9949 10254 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
09-16 11:36:16.012  9949 10254 D BluetoothAdapterProperties: onBleDisable
,09-16 11:36:16.012  9356  9356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 11:36:16.012  3459  3484 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,09-16 11:36:16.012  3949  4176 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
09-16 11:36:16.012  3459  4424 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-16 11:36:16.012  3459  4208 D SecContentProvider: insert(), uri = 2
,09-16 11:36:16.012  9949 10254 I BluetoothAdapterState: Entering PendingCommandState
09-16 11:36:16.012  9949 10255 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-16 11:36:16.012  9949 10255 E bt_btif : btif_vhci_sock_cleanup
,09-16 11:36:16.022  3459  4856 V AlarmManager:  remove PendingIntent] PendingIntent{9734b6b: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:16.022  9949 10275 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-16 11:36:16.022  9949 10258 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-16 11:36:16.022  9949 10258 D BluetoothAdapterProperties: Scan Mode:20
,09-16 11:36:16.032  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:16.032  9697  9697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:36:16.042  3459  4049 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef5cde5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b1f51b 5041:com.samsung.android.providers.context/u0a9}
,09-16 11:36:16.042  9356  9356 D DockEventReceiver: finishStartingService: stopping service
,09-16 11:36:16.052  3459  4834 V AlarmManager:  remove PendingIntent] PendingIntent{6d3e6c8: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:16.052  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef5cde5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5287a2d 4271:com.google.android.gms.persistent/u0a21}
,09-16 11:36:16.052  4271  4271 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,09-16 11:36:16.072  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef5cde5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1de32d 8934:com.sec.android.app.shealth:remote/u0a39}
,09-16 11:36:16.082  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef5cde5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf426af 9356:com.android.settings/1000}
,09-16 11:36:16.082  9356  9356 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:36:16.082  9356  9356 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,09-16 11:36:16.092  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef5cde5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{957b75a 9789:com.samsung.android.intelligenceservice2/5010}
,09-16 11:36:16.092  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:16.102  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef5cde5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b26bf8 9949:com.android.bluetooth/1002}
,09-16 11:36:16.102  9949 10364 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
09-16 11:36:16.102  9949 10364 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,09-16 11:36:16.112  3459  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef5cde5 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc9767 9803:com.google.android.apps.maps/u0a125}
,09-16 11:36:16.222  9949 10258 I bt_hci  : shut_down
,09-16 11:36:16.222  9949 10271 D bt_hwcfg: hw_epilog_process
09-16 11:36:16.222  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{f3a6361: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:16.222  9949 10271 I bt_vendor: low_power_mode_cb
,09-16 11:36:16.222  9949 10271 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-16 11:36:16.222  9949 10271 I bt_vendor: epilog_cb
09-16 11:36:16.222  9949 10271 I bt_hci  : epilog_finished_callback
,09-16 11:36:16.222  9949 10258 I bt_hci_h4: hal_close
,09-16 11:36:16.222  9949 10258 I bt_userial_vendor: device fd = 61 close
,09-16 11:36:16.222  9949 10258 I bt_upio : upio_set_bluetooth_power(on: 0)
09-16 11:36:16.222  3459  4208 V AlarmManager:  remove PendingIntent] PendingIntent{42a0e86: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:16.232  9949 10255 D bt_stack_manager: event_shut_down_stack finished.
,09-16 11:36:16.232  9949 10258 E BluetoothAdapterState: stateChangeCallback : 0
09-16 11:36:16.232  9949 10254 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
,09-16 11:36:16.232  3459  4380 V AlarmManager:  remove PendingIntent] PendingIntent{7f93347: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:16.232  9949  9949 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 11:36:16.232  9949 10254 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-16 11:36:16.232  3459  4386 V AlarmManager:  remove PendingIntent] PendingIntent{2a4a774: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
09-16 11:36:16.232  9949  9949 D BtGatt.GattService: Received stop request...Stopping profile...
,09-16 11:36:16.232  9949  9949 D BtGatt.GattService: stop()
09-16 11:36:16.232  9949  9949 D BtGatt.GattService: [GSIM LOG]: saveLogPref
09-16 11:36:16.232  3459  3484 V AlarmManager:  remove PendingIntent] PendingIntent{2d8d49d: PendingIntentRecord{1001aff com.android.bluetooth broadcastIntent}}
,09-16 11:36:16.232  9949  9949 D BtGatt.GattService: [GSIM LOG]: saveLogPref END
09-16 11:36:16.232  9949  9949 D BtGatt.GattService: cleanup binder
09-16 11:36:16.232  9949  9949 D BtGatt.AdvertiseManager: advertise clients cleared
09-16 11:36:16.232  9949  9949 D BtGatt.ScanManager: cleanup
09-16 11:36:16.232  9949  9949 D BtGatt.ScanManager: cleanup handler
09-16 11:36:16.232  9949  9949 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
09-16 11:36:16.232  9949  9949 E BtGatt.GattService: notifyProfileServiceStateChanged
,09-16 11:36:16.232  9949  9949 E BluetoothAdapterService: handleMessage() - Message: 1
09-16 11:36:16.232  9949  9949 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
,09-16 11:36:16.232  9949  9949 V BluetoothAdapterState: isTurningOff()=false
09-16 11:36:16.232  9949  9949 V BluetoothAdapterState: isTurningOn()=false
09-16 11:36:16.232  9949  9949 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 11:36:16.232  9949  9949 V BluetoothAdapterState: isBleTurningOff()=true
09-16 11:36:16.232  9949 10254 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
09-16 11:36:16.242  9949 10254 D BluetoothAdapterProperties: Setting state to 10
09-16 11:36:16.242  9949 10254 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-16 11:36:16.242  9949 10254 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-16 11:36:16.242  9949 10254 D BluetoothAdapterService: updateAdapterState state is 10
09-16 11:36:16.242  9949 10254 D BluetoothAdapterService: Autoconnection is available 
09-16 11:36:16.242  9949 10254 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
,09-16 11:36:16.242  9949 10254 D BluetoothAdapterService: BT on, init HID DEV count : 0
09-16 11:36:16.242  9949 10254 I BluetoothAdapterState: Entering OffState
09-16 11:36:16.242  3459  3979 V AlarmManager:  remove PendingIntent] PendingIntent{5888d12: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:16.242  3459  3570 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-16 11:36:16.242  3459  4424 V AlarmManager:  remove PendingIntent] PendingIntent{40bbce3: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:16.252  3459  4416 V AlarmManager:  remove PendingIntent] PendingIntent{71ec6e0: PendingIntentRecord{94857bc com.android.bluetooth broadcastIntent}}
,09-16 11:36:16.252  9949  9949 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-16 11:36:16.252  9949  9949 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-16 11:36:16.252  9949  9949 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-16 11:36:16.252  9949 10255 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-16 11:36:16.252  9949  9949 I art     : System.exit called, status: 0
09-16 11:36:16.252  9949  9949 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-16 11:36:16.282  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:16.282  3459  3979 I ActivityManager: Process com.android.bluetooth (pid 9949)(adj 0) has died(76,1770)
09-16 11:36:16.282  3459  3979 D ActivityManager: isAutoRunBlockedApp:: com.android.bluetooth, Auto Run ON
,09-16 11:36:16.452  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:16.632  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 11:36:16.812  3459  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
