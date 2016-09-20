#### Test 850469116a90ff6_thali04_samsung-SM-G935F Logs


```
--------- beginning of main
09-20 07:36:15.626  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:15.806  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:15.986  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:16.126  9868  9868 I FIPS_bssl: FIPS approved mode (1) | 9868 | app_process
09-20 07:36:16.126  9868  9868 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-20 07:36:16.136  9868  9868 D AndroidRuntime: CheckJNI is OFF
09-20 07:36:16.136  9868  9868 D AndroidRuntime: readGMSProperty: start
09-20 07:36:16.136  9868  9868 D AndroidRuntime: readGMSProperty: already setted!!
09-20 07:36:16.136  9868  9868 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-20 07:36:16.136  9868  9868 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-20 07:36:16.136  9868  9868 D AndroidRuntime: readGMSProperty: end
09-20 07:36:16.136  9868  9868 D AndroidRuntime: addProductProperty: start
09-20 07:36:16.146  9868  9868 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-20 07:36:16.166  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:16.176  9868  9868 I Radio-JNI: register_android_hardware_Radio DONE
09-20 07:36:16.176  9868  9868 E AffinityControl: AffinityControl: registerfunction enter
09-20 07:36:16.186  9868  9868 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-20 07:36:16.216  3428  4397 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-20 07:36:16.216  3428  4397 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-20 07:36:16.236  3428  4397 D ResourcesManager: For user 0 new overlays fetched Null
09-20 07:36:16.236  3428  4397 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 07:36:16.236  3428  4397 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-20 07:36:16.246  3428  4397 D ActivityManager: mDVFSHelper.acquire()
09-20 07:36:16.246  3428  4397 V WindowManager: addAppToken: AppWindowToken{d03fba274 token=Token{ab33a47 ActivityRecord{afbd186 u0 com.test.thalitest/.MainActivity t75}}} to stack=2 task=75 at 0
09-20 07:36:16.256  3428  3546 I InjectionManager: Inside getClassLibPath caller 
09-20 07:36:16.266  3428  3546 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-20 07:36:16.266  3428  3546 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{d34cc0c V.E...... R.....ID 0,0-0,0}
09-20 07:36:16.276  3428  3546 W WindowManager: Failed looking up window
09-20 07:36:16.276  3428  3546 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@2eeb955 does not exist
09-20 07:36:16.276  3428  3546 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 07:36:16.276  3428  3546 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-20 07:36:16.276  9877  9877 E Zygote  : v2
09-20 07:36:16.276  9877  9877 I libpersona: KNOX_SDCARD checking this for 10177
09-20 07:36:16.276  3428  3546 D ISSUE_DEBUG: InputChannelName : 8daff6a Starting com.test.thalitest
09-20 07:36:16.276  9877  9877 I libpersona: KNOX_SDCARD not a persona
09-20 07:36:16.276  9877  9877 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-20 07:36:16.276  3428  4397 I ActivityManager: Start proc 9877:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-20 07:36:16.276  9877  9877 E Zygote  : accessInfo : 0
09-20 07:36:16.276  9877  9877 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-20 07:36:16.276  3428  4397 D InputDispatcher: Focused application set to: xxxx
09-20 07:36:16.276  9868  9868 D AndroidRuntime: Shutting down VM
09-20 07:36:16.276  3428  3852 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-20 07:36:16.286  3007  3007 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-20 07:36:16.306  6592  6592 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 07:36:16.316  9877  9877 D TimaKeyStoreProvider: TimaSignature is unavailable
09-20 07:36:16.316  9877  9877 D ActivityThread: Added TimaKeyStore provider
09-20 07:36:16.316  3428  4773 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3428
09-20 07:36:16.316  3428  4773 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 07:36:16.316  3428  4773 D PowerManagerService: mDisplayReady: false
09-20 07:36:16.316  3428  4773 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 07:36:16.316  3428  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 07:36:16.316  3428  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 07:36:16.326  3007  3007 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fac343c00
09-20 07:36:16.316  3428  4773 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 07:36:16.326  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-20 07:36:16.316  3428  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 07:36:16.316  3428  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 07:36:16.316  3428  3566 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-20 07:36:16.326  3428  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 07:36:16.326  3428  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 07:36:16.326  3428  3552 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 07:36:16.326  3428  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 07:36:16.326  3428  3552 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 07:36:16.326  3428  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 07:36:16.326  3428  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 07:36:16.326  3428  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 07:36:16.326  3428  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 07:36:16.326  3428  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 07:36:16.326  3428  3552 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 07:36:16.326  3428  3449 V WindowStateAnimator: Finishing drawing window Window{5188d23 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-20 07:36:16.326  3428  3552 D PowerManagerService: mDisplayReady: true
09-20 07:36:16.326  6592  6592 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 07:36:16.326  3428  3552 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-20 07:36:16.326  3428  4397 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3428
09-20 07:36:16.336  6592  6592 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 07:36:16.336  6592  6592 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-20 07:36:16.346  3428  4669 D ActivityManager:  Launching com.test.thalitest, updated priority
09-20 07:36:16.346  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:16.356  3007  3016 D libEGL  : eglTerminate EGLDisplay = 0x7fac0c0e78
09-20 07:36:16.356  3007  3016 D libEGL  : eglTerminate EGLDisplay = 0x7fac0c0e78
09-20 07:36:16.366  3007  4429 I SurfaceFlinger: id=10 Removed MauncherAct (4/13)
09-20 07:36:16.366  3007  4445 I SurfaceFlinger: id=10 Removed MauncherAct (-2/13)
09-20 07:36:16.376  3428  3428 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-20 07:36:16.376  6206  6217 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-20 07:36:16.376  3428  3513 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-20 07:36:16.376  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fe3ed22a8
09-20 07:36:16.386  4370  4479 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-20 07:36:16.386  4370  4479 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
09-20 07:36:16.386  3428  4145 V WindowStateAnimator: Finishing drawing window Window{6ea9add u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-20 07:36:16.386  3428  4773 V WindowStateAnimator: Finishing drawing window Window{5188d23 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=READY_TO_SHOW
09-20 07:36:16.396  6592  6592 V ActivityThread: updateVisibility : ActivityRecord{f6dccb7 token=android.os.BinderProxy@a539741 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-20 07:36:16.396  4308  4308 D Launcher: onTrimMemory. Level: 20
09-20 07:36:16.396  4308  4308 V ActivityThread: updateVisibility : ActivityRecord{de8d969 token=android.os.BinderProxy@7ce6a40 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-20 07:36:16.396  3007  4445 I SurfaceFlinger: id=18 Removed VSBConnecti (7/12)
09-20 07:36:16.396  3007  3016 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/12)
09-20 07:36:16.396  3007  3016 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
09-20 07:36:16.396  3007  3872 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
09-20 07:36:16.406  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fe3ed22a8
09-20 07:36:16.406  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fe3ed2278
09-20 07:36:16.406  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fe3ed2278
09-20 07:36:16.466  3428  3428 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3428 (0x0)
09-20 07:36:16.486  3428  3428 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3428 (0x0)
09-20 07:36:16.486  3428  3428 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 07:36:16.486  3428  3428 D PowerManagerService: mDisplayReady: false
09-20 07:36:16.486  3428  3428 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 07:36:16.486  3428  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 07:36:16.486  3428  3428 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 07:36:16.486  3428  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 07:36:16.486  3428  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 07:36:16.486  3428  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 07:36:16.486  3428  3566 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-20 07:36:16.486  3007  3007 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fac343c00
09-20 07:36:16.486  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-20 07:36:16.486  3428  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 07:36:16.486  3428  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 07:36:16.486  3428  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 07:36:16.486  3428  3552 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 07:36:16.486  3428  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 07:36:16.486  3428  3552 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 07:36:16.486  3428  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 07:36:16.486  3428  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 07:36:16.486  3428  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 07:36:16.486  3428  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 07:36:16.486  3428  3552 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 07:36:16.486  3428  3552 D PowerManagerService: mDisplayReady: true
09-20 07:36:16.486  3428  3552 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 07:36:16.526  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:16.676  6206  6206 I TrayVisibilityController: handleMessage : msg.what = 1
09-20 07:36:16.696  3428  4669 I WindowManager: Screenshot max retries 4 of Token{ab33a47 ActivityRecord{afbd186 u0 com.test.thalitest/.MainActivity t75}} appWin=Window{8daff6a u0 d0 Starting com.test.thalitest} drawState=1
09-20 07:36:16.696  6206  6216 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-20 07:36:16.696  3428  3546 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 07:36:16.696  3428  3546 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-20 07:36:16.696  3428  3428 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 07:36:16.696  3428  3428 I KnoxTimeoutHandler: SD activityfalse
09-20 07:36:16.706  6206  6206 I Utils   : isCurrentUser current = 0, ownerId = 0
09-20 07:36:16.706  3428  6514 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 07:36:16.706  6206  6206 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-20 07:36:16.706  3428  6514 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 07:36:16.706  6206  6206 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-20 07:36:16.716  3428  3852 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-20 07:36:16.716  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:16.736  3428  6514 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 07:36:16.736  9877  9877 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-20 07:36:16.746  3428  6514 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 07:36:16.746  9877  9877 D RelationGraph: garbageCollect()
09-20 07:36:16.746  3428  3546 V WindowStateAnimator: Finishing drawing window Window{8daff6a u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-20 07:36:16.746  3428  3546 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 07:36:16.746  9877  9877 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 07:36:16.746  3428  3428 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 07:36:16.746  3428  3428 I KnoxTimeoutHandler: SD activityfalse
09-20 07:36:16.746  3428  4314 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-20 07:36:16.746  9877  9877 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-20 07:36:16.756  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fe3ed2188
09-20 07:36:16.756  3428  6514 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 07:36:16.756  3428  6514 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 07:36:16.756  3428  6514 D GameManagerService: identifyGamePackage. com.test.thalitest
09-20 07:36:16.766  9877  9877 D ResourcesManager: For user 0 new overlays fetched Null
09-20 07:36:16.766  9877  9877 I InjectionManager: Inside getClassLibPath caller 
09-20 07:36:16.786  9877  9877 D InjectionManager: InjectionManager
09-20 07:36:16.786  9877  9877 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-20 07:36:16.786  9877  9877 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-20 07:36:16.786  9877  9877 I InjectionManager: featureStore :{}
09-20 07:36:16.786  9877  9877 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 07:36:16.786  9877  9877 D RelationGraph: garbageCollect()
09-20 07:36:16.796  9877  9877 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-20 07:36:16.826  9877  9877 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-20 07:36:16.886  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:16.896  9877  9877 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-20 07:36:16.896  9877  9877 D ResourcesManager: For user 0 new overlays fetched Null
09-20 07:36:16.896  9877  9877 I InjectionManager: Inside getClassLibPath caller 
09-20 07:36:16.906  9877  9877 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-20 07:36:16.956  3428  3877 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-20 07:36:16.976  9877  9877 I cr_LibraryLoader: Time to load native libraries: 45 ms (timestamps 5372-5417)
09-20 07:36:16.976  9877  9877 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-20 07:36:17.036  9877  9892 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-20 07:36:17.056  3428  3877 I MdnieScenarioControlService: mGameModeLauncher : false
09-20 07:36:17.056  3428  3877 I MdnieScenarioControlService: setUIMode
09-20 07:36:17.056  9877  9877 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fc08cfc}
09-20 07:36:17.056  9877  9877 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-20 07:36:17.066  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:17.086  9877  9877 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-20 07:36:17.116  9877  9877 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-20 07:36:17.196  3428  3513 W ActivityManager: Activity pause timeout for ActivityRecord{afbd186 u0 com.test.thalitest/.MainActivity t75}
09-20 07:36:17.246  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:17.256  9877  9877 D libEGL  : eglInitialize EGLDisplay = 0xffe8708c
09-20 07:36:17.356  3428  4967 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
09-20 07:36:17.356  3428  4967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-20 07:36:17.426  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:17.446  9877  9877 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-20 07:36:17.466  9877  9877 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-20 07:36:17.466  9877  9877 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-20 07:36:17.496  9877  9877 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-20 07:36:17.546  9877  9877 D Activity: performCreate Call Injection manager
,09-20 07:36:17.546  9877  9877 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-20 07:36:17.556  9877  9877 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-20 07:36:17.566  9877  9877 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{25af53a I.E...... R.....ID 0,0-0,0}
,09-20 07:36:17.576  9877  9929 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-20 07:36:17.576  3428  4314 W WindowManager: Failed looking up window
09-20 07:36:17.576  3428  4314 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@9378635 does not exist
09-20 07:36:17.576  3428  4314 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-20 07:36:17.576  3428  4314 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-20 07:36:17.576  3428  4314 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-20 07:36:17.576  3428  4314 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-20 07:36:17.576  3428  4314 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-20 07:36:17.576  3428  4314 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-20 07:36:17.586  3428  4669 D ISSUE_DEBUG: InputChannelName : 9867aca com.test.thalitest/com.test.thalitest.MainActivity
,09-20 07:36:17.586  3428  3978 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-20 07:36:17.586  3428  3978 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 07:36:17.586  3428  3428 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-20 07:36:17.596  3428  3428 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-20 07:36:17.606  9877  9877 V ActivityThread: updateVisibility : ActivityRecord{abc21e1 token=android.os.BinderProxy@6ac1793 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-20 07:36:17.606  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:17.616  9877  9892 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-20 07:36:17.646  9877  9877 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9877
,09-20 07:36:17.646  3428  3978 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9877 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 07:36:17.646  3428  3863 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-20 07:36:17.646  3428  3863 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-20 07:36:17.656  3428  3863 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-20 07:36:17.666  3428  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-20 07:36:17.676  9877  9877 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-20 07:36:17.676  3428  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 07:36:17.676  3428  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 07:36:17.686  3428  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-20 07:36:17.686  3428  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-20 07:36:17.686  3428  3863 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 07:36:17.696  3007  3007 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,09-20 07:36:17.706  3428  6515 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-20 07:36:17.716  9877  9929 D libEGL  : eglInitialize EGLDisplay = 0xdc8bf7c4
,09-20 07:36:17.716  9877  9929 I OpenGLRenderer: Initialized EGL, version 1.4
,09-20 07:36:17.726  9877  9929 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-20 07:36:17.726  3428  4321 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3428
,09-20 07:36:17.726  3428  4321 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 07:36:17.726  3428  4321 D PowerManagerService: mDisplayReady: false
09-20 07:36:17.726  3428  4321 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 07:36:17.726  3428  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-20 07:36:17.726  3007  3007 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fac343c00
,09-20 07:36:17.726  3428  4321 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,09-20 07:36:17.726  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,09-20 07:36:17.726  3428  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 07:36:17.726  3428  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-20 07:36:17.736  3007  3052 W SurfaceFlinger: Ignoring duplicate VSYNC event from HWC (t=196171078782)
09-20 07:36:17.726  3428  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-20 07:36:17.726  3428  3566 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-20 07:36:17.726  3428  3546 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-20 07:36:17.726  3428  3546 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-20 07:36:17.756  3428  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-20 07:36:17.756  3428  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 07:36:17.756  3428  3552 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 07:36:17.756  3428  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 07:36:17.756  3428  3552 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 07:36:17.756  3428  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-20 07:36:17.756  3428  3552 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-20 07:36:17.756  3428  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-20 07:36:17.756  3428  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 07:36:17.756  3428  3552 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 07:36:17.756  3428  3552 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 07:36:17.756  3428  3552 D PowerManagerService: mDisplayReady: true
,09-20 07:36:17.756  3428  3552 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 07:36:17.756  6206  6206 E CocktailBarPositionManager: Window direction: 0
,09-20 07:36:17.756  6206  6206 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 07:36:17.766  9877  9877 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-20 07:36:17.786  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:17.786  3428  4321 V WindowStateAnimator: Finishing drawing window Window{9867aca u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-20 07:36:17.786  9877  9877 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-20 07:36:17.786  9877  9933 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-20 07:36:17.786  9877  9933 D libEGL  : eglInitialize EGLDisplay = 0xdb2ec3f4
,09-20 07:36:17.796  3428  4773 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3428
,09-20 07:36:17.796  3428  3546 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 07:36:17.796  3428  3428 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 07:36:17.796  3428  3978 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3428
09-20 07:36:17.796  3428  3546 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s106ms (total +1s552ms)
09-20 07:36:17.796  3428  3428 I KnoxTimeoutHandler: SD activityfalse
09-20 07:36:17.806  3428  4145 V WindowStateAnimator: Finishing drawing window Window{9867aca u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-20 07:36:17.806  9877  9877 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6ac1793 time:196244
09-20 07:36:17.806  9877  9933 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-20 07:36:17.806  3428  3546 D ActivityManager: mDVFSHelper.release()
09-20 07:36:17.806  3428  3546 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{afbd186 u0 com.test.thalitest/.MainActivity t75} time:196245
09-20 07:36:17.806  3428  3546 D ViewRootImpl: #3 mView = null
,09-20 07:36:17.816  3007  3018 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
,09-20 07:36:17.816  3007  3016 I SurfaceFlinger: id=20 Removed uhalitest (-2/11)
,09-20 07:36:17.836  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fe3ed22a8
,09-20 07:36:17.856  9877  9877 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9877
,09-20 07:36:17.946  3428  3428 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3428 (0x0)
09-20 07:36:17.946  3428  3428 I libsuspend: !@autosuspend_wakeup_count_disable
09-20 07:36:17.946  3428  3428 D PowerManagerService: mDisplayReady: false
09-20 07:36:17.946  3428  3428 I libsuspend: !@autosuspend_wakeup_count_disable done
09-20 07:36:17.946  3428  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 07:36:17.946  3428  3428 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-20 07:36:17.946  3428  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 07:36:17.946  3428  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 07:36:17.946  3428  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-20 07:36:17.946  3428  3566 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-20 07:36:17.956  3007  3007 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fac343c00
09-20 07:36:17.956  3428  3546 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-20 07:36:17.956  3007  3007 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-20 07:36:17.956  3428  3546 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-20 07:36:17.966  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:17.966  3428  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 07:36:17.966  3428  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 07:36:17.966  3428  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 07:36:17.966  3428  3552 I libsuspend: !@autosuspend_wakeup_count_enable
09-20 07:36:17.966  3428  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 07:36:17.966  3428  3552 I libsuspend: !@autosuspend_wakeup_count_enable done
09-20 07:36:17.966  3428  3552 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-20 07:36:17.966  3428  3552 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-20 07:36:17.966  3428  3552 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-20 07:36:17.966  3428  3552 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-20 07:36:17.966  3428  3552 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-20 07:36:17.966  3428  3552 D PowerManagerService: mDisplayReady: true
09-20 07:36:17.966  3428  3552 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-20 07:36:17.976  6206  6206 E CocktailBarPositionManager: Window direction: 0
09-20 07:36:17.976  6206  6206 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-20 07:36:18.066  9877  9877 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-20 07:36:18.146  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:18.156  9877  9941 D jxcore_app_log: JniHelper::setJavaVM(0xf4fb4000), pthread_self() = -628098768
,09-20 07:36:18.156  9877  9941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-20 07:36:18.156  9877  9941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-20 07:36:18.156  9877  9941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-20 07:36:18.156  9877  9941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-20 07:36:18.156  9877  9941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-20 07:36:18.156  9877  9941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f07fdb added. We now have 1 listener(s)
,09-20 07:36:18.156  9877  9941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
,09-20 07:36:18.156  9877  9941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-20 07:36:18.156  9877  9941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-20 07:36:18.156  9877  9941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-20 07:36:18.166  9877  9941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe261b6 added. We now have 1 listener(s)
09-20 07:36:18.166  9877  9941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-20 07:36:18.166  9877  9941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-20 07:36:18.166  9877  9941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-20 07:36:18.166  9877  9941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-20 07:36:18.166  9877  9941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-20 07:36:18.166  9877  9941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-20 07:36:18.166  9877  9941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-20 07:36:18.166  9877  9941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
,09-20 07:36:18.176  9877  9941 D BluetoothAdapter: STATE_ON
,09-20 07:36:18.186  9877  9941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-20 07:36:18.186  9877  9941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 07:36:18.186  9877  9941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 07:36:18.186  9877  9941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 07:36:18.186  9877  9941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 07:36:18.186  9877  9941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 07:36:18.186  9877  9941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 07:36:18.186  9877  9941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 07:36:18.186  9877  9941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-20 07:36:18.186  9877  9941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-20 07:36:18.186  9877  9941 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-20 07:36:18.186  9877  9941 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-20 07:36:18.186  9877  9877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 07:36:18.186  9877  9877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-20 07:36:18.196  4021  4021 D Recents : onTaskStackChanged
,09-20 07:36:18.206  4021  4021 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-20 07:36:18.216  4021  4021 D ResourcesManager: For user 0 new overlays fetched Null
,09-20 07:36:18.226  9877  9877 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-20 07:36:18.326  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:18.506  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:18.576  9877  9942 W jxcore-log: Initializing JXcore engine
09-20 07:36:18.576  9877  9942 W jxcore-log: JXcore engine is ready
,09-20 07:36:18.596  5035  5035 E audit   : type=1400 msg=audit(1474349778.596:264): avc:  denied  { ioctl } for  pid=9942 comm="Thread-164" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4249 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-20 07:36:18.596  5035  5035 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-20 07:36:18.596  5035  5035 E audit   : type=1300 msg=audit(1474349778.596:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d93043c8 items=0 ppid=3177 pid=9942 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-164" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-20 07:36:18.596  5035  5035 E audit   : type=1327 msg=audit(1474349778.596:264): proctitle="com.test.thalitest"
09-20 07:36:18.596  5035  5035 E audit   : type=1320 msg=audit(1474349778.596:264): 
09-20 07:36:18.596  5035  5035 E audit   : type=1400 msg=audit(1474349778.596:265): avc:  denied  { ioctl } for  pid=9942 comm="Thread-164" path="socket:[11218]" dev="sockfs" ino=11218 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-20 07:36:18.596  5035  5035 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-20 07:36:18.596  5035  5035 E audit   : type=1300 msg=audit(1474349778.596:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d93043c8 items=0 ppid=3177 pid=9942 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-164" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-20 07:36:18.596  5035  5035 E audit   : type=1327 msg=audit(1474349778.596:265): proctitle="com.test.thalitest"
09-20 07:36:18.596  5035  5035 E audit   : type=1320 msg=audit(1474349778.596:265): 
,09-20 07:36:18.596  9877  9942 W jxcore-log: Starting JXcore engine
,09-20 07:36:18.636  9877  9942 W jxcore-log: Platform android
09-20 07:36:18.636  9877  9942 W jxcore-log: 
09-20 07:36:18.636  9877  9942 W jxcore-log: Process ARCH arm
09-20 07:36:18.636  9877  9942 W jxcore-log: 
,09-20 07:36:18.686  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:18.706  9877  9942 I jxcore-log: JXcore Cordova bridge is ready!
09-20 07:36:18.706  9877  9942 I jxcore-log: 
09-20 07:36:18.706  9877  9942 W jxcore-log: JXcore engine is started
,09-20 07:36:18.706  9877  9941 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-20 07:36:18.716  9877  9877 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-20 07:36:18.866  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:19.046  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:19.226  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:19.256  3428  3903 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/75_task.xml.bak
,09-20 07:36:19.406  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:19.586  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:19.716  3428  6514 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-20 07:36:19.766  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:19.946  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:20.126  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:20.306  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:20.486  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:20.666  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:20.846  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:21.026  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:21.206  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:21.386  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:21.566  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:21.746  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:21.926  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:22.046  3151  3634 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,09-20 07:36:22.106  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:22.286  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:22.466  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:22.646  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:22.776  3428  6514 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-20 07:36:22.826  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:22.926  9877  9942 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-20 07:36:22.926  9877  9942 I jxcore-log: 
09-20 07:36:22.926  9877  9942 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-20 07:36:22.926  9877  9942 I jxcore-log: 
09-20 07:36:22.936  9877  9942 D BluetoothAdapter: STATE_ON
09-20 07:36:22.936  9877  9942 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 07:36:22.936  9877  9942 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 07:36:22.936  9877  9942 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 07:36:22.936  9877  9942 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 07:36:22.936  9877  9942 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 07:36:22.936  9877  9942 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 07:36:22.936  9877  9942 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 07:36:22.936  9877  9942 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-20 07:36:22.946  9877  9942 D BluetoothAdapter: STATE_ON
09-20 07:36:22.946  9877  9942 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-20 07:36:22.946  9877  9942 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-20 07:36:22.946  9877  9942 I jxcore-log: 
09-20 07:36:22.946  9877  9942 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-20 07:36:22.946  9877  9942 I jxcore-log: 
09-20 07:36:23.006  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:23.176  9877  9942 D executeNativeTests: Running unit tests
09-20 07:36:23.186  9877  9942 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
09-20 07:36:23.186  9877  9942 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-20 07:36:23.186  9877  9942 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-20 07:36:23.186  9877  9942 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-20 07:36:23.186  9877  9942 D com.test.thalitest.ThaliTestRunner: Total duration: 1 ms
09-20 07:36:23.186  9877  9942 I jxcore-log: *Native tests were executed*
09-20 07:36:23.186  9877  9942 I jxcore-log: 
09-20 07:36:23.186  9877  9942 I jxcore-log: Total number of executed tests:  1
09-20 07:36:23.186  9877  9942 I jxcore-log: 
09-20 07:36:23.186  9877  9942 I jxcore-log: Number of passed tests:  1
09-20 07:36:23.186  9877  9942 I jxcore-log: 
09-20 07:36:23.186  9877  9942 I jxcore-log: Number of failed tests:  0
09-20 07:36:23.186  9877  9942 I jxcore-log: 
09-20 07:36:23.186  9877  9942 I jxcore-log: Number of ignored tests:  0
09-20 07:36:23.186  9877  9942 I jxcore-log: 
09-20 07:36:23.186  9877  9942 I jxcore-log: Total duration:  1
09-20 07:36:23.186  9877  9942 I jxcore-log: 
09-20 07:36:23.186  9877  9942 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-20 07:36:23.186  9877  9942 I jxcore-log: 
09-20 07:36:23.186  9877  9942 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-20 07:36:23.186  9877  9942 I jxcore-log: 
09-20 07:36:23.186  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:23.206  9877  9877 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-20 07:36:23.366  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:23.546  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:23.696  9944  9944 I FIPS_bssl: FIPS approved mode (1) | 9944 | app_process
,09-20 07:36:23.706  9944  9944 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-20 07:36:23.706  9944  9944 D AndroidRuntime: CheckJNI is OFF
09-20 07:36:23.706  9944  9944 D AndroidRuntime: readGMSProperty: start
09-20 07:36:23.706  9944  9944 D AndroidRuntime: readGMSProperty: already setted!!
09-20 07:36:23.706  9944  9944 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-20 07:36:23.706  9944  9944 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-20 07:36:23.706  9944  9944 D AndroidRuntime: readGMSProperty: end
09-20 07:36:23.706  9944  9944 D AndroidRuntime: addProductProperty: start
,09-20 07:36:23.726  9944  9944 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-20 07:36:23.726  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:23.746  9944  9944 I Radio-JNI: register_android_hardware_Radio DONE
,09-20 07:36:23.746  9944  9944 E AffinityControl: AffinityControl: registerfunction enter
,09-20 07:36:23.756  9944  9944 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-20 07:36:23.766  3428  4321 D PackageManager: START PACKAGE DELETE: observer{262251535}
09-20 07:36:23.766  3428  4321 D PackageManager: pkg{<packageName>}
09-20 07:36:23.766  3428  4321 D PackageManager: user{0}
09-20 07:36:23.766  3428  4321 D PackageManager: caller{2000}
09-20 07:36:23.766  3428  4321 D PackageManager: flags{2}
,09-20 07:36:23.766  3428  4321 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-20 07:36:23.766  3428  4321 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-20 07:36:23.766  3428  4321 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-20 07:36:23.766  3428  4321 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-20 07:36:23.766  3428  4321 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-20 07:36:23.766  3428  3573 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-20 07:36:23.766  3428  3573 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-20 07:36:23.766  3428  3573 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-20 07:36:23.766  3428  3573 D ApplicationPolicy: getApplicationUninstallationEnabled
,09-20 07:36:23.766  3428  3573 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-20 07:36:23.766  3428  3573 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,09-20 07:36:23.766  3428  3573 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-20 07:36:23.766  3428  3573 D PackageManager: !@killApplicatoin: 10177, uninstall pkg
09-20 07:36:23.766  3428  3573 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-20 07:36:23.766  3428  3513 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=-1: uninstall pkg
09-20 07:36:23.766  3428  3573 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-20 07:36:23.776  3428  3513 I ActivityManager: Killing 9877:com.test.thalitest/u0a177 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-20 07:36:23.786  3428  3513 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-20 07:36:23.796  3428  3513 D ActivityManager: mDVFSHelper.acquire()
,09-20 07:36:23.796  3428  3573 D AASAinstall: there is not AASApackages.xml file
,09-20 07:36:23.886  3428  4967 D GraphicsStats: Buffer count: 7
09-20 07:36:23.886  3428  4397 I WindowState: WIN DEATH: Window{9867aca u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-20 07:36:23.886  3428  4314 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@a699c9c)
,09-20 07:36:23.886  3428  3863 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-20 07:36:23.886  3428  3863 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 07:36:23.886  3007  3016 I SurfaceFlinger: id=21 Removed NainActivit (6/10)
09-20 07:36:23.886  3428  3863 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-20 07:36:23.886  3007  3872 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
,09-20 07:36:23.906  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:24.086  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:24.096  3428  3573 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-20 07:36:24.166  3428  3573 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-20 07:36:24.166  3428  3513 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-20 07:36:24.166  3428  3513 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-20 07:36:24.166  3164  3164 W keystore: ENTER clear_uid from uid 1000 for 10177
,09-20 07:36:24.166  3428  3573 I art     : Waiting for a blocking GC Explicit
09-20 07:36:24.166  3428  3513 E ActivityManager: Failure starting process com.test.thalitest
09-20 07:36:24.166  3428  3513 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5277)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5194)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5032)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2643)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3481)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2595)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4997)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4958)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7379)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9146)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8769)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8924)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:458)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2597)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 07:36:24.166  3428  3513 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-20 07:36:24.176  3428  3513 I ActivityManager:   Force finishing activity ActivityRecord{afbd186 u0 com.test.thalitest/.MainActivity t75}
09-20 07:36:24.176  3428  3513 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
09-20 07:36:24.186  3428  3513 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,09-20 07:36:24.206  3007  3007 I SurfaceFlinger: id=22 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-20 07:36:24.236  4308  4308 D Launcher: onRestart, Launcher: 125920893
,09-20 07:36:24.246  3428  3438 I art     : Background sticky concurrent mark sweep GC freed 209283(12MB) AllocSpace objects, 66(1460KB) LOS objects, 25% free, 42MB/56MB, paused 3.948ms total 144.316ms
09-20 07:36:24.246  3428  3573 I art     : WaitForGcToComplete blocked for 74.094ms for cause Explicit
09-20 07:36:24.246  3428  3573 I art     : Starting a blocking GC Explicit
,09-20 07:36:24.266  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:24.446  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-20 07:36:24.466  3428  3573 I art     : Explicit concurrent mark sweep GC freed 104419(6MB) AllocSpace objects, 4(1872KB) LOS objects, 32% free, 33MB/49MB, paused 1.635ms total 223.097ms
,09-20 07:36:24.506  3428  3573 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-20 07:36:24.506  3428  3573 D AASAuninstall: userId = 0, info.removedAppID = 10177, info.uid = 10177, packageName = com.test.thalitest
,09-20 07:36:24.506  3428  3573 D AASAinstall: there is not AASApackages.xml file
,09-20 07:36:24.506  3428  3573 D PackageManager: result of delete: 1{262251535}
,09-20 07:36:24.506  3428  3573 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-20 07:36:24.506  3428  3573 D PackageManager: userId{-1}
09-20 07:36:24.506  3428  3573 D PackageManager: andCode{true}
09-20 07:36:24.506  9944  9944 I art     : System.exit called, status: 0
09-20 07:36:24.506  9944  9944 I AndroidRuntime: VM exiting with result code 0.
,09-20 07:36:24.516  3428  3513 I WindowManager: Screenshot max retries 4 of Token{c3d681c ActivityRecord{37f6d8f u0 com.samsung.android.MtpApplication/.USBConnection t74}} appWin=Window{6ea9add u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=1
,09-20 07:36:24.516  6206  6217 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,09-20 07:36:24.516  6206  6216 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} Intent { flg=0x10800000 cmp=com.samsung.android.MtpApplication/.USBConnection VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-20 07:36:24.516  3428  3428 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-20 07:36:24.526  3428  3513 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-20 07:36:24.536  3428  3546 W ResourceType: No known package when getting value for resource number 0x7f060012
,09-20 07:36:24.536  4308  4308 D Launcher: onStart, Launcher: 125920893
09-20 07:36:24.536  4308  4308 D Launcher.HomeView: onStart
,09-20 07:36:24.536  4308  4308 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-20 07:36:24.546  4308  4308 V ActivityThread: updateVisibility : ActivityRecord{de8d969 token=android.os.BinderProxy@7ce6a40 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-20 07:36:24.546  4308  4308 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
,09-20 07:36:24.546  4308  4308 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
09-20 07:36:24.546  4308  4308 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
09-20 07:36:24.546  4308  4308 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
09-20 07:36:24.546  4308  4308 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
,09-20 07:36:24.546  4308  4308 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
09-20 07:36:24.546  4308  4308 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-20 07:36:24.546  4308  4308 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
09-20 07:36:24.546  4308  4308 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
09-20 07:36:24.556  3428  3573 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=0: pkg removed
,09-20 07:36:24.556  3428  3546 W ResourceType: No known package when getting value for resource number 0x7f02003b
,09-20 07:36:24.566  3428  3546 W WindowManager: Token{ab33a47 ActivityRecord{afbd186 u0 com.test.thalitest/.MainActivity t75 f}} failed creating starting window
09-20 07:36:24.566  3428  3546 W WindowManager: android.content.res.Resources$NotFoundException: Resource ID #0x7f02003b
09-20 07:36:24.566  3428  3546 W WindowManager: 	at android.content.res.Resources.getValue(Resources.java:2558)
09-20 07:36:24.566  3428  3546 W WindowManager: 	at android.content.res.Resources.getDrawable(Resources.java:2001)
09-20 07:36:24.566  3428  3546 W WindowManager: 	at android.content.res.Resources.getDrawable(Resources.java:1987)
09-20 07:36:24.566  3428  3546 W WindowManager: 	at android.content.Context.getDrawable(Context.java:464)
09-20 07:36:24.566  3428  3546 W WindowManager: 	at com.android.internal.widget.ToolbarWidgetWrapper.setIcon(ToolbarWidgetWrapper.java:352)
09-20 07:36:24.566  3428  3546 W WindowManager: 	at com.android.internal.widget.ActionBarOverlayLayout.setIcon(ActionBarOverlayLayout.java:738)
09-20 07:36:24.566  3428  3546 W WindowManager: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4709)
09-20 07:36:24.566  3428  3546 W WindowManager: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-20 07:36:24.566  3428  3546 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-20 07:36:24.566  3428  3546 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-20 07:36:24.566  3428  3546 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 07:36:24.566  3428  3546 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-20 07:36:24.566  3428  3546 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 07:36:24.566  3428  3546 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-20 07:36:24.566  3428  3546 I Choreographer: Skipped 37 frames!  The application may be doing too much work on its main thread.
,09-20 07:36:24.566  3007  3007 I SurfaceFlinger: id=23 createSurf (1440x2560),1 flag=4, MauncherAct
,09-20 07:36:24.576  3428  3573 I ActivityManager:   Force finishing activity ActivityRecord{afbd186 u0 com.test.thalitest/.MainActivity t75 f}
09-20 07:36:24.576  3428  3573 W ActivityManager: Duplicate finish request for ActivityRecord{afbd186 u0 com.test.thalitest/.MainActivity t75 f}
,09-20 07:36:24.576  4308  4649 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-20 07:36:24.586  9426  9956 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-20 07:36:24.596  9426  9956 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-20 07:36:24.596  9426  9956 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-20 07:36:24.626  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fe3ed2188
09-20 07:36:24.626  3428  3792 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-20 07:36:24.626  3428  4967 V WindowStateAnimator: Finishing drawing window Window{514bb2 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
,09-20 07:36:24.646  3428  3849 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-20 07:36:24.646  3428  3849 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-20 07:36:24.646  3428  3428 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-20 07:36:24.646  3428  3428 I KnoxTimeoutHandler: Shared devices show user statefalse
09-20 07:36:24.646  3428  3428 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-20 07:36:24.646  3428  3903 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/75_task.xml
,09-20 07:36:24.646  3428  3513 D InputDispatcher: Focused application released
,09-20 07:36:24.646  3428  3513 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-20 07:36:24.646  3428  3513 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-20 07:36:24.666  3428  3546 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-20 07:36:24.666  3428  3428 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-20 07:36:24.666  3428  3546 D ActivityManager: mDVFSHelper.release()
09-20 07:36:24.666  3428  3546 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{d78e2c1 u0 com.sec.android.app.launcher/.activities.LauncherActivity t72} time:203109
,09-20 07:36:24.676  3428  3428 I KnoxTimeoutHandler: SD activityfalse
09-20 07:36:24.676  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-20 07:36:24.686  3428  3428 D ResourcesManager: For user 0 new overlays fetched Null
,09-20 07:36:24.686  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-20 07:36:24.686  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-20 07:36:24.686  3428  3428 D ResourcesManager: For user 0 new overlays fetched Null
,09-20 07:36:24.686  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-20 07:36:24.686  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-20 07:36:24.696  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-20 07:36:24.696  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-20 07:36:24.696  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-20 07:36:24.696  3428  3507 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-20 07:36:24.696  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,09-20 07:36:24.696  3428  4346 V WindowStateAnimator: Finishing drawing window Window{6ea9add u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-20 07:36:24.706  3428  3428 D ResourcesManager: For user 0 new overlays fetched Null
,09-20 07:36:24.706  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,09-20 07:36:24.706  3944  3944 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
09-20 07:36:24.706  3428  3507 D ResourcesManager: For user 0 new overlays fetched Null
,09-20 07:36:24.706  3944  3944 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
09-20 07:36:24.706  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-20 07:36:24.706  3007  3007 I SurfaceFlinger: id=24 createSurf (1592x384),1 flag=4, VSBConnecti
09-20 07:36:24.706  3428  3507 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-20 07:36:24.706  3428  3507 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-20 07:36:24.716  3428  3428 D ResourcesManager: For user 0 new overlays fetched Null
09-20 07:36:24.716  3428  3507 D ResourcesManager: For user 0 new overlays fetched Null
,09-20 07:36:24.716  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-20 07:36:24.716  4152  4152 I CatchNotificationsService: mPackageChangedReceiver : onReceive action = android.intent.action.PACKAGE_REMOVED
09-20 07:36:24.716  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-20 07:36:24.716  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-20 07:36:24.716  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-20 07:36:24.716  3428  3507 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-20 07:36:24.716  3428  3428 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-20 07:36:24.716  3428  3428 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,09-20 07:36:24.716  3428  3428 D ResourcesManager: For user 0 new overlays fetched Null
,09-20 07:36:24.716  3428  3428 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-20 07:36:24.716  3428  3428 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-20 07:36:24.716  3428  3507 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-20 07:36:24.716  3428  3507 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-20 07:36:24.726  3428  3507 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-20 07:36:24.726  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fe3ed2188
,09-20 07:36:24.726  3428  3428 D ResourcesManager: For user 0 new overlays fetched Null
09-20 07:36:24.726  3428  3428 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-20 07:36:24.726  3428  3507 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,09-20 07:36:24.726  3428  3428 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-20 07:36:24.726  3428  3428 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-20 07:36:24.726  3428  3428 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,09-20 07:36:24.726  3428  3428 D ResourcesManager: For user 0 new overlays fetched Null
,09-20 07:36:24.726  3428  3507 D ResourcesManager: For user 0 new overlays fetched Null
09-20 07:36:24.726  3428  3428 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-20 07:36:24.726  3428  3428 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,09-20 07:36:24.736  3428  3507 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
09-20 07:36:24.736  3428  3507 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,09-20 07:36:24.736  4334  4820 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.

```
