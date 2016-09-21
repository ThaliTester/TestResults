#### Test 850469111b8590e_thali05_samsung-SM-G935F Logs


```
--------- beginning of main
,09-21 11:58:43.260  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:43.260  4735  4735 I AODService: onSensorChanged: lux [0.0], NIT state [LOW]
09-21 11:58:43.440  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:43.620  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:43.720  9663  9663 I FIPS_bssl: FIPS approved mode (1) | 9663 | app_process
09-21 11:58:43.730  9663  9663 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 11:58:43.730  9663  9663 D AndroidRuntime: CheckJNI is OFF
09-21 11:58:43.730  9663  9663 D AndroidRuntime: readGMSProperty: start
09-21 11:58:43.730  9663  9663 D AndroidRuntime: readGMSProperty: already setted!!
09-21 11:58:43.730  9663  9663 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-21 11:58:43.730  9663  9663 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-21 11:58:43.730  9663  9663 D AndroidRuntime: readGMSProperty: end
09-21 11:58:43.730  9663  9663 D AndroidRuntime: addProductProperty: start
09-21 11:58:43.750  9663  9663 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 11:58:43.770  9663  9663 I Radio-JNI: register_android_hardware_Radio DONE
09-21 11:58:43.780  9663  9663 E AffinityControl: AffinityControl: registerfunction enter
09-21 11:58:43.780  9663  9663 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-21 11:58:43.800  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:43.810  3416  4440 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-21 11:58:43.810  3416  4440 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-21 11:58:43.830  3416  4440 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:43.840  3416  4440 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 11:58:43.840  3416  4440 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-21 11:58:43.840  3416  4440 D ActivityManager: mDVFSHelper.acquire()
09-21 11:58:43.850  3416  4440 V WindowManager: addAppToken: AppWindowToken{d0c07814d token=Token{5c458e4 ActivityRecord{54c0477 u0 com.test.thalitest/.MainActivity t12}}} to stack=2 task=12 at 0
09-21 11:58:43.850  3416  3534 I InjectionManager: Inside getClassLibPath caller 
09-21 11:58:43.860  3416  3534 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-21 11:58:43.860  3416  3534 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6308d05 V.E...... R.....ID 0,0-0,0}
09-21 11:58:43.860  3416  3534 W WindowManager: Failed looking up window
09-21 11:58:43.860  3416  3534 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@481c15a does not exist
09-21 11:58:43.860  3416  3534 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 11:58:43.860  3416  3534 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-21 11:58:43.860  3416  3534 D ISSUE_DEBUG: InputChannelName : 9c4ef8b Starting com.test.thalitest
09-21 11:58:43.870  9672  9672 E Zygote  : v2
09-21 11:58:43.870  9672  9672 I libpersona: KNOX_SDCARD checking this for 10177
09-21 11:58:43.870  9672  9672 I libpersona: KNOX_SDCARD not a persona
09-21 11:58:43.870  9672  9672 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-21 11:58:43.870  9672  9672 E Zygote  : accessInfo : 0
09-21 11:58:43.870  9672  9672 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-21 11:58:43.870  3006  3006 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-21 11:58:43.880  3416  4440 I ActivityManager: Start proc 9672:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-21 11:58:43.900  9672  9672 D TimaKeyStoreProvider: TimaSignature is unavailable
09-21 11:58:43.900  9672  9672 D ActivityThread: Added TimaKeyStore provider
09-21 11:58:43.910  6170  6170 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 11:58:43.910  3416  4181 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3416
09-21 11:58:43.910  3416  4181 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 11:58:43.910  3416  4181 D PowerManagerService: mDisplayReady: false
09-21 11:58:43.910  3416  4181 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 11:58:43.910  3416  3539 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 11:58:43.910  3416  4440 D InputDispatcher: Focused application set to: xxxx
09-21 11:58:43.910  3416  3539 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 11:58:43.910  6170  6170 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 11:58:43.910  3416  4181 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 11:58:43.910  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7faac03c00
09-21 11:58:43.910  3416  3539 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 11:58:43.910  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-21 11:58:43.910  3416  3539 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 11:58:43.910  3416  3552 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-21 11:58:43.920  9663  9663 D AndroidRuntime: Shutting down VM
09-21 11:58:43.920  3416  3859 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-21 11:58:43.920  3416  3539 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 11:58:43.920  3416  3539 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 11:58:43.920  3416  3539 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 11:58:43.920  3416  3539 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 11:58:43.920  3416  3539 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 11:58:43.920  3416  3539 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 11:58:43.920  3416  3539 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 11:58:43.920  3416  3539 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 11:58:43.920  3416  3539 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 11:58:43.920  3416  3539 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 11:58:43.920  3416  3539 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 11:58:43.920  3416  3539 D PowerManagerService: mDisplayReady: true
09-21 11:58:43.920  3416  3539 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-21 11:58:43.920  3416  3444 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3416
09-21 11:58:43.930  3416  4458 D ActivityManager:  Launching com.test.thalitest, updated priority
09-21 11:58:43.930  4313  4313 V ActivityThread: updateVisibility : ActivityRecord{7fdcd43 token=android.os.BinderProxy@e34921a {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-21 11:58:43.940  3416  3856 V WindowStateAnimator: Finishing drawing window Window{16dbde u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-21 11:58:43.950  3416  3416 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-21 11:58:43.950  5829  6651 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-21 11:58:43.950  3416  3505 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-21 11:58:43.960  3006  3556 D libEGL  : eglTerminate EGLDisplay = 0x7fa433ee78
09-21 11:58:43.960  3006  3556 D libEGL  : eglTerminate EGLDisplay = 0x7fa433ee78
09-21 11:58:43.960  3006  4525 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-21 11:58:43.960  3006  3558 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-21 11:58:43.970  4313  4313 D Launcher: onTrimMemory. Level: 20
09-21 11:58:43.970  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fc8866cd8
09-21 11:58:43.970  3416  3969 V WindowStateAnimator: Finishing drawing window Window{7322e60 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-21 11:58:43.970  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:43.980  6170  6170 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 11:58:43.980  6170  6170 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-21 11:58:43.980  6170  6170 V ActivityThread: updateVisibility : ActivityRecord{492cbde token=android.os.BinderProxy@b145ad3 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-21 11:58:43.980  3006  3558 I SurfaceFlinger: id=18 Removed VSBConnecti (7/12)
09-21 11:58:43.980  3006  3015 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/12)
09-21 11:58:43.980  3006  3015 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
09-21 11:58:43.980  3006  3556 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
09-21 11:58:43.990  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fc8866cd8
09-21 11:58:43.990  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fc8866ca8
09-21 11:58:43.990  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fc8866ca8
09-21 11:58:44.060  3416  3416 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3416 (0x0)
09-21 11:58:44.070  3416  3416 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3416 (0x0)
09-21 11:58:44.070  3416  3416 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 11:58:44.070  3416  3416 D PowerManagerService: mDisplayReady: false
09-21 11:58:44.070  3416  3416 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 11:58:44.070  3416  3539 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 11:58:44.070  3416  3539 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 11:58:44.070  3416  3416 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 11:58:44.070  3416  3539 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 11:58:44.070  3416  3539 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 11:58:44.070  3416  3552 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-21 11:58:44.070  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7faac03c00
09-21 11:58:44.070  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-21 11:58:44.080  3416  3539 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 11:58:44.080  3416  3539 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 11:58:44.080  3416  3539 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 11:58:44.080  3416  3539 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 11:58:44.080  3416  3539 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 11:58:44.080  3416  3539 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 11:58:44.080  3416  3539 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 11:58:44.080  3416  3539 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 11:58:44.080  3416  3539 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 11:58:44.080  3416  3539 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 11:58:44.080  3416  3539 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 11:58:44.080  3416  3539 D PowerManagerService: mDisplayReady: true
09-21 11:58:44.080  3416  3539 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-21 11:58:44.160  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:44.250  5829  5829 I TrayVisibilityController: handleMessage : msg.what = 1
09-21 11:58:44.270  3416  4458 I WindowManager: Screenshot max retries 4 of Token{5c458e4 ActivityRecord{54c0477 u0 com.test.thalitest/.MainActivity t12}} appWin=Window{9c4ef8b u0 d0 Starting com.test.thalitest} drawState=1
09-21 11:58:44.270  5829  5840 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-21 11:58:44.270  3416  3534 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 11:58:44.280  3416  3534 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-21 11:58:44.280  5829  5829 I Utils   : isCurrentUser current = 0, ownerId = 0
09-21 11:58:44.280  5829  5829 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-21 11:58:44.280  5829  5829 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-21 11:58:44.280  3416  3416 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 11:58:44.280  3416  3859 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-21 11:58:44.280  3416  6117 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 11:58:44.280  3416  6117 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 11:58:44.290  3416  3416 I KnoxTimeoutHandler: SD activityfalse
09-21 11:58:44.310  3416  6117 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-21 11:58:44.320  3416  6117 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 11:58:44.320  9672  9672 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-21 11:58:44.320  9672  9672 D RelationGraph: garbageCollect()
09-21 11:58:44.330  3416  3534 V WindowStateAnimator: Finishing drawing window Window{9c4ef8b u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-21 11:58:44.330  3416  3534 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 11:58:44.330  3416  3416 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 11:58:44.330  3416  3534 D ActivityManager: mDVFSHelper.release()
09-21 11:58:44.330  3416  3534 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ba4ec3a u0 com.samsung.android.MtpApplication/.USBConnection t11} time:197141
09-21 11:58:44.330  9672  9672 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 11:58:44.330  3416  3416 I KnoxTimeoutHandler: SD activityfalse
09-21 11:58:44.330  3416  6117 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-21 11:58:44.330  3416  4325 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-21 11:58:44.330  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:44.330  9672  9672 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-21 11:58:44.340  3416  6117 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 11:58:44.340  3416  6117 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 11:58:44.350  9672  9672 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:44.350  9672  9672 I InjectionManager: Inside getClassLibPath caller 
09-21 11:58:44.350  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc8866bb8
09-21 11:58:44.360  9672  9672 D InjectionManager: InjectionManager
09-21 11:58:44.360  9672  9672 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-21 11:58:44.370  9672  9672 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-21 11:58:44.370  9672  9672 I InjectionManager: featureStore :{}
09-21 11:58:44.370  9672  9672 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 11:58:44.370  9672  9672 D RelationGraph: garbageCollect()
09-21 11:58:44.370  9672  9672 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 11:58:44.410  9672  9672 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-21 11:58:44.480  9672  9672 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-21 11:58:44.480  9672  9672 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:44.480  9672  9672 I InjectionManager: Inside getClassLibPath caller 
09-21 11:58:44.490  9672  9672 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-21 11:58:44.520  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:44.530  3416  3883 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-21 11:58:44.550  9672  9672 I cr_LibraryLoader: Time to load native libraries: 35 ms (timestamps 7328-7363)
09-21 11:58:44.550  9672  9672 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-21 11:58:44.600  9672  9687 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-21 11:58:44.610  9672  9672 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c34f39f}
09-21 11:58:44.610  9672  9672 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-21 11:58:44.630  3416  3883 I MdnieScenarioControlService: mGameModeLauncher : false
09-21 11:58:44.630  3416  3883 I MdnieScenarioControlService: setUIMode
09-21 11:58:44.640  9672  9672 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-21 11:58:44.670  9672  9672 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-21 11:58:44.690  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:44.770  3416  3505 W ActivityManager: Activity pause timeout for ActivityRecord{54c0477 u0 com.test.thalitest/.MainActivity t12}
09-21 11:58:44.870  9672  9672 D libEGL  : eglInitialize EGLDisplay = 0xffcbdbdc
09-21 11:58:44.870  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:44.960  3416  4090 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
09-21 11:58:44.960  3416  4090 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-21 11:58:45.050  9672  9672 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-21 11:58:45.050  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:45.070  9672  9672 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-21 11:58:45.070  9672  9672 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-21 11:58:45.110  9672  9672 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-21 11:58:45.160  9672  9672 D Activity: performCreate Call Injection manager
,09-21 11:58:45.160  9672  9672 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-21 11:58:45.170  9672  9672 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-21 11:58:45.180  9672  9672 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{cef16aa I.E...... R.....ID 0,0-0,0}
,09-21 11:58:45.190  9672  9724 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-21 11:58:45.190  3416  3444 W WindowManager: Failed looking up window
09-21 11:58:45.190  3416  3444 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@8d4f4ba does not exist
09-21 11:58:45.190  3416  3444 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-21 11:58:45.190  3416  3444 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-21 11:58:45.190  3416  3444 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-21 11:58:45.190  3416  3444 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-21 11:58:45.190  3416  3444 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-21 11:58:45.190  3416  3444 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-21 11:58:45.200  3416  3445 D ISSUE_DEBUG: InputChannelName : 7190f6b com.test.thalitest/com.test.thalitest.MainActivity
,09-21 11:58:45.200  3416  4956 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,09-21 11:58:45.200  3416  4956 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 11:58:45.210  3416  3416 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-21 11:58:45.210  3416  3416 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-21 11:58:45.210  9672  9672 V ActivityThread: updateVisibility : ActivityRecord{122a638 token=android.os.BinderProxy@3bf96fd {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-21 11:58:45.220  9672  9687 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-21 11:58:45.230  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:45.250  9672  9672 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9672
,09-21 11:58:45.260  3416  4956 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9672 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-21 11:58:45.260  3416  3870 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-21 11:58:45.260  3416  3870 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-21 11:58:45.270  3416  3870 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-21 11:58:45.280  3416  6118 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-21 11:58:45.280  3416  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-21 11:58:45.290  3416  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-21 11:58:45.290  9672  9672 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-21 11:58:45.290  3416  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-21 11:58:45.300  3416  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-21 11:58:45.310  3416  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-21 11:58:45.310  3416  3870 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-21 11:58:45.320  3006  3006 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,09-21 11:58:45.350  9672  9724 D libEGL  : eglInitialize EGLDisplay = 0xdc53f7c4
09-21 11:58:45.350  9672  9724 I OpenGLRenderer: Initialized EGL, version 1.4
,09-21 11:58:45.360  9672  9724 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-21 11:58:45.360  3416  4326 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3416
,09-21 11:58:45.360  3416  4326 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 11:58:45.360  3416  4326 D PowerManagerService: mDisplayReady: false
09-21 11:58:45.360  3416  4326 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 11:58:45.360  3416  4326 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 11:58:45.370  3416  3539 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 11:58:45.370  3416  3539 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,09-21 11:58:45.370  3416  3539 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 11:58:45.370  3416  3539 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 11:58:45.370  3416  3552 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,09-21 11:58:45.370  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7faac03c00
09-21 11:58:45.370  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-21 11:58:45.370  3416  3534 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-21 11:58:45.370  3416  3534 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-21 11:58:45.390  3416  3539 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 11:58:45.390  3416  3539 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 11:58:45.390  3416  3539 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 11:58:45.390  3416  3539 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 11:58:45.390  3416  3539 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 11:58:45.390  3416  3539 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 11:58:45.390  3416  3539 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-21 11:58:45.390  3416  3539 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-21 11:58:45.390  3416  3539 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 11:58:45.390  3416  3539 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 11:58:45.390  3416  3539 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 11:58:45.390  3416  3539 D PowerManagerService: mDisplayReady: true
09-21 11:58:45.390  3416  3539 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-21 11:58:45.400  5829  5829 E CocktailBarPositionManager: Window direction: 0
09-21 11:58:45.400  5829  5829 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-21 11:58:45.410  9672  9672 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-21 11:58:45.420  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:45.430  3416  4325 V WindowStateAnimator: Finishing drawing window Window{7190f6b u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-21 11:58:45.430  9672  9672 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-21 11:58:45.440  3416  3969 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3416
09-21 11:58:45.440  3416  3534 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 11:58:45.440  3416  3416 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 11:58:45.440  3416  3534 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s166ms (total +1s590ms)
09-21 11:58:45.440  3416  3534 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{54c0477 u0 com.test.thalitest/.MainActivity t12} time:198254
09-21 11:58:45.440  3416  3534 D ViewRootImpl: #3 mView = null
09-21 11:58:45.440  3006  3558 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
09-21 11:58:45.440  3416  3416 I KnoxTimeoutHandler: SD activityfalse
09-21 11:58:45.440  3006  3015 I SurfaceFlinger: id=20 Removed uhalitest (-2/11)
09-21 11:58:45.450  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fc8866cd8
09-21 11:58:45.450  3416  4440 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3416
09-21 11:58:45.450  9672  9728 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 11:58:45.450  9672  9728 D libEGL  : eglInitialize EGLDisplay = 0xda8ec3f4
09-21 11:58:45.460  3416  3445 V WindowStateAnimator: Finishing drawing window Window{7190f6b u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-21 11:58:45.460  9672  9672 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3bf96fd time:198273
09-21 11:58:45.470  9672  9728 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-21 11:58:45.530  9672  9672 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9672
09-21 11:58:45.590  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:45.600  3416  3416 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3416 (0x0)
09-21 11:58:45.600  3416  3416 I libsuspend: !@autosuspend_wakeup_count_disable
09-21 11:58:45.600  3416  3416 D PowerManagerService: mDisplayReady: false
09-21 11:58:45.600  3416  3416 I libsuspend: !@autosuspend_wakeup_count_disable done
09-21 11:58:45.600  3416  3416 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-21 11:58:45.600  3416  3539 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 11:58:45.600  3416  3539 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 11:58:45.600  3416  3539 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 11:58:45.600  3416  3539 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 11:58:45.600  3416  3552 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-21 11:58:45.600  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7faac03c00
09-21 11:58:45.600  3416  3534 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-21 11:58:45.600  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-21 11:58:45.600  3416  3534 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-21 11:58:45.610  3416  3539 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 11:58:45.610  3416  3539 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 11:58:45.610  3416  3539 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 11:58:45.610  3416  3539 I libsuspend: !@autosuspend_wakeup_count_enable
09-21 11:58:45.610  3416  3539 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 11:58:45.610  3416  3539 I libsuspend: !@autosuspend_wakeup_count_enable done
09-21 11:58:45.610  3416  3539 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-21 11:58:45.610  3416  3539 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-21 11:58:45.610  3416  3539 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-21 11:58:45.610  3416  3539 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-21 11:58:45.610  3416  3539 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-21 11:58:45.610  3416  3539 D PowerManagerService: mDisplayReady: true
09-21 11:58:45.610  3416  3539 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-21 11:58:45.630  5829  5829 E CocktailBarPositionManager: Window direction: 0
09-21 11:58:45.630  5829  5829 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-21 11:58:45.750  9672  9672 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-21 11:58:45.770  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:45.770  4029  4029 D Recents : onTaskStackChanged
09-21 11:58:45.780  4029  4029 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
09-21 11:58:45.790  4029  4029 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:45.840  9672  9735 D jxcore_app_log: JniHelper::setJavaVM(0xf4b34000), pthread_self() = -646448848
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2527e5a added. We now have 1 listener(s)
09-21 11:58:45.850  9672  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
09-21 11:58:45.850  9672  9735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-21 11:58:45.850  9672  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:58:45.850  9672  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-21 11:58:45.850  9672  9735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2139581 added. We now have 1 listener(s)
09-21 11:58:45.850  9672  9735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:45.860  9672  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 11:58:45.860  9672  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-21 11:58:45.860  9672  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-21 11:58:45.860  9672  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 11:58:45.860  9672  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-21 11:58:45.860  9672  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:58:45.860  9672  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
09-21 11:58:45.870  9672  9735 D BluetoothAdapter: STATE_ON
09-21 11:58:45.870  9672  9735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-21 11:58:45.870  9672  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:45.870  9672  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:45.870  9672  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:45.870  9672  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:45.870  9672  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:45.870  9672  9735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:45.870  9672  9735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:58:45.870  9672  9735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 11:58:45.870  9672  9735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-21 11:58:45.870  9672  9735 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 11:58:45.880  9672  9735 I io.jxcore.node.LifeCycleMonitor: start: OK
09-21 11:58:45.880  9672  9672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:45.880  9672  9672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:45.900  9672  9672 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-21 11:58:45.950  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:46.130  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:46.230  9672  9736 W jxcore-log: Initializing JXcore engine
09-21 11:58:46.230  9672  9736 W jxcore-log: JXcore engine is ready
,09-21 11:58:46.250  5015  5015 E audit   : type=1400 msg=audit(1474451926.250:264): avc:  denied  { ioctl } for  pid=9736 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4247 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-21 11:58:46.250  5015  5015 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-21 11:58:46.250  5015  5015 E audit   : type=1300 msg=audit(1474451926.250:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d8b7f3c8 items=0 ppid=3179 pid=9736 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-21 11:58:46.250  5015  5015 E audit   : type=1327 msg=audit(1474451926.250:264): proctitle="com.test.thalitest"
09-21 11:58:46.250  5015  5015 E audit   : type=1320 msg=audit(1474451926.250:264): 
09-21 11:58:46.250  5015  5015 E audit   : type=1400 msg=audit(1474451926.250:265): avc:  denied  { ioctl } for  pid=9736 comm="Thread-160" path="socket:[38092]" dev="sockfs" ino=38092 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 11:58:46.250  5015  5015 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-21 11:58:46.250  5015  5015 E audit   : type=1300 msg=audit(1474451926.250:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d8b7f3c8 items=0 ppid=3179 pid=9736 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-21 11:58:46.250  5015  5015 E audit   : type=1327 msg=audit(1474451926.250:265): proctitle="com.test.thalitest"
09-21 11:58:46.250  5015  5015 E audit   : type=1320 msg=audit(1474451926.250:265): 
,09-21 11:58:46.250  9672  9736 W jxcore-log: Starting JXcore engine
,09-21 11:58:46.290  9672  9736 W jxcore-log: Platform android
09-21 11:58:46.290  9672  9736 W jxcore-log: 
09-21 11:58:46.290  9672  9736 W jxcore-log: Process ARCH arm
09-21 11:58:46.290  9672  9736 W jxcore-log: 
,09-21 11:58:46.310  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:46.360  9672  9736 I jxcore-log: JXcore Cordova bridge is ready!
09-21 11:58:46.360  9672  9736 I jxcore-log: 
09-21 11:58:46.360  9672  9736 W jxcore-log: JXcore engine is started
,09-21 11:58:46.360  9672  9735 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-21 11:58:46.370  9672  9672 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-21 11:58:46.490  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:46.670  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:46.850  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:46.860  3416  3909 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/12_task.xml.bak
,09-21 11:58:47.030  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:47.210  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:47.290  3416  6117 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-21 11:58:47.390  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:47.570  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:47.750  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:47.930  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:48.110  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:48.290  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:48.470  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:48.650  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:48.830  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:49.010  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:49.190  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:49.370  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:49.550  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:49.730  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:49.750  3416  6117 D SSRM:n  : SIOP:: AP = 330, PST = 307 (W:6), CP = 241, CUR = 254, LCD = 1
,09-21 11:58:49.910  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:50.090  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:50.270  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:50.350  3416  6117 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-21 11:58:50.450  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:50.510  9672  9736 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-21 11:58:50.510  9672  9736 I jxcore-log: 
,09-21 11:58:50.510  9672  9736 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-21 11:58:50.510  9672  9736 I jxcore-log: 
,09-21 11:58:50.520  9672  9736 D BluetoothAdapter: STATE_ON
,09-21 11:58:50.520  9672  9736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:50.520  9672  9736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:50.520  9672  9736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:50.520  9672  9736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:50.520  9672  9736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:50.520  9672  9736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:50.520  9672  9736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:58:50.520  9672  9736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 11:58:50.530  9672  9736 D BluetoothAdapter: STATE_ON
,09-21 11:58:50.530  9672  9736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 11:58:50.530  9672  9736 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-21 11:58:50.530  9672  9736 I jxcore-log: 
09-21 11:58:50.530  9672  9736 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-21 11:58:50.530  9672  9736 I jxcore-log: 
,09-21 11:58:50.630  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:50.710  3416  4090 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-21 11:58:50.710  3416  4090 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-21 11:58:50.710  3416  4090 D BatteryService: online:4, current avg:84, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-229
09-21 11:58:50.710  3416  4090 D BatteryService: stay LED for fully charged
09-21 11:58:50.710  3416  3416 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-21 11:58:50.710  3416  3416 I MotionRecognitionService: Plugged
,09-21 11:58:50.710  3416  3416 D MotionRecognitionService:   cableConnection= 1
09-21 11:58:50.710  3416  3416 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-21 11:58:50.710  3416  3416 D MotionRecognitionService: skip setTransmitPower. 
,09-21 11:58:50.720  3416  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-21 11:58:50.720  3939  3939 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-21 11:58:50.720  3939  3939 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-21 11:58:50.720  3939  3939 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-21 11:58:50.730  5048  5048 D CommonServiceConfiguration: getStringValueSetting
,09-21 11:58:50.740  5005  5005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-21 11:58:50.740  5005  5414 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-21 11:58:50.740  5048  5048 D BatteryMonitor: new battery level: 100
,09-21 11:58:50.740  4735  4735 D BatteryController: saveBatteryData : level[100], status[5]
,09-21 11:58:50.750  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-21 11:58:50.750  3939  3939 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-21 11:58:50.810  9672  9736 D executeNativeTests: Running unit tests
,09-21 11:58:50.810  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:50.820  9672  9736 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
,09-21 11:58:50.820  9672  9736 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-21 11:58:50.820  9672  9736 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-21 11:58:50.820  9672  9736 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-21 11:58:50.820  9672  9736 D com.test.thalitest.ThaliTestRunner: Total duration: 1 ms
09-21 11:58:50.820  9672  9736 I jxcore-log: *Native tests were executed*
09-21 11:58:50.820  9672  9736 I jxcore-log: 
09-21 11:58:50.820  9672  9736 I jxcore-log: Total number of executed tests:  1
09-21 11:58:50.820  9672  9736 I jxcore-log: 
,09-21 11:58:50.820  9672  9736 I jxcore-log: Number of passed tests:  1
09-21 11:58:50.820  9672  9736 I jxcore-log: 
09-21 11:58:50.820  9672  9736 I jxcore-log: Number of failed tests:  0
09-21 11:58:50.820  9672  9736 I jxcore-log: 
09-21 11:58:50.820  9672  9736 I jxcore-log: Number of ignored tests:  0
09-21 11:58:50.820  9672  9736 I jxcore-log: 
09-21 11:58:50.820  9672  9736 I jxcore-log: Total duration:  1
09-21 11:58:50.820  9672  9736 I jxcore-log: 
,09-21 11:58:50.820  9672  9736 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-21 11:58:50.820  9672  9736 I jxcore-log: 
09-21 11:58:50.820  9672  9736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 11:58:50.820  9672  9736 I jxcore-log: 
,09-21 11:58:50.840  9672  9672 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-21 11:58:50.990  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:51.170  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:51.290  9738  9738 I FIPS_bssl: FIPS approved mode (1) | 9738 | app_process
,09-21 11:58:51.290  9738  9738 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-21 11:58:51.290  9738  9738 D AndroidRuntime: CheckJNI is OFF
09-21 11:58:51.290  9738  9738 D AndroidRuntime: readGMSProperty: start
09-21 11:58:51.290  9738  9738 D AndroidRuntime: readGMSProperty: already setted!!
09-21 11:58:51.290  9738  9738 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-21 11:58:51.290  9738  9738 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-21 11:58:51.290  9738  9738 D AndroidRuntime: readGMSProperty: end
09-21 11:58:51.290  9738  9738 D AndroidRuntime: addProductProperty: start
,09-21 11:58:51.310  9738  9738 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-21 11:58:51.330  9738  9738 I Radio-JNI: register_android_hardware_Radio DONE
,09-21 11:58:51.330  9738  9738 E AffinityControl: AffinityControl: registerfunction enter
,09-21 11:58:51.340  9738  9738 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-21 11:58:51.350  3416  4326 D PackageManager: START PACKAGE DELETE: observer{112960780}
09-21 11:58:51.350  3416  4326 D PackageManager: pkg{<packageName>}
09-21 11:58:51.350  3416  4326 D PackageManager: user{0}
09-21 11:58:51.350  3416  4326 D PackageManager: caller{2000}
09-21 11:58:51.350  3416  4326 D PackageManager: flags{2}
,09-21 11:58:51.350  3416  4326 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-21 11:58:51.350  3416  4326 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-21 11:58:51.350  3416  4326 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-21 11:58:51.350  3416  4326 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-21 11:58:51.350  3416  4326 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-21 11:58:51.350  3416  3564 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,09-21 11:58:51.350  3416  3564 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-21 11:58:51.350  3416  3564 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-21 11:58:51.350  3416  3564 D ApplicationPolicy: getApplicationUninstallationEnabled
09-21 11:58:51.350  3416  3564 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-21 11:58:51.350  3416  3564 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-21 11:58:51.350  3416  3564 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-21 11:58:51.350  3416  3564 D PackageManager: !@killApplicatoin: 10177, uninstall pkg
,09-21 11:58:51.350  3416  3505 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=-1: uninstall pkg
09-21 11:58:51.350  3416  3564 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-21 11:58:51.350  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:51.350  3416  3564 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-21 11:58:51.350  3416  3505 I ActivityManager: Killing 9672:com.test.thalitest/u0a177 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-21 11:58:51.360  3416  3505 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-21 11:58:51.370  3416  3505 D ActivityManager: mDVFSHelper.acquire()
,09-21 11:58:51.380  3416  3564 D AASAinstall: there is not AASApackages.xml file
,09-21 11:58:51.480  3416  3445 D GraphicsStats: Buffer count: 7
09-21 11:58:51.480  3416  4458 I WindowState: WIN DEATH: Window{7190f6b u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
09-21 11:58:51.480  3416  4326 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@dc0a95b)
,09-21 11:58:51.480  3416  3870 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-21 11:58:51.480  3416  3870 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-21 11:58:51.480  3416  3870 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-21 11:58:51.480  3006  3556 I SurfaceFlinger: id=21 Removed NainActivit (6/10)
,09-21 11:58:51.480  3006  3556 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
,09-21 11:58:51.490  3006  4525 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
,09-21 11:58:51.530  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:51.670  3416  3564 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-21 11:58:51.710  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:51.730  3416  3564 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-21 11:58:51.730  3416  3505 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-21 11:58:51.740  3167  3167 W keystore: ENTER clear_uid from uid 1000 for 10177
,09-21 11:58:51.740  3416  3564 I art     : Waiting for a blocking GC Explicit
09-21 11:58:51.740  3416  3505 E ActivityManager: Failure starting process com.test.thalitest
09-21 11:58:51.740  3416  3505 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5277)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5194)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5032)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2643)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3481)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2595)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4997)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4958)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7379)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9146)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8769)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8924)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:458)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2597)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 11:58:51.740  3416  3505 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-21 11:58:51.740  3416  3534 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-21 11:58:51.740  3416  3534 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-21 11:58:51.740  3416  3534 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
09-21 11:58:51.740  3416  3534 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-21 11:58:51.740  3416  3534 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-21 11:58:51.740  3416  3534 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-21 11:58:51.740  3416  3534 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:51.740  3416  3534 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-21 11:58:51.740  3416  3534 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 11:58:51.740  3416  3534 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-21 11:58:51.740  3416  3534 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-21 11:58:51.740  3416  3534 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6568037 V.E...... R.....ID 0,0-0,0}
,09-21 11:58:51.740  3416  3505 I ActivityManager:   Force finishing activity ActivityRecord{54c0477 u0 com.test.thalitest/.MainActivity t12}
,09-21 11:58:51.750  3416  3505 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
09-21 11:58:51.750  3416  3534 W WindowManager: Failed looking up window
09-21 11:58:51.750  3416  3534 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@f6f89a4 does not exist
09-21 11:58:51.750  3416  3534 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 11:58:51.750  3416  3534 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-21 11:58:51.750  3416  3534 D ISSUE_DEBUG: InputChannelName : 745c30d Starting com.test.thalitest
,09-21 11:58:51.770  5829  5840 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,09-21 11:58:51.770  3416  3416 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-21 11:58:51.770  5829  5840 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} Intent { flg=0x10800000 cmp=com.samsung.android.MtpApplication/.USBConnection VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-21 11:58:51.800  3006  3006 I SurfaceFlinger: id=22 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-21 11:58:51.800  3416  3505 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-21 11:58:51.800  4313  4313 D Launcher: onRestart, Launcher: 113234223
,09-21 11:58:51.810  3416  3505 D InputDispatcher: Focused application released
,09-21 11:58:51.810  3416  3534 W WindowManager: Failed looking up window
09-21 11:58:51.810  3416  3534 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@f6f89a4 does not exist
09-21 11:58:51.810  3416  3534 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14795)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at com.android.server.wm.WindowManagerService.relayoutWindow(WindowManagerService.java:5208)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at com.android.server.wm.Session.relayout(Session.java:208)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.view.ViewRootImpl.relayoutWindow(ViewRootImpl.java:6690)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1994)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1437)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:7403)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:920)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.view.Choreographer.doCallbacks(Choreographer.java:695)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.view.Choreographer.doFrame(Choreographer.java:631)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:906)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.os.Handler.handleCallback(Handler.java:739)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-21 11:58:51.810  3416  3534 E ViewSystem: ViewRootImpl #2 Surface is not valid.
,09-21 11:58:51.810  3416  3534 D ViewRootImpl: #3 mView = null
,09-21 11:58:51.810  3416  3534 W WindowManager: Failed looking up window
09-21 11:58:51.810  3416  3534 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@f6f89a4 does not exist
09-21 11:58:51.810  3416  3534 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14795)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:4612)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:196)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3754)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:6893)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:4238)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 11:58:51.810  3416  3534 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-21 11:58:51.820  4313  4313 D Launcher: onStart, Launcher: 113234223
09-21 11:58:51.820  3416  6117 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
09-21 11:58:51.820  3416  3981 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-21 11:58:51.820  3416  3981 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-21 11:58:51.820  4313  4313 D Launcher.HomeView: onStart
09-21 11:58:51.820  3416  3416 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-21 11:58:51.830  3416  3416 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-21 11:58:51.830  3416  3416 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-21 11:58:51.830  3416  3427 I art     : Background sticky concurrent mark sweep GC freed 204384(12MB) AllocSpace objects, 72(1580KB) LOS objects, 24% free, 42MB/56MB, paused 2.515ms total 143.953ms
09-21 11:58:51.830  3416  3564 I art     : WaitForGcToComplete blocked for 88.960ms for cause Explicit
09-21 11:58:51.830  3416  3564 I art     : Starting a blocking GC Explicit
09-21 11:58:51.830  4313  4313 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-21 11:58:51.830  4313  4313 V ActivityThread: updateVisibility : ActivityRecord{7fdcd43 token=android.os.BinderProxy@e34921a {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-21 11:58:51.830  4313  4313 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
,09-21 11:58:51.830  4313  4313 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
,09-21 11:58:51.830  4313  4313 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
09-21 11:58:51.830  4313  4313 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
,09-21 11:58:51.840  4313  4313 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
,09-21 11:58:51.840  4313  4313 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
09-21 11:58:51.840  4313  4313 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-21 11:58:51.840  4313  4313 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
09-21 11:58:51.840  4313  4313 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
,09-21 11:58:51.850  3006  3006 I SurfaceFlinger: id=23 createSurf (1440x2560),1 flag=4, MauncherAct
09-21 11:58:51.850  3416  6117 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-21 11:58:51.860  3416  6117 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-21 11:58:51.870  4313  4617 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-21 11:58:51.870  3416  6117 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-21 11:58:51.870  3416  6117 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-21 11:58:51.870  3416  6117 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-21 11:58:51.880  3416  4956 V WindowStateAnimator: Finishing drawing window Window{7322e60 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-21 11:58:51.880  3006  3006 I SurfaceFlinger: id=24 createSurf (1592x384),1 flag=4, VSBConnecti
,09-21 11:58:51.890  3416  3534 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 11:58:51.890  3416  3416 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-21 11:58:51.890  3416  3534 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ba4ec3a u0 com.samsung.android.MtpApplication/.USBConnection t11} time:204704
09-21 11:58:51.890  3416  3534 D ActivityManager: mDVFSHelper.release()
,09-21 11:58:51.890  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc8866bb8
,09-21 11:58:51.890  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:51.890  6170  6170 V ActivityThread: updateVisibility : ActivityRecord{492cbde token=android.os.BinderProxy@b145ad3 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
09-21 11:58:51.890  3416  3416 I KnoxTimeoutHandler: SD activityfalse
,09-21 11:58:51.920  3416  4440 V WindowStateAnimator: Finishing drawing window Window{16dbde u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-21 11:58:51.920  6170  6170 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b145ad3 time:204734
,09-21 11:58:51.930  3416  4957 V WindowStateAnimator: Finishing drawing window Window{c67ff80 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
09-21 11:58:51.930  3416  3534 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 11:58:51.930  3416  3416 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-21 11:58:51.930  4313  4313 D Launcher.HomeView: onStop
09-21 11:58:51.930  4313  4313 D capture : ----destroy
09-21 11:58:51.930  3416  3416 I KnoxTimeoutHandler: SD activityfalse
09-21 11:58:51.940  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc8866bb8
09-21 11:58:51.940  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fc8866bb8
09-21 11:58:51.940  3416  3534 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 11:58:51.940  3416  3416 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 11:58:51.940  3416  3534 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6f6bc45 u0 com.sec.android.app.launcher/.activities.LauncherActivity t9} time:204759
09-21 11:58:51.950  3416  3416 I KnoxTimeoutHandler: SD activityfalse
,09-21 11:58:52.050  3416  3564 I art     : Explicit concurrent mark sweep GC freed 110518(7MB) AllocSpace objects, 6(1912KB) LOS objects, 32% free, 33MB/49MB, paused 1.559ms total 221.313ms
,09-21 11:58:52.070  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-21 11:58:52.070  5829  5829 I TrayVisibilityController: handleMessage : msg.what = 1
,09-21 11:58:52.070  3416  3883 D MdnieScenarioControlService:  packageName : com.samsung.android.MtpApplication    className : com.samsung.android.MtpApplication.USBConnection
,09-21 11:58:52.080  5829  5829 I Utils   : isCurrentUser current = 0, ownerId = 0
09-21 11:58:52.080  5829  5829 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-21 11:58:52.080  5829  5829 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
,09-21 11:58:52.090  3416  3564 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-21 11:58:52.090  3416  3564 D AASAuninstall: userId = 0, info.removedAppID = 10177, info.uid = 10177, packageName = com.test.thalitest
,09-21 11:58:52.090  3416  3564 D AASAinstall: there is not AASApackages.xml file
,09-21 11:58:52.090  3416  3564 D PackageManager: result of delete: 1{112960780}
,09-21 11:58:52.090  3416  3564 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-21 11:58:52.090  3416  3564 D PackageManager: userId{-1}
09-21 11:58:52.090  3416  3564 D PackageManager: andCode{true}
09-21 11:58:52.090  9738  9738 I art     : System.exit called, status: 0
09-21 11:58:52.090  9738  9738 I AndroidRuntime: VM exiting with result code 0.
,09-21 11:58:52.100  3416  3564 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=0: pkg removed
,09-21 11:58:52.140  9172  9750 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-21 11:58:52.140  9172  9750 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-21 11:58:52.140  9172  9750 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-21 11:58:52.160  3416  3505 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-21 11:58:52.160  3416  3505 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-21 11:58:52.170  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-21 11:58:52.170  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-21 11:58:52.180  3416  3883 I MdnieScenarioControlService: mGameModeLauncher : false
09-21 11:58:52.180  3416  3883 I MdnieScenarioControlService: setUIMode
,09-21 11:58:52.180  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.180  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-21 11:58:52.180  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-21 11:58:52.180  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.180  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.180  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-21 11:58:52.190  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-21 11:58:52.190  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-21 11:58:52.190  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-21 11:58:52.190  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-21 11:58:52.190  3939  3939 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
09-21 11:58:52.190  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-21 11:58:52.190  3939  3939 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
09-21 11:58:52.190  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,09-21 11:58:52.190  4148  4148 I CatchNotificationsService: mPackageChangedReceiver : onReceive action = android.intent.action.PACKAGE_REMOVED
,09-21 11:58:52.190  3416  3534 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
,09-21 11:58:52.200  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-21 11:58:52.200  3416  3534 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.200  3416  3534 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
09-21 11:58:52.200  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.200  3416  3833 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-21 11:58:52.200  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,09-21 11:58:52.200  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-21 11:58:52.210  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.210  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-21 11:58:52.210  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-21 11:58:52.210  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.210  4353  4825 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-21 11:58:52.210  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-21 11:58:52.210  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-21 11:58:52.210  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,09-21 11:58:52.220  5048  5273 D PresenceModule: onReceive: package removed,
09-21 11:58:52.210  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.220  5048  5273 D PresenceModule: handleMessage: msg 50, Last Publish Info: null
,09-21 11:58:52.220  5048  5273 D PresenceModule: Application package removed
,09-21 11:58:52.220  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-21 11:58:52.220  5048  5273 D PresenceModule: onAppPkgRemoved: com.test.thalitest
09-21 11:58:52.220  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.220  5048  5273 D PresenceModule: onApplicationPackageRemoved: invalid package
09-21 11:58:52.220  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,09-21 11:58:52.220  4160  4160 I PeoplePackageManager: onReceive:android.intent.action.PACKAGE_REMOVED
09-21 11:58:52.220  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-21 11:58:52.230  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.230  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-21 11:58:52.230  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-21 11:58:52.230  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-21 11:58:52.230  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-21 11:58:52.230  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-21 11:58:52.230  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-21 11:58:52.230  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-21 11:58:52.230  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,09-21 11:58:52.230  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.230  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.230  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
09-21 11:58:52.230  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-21 11:58:52.230  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
09-21 11:58:52.230  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,09-21 11:58:52.230  3416  3505 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aeb4079 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51d8157 6551:com.samsung.klmsagent/u0a28}
,09-21 11:58:52.240  6551  6551 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Wed Sep 21 11:58:52 GMT+02:00 2016
,09-21 11:58:52.240  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.240  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.240  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
09-21 11:58:52.240  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-21 11:58:52.240  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
09-21 11:58:52.240  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,09-21 11:58:52.240  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.240  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.240  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
09-21 11:58:52.240  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,09-21 11:58:52.240  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
,09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
,09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3445 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4828, uid=10130 that is not exported from uid 10128
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3502 D AccessibilityManagerService: onUserStateChangedLocked()
09-21 11:58:52.250  3416  3502 D AccessibilityManagerService: updateServicesLocked().mIsAccessibilityEnabled : false
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-21 11:58:52.250  3416  3799 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-21 11:58:52.250  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
,09-21 11:58:52.260  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
,09-21 11:58:52.260  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.260  4029  4029 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
,09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.270  3416  3502 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.270  3416  3502 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.270  6551  6551 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive().END.
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-21 11:58:52.260  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-21 11:58:52.270  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.270  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-21 11:58:52.270  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-21 11:58:52.270  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
,09-21 11:58:52.270  4300  4300 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-21 11:58:52.270  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.270  3416  3858 D NtpTrustedTime: currentTimeMillis() cache hit
09-21 11:58:52.270  3416  3858 V NetworkStats: removeUidsLocked() for UIDs [10177]
09-21 11:58:52.270  6551  6551 I KLMS-2.6.201: : KLMSIntentService(): onCreate()
09-21 11:58:52.270  3416  3858 V NetworkStats: performPollLocked(flags=0x3)
09-21 11:58:52.270  6551  6551 I KLMS-2.6.201: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
,09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-21 11:58:52.280  6551  6551 I KLMS-2.6.201: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-21 11:58:52.280  6551  9754 I KLMS-2.6.201: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
09-21 11:58:52.270  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-21 11:58:52.280  6551  9754 D KLMS-2.6.201: : KLMSIntentService(): PACKAGE_REMOVED
09-21 11:58:52.270  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.280  6551  9754 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemoved().START
,09-21 11:58:52.270  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-21 11:58:52.280  6551  9754 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
09-21 11:58:52.270  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-21 11:58:52.280  6551  9754 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
09-21 11:58:52.280  6551  9754 I KLMS-2.6.201: : MDMBridge(): getAllLicenseInfoFromSDK()
09-21 11:58:52.280  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.280  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-21 11:58:52.280  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-21 11:58:52.280  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-21 11:58:52.280  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-21 11:58:52.280  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-21 11:58:52.280  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-21 11:58:52.280  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-21 11:58:52.280  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.280  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
,09-21 11:58:52.280  3416  3858 D NetworkStatsRecorder: entry.iface is null
09-21 11:58:52.280  3416  3858 D NetworkStatsRecorder: entry.iface is null
09-21 11:58:52.280  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-21 11:58:52.280  3416  3858 D NetworkStatsRecorder: entry.iface is null
09-21 11:58:52.280  3416  3858 D NetworkStatsRecorder: entry.iface is null
09-21 11:58:52.280  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-21 11:58:52.280  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.280  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-21 11:58:52.280  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
09-21 11:58:52.280  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-21 11:58:52.280  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.280  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.280  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.280  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
09-21 11:58:52.280  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-21 11:58:52.280  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-21 11:58:52.280  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.280  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
,09-21 11:58:52.280  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
09-21 11:58:52.280  6551  9754 I KLMS-2.6.201: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-21 11:58:52.280  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.290  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
,09-21 11:58:52.290  3416  3858 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473661510213- -> /data/system/netstats/uid.1473661510213-.backup
09-21 11:58:52.290  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-21 11:58:52.290  3416  3858 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473661510213-
09-21 11:58:52.290  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-21 11:58:52.290  3416  3858 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473661510213-.backup -> /data/system/netstats/uid.1473661510213-
09-21 11:58:52.290  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-21 11:58:52.290  6551  9754 I KLMS-2.6.201: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-21 11:58:52.290  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-21 11:58:52.290  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-21 11:58:52.290  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-21 11:58:52.290  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.290  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
09-21 11:58:52.290  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
,09-21 11:58:52.290  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-21 11:58:52.290  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
,09-21 11:58:52.290  3416  3416 D ResourcesManager: For user 0 new overlays fetched Null
,09-21 11:58:52.290  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
09-21 11:58:52.290  3416  3416 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
,09-21 11:58:52.290  3416  3416 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,09-21 11:58:52.290  3416  3416 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-21 11:58:52.300  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.300  3416  3416 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
09-21 11:58:52.300  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
09-21 11:58:52.300  3416  3416 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
09-21 11:58:52.300  3416  3416 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-21 11:58:52.300  3416  3416 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-21 11:58:52.300  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-21 11:58:52.300  3416  3416 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10177 container id = 0
09-21 11:58:52.300  3416  3416 I OTPFW   : ProvisionData::getAllEntries Enter
09-21 11:58:52.300  3416  3416 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-21 11:58:52.300  3416  3416 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
09-21 11:58:52.300  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.300  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-21 11:58:52.300  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
,09-21 11:58:52.300  3416  3416 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
,09-21 11:58:52.300  3416  4809 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aeb4079 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5c3df5e 3416:system/1000}
09-21 11:58:52.300  3416  3416 D UcmService: Package update in userId-0 and uid-10177
09-21 11:58:52.300  3416  3416 D InjectionManagerService -AppFeature:  Info before com.test.thalitest removal target ={} 
09-21 11:58:52.300  3416  3416 D InjectionManagerService -AppFeature:  source ={}
09-21 11:58:52.300  3416  3416 W SQLiteLog: (28) failed to open "/data/system/gamemanager.db" with flag (131138) and mode_t (0) due to error (30)
,09-21 11:58:52.300  3416  3858 E DropBoxManagerService: Can't write: netstats_dump
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1222)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-21 11:58:52.300  3416 , 3858 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-21 11:58:52.300  3416  3858 E DropBoxManagerService: 	... 16 more
09-21 11:58:52.300  3416  3858 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop97.tmp
09-21 11:58:52.310  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.300  3416  3858 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473661510213-
09-21 11:58:52.300  6551  9754 I KLMS-2.6.201: : MDMBridge(): getAllLicenseInfoFromSDK()
,09-21 11:58:52.300  3416  3858 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1472201541317-1473661448159
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: Failed to open database '/data/system/gamemanager.db'.
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: #################################################################
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: #################################################################
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at com.android.server.SystemServer.run(SystemServer.java:508)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at com.android.server.SystemServer.main(SystemServer.java:363)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-21 11:58:52.310  3416  3416 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-21 11:58:52.310  3416  3858 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474285157055- -> /data/system/netstats/uid_tag.1474285157055-.backup
,09-21 11:58:52.310  6551  9754 D KLMS-2.6.201: : Systemprocess(): arrayLicenseInfo is null
09-21 11:58:52.310  3416  3858 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474285157055-
09-21 11:58:52.310  3416  3858 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474285157055-.backup -> /data/system/netstats/uid_tag.1474285157055-
09-21 11:58:52.310  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
09-21 11:58:52.310  3416  3416 D AndroidRuntime: Shutting down VM
09-21 11:58:52.310  3416  3416 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: main
09-21 11:58:52.310  3416  3416 E AndroidRuntime: java.lang.RuntimeException: Error receiving broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } in com.samsung.android.game.GameManagerService$UninstallReceiver@7db5346
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1003)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at com.android.server.SystemServer.run(SystemServer.java:508)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at com.android.server.SystemServer.main(SystemServer.java:363)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:52.310  3416  3416 E AndroidRuntime: #################################################################
09-21 11:58:52.310  3416  3416 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:52.310  3416  3416 E AndroidRuntime: #################################################################
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-21 11:58:52.310  3416  3416 E AndroidRuntime: 	... 8 more
09-21 11:58:52.310  6551  9754 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: #################################################################
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: #################################################################
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:587)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:523)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
09-21 11:58:52.320  6551  9754 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: #################################################################
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: #################################################################
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:587)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:523)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
09-21 11:58:52.320  6551  9754 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: Can't write: netstats_dump
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1223)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-21 11:58:52.320  3416  3858 E DropBoxManagerService: 	... 16 more
09-21 11:58:52.320  3416  3858 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop97.tmp
09-21 11:58:52.320  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.320  3416  3858 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474285157055-
09-21 11:58:52.320  3416  3858 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1473661510213-1474285006246
09-21 11:58:52.320  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-21 11:58:52.320  3416  3858 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1472634128224-1473173655101
09-21 11:58:52.320  3416  3858 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1473173718297-1473661448159
09-21 11:58:52.320  3416  3858 D NtpTrustedTime: currentTimeMillis() cache hit
09-21 11:58:52.320  3416  3858 V NetworkStats: performPollLocked() took 47ms
09-21 11:58:52.320  4288  9756 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
09-21 11:58:52.320  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
09-21 11:58:52.320  4288  9756 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
09-21 11:58:52.320  6551  9754 W SQLiteOpenHelper: Opened klms.db in read-only mode
09-21 11:58:52.320  4288  9756 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
09-21 11:58:52.320  4288  9756 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
09-21 11:58:52.320  4288  9756 D RegisteredComponentCache: Collect Tech packages for Knox
09-21 11:58:52.320  3416  3859 D NtpTrustedTime: currentTimeMillis() cache hit
09-21 11:58:52.320  3416  3859 D NtpTrustedTime: currentTimeMillis() cache hit
09-21 11:58:52.320  3416  3502 D ResourcesManager: For user 0 new overlays fetched Null
09-21 11:58:52.320  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
09-21 11:58:52.330  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-21 11:58:52.330  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-21 11:58:52.330  3416  3502 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in null rsrc of package com.sec.android.app.launcher
09-21 11:58:52.330  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-21 11:58:52.330  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-21 11:58:52.330  3416  3502 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs

```
