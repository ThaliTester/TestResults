#### Test 85046911783e9ea_thali04_samsung-SM-G935F Logs


```
--------- beginning of main
09-19 19:01:20.592  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:20.772  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:20.952  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:21.132  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:21.162  9667  9667 I FIPS_bssl: FIPS approved mode (1) | 9667 | app_process
09-19 19:01:21.172  9667  9667 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-19 19:01:21.172  9667  9667 D AndroidRuntime: CheckJNI is OFF
09-19 19:01:21.172  9667  9667 D AndroidRuntime: readGMSProperty: start
09-19 19:01:21.172  9667  9667 D AndroidRuntime: readGMSProperty: already setted!!
09-19 19:01:21.172  9667  9667 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-19 19:01:21.172  9667  9667 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-19 19:01:21.172  9667  9667 D AndroidRuntime: readGMSProperty: end
09-19 19:01:21.172  9667  9667 D AndroidRuntime: addProductProperty: start
09-19 19:01:21.192  9667  9667 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-19 19:01:21.212  9667  9667 I Radio-JNI: register_android_hardware_Radio DONE
09-19 19:01:21.222  9667  9667 E AffinityControl: AffinityControl: registerfunction enter
09-19 19:01:21.222  9667  9667 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-19 19:01:21.252  3407  3465 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-19 19:01:21.252  3407  3465 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-19 19:01:21.272  3407  3465 D ResourcesManager: For user 0 new overlays fetched Null
09-19 19:01:21.282  3407  3465 D GameManagerService: identifyGamePackage. com.test.thalitest
09-19 19:01:21.282  3407  3465 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-19 19:01:21.282  3407  3465 D ActivityManager: mDVFSHelper.acquire()
09-19 19:01:21.282  3407  3465 V WindowManager: addAppToken: AppWindowToken{d09e1bb6c token=Token{29ebc1f ActivityRecord{2f53be u0 com.test.thalitest/.MainActivity t75}}} to stack=2 task=75 at 0
09-19 19:01:21.292  3407  3560 I InjectionManager: Inside getClassLibPath caller 
09-19 19:01:21.292  3407  3560 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-19 19:01:21.292  3407  3560 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5b60c04 V.E...... R.....ID 0,0-0,0}
09-19 19:01:21.302  9676  9676 E Zygote  : v2
09-19 19:01:21.302  9676  9676 I libpersona: KNOX_SDCARD checking this for 10177
09-19 19:01:21.302  9676  9676 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-19 19:01:21.302  9676  9676 I libpersona: KNOX_SDCARD not a persona
09-19 19:01:21.302  9676  9676 E Zygote  : accessInfo : 0
09-19 19:01:21.302  9676  9676 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-19 19:01:21.302  3407  3560 W WindowManager: Failed looking up window
09-19 19:01:21.302  3407  3560 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@54485ed does not exist
09-19 19:01:21.302  3407  3560 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 19:01:21.302  3407  3560 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-19 19:01:21.302  3407  3560 D ISSUE_DEBUG: InputChannelName : 1496c22 Starting com.test.thalitest
09-19 19:01:21.302  3407  3465 I ActivityManager: Start proc 9676:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-19 19:01:21.302  3407  3465 D InputDispatcher: Focused application set to: xxxx
09-19 19:01:21.302  9667  9667 D AndroidRuntime: Shutting down VM
09-19 19:01:21.302  3407  3857 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-19 19:01:21.312  9676  9676 D TimaKeyStoreProvider: TimaSignature is unavailable
09-19 19:01:21.312  9676  9676 D ActivityThread: Added TimaKeyStore provider
09-19 19:01:21.312  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:21.312  3006  3006 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-19 19:01:21.342  6412  6412 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-19 19:01:21.362  3407  3983 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3407
09-19 19:01:21.362  3407  3983 I libsuspend: !@autosuspend_wakeup_count_disable
09-19 19:01:21.362  3407  3983 D PowerManagerService: mDisplayReady: false
09-19 19:01:21.362  3407  3983 I libsuspend: !@autosuspend_wakeup_count_disable done
09-19 19:01:21.362  3407  3566 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 19:01:21.362  6412  6412 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-19 19:01:21.362  3407  3566 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 19:01:21.362  3407  3566 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 19:01:21.362  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f77c03c00
09-19 19:01:21.362  3407  3983 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-19 19:01:21.362  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-19 19:01:21.362  3407  3566 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 19:01:21.362  3407  3575 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-19 19:01:21.362  3006  3054 W SurfaceFlinger: Ignoring duplicate VSYNC event from HWC (t=199249296357)
09-19 19:01:21.362  3407  4824 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3407
09-19 19:01:21.372  3407  3566 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 19:01:21.372  3407  3566 I libsuspend: !@autosuspend_wakeup_count_enable
09-19 19:01:21.372  3407  3566 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 19:01:21.372  3407  3566 I libsuspend: !@autosuspend_wakeup_count_enable done
09-19 19:01:21.372  3407  3566 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 19:01:21.372  3407  3566 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 19:01:21.372  3407  3566 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 19:01:21.372  3407  3566 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 19:01:21.372  3407  3566 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 19:01:21.372  3407  3566 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 19:01:21.372  3407  3566 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-19 19:01:21.372  3407  3566 D PowerManagerService: mDisplayReady: true
09-19 19:01:21.372  3407  3566 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-19 19:01:21.372  3407  3976 D ActivityManager:  Launching com.test.thalitest, updated priority
09-19 19:01:21.382  3407  4336 V WindowStateAnimator: Finishing drawing window Window{a021475 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-19 19:01:21.402  3407  3407 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-19 19:01:21.402  5822  5833 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-19 19:01:21.402  3407  3531 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-19 19:01:21.422  3006  3015 D libEGL  : eglTerminate EGLDisplay = 0x7f77980e78
09-19 19:01:21.422  3006  3015 D libEGL  : eglTerminate EGLDisplay = 0x7f77980e78
09-19 19:01:21.422  3407  4337 V WindowStateAnimator: Finishing drawing window Window{b39095f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-19 19:01:21.422  3006  3832 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-19 19:01:21.422  6412  6412 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-19 19:01:21.432  3006  4633 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-19 19:01:21.432  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fe85a4358
09-19 19:01:21.432  6412  6412 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-19 19:01:21.432  6412  6412 V ActivityThread: updateVisibility : ActivityRecord{e9085b9 token=android.os.BinderProxy@f8204e2 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-19 19:01:21.442  3006  4633 I SurfaceFlinger: id=18 Removed VSBConnecti (7/12)
09-19 19:01:21.442  3006  3015 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/12)
09-19 19:01:21.442  4324  4324 V ActivityThread: updateVisibility : ActivityRecord{71c4855 token=android.os.BinderProxy@f76aa5c {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-19 19:01:21.442  4324  4324 D Launcher: onTrimMemory. Level: 20
09-19 19:01:21.442  3006  3017 D libEGL  : eglTerminate EGLDisplay = 0x7f776fee78
09-19 19:01:21.442  3006  3015 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
09-19 19:01:21.442  3006  3907 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
09-19 19:01:21.462  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fe85a4358
09-19 19:01:21.462  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fe85a4358
09-19 19:01:21.492  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:21.512  3407  3407 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3407 (0x0)
09-19 19:01:21.512  3407  3407 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3407 (0x0)
09-19 19:01:21.512  3407  3407 I libsuspend: !@autosuspend_wakeup_count_disable
09-19 19:01:21.512  3407  3407 D PowerManagerService: mDisplayReady: false
09-19 19:01:21.512  3407  3407 I libsuspend: !@autosuspend_wakeup_count_disable done
09-19 19:01:21.512  3407  3566 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-19 19:01:21.512  3407  3407 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-19 19:01:21.512  3407  3566 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 19:01:21.512  3407  3566 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 19:01:21.512  3407  3566 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 19:01:21.512  3407  3575 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-19 19:01:21.512  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f77c03c00
09-19 19:01:21.512  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-19 19:01:21.512  3407  3566 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-19 19:01:21.512  3407  3566 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 19:01:21.512  3407  3566 I libsuspend: !@autosuspend_wakeup_count_enable
09-19 19:01:21.512  3407  3566 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 19:01:21.512  3407  3566 I libsuspend: !@autosuspend_wakeup_count_enable done
09-19 19:01:21.512  3407  3566 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 19:01:21.512  3407  3566 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-19 19:01:21.512  3407  3566 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 19:01:21.512  3407  3566 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 19:01:21.512  3407  3566 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 19:01:21.512  3407  3566 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-19 19:01:21.512  3407  3566 D PowerManagerService: mDisplayReady: true
09-19 19:01:21.522  3407  3566 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-19 19:01:21.562  3153  3646 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-19 19:01:21.672  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:21.712  5822  5822 I TrayVisibilityController: handleMessage : msg.what = 1
09-19 19:01:21.732  3407  3976 I WindowManager: Screenshot max retries 4 of Token{29ebc1f ActivityRecord{2f53be u0 com.test.thalitest/.MainActivity t75}} appWin=Window{1496c22 u0 d0 Starting com.test.thalitest} drawState=1
09-19 19:01:21.732  5822  5832 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-19 19:01:21.732  3407  3560 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-19 19:01:21.732  3407  3407 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-19 19:01:21.732  3407  3560 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-19 19:01:21.732  3407  3407 I KnoxTimeoutHandler: SD activityfalse
09-19 19:01:21.732  3407  6345 D GameManagerService: identifyGamePackage. com.test.thalitest
09-19 19:01:21.732  3407  6345 D GameManagerService: identifyGamePackage. com.test.thalitest
09-19 19:01:21.742  3407  3857 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-19 19:01:21.742  5822  5822 I Utils   : isCurrentUser current = 0, ownerId = 0
09-19 19:01:21.742  5822  5822 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-19 19:01:21.742  5822  5822 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-19 19:01:21.762  9676  9676 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-19 19:01:21.772  9676  9676 D RelationGraph: garbageCollect()
09-19 19:01:21.772  9676  9676 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-19 19:01:21.772  3407  6345 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-19 19:01:21.772  3407  3983 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-19 19:01:21.772  9676  9676 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-19 19:01:21.772  3407  3560 V WindowStateAnimator: Finishing drawing window Window{1496c22 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-19 19:01:21.772  3407  3560 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-19 19:01:21.772  3407  3407 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-19 19:01:21.772  3407  3407 I KnoxTimeoutHandler: SD activityfalse
09-19 19:01:21.782  3407  6345 D GameManagerService: identifyGamePackage. com.test.thalitest
09-19 19:01:21.782  3407  3560 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1c7b781 u0 com.samsung.android.MtpApplication/.USBConnection t74} time:199662
09-19 19:01:21.782  3407  3560 D ActivityManager: mDVFSHelper.release()
09-19 19:01:21.782  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fe85a4238
09-19 19:01:21.782  9676  9676 D ResourcesManager: For user 0 new overlays fetched Null
09-19 19:01:21.792  3407  6345 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-19 19:01:21.792  3407  6345 D GameManagerService: identifyGamePackage. com.test.thalitest
09-19 19:01:21.792  3407  6345 D GameManagerService: identifyGamePackage. com.test.thalitest
09-19 19:01:21.792  9676  9676 I InjectionManager: Inside getClassLibPath caller 
09-19 19:01:21.802  9676  9676 D InjectionManager: InjectionManager
09-19 19:01:21.802  9676  9676 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-19 19:01:21.802  9676  9676 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-19 19:01:21.802  9676  9676 I InjectionManager: featureStore :{}
09-19 19:01:21.812  9676  9676 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-19 19:01:21.812  9676  9676 D RelationGraph: garbageCollect()
09-19 19:01:21.812  9676  9676 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-19 19:01:21.842  9676  9676 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-19 19:01:21.852  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:21.902  9676  9676 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-19 19:01:21.902  9676  9676 D ResourcesManager: For user 0 new overlays fetched Null
09-19 19:01:21.902  9676  9676 I InjectionManager: Inside getClassLibPath caller 
09-19 19:01:21.912  9676  9676 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-19 19:01:21.982  9676  9676 I cr_LibraryLoader: Time to load native libraries: 42 ms (timestamps 9822-9864)
09-19 19:01:21.982  9676  9676 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-19 19:01:21.992  3407  3880 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-19 19:01:22.032  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:22.042  9676  9692 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-19 19:01:22.062  9676  9676 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {704ab88}
09-19 19:01:22.062  9676  9676 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-19 19:01:22.082  9676  9676 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-19 19:01:22.092  3407  3880 I MdnieScenarioControlService: mGameModeLauncher : false
09-19 19:01:22.092  3407  3880 I MdnieScenarioControlService: setUIMode
09-19 19:01:22.132  9676  9676 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-19 19:01:22.212  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:22.222  3407  3531 W ActivityManager: Activity pause timeout for ActivityRecord{2f53be u0 com.test.thalitest/.MainActivity t75}
09-19 19:01:22.322  9676  9676 D libEGL  : eglInitialize EGLDisplay = 0xffee955c
,09-19 19:01:22.392  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:22.422  3407  4430 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
,09-19 19:01:22.422  3407  4430 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-19 19:01:22.512  9676  9676 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-19 19:01:22.532  9676  9676 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-19 19:01:22.532  9676  9676 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-19 19:01:22.562  9676  9676 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-19 19:01:22.572  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:22.612  9676  9676 D Activity: performCreate Call Injection manager
,09-19 19:01:22.622  9676  9676 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-19 19:01:22.622  9676  9676 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-19 19:01:22.632  9676  9676 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ffdaa6 I.E...... R.....ID 0,0-0,0}
,09-19 19:01:22.642  9676  9729 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-19 19:01:22.642  3407  4267 W WindowManager: Failed looking up window
09-19 19:01:22.642  3407  4267 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@5bf7ecd does not exist
09-19 19:01:22.642  3407  4267 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-19 19:01:22.642  3407  4267 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-19 19:01:22.642  3407  4267 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-19 19:01:22.642  3407  4267 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-19 19:01:22.642  3407  4267 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-19 19:01:22.642  3407  4267 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-19 19:01:22.642  3407  4337 D ISSUE_DEBUG: InputChannelName : ab9a382 com.test.thalitest/com.test.thalitest.MainActivity
,09-19 19:01:22.652  3407  3464 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-19 19:01:22.652  3407  3464 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-19 19:01:22.652  3407  3407 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-19 19:01:22.652  3407  3407 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-19 19:01:22.662  9676  9676 V ActivityThread: updateVisibility : ActivityRecord{f60a094 token=android.os.BinderProxy@726cd0f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-19 19:01:22.672  9676  9692 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-19 19:01:22.692  9676  9676 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9676
,09-19 19:01:22.692  3407  3464 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9676 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-19 19:01:22.692  3407  3868 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-19 19:01:22.692  3407  3868 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-19 19:01:22.712  3407  3868 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-19 19:01:22.712  9676  9676 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-19 19:01:22.712  3407  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-19 19:01:22.722  3407  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-19 19:01:22.722  3407  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-19 19:01:22.732  3407  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-19 19:01:22.732  3006  3006 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,09-19 19:01:22.732  3407  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-19 19:01:22.732  3407  3868 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-19 19:01:22.742  3407  6346 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-19 19:01:22.742  9676  9729 D libEGL  : eglInitialize EGLDisplay = 0xdc5ff7c4
,09-19 19:01:22.742  9676  9729 I OpenGLRenderer: Initialized EGL, version 1.4
,09-19 19:01:22.752  9676  9729 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-19 19:01:22.752  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:22.752  3407  4822 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3407
,09-19 19:01:22.752  3407  4822 I libsuspend: !@autosuspend_wakeup_count_disable
09-19 19:01:22.752  3407  4822 D PowerManagerService: mDisplayReady: false
09-19 19:01:22.752  3407  4822 I libsuspend: !@autosuspend_wakeup_count_disable done
09-19 19:01:22.752  3407  3566 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-19 19:01:22.752  3407  4822 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-19 19:01:22.762  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f77c03c00
09-19 19:01:22.752  3407  3566 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 19:01:22.762  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-19 19:01:22.752  3407  3566 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 19:01:22.752  3407  3566 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 19:01:22.752  3407  3575 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-19 19:01:22.752  3407  3560 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-19 19:01:22.752  3407  3560 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-19 19:01:22.772  3407  3566 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 19:01:22.772  3407  3566 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 19:01:22.772  3407  3566 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 19:01:22.772  3407  3566 I libsuspend: !@autosuspend_wakeup_count_enable
09-19 19:01:22.772  3407  3566 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 19:01:22.772  3407  3566 I libsuspend: !@autosuspend_wakeup_count_enable done
09-19 19:01:22.772  3407  3566 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-19 19:01:22.772  3407  3566 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-19 19:01:22.772  3407  3566 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 19:01:22.772  3407  3566 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 19:01:22.772  3407  3566 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-19 19:01:22.772  3407  3566 D PowerManagerService: mDisplayReady: true
09-19 19:01:22.772  3407  3566 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-19 19:01:22.782  5822  5822 E CocktailBarPositionManager: Window direction: 0
09-19 19:01:22.782  5822  5822 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-19 19:01:22.792  9676  9676 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-19 19:01:22.802  3407  4824 V WindowStateAnimator: Finishing drawing window Window{ab9a382 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-19 19:01:22.802  9676  9676 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-19 19:01:22.812  3407  3976 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3407
09-19 19:01:22.812  3407  3560 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-19 19:01:22.812  3407  3407 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-19 19:01:22.812  3407  3560 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s91ms (total +1s531ms)
09-19 19:01:22.812  3407  3560 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2f53be u0 com.test.thalitest/.MainActivity t75} time:200699
09-19 19:01:22.812  3407  3560 D ViewRootImpl: #3 mView = null
,09-19 19:01:22.822  3006  4633 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
,09-19 19:01:22.822  3006  3832 I SurfaceFlinger: id=20 Removed uhalitest (-2/11)
,09-19 19:01:22.822  3407  3407 I KnoxTimeoutHandler: SD activityfalse
,09-19 19:01:22.822  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fe85a4358
09-19 19:01:22.822  3407  3465 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3407
,09-19 19:01:22.832  9676  9733 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-19 19:01:22.832  9676  9733 D libEGL  : eglInitialize EGLDisplay = 0xdaa7f3f4
,09-19 19:01:22.842  3407  4150 V WindowStateAnimator: Finishing drawing window Window{ab9a382 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-19 19:01:22.842  9676  9676 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@726cd0f time:200721
,09-19 19:01:22.852  9676  9733 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-19 19:01:22.902  9676  9676 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9676
,09-19 19:01:22.932  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:22.972  3407  3407 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3407 (0x0)
09-19 19:01:22.972  3407  3407 I libsuspend: !@autosuspend_wakeup_count_disable
09-19 19:01:22.972  3407  3407 D PowerManagerService: mDisplayReady: false
09-19 19:01:22.972  3407  3407 I libsuspend: !@autosuspend_wakeup_count_disable done
09-19 19:01:22.972  3407  3566 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-19 19:01:22.982  3407  3407 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-19 19:01:22.982  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f77c03c00
09-19 19:01:22.982  3407  3566 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 19:01:22.982  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-19 19:01:22.982  3407  3566 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 19:01:22.982  3407  3566 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 19:01:22.982  3407  3575 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-19 19:01:22.982  3407  3560 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-19 19:01:22.982  3407  3560 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,09-19 19:01:22.992  3407  3566 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-19 19:01:22.992  3407  3566 I libsuspend: !@autosuspend_wakeup_count_enable
09-19 19:01:22.992  3407  3566 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-19 19:01:22.992  3407  3566 I libsuspend: !@autosuspend_wakeup_count_enable done
09-19 19:01:22.992  3407  3566 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-19 19:01:22.992  3407  3566 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-19 19:01:22.992  3407  3566 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-19 19:01:22.992  3407  3566 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,09-19 19:01:22.992  3407  3566 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-19 19:01:22.992  3407  3566 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,09-19 19:01:22.992  3407  3566 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-19 19:01:22.992  3407  3566 D PowerManagerService: mDisplayReady: true
,09-19 19:01:22.992  3407  3566 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-19 19:01:23.002  5822  5822 E CocktailBarPositionManager: Window direction: 0
09-19 19:01:23.002  5822  5822 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-19 19:01:23.102  9676  9676 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-19 19:01:23.112  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:23.192  9676  9740 D jxcore_app_log: JniHelper::setJavaVM(0xf4ef4000), pthread_self() = -636487376
09-19 19:01:23.192  9676  9740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-19 19:01:23.192  9676  9740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-19 19:01:23.192  9676  9740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-19 19:01:23.192  9676  9740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-19 19:01:23.192  9676  9740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-19 19:01:23.192  9676  9740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a3956 added. We now have 1 listener(s)
09-19 19:01:23.192  9676  9740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
09-19 19:01:23.202  9676  9740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-19 19:01:23.202  9676  9740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 19:01:23.202  9676  9740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-19 19:01:23.202  9676  9740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c97d9ad added. We now have 1 listener(s)
09-19 19:01:23.202  9676  9740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 19:01:23.202  9676  9740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-19 19:01:23.202  9676  9740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-19 19:01:23.202  9676  9740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-19 19:01:23.202  9676  9740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-19 19:01:23.202  9676  9740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-19 19:01:23.202  9676  9740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 19:01:23.202  9676  9740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
09-19 19:01:23.212  9676  9740 D BluetoothAdapter: STATE_ON
09-19 19:01:23.212  9676  9740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-19 19:01:23.212  9676  9740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 19:01:23.212  9676  9740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 19:01:23.212  9676  9740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 19:01:23.212  9676  9740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 19:01:23.212  9676  9740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 19:01:23.212  9676  9740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 19:01:23.212  9676  9740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 19:01:23.212  9676  9740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 19:01:23.212  9676  9740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-19 19:01:23.212  9676  9740 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 19:01:23.212  9676  9740 I io.jxcore.node.LifeCycleMonitor: start: OK
09-19 19:01:23.222  9676  9676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 19:01:23.222  9676  9676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 19:01:23.232  4024  4024 D Recents : onTaskStackChanged
09-19 19:01:23.242  4024  4024 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
09-19 19:01:23.252  9676  9676 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-19 19:01:23.252  4024  4024 D ResourcesManager: For user 0 new overlays fetched Null
09-19 19:01:23.292  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:23.472  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:23.532  9676  9741 W jxcore-log: Initializing JXcore engine
09-19 19:01:23.532  9676  9741 W jxcore-log: JXcore engine is ready
09-19 19:01:23.552  5067  5067 E audit   : type=1400 msg=audit(1474304483.552:264): avc:  denied  { ioctl } for  pid=9741 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4243 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-19 19:01:23.552  5067  5067 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-19 19:01:23.552  5067  5067 E audit   : type=1300 msg=audit(1474304483.552:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d8d853c8 items=0 ppid=3178 pid=9741 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-19 19:01:23.552  5067  5067 E audit   : type=1327 msg=audit(1474304483.552:264): proctitle="com.test.thalitest"
09-19 19:01:23.552  5067  5067 E audit   : type=1320 msg=audit(1474304483.552:264): 
09-19 19:01:23.552  5067  5067 E audit   : type=1400 msg=audit(1474304483.552:265): avc:  denied  { ioctl } for  pid=9741 comm="Thread-160" path="socket:[37133]" dev="sockfs" ino=37133 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-19 19:01:23.552  5067  5067 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-19 19:01:23.552  5067  5067 E audit   : type=1300 msg=audit(1474304483.552:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d8d853c8 items=0 ppid=3178 pid=9741 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-19 19:01:23.552  5067  5067 E audit   : type=1327 msg=audit(1474304483.552:265): proctitle="com.test.thalitest"
09-19 19:01:23.552  5067  5067 E audit   : type=1320 msg=audit(1474304483.552:265): 
09-19 19:01:23.552  9676  9741 W jxcore-log: Starting JXcore engine
09-19 19:01:23.592  9676  9741 W jxcore-log: Platform android
09-19 19:01:23.592  9676  9741 W jxcore-log: 
09-19 19:01:23.592  9676  9741 W jxcore-log: Process ARCH arm
09-19 19:01:23.592  9676  9741 W jxcore-log: 
09-19 19:01:23.652  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:23.662  9676  9741 I jxcore-log: JXcore Cordova bridge is ready!
09-19 19:01:23.662  9676  9741 I jxcore-log: 
09-19 19:01:23.662  9676  9741 W jxcore-log: JXcore engine is started
09-19 19:01:23.662  9676  9740 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-19 19:01:23.672  9676  9676 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-19 19:01:23.832  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:24.012  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:24.192  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:24.292  3407  3908 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/75_task.xml.bak
,09-19 19:01:24.372  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:24.552  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:24.732  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:24.742  3407  6345 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-19 19:01:24.912  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:25.092  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:25.272  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:25.452  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:25.632  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:25.812  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:25.992  3407  6345 D SSRM:n  : SIOP:: AP = 300, PST = 295 (W:6), CP = 223, CUR = 143, LCD = 1
,09-19 19:01:25.992  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:26.172  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:26.352  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:26.532  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:26.712  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:26.892  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:27.072  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:27.252  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:27.432  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:27.612  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:27.792  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:27.802  3407  6345 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-19 19:01:27.822  9676  9741 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-19 19:01:27.822  9676  9741 I jxcore-log: 
,09-19 19:01:27.822  9676  9741 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-19 19:01:27.822  9676  9741 I jxcore-log: 
,09-19 19:01:27.832  9676  9741 D BluetoothAdapter: STATE_ON
,09-19 19:01:27.842  9676  9741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 19:01:27.842  9676  9741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 19:01:27.842  9676  9741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 19:01:27.842  9676  9741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 19:01:27.842  9676  9741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 19:01:27.842  9676  9741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 19:01:27.842  9676  9741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 19:01:27.842  9676  9741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 19:01:27.842  9676  9741 D BluetoothAdapter: STATE_ON
,09-19 19:01:27.842  9676  9741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-19 19:01:27.852  9676  9741 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-19 19:01:27.852  9676  9741 I jxcore-log: 
09-19 19:01:27.852  9676  9741 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-19 19:01:27.852  9676  9741 I jxcore-log: 
,09-19 19:01:27.972  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:28.072  9676  9741 D executeNativeTests: Running unit tests
,09-19 19:01:28.082  9676  9741 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
,09-19 19:01:28.082  9676  9741 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-19 19:01:28.082  9676  9741 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-19 19:01:28.082  9676  9741 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-19 19:01:28.082  9676  9741 D com.test.thalitest.ThaliTestRunner: Total duration: 1 ms
09-19 19:01:28.082  9676  9741 I jxcore-log: *Native tests were executed*
09-19 19:01:28.082  9676  9741 I jxcore-log: 
,09-19 19:01:28.082  9676  9741 I jxcore-log: Total number of executed tests:  1
09-19 19:01:28.082  9676  9741 I jxcore-log: 
09-19 19:01:28.082  9676  9741 I jxcore-log: Number of passed tests:  1
09-19 19:01:28.082  9676  9741 I jxcore-log: 
09-19 19:01:28.082  9676  9741 I jxcore-log: Number of failed tests:  0
09-19 19:01:28.082  9676  9741 I jxcore-log: 
09-19 19:01:28.082  9676  9741 I jxcore-log: Number of ignored tests:  0
09-19 19:01:28.082  9676  9741 I jxcore-log: 
,09-19 19:01:28.082  9676  9741 I jxcore-log: Total duration:  1
09-19 19:01:28.082  9676  9741 I jxcore-log: 
09-19 19:01:28.082  9676  9741 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-19 19:01:28.082  9676  9741 I jxcore-log: 
09-19 19:01:28.082  9676  9741 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 19:01:28.082  9676  9741 I jxcore-log: 
,09-19 19:01:28.102  9676  9676 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-19 19:01:28.152  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:28.332  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:28.512  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:28.542  9742  9742 I FIPS_bssl: FIPS approved mode (1) | 9742 | app_process
,09-19 19:01:28.542  9742  9742 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-19 19:01:28.552  9742  9742 D AndroidRuntime: CheckJNI is OFF
,09-19 19:01:28.552  9742  9742 D AndroidRuntime: readGMSProperty: start
09-19 19:01:28.552  9742  9742 D AndroidRuntime: readGMSProperty: already setted!!
09-19 19:01:28.552  9742  9742 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-19 19:01:28.552  9742  9742 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-19 19:01:28.552  9742  9742 D AndroidRuntime: readGMSProperty: end
09-19 19:01:28.552  9742  9742 D AndroidRuntime: addProductProperty: start
,09-19 19:01:28.572  9742  9742 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-19 19:01:28.582  9742  9742 I Radio-JNI: register_android_hardware_Radio DONE
,09-19 19:01:28.592  9742  9742 E AffinityControl: AffinityControl: registerfunction enter
,09-19 19:01:28.602  9742  9742 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-19 19:01:28.602  3407  4322 D PackageManager: START PACKAGE DELETE: observer{233683687}
09-19 19:01:28.602  3407  4322 D PackageManager: pkg{<packageName>}
09-19 19:01:28.602  3407  4322 D PackageManager: user{0}
09-19 19:01:28.602  3407  4322 D PackageManager: caller{2000}
09-19 19:01:28.602  3407  4322 D PackageManager: flags{2}
,09-19 19:01:28.602  3407  4322 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-19 19:01:28.602  3407  4322 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-19 19:01:28.602  3407  4322 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-19 19:01:28.602  3407  4322 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-19 19:01:28.602  3407  4322 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-19 19:01:28.602  3407  3583 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-19 19:01:28.612  3407  3583 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-19 19:01:28.612  3407  3583 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,09-19 19:01:28.612  3407  3583 D ApplicationPolicy: getApplicationUninstallationEnabled
09-19 19:01:28.612  3407  3583 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-19 19:01:28.612  3407  3583 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-19 19:01:28.612  3407  3583 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-19 19:01:28.612  3407  3583 D PackageManager: !@killApplicatoin: 10177, uninstall pkg
,09-19 19:01:28.612  3407  3583 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-19 19:01:28.612  3407  3531 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=-1: uninstall pkg
09-19 19:01:28.612  3407  3583 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-19 19:01:28.612  3407  3531 I ActivityManager: Killing 9676:com.test.thalitest/u0a177 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-19 19:01:28.622  3407  3531 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-19 19:01:28.632  3407  3531 D ActivityManager: mDVFSHelper.acquire()
,09-19 19:01:28.642  3407  3583 D AASAinstall: there is not AASApackages.xml file
,09-19 19:01:28.692  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:28.752  3407  4345 D GraphicsStats: Buffer count: 7
09-19 19:01:28.752  3407  4824 I WindowState: WIN DEATH: Window{ab9a382 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
09-19 19:01:28.752  3407  4337 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@825f132)
,09-19 19:01:28.752  3407  3868 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-19 19:01:28.762  3407  3868 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-19 19:01:28.762  3006  4633 I SurfaceFlinger: id=21 Removed NainActivit (6/10)
,09-19 19:01:28.762  3407  3868 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-19 19:01:28.772  3006  3017 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
,09-19 19:01:28.782  3006  4633 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
,09-19 19:01:28.872  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-19 19:01:28.952  3407  3583 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-19 19:01:29.022  3407  3583 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
09-19 19:01:29.022  3407  3531 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-19 19:01:29.022  3166  3166 W keystore: ENTER clear_uid from uid 1000 for 10177
,09-19 19:01:29.022  3407  3583 I art     : Starting a blocking GC Explicit
,09-19 19:01:29.032  3407  3531 E ActivityManager: Failure starting process com.test.thalitest
09-19 19:01:29.032  3407  3531 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5277)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5194)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5032)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2643)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3481)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2595)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4997)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4958)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7379)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9146)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8769)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8924)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:458)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2597)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 19:01:29.032  3407  3531 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-19 19:01:29.032  3407  3560 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-19 19:01:29.042  3407  3560 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-19 19:01:29.042  3407  3531 I ActivityManager:   Force finishing activity ActivityRecord{2f53be u0 com.test.thalitest/.MainActivity t75}
09-19 19:01:29.042  3407  3560 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
09-19 19:01:29.042  3407  3560 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-19 19:01:29.042  3407  3560 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-19 19:01:29.042  3407  3560 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-19 19:01:29.042  3407  3560 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 19:01:29.042  3407  3560 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-19 19:01:29.042  3407  3560 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 19:01:29.042  3407  3531 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
09-19 19:01:29.042  3407  3560 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-19 19:01:29.042  3407  3560 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-19 19:01:29.042  3407  3560 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6bdee7e V.E...... R.....ID 0,0-0,0}
09-19 19:01:29.042  3407  3560 W WindowManager: Failed looking up window
09-19 19:01:29.042  3407  3560 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@fd1fdf does not exist
09-19 19:01:29.042  3407  3560 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 19:01:29.042  3407  3560 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-19 19:01:29.042  3407  3560 D ISSUE_DEBUG: InputChannelName : f6b42c Starting com.test.thalitest
09-19 19:01:29.052  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:29.062  3006  3006 I SurfaceFlinger: id=22 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-19 19:01:29.092  4324  4324 D Launcher: onRestart, Launcher: 199332777
,09-19 19:01:29.112  3407  4150 V WindowStateAnimator: Finishing drawing window Window{b39095f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-19 19:01:29.122  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fe85a4238
,09-19 19:01:29.232  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:29.232  3407  3583 I art     : Explicit concurrent mark sweep GC freed 290613(18MB) AllocSpace objects, 74(3MB) LOS objects, 31% free, 34MB/50MB, paused 1.877ms total 208.687ms
,09-19 19:01:29.262  3407  3583 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-19 19:01:29.262  3407  3583 D AASAuninstall: userId = 0, info.removedAppID = 10177, info.uid = 10177, packageName = com.test.thalitest
,09-19 19:01:29.272  3407  3583 D AASAinstall: there is not AASApackages.xml file
09-19 19:01:29.272  3407  3583 D PackageManager: result of delete: 1{233683687}
,09-19 19:01:29.272  3407  3583 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-19 19:01:29.272  3407  3583 D PackageManager: userId{-1}
09-19 19:01:29.272  3407  3583 D PackageManager: andCode{true}
09-19 19:01:29.272  9742  9742 I art     : System.exit called, status: 0
09-19 19:01:29.272  9742  9742 I AndroidRuntime: VM exiting with result code 0.
,09-19 19:01:29.382  3407  3531 I WindowManager: Screenshot max retries 4 of Token{ab8a026 ActivityRecord{1c7b781 u0 com.samsung.android.MtpApplication/.USBConnection t74}} appWin=Window{b39095f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=2
,09-19 19:01:29.382  5822  5833 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,09-19 19:01:29.382  3407  3407 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-19 19:01:29.382  5822  5832 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} Intent { flg=0x10800000 cmp=com.samsung.android.MtpApplication/.USBConnection VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-19 19:01:29.392  3006  3006 I SurfaceFlinger: id=23 createSurf (1440x2560),1 flag=404, uhalitest
09-19 19:01:29.402  3407  3560 D ViewRootImpl: #3 mView = null
09-19 19:01:29.402  3006  3832 I SurfaceFlinger: id=23 Removed uhalitest (7/11)
09-19 19:01:29.402  3006  3907 I SurfaceFlinger: id=23 Removed uhalitest (-2/11)
09-19 19:01:29.412  3407  3531 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
09-19 19:01:29.412  3407  3795 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-19 19:01:29.422  3407  3531 D InputDispatcher: Focused application released
,09-19 19:01:29.422  3407  3583 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=0: pkg removed
,09-19 19:01:29.432  9210  9755 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-19 19:01:29.442  9210  9755 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-19 19:01:29.442  9210  9755 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-19 19:01:29.472  3407  4337 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-19 19:01:29.472  3407  4337 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-19 19:01:29.472  3407  3407 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-19 19:01:29.472  4324  4324 D Launcher: onStart, Launcher: 199332777
09-19 19:01:29.472  3407  3531 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-19 19:01:29.472  4324  4324 D Launcher.HomeView: onStart
09-19 19:01:29.472  3407  3531 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
09-19 19:01:29.472  3407  3560 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-19 19:01:29.472  3407  3407 I KnoxTimeoutHandler: Shared devices show user statefalse
09-19 19:01:29.472  3407  3407 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
09-19 19:01:29.472  3407  3407 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-19 19:01:29.482  3006  3006 I SurfaceFlinger: id=24 createSurf (1592x384),1 flag=4, VSBConnecti
,09-19 19:01:29.482  4324  4324 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-19 19:01:29.482  4324  4324 V ActivityThread: updateVisibility : ActivityRecord{71c4855 token=android.os.BinderProxy@f76aa5c {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-19 19:01:29.492  3407  3407 I KnoxTimeoutHandler: SD activityfalse

```
