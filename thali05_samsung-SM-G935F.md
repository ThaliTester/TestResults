#### Test 912434548f3f6c6_thali05_samsung-SM-G935F Logs


```
--------- beginning of main
11-01 12:09:39.341  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:39.521  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-01 12:09:39.701  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-01 12:09:39.851  9800  9800 I FIPS_bssl: FIPS approved mode (1) | 9800 | app_process
11-01 12:09:39.861  9800  9800 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-01 12:09:39.861  9800  9800 D AndroidRuntime: CheckJNI is OFF
11-01 12:09:39.861  9800  9800 D AndroidRuntime: readGMSProperty: start
11-01 12:09:39.861  9800  9800 D AndroidRuntime: readGMSProperty: already setted!!
11-01 12:09:39.861  9800  9800 D AndroidRuntime: propertySet: couldn't set property (it is from app)
11-01 12:09:39.861  9800  9800 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
11-01 12:09:39.861  9800  9800 D AndroidRuntime: readGMSProperty: end
11-01 12:09:39.861  9800  9800 D AndroidRuntime: addProductProperty: start
11-01 12:09:39.881  9800  9800 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-01 12:09:39.881  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-01 12:09:39.901  9800  9800 I Radio-JNI: register_android_hardware_Radio DONE
11-01 12:09:39.911  9800  9800 E AffinityControl: AffinityControl: registerfunction enter
11-01 12:09:39.911  9800  9800 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-01 12:09:39.941  3451  4406 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
11-01 12:09:39.941  3451  4406 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
11-01 12:09:39.971  3451  4406 D ResourcesManager: For user 0 new overlays fetched Null
11-01 12:09:39.971  3451  4406 D GameManagerService: identifyGamePackage. com.test.thalitest
11-01 12:09:39.981  3451  4406 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
11-01 12:09:39.981  3451  4406 D ActivityManager: mDVFSHelper.acquire()
11-01 12:09:39.981  3451  4406 V WindowManager: addAppToken: AppWindowToken{d0108404f token=Token{2d88aae ActivityRecord{ef21729 u0 com.test.thalitest/.MainActivity t13}}} to stack=2 task=13 at 0
11-01 12:09:39.991  3451  3588 I InjectionManager: Inside getClassLibPath caller 
11-01 12:09:40.001  3451  3588 D SecWifiDisplayUtil: Metadata value : SecSettings2
11-01 12:09:40.001  3451  3588 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{465ea47 V.E...... R.....ID 0,0-0,0}
11-01 12:09:40.001  9809  9809 E Zygote  : v2
11-01 12:09:40.001  9809  9809 I libpersona: KNOX_SDCARD checking this for 10177
11-01 12:09:40.001  9809  9809 I libpersona: KNOX_SDCARD not a persona
11-01 12:09:40.001  9809  9809 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
11-01 12:09:40.001  9809  9809 E Zygote  : accessInfo : 0
11-01 12:09:40.001  9809  9809 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
11-01 12:09:40.001  3451  4406 I ActivityManager: Start proc 9809:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
11-01 12:09:40.001  3451  3588 W WindowManager: Failed looking up window
11-01 12:09:40.001  3451  3588 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@6b09274 does not exist
11-01 12:09:40.001  3451  3588 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-01 12:09:40.001  3451  3588 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-01 12:09:40.001  3451  3588 D ISSUE_DEBUG: InputChannelName : f85e39d Starting com.test.thalitest
11-01 12:09:40.011  3451  4406 D InputDispatcher: Focused application set to: xxxx
11-01 12:09:40.011  3451  3856 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
11-01 12:09:40.011  9800  9800 D AndroidRuntime: Shutting down VM
11-01 12:09:40.021  3006  3006 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
11-01 12:09:40.041  9809  9809 D TimaKeyStoreProvider: TimaSignature is unavailable
11-01 12:09:40.041  9809  9809 D ActivityThread: Added TimaKeyStore provider
11-01 12:09:40.051  6181  6181 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
11-01 12:09:40.061  3451  3983 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3451
11-01 12:09:40.061  3451  3983 I libsuspend: !@autosuspend_wakeup_count_disable
11-01 12:09:40.061  3451  3983 D PowerManagerService: mDisplayReady: false
11-01 12:09:40.061  3451  3983 I libsuspend: !@autosuspend_wakeup_count_disable done
11-01 12:09:40.061  3451  3591 D DisplayPowerController: animateScreenStateChange[0]: target=3
11-01 12:09:40.061  6181  6181 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
11-01 12:09:40.061  3451  3591 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
11-01 12:09:40.061  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-01 12:09:40.061  3451  3983 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
11-01 12:09:40.061  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f78d03c00
11-01 12:09:40.061  3451  3591 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-01 12:09:40.061  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
11-01 12:09:40.061  3451  3591 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-01 12:09:40.061  3451  3602 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
11-01 12:09:40.071  3006  3052 W SurfaceFlinger: Ignoring duplicate VSYNC event from HWC (t=191992334400)
11-01 12:09:40.071  3451  3591 I libsuspend: !@autosuspend_wakeup_count_enable
11-01 12:09:40.071  3451  3978 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3451
11-01 12:09:40.071  3451  3591 I libsuspend: !@autosuspend_wakeup_count_enable done
11-01 12:09:40.071  3451  3591 D DisplayPowerController: animateScreenStateChange[0]: target=3
11-01 12:09:40.071  3451  3591 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
11-01 12:09:40.071  3451  3591 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-01 12:09:40.071  3451  3591 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-01 12:09:40.071  3451  3591 D DisplayPowerController: animateScreenStateChange[0]: target=3
11-01 12:09:40.071  3451  3591 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
11-01 12:09:40.071  3451  3591 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-01 12:09:40.071  3451  3591 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-01 12:09:40.071  3451  3591 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
11-01 12:09:40.071  3451  3591 D PowerManagerService: mDisplayReady: true
11-01 12:09:40.071  3451  3591 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
11-01 12:09:40.081  3451  4622 V WindowStateAnimator: Finishing drawing window Window{750c942 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
11-01 12:09:40.091  3451  4441 D ActivityManager:  Launching com.test.thalitest, updated priority
11-01 12:09:40.091  6795  6795 V ActivityThread: updateVisibility : ActivityRecord{5ad4a08 token=android.os.BinderProxy@5c72106 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
11-01 12:09:40.111  3006  3015 I SurfaceFlinger: id=18 Removed YUIInstallC (5/14)
11-01 12:09:40.111  3006  4456 I SurfaceFlinger: id=18 Removed YUIInstallC (-2/14)
11-01 12:09:40.111  3451  3451 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
11-01 12:09:40.121  5825  5835 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
11-01 12:09:40.121  3451  3553 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
11-01 12:09:40.121  3006  3015 D libEGL  : eglTerminate EGLDisplay = 0x7f78a80e78
11-01 12:09:40.131  3006  3015 D libEGL  : eglTerminate EGLDisplay = 0x7f78a80e78
11-01 12:09:40.141  3006  3015 I SurfaceFlinger: id=10 Removed MauncherAct (4/13)
11-01 12:09:40.141  3006  3017 I SurfaceFlinger: id=10 Removed MauncherAct (-2/13)
11-01 12:09:40.151  3451  3853 V WindowStateAnimator: Finishing drawing window Window{4a79c24 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
11-01 12:09:40.151  6181  6181 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
11-01 12:09:40.151  6181  6181 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
11-01 12:09:40.151  6181  6181 V ActivityThread: updateVisibility : ActivityRecord{939fd token=android.os.BinderProxy@3f0ab17 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
11-01 12:09:40.151  3006  3017 I SurfaceFlinger: id=19 Removed VSBConnecti (7/12)
11-01 12:09:40.151  4309  4309 V ActivityThread: updateVisibility : ActivityRecord{3502c06 token=android.os.BinderProxy@29c2f6e {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
11-01 12:09:40.151  4309  4309 D Launcher: onTrimMemory. Level: 20
11-01 12:09:40.151  3006  4168 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/12)
11-01 12:09:40.161  3006  4456 D libEGL  : eglTerminate EGLDisplay = 0x7f713fee78
11-01 12:09:40.161  3006  4168 I SurfaceFlinger: id=20 Removed VSBConnecti (5/11)
11-01 12:09:40.161  3006  4625 I SurfaceFlinger: id=20 Removed VSBConnecti (-2/11)
11-01 12:09:40.161  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fe0029b78
11-01 12:09:40.161  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fe0029b78
11-01 12:09:40.161  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fe0029b48
11-01 12:09:40.211  3451  3451 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3451 (0x0)
11-01 12:09:40.221  3451  3451 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3451 (0x0)
11-01 12:09:40.221  3451  3451 I libsuspend: !@autosuspend_wakeup_count_disable
11-01 12:09:40.221  3451  3451 D PowerManagerService: mDisplayReady: false
11-01 12:09:40.221  3451  3451 I libsuspend: !@autosuspend_wakeup_count_disable done
11-01 12:09:40.221  3451  3591 D DisplayPowerController: animateScreenStateChange[0]: target=4
11-01 12:09:40.221  3451  3451 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
11-01 12:09:40.221  3451  3591 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
11-01 12:09:40.221  3451  3591 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-01 12:09:40.221  3451  3591 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-01 12:09:40.221  3451  3602 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
11-01 12:09:40.221  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f78d03c00
11-01 12:09:40.221  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
11-01 12:09:40.221  3451  3591 D DisplayPowerController: animateScreenStateChange[0]: target=4
11-01 12:09:40.221  3451  3591 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
11-01 12:09:40.221  3451  3591 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-01 12:09:40.221  3451  3591 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-01 12:09:40.221  3451  3591 I libsuspend: !@autosuspend_wakeup_count_enable
11-01 12:09:40.221  3451  3591 D DisplayPowerController: animateScreenStateChange[0]: target=4
11-01 12:09:40.221  3451  3591 I libsuspend: !@autosuspend_wakeup_count_enable done
11-01 12:09:40.221  3451  3591 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
11-01 12:09:40.221  3451  3591 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-01 12:09:40.221  3451  3591 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-01 12:09:40.221  3451  3591 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
11-01 12:09:40.221  3451  3591 D PowerManagerService: mDisplayReady: true
11-01 12:09:40.221  3451  3591 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,11-01 12:09:40.241  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:40.421  5825  5825 I TrayVisibilityController: handleMessage : msg.what = 1
,11-01 12:09:40.421  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:40.451  3451  4441 I WindowManager: Screenshot max retries 4 of Token{2d88aae ActivityRecord{ef21729 u0 com.test.thalitest/.MainActivity t13}} appWin=Window{f85e39d u0 d0 Starting com.test.thalitest} drawState=1
,11-01 12:09:40.451  5825  6555 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
,11-01 12:09:40.451  3451  3588 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
11-01 12:09:40.451  3451  3588 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
11-01 12:09:40.451  3451  3451 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,11-01 12:09:40.481  3451  3451 I KnoxTimeoutHandler: SD activityfalse
,11-01 12:09:40.481  5825  5825 I Utils   : isCurrentUser current = 0, ownerId = 0
,11-01 12:09:40.481  5825  5825 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
,11-01 12:09:40.491  3451  6112 D GameManagerService: identifyGamePackage. com.test.thalitest
,11-01 12:09:40.481  5825  5825 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
,11-01 12:09:40.491  3451  6112 D GameManagerService: identifyGamePackage. com.test.thalitest,
11-01 12:09:40.491  3451  3856 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,11-01 12:09:40.501  9809  9809 D RelationGraph: garbageCollect()
11-01 12:09:40.491  9809  9809 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
11-01 12:09:40.501  3451  3583 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,11-01 12:09:40.501  9809  9809 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,11-01 12:09:40.501  3451  4981 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,11-01 12:09:40.501  9809  9809 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
11-01 12:09:40.501  3451  3588 V WindowStateAnimator: Finishing drawing window Window{f85e39d u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
,11-01 12:09:40.511  3451  6112 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,11-01 12:09:40.511  3451  3588 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
11-01 12:09:40.511  3451  3451 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,11-01 12:09:40.511  3451  3588 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a7f5ade u0 com.samsung.android.MtpApplication/.USBConnection t12} time:192438
11-01 12:09:40.511  3451  3588 D ActivityManager: mDVFSHelper.release()
,11-01 12:09:40.521  3451  6112 D GameManagerService: identifyGamePackage. com.test.thalitest
,11-01 12:09:40.521  3451  3451 I KnoxTimeoutHandler: SD activityfalse
,11-01 12:09:40.521  3006  3006 D libEGL  : eglInitialize EGLDisplay = 0x7fe0029a58
,11-01 12:09:40.531  3451  6112 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,11-01 12:09:40.531  9809  9809 D ResourcesManager: For user 0 new overlays fetched Null
,11-01 12:09:40.531  3451  6112 D GameManagerService: identifyGamePackage. com.test.thalitest
11-01 12:09:40.531  3451  6112 D GameManagerService: identifyGamePackage. com.test.thalitest
,11-01 12:09:40.531  9809  9809 I InjectionManager: Inside getClassLibPath caller 
,11-01 12:09:40.561  9809  9809 D InjectionManager: InjectionManager
,11-01 12:09:40.561  9809  9809 D InjectionManager: fillFeatureStoreMap com.test.thalitest
11-01 12:09:40.561  9809  9809 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
11-01 12:09:40.561  9809  9809 I InjectionManager: featureStore :{}
,11-01 12:09:40.561  9809  9809 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,11-01 12:09:40.561  9809  9809 D RelationGraph: garbageCollect()
,11-01 12:09:40.571  9809  9809 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,11-01 12:09:40.591  9809  9809 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
,11-01 12:09:40.601  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:40.641  9809  9809 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
,11-01 12:09:40.641  9809  9809 D ResourcesManager: For user 0 new overlays fetched Null
,11-01 12:09:40.641  9809  9809 I InjectionManager: Inside getClassLibPath caller 
,11-01 12:09:40.651  9809  9809 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-01 12:09:40.681  9809  9809 I cr_LibraryLoader: Time to load native libraries: 20 ms (timestamps 2585-2605)
11-01 12:09:40.681  9809  9809 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,11-01 12:09:40.711  3451  6112 D SSRM:n  : SIOP:: AP = 290, PST = 289 (W:10), CP = 238, CUR = 104, LCD = 1
,11-01 12:09:40.741  3451  3880 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,11-01 12:09:40.751  9809  9825 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,11-01 12:09:40.771  9809  9809 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bc6e5e2}
11-01 12:09:40.771  9809  9809 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,11-01 12:09:40.781  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:40.791  9809  9809 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,11-01 12:09:40.831  9809  9809 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,11-01 12:09:40.841  3451  3880 I MdnieScenarioControlService: mGameModeLauncher : false
11-01 12:09:40.841  3451  3880 I MdnieScenarioControlService: setUIMode
,11-01 12:09:40.951  3451  3553 W ActivityManager: Activity pause timeout for ActivityRecord{ef21729 u0 com.test.thalitest/.MainActivity t13}
,11-01 12:09:40.961  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:41.041  9809  9809 D libEGL  : eglInitialize EGLDisplay = 0xffd5181c
,11-01 12:09:41.141  3451  4441 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
11-01 12:09:41.141  3451  4441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,11-01 12:09:41.141  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:41.231  9809  9809 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,11-01 12:09:41.251  9809  9809 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-01 12:09:41.261  9809  9809 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,11-01 12:09:41.291  9809  9809 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,11-01 12:09:41.321  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:41.351  9809  9809 D Activity: performCreate Call Injection manager
,11-01 12:09:41.351  9809  9809 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,11-01 12:09:41.371  9809  9809 D SecWifiDisplayUtil: Metadata value : SecSettings2
,11-01 12:09:41.371  9809  9809 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5dbaf89 I.E...... R.....ID 0,0-0,0}
,11-01 12:09:41.381  9809  9862 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-01 12:09:41.391  3451  3853 W WindowManager: Failed looking up window
11-01 12:09:41.391  3451  3853 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@1a1747d does not exist
11-01 12:09:41.391  3451  3853 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
11-01 12:09:41.391  3451  3853 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
11-01 12:09:41.391  3451  3853 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
11-01 12:09:41.391  3451  3853 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
11-01 12:09:41.391  3451  3853 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
11-01 12:09:41.391  3451  3853 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,11-01 12:09:41.391  3451  5002 D ISSUE_DEBUG: InputChannelName : 8eadf72 com.test.thalitest/com.test.thalitest.MainActivity
,11-01 12:09:41.391  3451  4257 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,11-01 12:09:41.391  3451  4257 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
11-01 12:09:41.391  3451  3451 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,11-01 12:09:41.401  3451  3451 I KnoxTimeoutHandler: Shared devices show user statefalse
,11-01 12:09:41.401  9809  9809 V ActivityThread: updateVisibility : ActivityRecord{9417faf token=android.os.BinderProxy@fa3dc71 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,11-01 12:09:41.411  9809  9825 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,11-01 12:09:41.441  9809  9809 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9809
,11-01 12:09:41.441  3451  4622 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9809 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-01 12:09:41.441  3451  3867 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,11-01 12:09:41.441  3451  3867 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-01 12:09:41.451  3451  3867 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,11-01 12:09:41.451  3451  6113 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,11-01 12:09:41.461  3451  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,11-01 12:09:41.461  3451  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,11-01 12:09:41.471  9809  9809 D SecWifiDisplayUtil: Metadata value : SecSettings2
,11-01 12:09:41.471  3451  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,11-01 12:09:41.471  3451  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,11-01 12:09:41.481  3451  4145 E Watchdog: !@Sync 6 [11-01 12:09:41.487]
,11-01 12:09:41.481  3451  3867 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,11-01 12:09:41.481  3451  3867 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-01 12:09:41.491  3006  3006 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
,11-01 12:09:41.501  9809  9862 D libEGL  : eglInitialize EGLDisplay = 0xdc23f7c4
11-01 12:09:41.501  9809  9862 I OpenGLRenderer: Initialized EGL, version 1.4
,11-01 12:09:41.501  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:41.511  9809  9862 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,11-01 12:09:41.511  3451  4410 I libsuspend: !@autosuspend_wakeup_count_disable
,11-01 12:09:41.511  3451  4410 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3451
11-01 12:09:41.511  3451  4410 I libsuspend: !@autosuspend_wakeup_count_disable done
11-01 12:09:41.511  3451  4410 D PowerManagerService: mDisplayReady: false
11-01 12:09:41.511  3006  3006 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f78d03c00
,11-01 12:09:41.511  3451  3591 D DisplayPowerController: animateScreenStateChange[0]: target=3
11-01 12:09:41.511  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
11-01 12:09:41.511  3451  4410 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
11-01 12:09:41.511  3451  3591 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
11-01 12:09:41.511  3451  3591 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-01 12:09:41.511  3451  3591 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-01 12:09:41.511  3451  3602 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
,11-01 12:09:41.511  3451  3588 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
11-01 12:09:41.511  3451  3588 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,11-01 12:09:41.531  3451  3591 D DisplayPowerController: animateScreenStateChange[0]: target=3
,11-01 12:09:41.531  3451  3591 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
11-01 12:09:41.531  3451  3591 I libsuspend: !@autosuspend_wakeup_count_enable
11-01 12:09:41.531  3451  3591 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-01 12:09:41.531  3451  3591 I libsuspend: !@autosuspend_wakeup_count_enable done
11-01 12:09:41.531  3451  3591 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-01 12:09:41.531  3451  3591 D DisplayPowerController: animateScreenStateChange[0]: target=3
11-01 12:09:41.531  3451  3591 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
11-01 12:09:41.531  3451  3591 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-01 12:09:41.531  3451  3591 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-01 12:09:41.531  3451  3591 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,11-01 12:09:41.531  3451  3591 D PowerManagerService: mDisplayReady: true
11-01 12:09:41.531  3451  3591 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,11-01 12:09:41.541  5825  5825 E CocktailBarPositionManager: Window direction: 0
11-01 12:09:41.541  5825  5825 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,11-01 12:09:41.551  9809  9809 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,11-01 12:09:41.561  3451  4410 V WindowStateAnimator: Finishing drawing window Window{8eadf72 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,11-01 12:09:41.561  9809  9866 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-01 12:09:41.561  9809  9809 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
11-01 12:09:41.561  9809  9866 D libEGL  : eglInitialize EGLDisplay = 0xdb77f3f4
,11-01 12:09:41.571  3451  3588 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
11-01 12:09:41.571  3451  4406 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3451
11-01 12:09:41.571  3451  3451 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,11-01 12:09:41.571  3451  3451 I KnoxTimeoutHandler: SD activityfalse
,11-01 12:09:41.571  3451  4981 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3451
11-01 12:09:41.571  3451  3588 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s121ms (total +1s586ms)
11-01 12:09:41.571  3451  3588 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ef21729 u0 com.test.thalitest/.MainActivity t13} time:193497
11-01 12:09:41.571  3451  3588 D ViewRootImpl: #3 mView = null
,11-01 12:09:41.571  3006  4625 I SurfaceFlinger: id=21 Removed uhalitest (6/11)
,11-01 12:09:41.571  3006  3017 I SurfaceFlinger: id=21 Removed uhalitest (-2/11)
11-01 12:09:41.581  9809  9866 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
11-01 12:09:41.581  3006  3006 D libEGL  : eglTerminate EGLDisplay = 0x7fe0029b78
11-01 12:09:41.581  3451  3978 V WindowStateAnimator: Finishing drawing window Window{8eadf72 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN,
,11-01 12:09:41.591  9809  9809 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@fa3dc71 time:193512
,11-01 12:09:41.631  9809  9809 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9809
,11-01 12:09:41.681  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:41.721  3451  3451 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3451 (0x0)
11-01 12:09:41.721  3451  3451 I libsuspend: !@autosuspend_wakeup_count_disable
11-01 12:09:41.721  3451  3451 D PowerManagerService: mDisplayReady: false
11-01 12:09:41.721  3451  3451 I libsuspend: !@autosuspend_wakeup_count_disable done
11-01 12:09:41.721  3451  3591 D DisplayPowerController: animateScreenStateChange[0]: target=4
11-01 12:09:41.721  3451  3591 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
11-01 12:09:41.721  3451  3451 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
11-01 12:09:41.721  3451  3591 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-01 12:09:41.721  3451  3591 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-01 12:09:41.721  3451  3602 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
11-01 12:09:41.721  3006  3006 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f78d03c00
11-01 12:09:41.721  3451  3588 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
11-01 12:09:41.721  3006  3006 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
11-01 12:09:41.721  3451  3588 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,11-01 12:09:41.741  3451  3591 D DisplayPowerController: animateScreenStateChange[0]: target=4
11-01 12:09:41.741  3451  3591 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
11-01 12:09:41.741  3451  3591 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-01 12:09:41.741  3451  3591 I libsuspend: !@autosuspend_wakeup_count_enable
11-01 12:09:41.741  3451  3591 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-01 12:09:41.741  3451  3591 I libsuspend: !@autosuspend_wakeup_count_enable done
11-01 12:09:41.741  3451  3591 D DisplayPowerController: animateScreenStateChange[0]: target=4
11-01 12:09:41.741  3451  3591 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
11-01 12:09:41.741  3451  3591 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-01 12:09:41.741  3451  3591 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
11-01 12:09:41.741  3451  3591 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
11-01 12:09:41.741  3451  3591 D PowerManagerService: mDisplayReady: true
11-01 12:09:41.741  3451  3591 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,11-01 12:09:41.741  5825  5825 E CocktailBarPositionManager: Window direction: 0
11-01 12:09:41.741  5825  5825 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
,11-01 12:09:41.861  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:41.871  9809  9809 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-01 12:09:41.951  4023  4023 D Recents : onTaskStackChanged
,11-01 12:09:41.961  4023  4023 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,11-01 12:09:41.971  4023  4023 D ResourcesManager: For user 0 new overlays fetched Null
,11-01 12:09:41.991  9809  9873 D jxcore_app_log: JniHelper::setJavaVM(0xf49b4000), pthread_self() = -640681680
,11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2128cf9 added. We now have 1 listener(s)
,11-01 12:09:41.991  9809  9873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
,11-01 12:09:41.991  9809  9873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
,11-01 12:09:41.991  9809  9873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:09:41.991  9809  9873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-01 12:09:41.991  9809  9873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33dafec added. We now have 1 listener(s)
11-01 12:09:41.991  9809  9873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-01 12:09:42.001  9809  9873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-01 12:09:42.001  9809  9873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-01 12:09:42.001  9809  9873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,9,main], id: 159
11-01 12:09:42.001  9809  9873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-01 12:09:42.001  9809  9873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-01 12:09:42.001  9809  9873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-01 12:09:42.001  9809  9873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,9,main], id: 159
,11-01 12:09:42.001  9809  9873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-01 12:09:42.001  9809  9873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
,11-01 12:09:42.011  9809  9873 D BluetoothAdapter: STATE_ON
,11-01 12:09:42.011  9809  9873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-01 12:09:42.011  9809  9873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:09:42.011  9809  9873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:42.011  9809  9873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:42.011  9809  9873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:42.011  9809  9873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:42.011  9809  9873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:42.011  9809  9873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:09:42.011  9809  9873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:09:42.011  9809  9873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-01 12:09:42.011  9809  9873 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:09:42.011  9809  9873 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-01 12:09:42.021  9809  9809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:09:42.021  9809  9809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:09:42.041  9809  9809 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-01 12:09:42.041  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:42.221  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:42.401  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:42.561  9809  9874 W jxcore-log: Initializing JXcore engine
11-01 12:09:42.561  9809  9874 W jxcore-log: JXcore engine is ready
,11-01 12:09:42.581  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:42.581  4952  4952 E audit   : type=1400 msg=audit(1477998582.581:264): avc:  denied  { ioctl } for  pid=9874 comm="Thread-160" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2194 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-01 12:09:42.581  4952  4952 E audit   :  SEPF_SECMOBILE_6.0.1_0013
11-01 12:09:42.581  4952  4952 E audit   : type=1300 msg=audit(1477998582.581:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d890a3c8 items=0 ppid=3178 pid=9874 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
11-01 12:09:42.591  4952  4952 E audit   : type=1327 msg=audit(1477998582.581:264): proctitle="com.test.thalitest"
11-01 12:09:42.591  4952  4952 E audit   : type=1320 msg=audit(1477998582.581:264): 
11-01 12:09:42.591  4952  4952 E audit   : type=1400 msg=audit(1477998582.581:265): avc:  denied  { ioctl } for  pid=9874 comm="Thread-160" path="socket:[39000]" dev="sockfs" ino=39000 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-01 12:09:42.591  4952  4952 E audit   :  SEPF_SECMOBILE_6.0.1_0013
11-01 12:09:42.591  4952  4952 E audit   : type=1300 msg=audit(1477998582.581:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d890a3c8 items=0 ppid=3178 pid=9874 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-160" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
11-01 12:09:42.591  4952  4952 E audit   : type=1327 msg=audit(1477998582.581:265): proctitle="com.test.thalitest"
11-01 12:09:42.591  4952  4952 E audit   : type=1320 msg=audit(1477998582.581:265): 
,11-01 12:09:42.591  9809  9874 W jxcore-log: Starting JXcore engine
,11-01 12:09:42.631  9809  9874 W jxcore-log: Platform android
11-01 12:09:42.631  9809  9874 W jxcore-log: 
11-01 12:09:42.631  9809  9874 W jxcore-log: Process ARCH arm
11-01 12:09:42.631  9809  9874 W jxcore-log: 
,11-01 12:09:42.751  9809  9874 I jxcore-log: JXcore Cordova bridge is ready!
11-01 12:09:42.751  9809  9874 I jxcore-log: 
11-01 12:09:42.751  9809  9874 W jxcore-log: JXcore engine is started
,11-01 12:09:42.761  9809  9873 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
11-01 12:09:42.761  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:42.771  9809  9809 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-01 12:09:42.791  4411  4471 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
11-01 12:09:42.791  4411  4471 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,11-01 12:09:42.941  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:42.991  3451  3907 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/13_task.xml.bak
,11-01 12:09:43.121  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:43.301  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:43.481  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:43.501  3451  6112 D GameManagerService: identifyGamePackage. com.test.thalitest
,11-01 12:09:43.661  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:43.841  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:44.021  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:44.201  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:44.381  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:44.561  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:44.741  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:44.921  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:45.101  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:45.281  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:45.461  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:45.641  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:45.821  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:46.001  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:46.181  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:46.361  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:46.541  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:46.541  3451  6112 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,11-01 12:09:46.721  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:46.901  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:47.081  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:47.261  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:47.441  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:47.621  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:47.801  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:47.981  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:48.161  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:48.341  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:48.521  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:48.701  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:48.881  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:48.971  9809  9874 I jxcore-log: 2016-11-01 11:09:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-01 12:09:48.971  9809  9874 I jxcore-log: 
,11-01 12:09:48.971  9809  9874 I jxcore-log: 2016-11-01 11:09:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-01 12:09:48.971  9809  9874 I jxcore-log: 
,11-01 12:09:48.981  9809  9874 D BluetoothAdapter: STATE_ON
,11-01 12:09:48.981  9809  9874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:09:48.981  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:48.981  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:48.981  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:48.981  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:48.981  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:48.981  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:09:48.981  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:09:48.991  9809  9874 D BluetoothAdapter: STATE_ON
,11-01 12:09:48.991  9809  9874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-01 12:09:48.991  9809  9874 I jxcore-log: 2016-11-01 11:09:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-01 12:09:48.991  9809  9874 I jxcore-log: 
11-01 12:09:48.991  9809  9874 I jxcore-log: 2016-11-01 11:09:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-01 12:09:48.991  9809  9874 I jxcore-log: 
,11-01 12:09:49.061  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:49.151  9809  9874 I jxcore-log: 2016-11-01 11:09:49 - DEBUG UnitTest_app: 'Running unit tests'
11-01 12:09:49.151  9809  9874 I jxcore-log: 
,11-01 12:09:49.151  9809  9874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-01 12:09:49.151  9809  9874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39cfe46 added. We now have 2 listener(s)
11-01 12:09:49.151  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
11-01 12:09:49.151  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:09:49.151  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-01 12:09:49.151  9809  9874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:09:49.151  9809  9874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f75c807 added. We now have 2 listener(s)
11-01 12:09:49.151  9809  9874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-01 12:09:49.151  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-01 12:09:49.151  9809  9874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-01 12:09:49.161  9809  9874 D BluetoothAdapter: STATE_ON
,11-01 12:09:49.171  9809  9874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:09:49.171  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:49.171  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:49.171  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:49.171  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:49.171  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:49.171  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:09:49.171  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:09:49.171  9809  9874 D BluetoothAdapter: STATE_ON
,11-01 12:09:49.171  9809  9874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-01 12:09:49.171  9809  9874 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:09:49.171  9809  9874 D executeNativeTests: Running unit tests
,11-01 12:09:49.181  9809  9809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:09:49.191  9809  9809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:09:49.201  9809  9874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-01 12:09:49.201  9809  9874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d7d1cd added. We now have 3 listener(s)
11-01 12:09:49.201  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
11-01 12:09:49.201  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-01 12:09:49.201  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-01 12:09:49.201  9809  9874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-01 12:09:49.201  9809  9874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5efa82 added. We now have 3 listener(s)
,11-01 12:09:49.201  9809  9874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-01 12:09:49.201  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-01 12:09:49.211  9809  9874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-01 12:09:49.221  9809  9874 D BluetoothAdapter: STATE_ON
,11-01 12:09:49.221  9809  9874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:09:49.221  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:49.221  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:49.221  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:49.221  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:49.221  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:49.221  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:09:49.221  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-01 12:09:49.221  9809  9874 D BluetoothAdapter: STATE_ON
,11-01 12:09:49.231  9809  9874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-01 12:09:49.231  9809  9874 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-01 12:09:49.241  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:49.241  9809  9809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:09:49.241  9809  9809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-01 12:09:49.251  9809  9874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-01 12:09:49.251  9809  9874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-01 12:09:49.251  9809  9874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-01 12:09:49.251  9809  9874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-01 12:09:49.251  9809  9874 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-01 12:09:49.251  9809  9874 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-01 12:09:49.251  9809  9874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-01 12:09:49.251  9809  9874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-01 12:09:49.251  9809  9874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-01 12:09:49.251  9809  9874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-01 12:09:49.251  9809  9874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-01 12:09:49.251  9809  9874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:09:49.251  9809  9874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:09:49.251  9809  9874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:09:49.251  9809  9874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-01 12:09:49.251  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:09:49.251  9809  9874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-01 12:09:49.251  9809  9874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-01 12:09:49.251  9809  9874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d7d1cd removed from the list
11-01 12:09:49.251  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:49.251  9809  9874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5efa82 removed from the list
11-01 12:09:49.251  9809  9874 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:09:49.251  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-01 12:09:49.251  9809  9874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:49.251  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:49.251  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.261  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:09:49.261  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-01 12:09:49.261  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:49.261  9809  9874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5efa82 not in the list
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-01 12:09:49.261  9809  9874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-01 12:09:49.261  9809  9874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:09:49.261  9809  9874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:09:49.261  9809  9874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:09:49.261  9809  9874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:09:49.261  9809  9874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d7d1cd not in the list
11-01 12:09:49.261  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:49.261  9809  9874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5efa82 not in the list
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:09:49.261  9809  9874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:49.261  9809  9874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.261  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:09:49.261  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:09:49.261  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:49.261  9809  9874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5efa82 not in the list
,11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-01 12:09:49.261  9809  9874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-01 12:09:49.261  9809  9874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-01 12:09:49.261  9809  9874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-01 12:09:49.261  9809  9874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:09:49.261  9809  9874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-01 12:09:49.261  9809  9874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d7d1cd not in the list
11-01 12:09:49.261  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:49.261  9809  9874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5efa82 not in the list
11-01 12:09:49.261  9809  9874 D io.jxcore.node.ConnectivityMonitor: stop
11-01 12:09:49.261  9809  9874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:49.261  9809  9874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:49.261  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.271  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.271  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.271  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.271  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-01 12:09:49.271  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-01 12:09:49.271  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:49.271  9809  9874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5efa82 not in the list
11-01 12:09:49.271  9809  9874 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-01 12:09:49.271  9809  9874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-01 12:09:49.281  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.281  9809  9874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-01 12:09:49.281  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-01 12:09:49.281  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-01 12:09:49.281  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-01 12:09:49.281  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-01 12:09:49.281  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:49.281  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-01 12:09:49.281  9809  9874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-01 12:09:49.291  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.291  9809  9874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-01 12:09:49.291  9809  9874 D io.jxcore.node.ConnectivityMonitor: start: OK
11-01 12:09:49.291  9809  9874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-01 12:09:49.291  9809  9874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-01 12:09:49.291  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-01 12:09:49.291  9809  9874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-01 12:09:49.291  9809  9874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-01 12:09:49.291  9809  9809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:49.301  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-01 12:09:49.301  9809  9874 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-01 12:09:49.301  9809  9874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-01 12:09:49.301  9809  9809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-01 12:09:49.301  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.301  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.311  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.311  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.311  9809  9874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-01 12:09:49.311  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.311  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.311  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-01 12:09:49.321  9809  9874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-01 12:09:49.321  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.321  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.321  9809  9874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-01 12:09:49.331  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.331  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.331  9809  9874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-01 12:09:49.331  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.331  9809  9874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-01 12:09:49.331  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-01 12:09:49.331  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-01 12:09:49.331  9809  9874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-01 12:09:49.331  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.331  9809  9874 D BluetoothLeScanner: Start Scan
11-01 12:09:49.331  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.331  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.341  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:49.341  9809  9874 D BluetoothAdapter: STATE_ON
,11-01 12:09:49.341  4947  5449 D BtGatt.GattService: registerClient() - UUID=50410d43-a792-4748-bbcd-5f37c8b28191
,11-01 12:09:49.391  4947  5074 D BtGatt.GattService: onClientRegistered() - UUID=50410d43-a792-4748-bbcd-5f37c8b28191, clientIf=7
,11-01 12:09:49.391  9809  9819 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,11-01 12:09:49.401  4947  4961 D BtGatt.GattService: start scan with filters
,11-01 12:09:49.401  4947  4961 D BtGatt.GattService: getScanSettings
,11-01 12:09:49.421  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:49.421  4947  4961 D BtGatt.GattService: Is it foreground application = true
,11-01 12:09:49.421  4947  4961 D BtGatt.GattService: not a background application
,11-01 12:09:49.431  4947  4961 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,11-01 12:09:49.441  4947  4961 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,11-01 12:09:49.441  4947  4961 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,11-01 12:09:49.441  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-01 12:09:49.441  4947  5131 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
11-01 12:09:49.441  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.441  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-01 12:09:49.441  4947  5131 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 31, currDate: 1
11-01 12:09:49.451  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:49.451  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-01 12:09:49.451  4947  5116 D BtGatt.ScanManager: handling starting scan
11-01 12:09:49.451  4947  5116 D BtGatt.ScanManager: isFilteringSupported
11-01 12:09:49.451  9809  9809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-01 12:09:49.451  4947  5116 D BluetoothAdapter: enableStandAloneBleMode=
11-01 12:09:49.451  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-01 12:09:49.451  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-01 12:09:49.451  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-01 12:09:49.451  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-01 12:09:49.451  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-01 12:09:49.451  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-01 12:09:49.451  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-160,9,main], id: 160
,11-01 12:09:49.451  9809  9809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-01 12:09:49.451  4947  5116 D BluetoothAdapter: STATE_ON
,11-01 12:09:49.461  4947  5116 D BluetoothAdapter: STATE_ON
,11-01 12:09:49.461  4947  5116 D BluetoothAdapter: STATE_ON
,11-01 12:09:49.461  4947  5116 D BluetoothAdapter: STATE_ON
11-01 12:09:49.461  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-160,9,main], id: 160
,11-01 12:09:49.461  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-01 12:09:49.461  4947  5116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc6e5e2
11-01 12:09:49.461  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-160,9,main], id: 160
,11-01 12:09:49.461  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-160,9,main], id: 160
,11-01 12:09:49.471  9809  9809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-01 12:09:49.471  3451  3490 V AlarmManager:  remove PendingIntent] PendingIntent{cf6222b: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
11-01 12:09:49.471  9809  9874 I io.jxcore.node.ConnectionHelper: start: OK
,11-01 12:09:49.471  9809  9809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-01 12:09:49.471  9809  9809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:49.471  9809  9809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-01 12:09:49.471  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:09:49.471  4947  5131 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24633309
11-01 12:09:49.471  9809  9809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-01 12:09:49.471  4947  5131 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
11-01 12:09:49.471  4947  5131 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
,11-01 12:09:49.471  4947  5131 D BtGatt.GattService: [GSIM LOG]: reportData
11-01 12:09:49.481  4947  5131 D BtGatt.GattService: [GSIM LOG]: reportData, LST: com.test.thalitest
11-01 12:09:49.481  3451  4981 V AlarmManager:  remove PendingIntent] PendingIntent{b77d688: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:49.481  4947  5131 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24633309
,11-01 12:09:49.481  4947  5074 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
11-01 12:09:49.481  4947  5074 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,11-01 12:09:49.481  4947  5116 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
11-01 12:09:49.481  4947  5116 D BtGatt.ScanManager: High Rssi Filter value is = -128
11-01 12:09:49.481  4947  5116 D BtGatt.ScanManager: Low Rssi Filter value is = -128
11-01 12:09:49.481  4947  5116 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,11-01 12:09:49.491  3451  4257 V AlarmManager:  remove PendingIntent] PendingIntent{a93f821: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
11-01 12:09:49.491  4947  5074 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
11-01 12:09:49.491  4947  5074 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,11-01 12:09:49.491  4947  5116 D BtGatt.ScanManager: Starting BLE batch scan
,11-01 12:09:49.491  4947  5116 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,11-01 12:09:49.491  3451  4955 V AlarmManager:  remove PendingIntent] PendingIntent{120e446: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:49.501  3451  4410 V AlarmManager:  remove PendingIntent] PendingIntent{4b2b607: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:49.501  4947  5131 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 1
,11-01 12:09:49.501  4947  5131 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,11-01 12:09:49.501  3451  4312 V AlarmManager:  remove PendingIntent] PendingIntent{3f7d334: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:49.511  4947  5131 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 1
,11-01 12:09:49.511  4947  5131 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
11-01 12:09:49.511  4947  5131 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,11-01 12:09:49.511  4947  5131 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
,11-01 12:09:49.511  3451  5002 V AlarmManager:  remove PendingIntent] PendingIntent{116f55d: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:49.531  3451  4406 V AlarmManager:  remove PendingIntent] PendingIntent{876fed2: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:49.531  4947  5074 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,11-01 12:09:49.531  4947  5074 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,11-01 12:09:49.531  4947  5074 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,11-01 12:09:49.531  4947  5074 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,11-01 12:09:49.531  3451  4402 V AlarmManager:  remove PendingIntent] PendingIntent{4baaba3: PendingIntentRecord{6d8eea0 com.android.bluetooth broadcastIntent}}
11-01 12:09:49.531  3451  4186 V AlarmManager:  remove PendingIntent] PendingIntent{2d28a59: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:49.541  3451  3490 V AlarmManager:  remove PendingIntent] PendingIntent{3a2361e: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:49.541  3451  4981 V AlarmManager:  remove PendingIntent] PendingIntent{1c25eff: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:49.541  3451  4257 V AlarmManager:  remove PendingIntent] PendingIntent{ee54cc: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:49.551  3451  3853 V AlarmManager:  remove PendingIntent] PendingIntent{5187315: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:49.601  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:49.781  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-01 12:09:49.961  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-01 12:09:49.981  9809  9809 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-01 12:09:49.981  9809  9809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-01 12:09:49.981  9809  9809 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-01 12:09:50.001  3451  3610 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
11-01 12:09:50.021  3451  3610 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
11-01 12:09:50.141  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-01 12:09:50.321  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-01 12:09:50.501  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-01 12:09:50.531  3451  3816 V AlarmManager: Expired Alarm result :4
11-01 12:09:50.541  4947  4947 D BtGatt.ScanManager: awakened up at time 202462
11-01 12:09:50.541  4947  5116 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
11-01 12:09:50.541  3451  4312 V AlarmManager:  remove PendingIntent] PendingIntent{d67ec1b: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
11-01 12:09:50.551  4947  5074 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
11-01 12:09:50.551  4947  5074 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
11-01 12:09:50.551  4947  5074 D BtGatt.GattService: current time is 202473292354
11-01 12:09:50.551  4947  5074 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -72, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -77, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-01 12:09:50.551  4947  5074 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-01 12:09:50.551  4947  5074 D ScanRecord: parseFromBytes
11-01 12:09:50.551  4947  5074 D ScanRecord: first manudata for manu ID
11-01 12:09:50.551  4947  5074 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-01 12:09:50.551  4947  5074 D ScanRecord: parseFromBytes
11-01 12:09:50.551  4947  5074 D ScanRecord: first manudata for manu ID
11-01 12:09:50.561  3451  3978 V AlarmManager:  remove PendingIntent] PendingIntent{711f1b8: PendingIntentRecord{6d8eea0 com.android.bluetooth broadcastIntent}}
11-01 12:09:50.561  9809  9820 D ScanRecord: parseFromBytes
11-01 12:09:50.561  9809  9820 D ScanRecord: first manudata for manu ID
11-01 12:09:50.561  9809  9820 D ScanRecord: parseFromBytes
11-01 12:09:50.561  9809  9820 D ScanRecord: first manudata for manu ID
11-01 12:09:50.561  3451  4622 V AlarmManager:  remove PendingIntent] PendingIntent{69a2b91: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
11-01 12:09:50.571  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
11-01 12:09:50.571  3451  4955 V AlarmManager:  remove PendingIntent] PendingIntent{c10eaf6: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
11-01 12:09:50.581  3451  4402 V AlarmManager:  remove PendingIntent] PendingIntent{b0f2ef7: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
11-01 12:09:50.581  3451  4441 V AlarmManager:  remove PendingIntent] PendingIntent{fd07164: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
11-01 12:09:50.591  3451  3491 V AlarmManager:  remove PendingIntent] PendingIntent{5a4efcd: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:50.681  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:50.741  3451  6112 D SSRM:n  : SIOP:: AP = 340, PST = 293 (W:6), CP = 247, CUR = 104, LCD = 1
,11-01 12:09:50.861  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:51.041  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:51.221  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:51.401  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:51.561  3451  3816 V AlarmManager: Expired Alarm result :4
,11-01 12:09:51.561  4947  4947 D BtGatt.ScanManager: awakened up at time 203487
,11-01 12:09:51.561  4947  5116 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,11-01 12:09:51.571  3451  4257 V AlarmManager:  remove PendingIntent] PendingIntent{67dc393: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:51.581  4947  5074 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
11-01 12:09:51.581  4947  5074 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
11-01 12:09:51.581  4947  5074 D BtGatt.GattService: current time is 203503357738
11-01 12:09:51.581  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
11-01 12:09:51.581  4947  5074 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -72, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -72, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-01 12:09:51.581  3451  3983 V AlarmManager:  remove PendingIntent] PendingIntent{bd53fd0: PendingIntentRecord{6d8eea0 com.android.bluetooth broadcastIntent}}
,11-01 12:09:51.581  4947  5074 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-01 12:09:51.581  4947  5074 D ScanRecord: parseFromBytes
11-01 12:09:51.581  4947  5074 D ScanRecord: first manudata for manu ID
11-01 12:09:51.581  4947  5074 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-01 12:09:51.581  4947  5074 D ScanRecord: parseFromBytes
11-01 12:09:51.581  4947  5074 D ScanRecord: first manudata for manu ID
11-01 12:09:51.581  9809  9819 D ScanRecord: parseFromBytes
11-01 12:09:51.581  9809  9819 D ScanRecord: first manudata for manu ID
,11-01 12:09:51.581  9809  9819 D ScanRecord: parseFromBytes
11-01 12:09:51.581  9809  9819 D ScanRecord: first manudata for manu ID
11-01 12:09:51.581  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
,11-01 12:09:51.591  3451  4186 V AlarmManager:  remove PendingIntent] PendingIntent{e1dbbc9: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:51.601  3451  4312 V AlarmManager:  remove PendingIntent] PendingIntent{85662ce: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:51.611  3451  3490 V AlarmManager:  remove PendingIntent] PendingIntent{83705ef: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:51.611  3451  4622 V AlarmManager:  remove PendingIntent] PendingIntent{91688fc: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:51.621  3451  4981 V AlarmManager:  remove PendingIntent] PendingIntent{b3d4b85: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:51.761  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:51.941  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:52.121  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:52.301  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:52.481  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:52.591  3451  3816 V AlarmManager: Expired Alarm result :4
,11-01 12:09:52.591  4947  4947 D BtGatt.ScanManager: awakened up at time 204515
,11-01 12:09:52.591  4947  5116 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,11-01 12:09:52.601  3451  3978 V AlarmManager:  remove PendingIntent] PendingIntent{398120b: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:52.601  4947  5074 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=2
11-01 12:09:52.601  4947  5074 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
11-01 12:09:52.601  4947  5074 D BtGatt.GattService: current time is 204523949275
11-01 12:09:52.601  3451  3490 V AlarmManager:  remove PendingIntent] PendingIntent{cc138e8: PendingIntentRecord{6d8eea0 com.android.bluetooth broadcastIntent}}
,11-01 12:09:52.601  4947  5074 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -77, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -78, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-01 12:09:52.601  4947  5074 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-01 12:09:52.601  4947  5074 D ScanRecord: parseFromBytes
,11-01 12:09:52.601  4947  5074 D ScanRecord: first manudata for manu ID
11-01 12:09:52.601  4947  5074 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-01 12:09:52.601  4947  5074 D ScanRecord: parseFromBytes
11-01 12:09:52.601  4947  5074 D ScanRecord: first manudata for manu ID
,11-01 12:09:52.601  9809  9820 D ScanRecord: parseFromBytes
11-01 12:09:52.601  9809  9820 D ScanRecord: first manudata for manu ID
11-01 12:09:52.601  9809  9820 D ScanRecord: parseFromBytes
11-01 12:09:52.601  9809  9820 D ScanRecord: first manudata for manu ID
11-01 12:09:52.601  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
,11-01 12:09:52.621  3451  4622 V AlarmManager:  remove PendingIntent] PendingIntent{90c1b01: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:52.631  3451  4981 V AlarmManager:  remove PendingIntent] PendingIntent{e27fda6: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:52.631  3451  4402 V AlarmManager:  remove PendingIntent] PendingIntent{ab3c3e7: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:52.641  3451  4441 V AlarmManager:  remove PendingIntent] PendingIntent{fe4fb94: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:52.641  3451  4410 V AlarmManager:  remove PendingIntent] PendingIntent{19e663d: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:52.661  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:52.841  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:53.021  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:53.201  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:53.381  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:53.561  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:53.601  3451  3816 V AlarmManager: Expired Alarm result :4
,11-01 12:09:53.611  4947  4947 D BtGatt.ScanManager: awakened up at time 205531
,11-01 12:09:53.611  4947  5116 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,11-01 12:09:53.611  3451  3983 V AlarmManager:  remove PendingIntent] PendingIntent{3eeb783: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:53.621  4947  5074 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
,11-01 12:09:53.621  4947  5074 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
11-01 12:09:53.621  4947  5074 D BtGatt.GattService: current time is 205548232852
11-01 12:09:53.621  3451  4955 V AlarmManager:  remove PendingIntent] PendingIntent{ae03d00: PendingIntentRecord{6d8eea0 com.android.bluetooth broadcastIntent}}
,11-01 12:09:53.621  4947  5074 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -69, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -77, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-01 12:09:53.621  4947  5074 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-01 12:09:53.621  4947  5074 D ScanRecord: parseFromBytes
11-01 12:09:53.621  4947  5074 D ScanRecord: first manudata for manu ID
11-01 12:09:53.631  4947  5074 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-01 12:09:53.631  4947  5074 D ScanRecord: parseFromBytes
11-01 12:09:53.631  4947  5074 D ScanRecord: first manudata for manu ID
,11-01 12:09:53.631  4947  5074 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-01 12:09:53.631  4947  5074 D ScanRecord: parseFromBytes
11-01 12:09:53.631  4947  5074 D ScanRecord: first manudata for manu ID
11-01 12:09:53.631  9809  9819 D ScanRecord: parseFromBytes
11-01 12:09:53.631  9809  9819 D ScanRecord: first manudata for manu ID
,11-01 12:09:53.631  9809  9819 D ScanRecord: parseFromBytes
11-01 12:09:53.631  9809  9819 D ScanRecord: first manudata for manu ID
11-01 12:09:53.631  9809  9819 D ScanRecord: parseFromBytes
11-01 12:09:53.631  9809  9819 D ScanRecord: first manudata for manu ID
,11-01 12:09:53.631  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 3. Current thread: Thread[main,5,main], id: 1
,11-01 12:09:53.641  3451  4186 V AlarmManager:  remove PendingIntent] PendingIntent{2102939: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:53.641  3451  3978 V AlarmManager:  remove PendingIntent] PendingIntent{8871b7e: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:53.651  3451  3491 V AlarmManager:  remove PendingIntent] PendingIntent{d5b48df: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:53.651  3451  4622 V AlarmManager:  remove PendingIntent] PendingIntent{b8c292c: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:53.661  3451  4406 V AlarmManager:  remove PendingIntent] PendingIntent{3411ff5: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:53.741  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:53.921  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:54.101  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:54.281  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:54.461  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:54.481  9809  9874 D BluetoothAdapter: STATE_ON
,11-01 12:09:54.481  9809  9874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-01 12:09:54.491  9809  9874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-01 12:09:54.491  9809  9874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-01 12:09:54.491  9809  9874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:54.491  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-01 12:09:54.491  9809  9874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-01 12:09:54.491  9809  9874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-01 12:09:54.491  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-01 12:09:54.491  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-01 12:09:54.491  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-01 12:09:54.491  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-160,9,main], id: 160
,11-01 12:09:54.491  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:54.491  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:54.491  9809  9874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-01 12:09:54.491  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-160,9,main], id: 160
,11-01 12:09:54.491  9809  9874 D BluetoothAdapter: STATE_ON
,11-01 12:09:54.501  9809  9874 D BluetoothAdapter: STATE_ON
,11-01 12:09:54.501  9809  9874 D BluetoothLeScanner: Stop Scan
,11-01 12:09:54.511  4947  4961 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,11-01 12:09:54.511  4947  4961 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,11-01 12:09:54.511  4947  4961 D BtGatt.GattService: stopScan() - queue size =1
11-01 12:09:54.511  4947  5131 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
11-01 12:09:54.511  4947  5131 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 1, currDate: 1
11-01 12:09:54.511  4947  5131 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
11-01 12:09:54.511  4947  5131 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
11-01 12:09:54.511  4947  5131 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 0 => 0
11-01 12:09:54.511  4947  5116 D BtGatt.ScanManager: filter size is 1
,11-01 12:09:54.511  4947  5131 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
11-01 12:09:54.511  4947  5131 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
11-01 12:09:54.511  4947  5449 D BtGatt.GattService: unregisterClient() - clientIf=7
,11-01 12:09:54.511  4947  5116 D BtGatt.ScanManager: delete FilterIndex - 3
11-01 12:09:54.511  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-01 12:09:54.521  3451  4406 V AlarmManager:  remove PendingIntent] PendingIntent{6f5718a: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
11-01 12:09:54.511  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:54.521  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-01 12:09:54.521  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-160,9,main], id: 160
,11-01 12:09:54.521  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:54.521  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:54.521  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:54.521  4947  5074 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
11-01 12:09:54.521  4947  5074 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,11-01 12:09:54.521  4947  5116 D BtGatt.ScanManager: stopping BLe Batch
11-01 12:09:54.521  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:54.521  9809  9874 D BluetoothAdapter: STATE_ON
11-01 12:09:54.521  4947  5074 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
11-01 12:09:54.521  9809  9874 D BluetoothLeAdvertiser: stop advertising
,11-01 12:09:54.521  4947  5074 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
11-01 12:09:54.521  4947  5116 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,11-01 12:09:54.521  9809  9874 D BluetoothLeAdvertiser: wrapper is null
11-01 12:09:54.521  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-01 12:09:54.531  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:54.531  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:54.531  3451  4441 V AlarmManager:  remove PendingIntent] PendingIntent{9d593fb: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:54.531  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:54.531  3451  3978 V AlarmManager:  remove PendingIntent] PendingIntent{228ac18: PendingIntentRecord{6d8eea0 com.android.bluetooth broadcastIntent}}
,11-01 12:09:54.531  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-01 12:09:54.531  9809  9874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-01 12:09:54.531  4947  5074 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,11-01 12:09:54.531  4947  5074 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
11-01 12:09:54.531  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-01 12:09:54.531  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:54.541  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:54.541  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-01 12:09:54.541  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:54.541  9809  9874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-160,9,main], id: 160
11-01 12:09:54.541  9809  9809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-01 12:09:54.541  9809  9874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-01 12:09:54.541  9809  9874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-01 12:09:54.541  3451  4410 V AlarmManager:  remove PendingIntent] PendingIntent{250c671: PendingIntentRecord{6d8eea0 com.android.bluetooth broadcastIntent}}
11-01 12:09:54.541  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-01 12:09:54.541  9809  9809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-01 12:09:54.541  9809  9874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-01 12:09:54.541  9809  9874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d7d1cd not in the list
11-01 12:09:54.541  9809  9874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-01 12:09:54.541  9809  9809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-01 12:09:54.541  9809  9874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5efa82 not in the list
11-01 12:09:54.541  9809  9874 D io.jxcore.node.ConnectivityMonitor: stop
,11-01 12:09:54.541  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-01 12:09:54.541  9809  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-01 12:09:54.541  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-01 12:09:54.541  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-01 12:09:54.541  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-01 12:09:54.541  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-01 12:09:54.541  9809  9809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-01 12:09:54.541  9809  9809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-01 12:09:54.551  9809  9809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-01 12:09:54.551  9809  9809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:54.551  3451  4312 V AlarmManager:  remove PendingIntent] PendingIntent{5411c56: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
11-01 12:09:54.551  9809  9809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-01 12:09:54.551  9809  9809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-01 12:09:54.551  9809  9809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-01 12:09:54.551  3451  3978 V AlarmManager:  remove PendingIntent] PendingIntent{3df74d7: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:54.561  3451  4406 V AlarmManager:  remove PendingIntent] PendingIntent{10871c4: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:54.561  3451  4955 V AlarmManager:  remove PendingIntent] PendingIntent{4da58ad: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:54.571  3451  3853 V AlarmManager:  remove PendingIntent] PendingIntent{acaa7e2: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:54.581  3451  4402 V AlarmManager:  remove PendingIntent] PendingIntent{23c8773: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:54.581  3451  3983 V AlarmManager:  remove PendingIntent] PendingIntent{afce630: PendingIntentRecord{dcdd700 com.android.bluetooth broadcastIntent}}
,11-01 12:09:54.641  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:54.821  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:55.001  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:55.051  9809  9809 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-01 12:09:55.181  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:55.361  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:55.541  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:55.721  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:55.901  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:56.081  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:56.261  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:56.441  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:56.621  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:56.801  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:56.981  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:57.161  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:57.341  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:57.521  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,11-01 12:09:57.661  3451  6148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,11-01 12:09:57.701  3451  3796 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120

```
