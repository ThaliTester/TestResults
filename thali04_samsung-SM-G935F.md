#### Test 85615572904a9e7_thali04_samsung-SM-G935F Logs


```
--------- beginning of main
09-20 13:33:52.687  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,--------- beginning of system
09-20 13:33:52.797  3388  6494 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-20 13:33:52.867  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:33:53.047  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:33:53.227  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:33:53.257  9812  9812 I FIPS_bssl: FIPS approved mode (1) | 9812 | app_process
09-20 13:33:53.257  9812  9812 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-20 13:33:53.267  9812  9812 D AndroidRuntime: CheckJNI is OFF
09-20 13:33:53.267  9812  9812 D AndroidRuntime: readGMSProperty: start
09-20 13:33:53.267  9812  9812 D AndroidRuntime: readGMSProperty: already setted!!
09-20 13:33:53.267  9812  9812 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-20 13:33:53.267  9812  9812 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-20 13:33:53.267  9812  9812 D AndroidRuntime: readGMSProperty: end
09-20 13:33:53.267  9812  9812 D AndroidRuntime: addProductProperty: start
09-20 13:33:53.287  9812  9812 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-20 13:33:53.307  9812  9812 I Radio-JNI: register_android_hardware_Radio DONE
09-20 13:33:53.307  9812  9812 E AffinityControl: AffinityControl: registerfunction enter
09-20 13:33:53.317  9812  9812 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-20 13:33:53.347  3388  4587 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
09-20 13:33:53.347  3388  4587 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-20 13:33:53.367  3388  4587 D ResourcesManager: For user 0 new overlays fetched Null
09-20 13:33:53.367  3388  4587 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:33:53.367  3388  4587 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-20 13:33:53.377  3388  4587 D ActivityManager: mDVFSHelper.acquire()
09-20 13:33:53.377  3388  4587 V WindowManager: addAppToken: AppWindowToken{d075e139f token=Token{7f593e ActivityRecord{76fc5f9 u0 com.test.thalitest/.MainActivity t75}}} to stack=2 task=75 at 0
09-20 13:33:53.387  3388  3521 I InjectionManager: Inside getClassLibPath caller 
09-20 13:33:53.397  3388  3521 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-20 13:33:53.397  3388  3521 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{498d797 V.E...... R.....ID 0,0-0,0}
09-20 13:33:53.397  9821  9821 E Zygote  : v2
09-20 13:33:53.397  9821  9821 I libpersona: KNOX_SDCARD checking this for 10177
09-20 13:33:53.397  9821  9821 I libpersona: KNOX_SDCARD not a persona
09-20 13:33:53.397  9821  9821 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-20 13:33:53.397  3388  3521 W WindowManager: Failed looking up window
09-20 13:33:53.397  3388  3521 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@c8dfd84 does not exist
09-20 13:33:53.397  3388  3521 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 13:33:53.397  3388  3521 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-20 13:33:53.397  3388  3521 D ISSUE_DEBUG: InputChannelName : 3cb596d Starting com.test.thalitest
09-20 13:33:53.397  9821  9821 E Zygote  : accessInfo : 0
09-20 13:33:53.397  9821  9821 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-20 13:33:53.407  3388  4587 I ActivityManager: Start proc 9821:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-20 13:33:53.407  3388  4587 D InputDispatcher: Focused application set to: xxxx
09-20 13:33:53.407  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:33:53.407  9812  9812 D AndroidRuntime: Shutting down VM
09-20 13:33:53.407  3388  3853 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-20 13:33:53.407  3007  3007 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-20 13:33:53.437  9821  9821 D TimaKeyStoreProvider: TimaSignature is unavailable
09-20 13:33:53.437  9821  9821 D ActivityThread: Added TimaKeyStore provider
09-20 13:33:53.437  6535  6535 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 13:33:53.447  3388  4062 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3388
09-20 13:33:53.447  3388  4062 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 13:33:53.447  3388  4062 D PowerManagerService: mDisplayReady: false
09-20 13:33:53.447  3388  4062 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 13:33:53.447  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:33:53.447  6535  6535 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 13:33:53.447  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:33:53.447  3007  3007 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa8b03c00
09-20 13:33:53.447  3388  4062 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 13:33:53.447  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-20 13:33:53.447  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:33:53.447  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:33:53.447  3388  3535 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-20 13:33:53.447  3388  4409 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3388
09-20 13:33:53.457  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:33:53.457  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:33:53.457  3388  3525 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 13:33:53.457  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:33:53.457  3388  3525 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 13:33:53.457  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:33:53.457  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:33:53.457  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:33:53.457  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:33:53.457  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:33:53.457  3388  3525 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 13:33:53.457  3388  3525 D PowerManagerService: mDisplayReady: true
09-20 13:33:53.457  3388  3525 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-20 13:33:53.457  3388  3433 D ActivityManager:  Launching com.test.thalitest, updated priority
09-20 13:33:53.467  4310  4310 V ActivityThread: updateVisibility : ActivityRecord{aa80487 token=android.os.BinderProxy@4e12117 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-20 13:33:53.467  6193  6203 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-20 13:33:53.467  3388  3388 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-20 13:33:53.477  3388  4587 V WindowStateAnimator: Finishing drawing window Window{3ad2f65 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-20 13:33:53.477  3388  3496 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-20 13:33:53.487  3007  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fa85fee78
09-20 13:33:53.487  3007  3018 D libEGL  : eglTerminate EGLDisplay = 0x7fa85fee78
09-20 13:33:53.497  3007  4193 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-20 13:33:53.497  3007  3016 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-20 13:33:53.497  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc151cb48
09-20 13:33:53.507  4310  4310 D Launcher: onTrimMemory. Level: 20
09-20 13:33:53.507  3388  4162 V WindowStateAnimator: Finishing drawing window Window{1308ecf u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-20 13:33:53.507  6535  6535 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 13:33:53.507  6535  6535 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 13:33:53.507  6535  6535 V ActivityThread: updateVisibility : ActivityRecord{2715c9a token=android.os.BinderProxy@86f586c {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-20 13:33:53.507  3007  3016 I SurfaceFlinger: id=18 Removed VSBConnecti (7/12)
09-20 13:33:53.507  3007  3854 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/12)
09-20 13:33:53.517  3007  3854 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
09-20 13:33:53.517  3007  3018 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
09-20 13:33:53.517  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc151cb48
09-20 13:33:53.517  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc151cb18
09-20 13:33:53.517  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc151cb48
09-20 13:33:53.587  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:33:53.597  3388  3388 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3388 (0x0)
09-20 13:33:53.597  3388  3388 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3388 (0x0)
09-20 13:33:53.597  3388  3388 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 13:33:53.597  3388  3388 D PowerManagerService: mDisplayReady: false
09-20 13:33:53.597  3388  3388 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 13:33:53.597  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:33:53.597  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:33:53.597  3388  3388 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 13:33:53.597  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:33:53.597  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:33:53.597  3388  3535 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-20 13:33:53.607  3007  3007 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa8b03c00
09-20 13:33:53.607  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-20 13:33:53.607  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:33:53.607  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:33:53.607  3388  3525 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 13:33:53.607  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:33:53.607  3388  3525 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 13:33:53.607  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:33:53.607  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 13:33:53.607  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:33:53.607  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:33:53.607  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:33:53.607  3388  3525 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 13:33:53.607  3388  3525 D PowerManagerService: mDisplayReady: true
09-20 13:33:53.607  3388  3525 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 13:33:53.767  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:33:53.767  6193  6193 I TrayVisibilityController: handleMessage : msg.what = 1
09-20 13:33:53.807  3388  3433 I WindowManager: Screenshot max retries 4 of Token{7f593e ActivityRecord{76fc5f9 u0 com.test.thalitest/.MainActivity t75}} appWin=Window{3cb596d u0 d0 Starting com.test.thalitest} drawState=1
09-20 13:33:53.807  6193  6204 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-20 13:33:53.807  3388  3521 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:33:53.807  3388  3388 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:33:53.807  3388  3521 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-20 13:33:53.817  6193  6193 I Utils   : isCurrentUser current = 0, ownerId = 0
09-20 13:33:53.817  6193  6193 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-20 13:33:53.817  3388  3853 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-20 13:33:53.817  6193  6193 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-20 13:33:53.817  3388  6452 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:33:53.827  3388  6452 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:33:53.827  3388  3388 I KnoxTimeoutHandler: SD activityfalse
09-20 13:33:53.857  9821  9821 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-20 13:33:53.857  9821  9821 D RelationGraph: garbageCollect()
09-20 13:33:53.857  3388  6452 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 13:33:53.857  3388  3521 V WindowStateAnimator: Finishing drawing window Window{3cb596d u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-20 13:33:53.857  3388  3521 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:33:53.857  3388  3388 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 13:33:53.857  3388  3521 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{bce3571 u0 com.samsung.android.MtpApplication/.USBConnection t74} time:193028
09-20 13:33:53.857  3388  6452 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:33:53.857  3388  3521 D ActivityManager: mDVFSHelper.release()
09-20 13:33:53.857  3388  3388 I KnoxTimeoutHandler: SD activityfalse
09-20 13:33:53.867  9821  9821 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 13:33:53.867  3388  4623 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-20 13:33:53.867  9821  9821 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-20 13:33:53.867  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fc151ca28
09-20 13:33:53.877  3388  6452 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 13:33:53.877  3388  6452 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:33:53.877  3388  6452 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 13:33:53.877  9821  9821 D ResourcesManager: For user 0 new overlays fetched Null
09-20 13:33:53.887  9821  9821 I InjectionManager: Inside getClassLibPath caller 
09-20 13:33:53.897  9821  9821 D InjectionManager: InjectionManager
09-20 13:33:53.897  9821  9821 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-20 13:33:53.897  9821  9821 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-20 13:33:53.897  9821  9821 I InjectionManager: featureStore :{}
09-20 13:33:53.907  9821  9821 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 13:33:53.907  9821  9821 D RelationGraph: garbageCollect()
09-20 13:33:53.907  9821  9821 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 13:33:53.947  9821  9821 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-20 13:33:53.947  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:33:54.017  9821  9821 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-20 13:33:54.027  9821  9821 D ResourcesManager: For user 0 new overlays fetched Null
09-20 13:33:54.027  9821  9821 I InjectionManager: Inside getClassLibPath caller 
09-20 13:33:54.037  9821  9821 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-20 13:33:54.067  3388  3877 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-20 13:33:54.107  9821  9821 I cr_LibraryLoader: Time to load native libraries: 37 ms (timestamps 3237-3274)
09-20 13:33:54.107  9821  9821 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-20 13:33:54.107  3388  4126 E Watchdog: !@Sync 6 [09-20 13:33:54.122]
09-20 13:33:54.127  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:33:54.147  9821  9837 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-20 13:33:54.167  9821  9821 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {692d245}
09-20 13:33:54.167  9821  9821 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-20 13:33:54.177  3388  3877 I MdnieScenarioControlService: mGameModeLauncher : false
09-20 13:33:54.177  3388  3877 I MdnieScenarioControlService: setUIMode
09-20 13:33:54.187  9821  9821 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-20 13:33:54.217  9821  9821 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-20 13:33:54.297  3388  4169 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-20 13:33:54.297  3388  4169 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-20 13:33:54.297  3388  4169 D BatteryService: online:4, current avg:150, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:140
09-20 13:33:54.297  3388  4169 D BatteryService: stay LED for fully charged
09-20 13:33:54.297  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-20 13:33:54.307  3388  3388 I MotionRecognitionService: Plugged
09-20 13:33:54.307  3388  3388 D MotionRecognitionService:   cableConnection= 1
09-20 13:33:54.307  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-20 13:33:54.307  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
09-20 13:33:54.307  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:33:54.307  3388  3859 D WifiController: ApOrStaEnabledState  msg.what= 155652
09-20 13:33:54.307  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-20 13:33:54.307  3933  3933 D KeyguardUpdateMonitor: handleBatteryUpdate
09-20 13:33:54.307  3933  3933 D PowerUI : priorPlugType = 2 mPlugType =  2
09-20 13:33:54.317  5282  5282 D CommonServiceConfiguration: getStringValueSetting
09-20 13:33:54.317  5238  5238 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-20 13:33:54.317  5238  5543 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-20 13:33:54.327  5282  5282 D BatteryMonitor: new battery level: 100
09-20 13:33:54.327  3388  3496 W ActivityManager: Activity pause timeout for ActivityRecord{76fc5f9 u0 com.test.thalitest/.MainActivity t75}
09-20 13:33:54.327  4740  4740 D BatteryController: saveBatteryData : level[100], status[5]
09-20 13:33:54.327  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-20 13:33:54.327  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-20 13:33:54.347  9821  9821 D libEGL  : eglInitialize EGLDisplay = 0xffe0c37c
09-20 13:33:54.367  3388  6452 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:10), CP = 231, CUR = 150, LCD = 1
09-20 13:33:54.417  3388  4322 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
09-20 13:33:54.417  3388  4322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-20 13:33:54.487  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:33:54.487  9821  9821 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-20 13:33:54.507  9821  9821 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-20 13:33:54.507  9821  9821 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-20 13:33:54.537  9821  9821 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-20 13:33:54.587  9821  9821 D Activity: performCreate Call Injection manager
,09-20 13:33:54.597  9821  9821 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-20 13:33:54.607  9821  9821 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-20 13:33:54.617  9821  9821 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{29496ab I.E...... R.....ID 0,0-0,0}
,09-20 13:33:54.617  9821  9875 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-20 13:33:54.627  3388  4162 W WindowManager: Failed looking up window
09-20 13:33:54.627  3388  4162 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@93e8de4 does not exist
09-20 13:33:54.627  3388  4162 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 13:33:54.627  3388  4162 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 13:33:54.627  3388  4162 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 13:33:54.627  3388  4162 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-20 13:33:54.627  3388  4162 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-20 13:33:54.627  3388  4162 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-20 13:33:54.627  3388  4598 D ISSUE_DEBUG: InputChannelName : 136124d com.test.thalitest/com.test.thalitest.MainActivity
,09-20 13:33:54.627  3388  4322 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-20 13:33:54.627  3388  4322 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-20 13:33:54.627  3388  3388 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-20 13:33:54.637  3388  3388 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-20 13:33:54.637  9821  9821 V ActivityThread: updateVisibility : ActivityRecord{3a6c0a1 token=android.os.BinderProxy@f5e8d90 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-20 13:33:54.647  9821  9837 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-20 13:33:54.667  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:54.667  9821  9821 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9821
,09-20 13:33:54.667  3388  4322 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9821 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 13:33:54.667  3388  3865 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-20 13:33:54.667  3388  3865 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-20 13:33:54.677  3388  3865 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-20 13:33:54.677  3388  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 13:33:54.687  3388  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-20 13:33:54.687  9821  9821 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-20 13:33:54.687  3388  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-20 13:33:54.697  3388  3865 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-20 13:33:54.697  3388  3865 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-20 13:33:54.707  3007  3007 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,09-20 13:33:54.747  9821  9875 D libEGL  : eglInitialize EGLDisplay = 0xdc27f7c4
,09-20 13:33:54.747  9821  9875 I OpenGLRenderer: Initialized EGL, version 1.4
,09-20 13:33:54.757  9821  9875 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-20 13:33:54.757  3388  3434 I libsuspend: !@autosuspend_wakeup_count_disable
,09-20 13:33:54.757  3388  3434 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3388
09-20 13:33:54.757  3388  3434 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 13:33:54.757  3388  3434 D PowerManagerService: mDisplayReady: false
09-20 13:33:54.757  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:33:54.757  3007  3007 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa8b03c00
09-20 13:33:54.757  3388  3434 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 13:33:54.757  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-20 13:33:54.757  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:33:54.757  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:33:54.757  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:33:54.757  3388  3535 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-20 13:33:54.757  3388  3521 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-20 13:33:54.757  3388  3521 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-20 13:33:54.777  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-20 13:33:54.777  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:33:54.777  3388  3525 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 13:33:54.777  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:33:54.777  3388  3525 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 13:33:54.777  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:33:54.777  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:33:54.777  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:33:54.777  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:33:54.777  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:33:54.777  3388  3525 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 13:33:54.777  3388  3525 D PowerManagerService: mDisplayReady: true
09-20 13:33:54.777  3388  3525 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 13:33:54.787  6193  6193 E CocktailBarPositionManager: Window direction: 0
09-20 13:33:54.787  6193  6193 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 13:33:54.787  9821  9821 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-20 13:33:54.807  3388  4393 V WindowStateAnimator: Finishing drawing window Window{136124d u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-20 13:33:54.807  9821  9821 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-20 13:33:54.817  3388  3521 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 13:33:54.817  3388  3975 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3388
09-20 13:33:54.817  3388  3388 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 13:33:54.817  3388  3521 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s10ms (total +1s435ms)
09-20 13:33:54.817  3388  3521 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{76fc5f9 u0 com.test.thalitest/.MainActivity t75} time:193982
09-20 13:33:54.817  3388  3521 D ViewRootImpl: #3 mView = null
,09-20 13:33:54.817  3007  3854 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
09-20 13:33:54.817  3388  3388 I KnoxTimeoutHandler: SD activityfalse
,09-20 13:33:54.817  3007  3018 I SurfaceFlinger: id=20 Removed uhalitest (-2/11)
,09-20 13:33:54.817  3388  6453 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest,
,09-20 13:33:54.827  3388  4162 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3388
09-20 13:33:54.827  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc151cb48
09-20 13:33:54.827  9821  9879 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-20 13:33:54.827  9821  9879 D libEGL  : eglInitialize EGLDisplay = 0xda9ac3f4
,09-20 13:33:54.837  3388  4598 V WindowStateAnimator: Finishing drawing window Window{136124d u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-20 13:33:54.837  9821  9821 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f5e8d90 time:194003
,09-20 13:33:54.847  9821  9879 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-20 13:33:54.847  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:54.887  9821  9821 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9821
,09-20 13:33:54.977  3388  3388 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3388 (0x0)
,09-20 13:33:54.977  3388  3388 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 13:33:54.977  3388  3388 D PowerManagerService: mDisplayReady: false
09-20 13:33:54.977  3388  3388 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 13:33:54.977  3388  3388 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 13:33:54.977  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-20 13:33:54.977  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:33:54.977  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:33:54.977  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:33:54.977  3388  3535 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-20 13:33:54.977  3388  3521 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-20 13:33:54.977  3388  3521 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-20 13:33:54.977  3007  3007 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa8b03c00
,09-20 13:33:54.977  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,09-20 13:33:54.997  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-20 13:33:54.997  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:33:54.997  3388  3525 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 13:33:54.997  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:33:54.997  3388  3525 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 13:33:54.997  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:33:54.997  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-20 13:33:54.997  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:33:54.997  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:33:54.997  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:33:54.997  3388  3525 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 13:33:54.997  3388  3525 D PowerManagerService: mDisplayReady: true
,09-20 13:33:54.997  3388  3525 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 13:33:54.997  6193  6193 E CocktailBarPositionManager: Window direction: 0
09-20 13:33:54.997  6193  6193 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 13:33:55.027  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:55.067  9821  9821 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-20 13:33:55.167  9821  9886 D jxcore_app_log: JniHelper::setJavaVM(0xf49f4000), pthread_self() = -635700944
,09-20 13:33:55.167  9821  9886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-20 13:33:55.167  9821  9886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-20 13:33:55.167  9821  9886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-20 13:33:55.167  9821  9886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-20 13:33:55.167  9821  9886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-20 13:33:55.167  9821  9886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bcc809b added. We now have 1 listener(s)
,09-20 13:33:55.177  9821  9886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
09-20 13:33:55.177  9821  9886 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-20 13:33:55.177  9821  9886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-20 13:33:55.177  9821  9886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-20 13:33:55.177  9821  9886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bbe976 added. We now have 1 listener(s)
09-20 13:33:55.177  9821  9886 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-20 13:33:55.177  9821  9886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-20 13:33:55.177  9821  9886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-20 13:33:55.177  9821  9886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-20 13:33:55.177  9821  9886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-20 13:33:55.177  9821  9886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-20 13:33:55.187  9821  9886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 13:33:55.187  9821  9886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
,09-20 13:33:55.187  9821  9886 D BluetoothAdapter: STATE_ON
,09-20 13:33:55.197  9821  9886 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-20 13:33:55.197  9821  9886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 13:33:55.197  9821  9886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 13:33:55.197  9821  9886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 13:33:55.197  9821  9886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 13:33:55.197  9821  9886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 13:33:55.197  9821  9886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 13:33:55.197  9821  9886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 13:33:55.197  9821  9886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-20 13:33:55.197  9821  9886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-20 13:33:55.197  9821  9886 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-20 13:33:55.197  9821  9886 I io.jxcore.node.LifeCycleMonitor: start: OK
09-20 13:33:55.197  9821  9821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 13:33:55.207  9821  9821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 13:33:55.207  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:55.227  9821  9821 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-20 13:33:55.327  4025  4025 D Recents : onTaskStackChanged
,09-20 13:33:55.337  4025  4025 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-20 13:33:55.347  4025  4025 D ResourcesManager: For user 0 new overlays fetched Null
,09-20 13:33:55.387  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:55.567  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:55.607  4422  4474 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-20 13:33:55.607  4422  4474 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-20 13:33:55.617  9821  9887 W jxcore-log: Initializing JXcore engine
09-20 13:33:55.617  9821  9887 W jxcore-log: JXcore engine is ready
,09-20 13:33:55.637  5249  5249 E audit   : type=1400 msg=audit(1474371235.637:262): avc:  denied  { ioctl } for  pid=9887 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2227 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-20 13:33:55.637  5249  5249 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-20 13:33:55.637  5249  5249 E audit   : type=1300 msg=audit(1474371235.637:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=da0ba3c8 items=0 ppid=3176 pid=9887 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-20 13:33:55.637  5249  5249 E audit   : type=1327 msg=audit(1474371235.637:262): proctitle="com.test.thalitest"
09-20 13:33:55.637  5249  5249 E audit   : type=1320 msg=audit(1474371235.637:262): 
09-20 13:33:55.637  5249  5249 E audit   : type=1400 msg=audit(1474371235.637:263): avc:  denied  { ioctl } for  pid=9887 comm="Thread-160" path="socket:[10198]" dev="sockfs" ino=10198 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-20 13:33:55.637  5249  5249 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-20 13:33:55.637  5249  5249 E audit   : type=1300 msg=audit(1474371235.637:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=da0ba3c8 items=0 ppid=3176 pid=9887 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-20 13:33:55.637  5249  5249 E audit   : type=1327 msg=audit(1474371235.637:263): proctitle="com.test.thalitest"
09-20 13:33:55.637  5249  5249 E audit   : type=1320 msg=audit(1474371235.637:263): 
,09-20 13:33:55.637  9821  9887 W jxcore-log: Starting JXcore engine
,09-20 13:33:55.677  9821  9887 W jxcore-log: Platform android
09-20 13:33:55.677  9821  9887 W jxcore-log: 
09-20 13:33:55.677  9821  9887 W jxcore-log: Process ARCH arm
09-20 13:33:55.677  9821  9887 W jxcore-log: 
,09-20 13:33:55.747  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:55.747  9821  9887 I jxcore-log: JXcore Cordova bridge is ready!
09-20 13:33:55.747  9821  9887 I jxcore-log: 
09-20 13:33:55.747  9821  9887 W jxcore-log: JXcore engine is started
,09-20 13:33:55.757  9821  9886 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-20 13:33:55.757  9821  9821 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-20 13:33:55.927  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:56.107  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:56.287  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:56.387  3388  3903 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/75_task.xml.bak
,09-20 13:33:56.467  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:56.647  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:56.827  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:56.837  3388  6452 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-20 13:33:57.007  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:57.187  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:57.367  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:57.547  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:57.727  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:57.907  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:58.087  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:58.267  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:58.447  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:58.627  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:58.807  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:58.987  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:59.167  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:59.347  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:59.527  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:59.707  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:59.887  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:33:59.887  3388  6452 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-20 13:33:59.987  3388  3812 V AlarmManager: Expired Alarm result :8
,09-20 13:34:00.067  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:00.177  3388  3812 V AlarmManager: Expired Alarm result :4
,09-20 13:34:00.187  3388  3812 V AlarmManager: Send whitelist package alarm :PendingIntent{ae1bbd5: PendingIntentRecord{818d03b com.samsung.android.app.aodservice broadcastIntent}}
,09-20 13:34:00.187  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-20 13:34:00.187  3933  3933 D KeyguardUpdateMonitor: handleTimeUpdate
,09-20 13:34:00.207  3933  3933 D Clock   : received broadcast android.intent.action.TIME_TICK
,09-20 13:34:00.247  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:00.287  3933  3933 D DateView: received broadcast android.intent.action.TIME_TICK
,09-20 13:34:00.317  7907  7907 D [WeatherWidget(1240)]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,09-20 13:34:00.317  7907  7907 D [WeatherWidget(1240)]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,09-20 13:34:00.327  4740  4740 D AODService.ClockTimer: onReceive : com.samsung.android.app.aodservice.ClockTimer.TICK, mWakeUp = true
09-20 13:34:00.327  4740  4740 V BatteryController: getBatteryLevel[100.0], batteryStatus[5]
,09-20 13:34:00.327  3388  3850 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for DEVICE_PHYSICAL_CONTEXT_MONITOR
,09-20 13:34:00.327  3388  3850 I CAE     : setPropertyValue(DevicePhysicalContextMonitorRunner.java:155) - Get status
,09-20 13:34:00.327  3388  3850 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 56, 1, 1,
09-20 13:34:00.327  3388  3850 D SensorHubManager: SendSensorHubData: send data = -72, 56, 1, 1
09-20 13:34:00.327  3166  3166 D Sensorhubs: sendContextData: -72, 56, 1, 1
,09-20 13:34:00.337  3388  3850 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,09-20 13:34:00.337  3388  3850 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for DEVICE_PHYSICAL_CONTEXT_MONITOR
09-20 13:34:00.337  3388  3850 D SContextService: requestToUpdate() : service = Device Physical Context Monitor
09-20 13:34:00.337  4740  4740 D SContextManager:   .requestToUpdate : listener = com.samsung.android.app.aodservice.AODService$7@432f840, service=Device Physical Context Monitor
09-20 13:34:00.337  4740  4740 I AlpmModeManager: startAlpmMode : state  = BLANK
09-20 13:34:00.337  4740  4740 D DefaultClockView: Window showed. Time views updating
,09-20 13:34:00.337  3388  3975 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3388
09-20 13:34:00.337  3388  3975 I libsuspend: !@autosuspend_wakeup_count_disable
,09-20 13:34:00.337  3388  3975 D PowerManagerService: mDisplayReady: false
09-20 13:34:00.337  3388  3975 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 13:34:00.337  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:34:00.337  3388  3975 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,09-20 13:34:00.337  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:34:00.347  3007  3007 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa8b03c00
,09-20 13:34:00.337  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:34:00.347  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-20 13:34:00.337  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:34:00.347  3388  3535 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-20 13:34:00.347  3388  3521 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
,09-20 13:34:00.347  3388  3521 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-20 13:34:00.357  4740  4740 D AODUpdatePositionController: updatePosition: direction[2] updatePosition: X[-23] Y[313] NewPositionTimer[57]
,09-20 13:34:00.357  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:34:00.357  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:34:00.357  3388  3525 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 13:34:00.357  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:34:00.357  4740  4740 D DefaultClockView: LocalTime Pattern : HH:mm
09-20 13:34:00.357  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:34:00.357  3388  3525 I libsuspend: !@autosuspend_wakeup_count_enable done
,09-20 13:34:00.357  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 13:34:00.357  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 13:34:00.357  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:34:00.357  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:34:00.357  3388  3525 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,09-20 13:34:00.357  3388  3525 D PowerManagerService: mDisplayReady: true
09-20 13:34:00.357  3388  3525 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-20 13:34:00.357  4740  4740 D TimeViewHolder: onTimeUpdate: timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] isSplitHour:false isSingleView:false isAMPMonLeft:null time01: 13:34 time02: null ampm: null
,09-20 13:34:00.357  3166  3214 D Sensorhubs: readContextData: 1, 1, 56, 1, 1, 1, 1
,09-20 13:34:00.367  3388  3815 D SensorHubManager: onGetSensorHubDataLocked: library(7) = 1, 1, 56, 1, 1, 1, 1
,09-20 13:34:00.367  3388  3814 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 11, 34, 0,
,09-20 13:34:00.367  3388  3814 D SensorHubManager: SendSensorHubData: send data = -63, 14, 11, 34, 0
,09-20 13:34:00.367  3166  3215 D Sensorhubs: sendContextData: -63, 14, 11, 34, 0
,09-20 13:34:00.367  6193  6193 E CocktailBarPositionManager: Window direction: 0
,09-20 13:34:00.367  6193  6193 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 13:34:00.367  3388  3814 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :7], AP_SLEEP
,09-20 13:34:00.367  3388  3814 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 7
09-20 13:34:00.377  3388  3814 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 56, 1, 1, 1, 1,
,09-20 13:34:00.377  3388  3814 D CAE     : display(ContextProvider.java:375) - ================= DEVICE_PHYSICAL_CONTEXT_MONITOR =================
09-20 13:34:00.377  3388  3814 I CAE     : display(ContextProvider.java:391) - AODReason=[1], AODStatus=[1], DataType=[1]
,09-20 13:34:00.377  3388  3817 D SContextService: updateSContext() : event = Device Physical Context Monitor
,09-20 13:34:00.377  4740  4740 D RoamingTimeViewHolder: isDualClockSetting :: true isHomeTimeZoneExist :: false isEasyUxON :: false Utils.isRoaming(mContext) :: false
,09-20 13:34:00.377  4740  4740 D RoamingTimeViewHolder: getHomeCalendar : No homecity_timezone, set as default :  (libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167])
,09-20 13:34:00.377  4740  4740 D RoamingTimeViewHolder: onTimeUpdate: isVisible:false timeZone:libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167] text:wt., 20 wrz 13:34
,09-20 13:34:00.377  4740  4740 I AODService.ClockTimer: startAlarm : TICK
09-20 13:34:00.377  3388  4587 V AlarmManager: Add whitelist package alarm :PendingIntent{9533814: PendingIntentRecord{818d03b com.samsung.android.app.aodservice broadcastIntent}}
,09-20 13:34:00.377  4740  4740 I AlpmModeManager: handleUnblankDisplay: state  = BLANK
,09-20 13:34:00.377  4740  4740 V AlpmModeManager: updateAlpmMode: setDoze [DISPLAY_STATE_DOZE_SUSPEND]
,09-20 13:34:00.377  3388  4598 I PowerManagerService: [api] setDozeOverrideFromAod AlpmHlpmSysfs = -1, screenState = 4, Brightness = 0, wakefulness = false
09-20 13:34:00.377  3388  4598 D PowerManagerService: setDozeModeBySysfs:  value is -1 , we ignore it. 
,09-20 13:34:00.387  4740  4740 I AODService: onSContextChanged: AODScreenShown state is already true
09-20 13:34:00.387  4740  4740 D DefaultClockView: RootView invalidate()
,09-20 13:34:00.387  3388  3433 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3388
,09-20 13:34:00.427  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:00.537  3388  3388 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:AOD uid=1000 pid=3388 (0x0)
,09-20 13:34:00.537  3388  3388 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 13:34:00.537  3388  3388 D PowerManagerService: mDisplayReady: false
09-20 13:34:00.537  3388  3388 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 13:34:00.537  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-20 13:34:00.537  3388  3388 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 13:34:00.537  3007  3007 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa8b03c00
09-20 13:34:00.537  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:34:00.537  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-20 13:34:00.537  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-20 13:34:00.537  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:34:00.537  3388  3535 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-20 13:34:00.537  3388  3521 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-20 13:34:00.537  3388  3521 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-20 13:34:00.547  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-20 13:34:00.547  3388  3525 I libsuspend: !@autosuspend_wakeup_count_enable
,09-20 13:34:00.547  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:34:00.547  3388  3525 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 13:34:00.547  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-20 13:34:00.547  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:34:00.547  3388  3525 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-20 13:34:00.547  3388  3525 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 13:34:00.547  3388  3525 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 13:34:00.547  3388  3525 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 13:34:00.547  3388  3525 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,09-20 13:34:00.547  3388  3525 D PowerManagerService: mDisplayReady: true
09-20 13:34:00.547  3388  3525 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 13:34:00.577  6193  6193 E CocktailBarPositionManager: Window direction: 0
,09-20 13:34:00.577  6193  6193 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 13:34:00.607  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:00.787  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:00.967  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:01.147  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:01.327  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:01.507  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:01.687  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:01.707  9821  9887 I jxcore-log: 2016-09-20 11:34:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-20 13:34:01.707  9821  9887 I jxcore-log: 
,09-20 13:34:01.707  9821  9887 I jxcore-log: 2016-09-20 11:34:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-20 13:34:01.707  9821  9887 I jxcore-log: 
,09-20 13:34:01.717  9821  9887 D BluetoothAdapter: STATE_ON
,09-20 13:34:01.727  9821  9887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 13:34:01.727  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 13:34:01.727  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 13:34:01.727  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 13:34:01.727  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 13:34:01.727  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 13:34:01.727  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 13:34:01.727  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 13:34:01.727  9821  9887 D BluetoothAdapter: STATE_ON
,09-20 13:34:01.727  9821  9887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-20 13:34:01.737  9821  9887 I jxcore-log: 2016-09-20 11:34:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-20 13:34:01.737  9821  9887 I jxcore-log: 
,09-20 13:34:01.737  9821  9887 I jxcore-log: 2016-09-20 11:34:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-20 13:34:01.737  9821  9887 I jxcore-log: 
,09-20 13:34:01.817  8376  8399 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,09-20 13:34:01.867  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:01.897  9821  9887 I jxcore-log: Running unit tests
09-20 13:34:01.897  9821  9887 I jxcore-log: 
,09-20 13:34:01.897  9821  9887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-20 13:34:01.897  9821  9887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8d8a63 added. We now have 2 listener(s)
09-20 13:34:01.897  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-20 13:34:01.897  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-20 13:34:01.897  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-20 13:34:01.897  9821  9887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-20 13:34:01.897  9821  9887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b004660 added. We now have 2 listener(s)
09-20 13:34:01.897  9821  9887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-20 13:34:01.897  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-20 13:34:01.907  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-20 13:34:01.907  9821  9887 D BluetoothAdapter: STATE_ON
,09-20 13:34:01.917  9821  9887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 13:34:01.917  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 13:34:01.917  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 13:34:01.917  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 13:34:01.917  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 13:34:01.917  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 13:34:01.917  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 13:34:01.917  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 13:34:01.917  9821  9887 D BluetoothAdapter: STATE_ON
,09-20 13:34:01.917  9821  9887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-20 13:34:01.917  9821  9887 D io.jxcore.node.ConnectivityMonitor: start: OK
09-20 13:34:01.917  9821  9887 D executeNativeTests: Running unit tests
,09-20 13:34:01.927  9821  9821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 13:34:01.937  9821  9821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 13:34:01.957  9821  9887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-20 13:34:01.957  9821  9887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbdd08e added. We now have 3 listener(s)
09-20 13:34:01.957  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-20 13:34:01.957  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-20 13:34:01.957  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-20 13:34:01.957  9821  9887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-20 13:34:01.957  9821  9887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3140af added. We now have 3 listener(s)
09-20 13:34:01.957  9821  9887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-20 13:34:01.957  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-20 13:34:01.957  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-20 13:34:01.967  9821  9887 D BluetoothAdapter: STATE_ON
,09-20 13:34:01.977  9821  9887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 13:34:01.977  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 13:34:01.977  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 13:34:01.977  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 13:34:01.977  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 13:34:01.977  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 13:34:01.977  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 13:34:01.977  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 13:34:01.977  9821  9887 D BluetoothAdapter: STATE_ON
,09-20 13:34:01.977  9821  9887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-20 13:34:01.977  9821  9887 D io.jxcore.node.ConnectivityMonitor: start: OK
09-20 13:34:01.977  9821  9887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-20 13:34:01.977  9821  9887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-20 13:34:01.977  9821  9887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-20 13:34:01.977  9821  9887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-20 13:34:01.977  9821  9887 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-20 13:34:01.977  9821  9887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-20 13:34:01.977  9821  9887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-20 13:34:01.977  9821  9887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-20 13:34:01.977  9821  9887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-20 13:34:01.977  9821  9887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-20 13:34:01.977  9821  9887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-20 13:34:01.977  9821  9887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-20 13:34:01.977  9821  9887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-20 13:34:01.977  9821  9887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-20 13:34:01.977  9821  9887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-20 13:34:01.977  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-20 13:34:01.977  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-20 13:34:01.977  9821  9887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbdd08e removed from the list
09-20 13:34:01.977  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 13:34:01.977  9821  9887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3140af removed from the list
09-20 13:34:01.987  9821  9821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-20 13:34:01.987  9821  9821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-20 13:34:01.987  9821  9887 D io.jxcore.node.ConnectivityMonitor: stop
09-20 13:34:01.987  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 13:34:01.987  9821  9887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:34:01.987  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 13:34:01.987  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-20 13:34:01.987  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-20 13:34:01.987  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 13:34:01.987  9821  9887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3140af not in the list
09-20 13:34:01.987  9821  9887 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-20 13:34:01.987  9821  9887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-20 13:34:01.987  9821  9887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-20 13:34:01.987  9821  9887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-20 13:34:01.987  9821  9887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-20 13:34:01.987  9821  9887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:34:01.987  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 13:34:01.987  9821  9887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbdd08e not in the list
09-20 13:34:01.987  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 13:34:01.987  9821  9887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3140af not in the list
09-20 13:34:01.987  9821  9887 D io.jxcore.node.ConnectivityMonitor: stop
09-20 13:34:01.987  9821  9887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:34:01.987  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 13:34:01.987  9821  9887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:34:01.987  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 13:34:01.997  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-20 13:34:01.997  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-20 13:34:01.997  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 13:34:01.997  9821  9887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3140af not in the list
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-20 13:34:01.997  9821  9887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-20 13:34:01.997  9821  9887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-20 13:34:01.997  9821  9887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-20 13:34:01.997  9821  9887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-20 13:34:01.997  9821  9887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:34:01.997  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 13:34:01.997  9821  9887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbdd08e not in the list
09-20 13:34:01.997  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 13:34:01.997  9821  9887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3140af not in the list
09-20 13:34:01.997  9821  9887 D io.jxcore.node.ConnectivityMonitor: stop
09-20 13:34:01.997  9821  9887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:34:01.997  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 13:34:01.997  9821  9887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:34:01.997  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-20 13:34:01.997  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-20 13:34:01.997  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-20 13:34:01.997  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-20 13:34:01.997  9821  9887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3140af not in the list
09-20 13:34:01.997  9821  9887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-20 13:34:01.997  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 13:34:02.007  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.007  9821  9887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 13:34:02.007  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 13:34:02.007  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 13:34:02.007  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 13:34:02.007  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 13:34:02.007  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 13:34:02.007  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 13:34:02.007  9821  9887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-20 13:34:02.007  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.007  9821  9887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-20 13:34:02.007  9821  9887 D io.jxcore.node.ConnectivityMonitor: start: OK
09-20 13:34:02.007  9821  9887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-20 13:34:02.007  9821  9887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-20 13:34:02.007  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-20 13:34:02.007  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 13:34:02.007  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-20 13:34:02.007  9821  9887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-20 13:34:02.007  9821  9887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-20 13:34:02.017  9821  9821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-20 13:34:02.017  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.017  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.017  9821  9887 D BluetoothAdapter: STATE_ON
,09-20 13:34:02.017  9821  9821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-20 13:34:02.017  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-20 13:34:02.027  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.027  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.027  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-20 13:34:02.027  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-20 13:34:02.027  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.027  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.027  9821  9887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-20 13:34:02.027  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.037  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.037  9821  9887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-20 13:34:02.037  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-20 13:34:02.037  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-20 13:34:02.037  9821  9887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-20 13:34:02.037  9821  9887 D BluetoothLeScanner: Start Scan
09-20 13:34:02.037  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.037  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.037  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.037  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:02.047  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 13:34:02.047  5238  5256 D BtGatt.GattService: registerClient() - UUID=07c8f1a9-26fe-49d9-976c-aa31fdcd47e8
,09-20 13:34:02.087  5238  5383 D BtGatt.GattService: onClientRegistered() - UUID=07c8f1a9-26fe-49d9-976c-aa31fdcd47e8, clientIf=7
,09-20 13:34:02.097  9821  9832 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,09-20 13:34:02.097  5238  5542 D BtGatt.GattService: start scan with filters
,09-20 13:34:02.097  5238  5542 D BtGatt.GattService: getScanSettings
,09-20 13:34:02.117  5238  5542 D BtGatt.GattService: Is it foreground application = true
,09-20 13:34:02.117  5238  5542 D BtGatt.GattService: not a background application
,09-20 13:34:02.127  5238  5542 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-20 13:34:02.127  5238  5542 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-20 13:34:02.127  5238  5542 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-20 13:34:02.127  5238  5405 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-20 13:34:02.127  5238  5405 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 20, currDate: 20
09-20 13:34:02.137  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-20 13:34:02.137  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-20 13:34:02.137  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-20 13:34:02.137  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-20 13:34:02.137  5238  5395 D BtGatt.ScanManager: handling starting scan
09-20 13:34:02.137  5238  5395 D BtGatt.ScanManager: isFilteringSupported
,09-20 13:34:02.137  5238  5395 D BluetoothAdapter: enableStandAloneBleMode=
,09-20 13:34:02.137  5238  5395 D BluetoothAdapter: STATE_ON
,09-20 13:34:02.147  5238  5395 D BluetoothAdapter: STATE_ON
,09-20 13:34:02.147  5238  5405 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 8
,09-20 13:34:02.147  5238  5405 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
09-20 13:34:02.147  5238  5395 D BluetoothAdapter: STATE_ON
,09-20 13:34:02.147  5238  5395 D BluetoothAdapter: STATE_ON
,09-20 13:34:02.147  9821  9887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,09-20 13:34:02.147  5238  5395 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@692d245
09-20 13:34:02.147  9821  9887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-20 13:34:02.157  9821  9821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-20 13:34:02.157  5238  5405 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 6
,09-20 13:34:02.157  5238  5405 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24572854
09-20 13:34:02.157  3388  4943 V AlarmManager:  remove PendingIntent] PendingIntent{d6c00f1: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
09-20 13:34:02.157  5238  5405 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
,09-20 13:34:02.157  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-20 13:34:02.157  5238  5405 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
,09-20 13:34:02.167  3388  3975 V AlarmManager:  remove PendingIntent] PendingIntent{aac04d6: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
09-20 13:34:02.157  5238  5405 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-20 13:34:02.157  5238  5405 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-20 13:34:02.157  5238  5405 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-20 13:34:02.167  5238  5405 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-20 13:34:02.167  5238  5383 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
09-20 13:34:02.167  5238  5383 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 13:34:02.167  5238  5405 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-20 13:34:02.167  5238  5405 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-20 13:34:02.167  5238  5405 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-20 13:34:02.167  5238  5405 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-20 13:34:02.167  5238  5395 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
09-20 13:34:02.167  5238  5395 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-20 13:34:02.167  5238  5395 D BtGatt.ScanManager: Low Rssi Filter value is = -128
,09-20 13:34:02.167  5238  5405 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-20 13:34:02.177  3388  4342 V AlarmManager:  remove PendingIntent] PendingIntent{83b7357: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:02.167  5238  5395 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
09-20 13:34:02.167  5238  5405 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
,09-20 13:34:02.167  5238  5405 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24572854
,09-20 13:34:02.167  9821  9887 I io.jxcore.node.ConnectionHelper: start: OK
09-20 13:34:02.167  5238  5383 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
,09-20 13:34:02.177  3388  3434 V AlarmManager:  remove PendingIntent] PendingIntent{abece44: PendingIntentRecord{2aebb2d com.android.bluetooth broadcastIntent}}
09-20 13:34:02.167  5238  5383 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 13:34:02.167  5238  5395 D BtGatt.ScanManager: Starting BLE batch scan
,09-20 13:34:02.167  5238  5395 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
09-20 13:34:02.177  5238  5383 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
09-20 13:34:02.177  5238  5383 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-20 13:34:02.177  5238  5383 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
09-20 13:34:02.177  5238  5383 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 13:34:02.187  3388  4322 V AlarmManager:  remove PendingIntent] PendingIntent{33b9862: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:02.187  3388  4623 V AlarmManager:  remove PendingIntent] PendingIntent{699edf3: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:02.197  3388  4062 V AlarmManager:  remove PendingIntent] PendingIntent{2fc8ab0: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:02.197  3388  4587 V AlarmManager:  remove PendingIntent] PendingIntent{be8dd29: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:02.207  3388  3433 V AlarmManager:  remove PendingIntent] PendingIntent{c3ed8ae: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:02.207  3388  4322 V AlarmManager:  remove PendingIntent] PendingIntent{15b764f: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:02.217  3388  4393 V AlarmManager:  remove PendingIntent] PendingIntent{217a1dc: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:02.217  3388  4598 V AlarmManager:  remove PendingIntent] PendingIntent{38922e5: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:02.227  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:02.227  3388  4169 V AlarmManager:  remove PendingIntent] PendingIntent{c23d1ba: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:02.227  3388  3850 V AlarmManager:  remove PendingIntent] PendingIntent{503286b: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:02.407  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:02.587  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:02.667  9821  9821 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-20 13:34:02.667  9821  9821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-20 13:34:02.667  9821  9821 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-20 13:34:02.767  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:02.947  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:03.127  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:03.187  3388  3812 V AlarmManager: Expired Alarm result :4
,09-20 13:34:03.187  5238  5238 D BtGatt.ScanManager: awakened up at time 202355
,09-20 13:34:03.187  5238  5395 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 13:34:03.197  3388  3976 V AlarmManager:  remove PendingIntent] PendingIntent{22e0861: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:03.197  5238  5383 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
,09-20 13:34:03.197  5238  5383 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 13:34:03.197  5238  5383 D BtGatt.GattService: current time is 202364896969
,09-20 13:34:03.197  5238  5383 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -76, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -76, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -80, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-20 13:34:03.197  5238  5383 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-20 13:34:03.197  5238  5383 D ScanRecord: parseFromBytes
,09-20 13:34:03.207  3388  4623 V AlarmManager:  remove PendingIntent] PendingIntent{2d4f86: PendingIntentRecord{2aebb2d com.android.bluetooth broadcastIntent}}
,09-20 13:34:03.197  5238  5383 D ScanRecord: first manudata for manu ID
09-20 13:34:03.207  5238  5383 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-20 13:34:03.207  5238  5383 D ScanRecord: parseFromBytes
09-20 13:34:03.207  5238  5383 D ScanRecord: first manudata for manu ID
,09-20 13:34:03.207  5238  5383 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-20 13:34:03.207  5238  5383 D ScanRecord: parseFromBytes
09-20 13:34:03.207  5238  5383 D ScanRecord: first manudata for manu ID
,09-20 13:34:03.207  9821  9831 D ScanRecord: parseFromBytes
,09-20 13:34:03.207  9821  9831 D ScanRecord: first manudata for manu ID
09-20 13:34:03.217  9821  9831 D ScanRecord: parseFromBytes
09-20 13:34:03.217  9821  9831 D ScanRecord: first manudata for manu ID
09-20 13:34:03.217  9821  9831 D ScanRecord: parseFromBytes
09-20 13:34:03.217  9821  9831 D ScanRecord: first manudata for manu ID
,09-20 13:34:03.217  3388  4062 V AlarmManager:  remove PendingIntent] PendingIntent{929e047: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:03.227  3388  4587 V AlarmManager:  remove PendingIntent] PendingIntent{7145074: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:03.227  3388  3433 V AlarmManager:  remove PendingIntent] PendingIntent{1e1c99d: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:03.237  3388  4322 V AlarmManager:  remove PendingIntent] PendingIntent{4fede12: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:03.237  3388  4393 V AlarmManager:  remove PendingIntent] PendingIntent{c1a39e3: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:03.307  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:03.437  3388  3543 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-20 13:34:03.457  3388  3543 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-20 13:34:03.487  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:03.667  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:03.847  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:04.027  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:04.207  3388  3812 V AlarmManager: Expired Alarm result :4
09-20 13:34:04.207  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:04.207  5238  5238 D BtGatt.ScanManager: awakened up at time 203377
,09-20 13:34:04.207  5238  5395 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 13:34:04.217  3388  4169 V AlarmManager:  remove PendingIntent] PendingIntent{9166299: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:04.227  5238  5383 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
,09-20 13:34:04.227  5238  5383 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-20 13:34:04.227  3388  4342 V AlarmManager:  remove PendingIntent] PendingIntent{be8c95e: PendingIntentRecord{2aebb2d com.android.bluetooth broadcastIntent}}
09-20 13:34:04.227  5238  5383 D BtGatt.GattService: current time is 203392366161
09-20 13:34:04.227  5238  5383 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -75, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
,09-20 13:34:04.227  5238  5383 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,09-20 13:34:04.227  5238  5383 D ScanRecord: parseFromBytes
09-20 13:34:04.227  5238  5383 D ScanRecord: first manudata for manu ID
09-20 13:34:04.227  9821  9832 D ScanRecord: parseFromBytes
09-20 13:34:04.227  9821  9832 D ScanRecord: first manudata for manu ID
,09-20 13:34:04.237  3388  4409 V AlarmManager:  remove PendingIntent] PendingIntent{c2c913f: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:04.247  3388  3976 V AlarmManager:  remove PendingIntent] PendingIntent{8f53a0c: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:04.247  3388  3434 V AlarmManager:  remove PendingIntent] PendingIntent{9618f55: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:04.257  3388  4062 V AlarmManager:  remove PendingIntent] PendingIntent{8f41d6a: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:04.257  3388  4598 V AlarmManager:  remove PendingIntent] PendingIntent{ae3025b: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:04.367  3388  3433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-20 13:34:04.367  3388  3433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4355, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-20 13:34:04.367  3388  3433 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:186
09-20 13:34:04.367  3388  3433 D BatteryService: stay LED for fully charged
09-20 13:34:04.367  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-20 13:34:04.367  3388  3388 I MotionRecognitionService: Plugged
,09-20 13:34:04.367  3388  3388 D MotionRecognitionService:   cableConnection= 1
,09-20 13:34:04.367  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-20 13:34:04.367  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,09-20 13:34:04.377  3388  3859 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-20 13:34:04.377  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-20 13:34:04.377  3933  3933 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-20 13:34:04.377  3933  3933 D PowerUI : priorPlugType = 2 mPlugType =  2
09-20 13:34:04.387  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:04.397  3388  6452 D SSRM:n  : SIOP:: AP = 330, PST = 283 (W:6), CP = 241, CUR = 22, LCD = 1
,09-20 13:34:04.397  5282  5282 D CommonServiceConfiguration: getStringValueSetting
,09-20 13:34:04.407  5238  5238 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-20 13:34:04.407  5238  5543 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-20 13:34:04.417  4740  4740 D BatteryController: saveBatteryData : level[100], status[5]
,09-20 13:34:04.417  5282  5282 D BatteryMonitor: new battery level: 100
,09-20 13:34:04.427  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-20 13:34:04.427  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-20 13:34:04.567  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:04.747  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:04.927  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:05.107  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:05.227  3388  3812 V AlarmManager: Expired Alarm result :4
,09-20 13:34:05.237  5238  5238 D BtGatt.ScanManager: awakened up at time 204400
,09-20 13:34:05.237  5238  5395 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 13:34:05.237  3388  3850 V AlarmManager:  remove PendingIntent] PendingIntent{df8cbd1: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:05.247  5238  5383 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
09-20 13:34:05.247  5238  5383 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-20 13:34:05.247  3388  4322 V AlarmManager:  remove PendingIntent] PendingIntent{5aea636: PendingIntentRecord{2aebb2d com.android.bluetooth broadcastIntent}}
,09-20 13:34:05.267  3388  4943 V AlarmManager:  remove PendingIntent] PendingIntent{5c56937: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:05.277  3388  4162 V AlarmManager:  remove PendingIntent] PendingIntent{2a6bea4: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:05.287  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:05.467  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:05.647  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:05.827  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:06.007  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:06.187  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:06.247  3388  3812 V AlarmManager: Expired Alarm result :4
,09-20 13:34:06.247  5238  5238 D BtGatt.ScanManager: awakened up at time 205419
,09-20 13:34:06.267  5238  5395 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 13:34:06.267  3388  4342 V AlarmManager:  remove PendingIntent] PendingIntent{4b6efc2: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:06.277  5238  5383 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=5
,09-20 13:34:06.277  5238  5383 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 13:34:06.277  3388  4598 V AlarmManager:  remove PendingIntent] PendingIntent{fd61d3: PendingIntentRecord{2aebb2d com.android.bluetooth broadcastIntent}}
09-20 13:34:06.277  5238  5383 D BtGatt.GattService: current time is 205441883467
09-20 13:34:06.277  5238  5383 D BtGatt.GattService: Batch record : [-52, 11, 57, -70, 107, -17, 1, 0, -95, 1, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 116, -43, -111, -91, -20, -29, 1, -128, -79, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -72, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -77, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-20 13:34:06.277  3388  3976 V AlarmManager:  remove PendingIntent] PendingIntent{be32110: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:06.277  5238  5383 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-20 13:34:06.277  5238  5383 D ScanRecord: parseFromBytes
09-20 13:34:06.277  5238  5383 D ScanRecord: first manudata for manu ID
09-20 13:34:06.277  5238  5383 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-20 13:34:06.277  5238  5383 D ScanRecord: parseFromBytes
09-20 13:34:06.277  5238  5383 D ScanRecord: first manudata for manu ID
09-20 13:34:06.277  5238  5383 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-20 13:34:06.277  5238  5383 D ScanRecord: parseFromBytes
,09-20 13:34:06.277  5238  5383 D ScanRecord: first manudata for manu ID
09-20 13:34:06.277  5238  5383 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-20 13:34:06.277  5238  5383 D ScanRecord: parseFromBytes
09-20 13:34:06.277  5238  5383 D ScanRecord: first manudata for manu ID
09-20 13:34:06.277  5238  5383 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-20 13:34:06.277  5238  5383 D ScanRecord: parseFromBytes
09-20 13:34:06.277  5238  5383 D ScanRecord: first manudata for manu ID
,09-20 13:34:06.277  9821  9832 D ScanRecord: parseFromBytes
09-20 13:34:06.277  9821  9832 D ScanRecord: first manudata for manu ID
09-20 13:34:06.277  9821  9832 D ScanRecord: parseFromBytes
09-20 13:34:06.277  9821  9832 D ScanRecord: first manudata for manu ID
,09-20 13:34:06.277  9821  9832 D ScanRecord: parseFromBytes
09-20 13:34:06.277  9821  9832 D ScanRecord: first manudata for manu ID
09-20 13:34:06.277  9821  9832 D ScanRecord: parseFromBytes
09-20 13:34:06.277  9821  9832 D ScanRecord: first manudata for manu ID
09-20 13:34:06.277  9821  9832 D ScanRecord: parseFromBytes
09-20 13:34:06.277  9821  9832 D ScanRecord: first manudata for manu ID
,09-20 13:34:06.287  3388  4393 V AlarmManager:  remove PendingIntent] PendingIntent{6282409: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:06.297  3388  3975 V AlarmManager:  remove PendingIntent] PendingIntent{208460e: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:06.297  3388  4342 V AlarmManager:  remove PendingIntent] PendingIntent{fb2482f: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:06.307  3388  4322 V AlarmManager:  remove PendingIntent] PendingIntent{4413e3c: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:06.307  3388  3976 V AlarmManager:  remove PendingIntent] PendingIntent{f25f7c5: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:06.317  3388  4623 V AlarmManager:  remove PendingIntent] PendingIntent{c06b51a: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:06.317  3388  3434 V AlarmManager:  remove PendingIntent] PendingIntent{625384b: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:06.367  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:06.547  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:06.727  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:06.907  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:07.087  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:07.177  9821  9887 D BluetoothAdapter: STATE_ON
,09-20 13:34:07.187  9821  9887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-20 13:34:07.187  9821  9887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-20 13:34:07.187  9821  9887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-20 13:34:07.187  9821  9887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:34:07.187  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-20 13:34:07.187  9821  9887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-20 13:34:07.187  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-20 13:34:07.187  9821  9887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-20 13:34:07.187  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-20 13:34:07.187  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-20 13:34:07.187  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-20 13:34:07.197  9821  9887 D BluetoothAdapter: STATE_ON
,09-20 13:34:07.197  9821  9887 D BluetoothAdapter: STATE_ON
,09-20 13:34:07.197  9821  9887 D BluetoothLeScanner: Stop Scan
,09-20 13:34:07.207  5238  5256 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-20 13:34:07.207  5238  5256 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-20 13:34:07.207  5238  5256 D BtGatt.GattService: stopScan() - queue size =1
09-20 13:34:07.207  5238  5405 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
09-20 13:34:07.207  5238  5405 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 20, currDate: 20
,09-20 13:34:07.207  5238  5405 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-20 13:34:07.207  5238  5405 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-20 13:34:07.207  5238  5395 D BtGatt.ScanManager: filter size is 1
09-20 13:34:07.217  5238  5395 D BtGatt.ScanManager: delete FilterIndex - 3
09-20 13:34:07.217  5238  5405 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
09-20 13:34:07.217  5238  5405 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
09-20 13:34:07.217  5238  5405 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-20 13:34:07.217  5238  5542 D BtGatt.GattService: unregisterClient() - clientIf=7
,09-20 13:34:07.217  5238  5383 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
09-20 13:34:07.217  5238  5383 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-20 13:34:07.217  3388  4393 V AlarmManager:  remove PendingIntent] PendingIntent{a020228: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
09-20 13:34:07.217  5238  5395 D BtGatt.ScanManager: stopping BLe Batch
,09-20 13:34:07.217  5238  5383 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
09-20 13:34:07.217  5238  5383 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
09-20 13:34:07.217  5238  5395 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,09-20 13:34:07.227  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-20 13:34:07.227  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-20 13:34:07.227  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-20 13:34:07.227  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-20 13:34:07.227  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-20 13:34:07.227  9821  9887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-20 13:34:07.227  3388  4062 V AlarmManager:  remove PendingIntent] PendingIntent{2734b41: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:07.237  5238  5383 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=4
09-20 13:34:07.237  5238  5383 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,09-20 13:34:07.237  5238  5383 D BtGatt.GattService: current time is 206401006428
09-20 13:34:07.237  5238  5383 D BtGatt.GattService: Batch record : [-52, 11, 57, -70, 107, -17, 1, 0, -100, 4, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 35, 97, 126, -92, 22, -56, 1, -128, -85, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -74, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,09-20 13:34:07.237  5238  5383 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-20 13:34:07.237  3388  4322 V AlarmManager:  remove PendingIntent] PendingIntent{14b08e6: PendingIntentRecord{2aebb2d com.android.bluetooth broadcastIntent}}
09-20 13:34:07.237  5238  5383 D ScanRecord: parseFromBytes
,09-20 13:34:07.237  5238  5383 D ScanRecord: first manudata for manu ID
09-20 13:34:07.237  5238  5383 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-20 13:34:07.237  9821  9887 D BluetoothAdapter: STATE_ON
,09-20 13:34:07.237  5238  5383 D ScanRecord: parseFromBytes
09-20 13:34:07.237  5238  5383 D ScanRecord: first manudata for manu ID
09-20 13:34:07.237  5238  5383 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-20 13:34:07.237  5238  5383 D ScanRecord: parseFromBytes
09-20 13:34:07.237  5238  5383 D ScanRecord: first manudata for manu ID
09-20 13:34:07.237  5238  5383 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-20 13:34:07.237  5238  5383 D ScanRecord: parseFromBytes
09-20 13:34:07.237  5238  5383 D ScanRecord: first manudata for manu ID
09-20 13:34:07.237  9821  9887 D BluetoothAdapter: STATE_ON
09-20 13:34:07.237  9821  9887 D BluetoothLeAdvertiser: stop advertising
09-20 13:34:07.237  9821  9887 D BluetoothLeAdvertiser: wrapper is null
09-20 13:34:07.237  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-20 13:34:07.237  9821  9887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-20 13:34:07.247  3388  3433 V AlarmManager:  remove PendingIntent] PendingIntent{18d0e27: PendingIntentRecord{2aebb2d com.android.bluetooth broadcastIntent}}
09-20 13:34:07.237  9821  9887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-20 13:34:07.247  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-20 13:34:07.247  3388  4943 V AlarmManager:  remove PendingIntent] PendingIntent{c8918d4: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:07.247  9821  9821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-20 13:34:07.247  9821  9887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-20 13:34:07.247  9821  9821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 13:34:07.247  9821  9821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-20 13:34:07.247  9821  9887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-20 13:34:07.247  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-20 13:34:07.247  9821  9887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbdd08e not in the list
09-20 13:34:07.247  9821  9887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-20 13:34:07.247  9821  9887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3140af not in the list
09-20 13:34:07.247  9821  9887 D io.jxcore.node.ConnectivityMonitor: stop
09-20 13:34:07.247  9821  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-20 13:34:07.257  9821  9821 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-20 13:34:07.257  9821  9821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-20 13:34:07.257  3388  3433 V AlarmManager:  remove PendingIntent] PendingIntent{bc8ee40: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:07.257  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:07.257  9821  9821 D BluetoothAdapter: STATE_ON
,09-20 13:34:07.267  3388  4587 V AlarmManager:  remove PendingIntent] PendingIntent{2a52179: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
09-20 13:34:07.267  9821  9821 D BluetoothAdapter: STATE_ON
,09-20 13:34:07.267  9821  9821 D BluetoothAdapter: STATE_ON
,09-20 13:34:07.267  9821  9821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-20 13:34:07.267  3388  4623 V AlarmManager:  remove PendingIntent] PendingIntent{d184ebe: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:07.277  9821  9821 D BluetoothAdapter: STATE_ON
,09-20 13:34:07.277  9821  9821 D BluetoothAdapter: STATE_ON
,09-20 13:34:07.277  9821  9821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-20 13:34:07.277  9821  9821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-20 13:34:07.277  9821  9821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-20 13:34:07.277  9821  9821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-20 13:34:07.277  3388  3434 V AlarmManager:  remove PendingIntent] PendingIntent{4b9b1f: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:07.287  9821  9821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-20 13:34:07.287  9821  9821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 13:34:07.287  9821  9821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-20 13:34:07.287  3388  3433 V AlarmManager:  remove PendingIntent] PendingIntent{218ca3b: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:07.287  9821  9821 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-20 13:34:07.287  9821  9821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-20 13:34:07.287  9821  9821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-20 13:34:07.287  3388  3850 V AlarmManager:  remove PendingIntent] PendingIntent{6ce4558: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:07.297  9821  9821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-20 13:34:07.297  3388  4322 V AlarmManager:  remove PendingIntent] PendingIntent{90486b1: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:07.297  3388  4062 V AlarmManager:  remove PendingIntent] PendingIntent{5dd7796: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:07.307  3388  4587 V AlarmManager:  remove PendingIntent] PendingIntent{dbfcf17: PendingIntentRecord{af26259 com.android.bluetooth broadcastIntent}}
,09-20 13:34:07.447  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:07.627  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:07.807  9821  9821 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-20 13:34:07.807  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:07.987  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:08.167  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:08.347  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:08.527  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:08.707  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:08.887  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:09.067  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:09.247  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:09.427  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:09.607  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:09.787  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:09.967  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:10.147  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:10.327  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:10.507  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:10.687  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:10.867  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:11.047  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:11.227  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:11.407  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:11.587  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:11.767  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 13:34:11.947  3388  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
