#### Test 85046911bd0d025_thali04_samsung-SM-G935F Logs


```
--------- beginning of main
09-20 13:39:08.631  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:08.811  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:39:08.991  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:39:09.171  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:39:09.191  9619  9619 I FIPS_bssl: FIPS approved mode (1) | 9619 | app_process
09-20 13:39:09.191  9619  9619 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-20 13:39:09.201  9619  9619 D AndroidRuntime: CheckJNI is OFF
09-20 13:39:09.201  9619  9619 D AndroidRuntime: readGMSProperty: start
09-20 13:39:09.201  9619  9619 D AndroidRuntime: readGMSProperty: already setted!!
09-20 13:39:09.201  9619  9619 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-20 13:39:09.201  9619  9619 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-20 13:39:09.201  9619  9619 D AndroidRuntime: readGMSProperty: end
09-20 13:39:09.201  9619  9619 D AndroidRuntime: addProductProperty: start
09-20 13:39:09.211  9619  9619 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-20 13:39:09.241  9619  9619 I Radio-JNI: register_android_hardware_Radio DONE
09-20 13:39:09.241  9619  9619 E AffinityControl: AffinityControl: registerfunction enter
09-20 13:39:09.251  9619  9619 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-20 13:39:09.281  3454  3843 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-20 13:39:09.281  3454  3843 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-20 13:39:09.301  3454  3843 D ResourcesManager: For user 0 new overlays fetched Null
09-20 13:39:09.301  3454  3843 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:39:09.301  3454  3843 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-20 13:39:09.311  3454  3843 D ActivityManager: mDVFSHelper.acquire()
09-20 13:39:09.311  3454  3843 V WindowManager: addAppToken: AppWindowToken{d0d5f89b9 token=Token{b46cf80 ActivityRecord{3620403 u0 com.test.thalitest/.MainActivity t75}}} to stack=2 task=75 at 0
09-20 13:39:09.321  3454  3557 I InjectionManager: Inside getClassLibPath caller 
09-20 13:39:09.331  3454  3557 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-20 13:39:09.331  3454  3557 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b1bb6f1 V.E...... R.....ID 0,0-0,0}
09-20 13:39:09.341  3454  3557 W WindowManager: Failed looking up window
09-20 13:39:09.341  3454  3557 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@bf082d6 does not exist
09-20 13:39:09.341  3454  3557 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 13:39:09.341  3454  3557 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-20 13:39:09.341  9628  9628 E Zygote  : v2
09-20 13:39:09.341  9628  9628 I libpersona: KNOX_SDCARD checking this for 10177
09-20 13:39:09.341  3454  3557 D ISSUE_DEBUG: InputChannelName : 4c91957 Starting com.test.thalitest
09-20 13:39:09.341  9628  9628 I libpersona: KNOX_SDCARD not a persona
09-20 13:39:09.341  9628  9628 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-20 13:39:09.341  9628  9628 E Zygote  : accessInfo : 0
09-20 13:39:09.341  9628  9628 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-20 13:39:09.341  3454  3843 I ActivityManager: Start proc 9628:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-20 13:39:09.341  3454  3843 D InputDispatcher: Focused application set to: xxxx
09-20 13:39:09.341  9619  9619 D AndroidRuntime: Shutting down VM
09-20 13:39:09.341  3454  3862 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-20 13:39:09.341  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:39:09.351  3009  3009 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-20 13:39:09.371  9628  9628 D TimaKeyStoreProvider: TimaSignature is unavailable
09-20 13:39:09.371  9628  9628 D ActivityThread: Added TimaKeyStore provider
09-20 13:39:09.391  6204  6204 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 13:39:09.401  3454  4974 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3454
09-20 13:39:09.401  3454  4974 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 13:39:09.401  3454  4974 D PowerManagerService: mDisplayReady: false
09-20 13:39:09.401  3454  4974 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 13:39:09.401  3454  3561 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:39:09.401  6204  6204 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 13:39:09.401  3454  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:39:09.401  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb3543c00
09-20 13:39:09.401  3454  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:39:09.401  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-20 13:39:09.401  3454  4974 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 13:39:09.401  3454  3561 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:39:09.401  3454  3571 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-20 13:39:09.401  3454  3478 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3454
09-20 13:39:09.401  3454  3561 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:39:09.401  3454  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:39:09.401  3454  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:39:09.401  3454  3561 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:39:09.411  3454  3561 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 13:39:09.411  3454  3561 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 13:39:09.411  3454  3561 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:39:09.411  3454  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:39:09.411  3454  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:39:09.411  3454  3561 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:39:09.411  3454  3561 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 13:39:09.411  3454  3561 D PowerManagerService: mDisplayReady: true
09-20 13:39:09.411  3454  3561 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-20 13:39:09.411  3454  4434 D ActivityManager:  Launching com.test.thalitest, updated priority
09-20 13:39:09.421  3454  3477 V WindowStateAnimator: Finishing drawing window Window{4d04e8b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-20 13:39:09.431  3009  3984 D libEGL  : eglTerminate EGLDisplay = 0x7fadf3ee78
09-20 13:39:09.431  3454  3454 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-20 13:39:09.431  3009  3984 D libEGL  : eglTerminate EGLDisplay = 0x7fadf3ee78
09-20 13:39:09.431  5826  5836 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-20 13:39:09.441  3454  3529 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-20 13:39:09.451  3009  4477 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-20 13:39:09.451  3009  3018 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-20 13:39:09.451  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc75566c8
09-20 13:39:09.461  3454  4432 V WindowStateAnimator: Finishing drawing window Window{51f1405 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-20 13:39:09.461  6204  6204 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 13:39:09.461  4313  4313 V ActivityThread: updateVisibility : ActivityRecord{f556570 token=android.os.BinderProxy@833ed43 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-20 13:39:09.461  4313  4313 D Launcher: onTrimMemory. Level: 20
09-20 13:39:09.461  6204  6204 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 13:39:09.461  6204  6204 V ActivityThread: updateVisibility : ActivityRecord{5ddd037 token=android.os.BinderProxy@78303a8 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-20 13:39:09.461  3009  3984 I SurfaceFlinger: id=18 Removed VSBConnecti (7/12)
09-20 13:39:09.461  3009  4622 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/12)
09-20 13:39:09.471  3009  4622 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
09-20 13:39:09.471  3009  4477 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
09-20 13:39:09.471  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc75566c8
09-20 13:39:09.471  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc7556698
09-20 13:39:09.471  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc7556698
09-20 13:39:09.521  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:39:09.551  3454  3454 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3454 (0x0)
09-20 13:39:09.551  3454  3454 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3454 (0x0)
09-20 13:39:09.551  3454  3454 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 13:39:09.551  3454  3454 D PowerManagerService: mDisplayReady: false
09-20 13:39:09.551  3454  3454 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 13:39:09.551  3454  3561 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:39:09.551  3454  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:39:09.551  3454  3454 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 13:39:09.551  3454  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:39:09.551  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb3543c00
09-20 13:39:09.551  3454  3561 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:39:09.551  3454  3571 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-20 13:39:09.561  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-20 13:39:09.561  3454  3561 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:39:09.561  3454  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:39:09.561  3454  3561 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 13:39:09.561  3454  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:39:09.561  3454  3561 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 13:39:09.561  3454  3561 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:39:09.561  3454  3561 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:39:09.561  3454  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:39:09.561  3454  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:39:09.561  3454  3561 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:39:09.561  3454  3561 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 13:39:09.561  3454  3561 D PowerManagerService: mDisplayReady: true
09-20 13:39:09.561  3454  3561 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 13:39:09.711  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:39:09.731  5826  5826 I TrayVisibilityController: handleMessage : msg.what = 1
09-20 13:39:09.751  3454  4434 I WindowManager: Screenshot max retries 4 of Token{b46cf80 ActivityRecord{3620403 u0 com.test.thalitest/.MainActivity t75}} appWin=Window{4c91957 u0 d0 Starting com.test.thalitest} drawState=1
09-20 13:39:09.751  5826  5837 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-20 13:39:09.761  3454  3557 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:39:09.761  3454  3454 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:39:09.761  3454  3557 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-20 13:39:09.761  3454  6112 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:39:09.761  3454  6112 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:39:09.771  3454  3862 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-20 13:39:09.771  5826  5826 I Utils   : isCurrentUser current = 0, ownerId = 0
09-20 13:39:09.771  5826  5826 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-20 13:39:09.771  5826  5826 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-20 13:39:09.771  3454  3454 I KnoxTimeoutHandler: SD activityfalse
09-20 13:39:09.791  3454  6112 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 13:39:09.791  3454  6112 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:39:09.791  9628  9628 D RelationGraph: garbageCollect()
09-20 13:39:09.791  9628  9628 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-20 13:39:09.801  9628  9628 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 13:39:09.801  3454  3843 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-20 13:39:09.801  9628  9628 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-20 13:39:09.801  3454  6112 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 13:39:09.801  3454  6112 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:39:09.801  3454  6112 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:39:09.811  3454  3557 V WindowStateAnimator: Finishing drawing window Window{4c91957 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-20 13:39:09.811  3454  3557 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:39:09.811  3454  3454 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:39:09.811  3454  3454 I KnoxTimeoutHandler: SD activityfalse
09-20 13:39:09.811  3454  3557 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{26c9377 u0 com.samsung.android.MtpApplication/.USBConnection t74} time:162194
09-20 13:39:09.811  3454  3557 D ActivityManager: mDVFSHelper.release()
09-20 13:39:09.811  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fc75565a8
09-20 13:39:09.821  9628  9628 D ResourcesManager: For user 0 new overlays fetched Null
09-20 13:39:09.821  9628  9628 I InjectionManager: Inside getClassLibPath caller 
09-20 13:39:09.841  9628  9628 D InjectionManager: InjectionManager
09-20 13:39:09.841  9628  9628 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-20 13:39:09.841  9628  9628 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-20 13:39:09.841  9628  9628 I InjectionManager: featureStore :{}
09-20 13:39:09.841  9628  9628 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 13:39:09.841  9628  9628 D RelationGraph: garbageCollect()
09-20 13:39:09.851  9628  9628 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 13:39:09.881  9628  9628 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-20 13:39:09.881  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:39:09.931  3454  6112 D SSRM:n  : SIOP:: AP = 290, PST = 307 (W:14), CP = 247, CUR = 175, LCD = 1
09-20 13:39:09.931  3454  6112 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 13:39:09.941  9628  9628 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-20 13:39:09.951  9628  9628 D ResourcesManager: For user 0 new overlays fetched Null
09-20 13:39:09.951  9628  9628 I InjectionManager: Inside getClassLibPath caller 
09-20 13:39:09.961  9628  9628 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-20 13:39:10.001  9628  9628 I cr_LibraryLoader: Time to load native libraries: 28 ms (timestamps 2357-2385)
09-20 13:39:10.001  9628  9628 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-20 13:39:10.021  3454  3885 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-20 13:39:10.061  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:39:10.061  9628  9642 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-20 13:39:10.081  9628  9628 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8d78c78}
09-20 13:39:10.081  9628  9628 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-20 13:39:10.111  9628  9628 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-20 13:39:10.121  3454  3885 I MdnieScenarioControlService: mGameModeLauncher : false
09-20 13:39:10.121  3454  3885 I MdnieScenarioControlService: setUIMode
09-20 13:39:10.151  9628  9628 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-20 13:39:10.241  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:39:10.261  3454  3529 W ActivityManager: Activity pause timeout for ActivityRecord{3620403 u0 com.test.thalitest/.MainActivity t75}
09-20 13:39:10.371  9628  9628 D libEGL  : eglInitialize EGLDisplay = 0xff83867c
,09-20 13:39:10.431  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:10.481  3454  4911 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
,09-20 13:39:10.491  3454  4911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-20 13:39:10.571  9628  9628 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-20 13:39:10.591  9628  9628 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-20 13:39:10.591  9628  9628 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-20 13:39:10.601  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:10.651  9628  9628 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-20 13:39:10.741  9628  9628 D Activity: performCreate Call Injection manager
,09-20 13:39:10.751  9628  9628 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-20 13:39:10.761  3454  6113 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-20 13:39:10.761  9628  9628 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-20 13:39:10.771  9628  9628 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{472be97 I.E...... R.....ID 0,0-0,0}
,09-20 13:39:10.781  9628  9679 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-20 13:39:10.781  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:10.791  3454  4267 W WindowManager: Failed looking up window
09-20 13:39:10.791  3454  4267 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@70a2436 does not exist
09-20 13:39:10.791  3454  4267 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 13:39:10.791  3454  4267 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 13:39:10.791  3454  4267 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 13:39:10.791  3454  4267 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-20 13:39:10.791  3454  4267 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-20 13:39:10.791  3454  4267 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-20 13:39:10.791  3454  3477 D ISSUE_DEBUG: InputChannelName : e1e0f37 com.test.thalitest/com.test.thalitest.MainActivity
,09-20 13:39:10.801  3454  4432 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,09-20 13:39:10.801  3454  4432 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-20 13:39:10.801  3454  3454 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-20 13:39:10.801  3454  3454 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-20 13:39:10.811  9628  9628 V ActivityThread: updateVisibility : ActivityRecord{721186d token=android.os.BinderProxy@76ad6de {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-20 13:39:10.821  9628  9642 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-20 13:39:10.841  9628  9628 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9628
,09-20 13:39:10.841  3454  4911 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9628 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 13:39:10.851  3454  3873 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-20 13:39:10.851  3454  3873 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-20 13:39:10.851  3454  3873 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-20 13:39:10.861  3454  3873 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 13:39:10.861  3454  3873 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-20 13:39:10.871  3454  3873 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 13:39:10.871  9628  9628 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-20 13:39:10.881  3454  3873 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-20 13:39:10.881  3454  3873 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 13:39:10.891  3009  3009 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,09-20 13:39:10.901  3454  4974 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-20 13:39:10.901  3454  4974 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-20 13:39:10.901  3454  4974 D BatteryService: online:4, current avg:167, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:178
09-20 13:39:10.901  3454  4974 D BatteryService: stay LED for fully charged
09-20 13:39:10.901  3454  3454 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-20 13:39:10.901  3454  3454 I MotionRecognitionService: Plugged
09-20 13:39:10.901  3454  3454 D MotionRecognitionService:   cableConnection= 1
09-20 13:39:10.901  3454  3454 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-20 13:39:10.901  3454  3454 D MotionRecognitionService: skip setTransmitPower. 
,09-20 13:39:10.911  3454  3867 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-20 13:39:10.911  3943  3943 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-20 13:39:10.911  3943  3943 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-20 13:39:10.911  3943  3943 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-20 13:39:10.911  9628  9679 D libEGL  : eglInitialize EGLDisplay = 0xdc77f7c4
,09-20 13:39:10.911  9628  9679 I OpenGLRenderer: Initialized EGL, version 1.4
,09-20 13:39:10.921  5091  5091 D CommonServiceConfiguration: getStringValueSetting
,09-20 13:39:10.921  9628  9679 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-20 13:39:10.921  5051  5051 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-20 13:39:10.921  5051  5425 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-20 13:39:10.941  5091  5091 D BatteryMonitor: new battery level: 100
,09-20 13:39:10.941  4726  4726 D BatteryController: saveBatteryData : level[100], status[5]
09-20 13:39:10.941  3943  3943 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-20 13:39:10.941  3943  3943 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-20 13:39:10.951  3454  4432 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3454
,09-20 13:39:10.951  3454  4432 I libsuspend: !@autosuspend_wakeup_count_disable
,09-20 13:39:10.951  3454  4432 D PowerManagerService: mDisplayReady: false
09-20 13:39:10.951  3454  4432 I libsuspend: !@autosuspend_wakeup_count_disable done
,09-20 13:39:10.951  3454  3561 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:39:10.951  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fb3543c00
09-20 13:39:10.951  3454  4432 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 13:39:10.951  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,09-20 13:39:10.951  3454  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:39:10.951  3454  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:39:10.951  3454  3561 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:39:10.951  3454  3571 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-20 13:39:10.951  3454  3557 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
,09-20 13:39:10.951  3454  3557 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-20 13:39:10.961  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:10.971  3454  3561 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:39:10.971  3454  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:39:10.971  3454  3561 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 13:39:10.971  3454  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:39:10.971  3454  3561 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 13:39:10.971  3454  3561 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:39:10.971  3454  3561 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:39:10.971  3454  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:39:10.971  3454  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:39:10.971  3454  3561 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:39:10.971  3454  3561 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 13:39:10.971  3454  3561 D PowerManagerService: mDisplayReady: true
09-20 13:39:10.971  3454  3561 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 13:39:10.981  5826  5826 E CocktailBarPositionManager: Window direction: 0
09-20 13:39:10.981  5826  5826 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 13:39:10.991  9628  9628 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-20 13:39:11.001  3454  4434 V WindowStateAnimator: Finishing drawing window Window{e1e0f37 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-20 13:39:11.001  9628  9628 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-20 13:39:11.011  3454  4141 E Watchdog: !@Sync 5 [09-20 13:39:11.021]
,09-20 13:39:11.011  3454  3859 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3454
,09-20 13:39:11.011  3454  3557 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 13:39:11.011  3454  3454 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 13:39:11.011  3454  3557 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s256ms (total +1s698ms)
09-20 13:39:11.011  3454  3557 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3620403 u0 com.test.thalitest/.MainActivity t75} time:163396
09-20 13:39:11.011  3454  3557 D ViewRootImpl: #3 mView = null
09-20 13:39:11.011  3009  4477 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
09-20 13:39:11.011  3454  3454 I KnoxTimeoutHandler: SD activityfalse
09-20 13:39:11.011  3009  4622 I SurfaceFlinger: id=20 Removed uhalitest (-2/11)
09-20 13:39:11.021  3454  4267 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3454
,09-20 13:39:11.021  3454  4975 V WindowStateAnimator: Finishing drawing window Window{e1e0f37 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-20 13:39:11.031  9628  9628 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@76ad6de time:163411
,09-20 13:39:11.031  9628  9684 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-20 13:39:11.031  9628  9684 D libEGL  : eglInitialize EGLDisplay = 0xdafff3f4
09-20 13:39:11.031  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc75566c8
,09-20 13:39:11.061  9628  9684 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-20 13:39:11.111  9628  9628 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9628
,09-20 13:39:11.141  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:11.171  3454  3454 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3454 (0x0)
09-20 13:39:11.171  3454  3454 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 13:39:11.171  3454  3454 D PowerManagerService: mDisplayReady: false
09-20 13:39:11.171  3454  3454 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 13:39:11.171  3454  3454 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 13:39:11.171  3454  3561 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:39:11.171  3454  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:39:11.171  3454  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:39:11.171  3454  3561 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-20 13:39:11.171  3454  3571 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-20 13:39:11.171  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fb3543c00
09-20 13:39:11.171  3454  3557 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-20 13:39:11.171  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,09-20 13:39:11.171  3454  3557 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-20 13:39:11.191  3454  3561 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:39:11.191  3454  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:39:11.191  3454  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:39:11.191  3454  3561 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 13:39:11.191  3454  3561 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:39:11.191  3454  3561 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 13:39:11.191  3454  3561 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:39:11.191  3454  3561 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:39:11.191  3454  3561 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:39:11.191  3454  3561 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:39:11.191  3454  3561 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 13:39:11.191  3454  3561 D PowerManagerService: mDisplayReady: true
09-20 13:39:11.191  3454  3561 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 13:39:11.201  5826  5826 E CocktailBarPositionManager: Window direction: 0
09-20 13:39:11.201  5826  5826 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 13:39:11.261  4026  4026 D Recents : onTaskStackChanged
,09-20 13:39:11.271  4026  4026 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-20 13:39:11.281  4026  4026 D ResourcesManager: For user 0 new overlays fetched Null
,09-20 13:39:11.321  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:11.331  9628  9628 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-20 13:39:11.431  9628  9691 D jxcore_app_log: JniHelper::setJavaVM(0xf4d74000), pthread_self() = -630195920
,09-20 13:39:11.431  9628  9691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-20 13:39:11.431  9628  9691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-20 13:39:11.431  9628  9691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-20 13:39:11.431  9628  9691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-20 13:39:11.431  9628  9691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-20 13:39:11.431  9628  9691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a7b87 added. We now have 1 listener(s)
,09-20 13:39:11.431  9628  9691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
,09-20 13:39:11.431  9628  9691 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
,09-20 13:39:11.431  9628  9691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-20 13:39:11.431  9628  9691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-20 13:39:11.441  9628  9691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5efa252 added. We now have 1 listener(s)
09-20 13:39:11.441  9628  9691 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-20 13:39:11.441  9628  9691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-20 13:39:11.441  9628  9691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-20 13:39:11.441  9628  9691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-20 13:39:11.441  9628  9691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-20 13:39:11.441  9628  9691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-20 13:39:11.441  9628  9691 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 13:39:11.441  9628  9691 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
09-20 13:39:11.451  9628  9691 D BluetoothAdapter: STATE_ON
09-20 13:39:11.451  9628  9691 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-20 13:39:11.451  9628  9691 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 13:39:11.451  9628  9691 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 13:39:11.451  9628  9691 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 13:39:11.451  9628  9691 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 13:39:11.451  9628  9691 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 13:39:11.451  9628  9691 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 13:39:11.451  9628  9691 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 13:39:11.451  9628  9691 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-20 13:39:11.451  9628  9691 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-20 13:39:11.451  9628  9691 D io.jxcore.node.ConnectivityMonitor: start: OK
09-20 13:39:11.451  9628  9691 I io.jxcore.node.LifeCycleMonitor: start: OK
09-20 13:39:11.461  9628  9628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-20 13:39:11.461  9628  9628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 13:39:11.491  9628  9628 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-20 13:39:11.501  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:11.681  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:11.811  9628  9692 W jxcore-log: Initializing JXcore engine
09-20 13:39:11.811  9628  9692 W jxcore-log: JXcore engine is ready
,09-20 13:39:11.831  5059  5059 E audit   : type=1400 msg=audit(1474371551.831:262): avc:  denied  { ioctl } for  pid=9692 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3112 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-20 13:39:11.831  5059  5059 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-20 13:39:11.831  5059  5059 E audit   : type=1300 msg=audit(1474371551.831:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d92c43c8 items=0 ppid=3179 pid=9692 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-20 13:39:11.831  5059  5059 E audit   : type=1327 msg=audit(1474371551.831:262): proctitle="com.test.thalitest"
09-20 13:39:11.831  5059  5059 E audit   : type=1320 msg=audit(1474371551.831:262): 
09-20 13:39:11.831  5059  5059 E audit   : type=1400 msg=audit(1474371551.831:263): avc:  denied  { ioctl } for  pid=9692 comm="Thread-160" path="socket:[11213]" dev="sockfs" ino=11213 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-20 13:39:11.831  5059  5059 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-20 13:39:11.831  5059  5059 E audit   : type=1300 msg=audit(1474371551.831:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d92c43c8 items=0 ppid=3179 pid=9692 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-20 13:39:11.831  5059  5059 E audit   : type=1327 msg=audit(1474371551.831:263): proctitle="com.test.thalitest"
09-20 13:39:11.831  5059  5059 E audit   : type=1320 msg=audit(1474371551.831:263): 
,09-20 13:39:11.841  9628  9692 W jxcore-log: Starting JXcore engine
,09-20 13:39:11.861  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:11.881  9628  9692 W jxcore-log: Platform android
09-20 13:39:11.881  9628  9692 W jxcore-log: 
09-20 13:39:11.881  9628  9692 W jxcore-log: Process ARCH arm
09-20 13:39:11.881  9628  9692 W jxcore-log: 
,09-20 13:39:11.941  9628  9692 I jxcore-log: JXcore Cordova bridge is ready!
09-20 13:39:11.941  9628  9692 I jxcore-log: 
09-20 13:39:11.951  9628  9692 W jxcore-log: JXcore engine is started
,09-20 13:39:11.951  9628  9691 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-20 13:39:11.961  9628  9628 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-20 13:39:12.041  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:12.221  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:12.321  3454  3911 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/75_task.xml.bak
,09-20 13:39:12.401  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:12.581  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:12.761  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:12.771  3454  6112 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-20 13:39:12.941  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:13.121  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:13.301  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:13.481  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:13.661  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:13.841  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:14.021  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:14.201  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:14.381  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:14.561  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:14.741  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:14.921  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:15.101  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:15.281  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:15.461  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:15.641  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:15.821  3454  6112 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-20 13:39:15.821  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:16.001  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:16.181  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:16.241  9628  9692 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-20 13:39:16.241  9628  9692 I jxcore-log: 
,09-20 13:39:16.241  9628  9692 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-20 13:39:16.241  9628  9692 I jxcore-log: 
,09-20 13:39:16.251  9628  9692 D BluetoothAdapter: STATE_ON
,09-20 13:39:16.261  9628  9692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 13:39:16.261  9628  9692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 13:39:16.261  9628  9692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 13:39:16.261  9628  9692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 13:39:16.261  9628  9692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 13:39:16.261  9628  9692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 13:39:16.261  9628  9692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 13:39:16.261  9628  9692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 13:39:16.261  9628  9692 D BluetoothAdapter: STATE_ON
,09-20 13:39:16.261  9628  9692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-20 13:39:16.261  9628  9692 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-20 13:39:16.261  9628  9692 I jxcore-log: 
09-20 13:39:16.261  9628  9692 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-20 13:39:16.261  9628  9692 I jxcore-log: 
,09-20 13:39:16.361  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:16.491  9628  9692 D executeNativeTests: Running unit tests
,09-20 13:39:16.501  9628  9692 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
,09-20 13:39:16.501  9628  9692 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-20 13:39:16.501  9628  9692 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-20 13:39:16.501  9628  9692 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-20 13:39:16.501  9628  9692 D com.test.thalitest.ThaliTestRunner: Total duration: 1 ms
09-20 13:39:16.501  9628  9692 I jxcore-log: *Native tests were executed*
09-20 13:39:16.501  9628  9692 I jxcore-log: 
,09-20 13:39:16.501  9628  9692 I jxcore-log: Total number of executed tests:  1
09-20 13:39:16.501  9628  9692 I jxcore-log: 
09-20 13:39:16.501  9628  9692 I jxcore-log: Number of passed tests:  1
09-20 13:39:16.501  9628  9692 I jxcore-log: 
09-20 13:39:16.501  9628  9692 I jxcore-log: Number of failed tests:  0
09-20 13:39:16.501  9628  9692 I jxcore-log: 
09-20 13:39:16.501  9628  9692 I jxcore-log: Number of ignored tests:  0
09-20 13:39:16.501  9628  9692 I jxcore-log: 
,09-20 13:39:16.501  9628  9692 I jxcore-log: Total duration:  1
09-20 13:39:16.501  9628  9692 I jxcore-log: 
09-20 13:39:16.501  9628  9692 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-20 13:39:16.501  9628  9692 I jxcore-log: 
09-20 13:39:16.501  9628  9692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-20 13:39:16.501  9628  9692 I jxcore-log: 
,09-20 13:39:16.521  9628  9628 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-20 13:39:16.541  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:16.721  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:16.901  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:16.971  9693  9693 I FIPS_bssl: FIPS approved mode (1) | 9693 | app_process
,09-20 13:39:16.971  9693  9693 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-20 13:39:16.971  9693  9693 D AndroidRuntime: CheckJNI is OFF
09-20 13:39:16.971  9693  9693 D AndroidRuntime: readGMSProperty: start
09-20 13:39:16.971  9693  9693 D AndroidRuntime: readGMSProperty: already setted!!
09-20 13:39:16.971  9693  9693 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-20 13:39:16.971  9693  9693 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-20 13:39:16.971  9693  9693 D AndroidRuntime: readGMSProperty: end
09-20 13:39:16.971  9693  9693 D AndroidRuntime: addProductProperty: start
,09-20 13:39:16.991  9693  9693 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-20 13:39:17.011  9693  9693 I Radio-JNI: register_android_hardware_Radio DONE
,09-20 13:39:17.021  9693  9693 E AffinityControl: AffinityControl: registerfunction enter
,09-20 13:39:17.021  9693  9693 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-20 13:39:17.031  3454  3477 D PackageManager: START PACKAGE DELETE: observer{141905960}
09-20 13:39:17.031  3454  3477 D PackageManager: pkg{<packageName>}
09-20 13:39:17.031  3454  3477 D PackageManager: user{0}
09-20 13:39:17.031  3454  3477 D PackageManager: caller{2000}
09-20 13:39:17.031  3454  3477 D PackageManager: flags{2}
,09-20 13:39:17.031  3454  3477 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-20 13:39:17.031  3454  3477 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-20 13:39:17.031  3454  3477 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-20 13:39:17.031  3454  3477 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-20 13:39:17.031  3454  3477 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-20 13:39:17.031  3454  3589 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,09-20 13:39:17.031  3454  3589 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-20 13:39:17.031  3454  3589 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-20 13:39:17.031  3454  3589 D ApplicationPolicy: getApplicationUninstallationEnabled
09-20 13:39:17.031  3454  3589 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-20 13:39:17.031  3454  3589 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-20 13:39:17.041  3454  3589 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-20 13:39:17.041  3454  3589 D PackageManager: !@killApplicatoin: 10177, uninstall pkg
,09-20 13:39:17.041  3454  3589 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-20 13:39:17.041  3454  3529 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=-1: uninstall pkg
09-20 13:39:17.041  3454  3589 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-20 13:39:17.041  3454  3529 I ActivityManager: Killing 9628:com.test.thalitest/u0a177 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-20 13:39:17.041  3454  3529 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-20 13:39:17.051  3454  3529 D ActivityManager: mDVFSHelper.acquire()
,09-20 13:39:17.061  3454  3589 D AASAinstall: there is not AASApackages.xml file
,09-20 13:39:17.071  9702  9702 E Zygote  : v2
09-20 13:39:17.071  9702  9702 I libpersona: KNOX_SDCARD checking this for 10177
09-20 13:39:17.071  9702  9702 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-20 13:39:17.071  9702  9702 I libpersona: KNOX_SDCARD not a persona
,09-20 13:39:17.071  9702  9702 E Zygote  : accessInfo : 0
09-20 13:39:17.071  9702  9702 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,09-20 13:39:17.071  3454  3529 I ActivityManager: Start proc 9702:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
,09-20 13:39:17.081  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:39:17.081  3454  3529 I ActivityManager:   Force finishing activity ActivityRecord{3620403 u0 com.test.thalitest/.MainActivity t75}
,09-20 13:39:17.081  3454  3529 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,09-20 13:39:17.081  9702  9702 D TimaKeyStoreProvider: TimaSignature is unavailable
09-20 13:39:17.081  9702  9702 D ActivityThread: Added TimaKeyStore provider
,09-20 13:39:17.141  3454  4975 D GraphicsStats: Buffer count: 7
,09-20 13:39:17.141  3454  3477 I WindowState: WIN DEATH: Window{e1e0f37 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
09-20 13:39:17.141  3454  4911 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@c5b3427)
09-20 13:39:17.141  3454  3873 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 13:39:17.141  3454  3873 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 13:39:17.141  3454  3873 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 13:39:17.141  3009  3020 I SurfaceFlinger: id=21 Removed NainActivit (6/10)
,09-20 13:39:17.151  3009  4477 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
09-20 13:39:17.151  3009  4622 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
,09-20 13:39:17.181  3454  6148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-20 13:39:17.261  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:17.281  3454  3589 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-20 13:39:17.351  3454  3589 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
09-20 13:39:17.351  3166  3166 W keystore: ENTER clear_uid from uid 1000 for 10177
09-20 13:39:17.351  3454  3589 I art     : Waiting for a blocking GC Explicit
09-20 13:39:17.351  3454  3465 I art     : Background sticky concurrent mark sweep GC freed 199296(12MB) AllocSpace objects, 75(1680KB) LOS objects, 25% free, 42MB/56MB, paused 3.712ms total 121.702ms
09-20 13:39:17.351  3454  3589 I art     : Starting a blocking GC Explicit
09-20 13:39:17.361  3454  3557 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-20 13:39:17.361  3454  3557 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-20 13:39:17.361  3454  3557 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
09-20 13:39:17.361  3454  3557 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-20 13:39:17.361  3454  3557 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-20 13:39:17.361  3454  3557 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-20 13:39:17.361  3454  3557 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 13:39:17.361  3454  3557 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-20 13:39:17.361  3454  3557 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 13:39:17.361  3454  3557 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-20 13:39:17.361  3454  3557 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-20 13:39:17.361  3454  3557 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{c121779 V.E...... R.....ID 0,0-0,0}
09-20 13:39:17.361  3454  3557 W WindowManager: Failed looking up window
09-20 13:39:17.361  3454  3557 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@7710cbe does not exist
09-20 13:39:17.361  3454  3557 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 13:39:17.361  3454  3557 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-20 13:39:17.361  3454  3557 D ISSUE_DEBUG: InputChannelName : 5f8811f Starting com.test.thalitest
,09-20 13:39:17.371  3009  3009 I SurfaceFlinger: id=22 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-20 13:39:17.391  6204  6204 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,09-20 13:39:17.411  4313  4313 D Launcher: onRestart, Launcher: 181973588
,09-20 13:39:17.431  3454  4974 V WindowStateAnimator: Finishing drawing window Window{51f1405 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-20 13:39:17.431  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fc75565a8
09-20 13:39:17.431  6204  6204 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,09-20 13:39:17.441  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:17.541  3454  3589 I art     : Explicit concurrent mark sweep GC freed 103138(6MB) AllocSpace objects, 6(1912KB) LOS objects, 32% free, 33MB/49MB, paused 1.729ms total 191.264ms
,09-20 13:39:17.581  3454  3589 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-20 13:39:17.581  3454  3589 D AASAuninstall: userId = 0, info.removedAppID = 10177, info.uid = 10177, packageName = com.test.thalitest
,09-20 13:39:17.581  3454  3589 D AASAinstall: there is not AASApackages.xml file
09-20 13:39:17.581  3454  3589 D PackageManager: result of delete: 1{141905960}
,09-20 13:39:17.591  3454  3589 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-20 13:39:17.591  3454  3589 D PackageManager: userId{-1}
09-20 13:39:17.591  3454  3589 D PackageManager: andCode{true}
09-20 13:39:17.591  9693  9693 I art     : System.exit called, status: 0
09-20 13:39:17.591  9693  9693 I AndroidRuntime: VM exiting with result code 0.
,09-20 13:39:17.621  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:17.681  3454  3529 I WindowManager: Screenshot max retries 4 of Token{2333be4 ActivityRecord{26c9377 u0 com.samsung.android.MtpApplication/.USBConnection t74}} appWin=Window{51f1405 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=2
,09-20 13:39:17.691  5826  5837 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,09-20 13:39:17.691  5826  5906 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} Intent { flg=0x10800000 cmp=com.samsung.android.MtpApplication/.USBConnection VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-20 13:39:17.691  3454  3454 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-20 13:39:17.721  3454  3859 I ActivityManager: Killing 8405:com.samsung.storyservice/5004 (adj 15): DHA:empty #33
,09-20 13:39:17.731  4313  4313 D Launcher: onStart, Launcher: 181973588
09-20 13:39:17.731  4313  4313 D Launcher.HomeView: onStart
,09-20 13:39:17.741  4313  4313 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-20 13:39:17.741  3009  3009 I SurfaceFlinger: id=23 createSurf (1440x2560),1 flag=404, uhalitest
09-20 13:39:17.741  4313  4313 V ActivityThread: updateVisibility : ActivityRecord{f556570 token=android.os.BinderProxy@833ed43 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-20 13:39:17.751  4313  4313 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
09-20 13:39:17.751  4313  4313 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
09-20 13:39:17.751  3454  3529 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
09-20 13:39:17.751  4313  4313 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
09-20 13:39:17.751  4313  4313 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
09-20 13:39:17.751  4313  4313 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
09-20 13:39:17.751  4313  4313 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
09-20 13:39:17.751  4313  4313 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-20 13:39:17.751  4313  4313 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
09-20 13:39:17.751  4313  4313 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
,09-20 13:39:17.751  3009  3020 I SurfaceFlinger: id=23 Removed uhalitest (7/11)
09-20 13:39:17.761  3009  3984 I SurfaceFlinger: id=23 Removed uhalitest (-2/11)
,09-20 13:39:17.761  3454  3529 D InputDispatcher: Focused application released
,09-20 13:39:17.761  3454  3557 W WindowManager: Failed looking up window
09-20 13:39:17.761  3454  3557 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@7710cbe does not exist
09-20 13:39:17.761  3454  3557 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:2527)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1437)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:7403)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:920)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at android.view.Choreographer.doCallbacks(Choreographer.java:695)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at android.view.Choreographer.doFrame(Choreographer.java:631)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:906)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at android.os.Handler.handleCallback(Handler.java:739)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 13:39:17.761  3454  3557 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-20 13:39:17.761  3454  3557 D ViewRootImpl: #3 mView = null
,09-20 13:39:17.771  3454  3557 W WindowManager: Failed looking up window
09-20 13:39:17.771  3454  3557 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@7710cbe does not exist
09-20 13:39:17.771  3454  3557 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 13:39:17.771  3454  3557 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14795)
09-20 13:39:17.771  3454  3557 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:4612)
09-20 13:39:17.771  3454  3557 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:196)
09-20 13:39:17.771  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3754)
09-20 13:39:17.771  3454  3557 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:6893)
09-20 13:39:17.771  3454  3557 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:4238)
09-20 13:39:17.771  3454  3557 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 13:39:17.771  3454  3557 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-20 13:39:17.771  3454  3557 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 13:39:17.771  3454  3557 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-20 13:39:17.771  3009  3009 I SurfaceFlinger: id=24 createSurf (1440x2560),1 flag=4, MauncherAct
,09-20 13:39:17.771  9702  9702 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-20 13:39:17.771  9702  9702 D RelationGraph: garbageCollect()
09-20 13:39:17.771  3454  4975 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-20 13:39:17.771  3454  4975 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:39:17.771  3454  3454 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:39:17.771  6204  6204 D ViewRootImpl: Ignore stableInsets changed, SI=[0,0][0,0] PSI=[0,41][0,0]
,09-20 13:39:17.781  3454  3589 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=0: pkg removed
,09-20 13:39:17.781  3454  3589 I ActivityManager: Killing 9702:com.test.thalitest/u0a177 (adj 9): stop com.test.thalitest cause pkg removed
,09-20 13:39:17.791  9166  9719 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-20 13:39:17.791  3454  3589 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
09-20 13:39:17.791  3454  3454 I KnoxTimeoutHandler: Shared devices show user statefalse
09-20 13:39:17.791  3454  3454 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-20 13:39:17.791  3454  4432 V WindowStateAnimator: Finishing drawing window Window{51f1405 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-20 13:39:17.791  3009  3009 I SurfaceFlinger: id=25 createSurf (1592x384),1 flag=4, VSBConnecti
09-20 13:39:17.791  4313  4621 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-20 13:39:17.791  9166  9719 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-20 13:39:17.801  3454  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:39:17.811  9166  9719 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest

```
