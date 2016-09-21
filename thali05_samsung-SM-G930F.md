#### Test 861478345ecb88c_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-21 17:05:29.212  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:29.392  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:29.572  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:29.752  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:29.932  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:29.932  9314  9314 I FIPS_bssl: FIPS approved mode (1) | 9314 | app_process
09-21 17:05:29.942  9314  9314 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 17:05:29.942  9314  9314 D AndroidRuntime: CheckJNI is OFF
09-21 17:05:29.942  9314  9314 D AndroidRuntime: readGMSProperty: start
09-21 17:05:29.942  9314  9314 D AndroidRuntime: readGMSProperty: already setted!!
09-21 17:05:29.942  9314  9314 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-21 17:05:29.942  9314  9314 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-21 17:05:29.942  9314  9314 D AndroidRuntime: readGMSProperty: end
09-21 17:05:29.942  9314  9314 D AndroidRuntime: addProductProperty: start
09-21 17:05:29.962  9314  9314 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 17:05:29.982  9314  9314 I Radio-JNI: register_android_hardware_Radio DONE
09-21 17:05:29.982  9314  9314 E AffinityControl: AffinityControl: registerfunction enter
09-21 17:05:29.992  9314  9314 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-21 17:05:30.022  3425  4048 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-21 17:05:30.022  3425  4048 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-21 17:05:30.042  3425  4048 D ResourcesManager: For user 0 new overlays fetched Null
09-21 17:05:30.042  3425  4048 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 17:05:30.042  3425  4048 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-21 17:05:30.052  3425  4048 D ActivityManager: mDVFSHelper.acquire()
09-21 17:05:30.052  3425  4048 V WindowManager: addAppToken: AppWindowToken{d0a718905 token=Token{ea74c7c ActivityRecord{54aa76f u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-21 17:05:30.062  3425  3537 I InjectionManager: Inside getClassLibPath caller 
09-21 17:05:30.062  3425  3537 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-21 17:05:30.062  3425  3537 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6cd3bd V.E...... R.....ID 0,0-0,0}
09-21 17:05:30.072  9323  9323 E Zygote  : v2
09-21 17:05:30.072  9323  9323 I libpersona: KNOX_SDCARD checking this for 10171
09-21 17:05:30.072  9323  9323 I libpersona: KNOX_SDCARD not a persona
09-21 17:05:30.072  9323  9323 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-21 17:05:30.072  3425  3537 W WindowManager: Failed looking up window
09-21 17:05:30.072  3425  3537 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@807edb2 does not exist
09-21 17:05:30.072  3425  3537 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 17:05:30.072  3425  3537 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-21 17:05:30.072  3425  3537 D ISSUE_DEBUG: InputChannelName : f78a103 Starting com.test.thalitest
09-21 17:05:30.072  9323  9323 E Zygote  : accessInfo : 0
09-21 17:05:30.072  9323  9323 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-21 17:05:30.072  3425  4048 I ActivityManager: Start proc 9323:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-21 17:05:30.072  3004  3004 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-21 17:05:30.092  6061  6061 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 17:05:30.102  3425  4521 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3425
09-21 17:05:30.102  3425  4521 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 17:05:30.102  3425  4521 D PowerManagerService: mDisplayReady: false
09-21 17:05:30.102  3425  4521 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 17:05:30.102  3425  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 17:05:30.102  3425  4048 D InputDispatcher: Focused application set to: xxxx
09-21 17:05:30.102  3425  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 17:05:30.102  3004  3004 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f7f6c3c00
09-21 17:05:30.102  3425  4521 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 17:05:30.102  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-21 17:05:30.102  3425  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:05:30.102  6061  6061 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 17:05:30.102  3425  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:05:30.102  3425  3555 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-21 17:05:30.102  3425  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 17:05:30.102  9323  9323 D TimaKeyStoreProvider: TimaSignature is unavailable
09-21 17:05:30.102  3425  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 17:05:30.102  9323  9323 D ActivityThread: Added TimaKeyStore provider
09-21 17:05:30.102  3425  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:05:30.102  3425  4594 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 17:05:30.102  3425  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:05:30.102  3425  4594 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 17:05:30.102  3425  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 17:05:30.102  9314  9314 D AndroidRuntime: Shutting down VM
09-21 17:05:30.102  3425  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 17:05:30.102  3425  3537 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 17:05:30.102  3425  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:05:30.102  3425  3537 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-21 17:05:30.102  3425  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:05:30.102  3425  3425 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 17:05:30.102  3425  4594 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3425
09-21 17:05:30.102  3425  4594 D PowerManagerService: mDisplayReady: true
09-21 17:05:30.112  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:30.102  3425  3541 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 17:05:30.102  3425  3541 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-21 17:05:30.102  3425  3853 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-21 17:05:30.112  3425  3425 I KnoxTimeoutHandler: SD activityfalse
09-21 17:05:30.122  3425  4046 V WindowStateAnimator: Finishing drawing window Window{fd5e0bc u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-21 17:05:30.122  4378  4439 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-21 17:05:30.122  4378  4439 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
09-21 17:05:30.142  3425  4237 D ActivityManager:  Launching com.test.thalitest, updated priority
09-21 17:05:30.152  3425  3537 V WindowStateAnimator: Finishing drawing window Window{f78a103 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-21 17:05:30.152  3425  3537 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-21 17:05:30.152  3425  3537 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-21 17:05:30.152  3004  3004 D libEGL  : eglInitialize EGLDisplay = 0x7ffbe7e068
09-21 17:05:30.162  3425  4316 V WindowStateAnimator: Finishing drawing window Window{39a848e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-21 17:05:30.162  6061  6061 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 17:05:30.162  6061  6061 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 17:05:30.162  6061  6061 V ActivityThread: updateVisibility : ActivityRecord{b0bfd5a token=android.os.BinderProxy@db772df {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-21 17:05:30.162  3425  3425 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-21 17:05:30.172  3004  4475 I SurfaceFlinger: id=16 Removed VSBConnecti (8/13)
09-21 17:05:30.172  3425  3514 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-21 17:05:30.172  3004  3004 D libEGL  : eglTerminate EGLDisplay = 0x7ffbe7e158
09-21 17:05:30.172  3004  3004 D libEGL  : eglTerminate EGLDisplay = 0x7ffbe7e158
09-21 17:05:30.172  3004  3829 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/13)
09-21 17:05:30.172  3004  3012 D libEGL  : eglTerminate EGLDisplay = 0x7f7f440e78
09-21 17:05:30.172  3004  3012 D libEGL  : eglTerminate EGLDisplay = 0x7f7f440e78
09-21 17:05:30.192  3004  4363 I SurfaceFlinger: id=9 Removed MauncherAct (3/12)
09-21 17:05:30.192  3004  3012 I SurfaceFlinger: id=9 Removed MauncherAct (-2/12)
09-21 17:05:30.192  3004  3004 D libEGL  : eglTerminate EGLDisplay = 0x7ffbe7e188
09-21 17:05:30.192  3004  4363 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
09-21 17:05:30.202  3004  3012 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-21 17:05:30.202  3004  3004 D libEGL  : eglTerminate EGLDisplay = 0x7ffbe7e158
09-21 17:05:30.212  4277  4277 V ActivityThread: updateVisibility : ActivityRecord{1da5508 token=android.os.BinderProxy@63ba071 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-21 17:05:30.212  4277  4277 D Launcher: onTrimMemory. Level: 20
09-21 17:05:30.222  4378  4439 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 102ms lastUpdatedAfter : 146054ms
09-21 17:05:30.252  3425  3425 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3425 (0x0)
09-21 17:05:30.252  3425  3425 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3425 (0x0)
09-21 17:05:30.252  3425  3425 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 17:05:30.252  3425  3425 D PowerManagerService: mDisplayReady: false
09-21 17:05:30.252  3425  3425 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 17:05:30.252  3425  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 17:05:30.252  3425  3425 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 17:05:30.252  3425  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 17:05:30.252  3425  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:05:30.252  3425  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:05:30.252  3425  3555 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-21 17:05:30.252  3004  3004 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f7f6c3c00
09-21 17:05:30.252  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-21 17:05:30.262  3425  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 17:05:30.262  3425  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 17:05:30.262  3425  3541 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 17:05:30.262  3425  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:05:30.262  3425  3541 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 17:05:30.262  3425  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:05:30.262  3425  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 17:05:30.262  3425  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 17:05:30.262  3425  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:05:30.262  3425  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:05:30.262  3425  3541 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 17:05:30.262  3425  3541 D PowerManagerService: mDisplayReady: true
09-21 17:05:30.262  3425  3541 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-21 17:05:30.282  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:30.472  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:30.512  3425  4237 I WindowManager: Screenshot max retries 4 of Token{ea74c7c ActivityRecord{54aa76f u0 com.test.thalitest/.MainActivity t4}} appWin=Window{f78a103 u0 d0 Starting com.test.thalitest} drawState=4
09-21 17:05:30.512  3425  3537 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 17:05:30.512  3425  3425 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 17:05:30.522  3425  5959 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 17:05:30.522  3425  5959 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 17:05:30.522  3425  3853 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-21 17:05:30.542  3425  3537 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-21 17:05:30.542  3425  3537 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-21 17:05:30.552  3425  3425 I KnoxTimeoutHandler: SD activityfalse
09-21 17:05:30.552  9323  9323 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 17:05:30.572  3425  4591 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-21 17:05:30.572  9323  9323 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-21 17:05:30.582  3425  5959 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-21 17:05:30.582  3425  5959 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 17:05:30.582  9323  9323 D ResourcesManager: For user 0 new overlays fetched Null
09-21 17:05:30.592  3425  5959 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-21 17:05:30.592  9323  9323 I InjectionManager: Inside getClassLibPath caller 
09-21 17:05:30.592  3425  5959 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 17:05:30.592  3425  5959 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 17:05:30.612  9323  9323 D InjectionManager: InjectionManager
09-21 17:05:30.612  9323  9323 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-21 17:05:30.612  9323  9323 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-21 17:05:30.612  9323  9323 I InjectionManager: featureStore :{}
09-21 17:05:30.622  9323  9323 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 17:05:30.622  9323  9323 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-21 17:05:30.622  9323  9323 D RelationGraph: garbageCollect()
09-21 17:05:30.632  9323  9323 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 17:05:30.642  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:30.662  9323  9323 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-21 17:05:30.702  9323  9323 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-21 17:05:30.702  9323  9323 D ResourcesManager: For user 0 new overlays fetched Null
09-21 17:05:30.702  9323  9323 I InjectionManager: Inside getClassLibPath caller 
09-21 17:05:30.702  9323  9323 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-21 17:05:30.742  9323  9323 I cr_LibraryLoader: Time to load native libraries: 22 ms (timestamps 5250-5272)
09-21 17:05:30.742  9323  9323 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-21 17:05:30.772  3425  3876 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-21 17:05:30.782  9323  9338 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-21 17:05:30.812  9323  9323 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e22790c}
09-21 17:05:30.812  9323  9323 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-21 17:05:30.822  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:30.832  9323  9323 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-21 17:05:30.862  9323  9323 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-21 17:05:30.872  3425  3876 I MdnieScenarioControlService: mGameModeLauncher : false
09-21 17:05:30.872  3425  3876 I MdnieScenarioControlService: setUIMode
09-21 17:05:31.002  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:31.012  3425  3514 W ActivityManager: Activity pause timeout for ActivityRecord{54aa76f u0 com.test.thalitest/.MainActivity t4}
09-21 17:05:31.032  9323  9323 D libEGL  : eglInitialize EGLDisplay = 0xff87168c
09-21 17:05:31.102  3425  3971 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
09-21 17:05:31.102  3425  3971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-21 17:05:31.172  9323  9323 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-21 17:05:31.182  9323  9323 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-21 17:05:31.182  9323  9323 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-21 17:05:31.182  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:31.202  9323  9323 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-21 17:05:31.252  9323  9323 D Activity: performCreate Call Injection manager
,09-21 17:05:31.252  9323  9323 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-21 17:05:31.262  9323  9323 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-21 17:05:31.262  9323  9323 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9d3f458 I.E...... R.....ID 0,0-0,0}
,09-21 17:05:31.272  9323  9375 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-21 17:05:31.272  3425  4316 W WindowManager: Failed looking up window
09-21 17:05:31.272  3425  4316 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@ab82d12 does not exist
09-21 17:05:31.272  3425  4316 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-21 17:05:31.272  3425  4316 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-21 17:05:31.272  3425  4316 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-21 17:05:31.272  3425  4316 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-21 17:05:31.272  3425  4316 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-21 17:05:31.272  3425  4316 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-21 17:05:31.282  3425  4594 D ISSUE_DEBUG: InputChannelName : c12dce3 com.test.thalitest/com.test.thalitest.MainActivity
,09-21 17:05:31.282  3425  4591 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-21 17:05:31.282  3425  4591 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 17:05:31.282  3425  3425 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-21 17:05:31.282  3425  3425 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-21 17:05:31.282  9323  9323 V ActivityThread: updateVisibility : ActivityRecord{c783e96 token=android.os.BinderProxy@80164e3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-21 17:05:31.292  9323  9338 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-21 17:05:31.312  9323  9323 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9323
,09-21 17:05:31.322  3425  4289 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9323 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-21 17:05:31.322  3425  3864 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-21 17:05:31.322  3425  3864 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-21 17:05:31.322  3425  3864 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-21 17:05:31.332  3425  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-21 17:05:31.332  3425  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-21 17:05:31.342  3425  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-21 17:05:31.342  9323  9323 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-21 17:05:31.342  3425  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-21 17:05:31.352  3425  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-21 17:05:31.352  3425  3864 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-21 17:05:31.352  3004  3004 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,09-21 17:05:31.362  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:31.372  9323  9375 D libEGL  : eglInitialize EGLDisplay = 0xdc33f7c4
09-21 17:05:31.372  9323  9375 I OpenGLRenderer: Initialized EGL, version 1.4
,09-21 17:05:31.372  9323  9375 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-21 17:05:31.372  3425  4409 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3425
09-21 17:05:31.372  3425  4409 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 17:05:31.372  3425  4409 D PowerManagerService: mDisplayReady: false
09-21 17:05:31.372  3425  4409 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 17:05:31.372  3425  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 17:05:31.372  3425  4409 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 17:05:31.372  3425  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,09-21 17:05:31.372  3425  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:05:31.382  3004  3004 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f7f6c3c00
09-21 17:05:31.372  3425  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:05:31.382  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-21 17:05:31.382  3425  3555 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,09-21 17:05:31.382  3425  3537 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-21 17:05:31.382  3425  3537 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-21 17:05:31.392  3425  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 17:05:31.392  3425  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 17:05:31.392  3425  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:05:31.392  3425  3541 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 17:05:31.392  3425  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:05:31.392  3425  3541 I libsuspend: !@autosuspend_wakeup_count_enable done
,09-21 17:05:31.392  3425  3541 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 17:05:31.392  3425  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 17:05:31.392  3425  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:05:31.392  3425  3541 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-21 17:05:31.392  3425  3541 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 17:05:31.392  3425  3541 D PowerManagerService: mDisplayReady: true
09-21 17:05:31.392  3425  3541 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-21 17:05:31.412  9323  9323 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-21 17:05:31.432  3425  4591 V WindowStateAnimator: Finishing drawing window Window{c12dce3 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-21 17:05:31.432  9323  9323 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-21 17:05:31.432  9323  9379 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 17:05:31.432  9323  9379 D libEGL  : eglInitialize EGLDisplay = 0xdac3f3f4
,09-21 17:05:31.432  3425  4048 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3425
09-21 17:05:31.442  3425  3537 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 17:05:31.442  3425  3425 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 17:05:31.442  3425  3425 I KnoxTimeoutHandler: SD activityfalse
,09-21 17:05:31.442  3425  4521 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3425
09-21 17:05:31.442  3425  3537 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +933ms (total +1s386ms)
09-21 17:05:31.442  3425  3537 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{54aa76f u0 com.test.thalitest/.MainActivity t4} time:255973
,09-21 17:05:31.442  3425  3537 D ActivityManager: mDVFSHelper.release()
,09-21 17:05:31.452  9323  9379 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-21 17:05:31.452  3425  3447 V WindowStateAnimator: Finishing drawing window Window{c12dce3 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN,
,09-21 17:05:31.452  3425  3537 D ViewRootImpl: #3 mView = null
09-21 17:05:31.452  3004  4363 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
,09-21 17:05:31.452  9323  9323 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@80164e3 time:255982
09-21 17:05:31.452  3004  3012 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,09-21 17:05:31.452  3004  3004 D libEGL  : eglTerminate EGLDisplay = 0x7ffbe7e188
,09-21 17:05:31.492  9323  9323 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9323
,09-21 17:05:31.522  3425  5960 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-21 17:05:31.542  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:31.592  3425  3425 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3425 (0x0)
09-21 17:05:31.592  3425  3425 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 17:05:31.592  3425  3425 D PowerManagerService: mDisplayReady: false
09-21 17:05:31.592  3425  3425 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 17:05:31.592  3425  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 17:05:31.592  3425  3425 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 17:05:31.592  3425  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 17:05:31.592  3425  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:05:31.592  3425  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:05:31.592  3425  3555 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-21 17:05:31.592  3425  3537 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-21 17:05:31.592  3004  3004 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f7f6c3c00
,09-21 17:05:31.592  3425  3537 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-21 17:05:31.592  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,09-21 17:05:31.602  3425  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 17:05:31.602  3425  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 17:05:31.602  3425  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:05:31.602  3425  3541 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 17:05:31.602  3425  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:05:31.602  3425  3541 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 17:05:31.602  3425  3541 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 17:05:31.602  3425  3541 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 17:05:31.602  3425  3541 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 17:05:31.602  3425  3541 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 17:05:31.602  3425  3541 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 17:05:31.602  3425  3541 D PowerManagerService: mDisplayReady: true
09-21 17:05:31.602  3425  3541 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-21 17:05:31.722  9323  9323 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-21 17:05:31.722  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:31.822  9323  9386 D jxcore_app_log: JniHelper::setJavaVM(0xf4a74000), pthread_self() = -632555216
,09-21 17:05:31.822  9323  9386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 17:05:31.822  9323  9386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 17:05:31.822  9323  9386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 17:05:31.822  9323  9386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 17:05:31.822  9323  9386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-21 17:05:31.822  9323  9386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d92388 added. We now have 1 listener(s)
,09-21 17:05:31.822  9323  9386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-21 17:05:31.832  9323  9386 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-21 17:05:31.832  9323  9386 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 17:05:31.832  9323  9386 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-21 17:05:31.832  9323  9386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90a2707 added. We now have 1 listener(s)
09-21 17:05:31.832  9323  9386 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 17:05:31.832  9323  9386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 17:05:31.832  9323  9386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-21 17:05:31.832  9323  9386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-21 17:05:31.832  9323  9386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 17:05:31.832  9323  9386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-21 17:05:31.832  9323  9386 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:05:31.832  9323  9386 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
09-21 17:05:31.842  9323  9386 D BluetoothAdapter: STATE_ON
09-21 17:05:31.842  9323  9386 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-21 17:05:31.842  9323  9386 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:05:31.842  9323  9386 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:05:31.842  9323  9386 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:05:31.842  9323  9386 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:05:31.842  9323  9386 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:05:31.842  9323  9386 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:05:31.842  9323  9386 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:05:31.842  9323  9386 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 17:05:31.842  9323  9386 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-21 17:05:31.842  9323  9386 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 17:05:31.852  9323  9386 I io.jxcore.node.LifeCycleMonitor: start: OK
09-21 17:05:31.852  9323  9323 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 17:05:31.862  9323  9323 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:05:31.872  9323  9323 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-21 17:05:31.902  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:32.012  4017  4017 D Recents : onTaskStackChanged
,09-21 17:05:32.012  4017  4017 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-21 17:05:32.022  4017  4017 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 17:05:32.082  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:32.182  9323  9387 W jxcore-log: Initializing JXcore engine
09-21 17:05:32.182  9323  9387 W jxcore-log: JXcore engine is ready
,09-21 17:05:32.202  4998  4998 E audit   : type=1400 msg=audit(1474470332.202:264): avc:  denied  { ioctl } for  pid=9387 comm="Thread-156" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1055 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-21 17:05:32.202  4998  4998 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-21 17:05:32.202  4998  4998 E audit   : type=1300 msg=audit(1474470332.202:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=da3ba3c8 items=0 ppid=3174 pid=9387 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-156" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-21 17:05:32.202  4998  4998 E audit   : type=1327 msg=audit(1474470332.202:264): proctitle="com.test.thalitest"
09-21 17:05:32.202  4998  4998 E audit   : type=1320 msg=audit(1474470332.202:264): 
09-21 17:05:32.202  4998  4998 E audit   : type=1400 msg=audit(1474470332.202:265): avc:  denied  { ioctl } for  pid=9387 comm="Thread-156" path="socket:[37963]" dev="sockfs" ino=37963 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 17:05:32.202  4998  4998 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-21 17:05:32.202  4998  4998 E audit   : type=1300 msg=audit(1474470332.202:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=da3ba3c8 items=0 ppid=3174 pid=9387 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-156" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-21 17:05:32.202  4998  4998 E audit   : type=1327 msg=audit(1474470332.202:265): proctitle="com.test.thalitest"
09-21 17:05:32.202  4998  4998 E audit   : type=1320 msg=audit(1474470332.202:265): 
,09-21 17:05:32.212  9323  9387 W jxcore-log: Starting JXcore engine
,09-21 17:05:32.242  9323  9387 W jxcore-log: Platform android
09-21 17:05:32.242  9323  9387 W jxcore-log: 
09-21 17:05:32.242  9323  9387 W jxcore-log: Process ARCH arm
09-21 17:05:32.242  9323  9387 W jxcore-log: 
,09-21 17:05:32.262  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:32.312  9323  9387 I jxcore-log: JXcore Cordova bridge is ready!
09-21 17:05:32.312  9323  9387 I jxcore-log: 
09-21 17:05:32.312  9323  9387 W jxcore-log: JXcore engine is started
,09-21 17:05:32.322  9323  9386 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-21 17:05:32.322  9323  9323 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-21 17:05:32.442  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:32.622  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:32.802  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:32.982  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:33.062  3425  3901 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
09-21 17:05:33.172  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:33.352  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:33.522  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:33.532  3425  5959 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 17:05:33.712  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:33.892  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:34.072  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:34.252  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:34.422  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:34.602  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:34.782  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:34.962  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:35.142  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:35.322  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:35.502  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:35.682  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:35.862  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:36.042  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:36.222  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:36.402  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:36.582  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:36.612  3425  5959 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-21 17:05:36.762  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:36.942  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:37.122  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:37.182  3425  5959 D SSRM:n  : SIOP:: AP = 330, PST = 285 (W:6), CP = 243, LCD = 1
,09-21 17:05:37.302  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:37.482  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:37.662  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:37.842  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:38.022  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:38.202  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:38.372  9323  9387 I jxcore-log: 2016-09-21 15:05:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-21 17:05:38.372  9323  9387 I jxcore-log: 
,09-21 17:05:38.372  9323  9387 I jxcore-log: 2016-09-21 15:05:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-21 17:05:38.372  9323  9387 I jxcore-log: 
,09-21 17:05:38.382  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:38.382  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.392  9323  9387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:05:38.392  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:05:38.392  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:05:38.392  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:05:38.392  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:05:38.392  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:05:38.392  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:05:38.392  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 17:05:38.392  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.402  9323  9387 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 17:05:38.402  9323  9387 I jxcore-log: 2016-09-21 15:05:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-21 17:05:38.402  9323  9387 I jxcore-log: 
09-21 17:05:38.402  9323  9387 I jxcore-log: 2016-09-21 15:05:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-21 17:05:38.402  9323  9387 I jxcore-log: 
,09-21 17:05:38.552  9323  9387 I jxcore-log: Running unit tests
09-21 17:05:38.552  9323  9387 I jxcore-log: 
,09-21 17:05:38.552  9323  9387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 17:05:38.552  9323  9387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fc89ae added. We now have 2 listener(s)
09-21 17:05:38.562  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-21 17:05:38.562  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 17:05:38.562  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 17:05:38.562  9323  9387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 17:05:38.562  9323  9387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30dd34f added. We now have 2 listener(s)
09-21 17:05:38.562  9323  9387 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 17:05:38.562  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 17:05:38.562  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 17:05:38.562  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:38.572  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.572  9323  9387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:05:38.572  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:05:38.572  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:05:38.572  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:05:38.572  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:05:38.572  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:05:38.572  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:05:38.572  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 17:05:38.582  9323  9387 D BluetoothAdapter: STATE_ON
09-21 17:05:38.582  9323  9387 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 17:05:38.582  9323  9387 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 17:05:38.582  9323  9387 D executeNativeTests: Running unit tests
09-21 17:05:38.592  9323  9323 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 17:05:38.592  9323  9323 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:05:38.622  9323  9387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-21 17:05:38.622  9323  9387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cef455 added. We now have 3 listener(s)
09-21 17:05:38.622  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-21 17:05:38.622  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 17:05:38.622  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 17:05:38.622  9323  9387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-21 17:05:38.622  9323  9387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4e1e6a added. We now have 3 listener(s)
09-21 17:05:38.622  9323  9387 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 17:05:38.622  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 17:05:38.622  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 17:05:38.632  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.642  9323  9387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:05:38.642  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:05:38.642  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:05:38.642  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:05:38.642  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:05:38.642  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:05:38.642  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:05:38.642  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 17:05:38.642  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.642  9323  9387 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 17:05:38.642  9323  9387 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 17:05:38.652  9323  9387 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-21 17:05:38.652  9323  9387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 17:05:38.652  9323  9387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 17:05:38.652  9323  9387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-21 17:05:38.652  9323  9387 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-21 17:05:38.652  9323  9387 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-21 17:05:38.652  9323  9387 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-21 17:05:38.652  9323  9387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 17:05:38.652  9323  9387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 17:05:38.652  9323  9387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 17:05:38.652  9323  9387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-21 17:05:38.652  9323  9387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 17:05:38.652  9323  9387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-21 17:05:38.652  9323  9387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 17:05:38.652  9323  9387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:05:38.652  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 17:05:38.652  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 17:05:38.652  9323  9387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cef455 removed from the list
09-21 17:05:38.652  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:05:38.652  9323  9387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4e1e6a removed from the list
09-21 17:05:38.652  9323  9323 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 17:05:38.652  9323  9387 D io.jxcore.node.ConnectivityMonitor: stop
09-21 17:05:38.652  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:05:38.652  9323  9387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:05:38.652  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 17:05:38.652  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-21 17:05:38.652  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 17:05:38.652  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:05:38.652  9323  9387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4e1e6a not in the list
,09-21 17:05:38.652  9323  9387 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-21 17:05:38.652  9323  9387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 17:05:38.652  9323  9387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 17:05:38.652  9323  9387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 17:05:38.652  9323  9387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 17:05:38.652  9323  9387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:05:38.652  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 17:05:38.652  9323  9387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cef455 not in the list
09-21 17:05:38.652  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:05:38.652  9323  9387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4e1e6a not in the list
,09-21 17:05:38.662  9323  9323 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectivityMonitor: stop
,09-21 17:05:38.662  9323  9387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:05:38.662  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:05:38.662  9323  9387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:05:38.662  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 17:05:38.662  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-21 17:05:38.662  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 17:05:38.662  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:05:38.662  9323  9387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4e1e6a not in the list
,09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-21 17:05:38.662  9323  9387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 17:05:38.662  9323  9387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 17:05:38.662  9323  9387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 17:05:38.662  9323  9387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 17:05:38.662  9323  9387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:05:38.662  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:05:38.662  9323  9387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cef455 not in the list
,09-21 17:05:38.662  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:05:38.662  9323  9387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4e1e6a not in the list
09-21 17:05:38.662  9323  9387 D io.jxcore.node.ConnectivityMonitor: stop
09-21 17:05:38.662  9323  9387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:05:38.662  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:05:38.662  9323  9387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:05:38.662  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:05:38.672  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 17:05:38.672  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 17:05:38.672  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:05:38.672  9323  9387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4e1e6a not in the list
09-21 17:05:38.672  9323  9387 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-21 17:05:38.672  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 17:05:38.672  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.682  9323  9387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:05:38.682  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:05:38.682  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:05:38.682  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:05:38.682  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:05:38.682  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:05:38.682  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:05:38.682  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 17:05:38.682  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.682  9323  9387 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 17:05:38.682  9323  9387 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 17:05:38.682  9323  9387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 17:05:38.682  9323  9387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 17:05:38.682  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 17:05:38.682  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 17:05:38.682  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 17:05:38.692  9323  9323 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:05:38.692  9323  9387 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 17:05:38.692  9323  9387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-21 17:05:38.692  9323  9323 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:05:38.702  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.702  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.702  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.712  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 17:05:38.712  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.712  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.712  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-21 17:05:38.712  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-21 17:05:38.722  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.722  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.722  9323  9387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-21 17:05:38.722  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.722  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.732  9323  9387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-21 17:05:38.732  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 17:05:38.732  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-21 17:05:38.732  9323  9387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 17:05:38.732  9323  9387 D BluetoothLeScanner: Start Scan
,09-21 17:05:38.732  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.742  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.742  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.742  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.742  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:38.752  4992  5396 D BtGatt.GattService: registerClient() - UUID=3f85fbfd-db7d-4fbb-95f5-7686fbabecf1
,09-21 17:05:38.802  4992  5112 D BtGatt.GattService: onClientRegistered() - UUID=3f85fbfd-db7d-4fbb-95f5-7686fbabecf1, clientIf=7
,09-21 17:05:38.802  9323  9335 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-21 17:05:38.802  4992  5004 D BtGatt.GattService: start scan with filters
,09-21 17:05:38.812  4992  5004 D BtGatt.GattService: getScanSettings
,09-21 17:05:38.822  4992  5004 D BtGatt.GattService: Is it foreground application = true
,09-21 17:05:38.822  4992  5004 D BtGatt.GattService: not a background application
,09-21 17:05:38.832  4992  5004 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-21 17:05:38.832  4992  5004 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-21 17:05:38.832  4992  5004 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-21 17:05:38.832  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-21 17:05:38.832  4992  5214 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
,09-21 17:05:38.832  4992  5214 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 21, currDate: 21
09-21 17:05:38.832  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 17:05:38.842  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 17:05:38.842  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-21 17:05:38.842  4992  5206 D BtGatt.ScanManager: handling starting scan
,09-21 17:05:38.842  4992  5206 D BtGatt.ScanManager: isFilteringSupported
,09-21 17:05:38.842  4992  5206 D BluetoothAdapter: enableStandAloneBleMode=
09-21 17:05:38.842  4992  5206 D BluetoothAdapter: STATE_ON
,09-21 17:05:38.842  4992  5206 D BluetoothAdapter: STATE_ON
09-21 17:05:38.842  4992  5206 D BluetoothAdapter: STATE_ON
09-21 17:05:38.842  9323  9387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 17:05:38.842  4992  5206 D BluetoothAdapter: STATE_ON
09-21 17:05:38.842  9323  9387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 17:05:38.842  9323  9323 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 17:05:38.842  4992  5206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e22790c
09-21 17:05:38.852  4992  5214 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 63
09-21 17:05:38.852  4992  5214 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-21 17:05:38.852  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 17:05:38.852  3425  4594 V AlarmManager:  remove PendingIntent] PendingIntent{e8f0928: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:38.862  4992  5112 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-21 17:05:38.862  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:05:38.862  4992  5206 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 19
09-21 17:05:38.862  4992  5206 D BtGatt.ScanManager: High Rssi Filter value is = -128
,09-21 17:05:38.862  4992  5206 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-21 17:05:38.862  4992  5206 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574505
09-21 17:05:38.862  3425  4048 V AlarmManager:  remove PendingIntent] PendingIntent{4a14641: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:05:38.862  9323  9387 I io.jxcore.node.ConnectionHelper: start: OK
,09-21 17:05:38.862  4992  5112 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-21 17:05:38.862  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
,09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:05:38.862  4992  5206 D BtGatt.ScanManager: Starting BLE batch scan
09-21 17:05:38.862  4992  5214 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574505
,09-21 17:05:38.862  4992  5206 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,09-21 17:05:38.872  4992  5112 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,09-21 17:05:38.872  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:05:38.872  3425  4409 V AlarmManager:  remove PendingIntent] PendingIntent{358e7e6: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:38.872  4992  5112 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-21 17:05:38.872  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:38.872  3425  4365 V AlarmManager:  remove PendingIntent] PendingIntent{5670127: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
09-21 17:05:38.872  3425  4971 V AlarmManager:  remove PendingIntent] PendingIntent{a7b057d: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
09-21 17:05:38.882  3425  3977 V AlarmManager:  remove PendingIntent] PendingIntent{dbb9c72: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:38.882  3425  3971 V AlarmManager:  remove PendingIntent] PendingIntent{4b888c3: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:38.892  3425  3447 V AlarmManager:  remove PendingIntent] PendingIntent{60fd540: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:38.892  3425  3446 V AlarmManager:  remove PendingIntent] PendingIntent{7377c79: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:38.902  3425  4971 V AlarmManager:  remove PendingIntent] PendingIntent{9230dbe: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:38.902  3425  4237 V AlarmManager:  remove PendingIntent] PendingIntent{110ee1f: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:38.912  3425  4594 V AlarmManager:  remove PendingIntent] PendingIntent{7bd056c: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:38.912  3425  4591 V AlarmManager:  remove PendingIntent] PendingIntent{aa6735: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:38.922  3425  4409 V AlarmManager:  remove PendingIntent] PendingIntent{bfe47ca: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:38.922  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:39.102  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:39.292  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:39.352  9323  9323 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-21 17:05:39.352  9323  9323 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 17:05:39.352  9323  9323 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-21 17:05:39.462  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:39.642  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:39.822  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:39.872  3425  3813 V AlarmManager: Expired Alarm result :4
,09-21 17:05:39.882  4992  4992 D BtGatt.ScanManager: awakened up at time 264414
,09-21 17:05:39.882  4992  5206 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:05:39.892  3425  3977 V AlarmManager:  remove PendingIntent] PendingIntent{82b0c58: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:39.892  4992  5112 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=5
,09-21 17:05:39.892  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:39.892  4992  5112 D BtGatt.GattService: current time is 264428074348
09-21 17:05:39.892  4992  5112 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -52, 11, 57, -70, 107, -17, 1, 0, -103, 19, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 37, -47, 14, -113, 116, -46, 1, -128, -91, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-21 17:05:39.902  4992  5112 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-21 17:05:39.902  3425  4594 V AlarmManager:  remove PendingIntent] PendingIntent{c2741b1: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
,09-21 17:05:39.902  4992  5112 D ScanRecord: parseFromBytes
09-21 17:05:39.902  4992  5112 D ScanRecord: first manudata for manu ID
,09-21 17:05:39.912  4992  5112 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
,09-21 17:05:39.912  4992  5112 D ScanRecord: parseFromBytes
09-21 17:05:39.912  4992  5112 D ScanRecord: first manudata for manu ID
09-21 17:05:39.912  4992  5112 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-21 17:05:39.912  4992  5112 D ScanRecord: parseFromBytes
,09-21 17:05:39.912  4992  5112 D ScanRecord: first manudata for manu ID
09-21 17:05:39.912  4992  5112 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-21 17:05:39.912  3425  4591 V AlarmManager:  remove PendingIntent] PendingIntent{2a11696: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
09-21 17:05:39.912  4992  5112 D ScanRecord: parseFromBytes
,09-21 17:05:39.912  4992  5112 D ScanRecord: first manudata for manu ID
09-21 17:05:39.912  4992  5112 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-21 17:05:39.912  4992  5112 D ScanRecord: parseFromBytes
09-21 17:05:39.912  4992  5112 D ScanRecord: first manudata for manu ID
,09-21 17:05:39.922  9323  9333 D ScanRecord: parseFromBytes
,09-21 17:05:39.922  9323  9333 D ScanRecord: first manudata for manu ID
,09-21 17:05:39.922  3425  4409 V AlarmManager:  remove PendingIntent] PendingIntent{17c8217: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:39.922  9323  9333 D ScanRecord: parseFromBytes
09-21 17:05:39.922  9323  9333 D ScanRecord: first manudata for manu ID
09-21 17:05:39.922  9323  9333 D ScanRecord: parseFromBytes
09-21 17:05:39.922  9323  9333 D ScanRecord: first manudata for manu ID
09-21 17:05:39.922  9323  9333 D ScanRecord: parseFromBytes
09-21 17:05:39.922  9323  9333 D ScanRecord: first manudata for manu ID
09-21 17:05:39.922  9323  9333 D ScanRecord: parseFromBytes
,09-21 17:05:39.922  9323  9333 D ScanRecord: first manudata for manu ID
,09-21 17:05:39.932  3425  4365 V AlarmManager:  remove PendingIntent] PendingIntent{6709604: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:39.932  3425  4521 V AlarmManager:  remove PendingIntent] PendingIntent{6bd47ed: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:39.942  3425  4289 V AlarmManager:  remove PendingIntent] PendingIntent{8d00622: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:39.942  3425  4048 V AlarmManager:  remove PendingIntent] PendingIntent{2bd28b3: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:39.952  3425  4593 V AlarmManager:  remove PendingIntent] PendingIntent{a630e70: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:39.962  3425  4046 V AlarmManager:  remove PendingIntent] PendingIntent{53375e9: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:40.002  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:40.102  3425  3560 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-21 17:05:40.132  3425  3560 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-21 17:05:40.182  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:40.362  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:40.542  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:40.722  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:40.902  3425  3813 V AlarmManager: Expired Alarm result :4
,09-21 17:05:40.902  4992  4992 D BtGatt.ScanManager: awakened up at time 265437
,09-21 17:05:40.912  4992  5206 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:05:40.912  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:40.912  3425  3977 V AlarmManager:  remove PendingIntent] PendingIntent{a579d0f: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:40.922  4992  5112 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
,09-21 17:05:40.922  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:40.922  4992  5112 D BtGatt.GattService: current time is 265452657078
09-21 17:05:40.922  3425  4289 V AlarmManager:  remove PendingIntent] PendingIntent{1c2a19c: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
,09-21 17:05:40.922  4992  5112 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-21 17:05:40.922  4992  5112 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-21 17:05:40.922  4992  5112 D ScanRecord: parseFromBytes
,09-21 17:05:40.922  4992  5112 D ScanRecord: first manudata for manu ID
09-21 17:05:40.922  9323  9335 D ScanRecord: parseFromBytes
09-21 17:05:40.922  9323  9335 D ScanRecord: first manudata for manu ID
,09-21 17:05:40.932  3425  4048 V AlarmManager:  remove PendingIntent] PendingIntent{7c487a5: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:40.942  3425  4593 V AlarmManager:  remove PendingIntent] PendingIntent{ea0377a: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:40.942  3425  4046 V AlarmManager:  remove PendingIntent] PendingIntent{d7afb2b: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:40.952  3425  4521 V AlarmManager:  remove PendingIntent] PendingIntent{4263b88: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:40.952  3425  4237 V AlarmManager:  remove PendingIntent] PendingIntent{d9af921: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:41.082  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:41.262  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:41.442  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:41.622  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:41.802  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:41.932  3425  3813 V AlarmManager: Expired Alarm result :4
,09-21 17:05:41.932  4992  4992 D BtGatt.ScanManager: awakened up at time 266462
,09-21 17:05:41.932  4992  5206 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:05:41.932  3425  3447 V AlarmManager:  remove PendingIntent] PendingIntent{b2c1f07: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:41.942  4992  5112 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-21 17:05:41.942  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:05:41.942  3425  4409 V AlarmManager:  remove PendingIntent] PendingIntent{9a78834: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
,09-21 17:05:41.952  3425  4365 V AlarmManager:  remove PendingIntent] PendingIntent{40d065d: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:41.962  3425  3977 V AlarmManager:  remove PendingIntent] PendingIntent{a6a3bd2: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:41.982  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:42.162  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:42.342  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:42.522  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:42.702  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:42.882  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:42.952  3425  3813 V AlarmManager: Expired Alarm result :4
,09-21 17:05:42.952  4992  4992 D BtGatt.ScanManager: awakened up at time 267484
,09-21 17:05:42.952  4992  5206 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:05:42.952  3425  4048 V AlarmManager:  remove PendingIntent] PendingIntent{4ef3a0: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:42.962  4992  5112 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-21 17:05:42.962  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:05:42.962  3425  4409 V AlarmManager:  remove PendingIntent] PendingIntent{d98ab59: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
,09-21 17:05:42.982  3425  3446 V AlarmManager:  remove PendingIntent] PendingIntent{e0c431e: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:42.992  3425  4971 V AlarmManager:  remove PendingIntent] PendingIntent{edfe7ff: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:43.062  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:43.242  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:43.422  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:43.602  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:43.782  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:43.872  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:43.882  9323  9387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-21 17:05:43.882  9323  9387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 17:05:43.882  9323  9387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 17:05:43.882  9323  9387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:05:43.882  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-21 17:05:43.882  9323  9387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 17:05:43.882  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 17:05:43.882  9323  9387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-21 17:05:43.882  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 17:05:43.882  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 17:05:43.882  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-21 17:05:43.892  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:43.892  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:43.892  9323  9387 D BluetoothLeScanner: Stop Scan
,09-21 17:05:43.902  4992  5003 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-21 17:05:43.902  4992  5003 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-21 17:05:43.902  4992  5003 D BtGatt.GattService: stopScan() - queue size =1
09-21 17:05:43.902  4992  5214 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-21 17:05:43.902  4992  5214 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 21, currDate: 21
09-21 17:05:43.902  4992  5214 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:05:43.902  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-21 17:05:43.902  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:05:43.902  4992  5214 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-21 17:05:43.902  4992  5397 D BtGatt.GattService: unregisterClient() - clientIf=7
,09-21 17:05:43.902  4992  5206 D BtGatt.ScanManager: filter size is 1
09-21 17:05:43.902  4992  5214 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-21 17:05:43.902  4992  5206 D BtGatt.ScanManager: delete FilterIndex - 3
09-21 17:05:43.912  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-21 17:05:43.912  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 17:05:43.912  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 17:05:43.912  4992  5112 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-21 17:05:43.912  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 17:05:43.912  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:43.912  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 17:05:43.912  3425  4046 V AlarmManager:  remove PendingIntent] PendingIntent{c3fa9cc: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:43.912  4992  5206 D BtGatt.ScanManager: stopping BLe Batch
09-21 17:05:43.912  4992  5112 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
,09-21 17:05:43.912  9323  9387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 17:05:43.912  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:43.912  4992  5206 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:05:43.922  9323  9387 D BluetoothAdapter: STATE_ON
09-21 17:05:43.922  4992  5112 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-21 17:05:43.922  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:05:43.922  3425  4048 V AlarmManager:  remove PendingIntent] PendingIntent{c9fa415: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
09-21 17:05:43.922  9323  9387 D BluetoothAdapter: STATE_ON
09-21 17:05:43.922  9323  9387 D BluetoothLeAdvertiser: stop advertising
09-21 17:05:43.922  9323  9387 D BluetoothLeAdvertiser: wrapper is null
09-21 17:05:43.922  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-21 17:05:43.922  9323  9387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-21 17:05:43.922  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 17:05:43.932  3425  4409 V AlarmManager:  remove PendingIntent] PendingIntent{135732a: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
09-21 17:05:43.932  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 17:05:43.932  3425  4289 V AlarmManager:  remove PendingIntent] PendingIntent{955051b: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
,09-21 17:05:43.932  9323  9323 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-21 17:05:43.932  9323  9387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 17:05:43.932  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:05:43.932  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 17:05:43.932  9323  9387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:05:43.932  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-21 17:05:43.932  9323  9387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cef455 not in the list
,09-21 17:05:43.932  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:05:43.932  9323  9387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4e1e6a not in the list
09-21 17:05:43.932  9323  9387 D io.jxcore.node.ConnectivityMonitor: stop
09-21 17:05:43.932  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-21 17:05:43.942  3425  3971 V AlarmManager:  remove PendingIntent] PendingIntent{b34d7f7: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:43.942  9323  9323 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 17:05:43.942  9323  9323 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-21 17:05:43.942  9323  9323 D BluetoothAdapter: STATE_ON
,09-21 17:05:43.952  3425  4289 V AlarmManager:  remove PendingIntent] PendingIntent{f576664: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
09-21 17:05:43.952  9323  9323 D BluetoothAdapter: STATE_ON
,09-21 17:05:43.952  9323  9323 D BluetoothAdapter: STATE_ON
,09-21 17:05:43.952  3425  4316 V AlarmManager:  remove PendingIntent] PendingIntent{ec140cd: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:43.952  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 17:05:43.952  9323  9323 D BluetoothAdapter: STATE_ON
,09-21 17:05:43.962  3425  3447 V AlarmManager:  remove PendingIntent] PendingIntent{5953d82: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:43.962  9323  9323 D BluetoothAdapter: STATE_ON
09-21 17:05:43.962  9323  9323 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 17:05:43.962  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 17:05:43.962  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-21 17:05:43.962  9323  9323 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 17:05:43.962  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:43.962  3425  4594 V AlarmManager:  remove PendingIntent] PendingIntent{dd4fc93: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
09-21 17:05:43.962  9323  9323 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 17:05:43.962  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:05:43.962  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 17:05:43.972  9323  9323 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 17:05:43.972  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 17:05:43.972  9323  9323 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 17:05:43.972  3425  4591 V AlarmManager:  remove PendingIntent] PendingIntent{48ceef: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:43.972  9323  9323 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-21 17:05:43.972  3425  4594 V AlarmManager:  remove PendingIntent] PendingIntent{9e71dfc: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:44.142  3425  6007 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-21 17:05:44.142  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:44.322  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:44.472  9323  9323 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 17:05:44.502  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:44.682  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:44.862  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:45.042  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:45.222  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:45.402  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:45.582  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:45.762  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:45.942  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:46.122  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:46.302  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:46.482  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:46.662  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:46.842  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:47.022  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:47.202  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:47.202  3425  5959 D SSRM:n  : SIOP:: AP = 300, PST = 286 (W:14), CP = 250, LCD = 1
,09-21 17:05:47.382  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:47.562  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:47.742  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:47.922  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:48.102  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:48.282  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:48.462  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:48.642  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:48.822  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:48.942  9323  9387 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-21 17:05:48.942  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 17:05:48.962  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:48.972  9323  9387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:05:48.972  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:05:48.972  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:05:48.972  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:05:48.972  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:05:48.972  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:05:48.972  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:05:48.972  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 17:05:48.972  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:48.982  9323  9387 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 17:05:48.982  9323  9387 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 17:05:48.982  9323  9387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 17:05:48.982  9323  9387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 17:05:48.982  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-21 17:05:48.982  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:05:48.982  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 17:05:49.002  9323  9323 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:05:49.002  9323  9387 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 17:05:49.002  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:49.012  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.012  9323  9323 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 17:05:49.012  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.022  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.022  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.022  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-21 17:05:49.022  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 17:05:49.022  9323  9387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 17:05:49.022  9323  9387 D BluetoothLeScanner: Start Scan
,09-21 17:05:49.022  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.032  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.032  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.032  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.032  4992  5397 D BtGatt.GattService: registerClient() - UUID=927b511b-8e53-4b0e-a9ce-c3fdcad73d06
,09-21 17:05:49.052  3425  4594 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-21 17:05:49.052  3425  4594 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-21 17:05:49.052  3425  4594 D BatteryService: online:4, current avg:-42, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
09-21 17:05:49.052  3425  4594 D BatteryService: stay LED for fully charged
09-21 17:05:49.052  3425  3425 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-21 17:05:49.062  3425  3425 I MotionRecognitionService: Plugged
09-21 17:05:49.062  3425  3425 D MotionRecognitionService:   cableConnection= 1
09-21 17:05:49.062  3425  3425 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-21 17:05:49.062  3425  3425 D MotionRecognitionService: skip setTransmitPower. 
,09-21 17:05:49.062  3425  3858 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-21 17:05:49.062  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-21 17:05:49.062  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-21 17:05:49.062  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-21 17:05:49.072  5031  5031 D CommonServiceConfiguration: getStringValueSetting
09-21 17:05:49.082  4992  5112 D BtGatt.GattService: onClientRegistered() - UUID=927b511b-8e53-4b0e-a9ce-c3fdcad73d06, clientIf=7
09-21 17:05:49.082  9323  9333 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-21 17:05:49.082  4992  5003 D BtGatt.GattService: start scan with filters
09-21 17:05:49.082  4992  4992 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-21 17:05:49.082  4992  5395 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-21 17:05:49.082  4992  5003 D BtGatt.GattService: getScanSettings
09-21 17:05:49.082  5031  5031 D BatteryMonitor: new battery level: 100
,09-21 17:05:49.092  4697  4697 D BatteryController: saveBatteryData : level[100], status[5]
,09-21 17:05:49.092  4992  5003 D BtGatt.GattService: Is it foreground application = true
09-21 17:05:49.092  4992  5003 D BtGatt.GattService: not a background application
,09-21 17:05:49.092  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-21 17:05:49.092  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-21 17:05:49.102  4992  5003 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-21 17:05:49.102  4992  5003 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-21 17:05:49.102  4992  5003 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-21 17:05:49.102  4992  5214 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-21 17:05:49.102  4992  5214 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 21, currDate: 21
09-21 17:05:49.102  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 17:05:49.102  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-21 17:05:49.102  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 17:05:49.102  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-21 17:05:49.102  4992  5206 D BtGatt.ScanManager: handling starting scan
,09-21 17:05:49.112  4992  5206 D BluetoothAdapter: STATE_ON
09-21 17:05:49.112  3425  4316 V AlarmManager:  remove PendingIntent] PendingIntent{815ace7: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
09-21 17:05:49.112  4992  5206 D BluetoothAdapter: STATE_ON
09-21 17:05:49.112  9323  9387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 17:05:49.112  9323  9387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 17:05:49.112  9323  9323 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 17:05:49.112  4992  5214 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 64
09-21 17:05:49.112  4992  5214 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-21 17:05:49.112  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 17:05:49.122  3425  4594 V AlarmManager:  remove PendingIntent] PendingIntent{d933094: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.122  4992  5112 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-21 17:05:49.122  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:05:49.122  4992  5206 D BtGatt.ScanManager: set filter index= 4 for clientIf= 7
09-21 17:05:49.122  4992  5206 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-21 17:05:49.122  4992  5206 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-21 17:05:49.122  4992  5206 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-21 17:05:49.122  9323  9387 I io.jxcore.node.ConnectionHelper: start: OK
09-21 17:05:49.122  4992  5112 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-21 17:05:49.122  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:05:49.122  4992  5206 D BtGatt.ScanManager: Starting BLE batch scan
09-21 17:05:49.122  4992  5206 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,09-21 17:05:49.122  9323  9387 D BluetoothAdapter: STATE_ON
09-21 17:05:49.122  3425  4237 V AlarmManager:  remove PendingIntent] PendingIntent{6f0f73d: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.122  4992  5214 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 20
09-21 17:05:49.122  4992  5214 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574505
09-21 17:05:49.122  4992  5214 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-21 17:05:49.122  4992  5214 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 17:05:49.122  4992  5214 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-21 17:05:49.122  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:05:49.122  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:05:49.122  4992  5214 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:05:49.132  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:05:49.132  4992  5112 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,09-21 17:05:49.132  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:49.132  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:05:49.132  4992  5214 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 17:05:49.132  4992  5214 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:05:49.132  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-21 17:05:49.132  9323  9387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 17:05:49.132  9323  9387 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 17:05:49.132  9323  9387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 17:05:49.132  9323  9387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 17:05:49.132  3425  3977 V AlarmManager:  remove PendingIntent] PendingIntent{61c0b32: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
09-21 17:05:49.132  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:05:49.132  9323  9387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:05:49.132  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-21 17:05:49.132  9323  9387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 17:05:49.132  4992  5214 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574505
09-21 17:05:49.132  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 17:05:49.132  9323  9387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 17:05:49.132  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 17:05:49.132  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 17:05:49.132  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 17:05:49.132  4992  5112 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-21 17:05:49.132  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:49.132  9323  9387 D BluetoothAdapter: STATE_ON
09-21 17:05:49.132  9323  9387 D BluetoothAdapter: STATE_ON
09-21 17:05:49.132  9323  9387 D BluetoothLeScanner: Stop Scan
,09-21 17:05:49.132  3425  4289 V AlarmManager:  remove PendingIntent] PendingIntent{63083: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.142  4992  5004 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-21 17:05:49.142  4992  5004 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-21 17:05:49.142  4992  5004 D BtGatt.GattService: stopScan() - queue size =1
09-21 17:05:49.142  4992  5214 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-21 17:05:49.142  4992  5214 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 21, currDate: 21
,09-21 17:05:49.142  4992  5214 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:05:49.142  4992  5397 D BtGatt.GattService: unregisterClient() - clientIf=7
09-21 17:05:49.142  4992  5206 D BtGatt.ScanManager: filter size is 1
09-21 17:05:49.142  4992  5206 D BtGatt.ScanManager: delete FilterIndex - 4
09-21 17:05:49.142  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-21 17:05:49.142  4992  5112 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-21 17:05:49.142  3425  3977 V AlarmManager:  remove PendingIntent] PendingIntent{dbcc200: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
09-21 17:05:49.142  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:49.142  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 17:05:49.142  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 17:05:49.142  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-21 17:05:49.142  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 17:05:49.142  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 17:05:49.142  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:05:49.142  4992  5214 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-21 17:05:49.142  4992  5206 D BtGatt.ScanManager: stopping BLe Batch
09-21 17:05:49.142  4992  5214 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-21 17:05:49.142  9323  9387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-21 17:05:49.142  4992  5112 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-21 17:05:49.142  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:49.152  3425  4048 V AlarmManager:  remove PendingIntent] PendingIntent{87aca39: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
09-21 17:05:49.142  9323  9387 D BluetoothAdapter: STATE_ON
09-21 17:05:49.142  4992  5206 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:05:49.152  4992  5112 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-21 17:05:49.152  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:05:49.152  9323  9387 D BluetoothAdapter: STATE_ON
09-21 17:05:49.152  9323  9387 D BluetoothLeAdvertiser: stop advertising
09-21 17:05:49.152  9323  9387 D BluetoothLeAdvertiser: wrapper is null
09-21 17:05:49.152  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-21 17:05:49.152  3425  3971 V AlarmManager:  remove PendingIntent] PendingIntent{6fba87e: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
09-21 17:05:49.152  9323  9387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 17:05:49.152  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 17:05:49.152  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-21 17:05:49.152  3425  3446 V AlarmManager:  remove PendingIntent] PendingIntent{5f151df: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
09-21 17:05:49.152  9323  9323 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-21 17:05:49.152  9323  9387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 17:05:49.152  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:05:49.152  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 17:05:49.152  9323  9387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 17:05:49.152  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-21 17:05:49.152  9323  9387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cef455 not in the list
09-21 17:05:49.152  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:05:49.152  9323  9387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4e1e6a not in the list
09-21 17:05:49.152  9323  9387 D io.jxcore.node.ConnectivityMonitor: stop
09-21 17:05:49.152  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-21 17:05:49.162  9323  9323 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 17:05:49.162  9323  9323 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 17:05:49.162  3425  4971 V AlarmManager:  remove PendingIntent] PendingIntent{432cfb: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.162  9323  9323 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.162  3425  4046 V AlarmManager:  remove PendingIntent] PendingIntent{970d118: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.162  9323  9323 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.162  9323  9323 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.162  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 17:05:49.162  3425  4289 V AlarmManager:  remove PendingIntent] PendingIntent{54e8771: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.172  9323  9323 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.172  9323  9323 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.172  9323  9323 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 17:05:49.172  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 17:05:49.172  3425  3446 V AlarmManager:  remove PendingIntent] PendingIntent{21a4956: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
09-21 17:05:49.172  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 17:05:49.172  9323  9323 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 17:05:49.172  9323  9387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 17:05:49.172  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 17:05:49.172  3425  4289 V AlarmManager:  remove PendingIntent] PendingIntent{60d9dd7: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
09-21 17:05:49.172  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-21 17:05:49.172  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.182  9323  9387 D BluetoothAdapter: STATE_ON
09-21 17:05:49.182  9323  9387 D BluetoothLeAdvertiser: stop advertising
09-21 17:05:49.182  9323  9387 D BluetoothLeAdvertiser: wrapper is null
,09-21 17:05:49.182  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 17:05:49.182  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-21 17:05:49.182  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.182  3425  3446 V AlarmManager:  remove PendingIntent] PendingIntent{52de6c4: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
09-21 17:05:49.182  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.182  9323  9387 D BluetoothLeScanner: could not find callback wrapper
,09-21 17:05:49.182  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-21 17:05:49.182  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 17:05:49.182  9323  9387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4e1e6a not in the list
09-21 17:05:49.182  9323  9387 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 17:05:49.182  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 17:05:49.182  9323  9323 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 17:05:49.182  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:05:49.182  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 17:05:49.182  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 17:05:49.192  3425  4048 V AlarmManager:  remove PendingIntent] PendingIntent{484ab30: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.192  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.192  9323  9323 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 17:05:49.192  9323  9323 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 17:05:49.192  3425  3446 V AlarmManager:  remove PendingIntent] PendingIntent{7414a5c: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
09-21 17:05:49.192  9323  9323 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-21 17:05:49.202  9323  9387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 17:05:49.202  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 17:05:49.202  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 17:05:49.202  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 17:05:49.202  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 17:05:49.202  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 17:05:49.202  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 17:05:49.202  9323  9387 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 17:05:49.202  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.202  9323  9323 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-21 17:05:49.202  3425  3447 V AlarmManager:  remove PendingIntent] PendingIntent{a9ce165: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.202  9323  9387 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 17:05:49.202  9323  9387 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 17:05:49.202  9323  9387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 17:05:49.202  9323  9387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 17:05:49.202  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 17:05:49.202  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 17:05:49.202  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 17:05:49.202  3425  3977 V AlarmManager:  remove PendingIntent] PendingIntent{a96ee3a: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.212  9323  9387 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 17:05:49.212  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.212  9323  9323 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 17:05:49.212  3425  4289 V AlarmManager:  remove PendingIntent] PendingIntent{bf5b406: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.212  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.222  9323  9387 D BluetoothAdapter: STATE_ON
09-21 17:05:49.222  3425  4237 V AlarmManager:  remove PendingIntent] PendingIntent{71baac7: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.222  9323  9323 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 17:05:49.222  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.222  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 17:05:49.222  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 17:05:49.222  9323  9387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 17:05:49.222  9323  9387 D BluetoothLeScanner: Start Scan
,09-21 17:05:49.222  3425  4521 V AlarmManager:  remove PendingIntent] PendingIntent{1ba88f4: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.222  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.222  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.222  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.232  9323  9387 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.232  3425  3446 V AlarmManager:  remove PendingIntent] PendingIntent{2ded81d: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.232  4992  5397 D BtGatt.GattService: registerClient() - UUID=15d8f442-f843-4493-9f24-b2ad3aba79e9
,09-21 17:05:49.232  3425  4046 V AlarmManager:  remove PendingIntent] PendingIntent{2290a92: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.242  3425  4521 V AlarmManager:  remove PendingIntent] PendingIntent{b9e2c63: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.272  4992  5112 D BtGatt.GattService: onClientRegistered() - UUID=15d8f442-f843-4493-9f24-b2ad3aba79e9, clientIf=7
,09-21 17:05:49.272  9323  9335 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
09-21 17:05:49.272  4992  5003 D BtGatt.GattService: start scan with filters
,09-21 17:05:49.272  4992  5003 D BtGatt.GattService: getScanSettings
,09-21 17:05:49.272  4992  5003 D BtGatt.GattService: Is it foreground application = true
,09-21 17:05:49.272  4992  5003 D BtGatt.GattService: not a background application
,09-21 17:05:49.272  4992  5003 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-21 17:05:49.282  4992  5003 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-21 17:05:49.282  4992  5003 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-21 17:05:49.282  4992  5214 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
,09-21 17:05:49.282  4992  5214 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 21, currDate: 21
09-21 17:05:49.282  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 17:05:49.282  9323  9387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 17:05:49.282  9323  9387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 17:05:49.282  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 17:05:49.282  4992  5206 D BtGatt.ScanManager: handling starting scan
,09-21 17:05:49.282  4992  5206 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.282  4992  5206 D BluetoothAdapter: STATE_ON
,09-21 17:05:49.282  9323  9387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 17:05:49.282  9323  9387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 17:05:49.282  3425  4409 V AlarmManager:  remove PendingIntent] PendingIntent{b714060: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.292  4992  5214 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 65
09-21 17:05:49.292  4992  5214 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-21 17:05:49.292  4992  5112 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-21 17:05:49.292  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:05:49.292  4992  5206 D BtGatt.ScanManager: set filter index= 5 for clientIf= 7
09-21 17:05:49.292  4992  5206 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-21 17:05:49.292  4992  5206 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-21 17:05:49.292  4992  5206 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-21 17:05:49.292  3425  4593 V AlarmManager:  remove PendingIntent] PendingIntent{b15d919: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
09-21 17:05:49.292  4992  5112 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
09-21 17:05:49.292  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:05:49.292  4992  5206 D BtGatt.ScanManager: Starting BLE batch scan
09-21 17:05:49.292  4992  5206 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-21 17:05:49.292  9323  9387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 17:05:49.302  3425  4046 V AlarmManager:  remove PendingIntent] PendingIntent{2c93dde: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
09-21 17:05:49.292  9323  9323 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 17:05:49.292  4992  5112 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,09-21 17:05:49.292  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:49.292  4992  5214 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 21
09-21 17:05:49.292  4992  5214 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574505
09-21 17:05:49.292  4992  5214 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-21 17:05:49.292  4992  5214 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 17:05:49.292  4992  5214 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:05:49.302  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-21 17:05:49.302  9323  9387 I io.jxcore.node.ConnectionHelper: start: OK
09-21 17:05:49.302  4992  5112 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-21 17:05:49.302  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:49.302  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:05:49.302  4992  5214 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:05:49.302  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:05:49.302  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:05:49.302  4992  5214 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-21 17:05:49.302  3425  3971 V AlarmManager:  remove PendingIntent] PendingIntent{83d2bbf: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.302  4992  5214 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-21 17:05:49.302  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-21 17:05:49.302  4992  5214 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-21 17:05:49.302  4992  5214 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24574505
,09-21 17:05:49.312  3425  4594 V AlarmManager:  remove PendingIntent] PendingIntent{a1a028c: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.312  3425  3446 V AlarmManager:  remove PendingIntent] PendingIntent{e21edd5: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.312  3425  4237 V AlarmManager:  remove PendingIntent] PendingIntent{2a759ea: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.322  3425  4316 V AlarmManager:  remove PendingIntent] PendingIntent{3a2c4db: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.322  3425  4521 V AlarmManager:  remove PendingIntent] PendingIntent{aabb78: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.332  3425  4971 V AlarmManager:  remove PendingIntent] PendingIntent{4a09251: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.332  3425  4409 V AlarmManager:  remove PendingIntent] PendingIntent{992ab6: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.342  3425  4048 V AlarmManager:  remove PendingIntent] PendingIntent{afed3b7: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.342  3425  4046 V AlarmManager:  remove PendingIntent] PendingIntent{98c1724: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.352  3425  3977 V AlarmManager:  remove PendingIntent] PendingIntent{98b028d: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.352  3425  4591 V AlarmManager:  remove PendingIntent] PendingIntent{1053c42: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:49.362  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:49.542  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:49.722  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:49.792  9323  9323 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-21 17:05:49.792  9323  9323 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 17:05:49.792  9323  9323 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-21 17:05:49.902  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:50.082  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:50.262  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:50.302  3425  3813 V AlarmManager: Expired Alarm result :4
,09-21 17:05:50.302  4992  4992 D BtGatt.ScanManager: awakened up at time 274837
,09-21 17:05:50.302  4992  5206 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:05:50.312  3425  4048 V AlarmManager:  remove PendingIntent] PendingIntent{b058190: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:50.312  4992  5112 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
09-21 17:05:50.312  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-21 17:05:50.312  4992  5112 D BtGatt.GattService: current time is 274845523379
09-21 17:05:50.312  4992  5112 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -87, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -79, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
09-21 17:05:50.312  3425  4593 V AlarmManager:  remove PendingIntent] PendingIntent{4323a89: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
09-21 17:05:50.312  4992  5112 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-21 17:05:50.312  4992  5112 D ScanRecord: parseFromBytes
09-21 17:05:50.312  4992  5112 D ScanRecord: first manudata for manu ID
09-21 17:05:50.312  4992  5112 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-21 17:05:50.312  4992  5112 D ScanRecord: parseFromBytes
,09-21 17:05:50.312  4992  5112 D ScanRecord: first manudata for manu ID
09-21 17:05:50.312  4992  5112 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-21 17:05:50.312  4992  5112 D ScanRecord: parseFromBytes
09-21 17:05:50.312  4992  5112 D ScanRecord: first manudata for manu ID
09-21 17:05:50.322  9323  9333 D ScanRecord: parseFromBytes
09-21 17:05:50.322  9323  9333 D ScanRecord: first manudata for manu ID
,09-21 17:05:50.322  9323  9333 D ScanRecord: parseFromBytes
09-21 17:05:50.322  9323  9333 D ScanRecord: first manudata for manu ID
09-21 17:05:50.322  9323  9333 D ScanRecord: parseFromBytes
09-21 17:05:50.322  9323  9333 D ScanRecord: first manudata for manu ID
,09-21 17:05:50.342  3425  3447 V AlarmManager:  remove PendingIntent] PendingIntent{62eda8e: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:50.342  3425  3971 V AlarmManager:  remove PendingIntent] PendingIntent{5e82af: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:50.352  3425  4594 V AlarmManager:  remove PendingIntent] PendingIntent{66926bc: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:50.362  3425  4289 V AlarmManager:  remove PendingIntent] PendingIntent{5faf645: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:50.372  3425  3446 V AlarmManager:  remove PendingIntent] PendingIntent{142119a: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:50.442  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:50.622  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:50.802  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:50.982  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:51.162  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:51.312  3425  3813 V AlarmManager: Expired Alarm result :4
,09-21 17:05:51.322  4992  4992 D BtGatt.ScanManager: awakened up at time 275853
,09-21 17:05:51.322  4992  5206 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:05:51.322  3425  3977 V AlarmManager:  remove PendingIntent] PendingIntent{dfff2a8: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:51.332  4992  5112 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
,09-21 17:05:51.332  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:51.342  3425  3971 V AlarmManager:  remove PendingIntent] PendingIntent{7d9b1c1: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
09-21 17:05:51.332  4992  5112 D BtGatt.GattService: current time is 275869044763
,09-21 17:05:51.332  4992  5112 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -85, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-21 17:05:51.342  4992  5112 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-21 17:05:51.342  4992  5112 D ScanRecord: parseFromBytes
09-21 17:05:51.342  4992  5112 D ScanRecord: first manudata for manu ID
09-21 17:05:51.342  4992  5112 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-21 17:05:51.342  4992  5112 D ScanRecord: parseFromBytes
,09-21 17:05:51.342  4992  5112 D ScanRecord: first manudata for manu ID
09-21 17:05:51.342  9323  9335 D ScanRecord: parseFromBytes
,09-21 17:05:51.342  9323  9335 D ScanRecord: first manudata for manu ID
09-21 17:05:51.342  9323  9335 D ScanRecord: parseFromBytes
09-21 17:05:51.342  9323  9335 D ScanRecord: first manudata for manu ID
09-21 17:05:51.342  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:51.352  3425  4594 V AlarmManager:  remove PendingIntent] PendingIntent{81fad66: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:51.352  3425  4289 V AlarmManager:  remove PendingIntent] PendingIntent{f3618a7: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:51.362  3425  3446 V AlarmManager:  remove PendingIntent] PendingIntent{db59154: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:51.362  3425  3447 V AlarmManager:  remove PendingIntent] PendingIntent{38ea8fd: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:51.372  3425  4316 V AlarmManager:  remove PendingIntent] PendingIntent{be939f2: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:51.522  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:51.702  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:51.882  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:52.062  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:52.242  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:52.342  3425  3813 V AlarmManager: Expired Alarm result :4
,09-21 17:05:52.342  4992  4992 D BtGatt.ScanManager: awakened up at time 276877
,09-21 17:05:52.342  4992  5206 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-21 17:05:52.352  3425  4409 V AlarmManager:  remove PendingIntent] PendingIntent{2846ec0: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:52.352  4992  5112 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-21 17:05:52.352  4992  5112 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-21 17:05:52.362  3425  4048 V AlarmManager:  remove PendingIntent] PendingIntent{4a1d7f9: PendingIntentRecord{a5f8fd4 com.android.bluetooth broadcastIntent}}
,09-21 17:05:52.372  3425  4237 V AlarmManager:  remove PendingIntent] PendingIntent{c4d033e: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:52.382  3425  3977 V AlarmManager:  remove PendingIntent] PendingIntent{3bb759f: PendingIntentRecord{649045c com.android.bluetooth broadcastIntent}}
,09-21 17:05:52.422  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:52.602  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:52.782  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 17:05:52.962  3425  3793 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
