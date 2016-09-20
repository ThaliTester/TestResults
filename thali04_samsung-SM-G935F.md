#### Test 85615572478a184_thali04_samsung-SM-G935F Logs


```
--------- beginning of main
09-20 13:50:36.951  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:37.131  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:50:37.311  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:50:37.481  9791  9791 I FIPS_bssl: FIPS approved mode (1) | 9791 | app_process
09-20 13:50:37.491  9791  9791 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-20 13:50:37.491  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:50:37.491  9791  9791 D AndroidRuntime: CheckJNI is OFF
09-20 13:50:37.491  9791  9791 D AndroidRuntime: readGMSProperty: start
09-20 13:50:37.491  9791  9791 D AndroidRuntime: readGMSProperty: already setted!!
09-20 13:50:37.491  9791  9791 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-20 13:50:37.491  9791  9791 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-20 13:50:37.491  9791  9791 D AndroidRuntime: readGMSProperty: end
09-20 13:50:37.491  9791  9791 D AndroidRuntime: addProductProperty: start
09-20 13:50:37.511  9791  9791 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-20 13:50:37.531  9791  9791 I Radio-JNI: register_android_hardware_Radio DONE
09-20 13:50:37.541  9791  9791 E AffinityControl: AffinityControl: registerfunction enter
09-20 13:50:37.541  9791  9791 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-20 13:50:37.571  3433  4417 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-20 13:50:37.571  3433  4417 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-20 13:50:37.591  3433  4417 D ResourcesManager: For user 0 new overlays fetched Null
09-20 13:50:37.591  3433  4417 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:50:37.591  3433  4417 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-20 13:50:37.601  3433  4417 D ActivityManager: mDVFSHelper.acquire()
09-20 13:50:37.611  3433  4417 V WindowManager: addAppToken: AppWindowToken{d08a59007 token=Token{80ee646 ActivityRecord{450c221 u0 com.test.thalitest/.MainActivity t75}}} to stack=2 task=75 at 0
09-20 13:50:37.621  3433  3571 I InjectionManager: Inside getClassLibPath caller 
09-20 13:50:37.631  3433  3571 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-20 13:50:37.631  3433  3571 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{1f678ff V.E...... R.....ID 0,0-0,0}
09-20 13:50:37.631  9800  9800 E Zygote  : v2
09-20 13:50:37.631  9800  9800 I libpersona: KNOX_SDCARD checking this for 10177
09-20 13:50:37.631  9800  9800 I libpersona: KNOX_SDCARD not a persona
09-20 13:50:37.631  9800  9800 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-20 13:50:37.631  3433  3571 W WindowManager: Failed looking up window
09-20 13:50:37.631  3433  3571 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@30966cc does not exist
09-20 13:50:37.631  3433  3571 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 13:50:37.631  3433  3571 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-20 13:50:37.641  3433  3571 D ISSUE_DEBUG: InputChannelName : 61b1d15 Starting com.test.thalitest
09-20 13:50:37.641  9800  9800 E Zygote  : accessInfo : 0
09-20 13:50:37.641  9800  9800 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-20 13:50:37.641  3433  4417 I ActivityManager: Start proc 9800:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-20 13:50:37.641  3433  4417 D InputDispatcher: Focused application set to: xxxx
09-20 13:50:37.641  9791  9791 D AndroidRuntime: Shutting down VM
09-20 13:50:37.641  3433  3857 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-20 13:50:37.651  3009  3009 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-20 13:50:37.671  9800  9800 D TimaKeyStoreProvider: TimaSignature is unavailable
09-20 13:50:37.671  9800  9800 D ActivityThread: Added TimaKeyStore provider
09-20 13:50:37.671  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:50:37.681  6540  6540 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 13:50:37.691  3433  4188 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3433
09-20 13:50:37.691  3433  4188 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 13:50:37.691  3433  4188 D PowerManagerService: mDisplayReady: false
09-20 13:50:37.691  3433  4188 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 13:50:37.691  3433  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:50:37.691  6540  6540 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 13:50:37.691  3433  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:50:37.691  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7faee03c00
09-20 13:50:37.691  3433  4188 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 13:50:37.691  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-20 13:50:37.691  3433  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:50:37.691  3433  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:50:37.691  3433  3585 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-20 13:50:37.691  3433  4151 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3433
09-20 13:50:37.701  3433  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:50:37.701  3433  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:50:37.701  3433  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:50:37.701  3433  3574 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 13:50:37.701  3433  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:50:37.701  3433  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 13:50:37.701  3433  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:50:37.701  3433  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:50:37.701  3433  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:50:37.701  3433  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:50:37.701  3433  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 13:50:37.701  3433  3574 D PowerManagerService: mDisplayReady: true
09-20 13:50:37.701  3433  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-20 13:50:37.711  3433  4761 D ActivityManager:  Launching com.test.thalitest, updated priority
09-20 13:50:37.711  3433  3972 V WindowStateAnimator: Finishing drawing window Window{8b4d37 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-20 13:50:37.731  3009  3074 D libEGL  : eglTerminate EGLDisplay = 0x7fa853ee78
09-20 13:50:37.731  3009  3074 D libEGL  : eglTerminate EGLDisplay = 0x7fa853ee78
09-20 13:50:37.731  3433  3433 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-20 13:50:37.731  6204  6214 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-20 13:50:37.741  3433  3548 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-20 13:50:37.741  3009  4714 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-20 13:50:37.741  3009  3020 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-20 13:50:37.761  4312  4312 V ActivityThread: updateVisibility : ActivityRecord{6e44459 token=android.os.BinderProxy@357d0b4 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-20 13:50:37.761  4312  4312 D Launcher: onTrimMemory. Level: 20
09-20 13:50:37.761  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc1ce44f8
09-20 13:50:37.761  3433  4981 V WindowStateAnimator: Finishing drawing window Window{d6b0fd1 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-20 13:50:37.761  6540  6540 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 13:50:37.761  6540  6540 V ActivityThread: updateVisibility : ActivityRecord{2771096 token=android.os.BinderProxy@cf06dab {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-20 13:50:37.761  6540  6540 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 13:50:37.761  3009  3018 I SurfaceFlinger: id=18 Removed VSBConnecti (7/12)
09-20 13:50:37.761  3009  4714 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/12)
09-20 13:50:37.771  3009  4479 D libEGL  : eglTerminate EGLDisplay = 0x7fa75fee78
09-20 13:50:37.771  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc1ce44f8
09-20 13:50:37.771  3009  4714 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
09-20 13:50:37.771  3009  3020 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
09-20 13:50:37.801  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc1ce44f8
09-20 13:50:37.841  3433  3433 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3433 (0x0)
09-20 13:50:37.841  3433  3433 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3433 (0x0)
09-20 13:50:37.851  3433  3433 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 13:50:37.851  3433  3433 D PowerManagerService: mDisplayReady: false
09-20 13:50:37.851  3433  3433 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 13:50:37.851  3433  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:50:37.851  3433  3433 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 13:50:37.851  3433  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:50:37.851  3433  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:50:37.851  3433  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:50:37.851  3433  3585 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-20 13:50:37.851  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7faee03c00
09-20 13:50:37.851  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-20 13:50:37.851  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:50:37.851  3433  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:50:37.851  3433  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:50:37.851  3433  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:50:37.851  3433  3574 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 13:50:37.851  3433  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:50:37.851  3433  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 13:50:37.851  3433  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:50:37.851  3433  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:50:37.851  3433  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:50:37.851  3433  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:50:37.851  3433  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 13:50:37.851  3433  3574 D PowerManagerService: mDisplayReady: true
09-20 13:50:37.851  3433  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 13:50:38.031  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:50:38.031  6204  6204 I TrayVisibilityController: handleMessage : msg.what = 1
09-20 13:50:38.061  3433  4761 I WindowManager: Screenshot max retries 4 of Token{80ee646 ActivityRecord{450c221 u0 com.test.thalitest/.MainActivity t75}} appWin=Window{61b1d15 u0 d0 Starting com.test.thalitest} drawState=1
09-20 13:50:38.061  6204  6266 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-20 13:50:38.061  3433  3571 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:50:38.061  3433  3433 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:50:38.061  3433  3571 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-20 13:50:38.071  6204  6204 I Utils   : isCurrentUser current = 0, ownerId = 0
09-20 13:50:38.071  6204  6204 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-20 13:50:38.071  6204  6204 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-20 13:50:38.081  3433  6462 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:50:38.081  3433  3857 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-20 13:50:38.081  3433  6462 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:50:38.081  3433  3433 I KnoxTimeoutHandler: SD activityfalse
09-20 13:50:38.101  3433  6462 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 13:50:38.101  3433  6462 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:50:38.111  9800  9800 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-20 13:50:38.111  9800  9800 D RelationGraph: garbageCollect()
09-20 13:50:38.111  3433  6462 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 13:50:38.111  9800  9800 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 13:50:38.111  3433  6462 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:50:38.111  3433  6462 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:50:38.111  3433  4151 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-20 13:50:38.121  9800  9800 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-20 13:50:38.121  3433  3571 V WindowStateAnimator: Finishing drawing window Window{61b1d15 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-20 13:50:38.121  3433  3571 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:50:38.121  3433  3433 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:50:38.121  3433  3571 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b495de3 u0 com.samsung.android.MtpApplication/.USBConnection t74} time:188594
09-20 13:50:38.121  3433  3571 D ActivityManager: mDVFSHelper.release()
09-20 13:50:38.121  3433  3433 I KnoxTimeoutHandler: SD activityfalse
09-20 13:50:38.131  9800  9800 D ResourcesManager: For user 0 new overlays fetched Null
09-20 13:50:38.131  9800  9800 I InjectionManager: Inside getClassLibPath caller 
09-20 13:50:38.141  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fc1ce43d8
09-20 13:50:38.151  9800  9800 D InjectionManager: InjectionManager
09-20 13:50:38.151  9800  9800 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-20 13:50:38.151  9800  9800 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-20 13:50:38.151  9800  9800 I InjectionManager: featureStore :{}
09-20 13:50:38.151  9800  9800 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 13:50:38.151  9800  9800 D RelationGraph: garbageCollect()
09-20 13:50:38.161  9800  9800 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 13:50:38.191  9800  9800 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-20 13:50:38.211  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:50:38.261  9800  9800 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-20 13:50:38.271  9800  9800 D ResourcesManager: For user 0 new overlays fetched Null
09-20 13:50:38.271  9800  9800 I InjectionManager: Inside getClassLibPath caller 
09-20 13:50:38.281  9800  9800 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-20 13:50:38.331  3433  3882 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-20 13:50:38.341  9800  9800 I cr_LibraryLoader: Time to load native libraries: 33 ms (timestamps 8783-8816)
09-20 13:50:38.341  9800  9800 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-20 13:50:38.391  9800  9816 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-20 13:50:38.391  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:50:38.411  9800  9800 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {810b740}
09-20 13:50:38.411  9800  9800 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-20 13:50:38.431  3433  3882 I MdnieScenarioControlService: mGameModeLauncher : false
09-20 13:50:38.431  3433  3882 I MdnieScenarioControlService: setUIMode
09-20 13:50:38.431  9800  9800 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-20 13:50:38.461  9800  9800 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-20 13:50:38.561  3433  3548 W ActivityManager: Activity pause timeout for ActivityRecord{450c221 u0 com.test.thalitest/.MainActivity t75}
09-20 13:50:38.571  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:50:38.601  9800  9800 D libEGL  : eglInitialize EGLDisplay = 0xffc4855c
09-20 13:50:38.691  3433  4151 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
09-20 13:50:38.691  3433  4151 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-20 13:50:38.751  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:38.771  9800  9800 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-20 13:50:38.791  9800  9800 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-20 13:50:38.801  9800  9800 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-20 13:50:38.851  9800  9800 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-20 13:50:38.911  9800  9800 D Activity: performCreate Call Injection manager
,09-20 13:50:38.911  9800  9800 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-20 13:50:38.921  9800  9800 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-20 13:50:38.931  9800  9800 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{e9df51e I.E...... R.....ID 0,0-0,0}
,09-20 13:50:38.931  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:38.931  9800  9853 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-20 13:50:38.941  3433  3972 W WindowManager: Failed looking up window
09-20 13:50:38.941  3433  3972 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@4983b2c does not exist
09-20 13:50:38.941  3433  3972 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 13:50:38.941  3433  3972 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 13:50:38.941  3433  3972 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 13:50:38.941  3433  3972 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-20 13:50:38.941  3433  3972 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-20 13:50:38.941  3433  3972 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-20 13:50:38.941  3433  4980 D ISSUE_DEBUG: InputChannelName : 6e0c9f5 com.test.thalitest/com.test.thalitest.MainActivity
,09-20 13:50:38.951  3433  4417 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-20 13:50:38.951  3433  4417 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 13:50:38.951  3433  3433 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-20 13:50:38.951  3433  3433 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-20 13:50:38.951  9800  9800 V ActivityThread: updateVisibility : ActivityRecord{115abcc token=android.os.BinderProxy@bb78b27 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-20 13:50:38.961  9800  9816 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-20 13:50:38.991  9800  9800 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9800
,09-20 13:50:38.991  3433  4417 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9800 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 13:50:38.991  3433  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-20 13:50:38.991  3433  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-20 13:50:39.001  3433  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-20 13:50:39.001  3433  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-20 13:50:39.011  3433  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 13:50:39.011  9800  9800 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-20 13:50:39.011  3433  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 13:50:39.011  3433  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-20 13:50:39.021  3433  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 13:50:39.031  3009  3009 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,09-20 13:50:39.041  9800  9853 D libEGL  : eglInitialize EGLDisplay = 0xdc6ff7c4
09-20 13:50:39.041  9800  9853 I OpenGLRenderer: Initialized EGL, version 1.4
,09-20 13:50:39.051  9800  9853 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-20 13:50:39.051  3433  3782 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3433
09-20 13:50:39.051  3433  3782 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 13:50:39.051  3433  3782 D PowerManagerService: mDisplayReady: false
09-20 13:50:39.051  3433  3782 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 13:50:39.051  3433  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:50:39.061  3433  3782 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 13:50:39.061  3433  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:50:39.061  3433  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:50:39.061  3433  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:50:39.061  3433  3585 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-20 13:50:39.061  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7faee03c00
09-20 13:50:39.061  3433  3571 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-20 13:50:39.061  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-20 13:50:39.061  3433  3571 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-20 13:50:39.061  3009  3055 W SurfaceFlinger: Ignoring duplicate VSYNC event from HWC (t=189534282594)
,09-20 13:50:39.071  3433  6464 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-20 13:50:39.081  3433  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-20 13:50:39.081  3433  3574 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 13:50:39.081  3433  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:50:39.081  3433  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
,09-20 13:50:39.081  3433  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:50:39.081  3433  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:50:39.081  3433  3574 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:50:39.081  3433  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:50:39.081  3433  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-20 13:50:39.081  3433  3574 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:50:39.081  3433  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 13:50:39.081  3433  3574 D PowerManagerService: mDisplayReady: true
09-20 13:50:39.081  3433  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 13:50:39.081  6204  6204 E CocktailBarPositionManager: Window direction: 0
09-20 13:50:39.081  6204  6204 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 13:50:39.101  9800  9800 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-20 13:50:39.111  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:39.111  3433  4505 V WindowStateAnimator: Finishing drawing window Window{6e0c9f5 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-20 13:50:39.111  9800  9800 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-20 13:50:39.121  3433  3571 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-20 13:50:39.121  3433  4761 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3433
09-20 13:50:39.121  3433  3433 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 13:50:39.121  3433  3571 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s57ms (total +1s511ms)
,09-20 13:50:39.121  3433  3571 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{450c221 u0 com.test.thalitest/.MainActivity t75} time:189595
09-20 13:50:39.121  3433  3571 D ViewRootImpl: #3 mView = null
,09-20 13:50:39.121  3009  4479 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
,09-20 13:50:39.121  3433  3433 I KnoxTimeoutHandler: SD activityfalse
,09-20 13:50:39.121  3009  3018 I SurfaceFlinger: id=20 Removed uhalitest (-2/11)
,09-20 13:50:39.131  3433  4981 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3433
,09-20 13:50:39.131  9800  9857 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-20 13:50:39.131  9800  9857 D libEGL  : eglInitialize EGLDisplay = 0xd9fe23f4
,09-20 13:50:39.131  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fc1ce44f8
,09-20 13:50:39.141  3433  4417 V WindowStateAnimator: Finishing drawing window Window{6e0c9f5 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-20 13:50:39.141  9800  9800 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@bb78b27 time:189618
,09-20 13:50:39.161  9800  9857 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-20 13:50:39.211  9800  9800 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9800
,09-20 13:50:39.281  3433  3433 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3433 (0x0)
09-20 13:50:39.281  3433  3433 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 13:50:39.281  3433  3433 D PowerManagerService: mDisplayReady: false
09-20 13:50:39.281  3433  3433 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 13:50:39.281  3433  3433 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 13:50:39.281  3433  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:50:39.281  3433  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:50:39.281  3433  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:50:39.281  3433  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:50:39.281  3433  3585 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-20 13:50:39.281  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7faee03c00
09-20 13:50:39.281  3433  3571 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-20 13:50:39.281  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-20 13:50:39.281  3433  3571 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-20 13:50:39.291  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:50:39.291  3433  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:50:39.291  3433  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:50:39.291  3433  3574 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 13:50:39.291  3433  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:50:39.291  3433  3574 I libsuspend: !@autosuspend_wakeup_count_enable done
,09-20 13:50:39.291  3433  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:50:39.291  3433  3574 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:50:39.291  3433  3574 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:50:39.291  3433  3574 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:50:39.291  3433  3574 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-20 13:50:39.291  3433  3574 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 13:50:39.291  3433  3574 D PowerManagerService: mDisplayReady: true
09-20 13:50:39.291  3433  3574 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 13:50:39.301  6204  6204 E CocktailBarPositionManager: Window direction: 0
,09-20 13:50:39.301  6204  6204 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 13:50:39.441  9800  9800 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-20 13:50:39.471  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:39.541  9800  9864 D jxcore_app_log: JniHelper::setJavaVM(0xf4df4000), pthread_self() = -656410320
,09-20 13:50:39.541  9800  9864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-20 13:50:39.541  9800  9864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-20 13:50:39.541  9800  9864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-20 13:50:39.541  9800  9864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-20 13:50:39.541  9800  9864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-20 13:50:39.541  9800  9864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53fe1ce added. We now have 1 listener(s)
,09-20 13:50:39.541  9800  9864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
,09-20 13:50:39.541  9800  9864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
,09-20 13:50:39.541  9800  9864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-20 13:50:39.541  9800  9864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-20 13:50:39.551  9800  9864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8981685 added. We now have 1 listener(s)
09-20 13:50:39.551  9800  9864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-20 13:50:39.551  9800  9864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-20 13:50:39.551  9800  9864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-20 13:50:39.551  9800  9864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-20 13:50:39.551  9800  9864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-20 13:50:39.551  9800  9864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-20 13:50:39.551  9800  9864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 13:50:39.551  9800  9864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
09-20 13:50:39.561  9800  9864 D BluetoothAdapter: STATE_ON
09-20 13:50:39.561  4022  4022 D Recents : onTaskStackChanged
09-20 13:50:39.571  9800  9864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-20 13:50:39.571  9800  9864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 13:50:39.571  9800  9864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 13:50:39.571  9800  9864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 13:50:39.571  9800  9864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 13:50:39.571  9800  9864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 13:50:39.571  9800  9864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 13:50:39.571  9800  9864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 13:50:39.571  9800  9864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-20 13:50:39.571  9800  9864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-20 13:50:39.571  9800  9864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-20 13:50:39.571  9800  9864 I io.jxcore.node.LifeCycleMonitor: start: OK
09-20 13:50:39.571  9800  9800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-20 13:50:39.581  4022  4022 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
09-20 13:50:39.581  9800  9800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 13:50:39.591  4022  4022 D ResourcesManager: For user 0 new overlays fetched Null
09-20 13:50:39.601  9800  9800 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-20 13:50:39.651  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:39.831  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:39.941  9800  9865 W jxcore-log: Initializing JXcore engine
09-20 13:50:39.941  9800  9865 W jxcore-log: JXcore engine is ready
,09-20 13:50:39.961  5038  5038 E audit   : type=1400 msg=audit(1474372239.961:262): avc:  denied  { ioctl } for  pid=9865 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2225 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-20 13:50:39.961  5038  5038 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-20 13:50:39.961  5038  5038 E audit   : type=1300 msg=audit(1474372239.961:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d82053c8 items=0 ppid=3183 pid=9865 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-20 13:50:39.961  5038  5038 E audit   : type=1327 msg=audit(1474372239.961:262): proctitle="com.test.thalitest"
09-20 13:50:39.961  5038  5038 E audit   : type=1320 msg=audit(1474372239.961:262): 
09-20 13:50:39.961  5038  5038 E audit   : type=1400 msg=audit(1474372239.961:263): avc:  denied  { ioctl } for  pid=9865 comm="Thread-160" path="socket:[14250]" dev="sockfs" ino=14250 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-20 13:50:39.961  5038  5038 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-20 13:50:39.961  5038  5038 E audit   : type=1300 msg=audit(1474372239.961:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d82053c8 items=0 ppid=3183 pid=9865 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-20 13:50:39.961  5038  5038 E audit   : type=1327 msg=audit(1474372239.961:263): proctitle="com.test.thalitest"
09-20 13:50:39.961  5038  5038 E audit   : type=1320 msg=audit(1474372239.961:263): 
,09-20 13:50:39.961  9800  9865 W jxcore-log: Starting JXcore engine
,09-20 13:50:40.001  9800  9865 W jxcore-log: Platform android
09-20 13:50:40.001  9800  9865 W jxcore-log: 
09-20 13:50:40.001  9800  9865 W jxcore-log: Process ARCH arm
09-20 13:50:40.001  9800  9865 W jxcore-log: 
,09-20 13:50:40.011  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:40.071  9800  9865 I jxcore-log: JXcore Cordova bridge is ready!
09-20 13:50:40.071  9800  9865 I jxcore-log: 
09-20 13:50:40.071  9800  9865 W jxcore-log: JXcore engine is started
,09-20 13:50:40.081  9800  9864 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-20 13:50:40.081  9800  9800 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-20 13:50:40.191  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:40.371  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:40.551  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:40.611  3433  3908 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/75_task.xml.bak
,09-20 13:50:40.731  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:40.911  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:41.091  3433  6462 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-20 13:50:41.091  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:41.181  3433  6498 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-20 13:50:41.271  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:41.451  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:41.631  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:41.811  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:41.991  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:42.171  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:42.351  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:42.531  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:42.711  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:42.891  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:42.941  3433  4153 E Watchdog: !@Sync 6 [09-20 13:50:42.951]
,09-20 13:50:43.041  3433  6462 D SSRM:n  : SIOP:: AP = 330, PST = 294 (W:6), CP = 242, CUR = 151, LCD = 1
,09-20 13:50:43.071  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:43.251  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:43.431  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:43.611  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:43.791  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:43.971  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:44.131  3433  6462 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-20 13:50:44.151  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:44.311  4407  4460 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-20 13:50:44.311  4407  4460 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-20 13:50:44.331  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:44.511  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:44.691  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:44.871  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:45.051  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:45.231  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:45.411  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:45.591  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:45.771  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:45.951  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:46.081  8502  8529 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,09-20 13:50:46.101  9800  9865 I jxcore-log: 2016-09-20 11:50:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-20 13:50:46.101  9800  9865 I jxcore-log: 
,09-20 13:50:46.101  9800  9865 I jxcore-log: 2016-09-20 11:50:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-20 13:50:46.101  9800  9865 I jxcore-log: 
,09-20 13:50:46.111  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.121  9800  9865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 13:50:46.121  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 13:50:46.121  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 13:50:46.121  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 13:50:46.121  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 13:50:46.121  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 13:50:46.121  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 13:50:46.121  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 13:50:46.121  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.121  9800  9865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-20 13:50:46.121  9800  9865 I jxcore-log: 2016-09-20 11:50:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-20 13:50:46.121  9800  9865 I jxcore-log: 
,09-20 13:50:46.131  9800  9865 I jxcore-log: 2016-09-20 11:50:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-20 13:50:46.131  9800  9865 I jxcore-log: 
,09-20 13:50:46.131  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:46.281  9800  9865 I jxcore-log: Running unit tests
09-20 13:50:46.281  9800  9865 I jxcore-log: 
,09-20 13:50:46.281  9800  9865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-20 13:50:46.281  9800  9865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53532d1 added. We now have 2 listener(s)
09-20 13:50:46.281  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-20 13:50:46.281  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-20 13:50:46.281  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-20 13:50:46.281  9800  9865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-20 13:50:46.281  9800  9865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc88136 added. We now have 2 listener(s)
09-20 13:50:46.281  9800  9865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-20 13:50:46.281  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-20 13:50:46.281  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-20 13:50:46.291  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.291  9800  9865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 13:50:46.291  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 13:50:46.291  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 13:50:46.291  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 13:50:46.291  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 13:50:46.291  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 13:50:46.291  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 13:50:46.291  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 13:50:46.301  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.301  9800  9865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-20 13:50:46.301  9800  9865 D io.jxcore.node.ConnectivityMonitor: start: OK
09-20 13:50:46.301  9800  9865 D executeNativeTests: Running unit tests
,09-20 13:50:46.311  9800  9800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 13:50:46.311  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:46.311  9800  9800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 13:50:46.341  9800  9865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-20 13:50:46.341  9800  9865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3cabd4 added. We now have 3 listener(s)
09-20 13:50:46.341  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-20 13:50:46.341  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-20 13:50:46.341  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-20 13:50:46.341  9800  9865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-20 13:50:46.341  9800  9865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@627f17d added. We now have 3 listener(s)
09-20 13:50:46.341  9800  9865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-20 13:50:46.341  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-20 13:50:46.351  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-20 13:50:46.361  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.361  9800  9865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 13:50:46.361  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 13:50:46.361  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 13:50:46.361  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 13:50:46.361  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 13:50:46.361  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 13:50:46.361  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 13:50:46.361  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 13:50:46.371  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.371  9800  9865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-20 13:50:46.371  9800  9865 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-20 13:50:46.371  9800  9865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-20 13:50:46.371  9800  9865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-20 13:50:46.371  9800  9865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-20 13:50:46.371  9800  9865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-20 13:50:46.371  9800  9865 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-20 13:50:46.371  9800  9865 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-20 13:50:46.371  9800  9865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-20 13:50:46.371  9800  9865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-20 13:50:46.371  9800  9865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-20 13:50:46.371  9800  9865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-20 13:50:46.371  9800  9865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-20 13:50:46.371  9800  9865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-20 13:50:46.371  9800  9865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-20 13:50:46.371  9800  9865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-20 13:50:46.371  9800  9865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:50:46.371  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-20 13:50:46.371  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-20 13:50:46.371  9800  9865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3cabd4 removed from the list
09-20 13:50:46.371  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-20 13:50:46.371  9800  9865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@627f17d removed from the list
09-20 13:50:46.371  9800  9800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-20 13:50:46.371  9800  9865 D io.jxcore.node.ConnectivityMonitor: stop
09-20 13:50:46.371  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 13:50:46.381  9800  9865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-20 13:50:46.381  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-20 13:50:46.381  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-20 13:50:46.381  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-20 13:50:46.381  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 13:50:46.381  9800  9865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@627f17d not in the list
,09-20 13:50:46.381  9800  9865 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-20 13:50:46.381  9800  9865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-20 13:50:46.381  9800  9865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-20 13:50:46.381  9800  9865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-20 13:50:46.381  9800  9865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-20 13:50:46.381  9800  9865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:50:46.381  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 13:50:46.381  9800  9865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3cabd4 not in the list
09-20 13:50:46.381  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 13:50:46.381  9800  9865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@627f17d not in the list
,09-20 13:50:46.381  9800  9865 D io.jxcore.node.ConnectivityMonitor: stop
09-20 13:50:46.381  9800  9865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:50:46.381  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 13:50:46.381  9800  9865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-20 13:50:46.381  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-20 13:50:46.391  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-20 13:50:46.391  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-20 13:50:46.391  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 13:50:46.391  9800  9865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@627f17d not in the list
,09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-20 13:50:46.391  9800  9865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-20 13:50:46.391  9800  9865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-20 13:50:46.391  9800  9865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-20 13:50:46.391  9800  9865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-20 13:50:46.391  9800  9865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:50:46.391  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-20 13:50:46.391  9800  9865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3cabd4 not in the list
09-20 13:50:46.391  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 13:50:46.391  9800  9865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@627f17d not in the list
09-20 13:50:46.391  9800  9865 D io.jxcore.node.ConnectivityMonitor: stop
09-20 13:50:46.391  9800  9865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:50:46.391  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 13:50:46.391  9800  9865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:50:46.391  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-20 13:50:46.401  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-20 13:50:46.401  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-20 13:50:46.401  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 13:50:46.401  9800  9865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@627f17d not in the list
09-20 13:50:46.401  9800  9865 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-20 13:50:46.401  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-20 13:50:46.411  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.411  9800  9865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 13:50:46.411  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 13:50:46.411  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 13:50:46.411  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 13:50:46.411  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 13:50:46.411  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 13:50:46.411  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 13:50:46.411  9800  9865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 13:50:46.411  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.421  9800  9865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-20 13:50:46.421  9800  9865 D io.jxcore.node.ConnectivityMonitor: start: OK
09-20 13:50:46.421  9800  9865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-20 13:50:46.421  9800  9865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-20 13:50:46.421  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-20 13:50:46.421  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 13:50:46.421  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-20 13:50:46.431  9800  9800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 13:50:46.431  9800  9865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-20 13:50:46.431  9800  9865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-20 13:50:46.431  9800  9800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 13:50:46.441  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.441  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.441  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.451  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-20 13:50:46.451  9800  9865 D BluetoothAdapter: STATE_ON
09-20 13:50:46.451  9800  9865 D BluetoothAdapter: STATE_ON
09-20 13:50:46.451  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-20 13:50:46.451  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-20 13:50:46.461  9800  9865 D BluetoothAdapter: STATE_ON
09-20 13:50:46.461  9800  9865 D BluetoothAdapter: STATE_ON
09-20 13:50:46.461  9800  9865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-20 13:50:46.471  9800  9865 D BluetoothAdapter: STATE_ON
09-20 13:50:46.471  9800  9865 D BluetoothAdapter: STATE_ON
09-20 13:50:46.471  9800  9865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-20 13:50:46.471  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-20 13:50:46.471  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-20 13:50:46.471  9800  9865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-20 13:50:46.471  9800  9865 D BluetoothLeScanner: Start Scan
09-20 13:50:46.471  9800  9865 D BluetoothAdapter: STATE_ON
09-20 13:50:46.471  9800  9865 D BluetoothAdapter: STATE_ON
09-20 13:50:46.481  9800  9865 D BluetoothAdapter: STATE_ON
09-20 13:50:46.481  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.481  5029  5042 D BtGatt.GattService: registerClient() - UUID=efce6527-6443-4c29-b12e-be6ffabb4c2a
,09-20 13:50:46.491  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:46.541  5029  5177 D BtGatt.GattService: onClientRegistered() - UUID=efce6527-6443-4c29-b12e-be6ffabb4c2a, clientIf=7
,09-20 13:50:46.541  9800  9810 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-20 13:50:46.541  5029  5477 D BtGatt.GattService: start scan with filters
,09-20 13:50:46.551  5029  5477 D BtGatt.GattService: getScanSettings
,09-20 13:50:46.571  5029  5477 D BtGatt.GattService: Is it foreground application = true
,09-20 13:50:46.571  5029  5477 D BtGatt.GattService: not a background application
,09-20 13:50:46.581  5029  5477 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-20 13:50:46.591  5029  5477 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-20 13:50:46.591  5029  5477 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-20 13:50:46.591  5029  5257 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
,09-20 13:50:46.591  5029  5257 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 20, currDate: 20
09-20 13:50:46.591  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-20 13:50:46.591  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-20 13:50:46.591  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-20 13:50:46.591  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-20 13:50:46.591  5029  5248 D BtGatt.ScanManager: handling starting scan
09-20 13:50:46.591  5029  5248 D BtGatt.ScanManager: isFilteringSupported
,09-20 13:50:46.591  5029  5248 D BluetoothAdapter: enableStandAloneBleMode=
09-20 13:50:46.591  5029  5248 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.601  5029  5248 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.601  9800  9865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-20 13:50:46.601  9800  9865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-20 13:50:46.601  9800  9800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-20 13:50:46.611  5029  5248 D BluetoothAdapter: STATE_ON
09-20 13:50:46.611  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-20 13:50:46.611  5029  5248 D BluetoothAdapter: STATE_ON
,09-20 13:50:46.611  5029  5257 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 9
09-20 13:50:46.611  5029  5257 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-20 13:50:46.611  5029  5248 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@810b740
,09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 7
09-20 13:50:46.621  9800  9865 I io.jxcore.node.ConnectionHelper: start: OK
09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24572870
09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-20 13:50:46.621  3433  3782 V AlarmManager:  remove PendingIntent] PendingIntent{aeeef92: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-20 13:50:46.621  5029  5257 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24572870
,09-20 13:50:46.631  5029  5177 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-20 13:50:46.631  5029  5177 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-20 13:50:46.631  5029  5248 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
09-20 13:50:46.631  5029  5248 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-20 13:50:46.631  5029  5248 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-20 13:50:46.631  5029  5248 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-20 13:50:46.631  3433  3973 V AlarmManager:  remove PendingIntent] PendingIntent{1a6ad63: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:46.631  5029  5177 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
,09-20 13:50:46.631  5029  5177 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 13:50:46.631  5029  5248 D BtGatt.ScanManager: Starting BLE batch scan
09-20 13:50:46.631  5029  5248 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-20 13:50:46.631  3433  3477 V AlarmManager:  remove PendingIntent] PendingIntent{a5e2d60: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:46.641  5029  5177 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,09-20 13:50:46.641  5029  5177 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-20 13:50:46.641  5029  5177 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,09-20 13:50:46.641  5029  5177 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 13:50:46.641  3433  3972 V AlarmManager:  remove PendingIntent] PendingIntent{42cc219: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
09-20 13:50:46.641  3433  4980 V AlarmManager:  remove PendingIntent] PendingIntent{28872de: PendingIntentRecord{cccbcbf com.android.bluetooth broadcastIntent}}
,09-20 13:50:46.651  3433  4188 V AlarmManager:  remove PendingIntent] PendingIntent{f68bf8c: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:46.651  3433  4339 V AlarmManager:  remove PendingIntent] PendingIntent{c3e66d5: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:46.661  3433  4761 V AlarmManager:  remove PendingIntent] PendingIntent{7a4deea: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:46.661  3433  4325 V AlarmManager:  remove PendingIntent] PendingIntent{1a65db: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:46.671  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:46.671  3433  4980 V AlarmManager:  remove PendingIntent] PendingIntent{8a84878: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:46.671  3433  4505 V AlarmManager:  remove PendingIntent] PendingIntent{a8b9b51: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:46.681  3433  3476 V AlarmManager:  remove PendingIntent] PendingIntent{869ffb6: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:46.691  3433  3973 V AlarmManager:  remove PendingIntent] PendingIntent{dcf84b7: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:46.691  3433  3477 V AlarmManager:  remove PendingIntent] PendingIntent{8557424: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:46.851  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:47.031  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:47.111  9800  9800 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-20 13:50:47.111  9800  9800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-20 13:50:47.111  9800  9800 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-20 13:50:47.211  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:47.391  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:47.571  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:47.641  3433  3818 V AlarmManager: Expired Alarm result :4
,09-20 13:50:47.651  5029  5029 D BtGatt.ScanManager: awakened up at time 198122
,09-20 13:50:47.651  5029  5248 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 13:50:47.651  3433  4699 V AlarmManager:  remove PendingIntent] PendingIntent{d8e6142: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:47.661  5029  5177 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
,09-20 13:50:47.661  5029  5177 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-20 13:50:47.661  3433  4505 V AlarmManager:  remove PendingIntent] PendingIntent{24db553: PendingIntentRecord{cccbcbf com.android.bluetooth broadcastIntent}}
,09-20 13:50:47.661  5029  5177 D BtGatt.GattService: current time is 198132671588
09-20 13:50:47.661  5029  5177 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -77, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 50, -35, 86, -77, -92, -11, 1, -128, -96, 13, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 28, 57, 10, 3, 1, -37, 18, 61, -62, -57, -79, 0]
,09-20 13:50:47.661  3433  3595 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
09-20 13:50:47.661  5029  5177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-20 13:50:47.671  5029  5177 D ScanRecord: parseFromBytes
09-20 13:50:47.671  5029  5177 D ScanRecord: first manudata for manu ID
09-20 13:50:47.671  5029  5177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-20 13:50:47.671  5029  5177 D ScanRecord: parseFromBytes
09-20 13:50:47.671  5029  5177 D ScanRecord: first manudata for manu ID
09-20 13:50:47.671  5029  5177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 28, 57, 10, 3, 1, -37, 18, 61, -62, -57, -79]
,09-20 13:50:47.671  5029  5177 D ScanRecord: parseFromBytes
09-20 13:50:47.671  5029  5177 D ScanRecord: first manudata for manu ID
09-20 13:50:47.671  9800  9811 D ScanRecord: parseFromBytes
,09-20 13:50:47.671  9800  9811 D ScanRecord: first manudata for manu ID
,09-20 13:50:47.681  9800  9811 D ScanRecord: parseFromBytes
09-20 13:50:47.681  9800  9811 D ScanRecord: first manudata for manu ID
,09-20 13:50:47.681  9800  9811 D ScanRecord: parseFromBytes
09-20 13:50:47.681  9800  9811 D ScanRecord: first manudata for manu ID
,09-20 13:50:47.691  3433  3595 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-20 13:50:47.691  3433  3476 V AlarmManager:  remove PendingIntent] PendingIntent{987ae90: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:47.701  3433  3973 V AlarmManager:  remove PendingIntent] PendingIntent{9556389: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:47.701  3433  3477 V AlarmManager:  remove PendingIntent] PendingIntent{2a54f8e: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:47.711  3433  4980 V AlarmManager:  remove PendingIntent] PendingIntent{47453af: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:47.721  3433  3972 V AlarmManager:  remove PendingIntent] PendingIntent{f6123bc: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:47.751  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:47.931  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:48.111  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:48.291  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:48.471  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:48.651  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:48.661  3433  3818 V AlarmManager: Expired Alarm result :4
,09-20 13:50:48.671  5029  5029 D BtGatt.ScanManager: awakened up at time 199140
,09-20 13:50:48.681  5029  5248 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 13:50:48.681  3433  4761 V AlarmManager:  remove PendingIntent] PendingIntent{72ad69a: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:48.681  5029  5177 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=4
,09-20 13:50:48.681  3433  3477 V AlarmManager:  remove PendingIntent] PendingIntent{fbc7bcb: PendingIntentRecord{cccbcbf com.android.bluetooth broadcastIntent}}
09-20 13:50:48.681  5029  5177 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 13:50:48.681  5029  5177 D BtGatt.GattService: current time is 199158641472
09-20 13:50:48.681  5029  5177 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -77, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -77, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -85, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -52, 11, 57, -70, 107, -17, 1, 0, -98, 5, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-20 13:50:48.681  5029  5177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-20 13:50:48.691  5029  5177 D ScanRecord: parseFromBytes
09-20 13:50:48.691  5029  5177 D ScanRecord: first manudata for manu ID
,09-20 13:50:48.691  5029  5177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-20 13:50:48.691  5029  5177 D ScanRecord: parseFromBytes
,09-20 13:50:48.691  5029  5177 D ScanRecord: first manudata for manu ID
,09-20 13:50:48.691  5029  5177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-20 13:50:48.691  5029  5177 D ScanRecord: parseFromBytes
09-20 13:50:48.691  5029  5177 D ScanRecord: first manudata for manu ID
09-20 13:50:48.701  3433  4980 V AlarmManager:  remove PendingIntent] PendingIntent{afabfa8: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
09-20 13:50:48.691  5029  5177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
,09-20 13:50:48.691  5029  5177 D ScanRecord: parseFromBytes
09-20 13:50:48.691  5029  5177 D ScanRecord: first manudata for manu ID
09-20 13:50:48.691  9800  9810 D ScanRecord: parseFromBytes
09-20 13:50:48.691  9800  9810 D ScanRecord: first manudata for manu ID
,09-20 13:50:48.691  9800  9810 D ScanRecord: parseFromBytes
09-20 13:50:48.691  9800  9810 D ScanRecord: first manudata for manu ID
09-20 13:50:48.691  9800  9810 D ScanRecord: parseFromBytes
09-20 13:50:48.691  9800  9810 D ScanRecord: first manudata for manu ID
,09-20 13:50:48.691  9800  9810 D ScanRecord: parseFromBytes
09-20 13:50:48.691  9800  9810 D ScanRecord: first manudata for manu ID
,09-20 13:50:48.701  3433  3972 V AlarmManager:  remove PendingIntent] PendingIntent{718fac1: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:48.711  3433  3782 V AlarmManager:  remove PendingIntent] PendingIntent{44fc266: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:48.711  3433  4981 V AlarmManager:  remove PendingIntent] PendingIntent{41509a7: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:48.721  3433  4339 V AlarmManager:  remove PendingIntent] PendingIntent{4102e54: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:48.831  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:49.011  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:49.191  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:49.371  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:49.551  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:49.691  3433  3818 V AlarmManager: Expired Alarm result :4
,09-20 13:50:49.691  5029  5029 D BtGatt.ScanManager: awakened up at time 200166
,09-20 13:50:49.701  5029  5248 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 13:50:49.701  3433  4505 V AlarmManager:  remove PendingIntent] PendingIntent{3859ef2: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:49.701  5029  5177 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
,09-20 13:50:49.711  5029  5177 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 13:50:49.711  5029  5177 D BtGatt.GattService: current time is 200180605548
09-20 13:50:49.711  5029  5177 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -72, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -52, 11, 57, -70, 107, -17, 1, 0, -100, 0, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 0]
,09-20 13:50:49.711  3433  4324 V AlarmManager:  remove PendingIntent] PendingIntent{77e9943: PendingIntentRecord{cccbcbf com.android.bluetooth broadcastIntent}}
09-20 13:50:49.711  5029  5177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-20 13:50:49.711  5029  5177 D ScanRecord: parseFromBytes
09-20 13:50:49.711  5029  5177 D ScanRecord: first manudata for manu ID
09-20 13:50:49.711  5029  5177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-20 13:50:49.711  5029  5177 D ScanRecord: parseFromBytes
,09-20 13:50:49.711  5029  5177 D ScanRecord: first manudata for manu ID
09-20 13:50:49.711  5029  5177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82]
09-20 13:50:49.711  5029  5177 D ScanRecord: parseFromBytes
,09-20 13:50:49.711  9800  9811 D ScanRecord: parseFromBytes
09-20 13:50:49.711  9800  9811 D ScanRecord: parseFromBytes
09-20 13:50:49.711  9800  9811 D ScanRecord: first manudata for manu ID
09-20 13:50:49.711  9800  9811 D ScanRecord: parseFromBytes
,09-20 13:50:49.711  9800  9811 D ScanRecord: first manudata for manu ID
,09-20 13:50:49.721  3433  3476 V AlarmManager:  remove PendingIntent] PendingIntent{6bdbc0: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:49.731  3433  4761 V AlarmManager:  remove PendingIntent] PendingIntent{16140f9: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:49.731  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:49.731  3433  4151 V AlarmManager:  remove PendingIntent] PendingIntent{1cab83e: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:49.741  3433  4980 V AlarmManager:  remove PendingIntent] PendingIntent{567869f: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:49.741  3433  4417 V AlarmManager:  remove PendingIntent] PendingIntent{612f3ec: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:49.751  3433  3782 V AlarmManager:  remove PendingIntent] PendingIntent{ebf3b5: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:49.761  3433  4981 V AlarmManager:  remove PendingIntent] PendingIntent{bb61a4a: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:49.761  3433  4339 V AlarmManager:  remove PendingIntent] PendingIntent{7c7edbb: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:49.911  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:50.091  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:50.271  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:50.451  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:50.631  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:50.711  3433  3818 V AlarmManager: Expired Alarm result :4
,09-20 13:50:50.711  5029  5029 D BtGatt.ScanManager: awakened up at time 201188
,09-20 13:50:50.721  5029  5248 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 13:50:50.721  3433  4324 V AlarmManager:  remove PendingIntent] PendingIntent{351631: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:50.731  5029  5177 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
09-20 13:50:50.731  5029  5177 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 13:50:50.731  3433  3972 V AlarmManager:  remove PendingIntent] PendingIntent{e439116: PendingIntentRecord{cccbcbf com.android.bluetooth broadcastIntent}}
09-20 13:50:50.731  5029  5177 D BtGatt.GattService: current time is 201205239970
09-20 13:50:50.731  5029  5177 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -80, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -72, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-20 13:50:50.731  5029  5177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-20 13:50:50.731  5029  5177 D ScanRecord: parseFromBytes
09-20 13:50:50.731  5029  5177 D ScanRecord: first manudata for manu ID
09-20 13:50:50.731  5029  5177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-20 13:50:50.731  5029  5177 D ScanRecord: parseFromBytes
09-20 13:50:50.731  5029  5177 D ScanRecord: first manudata for manu ID
09-20 13:50:50.731  9800  9810 D ScanRecord: parseFromBytes
09-20 13:50:50.731  9800  9810 D ScanRecord: first manudata for manu ID
,09-20 13:50:50.731  9800  9810 D ScanRecord: parseFromBytes
09-20 13:50:50.731  9800  9810 D ScanRecord: first manudata for manu ID
,09-20 13:50:50.741  3433  3476 V AlarmManager:  remove PendingIntent] PendingIntent{5fdaa97: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:50.751  3433  4761 V AlarmManager:  remove PendingIntent] PendingIntent{ec5d484: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:50.751  3433  4151 V AlarmManager:  remove PendingIntent] PendingIntent{313e46d: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:50.761  3433  4980 V AlarmManager:  remove PendingIntent] PendingIntent{85fa8a2: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:50.761  3433  4699 V AlarmManager:  remove PendingIntent] PendingIntent{5685933: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:50.811  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:50.991  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:51.171  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:51.351  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:51.531  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:51.631  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:51.641  9800  9865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-20 13:50:51.641  9800  9865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-20 13:50:51.641  9800  9865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-20 13:50:51.641  9800  9865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:50:51.641  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-20 13:50:51.641  9800  9865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-20 13:50:51.641  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-20 13:50:51.641  9800  9865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-20 13:50:51.641  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-20 13:50:51.641  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-20 13:50:51.641  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-20 13:50:51.641  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:51.651  9800  9865 D BluetoothAdapter: STATE_ON
,09-20 13:50:51.651  9800  9865 D BluetoothLeScanner: Stop Scan
,09-20 13:50:51.661  5029  5042 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-20 13:50:51.661  5029  5042 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-20 13:50:51.661  5029  5042 D BtGatt.GattService: stopScan() - queue size =1
,09-20 13:50:51.661  5029  5257 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-20 13:50:51.661  5029  5257 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 20, currDate: 20
09-20 13:50:51.661  5029  5257 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-20 13:50:51.661  5029  5257 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-20 13:50:51.661  5029  5248 D BtGatt.ScanManager: filter size is 1
09-20 13:50:51.661  5029  5257 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
,09-20 13:50:51.661  5029  5257 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-20 13:50:51.661  5029  5248 D BtGatt.ScanManager: delete FilterIndex - 3
,09-20 13:50:51.661  5029  5257 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
09-20 13:50:51.671  5029  5216 D BtGatt.GattService: unregisterClient() - clientIf=7
09-20 13:50:51.671  3433  4324 V AlarmManager:  remove PendingIntent] PendingIntent{90db4f0: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
09-20 13:50:51.671  5029  5177 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-20 13:50:51.671  5029  5177 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 13:50:51.671  5029  5248 D BtGatt.ScanManager: stopping BLe Batch
,09-20 13:50:51.671  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-20 13:50:51.671  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-20 13:50:51.671  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-20 13:50:51.671  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-20 13:50:51.671  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-20 13:50:51.671  5029  5177 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
,09-20 13:50:51.671  5029  5177 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-20 13:50:51.671  5029  5248 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
09-20 13:50:51.671  9800  9865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-20 13:50:51.681  5029  5177 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-20 13:50:51.681  5029  5177 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 13:50:51.681  9800  9865 D BluetoothAdapter: STATE_ON
09-20 13:50:51.681  3433  3476 V AlarmManager:  remove PendingIntent] PendingIntent{9975a69: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:51.681  3433  3973 V AlarmManager:  remove PendingIntent] PendingIntent{933acee: PendingIntentRecord{cccbcbf com.android.bluetooth broadcastIntent}}
,09-20 13:50:51.681  9800  9865 D BluetoothAdapter: STATE_ON
09-20 13:50:51.681  9800  9865 D BluetoothLeAdvertiser: stop advertising
09-20 13:50:51.681  9800  9865 D BluetoothLeAdvertiser: wrapper is null
,09-20 13:50:51.681  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-20 13:50:51.681  9800  9865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-20 13:50:51.681  9800  9865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-20 13:50:51.691  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-20 13:50:51.691  3433  4151 V AlarmManager:  remove PendingIntent] PendingIntent{7c5558f: PendingIntentRecord{cccbcbf com.android.bluetooth broadcastIntent}}
,09-20 13:50:51.691  9800  9865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-20 13:50:51.691  9800  9800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-20 13:50:51.691  9800  9800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 13:50:51.691  9800  9800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-20 13:50:51.691  9800  9865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:50:51.691  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-20 13:50:51.691  9800  9865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3cabd4 not in the list
09-20 13:50:51.691  9800  9865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 13:50:51.691  9800  9865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@627f17d not in the list
09-20 13:50:51.691  9800  9865 D io.jxcore.node.ConnectivityMonitor: stop
,09-20 13:50:51.691  9800  9865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-20 13:50:51.701  9800  9800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-20 13:50:51.701  9800  9800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-20 13:50:51.701  3433  3973 V AlarmManager:  remove PendingIntent] PendingIntent{34bbbab: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:51.701  9800  9800 D BluetoothAdapter: STATE_ON
,09-20 13:50:51.711  9800  9800 D BluetoothAdapter: STATE_ON
,09-20 13:50:51.711  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:50:51.711  3433  3476 V AlarmManager:  remove PendingIntent] PendingIntent{baf3208: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:51.711  9800  9800 D BluetoothAdapter: STATE_ON
,09-20 13:50:51.711  9800  9800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-20 13:50:51.711  3433  3782 V AlarmManager:  remove PendingIntent] PendingIntent{506eda1: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:51.711  9800  9800 D BluetoothAdapter: STATE_ON
,09-20 13:50:51.711  9800  9800 D BluetoothAdapter: STATE_ON
,09-20 13:50:51.711  9800  9800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-20 13:50:51.711  9800  9800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-20 13:50:51.711  9800  9800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-20 13:50:51.721  9800  9800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-20 13:50:51.721  3433  4324 V AlarmManager:  remove PendingIntent] PendingIntent{be06bc6: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:51.721  9800  9800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-20 13:50:51.721  9800  9800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 13:50:51.721  9800  9800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-20 13:50:51.721  3433  4188 V AlarmManager:  remove PendingIntent] PendingIntent{886787: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:51.731  9800  9800 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-20 13:50:51.731  9800  9800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-20 13:50:51.731  9800  9800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 13:50:51.731  3433  4505 V AlarmManager:  remove PendingIntent] PendingIntent{9f9f523: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:51.731  9800  9800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-20 13:50:51.731  3433  4188 V AlarmManager:  remove PendingIntent] PendingIntent{4303a20: PendingIntentRecord{78cae68 com.android.bluetooth broadcastIntent}}
,09-20 13:50:51.891  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:52.071  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:52.231  9800  9800 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-20 13:50:52.251  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:52.431  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:52.611  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:52.791  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:52.971  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:53.071  3433  6462 D SSRM:n  : SIOP:: AP = 320, PST = 298 (W:6), CP = 252, CUR = 151, LCD = 1
,09-20 13:50:53.151  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:53.331  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:53.511  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:53.691  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:53.871  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:54.051  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:54.231  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:54.411  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:54.591  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:54.771  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:54.951  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:55.131  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:55.311  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:55.491  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:55.671  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:55.851  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:50:56.031  3433  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
