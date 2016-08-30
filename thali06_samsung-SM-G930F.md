#### Test 82642184cbac892_thali06_samsung-SM-G930F Logs


```
--------- beginning of main
08-30 02:49:03.167  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:03.347  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 02:49:03.527  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 02:49:03.697  9201  9201 I FIPS_bssl: FIPS approved mode (1) | 9201 | app_process
08-30 02:49:03.697  9201  9201 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 02:49:03.707  9201  9201 D AndroidRuntime: CheckJNI is OFF
08-30 02:49:03.707  9201  9201 D AndroidRuntime: readGMSProperty: start
08-30 02:49:03.707  9201  9201 D AndroidRuntime: readGMSProperty: already setted!!
08-30 02:49:03.707  9201  9201 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 02:49:03.707  9201  9201 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 02:49:03.707  9201  9201 D AndroidRuntime: readGMSProperty: end
08-30 02:49:03.707  9201  9201 D AndroidRuntime: addProductProperty: start
08-30 02:49:03.707  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 02:49:03.717  9201  9201 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 02:49:03.747  9201  9201 I Radio-JNI: register_android_hardware_Radio DONE
08-30 02:49:03.747  9201  9201 E AffinityControl: AffinityControl: registerfunction enter
08-30 02:49:03.757  9201  9201 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 02:49:03.787  3428  3765 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
08-30 02:49:03.787  3428  3765 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
08-30 02:49:03.817  3428  3765 D ResourcesManager: For user 0 new overlays fetched Null
08-30 02:49:03.817  3428  3765 D GameManagerService: identifyGamePackage. com.test.thalitest
08-30 02:49:03.817  3428  3765 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
08-30 02:49:03.817  3428  3765 D ActivityManager: mDVFSHelper.acquire()
08-30 02:49:03.827  3428  3765 V WindowManager: addAppToken: AppWindowToken{d0be27347 token=Token{cf04e86 ActivityRecord{231a361 u0 com.test.thalitest/.MainActivity t16}}} to stack=2 task=16 at 0
08-30 02:49:03.827  3428  3542 I InjectionManager: Inside getClassLibPath caller 
08-30 02:49:03.837  3428  3542 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-30 02:49:03.837  3428  3542 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{504843f V.E...... R.....ID 0,0-0,0}
08-30 02:49:03.837  9210  9210 E Zygote  : v2
08-30 02:49:03.837  9210  9210 I libpersona: KNOX_SDCARD checking this for 10170
08-30 02:49:03.837  9210  9210 I libpersona: KNOX_SDCARD not a persona
08-30 02:49:03.837  3428  3542 W WindowManager: Failed looking up window
08-30 02:49:03.837  3428  3542 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@af1b10c does not exist
08-30 02:49:03.837  3428  3542 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:49:03.837  3428  3542 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 02:49:03.837  9210  9210 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0012
08-30 02:49:03.847  3428  3542 D ISSUE_DEBUG: InputChannelName : 8223a55 Starting com.test.thalitest
08-30 02:49:03.847  9210  9210 E Zygote  : accessInfo : 0
08-30 02:49:03.847  9210  9210 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-30 02:49:03.847  3428  3765 I ActivityManager: Start proc 9210:com.test.thalitest/u0a170 for activity com.test.thalitest/.MainActivity
08-30 02:49:03.847  3428  3765 D InputDispatcher: Focused application set to: xxxx
08-30 02:49:03.847  9201  9201 D AndroidRuntime: Shutting down VM
08-30 02:49:03.847  3428  3841 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-30 02:49:03.847  2990  2990 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
08-30 02:49:03.877  9210  9210 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:49:03.877  9210  9210 D ActivityThread: Added TimaKeyStore provider
08-30 02:49:03.887  5879  5879 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 02:49:03.887  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 02:49:03.887  5879  5879 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 02:49:03.887  3428  4290 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3428
08-30 02:49:03.887  3428  4290 I libsuspend: !@autosuspend_wakeup_count_disable
08-30 02:49:03.887  3428  4290 D PowerManagerService: mDisplayReady: false
08-30 02:49:03.887  3428  4290 I libsuspend: !@autosuspend_wakeup_count_disable done
08-30 02:49:03.887  3428  3546 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 02:49:03.887  3428  3546 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 02:49:03.887  3428  4290 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-30 02:49:03.887  3428  3546 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 02:49:03.887  3428  3546 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 02:49:03.897  3428  3558 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
08-30 02:49:03.897  2990  2990 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f97b43c00
08-30 02:49:03.897  2990  2990 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
08-30 02:49:03.897  3428  3546 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 02:49:03.897  3428  3546 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 02:49:03.897  3428  3546 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 02:49:03.897  3428  3546 I libsuspend: !@autosuspend_wakeup_count_enable
08-30 02:49:03.897  3428  3546 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 02:49:03.897  3428  3546 I libsuspend: !@autosuspend_wakeup_count_enable done
08-30 02:49:03.897  3428  3546 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 02:49:03.897  3428  3546 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 02:49:03.897  3428  3546 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 02:49:03.897  3428  3546 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 02:49:03.897  3428  3546 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-30 02:49:03.897  3428  3546 D PowerManagerService: mDisplayReady: true
08-30 02:49:03.897  3428  3546 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
08-30 02:49:03.897  3428  4590 D ActivityManager:  Launching com.test.thalitest, updated priority
08-30 02:49:03.917  3428  3428 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
08-30 02:49:03.917  3428  3765 V WindowStateAnimator: Finishing drawing window Window{8101184 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-30 02:49:03.917  3428  3517 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-30 02:49:03.927  2990  3889 D libEGL  : eglTerminate EGLDisplay = 0x7f905fee78
08-30 02:49:03.927  2990  3889 D libEGL  : eglTerminate EGLDisplay = 0x7f905fee78
08-30 02:49:03.937  2990  3002 I SurfaceFlinger: id=10 Removed MauncherAct (4/13)
08-30 02:49:03.937  2990  3000 I SurfaceFlinger: id=10 Removed MauncherAct (-2/13)
08-30 02:49:03.947  3428  4304 V WindowStateAnimator: Finishing drawing window Window{fb24616 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-30 02:49:03.947  5879  5879 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 02:49:03.947  5879  5879 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 02:49:03.947  5879  5879 V ActivityThread: updateVisibility : ActivityRecord{62d4986 token=android.os.BinderProxy@726cb78 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-30 02:49:03.947  4278  4278 V ActivityThread: updateVisibility : ActivityRecord{5f6d876 token=android.os.BinderProxy@920cc42 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
08-30 02:49:03.947  4278  4278 D Launcher: onTrimMemory. Level: 20
08-30 02:49:03.947  2990  2990 D libEGL  : eglTerminate EGLDisplay = 0x7fda761a98
08-30 02:49:03.947  2990  2990 D libEGL  : eglInitialize EGLDisplay = 0x7fda761978
08-30 02:49:03.957  2990  3000 D libEGL  : eglTerminate EGLDisplay = 0x7f978c0e78
08-30 02:49:03.957  2990  3000 D libEGL  : eglTerminate EGLDisplay = 0x7f978c0e78
08-30 02:49:03.957  2990  3889 I SurfaceFlinger: id=17 Removed VSBConnecti (7/12)
08-30 02:49:03.957  2990  4349 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/12)
08-30 02:49:03.967  2990  4535 I SurfaceFlinger: id=18 Removed VSBConnecti (4/11)
08-30 02:49:03.967  2990  3000 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/11)
08-30 02:49:03.977  2990  2990 D libEGL  : eglTerminate EGLDisplay = 0x7fda761a98
08-30 02:49:03.977  2990  2990 D libEGL  : eglTerminate EGLDisplay = 0x7fda761a98
08-30 02:49:04.047  3428  3428 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3428 (0x0)
08-30 02:49:04.047  3428  3428 I libsuspend: !@autosuspend_wakeup_count_disable
08-30 02:49:04.047  3428  3428 D PowerManagerService: mDisplayReady: false
08-30 02:49:04.047  3428  3428 I libsuspend: !@autosuspend_wakeup_count_disable done
08-30 02:49:04.047  3428  3546 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 02:49:04.047  3428  3428 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-30 02:49:04.047  3428  3546 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 02:49:04.047  3428  3546 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 02:49:04.047  3428  3546 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 02:49:04.047  3428  3558 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
08-30 02:49:04.047  2990  2990 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f97b43c00
08-30 02:49:04.047  2990  2990 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
08-30 02:49:04.047  3428  3546 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 02:49:04.047  3428  3546 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 02:49:04.047  3428  3546 I libsuspend: !@autosuspend_wakeup_count_enable
08-30 02:49:04.047  3428  3546 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 02:49:04.047  3428  3546 I libsuspend: !@autosuspend_wakeup_count_enable done
08-30 02:49:04.047  3428  3546 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 02:49:04.047  3428  3546 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 02:49:04.047  3428  3546 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 02:49:04.047  3428  3546 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 02:49:04.047  3428  3546 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 02:49:04.047  3428  3546 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-30 02:49:04.047  3428  3546 D PowerManagerService: mDisplayReady: true
08-30 02:49:04.047  3428  3546 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
08-30 02:49:04.067  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:04.227  3428  4590 I WindowManager: Screenshot max retries 4 of Token{cf04e86 ActivityRecord{231a361 u0 com.test.thalitest/.MainActivity t16}} appWin=Window{8223a55 u0 d0 Starting com.test.thalitest} drawState=1
08-30 02:49:04.237  3428  3542 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 02:49:04.237  3428  3542 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
08-30 02:49:04.247  3428  3428 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 02:49:04.247  3428  3841 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-30 02:49:04.247  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 02:49:04.257  3428  3428 I KnoxTimeoutHandler: SD activityfalse
08-30 02:49:04.267  9210  9210 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-30 02:49:04.277  3428  5787 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-30 02:49:04.277  3428  3455 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
08-30 02:49:04.277  9210  9210 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
08-30 02:49:04.277  3428  3542 V WindowStateAnimator: Finishing drawing window Window{8223a55 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-30 02:49:04.277  3428  3542 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 02:49:04.277  3428  3428 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 02:49:04.287  3428  3542 D ActivityManager: mDVFSHelper.release()
08-30 02:49:04.287  3428  3542 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a87daa7 u0 com.samsung.android.MtpApplication/.USBConnection t15} time:296920
08-30 02:49:04.287  3428  3428 I KnoxTimeoutHandler: SD activityfalse
08-30 02:49:04.297  3428  5787 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-30 02:49:04.297  2990  2990 D libEGL  : eglInitialize EGLDisplay = 0x7fda761978
08-30 02:49:04.297  9210  9210 D ResourcesManager: For user 0 new overlays fetched Null
08-30 02:49:04.307  9210  9210 I InjectionManager: Inside getClassLibPath caller 
08-30 02:49:04.317  9210  9210 D InjectionManager: InjectionManager
08-30 02:49:04.317  9210  9210 D InjectionManager: fillFeatureStoreMap com.test.thalitest
08-30 02:49:04.317  9210  9210 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
08-30 02:49:04.317  9210  9210 I InjectionManager: featureStore :{}
08-30 02:49:04.327  9210  9210 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-30 02:49:04.327  9210  9210 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
08-30 02:49:04.327  9210  9210 D RelationGraph: garbageCollect()
08-30 02:49:04.337  9210  9210 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-30 02:49:04.367  9210  9210 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410650)
08-30 02:49:04.397  9210  9210 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
08-30 02:49:04.397  9210  9210 D ResourcesManager: For user 0 new overlays fetched Null
08-30 02:49:04.397  9210  9210 I InjectionManager: Inside getClassLibPath caller 
08-30 02:49:04.397  9210  9210 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 02:49:04.427  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 02:49:04.447  9210  9210 I cr_LibraryLoader: Time to load native libraries: 23 ms (timestamps 7057-7080)
08-30 02:49:04.447  9210  9210 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-30 02:49:04.467  9210  9225 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
08-30 02:49:04.467  9210  9210 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {41ec048}
08-30 02:49:04.467  9210  9210 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-30 02:49:04.487  9210  9210 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 02:49:04.487  3428  3864 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
08-30 02:49:04.517  9210  9210 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
08-30 02:49:04.597  3428  3864 I MdnieScenarioControlService: mGameModeLauncher : false
08-30 02:49:04.597  3428  3864 I MdnieScenarioControlService: setUIMode
08-30 02:49:04.607  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 02:49:04.737  3428  3517 W ActivityManager: Activity pause timeout for ActivityRecord{231a361 u0 com.test.thalitest/.MainActivity t16}
08-30 02:49:04.767  9210  9210 D libEGL  : eglInitialize EGLDisplay = 0xffbbb48c
08-30 02:49:04.767  9210  9210 D         : ro.exynos.dss isEnabled: 0
08-30 02:49:04.787  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 02:49:04.827  3428  4589 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10170
08-30 02:49:04.827  3428  4589 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29713 com.android.server.am.ActivityManagerService.registerReceiver:22578 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3988 
08-30 02:49:04.917  9210  9210 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
08-30 02:49:04.937  9210  9210 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 02:49:04.937  9210  9210 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
08-30 02:49:04.937  9210  9210 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
08-30 02:49:04.937  9210  9210 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
08-30 02:49:04.967  9210  9210 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
08-30 02:49:04.967  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 02:49:04.977  9210  9210 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-30 02:49:05.057  9210  9210 D Activity: performCreate Call Injection manager
,08-30 02:49:05.057  9210  9210 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,08-30 02:49:05.077  9210  9210 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-30 02:49:05.087  9210  9210 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{1e081c1 I.E...... R.....ID 0,0-0,0}
,08-30 02:49:05.097  9210  9262 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 02:49:05.107  3428  4321 W WindowManager: Failed looking up window
08-30 02:49:05.107  3428  4321 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@dba9c79 does not exist
08-30 02:49:05.107  3428  4321 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 02:49:05.107  3428  4321 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-30 02:49:05.107  3428  4321 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-30 02:49:05.107  3428  4321 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
08-30 02:49:05.107  3428  4321 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
08-30 02:49:05.107  3428  4321 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,08-30 02:49:05.107  3428  4590 D ISSUE_DEBUG: InputChannelName : 2b7adbe com.test.thalitest/com.test.thalitest.MainActivity
,08-30 02:49:05.107  3428  3965 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-30 02:49:05.107  3428  3965 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 02:49:05.107  3428  3428 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-30 02:49:05.107  3428  3428 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-30 02:49:05.117  9210  9210 V ActivityThread: updateVisibility : ActivityRecord{52168a7 token=android.os.BinderProxy@d21c0cf {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-30 02:49:05.147  9210  9210 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10170, CallingPid : 9210
,08-30 02:49:05.147  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:05.147  3428  3965 D ConnectivityService: listenForNetwork for Listen from uid/pid:10170/9210 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 02:49:05.147  3428  3852 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-30 02:49:05.147  3428  3852 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 02:49:05.147  3428  3852 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-30 02:49:05.147  3428  3852 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 02:49:05.147  3428  3852 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 02:49:05.147  3428  3852 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-30 02:49:05.147  3428  3852 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 02:49:05.147  3428  3852 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-30 02:49:05.147  3428  3852 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 02:49:05.167  9210  9210 D SecWifiDisplayUtil: Metadata value : SecSettings2
,08-30 02:49:05.167  9210  9225 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-30 02:49:05.187  2990  2990 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, NainActivit
,08-30 02:49:05.227  9210  9262 D libEGL  : eglInitialize EGLDisplay = 0xdcbff7c4
,08-30 02:49:05.227  9210  9262 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 02:49:05.227  9210  9262 D         : ro.exynos.dss isEnabled: 0
,08-30 02:49:05.227  9210  9262 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,08-30 02:49:05.237  3428  5788 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,08-30 02:49:05.247  3428  4769 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3428
,08-30 02:49:05.247  3428  4769 I libsuspend: !@autosuspend_wakeup_count_disable
08-30 02:49:05.247  3428  4769 D PowerManagerService: mDisplayReady: false
08-30 02:49:05.247  3428  4769 I libsuspend: !@autosuspend_wakeup_count_disable done
08-30 02:49:05.247  3428  4769 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-30 02:49:05.247  3428  3546 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 02:49:05.247  3428  3546 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 02:49:05.247  3428  3546 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,08-30 02:49:05.247  3428  3546 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 02:49:05.247  2990  2990 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7f97b43c00
08-30 02:49:05.247  3428  3558 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
08-30 02:49:05.247  2990  2990 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
,08-30 02:49:05.247  3428  3542 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
08-30 02:49:05.247  3428  3542 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,08-30 02:49:05.277  3428  3546 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 02:49:05.277  3428  3546 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 02:49:05.277  3428  3546 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 02:49:05.277  3428  3546 I libsuspend: !@autosuspend_wakeup_count_enable
08-30 02:49:05.277  3428  3546 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 02:49:05.277  3428  3546 I libsuspend: !@autosuspend_wakeup_count_enable done
08-30 02:49:05.277  3428  3546 D DisplayPowerController: animateScreenStateChange[0]: target=3
08-30 02:49:05.277  3428  3546 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
08-30 02:49:05.277  3428  3546 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 02:49:05.277  3428  3546 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 02:49:05.277  3428  3546 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-30 02:49:05.277  3428  3546 D PowerManagerService: mDisplayReady: true
08-30 02:49:05.277  3428  3546 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-30 02:49:05.287  9210  9210 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-30 02:49:05.297  9210  9266 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 02:49:05.297  9210  9266 D libEGL  : eglInitialize EGLDisplay = 0xdc33f3ec
,08-30 02:49:05.297  3428  3454 V WindowStateAnimator: Finishing drawing window Window{2b7adbe u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
08-30 02:49:05.297  9210  9210 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,08-30 02:49:05.307  9210  9266 D         : ro.exynos.dss isEnabled: 0
,08-30 02:49:05.307  3428  3765 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3428
,08-30 02:49:05.307  3428  3542 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 02:49:05.307  3428  3428 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 02:49:05.307  3428  3542 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s76ms (total +1s486ms)
,08-30 02:49:05.307  3428  3542 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{231a361 u0 com.test.thalitest/.MainActivity t16} time:297947
,08-30 02:49:05.307  3428  3542 D ViewRootImpl: #3 mView = null
08-30 02:49:05.307  3428  4769 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3428
,08-30 02:49:05.307  2990  4349 I SurfaceFlinger: id=19 Removed uhalitest (6/11)
,08-30 02:49:05.317  3428  3428 I KnoxTimeoutHandler: SD activityfalse
08-30 02:49:05.317  9210  9266 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,08-30 02:49:05.317  2990  3002 I SurfaceFlinger: id=19 Removed uhalitest (-2/11)
,08-30 02:49:05.317  2990  2990 D libEGL  : eglTerminate EGLDisplay = 0x7fda761a98
,08-30 02:49:05.327  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:05.327  3428  4767 V WindowStateAnimator: Finishing drawing window Window{2b7adbe u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-30 02:49:05.327  9210  9210 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d21c0cf time:297969
,08-30 02:49:05.357  9210  9210 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9210
,08-30 02:49:05.457  3428  3428 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3428 (0x0)
08-30 02:49:05.457  3428  3428 I libsuspend: !@autosuspend_wakeup_count_disable
08-30 02:49:05.457  3428  3428 D PowerManagerService: mDisplayReady: false
08-30 02:49:05.457  3428  3428 I libsuspend: !@autosuspend_wakeup_count_disable done
08-30 02:49:05.457  3428  3546 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 02:49:05.457  3428  3428 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
08-30 02:49:05.457  3428  3546 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 02:49:05.457  3428  3546 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 02:49:05.457  3428  3546 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 02:49:05.457  3428  3558 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
08-30 02:49:05.467  2990  2990 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7f97b43c00
08-30 02:49:05.467  3428  3542 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
08-30 02:49:05.467  2990  2990 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
08-30 02:49:05.467  3428  3542 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
,08-30 02:49:05.477  3428  3546 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 02:49:05.477  3428  3546 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 02:49:05.477  3428  3546 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 02:49:05.477  3428  3546 I libsuspend: !@autosuspend_wakeup_count_enable
08-30 02:49:05.477  3428  3546 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 02:49:05.477  3428  3546 I libsuspend: !@autosuspend_wakeup_count_enable done
08-30 02:49:05.477  3428  3546 D DisplayPowerController: animateScreenStateChange[0]: target=4
08-30 02:49:05.477  3428  3546 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
08-30 02:49:05.477  3428  3546 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
08-30 02:49:05.477  3428  3546 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
08-30 02:49:05.477  3428  3546 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-30 02:49:05.477  3428  3546 D PowerManagerService: mDisplayReady: true
08-30 02:49:05.477  3428  3546 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-30 02:49:05.507  9210  9210 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-30 02:49:05.507  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:05.607  9210  9273 D jxcore_app_log: JniHelper::setJavaVM(0xf5074000), pthread_self() = -643827408
,08-30 02:49:05.607  9210  9273 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 02:49:05.607  9210  9273 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 02:49:05.607  9210  9273 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 02:49:05.607  9210  9273 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 02:49:05.607  9210  9273 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 02:49:05.607  9210  9273 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6c5d31 added. We now have 1 listener(s)
,08-30 02:49:05.617  9210  9273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,08-30 02:49:05.617  9210  9273 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
08-30 02:49:05.617  9210  9273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 02:49:05.617  9210  9273 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 02:49:05.617  9210  9273 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fff0784 added. We now have 1 listener(s)
08-30 02:49:05.617  9210  9273 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 02:49:05.617  9210  9273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 02:49:05.617  9210  9273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 02:49:05.617  9210  9273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 02:49:05.617  9210  9273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 02:49:05.617  9210  9273 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 02:49:05.617  9210  9273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 02:49:05.617  9210  9273 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,08-30 02:49:05.627  9210  9273 D BluetoothAdapter: STATE_ON
,08-30 02:49:05.627  9210  9273 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 02:49:05.627  9210  9273 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:49:05.627  9210  9273 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:49:05.627  9210  9273 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 02:49:05.627  9210  9273 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:49:05.627  9210  9273 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:49:05.627  9210  9273 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 02:49:05.627  9210  9273 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 02:49:05.627  9210  9273 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 02:49:05.627  9210  9273 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 02:49:05.627  9210  9273 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 02:49:05.627  9210  9273 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 02:49:05.637  9210  9210 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 02:49:05.637  9210  9210 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 02:49:05.657  9210  9210 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 02:49:05.687  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:05.737  4009  4009 D Recents : onTaskStackChanged
,08-30 02:49:05.747  4009  4009 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,08-30 02:49:05.757  4009  4009 D ResourcesManager: For user 0 new overlays fetched Null
,08-30 02:49:05.867  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:06.027  9210  9274 W jxcore-log: Initializing JXcore engine
08-30 02:49:06.027  9210  9274 W jxcore-log: JXcore engine is ready
,08-30 02:49:06.047  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:06.047  4997  4997 E audit   : type=1400 msg=audit(1472518146.047:264): avc:  denied  { ioctl } for  pid=9274 comm="Thread-151" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2229 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 02:49:06.047  4997  4997 E audit   :  SEPF_SECMOBILE_6.0.1_0012
08-30 02:49:06.047  4997  4997 E audit   : type=1300 msg=audit(1472518146.047:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=1 a3=d840a3c8 items=0 ppid=3162 pid=9274 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 tty=(none) ses=4294967295 comm="Thread-151" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 02:49:06.047  4997  4997 E audit   : type=1327 msg=audit(1472518146.047:264): proctitle="com.test.thalitest"
08-30 02:49:06.047  4997  4997 E audit   : type=1320 msg=audit(1472518146.047:264): 
08-30 02:49:06.047  4997  4997 E audit   : type=1400 msg=audit(1472518146.047:265): avc:  denied  { ioctl } for  pid=9274 comm="Thread-151" path="socket:[11202]" dev="sockfs" ino=11202 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-30 02:49:06.047  4997  4997 E audit   :  SEPF_SECMOBILE_6.0.1_0012
08-30 02:49:06.047  4997  4997 E audit   : type=1300 msg=audit(1472518146.047:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=39 a1=5451 a2=1 a3=d840a3c8 items=0 ppid=3162 pid=9274 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 tty=(none) ses=4294967295 comm="Thread-151" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 02:49:06.047  4997  4997 E audit   : type=1327 msg=audit(1472518146.047:265): proctitle="com.test.thalitest"
08-30 02:49:06.047  4997  4997 E audit   : type=1320 msg=audit(1472518146.047:265): 
,08-30 02:49:06.057  9210  9274 W jxcore-log: Starting JXcore engine
,08-30 02:49:06.087  9210  9274 W jxcore-log: Platform android
08-30 02:49:06.087  9210  9274 W jxcore-log: 
08-30 02:49:06.087  9210  9274 W jxcore-log: Process ARCH arm
08-30 02:49:06.087  9210  9274 W jxcore-log: 
,08-30 02:49:06.157  9210  9274 I jxcore-log: JXcore Cordova bridge is ready!
08-30 02:49:06.157  9210  9274 I jxcore-log: 
08-30 02:49:06.157  9210  9274 W jxcore-log: JXcore engine is started
,08-30 02:49:06.167  9210  9273 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 02:49:06.177  9210  9210 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 02:49:06.227  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:06.407  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:06.587  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:06.767  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:06.837  3428  3890 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/16_task.xml.bak
,08-30 02:49:06.947  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:07.127  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:07.307  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:07.487  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:07.667  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:07.847  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:08.027  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:08.207  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:08.387  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:08.557  3428  5787 D SSRM:n  : SIOP:: AP = 320, PST = 289 (W:6), CP = 250, LCD = 1
,08-30 02:49:08.567  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:08.747  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:08.927  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:09.107  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:09.287  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:09.467  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:09.647  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:09.827  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:10.007  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:10.187  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:10.317  3428  5787 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 02:49:10.367  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:10.547  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:10.727  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:10.907  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:11.087  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:11.267  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:11.447  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:11.627  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:11.807  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:11.987  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:12.167  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:12.237  9210  9274 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 02:49:12.237  9210  9274 I jxcore-log: 
,08-30 02:49:12.237  9210  9274 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 02:49:12.237  9210  9274 I jxcore-log: 
,08-30 02:49:12.237  9210  9274 D BluetoothAdapter: STATE_ON
,08-30 02:49:12.247  9210  9274 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:49:12.247  9210  9274 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:49:12.247  9210  9274 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 02:49:12.247  9210  9274 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:49:12.247  9210  9274 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:49:12.247  9210  9274 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 02:49:12.247  9210  9274 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 02:49:12.247  9210  9274 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 02:49:12.247  9210  9274 D BluetoothAdapter: STATE_ON
,08-30 02:49:12.257  9210  9274 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 02:49:12.257  9210  9274 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 02:49:12.257  9210  9274 I jxcore-log: 
08-30 02:49:12.257  9210  9274 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 02:49:12.257  9210  9274 I jxcore-log: 
,08-30 02:49:12.347  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:12.427  9210  9274 I jxcore-log: Running unit tests
08-30 02:49:12.427  9210  9274 I jxcore-log: 
,08-30 02:49:12.427  9210  9274 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 02:49:12.427  9210  9274 I jxcore-log: Failed to execute UT.
08-30 02:49:12.427  9210  9274 I jxcore-log: 
08-30 02:49:12.427  9210  9274 I jxcore-log: Unit Test app is loaded
08-30 02:49:12.427  9210  9274 I jxcore-log: 
,08-30 02:49:12.427  9210  9274 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 02:49:12.427  9210  9274 I jxcore-log: 
,08-30 02:49:12.427  9210  9274 I jxcore-log: My device name is: samsung-SM-G930F
08-30 02:49:12.427  9210  9274 I jxcore-log: 
,08-30 02:49:12.437  9210  9274 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 02:49:12.437  9210  9274 I jxcore-log: 
,08-30 02:49:12.447  9210  9210 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 02:49:12.527  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:12.707  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:12.887  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:13.067  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:13.247  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:13.427  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:13.467  9210  9274 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 02:49:13.467  9210  9274 I jxcore-log: 
,08-30 02:49:13.607  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:13.657  9210  9274 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 02:49:13.657  9210  9274 I jxcore-log: 
,08-30 02:49:13.667  9210  9274 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 02:49:13.667  9210  9274 I jxcore-log: 
,08-30 02:49:13.787  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:13.877  3428  3565 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 02:49:13.897  3428  3565 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 02:49:13.967  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:14.147  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:14.257  9210  9274 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 02:49:14.257  9210  9274 I jxcore-log: 
,08-30 02:49:14.327  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:14.357  9210  9274 I jxcore-log: ERROR runTests: 
08-30 02:49:14.357  9210  9274 I jxcore-log: 
,08-30 02:49:14.357  9210  9274 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 02:49:14.357  9210  9274 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-30 02:49:14.357  9210  9274 I jxcore-log: WARN testUtils: logCallback not set!
08-30 02:49:14.357  9210  9274 I jxcore-log: 
,08-30 02:49:14.357  9210  9274 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _functionName: 'loadFile',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _lineNumber: '26',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _columnNumber: '11',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 02:49:14.357  9210  9274 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _functionName: '',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _lineNumber: '38',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _columnNumber: '7',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 02:49:14.357  9210  9274 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _functionName: '',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _lineNumber: '35',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _columnNumber: '3',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 02:49:14.357  9210  9274 I jxcore-log:   { _fileName: 'module.js',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _lineNumber: '621',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _columnNumber: '8',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 02:49:14.357  9210  9274 I jxcore-log:   { _fileName: 'module.js',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _lineNumber: '651',
08-30 02:49:14.357  9210  9274 I jxcore-log:     _columnNumber: '1',
08-30 02:49:14.357  9210  9274 I jxcore-log:    
,08-30 02:49:14.357  9210  9274 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 02:49:14.357  9210  9274 I jxcore-log: 
08-30 02:49:14.357  9210  9274 E jxcore-log: Error: 
08-30 02:49:14.357  9210  9274 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 02:49:14.357  9210  9274 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 02:49:14.357  9210  9274 E jxcore-log: 
,08-30 02:49:14.507  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:14.567  3428  5825 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 02:49:14.687  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:14.817  9277  9277 I FIPS_bssl: FIPS approved mode (1) | 9277 | app_process
,08-30 02:49:14.817  9277  9277 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 02:49:14.827  9277  9277 D AndroidRuntime: CheckJNI is OFF
08-30 02:49:14.827  9277  9277 D AndroidRuntime: readGMSProperty: start
08-30 02:49:14.827  9277  9277 D AndroidRuntime: readGMSProperty: already setted!!
08-30 02:49:14.827  9277  9277 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 02:49:14.827  9277  9277 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 02:49:14.827  9277  9277 D AndroidRuntime: readGMSProperty: end
08-30 02:49:14.827  9277  9277 D AndroidRuntime: addProductProperty: start
,08-30 02:49:14.847  9277  9277 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 02:49:14.867  9277  9277 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 02:49:14.867  9277  9277 E AffinityControl: AffinityControl: registerfunction enter
08-30 02:49:14.867  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:14.877  9277  9277 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 02:49:14.877  3428  4350 D PackageManager: START PACKAGE DELETE: observer{122374323}
08-30 02:49:14.877  3428  4350 D PackageManager: pkg{<packageName>}
08-30 02:49:14.877  3428  4350 D PackageManager: user{0}
08-30 02:49:14.877  3428  4350 D PackageManager: caller{2000}
08-30 02:49:14.877  3428  4350 D PackageManager: flags{2}
,08-30 02:49:14.877  3428  4350 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-30 02:49:14.877  3428  4350 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 02:49:14.877  3428  4350 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-30 02:49:14.877  3428  4350 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 02:49:14.877  3428  4350 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 02:49:14.877  3428  3565 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 02:49:14.877  3428  3565 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-30 02:49:14.877  3428  3565 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-30 02:49:14.877  3428  3565 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 02:49:14.877  3428  3565 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-30 02:49:14.887  3428  3565 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-30 02:49:14.887  3428  3565 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-30 02:49:14.887  3428  3565 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
08-30 02:49:14.887  3428  3565 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-30 02:49:14.887  3428  3517 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
08-30 02:49:14.887  3428  3565 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-30 02:49:14.887  3428  3517 I ActivityManager: Killing 9210:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-30 02:49:14.887  3428  3517 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-30 02:49:14.897  3428  3517 D ActivityManager: mDVFSHelper.acquire()
,08-30 02:49:14.907  9287  9287 E Zygote  : v2
08-30 02:49:14.907  9287  9287 I libpersona: KNOX_SDCARD checking this for 10170
08-30 02:49:14.907  9287  9287 I libpersona: KNOX_SDCARD not a persona
08-30 02:49:14.917  9287  9287 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0012
08-30 02:49:14.917  3428  3565 D AASAinstall: there is not AASApackages.xml file
08-30 02:49:14.917  9287  9287 E Zygote  : accessInfo : 0
,08-30 02:49:14.917  9287  9287 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-30 02:49:14.917  3428  3517 I ActivityManager: Start proc 9287:com.test.thalitest/u0a170 for activity com.test.thalitest/.MainActivity
,08-30 02:49:14.927  3428  3517 I ActivityManager:   Force finishing activity ActivityRecord{231a361 u0 com.test.thalitest/.MainActivity t16}
08-30 02:49:14.927  3428  3517 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,08-30 02:49:14.927  9287  9287 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:49:14.927  9287  9287 D ActivityThread: Added TimaKeyStore provider
,08-30 02:49:14.967  3137  3725 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,08-30 02:49:15.017  3428  3765 D GraphicsStats: Buffer count: 7
08-30 02:49:15.017  3428  3965 I WindowState: WIN DEATH: Window{2b7adbe u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 02:49:15.017  3428  3454 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1ad1b2b)
08-30 02:49:15.017  3428  3852 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 02:49:15.017  3428  3852 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 02:49:15.027  3428  3852 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 02:49:15.027  2990  3000 I SurfaceFlinger: id=20 Removed NainActivit (6/10)
08-30 02:49:15.027  2990  4535 I SurfaceFlinger: id=20 Removed NainActivit (-2/10)
,08-30 02:49:15.027  2990  4349 I SurfaceFlinger: id=20 Removed NainActivit (-2/10)
,08-30 02:49:15.047  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:15.127  3428  3565 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-30 02:49:15.177  3428  3565 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
08-30 02:49:15.187  3428  3542 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 02:49:15.187  3428  3542 D SecWifiDisplayUtil: Metadata value : SecSettings2
08-30 02:49:15.187  3428  3542 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-30 02:49:15.187  3428  3542 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
08-30 02:49:15.187  3428  3542 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
08-30 02:49:15.187  3428  3542 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
08-30 02:49:15.187  3428  3542 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-30 02:49:15.187  3428  3542 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:49:15.187  3428  3542 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-30 02:49:15.187  3428  3542 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:49:15.187  3428  3542 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 02:49:15.187  3428  3542 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{33ddb88 V.E...... R.....ID 0,0-0,0}
08-30 02:49:15.187  3150  3150 W keystore: ENTER clear_uid from uid 1000 for 10170
08-30 02:49:15.187  3428  3565 I art     : Starting a blocking GC Explicit
,08-30 02:49:15.197  3428  3542 W WindowManager: Failed looking up window
08-30 02:49:15.197  3428  3542 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@d6a1921 does not exist
08-30 02:49:15.197  3428  3542 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:49:15.197  3428  3542 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 02:49:15.197  3428  3542 D ISSUE_DEBUG: InputChannelName : a5af146 Starting com.test.thalitest
,08-30 02:49:15.207  2990  2990 I SurfaceFlinger: id=21 createSurf (1528x2641),1 flag=4, VSBConnecti
,08-30 02:49:15.217  5879  8622 D mali_winsys: new_window_surface returns 0x3000,  [1528x2641]-format:1
,08-30 02:49:15.227  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:15.227  5879  5879 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 02:49:15.227  5879  5879 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-30 02:49:15.237  4278  4278 D Launcher: onRestart, Launcher: 209068983
,08-30 02:49:15.357  3428  3565 I art     : Explicit concurrent mark sweep GC freed 193851(10MB) AllocSpace objects, 10(2040KB) LOS objects, 32% free, 32MB/48MB, paused 1.440ms total 165.428ms
,08-30 02:49:15.387  3428  3565 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-30 02:49:15.387  3428  3565 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,08-30 02:49:15.397  3428  3565 D AASAinstall: there is not AASApackages.xml file
08-30 02:49:15.397  3428  3565 D PackageManager: result of delete: 1{122374323}
,08-30 02:49:15.397  3428  3565 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 02:49:15.397  3428  3565 D PackageManager: userId{-1}
08-30 02:49:15.397  3428  3565 D PackageManager: andCode{true}
08-30 02:49:15.397  9277  9277 I art     : System.exit called, status: 0
08-30 02:49:15.397  9277  9277 I AndroidRuntime: VM exiting with result code 0.
,08-30 02:49:15.407  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,08-30 02:49:15.527  3428  3517 I WindowManager: Screenshot max retries 4 of Token{4a12b54 ActivityRecord{a87daa7 u0 com.samsung.android.MtpApplication/.USBConnection t15}} appWin=Window{fb24616 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=1
,08-30 02:49:15.527  3428  3428 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,08-30 02:49:15.537  3428  3517 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-30 02:49:15.537  4278  4278 D Launcher: onStart, Launcher: 209068983
08-30 02:49:15.537  4278  4278 D Launcher.HomeView: onStart
,08-30 02:49:15.537  4278  4278 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,08-30 02:49:15.547  4278  4278 V ActivityThread: updateVisibility : ActivityRecord{5f6d876 token=android.os.BinderProxy@920cc42 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,08-30 02:49:15.547  4278  4278 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
08-30 02:49:15.547  4278  4278 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
08-30 02:49:15.547  4278  4278 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
,08-30 02:49:15.547  4278  4278 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
08-30 02:49:15.547  4278  4278 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
08-30 02:49:15.547  4278  4278 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
,08-30 02:49:15.557  4278  4278 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
08-30 02:49:15.557  4278  4278 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
08-30 02:49:15.557  4278  4278 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
,08-30 02:49:15.557  9305  9305 E Zygote  : v2
08-30 02:49:15.557  9305  9305 I libpersona: KNOX_SDCARD checking this for 10008
08-30 02:49:15.557  9305  9305 I libpersona: KNOX_SDCARD not a persona
08-30 02:49:15.557  9305  9305 E libpersona: scanKnoxPersonas
,08-30 02:49:15.557  9305  9305 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
,08-30 02:49:15.557  3428  3565 I ActivityManager: Start proc 9305:com.android.defcontainer/u0a8 for service com.android.defcontainer/.DefaultContainerService
08-30 02:49:15.557  9305  9305 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0012
08-30 02:49:15.557  9305  9305 E Zygote  : accessInfo : 0
08-30 02:49:15.557  9305  9305 E libpersona: scanKnoxPersonas
08-30 02:49:15.557  9305  9305 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
,08-30 02:49:15.567  3428  4589 I ActivityManager: Killing 8734:com.google.android.partnersetup/u0a23 (adj 15): DHA:empty #33
,08-30 02:49:15.577  3428  3517 D InputDispatcher: Focused application released
,08-30 02:49:15.577  2990  2990 I SurfaceFlinger: id=22 createSurf (1440x2560),1 flag=4, MauncherAct
,08-30 02:49:15.587  3428  4590 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-30 02:49:15.587  3428  4590 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 02:49:15.587  3428  3428 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-30 02:49:15.587  9287  9287 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
08-30 02:49:15.587  3428  3781 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
08-30 02:49:15.587  3428  3565 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-30 02:49:15.587  3428  3565 I ActivityManager: Killing 9287:com.test.thalitest/u0a170 (adj 9): stop com.test.thalitest cause pkg removed
,08-30 02:49:15.587  5879  5879 D ViewRootImpl: Ignore stableInsets changed, SI=[0,0][0,0] PSI=[0,41][0,0]
,08-30 02:49:15.597  3428  3428 I KnoxTimeoutHandler: Shared devices show user statefalse
08-30 02:49:15.597  3428  3428 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-30 02:49:15.597  3428  3542 W WindowManager: Failed looking up window
08-30 02:49:15.597  3428  3542 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@d6a1921 does not exist
08-30 02:49:15.597  3428  3542 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14795)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at com.android.server.wm.WindowManagerService.relayoutWindow(WindowManagerService.java:5208)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at com.android.server.wm.Session.relayout(Session.java:208)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.view.ViewRootImpl.relayoutWindow(ViewRootImpl.java:6690)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1994)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1437)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:7403)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:920)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.view.Choreographer.doCallbacks(Choreographer.java:695)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.view.Choreographer.doFrame(Choreographer.java:631)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:906)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 02:49:15.597  3428  3542 E ViewSystem: ViewRootImpl #2 Surface is not valid.
08-30 02:49:15.597  3428  3542 D ViewRootImpl: #3 mView = null
,08-30 02:49:15.597  3428  3542 W WindowManager: Failed looking up window
08-30 02:49:15.597  3428  3542 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@d6a1921 does not exist
08-30 02:49:15.597  3428  3542 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14795)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:4612)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:196)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3754)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:6893)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:4238)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:49:15.597  3428  3542 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 02:49:15.597  4278  4596 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
08-30 02:49:15.607  9305  9305 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:49:15.607  9305  9305 D ActivityThread: Added TimaKeyStore provider
08-30 02:49:15.617  3428  3565 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
08-30 02:49:15.617  3428  4766 V WindowStateAnimator: Finishing drawing window Window{fb24616 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-30 02:49:15.617  2990  2990 I SurfaceFlinger: id=23 createSurf (1592x384),1 flag=4, VSBConnecti

```
