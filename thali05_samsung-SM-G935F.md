#### Test 8504691198a5312_thali05_samsung-SM-G935F Logs


```
--------- beginning of system
09-26 09:01:11.897  3152  3628 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,--------- beginning of main
09-26 09:01:12.837  9745  9745 I FIPS_bssl: FIPS approved mode (1) | 9745 | app_process
09-26 09:01:12.847  9745  9745 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-26 09:01:12.847  9745  9745 D AndroidRuntime: CheckJNI is OFF
09-26 09:01:12.847  9745  9745 D AndroidRuntime: readGMSProperty: start
09-26 09:01:12.847  9745  9745 D AndroidRuntime: readGMSProperty: already setted!!
09-26 09:01:12.847  9745  9745 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-26 09:01:12.847  9745  9745 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-26 09:01:12.847  9745  9745 D AndroidRuntime: readGMSProperty: end
09-26 09:01:12.847  9745  9745 D AndroidRuntime: addProductProperty: start
09-26 09:01:12.867  9745  9745 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-26 09:01:12.887  9745  9745 I Radio-JNI: register_android_hardware_Radio DONE
09-26 09:01:12.897  9745  9745 E AffinityControl: AffinityControl: registerfunction enter
09-26 09:01:12.897  9745  9745 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-26 09:01:12.927  3440  6141 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-26 09:01:12.927  3440  4393 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
09-26 09:01:12.927  3440  4393 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-26 09:01:12.947  3440  4393 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:12.947  3440  4393 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 09:01:12.947  3440  4393 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-26 09:01:12.957  3440  4393 D ActivityManager: mDVFSHelper.acquire()
09-26 09:01:12.967  3440  4393 V WindowManager: addAppToken: AppWindowToken{d0fc3f0c0 token=Token{d85e243 ActivityRecord{5686bf2 u0 com.test.thalitest/.MainActivity t12}}} to stack=2 task=12 at 0
09-26 09:01:12.977  3440  3549 I InjectionManager: Inside getClassLibPath caller 
09-26 09:01:12.987  3440  3549 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-26 09:01:12.987  3440  3549 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9d717d8 V.E...... R.....ID 0,0-0,0}
09-26 09:01:12.997  9754  9754 E Zygote  : v2
09-26 09:01:12.997  9754  9754 I libpersona: KNOX_SDCARD checking this for 10177
09-26 09:01:12.997  9754  9754 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-26 09:01:12.997  9754  9754 I libpersona: KNOX_SDCARD not a persona
09-26 09:01:12.997  3440  3549 W WindowManager: Failed looking up window
09-26 09:01:12.997  3440  3549 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@2e92731 does not exist
09-26 09:01:12.997  3440  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 09:01:12.997  3440  3549 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-26 09:01:12.997  3440  3549 D ISSUE_DEBUG: InputChannelName : 81cce16 Starting com.test.thalitest
09-26 09:01:12.997  9754  9754 E Zygote  : accessInfo : 0
09-26 09:01:12.997  9754  9754 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-26 09:01:13.007  3009  3009 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-26 09:01:13.007  3440  4393 I ActivityManager: Start proc 9754:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-26 09:01:13.027  6175  6175 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-26 09:01:13.037  9754  9754 D TimaKeyStoreProvider: TimaSignature is unavailable
09-26 09:01:13.037  9754  9754 D ActivityThread: Added TimaKeyStore provider
09-26 09:01:13.037  3440  4120 I libsuspend: !@autosuspend_wakeup_count_disable
09-26 09:01:13.037  3440  4120 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3440
09-26 09:01:13.037  3440  4120 I libsuspend: !@autosuspend_wakeup_count_disable done
09-26 09:01:13.037  3440  4120 D PowerManagerService: mDisplayReady: false
09-26 09:01:13.037  3440  4393 D InputDispatcher: Focused application set to: xxxx
09-26 09:01:13.037  3440  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 09:01:13.037  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f9b243c00
09-26 09:01:13.037  3440  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 09:01:13.037  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-26 09:01:13.037  3440  4120 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-26 09:01:13.037  3440  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:13.037  3440  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:13.037  3440  3564 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-26 09:01:13.037  3440  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 09:01:13.037  9745  9745 D AndroidRuntime: Shutting down VM
09-26 09:01:13.037  3440  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 09:01:13.037  3440  3553 I libsuspend: !@autosuspend_wakeup_count_enable
09-26 09:01:13.037  3440  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:13.037  3440  3553 I libsuspend: !@autosuspend_wakeup_count_enable done
09-26 09:01:13.037  3440  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:13.037  3440  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 09:01:13.037  3440  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 09:01:13.037  3440  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:13.037  3440  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:13.037  3440  3553 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-26 09:01:13.037  3440  3553 D PowerManagerService: mDisplayReady: true
09-26 09:01:13.037  3440  3553 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-26 09:01:13.047  3440  3852 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-26 09:01:13.047  3440  3461 V WindowStateAnimator: Finishing drawing window Window{d319cfc u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-26 09:01:13.047  6175  6175 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-26 09:01:13.047  3440  3967 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3440
09-26 09:01:13.047  6175  6175 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-26 09:01:13.047  3440  4330 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3440
09-26 09:01:13.047  6175  6175 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-26 09:01:13.057  3440  4120 D ActivityManager:  Launching com.test.thalitest, updated priority
09-26 09:01:13.067  5817  5828 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-26 09:01:13.067  3440  3440 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-26 09:01:13.087  3009  4400 D libEGL  : eglTerminate EGLDisplay = 0x7f930ffe78
09-26 09:01:13.087  3009  4400 D libEGL  : eglTerminate EGLDisplay = 0x7f930ffe78
09-26 09:01:13.087  3009  3017 I SurfaceFlinger: id=10 Removed MauncherAct (4/13)
09-26 09:01:13.087  3009  3019 I SurfaceFlinger: id=10 Removed MauncherAct (-2/13)
09-26 09:01:13.097  3440  3462 V WindowStateAnimator: Finishing drawing window Window{5ee56ce u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-26 09:01:13.097  3440  4407 V WindowStateAnimator: Finishing drawing window Window{d319cfc u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=READY_TO_SHOW
09-26 09:01:13.097  6175  6175 V ActivityThread: updateVisibility : ActivityRecord{79da5e0 token=android.os.BinderProxy@5dede8d {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-26 09:01:13.107  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fd2b2d0b8
09-26 09:01:13.107  3009  3971 I SurfaceFlinger: id=18 Removed VSBConnecti (7/12)
09-26 09:01:13.107  3009  3019 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/12)
09-26 09:01:13.117  3009  3017 D libEGL  : eglTerminate EGLDisplay = 0x7f9afc0e78
09-26 09:01:13.117  3009  3019 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
09-26 09:01:13.117  3009  4400 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
09-26 09:01:13.137  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fd2b2d0b8
09-26 09:01:13.147  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fd2b2d0b8
09-26 09:01:13.197  3440  3440 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3440 (0x0)
09-26 09:01:13.197  3440  3440 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3440 (0x0)
09-26 09:01:13.197  3440  3440 D PowerManagerService: mDisplayReady: false
09-26 09:01:13.197  3440  3440 I libsuspend: !@autosuspend_wakeup_count_disable
09-26 09:01:13.197  3440  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 09:01:13.197  3440  3440 I libsuspend: !@autosuspend_wakeup_count_disable done
09-26 09:01:13.197  3440  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 09:01:13.197  3440  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:13.197  3440  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:13.197  3440  3553 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-26 09:01:13.197  3440  3564 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-26 09:01:13.207  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f9b243c00
09-26 09:01:13.207  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-26 09:01:13.207  3440  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 09:01:13.207  3440  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 09:01:13.207  3440  3553 I libsuspend: !@autosuspend_wakeup_count_enable
09-26 09:01:13.207  3440  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:13.207  3440  3553 I libsuspend: !@autosuspend_wakeup_count_enable done
09-26 09:01:13.207  3440  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:13.207  3440  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 09:01:13.207  3440  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 09:01:13.207  3440  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:13.207  3440  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:13.207  3440  3553 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-26 09:01:13.207  3440  3553 D PowerManagerService: mDisplayReady: true
09-26 09:01:13.207  3440  3553 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-26 09:01:13.367  5817  5817 I TrayVisibilityController: handleMessage : msg.what = 1
09-26 09:01:13.387  3440  4120 I WindowManager: Screenshot max retries 4 of Token{d85e243 ActivityRecord{5686bf2 u0 com.test.thalitest/.MainActivity t12}} appWin=Window{81cce16 u0 d0 Starting com.test.thalitest} drawState=1
09-26 09:01:13.387  5817  5827 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-26 09:01:13.387  3440  3549 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 09:01:13.387  3440  3440 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 09:01:13.387  3440  3549 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-26 09:01:13.397  3440  3440 I KnoxTimeoutHandler: SD activityfalse
09-26 09:01:13.417  3440  3519 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-26 09:01:13.417  4314  4314 D Launcher.HomeView: onStop
09-26 09:01:13.417  4314  4314 D capture : ----destroy
09-26 09:01:13.427  4314  4314 V ActivityThread: updateVisibility : ActivityRecord{90c0b65 token=android.os.BinderProxy@6072bc {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-26 09:01:13.427  9754  9754 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-26 09:01:13.427  9754  9754 D RelationGraph: garbageCollect()
09-26 09:01:13.437  5817  5817 I Utils   : isCurrentUser current = 0, ownerId = 0
09-26 09:01:13.437  5817  5817 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-26 09:01:13.437  5817  5817 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-26 09:01:13.437  3440  3549 V WindowStateAnimator: Finishing drawing window Window{81cce16 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-26 09:01:13.437  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fd2b2cf98
09-26 09:01:13.437  4314  4314 D Launcher: onTrimMemory. Level: 20
09-26 09:01:13.437  3440  3549 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 09:01:13.437  3440  3440 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 09:01:13.437  3440  3852 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-26 09:01:13.447  9754  9754 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-26 09:01:13.447  3440  6104 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 09:01:13.447  3440  6104 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 09:01:13.457  3440  3440 I KnoxTimeoutHandler: SD activityfalse
09-26 09:01:13.457  3440  3544 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
09-26 09:01:13.457  9754  9754 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-26 09:01:13.457  3440  3849 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-26 09:01:13.467  3440  6104 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-26 09:01:13.477  9754  9754 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:13.477  3440  6104 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 09:01:13.477  9754  9754 I InjectionManager: Inside getClassLibPath caller 
09-26 09:01:13.477  3440  6104 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-26 09:01:13.487  3440  6104 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 09:01:13.487  3440  6104 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 09:01:13.497  9754  9754 D InjectionManager: InjectionManager
09-26 09:01:13.497  9754  9754 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-26 09:01:13.497  9754  9754 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-26 09:01:13.497  9754  9754 I InjectionManager: featureStore :{}
09-26 09:01:13.497  9754  9754 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-26 09:01:13.497  9754  9754 D RelationGraph: garbageCollect()
09-26 09:01:13.507  9754  9754 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-26 09:01:13.537  9754  9754 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-26 09:01:13.597  9754  9754 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-26 09:01:13.597  9754  9754 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:13.597  9754  9754 I InjectionManager: Inside getClassLibPath caller 
09-26 09:01:13.607  9754  9754 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-26 09:01:13.657  9754  9754 I cr_LibraryLoader: Time to load native libraries: 34 ms (timestamps 9969-3)
09-26 09:01:13.657  9754  9754 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-26 09:01:13.707  3440  3876 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-26 09:01:13.727  9754  9771 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-26 09:01:13.737  9754  9754 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8056d81}
09-26 09:01:13.737  9754  9754 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-26 09:01:13.767  9754  9754 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-26 09:01:13.807  9754  9754 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-26 09:01:13.807  3440  3876 I MdnieScenarioControlService: mGameModeLauncher : false
09-26 09:01:13.807  3440  3876 I MdnieScenarioControlService: setUIMode
09-26 09:01:13.887  3440  3519 W ActivityManager: Activity pause timeout for ActivityRecord{5686bf2 u0 com.test.thalitest/.MainActivity t12}
09-26 09:01:13.957  9754  9754 D libEGL  : eglInitialize EGLDisplay = 0xffb2ab8c
09-26 09:01:14.037  3440  4404 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
09-26 09:01:14.037  3440  4404 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-26 09:01:14.097  9754  9754 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-26 09:01:14.097  3152  3628 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-26 09:01:14.107  9754  9754 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-26 09:01:14.107  9754  9754 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-26 09:01:14.127  9754  9754 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-26 09:01:14.157  9754  9754 D Activity: performCreate Call Injection manager
,09-26 09:01:14.157  9754  9754 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-26 09:01:14.167  9754  9754 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-26 09:01:14.177  9754  9754 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a6f6874 I.E...... R.....ID 0,0-0,0}
,09-26 09:01:14.177  9754  9809 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-26 09:01:14.177  3440  4407 W WindowManager: Failed looking up window
09-26 09:01:14.177  3440  4407 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@8861211 does not exist
09-26 09:01:14.177  3440  4407 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-26 09:01:14.177  3440  4407 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-26 09:01:14.177  3440  4407 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-26 09:01:14.177  3440  4407 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-26 09:01:14.177  3440  4407 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-26 09:01:14.177  3440  4407 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-26 09:01:14.187  3440  4057 D ISSUE_DEBUG: InputChannelName : 4bd0f76 com.test.thalitest/com.test.thalitest.MainActivity
,09-26 09:01:14.187  3440  4331 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,09-26 09:01:14.187  3440  4331 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-26 09:01:14.187  3440  3440 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-26 09:01:14.187  3440  3440 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-26 09:01:14.197  9754  9754 V ActivityThread: updateVisibility : ActivityRecord{1cbb612 token=android.os.BinderProxy@3408c6f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-26 09:01:14.197  9754  9771 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-26 09:01:14.217  9754  9754 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9754
,09-26 09:01:14.217  3440  4057 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9754 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-26 09:01:14.217  3440  3863 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-26 09:01:14.227  3440  3863 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -36]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 09:01:14.227  3440  3863 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-26 09:01:14.227  3440  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-26 09:01:14.237  3440  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-26 09:01:14.237  9754  9754 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-26 09:01:14.237  3440  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-26 09:01:14.247  3440  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-26 09:01:14.247  3440  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-26 09:01:14.247  3440  3863 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-26 09:01:14.257  3009  3009 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,09-26 09:01:14.267  9754  9809 D libEGL  : eglInitialize EGLDisplay = 0xdc23f7c4
09-26 09:01:14.267  9754  9809 I OpenGLRenderer: Initialized EGL, version 1.4
,09-26 09:01:14.277  9754  9809 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-26 09:01:14.277  3440  4393 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3440
,09-26 09:01:14.277  3440  4393 I libsuspend: !@autosuspend_wakeup_count_disable
09-26 09:01:14.277  3440  4393 D PowerManagerService: mDisplayReady: false
09-26 09:01:14.277  3440  4393 I libsuspend: !@autosuspend_wakeup_count_disable done
09-26 09:01:14.277  3440  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 09:01:14.277  3440  4393 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-26 09:01:14.277  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f9b243c00
09-26 09:01:14.277  3440  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 09:01:14.277  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-26 09:01:14.277  3440  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:14.277  3440  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:14.277  3440  3564 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-26 09:01:14.277  3440  3549 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-26 09:01:14.277  3440  3549 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-26 09:01:14.297  3440  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 09:01:14.297  3440  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 09:01:14.297  3440  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:14.297  3440  3553 I libsuspend: !@autosuspend_wakeup_count_enable
09-26 09:01:14.297  3440  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:14.297  3440  3553 I libsuspend: !@autosuspend_wakeup_count_enable done
09-26 09:01:14.297  3440  3553 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 09:01:14.297  3440  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 09:01:14.297  3440  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:14.297  3440  3553 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:14.297  3440  3553 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-26 09:01:14.297  3440  3553 D PowerManagerService: mDisplayReady: true
09-26 09:01:14.297  3440  3553 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-26 09:01:14.307  5817  5817 E CocktailBarPositionManager: Window direction: 0
09-26 09:01:14.307  5817  5817 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-26 09:01:14.307  9754  9754 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-26 09:01:14.327  3440  4823 V WindowStateAnimator: Finishing drawing window Window{4bd0f76 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-26 09:01:14.327  9754  9754 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-26 09:01:14.337  3440  4404 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3440
09-26 09:01:14.337  3440  3549 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-26 09:01:14.337  3440  3440 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-26 09:01:14.337  3440  3549 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +951ms (total +1s369ms)
,09-26 09:01:14.337  3440  3549 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5686bf2 u0 com.test.thalitest/.MainActivity t12} time:190685
,09-26 09:01:14.337  3440  3549 D ActivityManager: mDVFSHelper.release()
09-26 09:01:14.337  3440  3549 D ViewRootImpl: #3 mView = null
09-26 09:01:14.337  3440  3849 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3440
09-26 09:01:14.337  3440  3440 I KnoxTimeoutHandler: SD activityfalse
,09-26 09:01:14.337  3009  3017 I SurfaceFlinger: id=20 Removed uhalitest (6/11)
,09-26 09:01:14.347  3009  3019 I SurfaceFlinger: id=20 Removed uhalitest (-2/11)
,09-26 09:01:14.347  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fd2b2d0b8
,09-26 09:01:14.347  9754  9813 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-26 09:01:14.347  9754  9813 D libEGL  : eglInitialize EGLDisplay = 0xdacec3f4
,09-26 09:01:14.357  3440  3967 V WindowStateAnimator: Finishing drawing window Window{4bd0f76 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-26 09:01:14.367  9754  9754 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3408c6f time:190711
,09-26 09:01:14.377  9754  9813 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-26 09:01:14.417  9754  9754 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9754
,09-26 09:01:14.437  3440  6106 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-26 09:01:14.487  3440  3440 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3440 (0x0)
09-26 09:01:14.487  3440  3440 I libsuspend: !@autosuspend_wakeup_count_disable
09-26 09:01:14.487  3440  3440 D PowerManagerService: mDisplayReady: false
09-26 09:01:14.487  3440  3440 I libsuspend: !@autosuspend_wakeup_count_disable done
09-26 09:01:14.487  3440  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 09:01:14.487  3440  3440 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-26 09:01:14.487  3440  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 09:01:14.487  3440  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:14.487  3440  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:14.487  3440  3564 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-26 09:01:14.487  3440  3549 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-26 09:01:14.487  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f9b243c00
09-26 09:01:14.487  3440  3549 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-26 09:01:14.487  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,09-26 09:01:14.507  3440  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-26 09:01:14.507  3440  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 09:01:14.507  3440  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:14.507  3440  3553 I libsuspend: !@autosuspend_wakeup_count_enable
09-26 09:01:14.507  3440  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:14.507  3440  3553 I libsuspend: !@autosuspend_wakeup_count_enable done
09-26 09:01:14.507  3440  3553 D DisplayPowerController: animateScreenStateChange[0]: target=4
,09-26 09:01:14.507  3440  3553 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 09:01:14.507  3440  3553 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:14.507  3440  3553 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:14.507  3440  3553 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-26 09:01:14.507  3440  3553 D PowerManagerService: mDisplayReady: true
,09-26 09:01:14.507  3440  3553 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-26 09:01:14.507  5817  5817 E CocktailBarPositionManager: Window direction: 0
09-26 09:01:14.507  5817  5817 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,09-26 09:01:14.617  9754  9754 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-26 09:01:14.697  9754  9820 D jxcore_app_log: JniHelper::setJavaVM(0xf4934000), pthread_self() = -632817360
,09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7d6a4 added. We now have 1 listener(s)
,09-26 09:01:14.707  9754  9820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
,09-26 09:01:14.707  9754  9820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
,09-26 09:01:14.707  9754  9820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 09:01:14.707  9754  9820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-26 09:01:14.707  9754  9820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf359d3 added. We now have 1 listener(s)
09-26 09:01:14.707  9754  9820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 09:01:14.717  9754  9820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 09:01:14.717  9754  9820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-26 09:01:14.717  9754  9820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-26 09:01:14.717  9754  9820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-26 09:01:14.717  9754  9820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-26 09:01:14.717  9754  9820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 09:01:14.717  9754  9820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
09-26 09:01:14.727  9754  9820 D BluetoothAdapter: STATE_ON
09-26 09:01:14.727  9754  9820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-26 09:01:14.727  9754  9820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 09:01:14.727  9754  9820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 09:01:14.727  9754  9820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 09:01:14.727  9754  9820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 09:01:14.727  9754  9820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 09:01:14.727  9754  9820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 09:01:14.727  9754  9820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 09:01:14.727  9754  9820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 09:01:14.727  9754  9820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-26 09:01:14.727  9754  9820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 09:01:14.727  9754  9820 I io.jxcore.node.LifeCycleMonitor: start: OK
09-26 09:01:14.727  9754  9754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 09:01:14.737  9754  9754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 09:01:14.757  9754  9754 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-26 09:01:14.887  4021  4021 D Recents : onTaskStackChanged
,09-26 09:01:14.897  4021  4021 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-26 09:01:14.907  4021  4021 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:15.067  9754  9821 W jxcore-log: Initializing JXcore engine
09-26 09:01:15.067  9754  9821 W jxcore-log: JXcore engine is ready
,09-26 09:01:15.087  5016  5016 E audit   : type=1400 msg=audit(1474873275.087:264): avc:  denied  { ioctl } for  pid=9821 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3099 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-26 09:01:15.087  5016  5016 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-26 09:01:15.087  5016  5016 E audit   : type=1300 msg=audit(1474873275.087:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=da37a3c8 items=0 ppid=3177 pid=9821 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-26 09:01:15.087  5016  5016 E audit   : type=1327 msg=audit(1474873275.087:264): proctitle="com.test.thalitest"
09-26 09:01:15.087  5016  5016 E audit   : type=1320 msg=audit(1474873275.087:264): 
09-26 09:01:15.087  5016  5016 E audit   : type=1400 msg=audit(1474873275.087:265): avc:  denied  { ioctl } for  pid=9821 comm="Thread-160" path="socket:[38078]" dev="sockfs" ino=38078 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-26 09:01:15.087  5016  5016 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-26 09:01:15.087  5016  5016 E audit   : type=1300 msg=audit(1474873275.087:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=da37a3c8 items=0 ppid=3177 pid=9821 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-26 09:01:15.087  5016  5016 E audit   : type=1327 msg=audit(1474873275.087:265): proctitle="com.test.thalitest"
09-26 09:01:15.087  5016  5016 E audit   : type=1320 msg=audit(1474873275.087:265): 
,09-26 09:01:15.087  9754  9821 W jxcore-log: Starting JXcore engine
,09-26 09:01:15.127  9754  9821 W jxcore-log: Platform android
09-26 09:01:15.127  9754  9821 W jxcore-log: 
09-26 09:01:15.127  9754  9821 W jxcore-log: Process ARCH arm
09-26 09:01:15.127  9754  9821 W jxcore-log: 
,09-26 09:01:15.197  9754  9821 I jxcore-log: JXcore Cordova bridge is ready!
09-26 09:01:15.197  9754  9821 I jxcore-log: 
09-26 09:01:15.197  9754  9821 W jxcore-log: JXcore engine is started
,09-26 09:01:15.207  9754  9820 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-26 09:01:15.207  9754  9754 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-26 09:01:15.337  3440  6104 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:10), CP = 211, CUR = 181, LCD = 1
,09-26 09:01:15.967  3440  3902 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/12_task.xml.bak
,09-26 09:01:16.457  3440  6104 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-26 09:01:16.857  3440  4142 E Watchdog: !@Sync 6 [09-26 09:01:16.864]
,09-26 09:01:17.147  3440  4057 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-26 09:01:17.147  3440  4057 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4313, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-26 09:01:17.147  3440  4057 D BatteryService: online:4, current avg:94, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-234
09-26 09:01:17.147  3440  4057 D BatteryService: stay LED for fully charged
09-26 09:01:17.147  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-26 09:01:17.157  3440  3440 I MotionRecognitionService: Plugged
09-26 09:01:17.157  3440  3440 D MotionRecognitionService:   cableConnection= 1
09-26 09:01:17.157  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-26 09:01:17.157  3440  3440 D MotionRecognitionService: skip setTransmitPower. 
,09-26 09:01:17.157  3440  3857 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-26 09:01:17.157  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-26 09:01:17.157  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
09-26 09:01:17.167  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-26 09:01:17.177  5046  5046 D CommonServiceConfiguration: getStringValueSetting
,09-26 09:01:17.177  5005  5005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-26 09:01:17.177  5005  5383 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-26 09:01:17.187  5046  5046 D BatteryMonitor: new battery level: 100
,09-26 09:01:17.187  4756  4756 D BatteryController: saveBatteryData : level[100], status[5]
,09-26 09:01:17.207  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-26 09:01:17.207  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-26 09:01:18.287  4410  4493 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
09-26 09:01:18.287  4410  4493 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,09-26 09:01:19.387  9754  9821 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-26 09:01:19.387  9754  9821 I jxcore-log: 
,09-26 09:01:19.387  9754  9821 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-26 09:01:19.387  9754  9821 I jxcore-log: 
,09-26 09:01:19.397  9754  9821 D BluetoothAdapter: STATE_ON
,09-26 09:01:19.397  9754  9821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 09:01:19.397  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 09:01:19.397  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 09:01:19.397  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 09:01:19.397  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 09:01:19.397  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 09:01:19.397  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 09:01:19.397  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 09:01:19.407  9754  9821 D BluetoothAdapter: STATE_ON
,09-26 09:01:19.407  9754  9821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 09:01:19.407  9754  9821 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-26 09:01:19.407  9754  9821 I jxcore-log: 
,09-26 09:01:19.407  9754  9821 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-26 09:01:19.407  9754  9821 I jxcore-log: 
,09-26 09:01:19.497  3440  6104 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-26 09:01:19.677  9754  9821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 09:01:19.677  9754  9821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e61bc74 added. We now have 2 listener(s)
09-26 09:01:19.677  9754  9821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-26 09:01:19.677  9754  9821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 09:01:19.677  9754  9821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 09:01:19.677  9754  9821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 09:01:19.677  9754  9821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc0c59d added. We now have 2 listener(s)
,09-26 09:01:19.677  9754  9821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 09:01:19.687  9754  9821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 09:01:19.687  9754  9821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 09:01:19.697  9754  9821 D BluetoothAdapter: STATE_ON
,09-26 09:01:19.697  9754  9821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 09:01:19.697  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 09:01:19.697  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 09:01:19.697  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 09:01:19.697  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 09:01:19.697  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 09:01:19.697  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 09:01:19.697  9754  9821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 09:01:19.707  9754  9821 D BluetoothAdapter: STATE_ON
,09-26 09:01:19.707  9754  9821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 09:01:19.707  9754  9821 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 09:01:19.707  9754  9821 D ExecuteNativeTests: Running unit tests
09-26 09:01:19.707  9754  9821 D BluetoothAdapter: enable()
,09-26 09:01:19.717  9754  9754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 09:01:19.717  9754  9821 D BluetoothAdapter: enable(): BT is already enabled..!
,09-26 09:01:19.727  9754  9754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 09:01:19.737  3440  3519 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6664226 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{313fc9c 5032:com.samsung.android.providers.context/u0a9}
,09-26 09:01:19.737  9754  9821 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-26 09:01:19.737  3440  3462 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-26 09:01:19.737  3440  3462 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-26 09:01:19.737  3440  3462 D WifiService: setWifiEnabled: true pid=9754, uid=10177
,09-26 09:01:19.747  3440  3462 W ActivityManager: Permission Denial: getCurrentUser() from pid=9754, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
,09-26 09:01:19.747  3440  3854 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-26 09:01:19.747  3440  3462 W WifiService: Failed getting userId using ActivityManagerNative
09-26 09:01:19.747  3440  3462 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9754, uid=10177 requires android.permission.INTERACT_ACROSS_USERS
09-26 09:01:19.747  3440  3462 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28247)
09-26 09:01:19.747  3440  3462 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
09-26 09:01:19.747  3440  3462 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
09-26 09:01:19.747  3440  3462 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-26 09:01:19.747  3440  3462 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
09-26 09:01:19.747  3440  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-26 09:01:19.747  3440  3462 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
09-26 09:01:19.747  3440  3854 D WifiBigDataLog: init : 
09-26 09:01:19.747  3440  3462 D SettingsProvider: isChangeAllowed() : name = wifi_on
09-26 09:01:19.747  3440  3857 D WifiStateMachine: setFccChannel: channel = 0
,09-26 09:01:19.747  3440  3857 D WifiController: [FCC]setFccChannel() is called !!!
09-26 09:01:19.747  3440  3857 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,09-26 09:01:19.747  3440  3854 D WifiStateMachine: setFccChannelNative: channel = 0
,09-26 09:01:19.747  3440  3854 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-26 09:01:19.757  3440  3519 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{115ee67 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{313fc9c 5032:com.samsung.android.providers.context/u0a9}
,09-26 09:01:21.447  8412  8435 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,09-26 09:01:23.017  3440  3571 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-26 09:01:23.047  3440  3571 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-26 09:01:25.357  3440  6104 D SSRM:n  : SIOP:: AP = 280, PST = 260 (W:6), CP = 220, CUR = 94, LCD = 1
,09-26 09:01:27.217  3440  4404 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-26 09:01:27.217  3440  4404 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-26 09:01:27.217  3440  4404 D BatteryService: online:4, current avg:109, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:181
09-26 09:01:27.217  3440  4404 D BatteryService: stay LED for fully charged
09-26 09:01:27.217  3440  3440 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-26 09:01:27.227  3440  3440 I MotionRecognitionService: Plugged
,09-26 09:01:27.227  3440  3440 D MotionRecognitionService:   cableConnection= 1
09-26 09:01:27.227  3440  3440 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-26 09:01:27.227  3440  3440 D MotionRecognitionService: skip setTransmitPower. 
,09-26 09:01:27.227  3440  3857 D WifiController: ApOrStaEnabledState  msg.what= 155652
,09-26 09:01:27.237  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-26 09:01:27.237  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
09-26 09:01:27.237  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
09-26 09:01:27.267  5046  5046 D CommonServiceConfiguration: getStringValueSetting
,09-26 09:01:27.277  5005  5005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-26 09:01:27.277  5005  5383 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-26 09:01:27.287  4756  4756 D BatteryController: saveBatteryData : level[100], status[5]
,09-26 09:01:27.287  5046  5046 D BatteryMonitor: new battery level: 100
,09-26 09:01:27.287  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-26 09:01:27.287  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-26 09:01:29.747  9754  9821 I com.test.thalitest.ThaliTestRunner: Running UT
,09-26 09:01:29.777  9754  9821 I jxcore-log: *Native tests were executed*
09-26 09:01:29.777  9754  9821 I jxcore-log: 
09-26 09:01:29.777  9754  9821 I jxcore-log: Total number of executed tests:  1
09-26 09:01:29.777  9754  9821 I jxcore-log: 
09-26 09:01:29.777  9754  9821 I jxcore-log: Number of passed tests:  1
09-26 09:01:29.777  9754  9821 I jxcore-log: 
09-26 09:01:29.777  9754  9821 I jxcore-log: Number of failed tests:  0
09-26 09:01:29.777  9754  9821 I jxcore-log: 
09-26 09:01:29.777  9754  9821 I jxcore-log: Number of ignored tests:  0
09-26 09:01:29.777  9754  9821 I jxcore-log: 
09-26 09:01:29.777  9754  9821 I jxcore-log: Total duration:  2
09-26 09:01:29.777  9754  9821 I jxcore-log: 
09-26 09:01:29.777  9754  9821 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-26 09:01:29.777  9754  9821 I jxcore-log: 
,09-26 09:01:29.777  9754  9821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-26 09:01:29.777  9754  9821 I jxcore-log: 
09-26 09:01:29.777  9754  9821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-26 09:01:29.777  9754  9821 I jxcore-log: 
,09-26 09:01:29.807  9754  9754 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-26 09:01:30.237  9825  9825 I FIPS_bssl: FIPS approved mode (1) | 9825 | app_process
,09-26 09:01:30.237  9825  9825 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-26 09:01:30.247  9825  9825 D AndroidRuntime: CheckJNI is OFF
09-26 09:01:30.247  9825  9825 D AndroidRuntime: readGMSProperty: start
09-26 09:01:30.247  9825  9825 D AndroidRuntime: readGMSProperty: already setted!!
09-26 09:01:30.247  9825  9825 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-26 09:01:30.247  9825  9825 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-26 09:01:30.247  9825  9825 D AndroidRuntime: readGMSProperty: end
09-26 09:01:30.247  9825  9825 D AndroidRuntime: addProductProperty: start
,09-26 09:01:30.257  9825  9825 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-26 09:01:30.277  9825  9825 I Radio-JNI: register_android_hardware_Radio DONE
,09-26 09:01:30.287  9825  9825 E AffinityControl: AffinityControl: registerfunction enter
,09-26 09:01:30.297  9825  9825 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-26 09:01:30.297  3440  3461 D PackageManager: START PACKAGE DELETE: observer{262411284}
09-26 09:01:30.297  3440  3461 D PackageManager: pkg{<packageName>}
09-26 09:01:30.297  3440  3461 D PackageManager: user{0}
09-26 09:01:30.297  3440  3461 D PackageManager: caller{2000}
09-26 09:01:30.297  3440  3461 D PackageManager: flags{2}
09-26 09:01:30.297  3440  3461 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-26 09:01:30.297  3440  3461 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-26 09:01:30.297  3440  3461 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-26 09:01:30.297  3440  3461 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-26 09:01:30.297  3440  3461 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-26 09:01:30.297  3440  3571 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-26 09:01:30.307  3440  3571 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-26 09:01:30.307  3440  3571 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-26 09:01:30.307  3440  3571 D ApplicationPolicy: getApplicationUninstallationEnabled
09-26 09:01:30.307  3440  3571 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-26 09:01:30.307  3440  3571 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-26 09:01:30.307  3440  3571 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-26 09:01:30.307  3440  3571 D PackageManager: !@killApplicatoin: 10177, uninstall pkg
09-26 09:01:30.307  3440  3571 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,09-26 09:01:30.307  3440  3519 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=-1: uninstall pkg
09-26 09:01:30.307  3440  3571 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-26 09:01:30.307  3440  3519 I ActivityManager: Killing 9754:com.test.thalitest/u0a177 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-26 09:01:30.307  3440  3519 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-26 09:01:30.317  3440  3519 D ActivityManager: mDVFSHelper.acquire()
,09-26 09:01:30.337  3440  3571 D AASAinstall: there is not AASApackages.xml file
,09-26 09:01:30.347  9834  9834 E Zygote  : v2
09-26 09:01:30.347  9834  9834 I libpersona: KNOX_SDCARD checking this for 10177
09-26 09:01:30.347  9834  9834 I libpersona: KNOX_SDCARD not a persona
,09-26 09:01:30.347  9834  9834 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-26 09:01:30.347  9834  9834 E Zygote  : accessInfo : 0
09-26 09:01:30.347  3440  3519 I ActivityManager: Start proc 9834:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-26 09:01:30.347  9834  9834 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,09-26 09:01:30.357  3440  3519 I ActivityManager:   Force finishing activity ActivityRecord{5686bf2 u0 com.test.thalitest/.MainActivity t12}
09-26 09:01:30.357  3440  3519 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,09-26 09:01:30.377  9834  9834 D TimaKeyStoreProvider: TimaSignature is unavailable
09-26 09:01:30.377  9834  9834 D ActivityThread: Added TimaKeyStore provider
,09-26 09:01:30.457  3440  3967 D GraphicsStats: Buffer count: 7
,09-26 09:01:30.457  3440  4820 I WindowState: WIN DEATH: Window{4bd0f76 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
09-26 09:01:30.457  3440  4331 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2890a03)
09-26 09:01:30.457  3440  3863 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-26 09:01:30.457  3440  3863 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-26 09:01:30.467  3440  3863 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-26 09:01:30.467  3009  4397 I SurfaceFlinger: id=21 Removed NainActivit (6/10)
,09-26 09:01:30.477  3009  3019 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
,09-26 09:01:30.487  3009  4397 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
,09-26 09:01:30.617  3440  3571 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-26 09:01:30.677  3440  3571 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
09-26 09:01:30.677  3165  3165 W keystore: ENTER clear_uid from uid 1000 for 10177
,09-26 09:01:30.677  3440  3571 I art     : Starting a blocking GC Explicit
,09-26 09:01:30.687  3440  3549 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-26 09:01:30.687  3440  3549 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-26 09:01:30.687  3440  3549 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
09-26 09:01:30.687  3440  3549 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-26 09:01:30.687  3440  3549 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-26 09:01:30.687  3440  3549 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-26 09:01:30.687  3440  3549 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 09:01:30.687  3440  3549 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-26 09:01:30.687  3440  3549 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 09:01:30.687  3440  3549 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-26 09:01:30.687  3440  3549 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-26 09:01:30.687  3440  3549 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{f64de75 V.E...... R.....ID 0,0-0,0}
,09-26 09:01:30.687  3440  3549 W WindowManager: Failed looking up window
09-26 09:01:30.687  3440  3549 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@d388e0a does not exist
09-26 09:01:30.687  3440  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 09:01:30.687  3440  3549 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-26 09:01:30.687  3440  3549 D ISSUE_DEBUG: InputChannelName : 217b67b Starting com.test.thalitest
,09-26 09:01:30.697  5817  5827 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,09-26 09:01:30.697  3440  3440 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
09-26 09:01:30.697  5817  6628 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} Intent { flg=0x10800000 cmp=com.samsung.android.MtpApplication/.USBConnection VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-26 09:01:30.707  3009  3009 I SurfaceFlinger: id=22 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-26 09:01:30.717  3440  4330 I ActivityManager: Killing 8916:com.samsung.android.app.appsedge/u0a1 (adj 15): DHA:empty #33
,09-26 09:01:30.727  3440  3519 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-26 09:01:30.727  4314  4314 D Launcher: onRestart, Launcher: 132634249
,09-26 09:01:30.737  3440  3519 D InputDispatcher: Focused application released
,09-26 09:01:30.737  3440  3549 W WindowManager: Failed looking up window
09-26 09:01:30.737  3440  3549 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@d388e0a does not exist
09-26 09:01:30.737  3440  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14795)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService.relayoutWindow(WindowManagerService.java:5208)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at com.android.server.wm.Session.relayout(Session.java:208)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.view.ViewRootImpl.relayoutWindow(ViewRootImpl.java:6690)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1994)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1437)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:7403)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:920)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.view.Choreographer.doCallbacks(Choreographer.java:695)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.view.Choreographer.doFrame(Choreographer.java:631)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:906)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.os.Handler.handleCallback(Handler.java:739)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-26 09:01:30.737  3440  3549 E ViewSystem: ViewRootImpl #2 Surface is not valid.
09-26 09:01:30.737  9834  9834 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-26 09:01:30.737  9834  9834 D RelationGraph: garbageCollect()
09-26 09:01:30.737  3440  3549 D ViewRootImpl: #3 mView = null
,09-26 09:01:30.737  3440  3549 W WindowManager: Failed looking up window
09-26 09:01:30.737  3440  3549 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@d388e0a does not exist
09-26 09:01:30.737  3440  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14795)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:4612)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:196)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3754)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:6893)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:4238)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 09:01:30.737  3440  3549 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-26 09:01:30.737  9834  9834 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,09-26 09:01:30.737  9834  9834 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-26 09:01:30.737  3440  4605 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-26 09:01:30.747  4314  4314 D Launcher: onStart, Launcher: 132634249
,09-26 09:01:30.747  4314  4314 D Launcher.HomeView: onStart
,09-26 09:01:30.747  9834  9834 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
,09-26 09:01:30.747  9834  9834 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
09-26 09:01:30.747  9834  9834 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
09-26 09:01:30.747  9834  9834 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
09-26 09:01:30.747  4314  4314 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-26 09:01:30.757  4314  4314 V ActivityThread: updateVisibility : ActivityRecord{90c0b65 token=android.os.BinderProxy@6072bc {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-26 09:01:30.757  3440  4820 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.appsedge, Auto Run ON
,09-26 09:01:30.757  9834  9834 I InjectionManager: Inside getClassLibPath caller 
,09-26 09:01:30.757  3009  3009 I SurfaceFlinger: id=23 createSurf (1440x2560),1 flag=4, MauncherAct
,09-26 09:01:30.757  3440  4819 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,09-26 09:01:30.757  3440  4819 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 09:01:30.757  3440  3440 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-26 09:01:30.767  4314  4633 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-26 09:01:30.767  3440  6104 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-26 09:01:30.767  9834  9834 D AndroidRuntime: Shutting down VM
09-26 09:01:30.767  9834  9834 E AndroidRuntime: FATAL EXCEPTION: main
09-26 09:01:30.767  9834  9834 E AndroidRuntime: Process: com.test.thalitest, PID: 9834
09-26 09:01:30.767  9834  9834 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-26 09:01:30.767  9834  9834 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
09-26 09:01:30.767  9834  9834 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6294)
09-26 09:01:30.767  9834  9834 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:222)
09-26 09:01:30.767  9834  9834 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1861)
09-26 09:01:30.767  9834  9834 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 09:01:30.767  9834  9834 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
09-26 09:01:30.767  9834  9834 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7229)
09-26 09:01:30.767  9834  9834 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 09:01:30.767  9834  9834 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-26 09:01:30.767  9834  9834 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-26 09:01:30.767  9834  9834 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-26 09:01:30.767  9834  9834 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
09-26 09:01:30.767  9834  9834 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
09-26 09:01:30.767  9834  9834 E AndroidRuntime: 	... 9 more
,09-26 09:01:30.777  3440  3440 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-26 09:01:30.777  3440  3440 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-26 09:01:30.777  9834  9834 I Process : Sending signal. PID: 9834 SIG: 9
,09-26 09:01:30.807  9681  9681 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
09-26 09:01:30.807  3440  3519 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{331ecf1 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f554eb 9681:com.samsung.android.sm/1000}
,09-26 09:01:30.817  3440  4820 V WindowStateAnimator: Finishing drawing window Window{ddf7dc9 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
,09-26 09:01:30.817  3440  4330 I ActivityManager: Process com.test.thalitest (pid 9834)(adj 9) has died(154,1779)
,09-26 09:01:30.827  3440  4330 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
09-26 09:01:30.827  3440  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26743 com.android.server.am.ActivityManagerService.appDiedLocked:7562 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1916 android.os.BinderProxy.sendDeathNotice:558 
,09-26 09:01:30.827  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fd2b2cf98
,09-26 09:01:30.837  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fd2b2cf98
,09-26 09:01:30.837  3440  4404 V WindowStateAnimator: Finishing drawing window Window{5ee56ce u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-26 09:01:30.837  3440  3571 I art     : Explicit concurrent mark sweep GC freed 111819(7MB) AllocSpace objects, 6(1912KB) LOS objects, 32% free, 33MB/49MB, paused 1.766ms total 160.882ms
09-26 09:01:30.837  3009  3009 I SurfaceFlinger: id=24 createSurf (1592x384),1 flag=4, VSBConnecti
,09-26 09:01:30.847  3440  6104 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-26 09:01:30.847  3440  6104 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-26 09:01:30.847  3440  3549 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-26 09:01:30.847  3440  3440 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-26 09:01:30.847  3440  3549 D ActivityManager: mDVFSHelper.release()
09-26 09:01:30.847  3440  3549 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5be4a4 u0 com.sec.android.app.launcher/.activities.LauncherActivity t9} time:207199
,09-26 09:01:30.857  3440  3440 I KnoxTimeoutHandler: SD activityfalse
,09-26 09:01:30.857  6175  6175 V ActivityThread: updateVisibility : ActivityRecord{79da5e0 token=android.os.BinderProxy@5dede8d {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,09-26 09:01:30.867  3440  3571 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-26 09:01:30.867  3440  3571 D AASAuninstall: userId = 0, info.removedAppID = 10177, info.uid = 10177, packageName = com.test.thalitest
,09-26 09:01:30.867  3440  4331 V WindowStateAnimator: Finishing drawing window Window{d319cfc u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-26 09:01:30.867  6175  6175 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5dede8d time:207215
09-26 09:01:30.867  4314  4314 D Launcher.HomeView: onStop
09-26 09:01:30.867  4314  4314 D capture : ----destroy
,09-26 09:01:30.867  3440  6104 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-26 09:01:30.867  3440  3571 D AASAinstall: there is not AASApackages.xml file
09-26 09:01:30.867  3440  3571 D PackageManager: result of delete: 1{262411284}
,09-26 09:01:30.867  3440  3571 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-26 09:01:30.867  3440  3571 D PackageManager: userId{-1}
09-26 09:01:30.867  3440  3571 D PackageManager: andCode{true}
09-26 09:01:30.867  9825  9825 I art     : System.exit called, status: 0
09-26 09:01:30.867  9825  9825 I AndroidRuntime: VM exiting with result code 0.
09-26 09:01:30.867  3440  6104 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
09-26 09:01:30.867  3440  6104 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-26 09:01:30.887  9852  9852 E Zygote  : v2
09-26 09:01:30.887  9852  9852 I libpersona: KNOX_SDCARD checking this for 10010
09-26 09:01:30.887  9852  9852 I libpersona: KNOX_SDCARD not a persona
09-26 09:01:30.887  9852  9852 E libpersona: scanKnoxPersonas
09-26 09:01:30.887  9852  9852 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
,09-26 09:01:30.887  9852  9852 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-26 09:01:30.887  3440  3571 I ActivityManager: Start proc 9852:com.android.defcontainer/u0a10 for service com.android.defcontainer/.DefaultContainerService
09-26 09:01:30.887  3440  3571 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=0: pkg removed
09-26 09:01:30.887  9852  9852 E Zygote  : accessInfo : 0
09-26 09:01:30.887  9852  9852 E libpersona: scanKnoxPersonas
09-26 09:01:30.887  9852  9852 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
,09-26 09:01:30.897  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fd2b2cf98
,09-26 09:01:30.917  9852  9852 D TimaKeyStoreProvider: TimaSignature is unavailable
09-26 09:01:30.917  9852  9852 D ActivityThread: Added TimaKeyStore provider
,09-26 09:01:30.957  3440  3549 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 09:01:30.957  3440  3440 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-26 09:01:30.957  3440  3440 I KnoxTimeoutHandler: SD activityfalse
,09-26 09:01:30.977  3440  3549 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{44d45b8 u0 com.samsung.android.MtpApplication/.USBConnection t11} time:207325
,09-26 09:01:30.977  3440  3902 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/12_task.xml
,09-26 09:01:30.977  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:30.987  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:30.987  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:30.987  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:30.987  9852  9852 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-26 09:01:30.987  9852  9852 D RelationGraph: garbageCollect()
09-26 09:01:30.987  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:30.997  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-26 09:01:30.997  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-26 09:01:30.997  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:30.997  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-26 09:01:30.997  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-26 09:01:30.997  9852  9852 W ResourcesManager: getTopLevelResources: /system/priv-app/DefaultContainerService/DefaultContainerService.apk / 1.0 running in com.android.defcontainer rsrc of package com.android.defcontainer
,09-26 09:01:30.997  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,09-26 09:01:30.997  3440  3849 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-26 09:01:30.997  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-26 09:01:30.997  9852  9852 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-26 09:01:30.997  5817  5817 I TrayVisibilityController: handleMessage : msg.what = 1
,09-26 09:01:31.007  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.007  9852  9852 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:31.007  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,09-26 09:01:31.007  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-26 09:01:31.007  3440  3512 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:31.017  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.017  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-26 09:01:31.017  3944  3944 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
09-26 09:01:31.017  3440  3512 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-26 09:01:31.017  3944  3944 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
09-26 09:01:31.017  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.017  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-26 09:01:31.017  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.017  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-26 09:01:31.017  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.017  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,09-26 09:01:31.017  3440  3512 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:31.017  9852  9852 I InjectionManager: Inside getClassLibPath caller 
,09-26 09:01:31.017  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:31.017  3440  3512 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-26 09:01:31.017  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-26 09:01:31.017  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm,
,09-26 09:01:31.027  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:31.027  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-26 09:01:31.027  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:31.027  3440  3512 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-26 09:01:31.027  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-26 09:01:31.027  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:31.027  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-26 09:01:31.027  3440  3512 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-26 09:01:31.027  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:31.027  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
09-26 09:01:31.027  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,09-26 09:01:31.027  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-26 09:01:31.027  4143  4143 I CatchNotificationsService: mPackageChangedReceiver : onReceive action = android.intent.action.PACKAGE_REMOVED
,09-26 09:01:31.027  3440  3512 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:31.027  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.027  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-26 09:01:31.027  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-26 09:01:31.027  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,09-26 09:01:31.027  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,09-26 09:01:31.037  3440  3549 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
,09-26 09:01:31.037  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:31.037  9852  9852 D InjectionManager: InjectionManager
09-26 09:01:31.037  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-26 09:01:31.037  9852  9852 D InjectionManager: fillFeatureStoreMap com.android.defcontainer
09-26 09:01:31.037  3440  3512 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:31.037  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,09-26 09:01:31.037  3440  3512 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
,09-26 09:01:31.037  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.037  3440  3549 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.037  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:31.037  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms,
09-26 09:01:31.037  9852  9852 I InjectionManager: Constructor com.android.defcontainer, Feature store :{}
09-26 09:01:31.037  3440  3549 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
,09-26 09:01:31.037  9852  9852 I InjectionManager: featureStore :{}
09-26 09:01:31.037  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.037  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:31.037  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.037  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.037  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:31.037  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.037  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.037  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3826 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
09-26 09:01:31.047  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.047  3440  3512 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
09-26 09:01:31.047  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-26 09:01:31.057  3440  3512 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
09-26 09:01:31.057  3440  3512 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
09-26 09:01:31.057  4301  4301 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.android.phone rsrc of package com.android.mms
09-26 09:01:31.057  3440  3512 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.057  4278  4777 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-26 09:01:31.057  3440  3512 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
09-26 09:01:31.057  3440  3512 D AccessibilityManagerService: onUserStateChangedLocked()
09-26 09:01:31.057  3440  3512 D AccessibilityManagerService: updateServicesLocked().mIsAccessibilityEnabled : false
09-26 09:01:31.057  9852  9866 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
09-26 09:01:31.057  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.057  4301  4301 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.057  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-26 09:01:31.057  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  9852  9866 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  5046  5260 D PresenceModule: onReceive: package removed
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  5046  5260 D PresenceModule: handleMessage: msg 50, Last Publish Info: null
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.067  5046  5260 D PresenceModule: Application package removed
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.067  5046  5260 D PresenceModule: onAppPkgRemoved: com.test.thalitest
09-26 09:01:31.067  5046  5260 D PresenceModule: onApplicationPackageRemoved: invalid package
09-26 09:01:31.067  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.067  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.077  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.077  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.077  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.077  4301  4301 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.phone rsrc of package com.google.android.talk
09-26 09:01:31.077  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.077  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.077  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.077  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.077  3440  3440 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:31.077  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-26 09:01:31.077  9852  9866 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
09-26 09:01:31.077  4158  4158 I PeoplePackageManager: onReceive:android.intent.action.PACKAGE_REMOVED
09-26 09:01:31.077  3440  3512 D EnterpriseDeviceManagerService: Package has changed for user 0
09-26 09:01:31.077  3440  3512 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-26 09:01:31.077  8412  8431 I SystemBroadcastReceiver: [#CMH#] Received broadcast 
09-26 09:01:31.077  8412  8431 I ControllerEventHandler: [#CMH#] onPackageRemoved  null
09-26 09:01:31.077  8412  8431 I SystemBroadcastReceiver: [#CMH#] onReceive completed 
,09-26 09:01:31.087  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.087  3440  3512 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-26 09:01:31.087  4301  4301 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.087  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-26 09:01:31.087  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-26 09:01:31.087  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-26 09:01:31.087  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-26 09:01:31.087  3440  3512 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-26 09:01:31.087  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-26 09:01:31.087  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.087  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-26 09:01:31.087  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:31.097  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:31.097  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:31.097  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:31.097  3440  3519 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d6d60f u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f2d3b8 6509:com.samsung.klmsagent/u0a28}
09-26 09:01:31.097  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:31.097  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:31.097  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
09-26 09:01:31.097  6509  6509 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Mon Sep 26 09:01:31 GMT+02:00 2016
09-26 09:01:31.097  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.097  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
09-26 09:01:31.097  3440  3512 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.097  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-26 09:01:31.097  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-26 09:01:31.097  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-26 09:01:31.107  3440  3851 V NetworkStats: removeUidsLocked() for UIDs [10177]
09-26 09:01:31.107  3440  3851 D NtpTrustedTime: currentTimeMillis() cache hit
09-26 09:01:31.107  3440  3851 V NetworkStats: performPollLocked(flags=0x3)
09-26 09:01:31.107  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.107  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-26 09:01:31.107  3440  3512 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.107  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-26 09:01:31.107  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-26 09:01:31.107  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-26 09:01:31.107  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-26 09:01:31.107  3440  3851 D NetworkStatsRecorder: entry.iface is null
09-26 09:01:31.107  3440  3851 D NetworkStatsRecorder: entry.iface is null
09-26 09:01:31.107  3440  3851 D NetworkStatsRecorder: entry.iface is null
09-26 09:01:31.107  3440  3851 D NetworkStatsRecorder: entry.iface is null
09-26 09:01:31.107  4021  4021 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
09-26 09:01:31.107  3440  3440 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.107  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.107  3440  3461 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4902, uid=10130 that is not exported from uid 10128
09-26 09:01:31.107  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:31.107  3440  3512 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
09-26 09:01:31.107  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-26 09:01:31.117  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-26 09:01:31.117  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-26 09:01:31.117  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-26 09:01:31.117  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-26 09:01:31.117  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-26 09:01:31.117  3440  3512 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.117  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-26 09:01:31.117  3440  3440 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos

```
