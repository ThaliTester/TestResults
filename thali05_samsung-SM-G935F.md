#### Test 89624796d0595a7_thali05_samsung-SM-G935F Logs


```
--------- beginning of main
11-09 11:54:38.924  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:39.104  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-09 11:54:39.274  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-09 11:54:39.424  9608  9608 I FIPS_bssl: FIPS approved mode (1) | 9608 | app_process
11-09 11:54:39.434  9608  9608 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-09 11:54:39.434  9608  9608 D AndroidRuntime: CheckJNI is OFF
11-09 11:54:39.434  9608  9608 D AndroidRuntime: readGMSProperty: start
11-09 11:54:39.434  9608  9608 D AndroidRuntime: readGMSProperty: already setted!!
11-09 11:54:39.434  9608  9608 D AndroidRuntime: propertySet: couldn't set property (it is from app)
11-09 11:54:39.434  9608  9608 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
11-09 11:54:39.434  9608  9608 D AndroidRuntime: readGMSProperty: end
11-09 11:54:39.434  9608  9608 D AndroidRuntime: addProductProperty: start
11-09 11:54:39.454  9608  9608 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-09 11:54:39.454  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-09 11:54:39.484  9608  9608 I Radio-JNI: register_android_hardware_Radio DONE
11-09 11:54:39.494  9608  9608 E AffinityControl: AffinityControl: registerfunction enter
11-09 11:54:39.504  9608  9608 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-09 11:54:39.554  3427  4258 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
11-09 11:54:39.554  3427  4258 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
11-09 11:54:39.574  3427  4258 D ResourcesManager: For user 0 new overlays fetched Null
11-09 11:54:39.574  3427  4258 D GameManagerService: identifyGamePackage. com.test.thalitest
11-09 11:54:39.574  3427  4258 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
11-09 11:54:39.584  3427  4258 D ActivityManager: mDVFSHelper.acquire()
11-09 11:54:39.584  3427  4258 V WindowManager: addAppToken: AppWindowToken{d06137c2d token=Token{7a9f344 ActivityRecord{8f80c57 u0 com.test.thalitest/.MainActivity t13}}} to stack=2 task=13 at 0
11-09 11:54:39.584  3427  3579 I InjectionManager: Inside getClassLibPath caller 
11-09 11:54:39.594  3427  3579 D SecWifiDisplayUtil: Metadata value : SecSettings2
11-09 11:54:39.594  3427  3579 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{4a503e5 V.E...... R.....ID 0,0-0,0}
11-09 11:54:39.594  3427  3579 W WindowManager: Failed looking up window
11-09 11:54:39.594  3427  3579 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@9909eba does not exist
11-09 11:54:39.594  3427  3579 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-09 11:54:39.594  3427  3579 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-09 11:54:39.594  9617  9617 E Zygote  : v2
11-09 11:54:39.594  9617  9617 I libpersona: KNOX_SDCARD checking this for 10177
11-09 11:54:39.594  9617  9617 I libpersona: KNOX_SDCARD not a persona
11-09 11:54:39.604  3427  3579 D ISSUE_DEBUG: InputChannelName : cc716b Starting com.test.thalitest
11-09 11:54:39.604  9617  9617 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
11-09 11:54:39.604  3427  4258 I ActivityManager: Start proc 9617:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
11-09 11:54:39.604  9617  9617 E Zygote  : accessInfo : 0
11-09 11:54:39.604  9617  9617 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
11-09 11:54:39.604  3427  4258 D InputDispatcher: Focused application set to: xxxx
11-09 11:54:39.604  3427  3858 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
11-09 11:54:39.604  9608  9608 D AndroidRuntime: Shutting down VM
11-09 11:54:39.614  3009  3009 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, uhalitest
11-09 11:54:39.634  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-09 11:54:39.644  6167  6167 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
11-09 11:54:39.644  9617  9617 D TimaKeyStoreProvider: TimaSignature is unavailable
11-09 11:54:39.644  9617  9617 D ActivityThread: Added TimaKeyStore provider
11-09 11:54:39.654  3427  4426 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3427
11-09 11:54:39.654  3427  4426 I libsuspend: !@autosuspend_wakeup_count_disable
11-09 11:54:39.654  3427  4426 D PowerManagerService: mDisplayReady: false
11-09 11:54:39.654  3427  4426 I libsuspend: !@autosuspend_wakeup_count_disable done
11-09 11:54:39.654  3427  3583 D DisplayPowerController: animateScreenStateChange[0]: target=3
11-09 11:54:39.654  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f90683c00
11-09 11:54:39.654  3427  4426 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
11-09 11:54:39.654  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
11-09 11:54:39.654  3427  3583 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
11-09 11:54:39.654  3427  3583 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-09 11:54:39.654  3427  3583 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-09 11:54:39.654  3427  3595 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
11-09 11:54:39.654  3427  3583 D DisplayPowerController: animateScreenStateChange[0]: target=3
11-09 11:54:39.654  3427  3583 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
11-09 11:54:39.654  3427  3583 I libsuspend: !@autosuspend_wakeup_count_enable
11-09 11:54:39.654  3427  3583 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-09 11:54:39.654  3427  3583 I libsuspend: !@autosuspend_wakeup_count_enable done
11-09 11:54:39.654  3427  3583 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-09 11:54:39.654  3427  3583 D DisplayPowerController: animateScreenStateChange[0]: target=3
11-09 11:54:39.654  3427  3583 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
11-09 11:54:39.654  3427  3583 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-09 11:54:39.654  3427  3583 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-09 11:54:39.654  3427  3583 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
11-09 11:54:39.654  3427  3583 D PowerManagerService: mDisplayReady: true
11-09 11:54:39.654  3427  3583 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
11-09 11:54:39.664  3427  3982 D ActivityManager:  Launching com.test.thalitest, updated priority
11-09 11:54:39.674  3427  4891 V WindowStateAnimator: Finishing drawing window Window{ee34c18 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
11-09 11:54:39.674  6167  6167 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
11-09 11:54:39.674  6822  6822 V ActivityThread: updateVisibility : ActivityRecord{ff7e26b token=android.os.BinderProxy@dbed033 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
11-09 11:54:39.674  6167  6167 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
11-09 11:54:39.674  6167  6167 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
11-09 11:54:39.674  6167  6167 V ActivityThread: updateVisibility : ActivityRecord{396e805 token=android.os.BinderProxy@8d489df {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
11-09 11:54:39.684  3009  3017 D libEGL  : eglTerminate EGLDisplay = 0x7f90400e78
11-09 11:54:39.684  3009  3017 D libEGL  : eglTerminate EGLDisplay = 0x7f90400e78
11-09 11:54:39.684  5830  6628 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
11-09 11:54:39.684  3427  3427 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
11-09 11:54:39.684  3427  3557 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
11-09 11:54:39.684  3009  3019 I SurfaceFlinger: id=10 Removed MauncherAct (4/14)
11-09 11:54:39.694  3009  4492 I SurfaceFlinger: id=10 Removed MauncherAct (-2/14)
11-09 11:54:39.694  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7ffea28df8
11-09 11:54:39.704  3009  3017 I SurfaceFlinger: id=20 Removed VSBConnecti (8/13)
11-09 11:54:39.704  3009  3019 I SurfaceFlinger: id=20 Removed VSBConnecti (-2/13)
11-09 11:54:39.714  3009  3070 I SurfaceFlinger: id=19 Removed YUIInstallC (4/12)
11-09 11:54:39.714  3009  3017 I SurfaceFlinger: id=19 Removed YUIInstallC (-2/12)
11-09 11:54:39.714  4324  4324 V ActivityThread: updateVisibility : ActivityRecord{e576fb0 token=android.os.BinderProxy@3b26156 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
11-09 11:54:39.714  4324  4324 D Launcher: onTrimMemory. Level: 20
11-09 11:54:39.714  3009  3017 D libEGL  : eglTerminate EGLDisplay = 0x7f90400e78
11-09 11:54:39.724  3009  3017 I SurfaceFlinger: id=21 Removed VSBConnecti (5/11)
11-09 11:54:39.724  3009  4512 I SurfaceFlinger: id=21 Removed VSBConnecti (-2/11)
11-09 11:54:39.724  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7ffea28df8
11-09 11:54:39.724  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7ffea28dc8
11-09 11:54:39.804  3427  3427 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3427 (0x0)
11-09 11:54:39.804  3427  3427 I libsuspend: !@autosuspend_wakeup_count_disable
11-09 11:54:39.804  3427  3427 D PowerManagerService: mDisplayReady: false
11-09 11:54:39.804  3427  3427 I libsuspend: !@autosuspend_wakeup_count_disable done
11-09 11:54:39.804  3427  3583 D DisplayPowerController: animateScreenStateChange[0]: target=4
11-09 11:54:39.804  3427  3427 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
11-09 11:54:39.804  3427  3583 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
11-09 11:54:39.804  3427  3583 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-09 11:54:39.804  3427  3583 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-09 11:54:39.804  3427  3595 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
11-09 11:54:39.804  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f90683c00
11-09 11:54:39.804  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
11-09 11:54:39.814  3427  3583 D DisplayPowerController: animateScreenStateChange[0]: target=4
11-09 11:54:39.814  3427  3583 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
11-09 11:54:39.814  3427  3583 I libsuspend: !@autosuspend_wakeup_count_enable
11-09 11:54:39.814  3427  3583 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-09 11:54:39.814  3427  3583 I libsuspend: !@autosuspend_wakeup_count_enable done
11-09 11:54:39.814  3427  3583 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-09 11:54:39.814  3427  3583 D DisplayPowerController: animateScreenStateChange[0]: target=4
11-09 11:54:39.814  3427  3583 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
11-09 11:54:39.814  3427  3583 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-09 11:54:39.814  3427  3583 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-09 11:54:39.814  3427  3583 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
11-09 11:54:39.814  3427  3583 D PowerManagerService: mDisplayReady: true
11-09 11:54:39.814  3427  3583 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
11-09 11:54:39.814  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:39.994  5830  5830 I TrayVisibilityController: handleMessage : msg.what = 1
,11-09 11:54:39.994  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:40.034  3427  3982 I WindowManager: Screenshot max retries 4 of Token{7a9f344 ActivityRecord{8f80c57 u0 com.test.thalitest/.MainActivity t13}} appWin=Window{cc716b u0 d0 Starting com.test.thalitest} drawState=1
,11-09 11:54:40.034  5830  5840 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
11-09 11:54:40.034  3427  3579 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
11-09 11:54:40.034  3427  3579 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
11-09 11:54:40.034  3427  3427 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,11-09 11:54:40.044  3427  3858 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,11-09 11:54:40.044  3427  6114 D GameManagerService: identifyGamePackage. com.test.thalitest
,11-09 11:54:40.044  3427  6114 D GameManagerService: identifyGamePackage. com.test.thalitest
,11-09 11:54:40.044  5830  5830 I Utils   : isCurrentUser current = 0, ownerId = 0
,11-09 11:54:40.044  5830  5830 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
11-09 11:54:40.044  5830  5830 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
,11-09 11:54:40.054  3427  3427 I KnoxTimeoutHandler: SD activityfalse
,11-09 11:54:40.074  9617  9617 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,11-09 11:54:40.074  9617  9617 D RelationGraph: garbageCollect()
,11-09 11:54:40.074  3427  6114 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,11-09 11:54:40.074  9617  9617 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,11-09 11:54:40.084  3427  6114 D GameManagerService: identifyGamePackage. com.test.thalitest
11-09 11:54:40.084  3427  3982 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,11-09 11:54:40.084  9617  9617 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,11-09 11:54:40.084  3427  3579 V WindowStateAnimator: Finishing drawing window Window{cc716b u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
11-09 11:54:40.084  3427  3579 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,11-09 11:54:40.084  3427  3427 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
11-09 11:54:40.084  3427  6114 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
11-09 11:54:40.084  3427  3579 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{d419b94 u0 com.samsung.android.MtpApplication/.USBConnection t12} time:180889
11-09 11:54:40.084  3427  3579 D ActivityManager: mDVFSHelper.release()
11-09 11:54:40.084  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7ffea28cd8
11-09 11:54:40.094  3427  6114 D GameManagerService: identifyGamePackage. com.test.thalitest
11-09 11:54:40.094  3427  6114 D GameManagerService: identifyGamePackage. com.test.thalitest
,11-09 11:54:40.094  3427  3427 I KnoxTimeoutHandler: SD activityfalse
,11-09 11:54:40.104  9617  9617 D ResourcesManager: For user 0 new overlays fetched Null
,11-09 11:54:40.104  9617  9617 I InjectionManager: Inside getClassLibPath caller 
,11-09 11:54:40.124  9617  9617 D InjectionManager: InjectionManager
11-09 11:54:40.124  9617  9617 D InjectionManager: fillFeatureStoreMap com.test.thalitest
,11-09 11:54:40.124  9617  9617 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
11-09 11:54:40.124  9617  9617 I InjectionManager: featureStore :{}
,11-09 11:54:40.134  9617  9617 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
11-09 11:54:40.134  9617  9617 D RelationGraph: garbageCollect()
,11-09 11:54:40.134  9617  9617 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,11-09 11:54:40.164  9617  9617 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
,11-09 11:54:40.174  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:40.234  9617  9617 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
,11-09 11:54:40.234  9617  9617 D ResourcesManager: For user 0 new overlays fetched Null
,11-09 11:54:40.234  9617  9617 I InjectionManager: Inside getClassLibPath caller 
,11-09 11:54:40.244  9617  9617 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-09 11:54:40.294  3427  3881 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,11-09 11:54:40.294  9617  9617 I cr_LibraryLoader: Time to load native libraries: 34 ms (timestamps 1060-1094)
,11-09 11:54:40.294  9617  9617 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,11-09 11:54:40.344  3427  6115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,11-09 11:54:40.354  9617  9633 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,11-09 11:54:40.354  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:40.364  3427  3557 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c78ca9d u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{71337fd 9196:com.samsung.android.sm.provider/1000}
,11-09 11:54:40.374  9617  9617 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {180e05b}
11-09 11:54:40.374  9617  9617 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,11-09 11:54:40.374  3427  6115 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,11-09 11:54:40.394  9617  9617 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,11-09 11:54:40.394  3427  3881 I MdnieScenarioControlService: mGameModeLauncher : false
11-09 11:54:40.394  3427  3881 I MdnieScenarioControlService: setUIMode
,11-09 11:54:40.424  9617  9617 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,11-09 11:54:40.484  3427  6115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,11-09 11:54:40.504  3427  3557 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2c065e u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{71337fd 9196:com.samsung.android.sm.provider/1000}
,11-09 11:54:40.534  3427  3557 W ActivityManager: Activity pause timeout for ActivityRecord{8f80c57 u0 com.test.thalitest/.MainActivity t13}
,11-09 11:54:40.534  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:40.574  9617  9617 D libEGL  : eglInitialize EGLDisplay = 0xfff3e3ec
,11-09 11:54:40.644  3427  3855 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
11-09 11:54:40.644  3427  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,11-09 11:54:40.704  9617  9617 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,11-09 11:54:40.714  9617  9617 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-09 11:54:40.714  9617  9617 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
11-09 11:54:40.714  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:40.744  9617  9617 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,11-09 11:54:40.794  9617  9617 D Activity: performCreate Call Injection manager
,11-09 11:54:40.794  9617  9617 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,11-09 11:54:40.804  9617  9617 D SecWifiDisplayUtil: Metadata value : SecSettings2
,11-09 11:54:40.814  9617  9617 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6b66d96 I.E...... R.....ID 0,0-0,0}
,11-09 11:54:40.814  9617  9671 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-09 11:54:40.824  3427  3982 W WindowManager: Failed looking up window
11-09 11:54:40.824  3427  3982 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@902ba72 does not exist
11-09 11:54:40.824  3427  3982 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
11-09 11:54:40.824  3427  3982 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
11-09 11:54:40.824  3427  3982 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
11-09 11:54:40.824  3427  3982 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
11-09 11:54:40.824  3427  3982 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
11-09 11:54:40.824  3427  3982 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,11-09 11:54:40.824  3427  3855 D ISSUE_DEBUG: InputChannelName : 1244ec3 com.test.thalitest/com.test.thalitest.MainActivity
,11-09 11:54:40.834  3427  4434 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
11-09 11:54:40.834  3427  4434 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
11-09 11:54:40.834  3427  3427 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,11-09 11:54:40.834  3427  3427 I KnoxTimeoutHandler: Shared devices show user statefalse
,11-09 11:54:40.834  9617  9617 V ActivityThread: updateVisibility : ActivityRecord{7874504 token=android.os.BinderProxy@f66b099 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,11-09 11:54:40.844  9617  9633 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,11-09 11:54:40.864  9617  9617 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9617
11-09 11:54:40.864  3427  4434 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9617 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
11-09 11:54:40.864  3427  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
11-09 11:54:40.874  3427  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-09 11:54:40.874  3427  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
11-09 11:54:40.884  3427  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
11-09 11:54:40.884  3427  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
11-09 11:54:40.884  9617  9617 D SecWifiDisplayUtil: Metadata value : SecSettings2
11-09 11:54:40.894  3427  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
11-09 11:54:40.894  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-09 11:54:40.894  3427  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
11-09 11:54:40.904  3427  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
11-09 11:54:40.904  3427  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
11-09 11:54:40.904  3009  3009 I SurfaceFlinger: id=23 createSurf (1x1),1 flag=404, NainActivit
11-09 11:54:40.934  9617  9671 D libEGL  : eglInitialize EGLDisplay = 0xdc83f7c4
11-09 11:54:40.934  9617  9671 I OpenGLRenderer: Initialized EGL, version 1.4
11-09 11:54:40.944  9617  9671 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
11-09 11:54:40.944  3427  3489 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3427
11-09 11:54:40.944  3427  3489 I libsuspend: !@autosuspend_wakeup_count_disable
11-09 11:54:40.944  3427  3489 D PowerManagerService: mDisplayReady: false
11-09 11:54:40.944  3427  3489 I libsuspend: !@autosuspend_wakeup_count_disable done
11-09 11:54:40.944  3427  3583 D DisplayPowerController: animateScreenStateChange[0]: target=3
11-09 11:54:40.944  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f90683c00
11-09 11:54:40.944  3427  3489 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
11-09 11:54:40.944  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
11-09 11:54:40.944  3427  3583 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
11-09 11:54:40.944  3427  3583 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-09 11:54:40.944  3427  3583 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-09 11:54:40.944  3427  3595 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
11-09 11:54:40.944  3427  3579 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
11-09 11:54:40.944  3427  3579 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
11-09 11:54:40.964  3427  3583 D DisplayPowerController: animateScreenStateChange[0]: target=3
11-09 11:54:40.964  3427  3583 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
11-09 11:54:40.964  3427  3583 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-09 11:54:40.964  3427  3583 I libsuspend: !@autosuspend_wakeup_count_enable
11-09 11:54:40.964  3427  3583 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-09 11:54:40.964  3427  3583 I libsuspend: !@autosuspend_wakeup_count_enable done
11-09 11:54:40.964  3427  3583 D DisplayPowerController: animateScreenStateChange[0]: target=3
11-09 11:54:40.964  3427  3583 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
11-09 11:54:40.964  3427  3583 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-09 11:54:40.964  3427  3583 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-09 11:54:40.964  3427  3583 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
11-09 11:54:40.964  3427  3583 D PowerManagerService: mDisplayReady: true
11-09 11:54:40.974  3427  3583 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
11-09 11:54:40.974  5830  5830 E CocktailBarPositionManager: Window direction: 0
11-09 11:54:40.974  5830  5830 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
11-09 11:54:40.984  9617  9617 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
11-09 11:54:41.004  3427  3982 V WindowStateAnimator: Finishing drawing window Window{1244ec3 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
11-09 11:54:41.004  9617  9675 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-09 11:54:41.004  9617  9675 D libEGL  : eglInitialize EGLDisplay = 0xda0ac3f4
11-09 11:54:41.004  9617  9617 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
11-09 11:54:41.014  3427  4171 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3427
11-09 11:54:41.014  3427  3579 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
11-09 11:54:41.014  3427  3427 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
11-09 11:54:41.014  3427  3579 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +978ms (total +1s426ms)
11-09 11:54:41.014  3427  3579 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8f80c57 u0 com.test.thalitest/.MainActivity t13} time:181811
11-09 11:54:41.014  3427  3579 D ViewRootImpl: #3 mView = null
11-09 11:54:41.014  3427  3427 I KnoxTimeoutHandler: SD activityfalse
11-09 11:54:41.014  3009  3019 I SurfaceFlinger: id=22 Removed uhalitest (6/11)
11-09 11:54:41.014  3009  4492 I SurfaceFlinger: id=22 Removed uhalitest (-2/11)
11-09 11:54:41.014  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7ffea28df8
11-09 11:54:41.014  3427  3488 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3427
11-09 11:54:41.014  9617  9675 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
11-09 11:54:41.034  3427  4425 V WindowStateAnimator: Finishing drawing window Window{1244ec3 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
11-09 11:54:41.034  9617  9617 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f66b099 time:181832
11-09 11:54:41.074  9617  9617 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9617
11-09 11:54:41.074  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-09 11:54:41.164  3427  3427 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3427 (0x0)
11-09 11:54:41.164  3427  3427 D PowerManagerService: mDisplayReady: false
11-09 11:54:41.164  3427  3427 I libsuspend: !@autosuspend_wakeup_count_disable
11-09 11:54:41.164  3427  3583 D DisplayPowerController: animateScreenStateChange[0]: target=4
11-09 11:54:41.164  3427  3427 I libsuspend: !@autosuspend_wakeup_count_disable done
11-09 11:54:41.164  3427  3427 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
11-09 11:54:41.164  3427  3583 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
11-09 11:54:41.164  3427  3583 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-09 11:54:41.164  3427  3583 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-09 11:54:41.164  3427  3595 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
11-09 11:54:41.174  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f90683c00
11-09 11:54:41.174  3427  3579 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
11-09 11:54:41.174  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
11-09 11:54:41.174  3427  3579 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
11-09 11:54:41.184  3427  3583 D DisplayPowerController: animateScreenStateChange[0]: target=4
11-09 11:54:41.184  3427  3583 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
11-09 11:54:41.184  3427  3583 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-09 11:54:41.184  3427  3583 I libsuspend: !@autosuspend_wakeup_count_enable
11-09 11:54:41.184  3427  3583 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-09 11:54:41.184  3427  3583 I libsuspend: !@autosuspend_wakeup_count_enable done
11-09 11:54:41.184  3427  3583 D DisplayPowerController: animateScreenStateChange[0]: target=4
11-09 11:54:41.184  3427  3583 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
11-09 11:54:41.184  3427  3583 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-09 11:54:41.184  3427  3583 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-09 11:54:41.184  3427  3583 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
11-09 11:54:41.184  3427  3583 D PowerManagerService: mDisplayReady: true
11-09 11:54:41.184  3427  3583 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
11-09 11:54:41.194  5830  5830 E CocktailBarPositionManager: Window direction: 0
11-09 11:54:41.194  5830  5830 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
11-09 11:54:41.254  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-09 11:54:41.274  9617  9617 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
11-09 11:54:41.384  9617  9682 D jxcore_app_log: JniHelper::setJavaVM(0xf4eb4000), pthread_self() = -646973136
11-09 11:54:41.384  9617  9682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-09 11:54:41.384  9617  9682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-09 11:54:41.384  9617  9682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-09 11:54:41.384  9617  9682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-09 11:54:41.384  9617  9682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-09 11:54:41.384  9617  9682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f036846 added. We now have 1 listener(s)
11-09 11:54:41.394  9617  9682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
11-09 11:54:41.394  9617  9682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
11-09 11:54:41.394  9617  9682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-09 11:54:41.394  9617  9682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-09 11:54:41.394  9617  9682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2e495d added. We now have 1 listener(s)
11-09 11:54:41.394  9617  9682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-09 11:54:41.394  9617  9682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-09 11:54:41.394  9617  9682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-09 11:54:41.394  9617  9682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-09 11:54:41.394  9617  9682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-09 11:54:41.394  9617  9682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-09 11:54:41.404  9617  9682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 11:54:41.404  9617  9682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
11-09 11:54:41.404  9617  9682 D BluetoothAdapter: STATE_ON
11-09 11:54:41.414  9617  9682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-09 11:54:41.414  9617  9682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 11:54:41.414  9617  9682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:54:41.414  9617  9682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:54:41.414  9617  9682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:54:41.414  9617  9682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:54:41.414  9617  9682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:54:41.414  9617  9682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:54:41.414  9617  9682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 11:54:41.414  9617  9682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-09 11:54:41.414  9617  9682 D io.jxcore.node.ConnectivityMonitor: start: OK
11-09 11:54:41.414  9617  9682 I io.jxcore.node.LifeCycleMonitor: start: OK
11-09 11:54:41.414  9617  9617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:54:41.414  9617  9617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 11:54:41.434  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-09 11:54:41.444  9617  9617 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
11-09 11:54:41.534  4025  4025 D Recents : onTaskStackChanged
11-09 11:54:41.534  4025  4025 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
11-09 11:54:41.554  4025  4025 D ResourcesManager: For user 0 new overlays fetched Null
11-09 11:54:41.614  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:41.794  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:41.884  3427  6114 D SSRM:n  : SIOP:: AP = 280, PST = 290 (W:10), CP = 233, CUR = 149, LCD = 1
,11-09 11:54:41.964  9617  9683 W jxcore-log: Initializing JXcore engine
11-09 11:54:41.964  9617  9683 W jxcore-log: JXcore engine is ready
,11-09 11:54:41.974  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:41.994  5042  5042 E audit   : type=1400 msg=audit(1478688881.984:264): avc:  denied  { ioctl } for  pid=9683 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1340 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-09 11:54:41.994  5042  5042 E audit   :  SEPF_SECMOBILE_6.0.1_0013
11-09 11:54:41.994  5042  5042 E audit   : type=1300 msg=audit(1478688881.984:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d828a3c8 items=0 ppid=3180 pid=9683 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
11-09 11:54:41.994  5042  5042 E audit   : type=1327 msg=audit(1478688881.984:264): proctitle="com.test.thalitest"
11-09 11:54:41.994  5042  5042 E audit   : type=1320 msg=audit(1478688881.984:264): 
11-09 11:54:41.994  5042  5042 E audit   : type=1400 msg=audit(1478688881.984:265): avc:  denied  { ioctl } for  pid=9683 comm="Thread-160" path="socket:[38119]" dev="sockfs" ino=38119 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-09 11:54:41.994  5042  5042 E audit   :  SEPF_SECMOBILE_6.0.1_0013
11-09 11:54:41.994  5042  5042 E audit   : type=1300 msg=audit(1478688881.984:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d828a3c8 items=0 ppid=3180 pid=9683 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
11-09 11:54:41.994  5042  5042 E audit   : type=1327 msg=audit(1478688881.984:265): proctitle="com.test.thalitest"
11-09 11:54:41.994  5042  5042 E audit   : type=1320 msg=audit(1478688881.984:265): 
,11-09 11:54:41.994  9617  9683 W jxcore-log: Starting JXcore engine
,11-09 11:54:42.034  9617  9683 W jxcore-log: Platform android
11-09 11:54:42.034  9617  9683 W jxcore-log: 
11-09 11:54:42.034  9617  9683 W jxcore-log: Process ARCH arm
11-09 11:54:42.034  9617  9683 W jxcore-log: 
,11-09 11:54:42.134  9617  9683 I jxcore-log: JXcore Cordova bridge is ready!
11-09 11:54:42.134  9617  9683 I jxcore-log: 
11-09 11:54:42.134  9617  9683 W jxcore-log: JXcore engine is started
,11-09 11:54:42.144  9617  9682 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-09 11:54:42.144  9617  9617 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-09 11:54:42.154  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:42.334  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:42.514  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:42.594  3427  3908 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/13_task.xml.bak
,11-09 11:54:42.604  3427  4426 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
11-09 11:54:42.604  3427  4426 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
11-09 11:54:42.604  3427  4426 D BatteryService: online:4, current avg:120, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-223
11-09 11:54:42.604  3427  4426 D BatteryService: stay LED for fully charged
11-09 11:54:42.604  3427  3427 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,11-09 11:54:42.604  3427  3427 I MotionRecognitionService: Plugged
,11-09 11:54:42.604  3427  3427 D MotionRecognitionService:   cableConnection= 1
11-09 11:54:42.604  3427  3427 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
11-09 11:54:42.604  3427  3427 D MotionRecognitionService: skip setTransmitPower. 
11-09 11:54:42.614  3427  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
11-09 11:54:42.614  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
11-09 11:54:42.614  3939  3939 D KeyguardUpdateMonitor: handleBatteryUpdate
11-09 11:54:42.614  3939  3939 D PowerUI : priorPlugType = 2 mPlugType =  2
,11-09 11:54:42.624  5073  5073 D CommonServiceConfiguration: getStringValueSetting
,11-09 11:54:42.624  5073  5073 D BatteryMonitor: new battery level: 100
,11-09 11:54:42.624  5033  5033 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,11-09 11:54:42.624  5033  5429 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,11-09 11:54:42.634  4759  4759 D BatteryController: saveBatteryData : level[100], status[5]
,11-09 11:54:42.634  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,11-09 11:54:42.634  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,11-09 11:54:42.704  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:42.874  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:43.044  3427  6114 D GameManagerService: identifyGamePackage. com.test.thalitest
,11-09 11:54:43.054  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:43.234  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:43.414  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:43.594  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:43.774  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:43.954  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:44.134  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:44.314  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:44.494  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:44.674  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:44.854  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:45.034  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:45.214  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:45.394  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:45.574  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:45.754  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:45.934  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:46.104  3427  6114 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,11-09 11:54:46.114  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:46.294  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:46.474  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:46.654  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:46.834  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:47.014  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:47.194  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:47.374  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:47.554  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:47.734  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:47.914  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:48.094  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:48.274  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:48.344  9617  9683 I jxcore-log: 2016-11-09 10:54:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-09 11:54:48.344  9617  9683 I jxcore-log: 
,11-09 11:54:48.344  9617  9683 I jxcore-log: 2016-11-09 10:54:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-09 11:54:48.344  9617  9683 I jxcore-log: 
,11-09 11:54:48.354  9617  9683 D BluetoothAdapter: STATE_ON
,11-09 11:54:48.354  9617  9683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 11:54:48.354  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:54:48.354  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:54:48.354  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:54:48.354  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:54:48.354  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:54:48.354  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:54:48.354  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 11:54:48.364  9617  9683 D BluetoothAdapter: STATE_ON
,11-09 11:54:48.364  9617  9683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 11:54:48.364  9617  9683 I jxcore-log: 2016-11-09 10:54:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-09 11:54:48.364  9617  9683 I jxcore-log: 
11-09 11:54:48.364  9617  9683 I jxcore-log: 2016-11-09 10:54:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-09 11:54:48.364  9617  9683 I jxcore-log: 
,11-09 11:54:48.454  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:48.524  9617  9683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-09 11:54:48.524  9617  9683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ec1e63 added. We now have 2 listener(s)
11-09 11:54:48.524  9617  9683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
11-09 11:54:48.524  9617  9683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-09 11:54:48.524  9617  9683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-09 11:54:48.524  9617  9683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-09 11:54:48.524  9617  9683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d4a60 added. We now have 2 listener(s)
,11-09 11:54:48.524  9617  9683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-09 11:54:48.524  9617  9683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-09 11:54:48.534  9617  9683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-09 11:54:48.534  9617  9683 D BluetoothAdapter: STATE_ON
,11-09 11:54:48.544  9617  9683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 11:54:48.544  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 11:54:48.544  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 11:54:48.544  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 11:54:48.544  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 11:54:48.544  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 11:54:48.544  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 11:54:48.544  9617  9683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 11:54:48.544  9617  9683 D BluetoothAdapter: STATE_ON
,11-09 11:54:48.554  9617  9683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 11:54:48.554  9617  9683 D io.jxcore.node.ConnectivityMonitor: start: OK
11-09 11:54:48.554  9617  9683 D ExecuteNativeTests: Running unit tests
11-09 11:54:48.554  9617  9683 D BluetoothAdapter: enable()
,11-09 11:54:48.554  9617  9683 D BluetoothAdapter: enable(): BT is already enabled..!
,11-09 11:54:48.564  9617  9617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:54:48.564  9617  9617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 11:54:48.574  3427  3557 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ca66eb3 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6264f34 5062:com.samsung.android.providers.context/u0a9}
,11-09 11:54:48.574  9617  9683 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,11-09 11:54:48.574  3427  4444 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,11-09 11:54:48.584  3427  4444 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,11-09 11:54:48.584  3427  4444 D WifiService: setWifiEnabled: true pid=9617, uid=10177
,11-09 11:54:48.594  3427  4444 W ActivityManager: Permission Denial: getCurrentUser() from pid=9617, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
,11-09 11:54:48.604  3427  4444 W WifiService: Failed getting userId using ActivityManagerNative
11-09 11:54:48.604  3427  4444 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9617, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
11-09 11:54:48.604  3427  4444 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28247)
11-09 11:54:48.604  3427  4444 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
11-09 11:54:48.604  3427  4444 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
11-09 11:54:48.604  3427  4444 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
11-09 11:54:48.604  3427  4444 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,11-09 11:54:48.604  3427  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
11-09 11:54:48.604  3427  4444 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
11-09 11:54:48.604  3427  4444 D SettingsProvider: isChangeAllowed() : name = wifi_on
11-09 11:54:48.604  3427  3863 D WifiStateMachine: setFccChannel: channel = 0
,11-09 11:54:48.604  3427  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
11-09 11:54:48.604  3427  3860 D WifiBigDataLog: init : 
,11-09 11:54:48.604  3427  3863 D WifiController: [FCC]setFccChannel() is called !!!
11-09 11:54:48.604  3427  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,11-09 11:54:48.604  3427  3860 D WifiStateMachine: setFccChannelNative: channel = 0
,11-09 11:54:48.604  3427  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
,11-09 11:54:48.614  3427  3557 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a09dc70 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6264f34 5062:com.samsung.android.providers.context/u0a9}
,11-09 11:54:48.634  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:48.814  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:48.974  3427  6149 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,11-09 11:54:48.994  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:49.174  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:49.364  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:49.544  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:49.644  3427  3602 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,11-09 11:54:49.664  3427  3602 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,11-09 11:54:49.724  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:49.904  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:50.084  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:50.254  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:50.434  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:50.614  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:50.804  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:50.984  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:51.154  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:51.344  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:51.524  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:51.704  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:51.884  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:51.904  3427  6114 D SSRM:n  : SIOP:: AP = 320, PST = 282 (W:6), CP = 243, CUR = 120, LCD = 1
,11-09 11:54:52.054  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:52.234  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:52.414  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:52.584  3427  4135 E Watchdog: !@Sync 6 [11-09 11:54:52.593]
,11-09 11:54:52.604  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:52.784  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:52.964  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:53.144  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:53.324  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:53.504  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:53.684  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:53.864  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:53.924  4411  4464 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
11-09 11:54:53.924  4411  4464 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,11-09 11:54:54.044  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:54.224  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:54.404  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:54.584  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:54.764  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:54.944  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:55.124  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:55.304  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:55.484  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:55.664  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:55.844  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:56.024  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:56.204  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:56.384  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:56.564  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:56.744  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:56.924  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:57.104  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:57.284  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-09 11:54:57.464  3427  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
