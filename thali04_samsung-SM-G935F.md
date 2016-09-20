#### Test 8561557223fedb8_thali04_samsung-SM-G935F Logs


```
--------- beginning of main
09-20 17:58:54.416  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:54.596  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 17:58:54.776  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 17:58:54.956  9822  9822 I FIPS_bssl: FIPS approved mode (1) | 9822 | app_process
09-20 17:58:54.956  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 17:58:54.956  9822  9822 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-20 17:58:54.966  9822  9822 D AndroidRuntime: CheckJNI is OFF
09-20 17:58:54.966  9822  9822 D AndroidRuntime: readGMSProperty: start
09-20 17:58:54.966  9822  9822 D AndroidRuntime: readGMSProperty: already setted!!
09-20 17:58:54.966  9822  9822 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-20 17:58:54.966  9822  9822 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-20 17:58:54.966  9822  9822 D AndroidRuntime: readGMSProperty: end
09-20 17:58:54.966  9822  9822 D AndroidRuntime: addProductProperty: start
09-20 17:58:54.976  9822  9822 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-20 17:58:55.006  9822  9822 I Radio-JNI: register_android_hardware_Radio DONE
09-20 17:58:55.006  9822  9822 E AffinityControl: AffinityControl: registerfunction enter
09-20 17:58:55.016  9822  9822 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-20 17:58:55.036  3432  3459 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-20 17:58:55.046  3432  3459 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-20 17:58:55.066  3432  3459 D ResourcesManager: For user 0 new overlays fetched Null
09-20 17:58:55.066  3432  3459 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 17:58:55.066  3432  3459 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-20 17:58:55.066  3432  3459 D ActivityManager: mDVFSHelper.acquire()
09-20 17:58:55.066  3432  3459 V WindowManager: addAppToken: AppWindowToken{d012a0877 token=Token{7d13a76 ActivityRecord{5f40911 u0 com.test.thalitest/.MainActivity t75}}} to stack=2 task=75 at 0
09-20 17:58:55.076  3432  3552 I InjectionManager: Inside getClassLibPath caller 
09-20 17:58:55.086  3432  3552 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-20 17:58:55.086  3432  3552 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{8a38f6f V.E...... R.....ID 0,0-0,0}
09-20 17:58:55.086  9831  9831 E Zygote  : v2
09-20 17:58:55.086  9831  9831 I libpersona: KNOX_SDCARD checking this for 10177
09-20 17:58:55.086  9831  9831 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-20 17:58:55.086  9831  9831 I libpersona: KNOX_SDCARD not a persona
09-20 17:58:55.086  3432  3552 W WindowManager: Failed looking up window
09-20 17:58:55.086  3432  3552 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@232147c does not exist
09-20 17:58:55.086  3432  3552 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 17:58:55.086  3432  3552 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-20 17:58:55.086  3432  3552 D ISSUE_DEBUG: InputChannelName : 578b105 Starting com.test.thalitest
09-20 17:58:55.086  9831  9831 E Zygote  : accessInfo : 0
09-20 17:58:55.086  9831  9831 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-20 17:58:55.086  3432  3459 I ActivityManager: Start proc 9831:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-20 17:58:55.086  3432  3459 D InputDispatcher: Focused application set to: xxxx
09-20 17:58:55.096  9822  9822 D AndroidRuntime: Shutting down VM
09-20 17:58:55.096  3432  3859 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-20 17:58:55.116  9831  9831 D TimaKeyStoreProvider: TimaSignature is unavailable
09-20 17:58:55.116  9831  9831 D ActivityThread: Added TimaKeyStore provider
09-20 17:58:55.116  3008  3008 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-20 17:58:55.136  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 17:58:55.146  6541  6541 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 17:58:55.166  3432  4059 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3432
09-20 17:58:55.166  3432  4059 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 17:58:55.166  3432  4059 D PowerManagerService: mDisplayReady: false
09-20 17:58:55.166  3432  4059 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 17:58:55.166  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 17:58:55.166  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f7e183c00
09-20 17:58:55.166  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 17:58:55.166  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-20 17:58:55.166  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:58:55.166  3432  4059 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 17:58:55.166  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:58:55.166  3432  3573 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-20 17:58:55.166  3008  3053 W SurfaceFlinger: Ignoring duplicate VSYNC event from HWC (t=182617400369)
09-20 17:58:55.166  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 17:58:55.166  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 17:58:55.166  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:58:55.166  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:58:55.166  3432  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 17:58:55.166  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 17:58:55.166  3432  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 17:58:55.166  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 17:58:55.166  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:58:55.166  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:58:55.166  3432  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 17:58:55.166  3432  3556 D PowerManagerService: mDisplayReady: true
09-20 17:58:55.166  3432  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-20 17:58:55.176  3432  4352 D ActivityManager:  Launching com.test.thalitest, updated priority
09-20 17:58:55.186  3432  5013 V WindowStateAnimator: Finishing drawing window Window{c41aa66 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-20 17:58:55.186  6541  6541 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 17:58:55.186  6541  6541 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 17:58:55.196  6541  6541 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 17:58:55.196  6541  6541 V ActivityThread: updateVisibility : ActivityRecord{798a489 token=android.os.BinderProxy@9b51e72 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-20 17:58:55.206  6208  6219 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-20 17:58:55.206  3432  3432 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-20 17:58:55.206  3432  3520 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-20 17:58:55.226  3008  3019 I SurfaceFlinger: id=18 Removed VSBConnecti (8/13)
09-20 17:58:55.226  3008  3844 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/13)
09-20 17:58:55.226  3008  4630 D libEGL  : eglTerminate EGLDisplay = 0x7f766ffe78
09-20 17:58:55.226  3008  4630 D libEGL  : eglTerminate EGLDisplay = 0x7f766ffe78
09-20 17:58:55.236  3008  3844 D libEGL  : eglTerminate EGLDisplay = 0x7f777fee78
09-20 17:58:55.236  3008  4630 I SurfaceFlinger: id=9 Removed MauncherAct (3/12)
09-20 17:58:55.236  3008  3017 I SurfaceFlinger: id=9 Removed MauncherAct (-2/12)
09-20 17:58:55.236  3008  4355 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
09-20 17:58:55.246  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc28f10a8
09-20 17:58:55.246  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc28f10a8
09-20 17:58:55.246  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc28f1078
09-20 17:58:55.256  4313  4313 V ActivityThread: updateVisibility : ActivityRecord{be37030 token=android.os.BinderProxy@9a776c {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-20 17:58:55.256  4313  4313 D Launcher: onTrimMemory. Level: 20
09-20 17:58:55.316  3432  3432 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3432 (0x0)
09-20 17:58:55.316  3432  3432 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 17:58:55.316  3432  3432 D PowerManagerService: mDisplayReady: false
09-20 17:58:55.316  3432  3432 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 17:58:55.316  3432  3432 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,09-20 17:58:55.316  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 17:58:55.316  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 17:58:55.316  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:58:55.316  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:58:55.316  3432  3573 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-20 17:58:55.316  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f7e183c00
09-20 17:58:55.316  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-20 17:58:55.316  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 17:58:55.316  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 17:58:55.316  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 17:58:55.316  3432  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 17:58:55.316  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:58:55.316  3432  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 17:58:55.316  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:58:55.316  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 17:58:55.316  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 17:58:55.316  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:58:55.316  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:58:55.316  3432  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 17:58:55.316  3432  3556 D PowerManagerService: mDisplayReady: true
09-20 17:58:55.316  3432  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-20 17:58:55.496  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 17:58:55.506  6208  6208 I TrayVisibilityController: handleMessage : msg.what = 1
09-20 17:58:55.536  3432  4352 I WindowManager: Screenshot max retries 4 of Token{7d13a76 ActivityRecord{5f40911 u0 com.test.thalitest/.MainActivity t75}} appWin=Window{578b105 u0 d0 Starting com.test.thalitest} drawState=1
09-20 17:58:55.536  6208  6218 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-20 17:58:55.536  3432  3552 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 17:58:55.536  3432  3432 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 17:58:55.536  3432  3552 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-20 17:58:55.546  6208  6208 I Utils   : isCurrentUser current = 0, ownerId = 0
09-20 17:58:55.546  6208  6208 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-20 17:58:55.546  6208  6208 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-20 17:58:55.556  3432  3859 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-20 17:58:55.556  3432  6457 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 17:58:55.556  3432  6457 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 17:58:55.566  3432  3432 I KnoxTimeoutHandler: SD activityfalse
09-20 17:58:55.586  3432  6457 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 17:58:55.586  9831  9831 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-20 17:58:55.586  9831  9831 D RelationGraph: garbageCollect()
09-20 17:58:55.586  3432  3552 V WindowStateAnimator: Finishing drawing window Window{578b105 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-20 17:58:55.586  3432  3552 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 17:58:55.586  3432  3432 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 17:58:55.586  3432  3552 D ActivityManager: mDVFSHelper.release()
09-20 17:58:55.586  3432  3432 I KnoxTimeoutHandler: SD activityfalse
09-20 17:58:55.586  3432  6457 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 17:58:55.586  3432  3552 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{64cc942 u0 com.samsung.android.MtpApplication/.USBConnection t74} time:183039
09-20 17:58:55.596  9831  9831 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 17:58:55.596  3432  4351 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-20 17:58:55.596  9831  9831 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-20 17:58:55.596  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fc28f0f88
09-20 17:58:55.606  3432  6457 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 17:58:55.606  3432  6457 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 17:58:55.606  3432  6457 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 17:58:55.606  9831  9831 D ResourcesManager: For user 0 new overlays fetched Null
09-20 17:58:55.616  9831  9831 I InjectionManager: Inside getClassLibPath caller 
09-20 17:58:55.636  9831  9831 D InjectionManager: InjectionManager
09-20 17:58:55.636  9831  9831 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-20 17:58:55.636  9831  9831 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-20 17:58:55.636  9831  9831 I InjectionManager: featureStore :{}
09-20 17:58:55.636  9831  9831 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 17:58:55.636  9831  9831 D RelationGraph: garbageCollect()
09-20 17:58:55.646  9831  9831 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 17:58:55.676  9831  9831 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-20 17:58:55.676  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 17:58:55.736  9831  9831 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-20 17:58:55.736  9831  9831 D ResourcesManager: For user 0 new overlays fetched Null
09-20 17:58:55.736  9831  9831 I InjectionManager: Inside getClassLibPath caller 
09-20 17:58:55.746  9831  9831 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-20 17:58:55.796  3432  3882 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-20 17:58:55.806  9831  9831 I cr_LibraryLoader: Time to load native libraries: 34 ms (timestamps 3216-3250)
09-20 17:58:55.806  9831  9831 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-20 17:58:55.846  3432  4254 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-20 17:58:55.846  3432  4254 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-20 17:58:55.846  3432  4254 D BatteryService: online:4, current avg:6, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
09-20 17:58:55.846  3432  4254 D BatteryService: stay LED for fully charged
09-20 17:58:55.846  3432  3432 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-20 17:58:55.856  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 17:58:55.856  3432  3432 I MotionRecognitionService: Plugged
09-20 17:58:55.856  3432  3432 D MotionRecognitionService:   cableConnection= 1
09-20 17:58:55.856  3432  3432 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-20 17:58:55.856  3432  3432 D MotionRecognitionService: skip setTransmitPower. 
09-20 17:58:55.866  3432  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
09-20 17:58:55.866  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-20 17:58:55.866  3939  3939 D KeyguardUpdateMonitor: handleBatteryUpdate
09-20 17:58:55.866  3939  3939 D PowerUI : priorPlugType = 2 mPlugType =  2
09-20 17:58:55.866  9831  9848 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-20 17:58:55.876  5088  5088 D CommonServiceConfiguration: getStringValueSetting
09-20 17:58:55.876  5048  5048 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-20 17:58:55.876  5048  5435 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-20 17:58:55.886  5088  5088 D BatteryMonitor: new battery level: 100
09-20 17:58:55.886  4753  4753 D BatteryController: saveBatteryData : level[100], status[5]
09-20 17:58:55.886  9831  9831 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {11ceec4}
09-20 17:58:55.886  9831  9831 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-20 17:58:55.896  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-20 17:58:55.896  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-20 17:58:55.896  3432  3882 I MdnieScenarioControlService: mGameModeLauncher : false
09-20 17:58:55.896  3432  3882 I MdnieScenarioControlService: setUIMode
09-20 17:58:55.906  9831  9831 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-20 17:58:55.936  9831  9831 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-20 17:58:56.036  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 17:58:56.036  3432  3520 W ActivityManager: Activity pause timeout for ActivityRecord{5f40911 u0 com.test.thalitest/.MainActivity t75}
09-20 17:58:56.046  9831  9831 D libEGL  : eglInitialize EGLDisplay = 0xff9be88c
09-20 17:58:56.116  3432  4458 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
09-20 17:58:56.116  3432  4458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-20 17:58:56.126  3432  6457 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:14), CP = 218, CUR = 6, LCD = 1
,09-20 17:58:56.196  9831  9831 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-20 17:58:56.206  9831  9831 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-20 17:58:56.206  9831  9831 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-20 17:58:56.216  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:56.226  9831  9831 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-20 17:58:56.256  9831  9831 D Activity: performCreate Call Injection manager
,09-20 17:58:56.256  9831  9831 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-20 17:58:56.276  9831  9831 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-20 17:58:56.286  9831  9831 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ba38442 I.E...... R.....ID 0,0-0,0}
,09-20 17:58:56.286  9831  9885 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-20 17:58:56.296  3432  4254 W WindowManager: Failed looking up window
09-20 17:58:56.296  3432  4254 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@b4980dc does not exist
09-20 17:58:56.296  3432  4254 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 17:58:56.296  3432  4254 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 17:58:56.296  3432  4254 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 17:58:56.296  3432  4254 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-20 17:58:56.296  3432  4254 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-20 17:58:56.296  3432  4254 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-20 17:58:56.296  3432  3460 D ISSUE_DEBUG: InputChannelName : 9b715e5 com.test.thalitest/com.test.thalitest.MainActivity
,09-20 17:58:56.296  3432  4059 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,09-20 17:58:56.296  3432  4059 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 17:58:56.296  3432  3432 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-20 17:58:56.296  3432  3432 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-20 17:58:56.306  9831  9831 V ActivityThread: updateVisibility : ActivityRecord{d410990 token=android.os.BinderProxy@f9f168a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-20 17:58:56.306  9831  9848 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-20 17:58:56.326  9831  9831 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9831
,09-20 17:58:56.336  3432  4059 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9831 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 17:58:56.336  3432  3870 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-20 17:58:56.336  3432  3870 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-20 17:58:56.336  3432  3870 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-20 17:58:56.346  3432  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 17:58:56.346  3432  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 17:58:56.356  9831  9831 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-20 17:58:56.356  3432  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-20 17:58:56.356  3432  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 17:58:56.366  3432  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-20 17:58:56.366  3432  3870 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 17:58:56.366  3008  3008 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,09-20 17:58:56.386  9831  9885 D libEGL  : eglInitialize EGLDisplay = 0xdc83f7c4
,09-20 17:58:56.386  9831  9885 I OpenGLRenderer: Initialized EGL, version 1.4
,09-20 17:58:56.396  9831  9885 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-20 17:58:56.396  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:56.396  3432  4606 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3432
09-20 17:58:56.396  3432  4606 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 17:58:56.396  3432  4606 D PowerManagerService: mDisplayReady: false
09-20 17:58:56.396  3432  4606 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 17:58:56.396  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-20 17:58:56.396  3432  4606 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 17:58:56.396  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 17:58:56.396  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-20 17:58:56.396  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-20 17:58:56.396  3432  3573 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,09-20 17:58:56.406  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f7e183c00
09-20 17:58:56.396  3432  3552 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-20 17:58:56.406  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,09-20 17:58:56.396  3432  3552 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-20 17:58:56.426  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 17:58:56.426  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 17:58:56.426  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:58:56.426  3432  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 17:58:56.426  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:58:56.426  3432  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 17:58:56.426  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 17:58:56.426  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 17:58:56.426  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:58:56.426  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:58:56.426  3432  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 17:58:56.426  3432  3556 D PowerManagerService: mDisplayReady: true
09-20 17:58:56.426  3432  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 17:58:56.426  6208  6208 E CocktailBarPositionManager: Window direction: 0
09-20 17:58:56.426  6208  6208 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 17:58:56.436  9831  9831 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-20 17:58:56.446  3432  3460 V WindowStateAnimator: Finishing drawing window Window{9b715e5 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-20 17:58:56.456  9831  9831 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-20 17:58:56.456  3432  4752 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3432
09-20 17:58:56.456  3432  3552 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-20 17:58:56.456  3432  3432 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 17:58:56.456  3432  3552 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +921ms (total +1s387ms)
09-20 17:58:56.456  3432  3552 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5f40911 u0 com.test.thalitest/.MainActivity t75} time:183908
09-20 17:58:56.456  3432  3552 D ViewRootImpl: #3 mView = null
09-20 17:58:56.456  3008  3019 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
,09-20 17:58:56.466  3008  4630 I SurfaceFlinger: id=20 Removed uhalitest (-2/11)
,09-20 17:58:56.466  3432  3432 I KnoxTimeoutHandler: SD activityfalse
,09-20 17:58:56.466  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc28f10a8
,09-20 17:58:56.466  9831  9889 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-20 17:58:56.466  9831  9889 D libEGL  : eglInitialize EGLDisplay = 0xd9fff3f4
,09-20 17:58:56.466  3432  3970 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3432
,09-20 17:58:56.476  3432  4352 V WindowStateAnimator: Finishing drawing window Window{9b715e5 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-20 17:58:56.476  9831  9889 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-20 17:58:56.476  9831  9831 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f9f168a time:183925
,09-20 17:58:56.516  9831  9831 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9831
,09-20 17:58:56.556  3432  6458 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-20 17:58:56.576  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:56.626  3432  3432 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3432 (0x0)
09-20 17:58:56.626  3432  3432 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 17:58:56.626  3432  3432 D PowerManagerService: mDisplayReady: false
09-20 17:58:56.626  3432  3432 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 17:58:56.626  3432  3432 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 17:58:56.626  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-20 17:58:56.626  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 17:58:56.626  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:58:56.626  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:58:56.626  3432  3573 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-20 17:58:56.626  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f7e183c00
09-20 17:58:56.626  3432  3552 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-20 17:58:56.626  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-20 17:58:56.626  3432  3552 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-20 17:58:56.636  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 17:58:56.636  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 17:58:56.636  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:58:56.636  3432  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 17:58:56.636  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:58:56.636  3432  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 17:58:56.636  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 17:58:56.636  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 17:58:56.636  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:58:56.636  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:58:56.636  3432  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 17:58:56.636  3432  3556 D PowerManagerService: mDisplayReady: true
09-20 17:58:56.636  3432  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 17:58:56.646  6208  6208 E CocktailBarPositionManager: Window direction: 0
09-20 17:58:56.646  6208  6208 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 17:58:56.726  9831  9831 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-20 17:58:56.756  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:56.806  9831  9896 D jxcore_app_log: JniHelper::setJavaVM(0xf4eb4000), pthread_self() = -645400272
,09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea981f2 added. We now have 1 listener(s)
,09-20 17:58:56.816  9831  9896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
,09-20 17:58:56.816  9831  9896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-20 17:58:56.816  9831  9896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-20 17:58:56.816  9831  9896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-20 17:58:56.816  9831  9896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@374bff9 added. We now have 1 listener(s)
09-20 17:58:56.816  9831  9896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-20 17:58:56.826  9831  9896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-20 17:58:56.826  9831  9896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-20 17:58:56.826  9831  9896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-20 17:58:56.826  9831  9896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-20 17:58:56.826  9831  9896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-20 17:58:56.826  9831  9896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 17:58:56.826  9831  9896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
,09-20 17:58:56.836  9831  9896 D BluetoothAdapter: STATE_ON
,09-20 17:58:56.836  9831  9896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-20 17:58:56.836  9831  9896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 17:58:56.836  9831  9896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 17:58:56.836  9831  9896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 17:58:56.836  9831  9896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 17:58:56.836  9831  9896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 17:58:56.836  9831  9896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 17:58:56.836  9831  9896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 17:58:56.836  9831  9896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-20 17:58:56.836  9831  9896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-20 17:58:56.836  9831  9896 D io.jxcore.node.ConnectivityMonitor: start: OK
09-20 17:58:56.836  9831  9896 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-20 17:58:56.836  9831  9831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 17:58:56.846  9831  9831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 17:58:56.856  9831  9831 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-20 17:58:56.936  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:57.036  4027  4027 D Recents : onTaskStackChanged
,09-20 17:58:57.046  4027  4027 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-20 17:58:57.056  4027  4027 D ResourcesManager: For user 0 new overlays fetched Null
,09-20 17:58:57.116  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:57.186  9831  9897 W jxcore-log: Initializing JXcore engine
09-20 17:58:57.186  9831  9897 W jxcore-log: JXcore engine is ready
,09-20 17:58:57.206  5058  5058 E audit   : type=1400 msg=audit(1474387137.206:264): avc:  denied  { ioctl } for  pid=9897 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1176 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-20 17:58:57.206  5058  5058 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-20 17:58:57.206  5058  5058 E audit   : type=1300 msg=audit(1474387137.206:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d977a3c8 items=0 ppid=3177 pid=9897 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-20 17:58:57.206  5058  5058 E audit   : type=1327 msg=audit(1474387137.206:264): proctitle="com.test.thalitest"
09-20 17:58:57.206  5058  5058 E audit   : type=1320 msg=audit(1474387137.206:264): 
09-20 17:58:57.206  5058  5058 E audit   : type=1400 msg=audit(1474387137.206:265): avc:  denied  { ioctl } for  pid=9897 comm="Thread-160" path="socket:[34204]" dev="sockfs" ino=34204 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-20 17:58:57.206  5058  5058 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-20 17:58:57.206  5058  5058 E audit   : type=1300 msg=audit(1474387137.206:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d977a3c8 items=0 ppid=3177 pid=9897 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-20 17:58:57.206  5058  5058 E audit   : type=1327 msg=audit(1474387137.206:265): proctitle="com.test.thalitest"
09-20 17:58:57.206  5058  5058 E audit   : type=1320 msg=audit(1474387137.206:265): 
,09-20 17:58:57.206  9831  9897 W jxcore-log: Starting JXcore engine
,09-20 17:58:57.246  9831  9897 W jxcore-log: Platform android
09-20 17:58:57.246  9831  9897 W jxcore-log: 
09-20 17:58:57.246  9831  9897 W jxcore-log: Process ARCH arm
09-20 17:58:57.246  9831  9897 W jxcore-log: 
,09-20 17:58:57.296  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:57.326  9831  9897 I jxcore-log: JXcore Cordova bridge is ready!
09-20 17:58:57.326  9831  9897 I jxcore-log: 
09-20 17:58:57.326  9831  9897 W jxcore-log: JXcore engine is started
,09-20 17:58:57.326  9831  9896 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-20 17:58:57.336  9831  9831 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-20 17:58:57.476  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:57.656  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:57.836  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:58.016  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:58.086  3432  3908 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/75_task.xml.bak
,09-20 17:58:58.196  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:58.376  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:58.556  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:58.566  3432  6457 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-20 17:58:58.736  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:58.916  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:59.096  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:59.276  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:59.456  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:59.636  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:59.816  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:58:59.996  3432  3818 V AlarmManager: Expired Alarm result :8
,09-20 17:58:59.996  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:00.176  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:00.356  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:00.536  3432  3818 V AlarmManager: Expired Alarm result :4
,09-20 17:59:00.536  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:00.536  3432  3818 V AlarmManager: Send whitelist package alarm :PendingIntent{a7f7916: PendingIntentRecord{be63d0d com.samsung.android.app.aodservice broadcastIntent}}
,09-20 17:59:00.546  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-20 17:59:00.546  3939  3939 D KeyguardUpdateMonitor: handleTimeUpdate
,09-20 17:59:00.556  3939  3939 D Clock   : received broadcast android.intent.action.TIME_TICK
,09-20 17:59:00.616  3939  3939 D DateView: received broadcast android.intent.action.TIME_TICK
,09-20 17:59:00.656  7950  7950 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,09-20 17:59:00.656  7950  7950 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-20 17:59:00.666  4753  4753 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
09-20 17:59:00.666  4753  4753 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,09-20 17:59:00.666  3432  4352 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-20 17:59:00.666  3432  4352 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
,09-20 17:59:00.666  3432  4352 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
09-20 17:59:00.666  3432  4352 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
09-20 17:59:00.666  3166  3166 D Sensorhubs: sendContextData: -72, 56, 1, 1
,09-20 17:59:00.676  3432  4352 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-20 17:59:00.676  3432  4352 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-20 17:59:00.676  3432  4352 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
09-20 17:59:00.676  4753  4753 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@db6f041, service=Device Physical Context Monitor
09-20 17:59:00.676  4753  4753 I AlpmModeManager: startAlpmMode : state  = BLANK
09-20 17:59:00.676  4753  4753 D DefaultClockView: Window showed. Time views updating
09-20 17:59:00.676  3432  4416 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3432
09-20 17:59:00.676  3432  4416 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 17:59:00.676  3432  4416 D PowerManagerService: mDisplayReady: false
09-20 17:59:00.676  3432  4416 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 17:59:00.676  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 17:59:00.676  4753  4753 D AODUpdatePositionController: updatePosition: direction[6] updatePosition: X[-3] Y[741] NewPositionTimer[57]
09-20 17:59:00.676  3432  4416 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 17:59:00.676  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 17:59:00.676  3008  3008 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f7e183c00
09-20 17:59:00.676  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:59:00.676  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-20 17:59:00.676  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:59:00.676  4753  4753 D DefaultClockView: LocalTime Pattern : HH:mm
09-20 17:59:00.676  3432  3573 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-20 17:59:00.676  3432  3552 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-20 17:59:00.676  3432  3552 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-20 17:59:00.676  4753  4753 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 17:59 time02: null ampm: null
,09-20 17:59:00.696  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 17:59:00.696  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 17:59:00.696  3432  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 17:59:00.696  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:59:00.696  3432  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 17:59:00.696  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:59:00.696  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 17:59:00.696  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 17:59:00.696  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:59:00.696  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:59:00.696  3432  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 17:59:00.696  3432  3556 D PowerManagerService: mDisplayReady: true
09-20 17:59:00.696  3432  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-20 17:59:00.696  6208  6208 E CocktailBarPositionManager: Window direction: 0
09-20 17:59:00.696  6208  6208 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-20 17:59:00.706  4753  4753 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
09-20 17:59:00.706  4753  4753 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
09-20 17:59:00.706  4753  4753 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:wt., 20 wrz 17:59
09-20 17:59:00.706  4753  4753 I AODService.ClockTimer: startAlarm : TICK
09-20 17:59:00.706  3432  5011 V AlarmManager: Add whitelist package alarm :PendingIntent{ddcd90c: PendingIntentRecord{be63d0d com.samsung.android.app.aodservice broadcastIntent}}
09-20 17:59:00.706  4753  4753 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
09-20 17:59:00.706  4753  4753 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
09-20 17:59:00.706  3432  3970 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
09-20 17:59:00.706  3432  3970 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
09-20 17:59:00.706  3432  5013 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3432
09-20 17:59:00.706  4753  4753 D DefaultClockView: RootView invalidate()
09-20 17:59:00.706  3432  3979 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3432
,09-20 17:59:00.716  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 17:59:00.716  3166  3211 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
09-20 17:59:00.716  3432  3821 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
09-20 17:59:00.716  3432  3820 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 15, 59, 0,
09-20 17:59:00.716  3432  3820 D SensorHubManager: SendSensorHubData: send data = -63, 14, 15, 59, 0
09-20 17:59:00.716  3166  3212 D Sensorhubs: sendContextData: -63, 14, 15, 59, 0
09-20 17:59:00.716  3432  3820 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
09-20 17:59:00.716  3432  3820 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
09-20 17:59:00.716  3432  3820 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
09-20 17:59:00.726  3432  3820 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
09-20 17:59:00.726  3432  3820 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
09-20 17:59:00.726  3432  3823 D SContextService: updateSContext() : event = Device Physical Context Monitor
09-20 17:59:00.726  4753  4753 I AODService: onSContextChanged: AODScreenShown state is already true
,09-20 17:59:00.856  3432  3432 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3432 (0x0)
,09-20 17:59:00.866  3432  3432 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 17:59:00.866  3432  3432 D PowerManagerService: mDisplayReady: false
09-20 17:59:00.866  3432  3432 I libsuspend: !@autosuspend_wakeup_count_disable done
,09-20 17:59:00.866  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 17:59:00.866  3432  3432 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 17:59:00.866  3008  3008 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f7e183c00
,09-20 17:59:00.866  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 17:59:00.866  3008  3008 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-20 17:59:00.866  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-20 17:59:00.866  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:59:00.866  3432  3573 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-20 17:59:00.866  3432  3552 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-20 17:59:00.866  3432  3552 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-20 17:59:00.886  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-20 17:59:00.886  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 17:59:00.886  3432  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 17:59:00.886  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:59:00.886  3432  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
,09-20 17:59:00.886  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:59:00.886  3432  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 17:59:00.886  3432  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,09-20 17:59:00.886  3432  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 17:59:00.886  3432  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 17:59:00.886  3432  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,09-20 17:59:00.886  3432  3556 D PowerManagerService: mDisplayReady: true
,09-20 17:59:00.886  3432  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 17:59:00.896  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:00.896  6208  6208 E CocktailBarPositionManager: Window direction: 0
,09-20 17:59:00.896  6208  6208 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 17:59:01.076  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:01.256  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:01.436  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:01.616  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:01.626  3432  6457 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-20 17:59:01.796  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:01.976  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:02.156  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:02.336  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:02.516  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:02.696  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:02.876  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:03.056  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:03.236  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:03.416  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:03.426  9831  9897 I jxcore-log: 2016-09-20 15:59:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-20 17:59:03.426  9831  9897 I jxcore-log: 
,09-20 17:59:03.426  9831  9897 I jxcore-log: 2016-09-20 15:59:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-20 17:59:03.426  9831  9897 I jxcore-log: 
,09-20 17:59:03.436  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.446  9831  9897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 17:59:03.446  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 17:59:03.446  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 17:59:03.446  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 17:59:03.446  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 17:59:03.446  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 17:59:03.446  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 17:59:03.446  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 17:59:03.446  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.446  9831  9897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-20 17:59:03.446  9831  9897 I jxcore-log: 2016-09-20 15:59:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-20 17:59:03.446  9831  9897 I jxcore-log: 
,09-20 17:59:03.456  9831  9897 I jxcore-log: 2016-09-20 15:59:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-20 17:59:03.456  9831  9897 I jxcore-log: 
,09-20 17:59:03.556  8539  8564 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,09-20 17:59:03.596  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:03.606  9831  9897 I jxcore-log: Running unit tests
09-20 17:59:03.606  9831  9897 I jxcore-log: 
,09-20 17:59:03.606  9831  9897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-20 17:59:03.606  9831  9897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21dfa7e added. We now have 2 listener(s)
09-20 17:59:03.606  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-20 17:59:03.606  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-20 17:59:03.606  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-20 17:59:03.606  9831  9897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-20 17:59:03.606  9831  9897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48a3bdf added. We now have 2 listener(s)
09-20 17:59:03.606  9831  9897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-20 17:59:03.606  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-20 17:59:03.606  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-20 17:59:03.616  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.616  9831  9897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 17:59:03.616  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 17:59:03.616  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 17:59:03.616  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 17:59:03.616  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 17:59:03.616  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 17:59:03.616  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 17:59:03.616  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 17:59:03.626  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.626  9831  9897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-20 17:59:03.626  9831  9897 D io.jxcore.node.ConnectivityMonitor: start: OK
09-20 17:59:03.626  9831  9897 D executeNativeTests: Running unit tests
,09-20 17:59:03.636  9831  9831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 17:59:03.636  9831  9831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 17:59:03.666  9831  9897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-20 17:59:03.666  9831  9897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40b5b65 added. We now have 3 listener(s)
,09-20 17:59:03.666  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-20 17:59:03.666  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-20 17:59:03.666  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-20 17:59:03.666  9831  9897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-20 17:59:03.666  9831  9897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cce03a added. We now have 3 listener(s)
,09-20 17:59:03.666  9831  9897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-20 17:59:03.666  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-20 17:59:03.676  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-20 17:59:03.686  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.686  9831  9897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 17:59:03.686  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 17:59:03.686  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 17:59:03.686  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 17:59:03.686  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 17:59:03.686  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 17:59:03.686  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 17:59:03.686  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 17:59:03.686  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.696  9831  9897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-20 17:59:03.696  9831  9897 D io.jxcore.node.ConnectivityMonitor: start: OK
09-20 17:59:03.696  9831  9897 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-20 17:59:03.696  9831  9897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-20 17:59:03.696  9831  9897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-20 17:59:03.696  9831  9897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-20 17:59:03.696  9831  9897 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-20 17:59:03.696  9831  9897 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-20 17:59:03.696  9831  9897 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-20 17:59:03.696  9831  9897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-20 17:59:03.696  9831  9897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-20 17:59:03.696  9831  9897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-20 17:59:03.696  9831  9897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-20 17:59:03.696  9831  9897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-20 17:59:03.696  9831  9897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-20 17:59:03.696  9831  9897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-20 17:59:03.696  9831  9897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 17:59:03.696  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-20 17:59:03.696  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-20 17:59:03.696  9831  9897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40b5b65 removed from the list
09-20 17:59:03.696  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 17:59:03.696  9831  9897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cce03a removed from the list
,09-20 17:59:03.696  9831  9831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 17:59:03.696  9831  9897 D io.jxcore.node.ConnectivityMonitor: stop
09-20 17:59:03.696  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 17:59:03.696  9831  9897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 17:59:03.696  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-20 17:59:03.706  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-20 17:59:03.706  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-20 17:59:03.706  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 17:59:03.706  9831  9897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cce03a not in the list
,09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-20 17:59:03.706  9831  9897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-20 17:59:03.706  9831  9897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-20 17:59:03.706  9831  9897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-20 17:59:03.706  9831  9897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-20 17:59:03.706  9831  9897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 17:59:03.706  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 17:59:03.706  9831  9897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40b5b65 not in the list
09-20 17:59:03.706  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-20 17:59:03.706  9831  9897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cce03a not in the list
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectivityMonitor: stop
09-20 17:59:03.706  9831  9897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 17:59:03.706  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 17:59:03.706  9831  9897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-20 17:59:03.706  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 17:59:03.706  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-20 17:59:03.706  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-20 17:59:03.706  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 17:59:03.706  9831  9897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cce03a not in the list
,09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-20 17:59:03.706  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-20 17:59:03.716  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-20 17:59:03.716  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-20 17:59:03.716  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-20 17:59:03.716  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-20 17:59:03.716  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-20 17:59:03.716  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-20 17:59:03.716  9831  9897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-20 17:59:03.716  9831  9897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-20 17:59:03.716  9831  9897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-20 17:59:03.716  9831  9897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-20 17:59:03.716  9831  9897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-20 17:59:03.716  9831  9897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-20 17:59:03.716  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 17:59:03.716  9831  9897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40b5b65 not in the list
09-20 17:59:03.716  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 17:59:03.716  9831  9897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cce03a not in the list
09-20 17:59:03.716  9831  9897 D io.jxcore.node.ConnectivityMonitor: stop
09-20 17:59:03.716  9831  9897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 17:59:03.716  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 17:59:03.716  9831  9897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 17:59:03.716  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 17:59:03.716  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-20 17:59:03.716  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-20 17:59:03.716  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 17:59:03.716  9831  9897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cce03a not in the list
09-20 17:59:03.716  9831  9897 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-20 17:59:03.716  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-20 17:59:03.726  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.726  9831  9897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 17:59:03.726  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 17:59:03.726  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 17:59:03.726  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 17:59:03.726  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 17:59:03.726  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 17:59:03.726  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 17:59:03.726  9831  9897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 17:59:03.726  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.726  9831  9897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-20 17:59:03.726  9831  9897 D io.jxcore.node.ConnectivityMonitor: start: OK
09-20 17:59:03.726  9831  9897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-20 17:59:03.726  9831  9897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-20 17:59:03.726  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-20 17:59:03.726  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 17:59:03.726  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-20 17:59:03.736  9831  9831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 17:59:03.736  9831  9897 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-20 17:59:03.736  9831  9897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-20 17:59:03.736  9831  9831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 17:59:03.736  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.746  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.746  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.746  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-20 17:59:03.746  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.746  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.746  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-20 17:59:03.746  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-20 17:59:03.756  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.756  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.756  9831  9897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-20 17:59:03.756  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.756  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.766  9831  9897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-20 17:59:03.766  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-20 17:59:03.766  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-20 17:59:03.766  9831  9897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-20 17:59:03.766  9831  9897 D BluetoothLeScanner: Start Scan
,09-20 17:59:03.766  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.766  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.776  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:03.776  9831  9897 D BluetoothAdapter: STATE_ON
09-20 17:59:03.776  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:03.776  5048  5448 D BtGatt.GattService: registerClient() - UUID=01a621eb-2b44-4b8c-ac79-e6c4bcf24c57
,09-20 17:59:03.826  5048  5182 D BtGatt.GattService: onClientRegistered() - UUID=01a621eb-2b44-4b8c-ac79-e6c4bcf24c57, clientIf=7
,09-20 17:59:03.826  9831  9841 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-20 17:59:03.836  5048  5061 D BtGatt.GattService: start scan with filters
,09-20 17:59:03.836  5048  5061 D BtGatt.GattService: getScanSettings
,09-20 17:59:03.846  5048  5061 D BtGatt.GattService: Is it foreground application = true
,09-20 17:59:03.846  5048  5061 D BtGatt.GattService: not a background application
,09-20 17:59:03.846  5048  5061 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-20 17:59:03.856  5048  5061 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-20 17:59:03.856  5048  5061 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-20 17:59:03.856  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-20 17:59:03.856  5048  5255 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-20 17:59:03.866  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-20 17:59:03.866  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-20 17:59:03.866  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-20 17:59:03.866  5048  5243 D BtGatt.ScanManager: handling starting scan
09-20 17:59:03.866  5048  5255 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 20, currDate: 20
09-20 17:59:03.866  5048  5243 D BtGatt.ScanManager: isFilteringSupported
09-20 17:59:03.866  5048  5243 D BluetoothAdapter: enableStandAloneBleMode=
09-20 17:59:03.866  5048  5243 D BluetoothAdapter: STATE_ON
09-20 17:59:03.866  5048  5243 D BluetoothAdapter: STATE_ON
09-20 17:59:03.866  5048  5243 D BluetoothAdapter: STATE_ON
09-20 17:59:03.866  5048  5243 D BluetoothAdapter: STATE_ON
09-20 17:59:03.866  9831  9897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-20 17:59:03.876  9831  9897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-20 17:59:03.876  9831  9831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-20 17:59:03.876  5048  5243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb3c5d7
09-20 17:59:03.876  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-20 17:59:03.876  3432  4416 V AlarmManager:  remove PendingIntent] PendingIntent{6ea6709: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:03.886  5048  5182 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,09-20 17:59:03.886  5048  5182 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 17:59:03.886  5048  5255 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 37
,09-20 17:59:03.886  5048  5255 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-20 17:59:03.886  9831  9897 I io.jxcore.node.ConnectionHelper: start: OK
09-20 17:59:03.886  5048  5243 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
,09-20 17:59:03.886  3432  3460 V AlarmManager:  remove PendingIntent] PendingIntent{728cd0e: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
09-20 17:59:03.886  5048  5243 D BtGatt.ScanManager: High Rssi Filter value is = -128
,09-20 17:59:03.886  5048  5243 D BtGatt.ScanManager: Low Rssi Filter value is = -128
,09-20 17:59:03.886  5048  5243 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-20 17:59:03.896  5048  5182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
,09-20 17:59:03.896  5048  5182 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 1
09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24573119
,09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
,09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-20 17:59:03.896  3432  3979 V AlarmManager:  remove PendingIntent] PendingIntent{1adc32f: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
09-20 17:59:03.896  5048  5243 D BtGatt.ScanManager: Starting BLE batch scan
09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-20 17:59:03.896  5048  5243 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-20 17:59:03.896  5048  5255 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24573119
,09-20 17:59:03.896  5048  5182 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,09-20 17:59:03.896  5048  5182 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-20 17:59:03.906  5048  5182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,09-20 17:59:03.906  5048  5182 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 17:59:03.906  3432  3970 V AlarmManager:  remove PendingIntent] PendingIntent{dce9d3c: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:03.906  3432  4351 V AlarmManager:  remove PendingIntent] PendingIntent{d496ac5: PendingIntentRecord{28ac1a com.android.bluetooth broadcastIntent}}
,09-20 17:59:03.906  3432  4152 V AlarmManager:  remove PendingIntent] PendingIntent{bdd634b: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:03.916  3432  3460 V AlarmManager:  remove PendingIntent] PendingIntent{8865128: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:03.926  3432  5011 V AlarmManager:  remove PendingIntent] PendingIntent{adaee41: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:03.926  3432  4351 V AlarmManager:  remove PendingIntent] PendingIntent{b156fe6: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:03.936  3432  4458 V AlarmManager:  remove PendingIntent] PendingIntent{21ce927: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:03.936  3432  4352 V AlarmManager:  remove PendingIntent] PendingIntent{8357d4: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:03.946  3432  4606 V AlarmManager:  remove PendingIntent] PendingIntent{ea72d7d: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:03.946  3432  5011 V AlarmManager:  remove PendingIntent] PendingIntent{8b8a472: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:03.956  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:04.096  3432  6496 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-20 17:59:04.136  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:04.316  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:04.376  9831  9831 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-20 17:59:04.376  9831  9831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-20 17:59:04.376  9831  9831 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-20 17:59:04.496  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:04.676  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:04.856  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:04.906  3432  3818 V AlarmManager: Expired Alarm result :4
,09-20 17:59:04.906  5048  5048 D BtGatt.ScanManager: awakened up at time 192358
,09-20 17:59:04.916  5048  5243 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 17:59:04.916  3432  4416 V AlarmManager:  remove PendingIntent] PendingIntent{ea81d40: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:04.916  5048  5182 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
,09-20 17:59:04.916  5048  5182 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-20 17:59:04.916  5048  5182 D BtGatt.GattService: current time is 192368572900
09-20 17:59:04.916  5048  5182 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -75, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -78, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -78, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,09-20 17:59:04.926  3432  4458 V AlarmManager:  remove PendingIntent] PendingIntent{5fe2479: PendingIntentRecord{28ac1a com.android.bluetooth broadcastIntent}}
,09-20 17:59:04.926  5048  5182 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-20 17:59:04.926  5048  5182 D ScanRecord: parseFromBytes
09-20 17:59:04.926  5048  5182 D ScanRecord: first manudata for manu ID
,09-20 17:59:04.926  5048  5182 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-20 17:59:04.926  5048  5182 D ScanRecord: parseFromBytes
09-20 17:59:04.926  5048  5182 D ScanRecord: first manudata for manu ID
09-20 17:59:04.926  5048  5182 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-20 17:59:04.926  5048  5182 D ScanRecord: parseFromBytes
09-20 17:59:04.926  5048  5182 D ScanRecord: first manudata for manu ID
,09-20 17:59:04.936  9831  9842 D ScanRecord: parseFromBytes
,09-20 17:59:04.936  9831  9842 D ScanRecord: first manudata for manu ID
,09-20 17:59:04.936  9831  9842 D ScanRecord: parseFromBytes
,09-20 17:59:04.936  9831  9842 D ScanRecord: first manudata for manu ID
09-20 17:59:04.936  3432  4752 V AlarmManager:  remove PendingIntent] PendingIntent{ae895be: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
09-20 17:59:04.936  9831  9842 D ScanRecord: parseFromBytes
09-20 17:59:04.936  9831  9842 D ScanRecord: first manudata for manu ID
,09-20 17:59:04.946  3432  5013 V AlarmManager:  remove PendingIntent] PendingIntent{19bd61f: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:04.946  3432  4059 V AlarmManager:  remove PendingIntent] PendingIntent{591cd6c: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:04.956  3432  4351 V AlarmManager:  remove PendingIntent] PendingIntent{9338f35: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:04.966  3432  4254 V AlarmManager:  remove PendingIntent] PendingIntent{8944fca: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:05.036  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:05.126  3432  3581 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-20 17:59:05.146  3432  3581 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-20 17:59:05.216  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:05.396  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:05.576  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:05.756  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:05.826  3432  4153 E Watchdog: !@Sync 6 [09-20 17:59:05.837]
,09-20 17:59:05.926  3432  3818 V AlarmManager: Expired Alarm result :4
,09-20 17:59:05.926  5048  5048 D BtGatt.ScanManager: awakened up at time 193377
,09-20 17:59:05.926  5048  5243 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 17:59:05.936  3432  4606 V AlarmManager:  remove PendingIntent] PendingIntent{2845458: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:05.936  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:05.936  5048  5182 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-20 17:59:05.936  5048  5182 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 17:59:05.946  3432  3979 V AlarmManager:  remove PendingIntent] PendingIntent{81ae9b1: PendingIntentRecord{28ac1a com.android.bluetooth broadcastIntent}}
,09-20 17:59:05.956  3432  3970 V AlarmManager:  remove PendingIntent] PendingIntent{68f9e96: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:05.966  3432  4416 V AlarmManager:  remove PendingIntent] PendingIntent{b7c6a17: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:06.116  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:06.146  3432  6457 D SSRM:n  : SIOP:: AP = 320, PST = 269 (W:6), CP = 228, CUR = 6, LCD = 1
,09-20 17:59:06.296  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:06.476  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:06.656  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:06.836  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:06.946  3432  3818 V AlarmManager: Expired Alarm result :4
,09-20 17:59:06.946  5048  5048 D BtGatt.ScanManager: awakened up at time 194398
,09-20 17:59:06.956  5048  5243 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 17:59:06.956  3432  3979 V AlarmManager:  remove PendingIntent] PendingIntent{2436fed: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
09-20 17:59:06.956  5048  5182 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
,09-20 17:59:06.956  3432  5013 V AlarmManager:  remove PendingIntent] PendingIntent{11f0e22: PendingIntentRecord{28ac1a com.android.bluetooth broadcastIntent}}
,09-20 17:59:06.956  5048  5182 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 17:59:06.956  5048  5182 D BtGatt.GattService: current time is 194407673322
09-20 17:59:06.956  5048  5182 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -88, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -76, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-20 17:59:06.956  5048  5182 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-20 17:59:06.956  5048  5182 D ScanRecord: parseFromBytes
09-20 17:59:06.956  5048  5182 D ScanRecord: first manudata for manu ID
,09-20 17:59:06.956  5048  5182 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-20 17:59:06.956  5048  5182 D ScanRecord: parseFromBytes
09-20 17:59:06.956  5048  5182 D ScanRecord: first manudata for manu ID
09-20 17:59:06.966  9831  9842 D ScanRecord: parseFromBytes
,09-20 17:59:06.966  9831  9842 D ScanRecord: first manudata for manu ID
09-20 17:59:06.966  9831  9842 D ScanRecord: parseFromBytes
09-20 17:59:06.966  9831  9842 D ScanRecord: first manudata for manu ID
,09-20 17:59:06.986  3432  3970 V AlarmManager:  remove PendingIntent] PendingIntent{d390b3: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:06.986  3432  4416 V AlarmManager:  remove PendingIntent] PendingIntent{d9d5670: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:07.006  3432  4152 V AlarmManager:  remove PendingIntent] PendingIntent{6f41de9: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:07.016  3432  4752 V AlarmManager:  remove PendingIntent] PendingIntent{243ea6e: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:07.016  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:07.026  3432  3460 V AlarmManager:  remove PendingIntent] PendingIntent{76c850f: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:07.196  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:07.256  4427  4481 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-20 17:59:07.256  4427  4481 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-20 17:59:07.376  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:07.556  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:07.736  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:07.916  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:07.966  3432  3818 V AlarmManager: Expired Alarm result :4
,09-20 17:59:07.966  5048  5048 D BtGatt.ScanManager: awakened up at time 195415
,09-20 17:59:07.966  5048  5243 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 17:59:07.976  3432  4351 V AlarmManager:  remove PendingIntent] PendingIntent{8e7afa5: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:07.976  5048  5182 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
09-20 17:59:07.976  5048  5182 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 17:59:07.976  5048  5182 D BtGatt.GattService: current time is 195425292514
09-20 17:59:07.976  5048  5182 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -74, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -79, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-20 17:59:07.976  3432  4458 V AlarmManager:  remove PendingIntent] PendingIntent{c83f7a: PendingIntentRecord{28ac1a com.android.bluetooth broadcastIntent}}
,09-20 17:59:07.976  5048  5182 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-20 17:59:07.976  5048  5182 D ScanRecord: parseFromBytes
09-20 17:59:07.976  5048  5182 D ScanRecord: first manudata for manu ID
09-20 17:59:07.976  5048  5182 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-20 17:59:07.976  5048  5182 D ScanRecord: parseFromBytes
09-20 17:59:07.976  5048  5182 D ScanRecord: first manudata for manu ID
,09-20 17:59:07.986  5048  5182 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-20 17:59:07.986  5048  5182 D ScanRecord: parseFromBytes
09-20 17:59:07.986  5048  5182 D ScanRecord: first manudata for manu ID
09-20 17:59:07.986  9831  9841 D ScanRecord: parseFromBytes
,09-20 17:59:07.986  9831  9841 D ScanRecord: first manudata for manu ID
09-20 17:59:07.986  9831  9841 D ScanRecord: parseFromBytes
09-20 17:59:07.986  9831  9841 D ScanRecord: first manudata for manu ID
09-20 17:59:07.986  9831  9841 D ScanRecord: parseFromBytes
,09-20 17:59:07.986  9831  9841 D ScanRecord: first manudata for manu ID
,09-20 17:59:07.996  3432  4063 V AlarmManager:  remove PendingIntent] PendingIntent{af6632b: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.006  3432  3979 V AlarmManager:  remove PendingIntent] PendingIntent{b618388: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.006  3432  4352 V AlarmManager:  remove PendingIntent] PendingIntent{1c8a121: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.016  3432  3970 V AlarmManager:  remove PendingIntent] PendingIntent{40ad946: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.016  3432  4059 V AlarmManager:  remove PendingIntent] PendingIntent{8f60707: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.096  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:08.276  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:08.456  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:08.636  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:08.816  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:08.896  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:08.896  9831  9897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-20 17:59:08.906  9831  9897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-20 17:59:08.906  9831  9897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-20 17:59:08.906  9831  9897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 17:59:08.906  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-20 17:59:08.906  9831  9897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-20 17:59:08.906  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-20 17:59:08.906  9831  9897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-20 17:59:08.906  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-20 17:59:08.906  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-20 17:59:08.906  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-20 17:59:08.906  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:08.916  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:08.916  9831  9897 D BluetoothLeScanner: Stop Scan
,09-20 17:59:08.926  5048  5062 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-20 17:59:08.926  5048  5062 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-20 17:59:08.926  5048  5062 D BtGatt.GattService: stopScan() - queue size =1
09-20 17:59:08.926  5048  5255 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-20 17:59:08.926  5048  5255 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 20, currDate: 20
09-20 17:59:08.926  5048  5255 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-20 17:59:08.926  5048  5255 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-20 17:59:08.926  5048  5255 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
09-20 17:59:08.926  5048  5243 D BtGatt.ScanManager: filter size is 1
09-20 17:59:08.926  5048  5255 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-20 17:59:08.926  5048  5255 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-20 17:59:08.926  5048  5243 D BtGatt.ScanManager: delete FilterIndex - 3
,09-20 17:59:08.926  5048  5062 D BtGatt.GattService: unregisterClient() - clientIf=7
09-20 17:59:08.926  3432  4458 V AlarmManager:  remove PendingIntent] PendingIntent{d4f5034: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.926  5048  5182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
,09-20 17:59:08.926  5048  5182 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-20 17:59:08.936  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-20 17:59:08.936  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-20 17:59:08.936  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-20 17:59:08.936  5048  5243 D BtGatt.ScanManager: stopping BLe Batch
09-20 17:59:08.936  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-20 17:59:08.936  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-20 17:59:08.936  5048  5182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-20 17:59:08.936  5048  5182 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 17:59:08.936  5048  5243 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 17:59:08.936  5048  5182 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,09-20 17:59:08.936  5048  5182 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-20 17:59:08.946  9831  9897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-20 17:59:08.946  3432  4606 V AlarmManager:  remove PendingIntent] PendingIntent{16d2e5d: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
09-20 17:59:08.946  3432  4752 V AlarmManager:  remove PendingIntent] PendingIntent{88b43d2: PendingIntentRecord{28ac1a com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.946  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:08.946  3432  4606 V AlarmManager:  remove PendingIntent] PendingIntent{8620ca3: PendingIntentRecord{28ac1a com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.946  9831  9897 D BluetoothAdapter: STATE_ON
,09-20 17:59:08.946  9831  9897 D BluetoothLeAdvertiser: stop advertising
09-20 17:59:08.946  9831  9897 D BluetoothLeAdvertiser: wrapper is null
09-20 17:59:08.946  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-20 17:59:08.946  9831  9897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-20 17:59:08.946  9831  9897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-20 17:59:08.956  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-20 17:59:08.956  3432  4254 V AlarmManager:  remove PendingIntent] PendingIntent{aab3ba0: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.956  9831  9831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-20 17:59:08.956  9831  9897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-20 17:59:08.956  9831  9831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 17:59:08.956  9831  9831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-20 17:59:08.956  9831  9897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 17:59:08.956  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-20 17:59:08.956  9831  9897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40b5b65 not in the list
,09-20 17:59:08.956  9831  9897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 17:59:08.956  9831  9897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cce03a not in the list
09-20 17:59:08.956  9831  9897 D io.jxcore.node.ConnectivityMonitor: stop
,09-20 17:59:08.956  9831  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-20 17:59:08.966  3432  4152 V AlarmManager:  remove PendingIntent] PendingIntent{41871cc: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.966  9831  9831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-20 17:59:08.966  9831  9831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-20 17:59:08.966  9831  9831 D BluetoothAdapter: STATE_ON
,09-20 17:59:08.976  9831  9831 D BluetoothAdapter: STATE_ON
,09-20 17:59:08.976  9831  9831 D BluetoothAdapter: STATE_ON
,09-20 17:59:08.976  3432  3970 V AlarmManager:  remove PendingIntent] PendingIntent{dccc15: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.976  9831  9831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-20 17:59:08.976  3432  5013 V AlarmManager:  remove PendingIntent] PendingIntent{16f7b2a: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.976  9831  9831 D BluetoothAdapter: STATE_ON
,09-20 17:59:08.976  9831  9831 D BluetoothAdapter: STATE_ON
09-20 17:59:08.976  9831  9831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-20 17:59:08.976  9831  9831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-20 17:59:08.976  9831  9831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-20 17:59:08.986  9831  9831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-20 17:59:08.986  3432  3970 V AlarmManager:  remove PendingIntent] PendingIntent{7a6d1b: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.986  9831  9831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-20 17:59:08.986  9831  9831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 17:59:08.986  9831  9831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-20 17:59:08.996  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:08.996  3432  4254 V AlarmManager:  remove PendingIntent] PendingIntent{348bff7: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.996  9831  9831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-20 17:59:08.996  9831  9831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-20 17:59:08.996  9831  9831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-20 17:59:08.996  3432  3970 V AlarmManager:  remove PendingIntent] PendingIntent{812e64: PendingIntentRecord{2b95a7e com.android.bluetooth broadcastIntent}}
,09-20 17:59:08.996  9831  9831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-20 17:59:09.176  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:09.356  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:09.506  9831  9831 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-20 17:59:09.536  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:09.716  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:09.896  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:10.076  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:10.256  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:10.436  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:10.616  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:10.796  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:10.976  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:11.156  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:11.336  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:11.516  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:11.696  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:11.876  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:12.056  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:12.236  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:12.416  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:12.596  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:12.776  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:12.956  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:13.136  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:13.316  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:13.496  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 17:59:13.676  3432  3797 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
