#### Test 8504691198a5312_thali05_samsung-SM-G930F Logs


```
--------- beginning of system
09-26 09:01:12.651  3398  5983 D SSRM:n  : SIOP:: AP = 250, PST = 252 (W:14), CP = 211, CUR = 140, LCD = 1
,--------- beginning of main
09-26 09:01:13.661  9457  9457 I FIPS_bssl: FIPS approved mode (1) | 9457 | app_process
09-26 09:01:13.661  9457  9457 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-26 09:01:13.671  9457  9457 D AndroidRuntime: CheckJNI is OFF
09-26 09:01:13.671  9457  9457 D AndroidRuntime: readGMSProperty: start
09-26 09:01:13.671  9457  9457 D AndroidRuntime: readGMSProperty: already setted!!
09-26 09:01:13.671  9457  9457 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-26 09:01:13.671  9457  9457 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-26 09:01:13.671  9457  9457 D AndroidRuntime: readGMSProperty: end
09-26 09:01:13.671  9457  9457 D AndroidRuntime: addProductProperty: start
09-26 09:01:13.691  9457  9457 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-26 09:01:13.711  9457  9457 I Radio-JNI: register_android_hardware_Radio DONE
09-26 09:01:13.711  9457  9457 E AffinityControl: AffinityControl: registerfunction enter
09-26 09:01:13.721  9457  9457 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-26 09:01:13.751  3398  3992 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
09-26 09:01:13.751  3398  3992 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-26 09:01:13.771  3398  3992 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:13.771  3398  3992 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 09:01:13.771  3398  3992 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-26 09:01:13.781  3398  3992 D ActivityManager: mDVFSHelper.acquire()
09-26 09:01:13.781  3398  3992 V WindowManager: addAppToken: AppWindowToken{d05a32e3b token=Token{3ec0cca ActivityRecord{2502035 u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-26 09:01:13.781  3398  3552 I InjectionManager: Inside getClassLibPath caller 
09-26 09:01:13.791  3398  3552 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-26 09:01:13.791  3398  3552 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a5b29b3 V.E...... R.....ID 0,0-0,0}
09-26 09:01:13.801  9466  9466 E Zygote  : v2
09-26 09:01:13.801  9466  9466 I libpersona: KNOX_SDCARD checking this for 10171
09-26 09:01:13.801  9466  9466 I libpersona: KNOX_SDCARD not a persona
09-26 09:01:13.801  9466  9466 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-26 09:01:13.801  3398  3552 W WindowManager: Failed looking up window
09-26 09:01:13.801  3398  3552 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@2f77b70 does not exist
09-26 09:01:13.801  3398  3552 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 09:01:13.801  3398  3552 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-26 09:01:13.801  3398  3552 D ISSUE_DEBUG: InputChannelName : 39bdee9 Starting com.test.thalitest
09-26 09:01:13.801  9466  9466 E Zygote  : accessInfo : 0
09-26 09:01:13.801  9466  9466 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-26 09:01:13.801  3398  3992 I ActivityManager: Start proc 9466:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-26 09:01:13.801  3398  3992 D InputDispatcher: Focused application set to: xxxx
09-26 09:01:13.811  9457  9457 D AndroidRuntime: Shutting down VM
09-26 09:01:13.811  3398  3853 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-26 09:01:13.811  3004  3004 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
09-26 09:01:13.831  9466  9466 D TimaKeyStoreProvider: TimaSignature is unavailable
09-26 09:01:13.831  9466  9466 D ActivityThread: Added TimaKeyStore provider
09-26 09:01:13.841  6073  6073 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-26 09:01:13.851  3398  4293 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3398
09-26 09:01:13.851  3398  4293 I libsuspend: !@autosuspend_wakeup_count_disable
09-26 09:01:13.851  3398  4293 D PowerManagerService: mDisplayReady: false
09-26 09:01:13.851  3398  4293 I libsuspend: !@autosuspend_wakeup_count_disable done
09-26 09:01:13.851  3398  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 09:01:13.851  3398  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 09:01:13.851  6073  6073 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-26 09:01:13.851  3398  4293 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-26 09:01:13.851  3398  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:13.851  3004  3004 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fac403c00
09-26 09:01:13.851  3398  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:13.851  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-26 09:01:13.851  3398  3567 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-26 09:01:13.851  3398  4768 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3398
09-26 09:01:13.851  3398  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 09:01:13.851  3398  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-26 09:01:13.851  3398  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 09:01:13.851  3398  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
09-26 09:01:13.851  3398  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:13.851  3398  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:13.851  3398  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 09:01:13.851  3398  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 09:01:13.851  3398  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:13.851  3398  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:13.851  3398  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-26 09:01:13.851  3398  3556 D PowerManagerService: mDisplayReady: true
09-26 09:01:13.851  3398  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-26 09:01:13.861  3398  3452 D ActivityManager:  Launching com.test.thalitest, updated priority
09-26 09:01:13.861  4281  4281 V ActivityThread: updateVisibility : ActivityRecord{f8253b8 token=android.os.BinderProxy@2b00712 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-26 09:01:13.871  3398  3975 V WindowStateAnimator: Finishing drawing window Window{90b5b33 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-26 09:01:13.881  3398  3517 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-26 09:01:13.881  3398  3398 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-26 09:01:13.881  3004  4306 D libEGL  : eglTerminate EGLDisplay = 0x7fa43fee78
09-26 09:01:13.891  3004  4306 D libEGL  : eglTerminate EGLDisplay = 0x7fa43fee78
09-26 09:01:13.901  3151  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-26 09:01:13.901  3004  3015 I SurfaceFlinger: id=10 Removed MauncherAct (4/13)
09-26 09:01:13.901  3004  4306 I SurfaceFlinger: id=10 Removed MauncherAct (-2/13)
09-26 09:01:13.911  4281  4281 D Launcher: onTrimMemory. Level: 20
09-26 09:01:13.911  3398  4371 V WindowStateAnimator: Finishing drawing window Window{6a966d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-26 09:01:13.911  6073  6073 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-26 09:01:13.911  6073  6073 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-26 09:01:13.911  6073  6073 V ActivityThread: updateVisibility : ActivityRecord{b9a0356 token=android.os.BinderProxy@489fd6b {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-26 09:01:13.911  3004  3004 D libEGL  : eglTerminate EGLDisplay = 0x7fed75b1a8
09-26 09:01:13.921  3004  4306 I SurfaceFlinger: id=16 Removed VSBConnecti (7/12)
09-26 09:01:13.921  3004  4329 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/12)
09-26 09:01:13.921  3004  3013 D libEGL  : eglTerminate EGLDisplay = 0x7fac180e78
09-26 09:01:13.921  3004  4329 I SurfaceFlinger: id=17 Removed VSBConnecti (5/11)
09-26 09:01:13.921  3004  4209 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
09-26 09:01:13.931  3004  3004 D libEGL  : eglTerminate EGLDisplay = 0x7fed75b1a8
09-26 09:01:13.931  3004  3004 D libEGL  : eglTerminate EGLDisplay = 0x7fed75b178
09-26 09:01:14.001  3398  3398 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3398 (0x0)
09-26 09:01:14.001  3398  3398 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3398 (0x0)
09-26 09:01:14.001  3398  3398 I libsuspend: !@autosuspend_wakeup_count_disable
09-26 09:01:14.001  3398  3398 D PowerManagerService: mDisplayReady: false
09-26 09:01:14.001  3398  3398 I libsuspend: !@autosuspend_wakeup_count_disable done
09-26 09:01:14.001  3398  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 09:01:14.001  3398  3398 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-26 09:01:14.001  3398  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 09:01:14.001  3398  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:14.001  3398  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:14.001  3398  3567 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-26 09:01:14.001  3004  3004 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fac403c00
09-26 09:01:14.001  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-26 09:01:14.011  3398  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 09:01:14.011  3398  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 09:01:14.011  3398  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-26 09:01:14.011  3398  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:14.011  3398  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
09-26 09:01:14.011  3398  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:14.011  3398  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 09:01:14.011  3398  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 09:01:14.011  3398  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:14.011  3398  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:14.011  3398  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-26 09:01:14.011  3398  3556 D PowerManagerService: mDisplayReady: true
09-26 09:01:14.011  3398  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-26 09:01:14.201  3398  3452 I WindowManager: Screenshot max retries 4 of Token{3ec0cca ActivityRecord{2502035 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{39bdee9 u0 d0 Starting com.test.thalitest} drawState=1
,09-26 09:01:14.201  3398  3552 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-26 09:01:14.201  3398  3552 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-26 09:01:14.211  3398  3398 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-26 09:01:14.211  3398  5983 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 09:01:14.221  3398  3398 I KnoxTimeoutHandler: SD activityfalse
,09-26 09:01:14.211  3398  5983 D GameManagerService: identifyGamePackage. com.test.thalitest
09-26 09:01:14.221  3398  3853 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,09-26 09:01:14.241  9466  9466 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,09-26 09:01:14.251  3398  3552 V WindowStateAnimator: Finishing drawing window Window{39bdee9 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-26 09:01:14.251  3398  5983 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-26 09:01:14.251  3398  3552 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-26 09:01:14.251  3398  3398 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 09:01:14.251  3398  4004 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-26 09:01:14.251  3398  3552 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1cc289f u0 com.samsung.android.MtpApplication/.USBConnection t3} time:213402
09-26 09:01:14.251  3398  3552 D ActivityManager: mDVFSHelper.release()
09-26 09:01:14.251  9466  9466 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-26 09:01:14.251  3398  3398 I KnoxTimeoutHandler: SD activityfalse
,09-26 09:01:14.251  3004  3004 D libEGL  : eglInitialize EGLDisplay = 0x7fed75b088,
,09-26 09:01:14.261  3398  5983 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-26 09:01:14.261  3398  5983 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-26 09:01:14.261  9466  9466 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:14.261  3398  5983 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-26 09:01:14.261  3398  5983 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-26 09:01:14.271  9466  9466 I InjectionManager: Inside getClassLibPath caller 
,09-26 09:01:14.291  9466  9466 D InjectionManager: InjectionManager
09-26 09:01:14.291  9466  9466 D InjectionManager: fillFeatureStoreMap com.test.thalitest
,09-26 09:01:14.291  9466  9466 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-26 09:01:14.291  9466  9466 I InjectionManager: featureStore :{}
,09-26 09:01:14.301  9466  9466 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,09-26 09:01:14.301  9466  9466 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-26 09:01:14.301  9466  9466 D RelationGraph: garbageCollect()
,09-26 09:01:14.301  9466  9466 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,09-26 09:01:14.311  3398  4004 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-26 09:01:14.311  3398  4004 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-26 09:01:14.311  3398  4004 D BatteryService: online:4, current avg:7, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
09-26 09:01:14.311  3398  4004 D BatteryService: stay LED for fully charged
09-26 09:01:14.311  3398  3398 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-26 09:01:14.311  3398  3398 I MotionRecognitionService: Plugged
09-26 09:01:14.311  3398  3398 D MotionRecognitionService:   cableConnection= 1
09-26 09:01:14.311  3398  3398 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-26 09:01:14.311  3398  3398 D MotionRecognitionService: skip setTransmitPower. 
09-26 09:01:14.311  3398  3858 D WifiController: ApOrStaEnabledState  msg.what= 155652
09-26 09:01:14.311  3930  3930 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-26 09:01:14.311  3930  3930 D KeyguardUpdateMonitor: handleBatteryUpdate
09-26 09:01:14.311  3930  3930 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-26 09:01:14.321  5053  5053 D CommonServiceConfiguration: getStringValueSetting
,09-26 09:01:14.321  5015  5015 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-26 09:01:14.321  5015  5427 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-26 09:01:14.321  4674  4674 D BatteryController: saveBatteryData : level[100], status[5]
,09-26 09:01:14.321  5053  5053 D BatteryMonitor: new battery level: 100
,09-26 09:01:14.341  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-26 09:01:14.341  3930  3930 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-26 09:01:14.341  9466  9466 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
,09-26 09:01:14.371  9466  9466 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
,09-26 09:01:14.381  9466  9466 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:14.381  9466  9466 I InjectionManager: Inside getClassLibPath caller 
,09-26 09:01:14.381  9466  9466 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-26 09:01:14.431  9466  9466 I cr_LibraryLoader: Time to load native libraries: 34 ms (timestamps 3551-3585)
,09-26 09:01:14.431  9466  9466 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-26 09:01:14.471  3398  3878 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,09-26 09:01:14.501  9466  9483 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,09-26 09:01:14.531  9466  9466 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9b01e16}
09-26 09:01:14.531  9466  9466 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-26 09:01:14.551  9466  9466 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,09-26 09:01:14.571  3398  3878 I MdnieScenarioControlService: mGameModeLauncher : false
09-26 09:01:14.571  3398  3878 I MdnieScenarioControlService: setUIMode
,09-26 09:01:14.591  9466  9466 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,09-26 09:01:14.701  3398  3517 W ActivityManager: Activity pause timeout for ActivityRecord{2502035 u0 com.test.thalitest/.MainActivity t4}
,09-26 09:01:14.781  9466  9466 D libEGL  : eglInitialize EGLDisplay = 0xff85a69c
,09-26 09:01:14.871  3398  4266 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
,09-26 09:01:14.871  3398  4266 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-26 09:01:14.951  9466  9466 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-26 09:01:14.971  9466  9466 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-26 09:01:14.971  9466  9466 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-26 09:01:14.991  9466  9466 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-26 09:01:15.091  9466  9466 D Activity: performCreate Call Injection manager
,09-26 09:01:15.101  9466  9466 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-26 09:01:15.111  9466  9466 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-26 09:01:15.131  9466  9466 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b984e4d I.E...... R.....ID 0,0-0,0}
,09-26 09:01:15.141  9466  9520 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-26 09:01:15.161  3398  4985 W WindowManager: Failed looking up window
09-26 09:01:15.161  3398  4985 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@6a571d0 does not exist
09-26 09:01:15.161  3398  4985 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-26 09:01:15.161  3398  4985 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-26 09:01:15.161  3398  4985 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-26 09:01:15.161  3398  4985 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-26 09:01:15.161  3398  4985 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-26 09:01:15.161  3398  4985 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-26 09:01:15.161  3398  4004 D ISSUE_DEBUG: InputChannelName : 3ff05c9 com.test.thalitest/com.test.thalitest.MainActivity
,09-26 09:01:15.171  3398  3453 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-26 09:01:15.171  3398  3453 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-26 09:01:15.171  3398  3398 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-26 09:01:15.171  3398  3398 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-26 09:01:15.181  9466  9466 V ActivityThread: updateVisibility : ActivityRecord{b288613 token=android.os.BinderProxy@e9684b5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-26 09:01:15.191  9466  9483 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-26 09:01:15.211  3398  5985 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,09-26 09:01:15.221  9466  9466 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9466
,09-26 09:01:15.231  3398  3453 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9466 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-26 09:01:15.231  3398  3864 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-26 09:01:15.231  3398  3864 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 09:01:15.241  3398  3864 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,09-26 09:01:15.241  3398  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-26 09:01:15.251  3398  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-26 09:01:15.251  9466  9466 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-26 09:01:15.261  3398  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,09-26 09:01:15.271  3398  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-26 09:01:15.271  3398  3864 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,09-26 09:01:15.271  3398  3864 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-26 09:01:15.271  3004  3004 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,09-26 09:01:15.291  9466  9520 D libEGL  : eglInitialize EGLDisplay = 0xdc53f7c4
,09-26 09:01:15.291  9466  9520 I OpenGLRenderer: Initialized EGL, version 1.4
,09-26 09:01:15.301  9466  9520 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-26 09:01:15.301  3398  4266 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3398
,09-26 09:01:15.301  3398  4266 I libsuspend: !@autosuspend_wakeup_count_disable
09-26 09:01:15.301  3398  4266 D PowerManagerService: mDisplayReady: false
09-26 09:01:15.301  3398  4266 I libsuspend: !@autosuspend_wakeup_count_disable done
09-26 09:01:15.301  3398  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-26 09:01:15.301  3398  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
,09-26 09:01:15.301  3004  3004 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fac403c00
09-26 09:01:15.301  3398  4266 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-26 09:01:15.301  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-26 09:01:15.301  3398  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
,09-26 09:01:15.301  3398  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:15.301  3398  3567 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-26 09:01:15.301  3398  3552 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-26 09:01:15.311  3398  3552 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
,09-26 09:01:15.331  3398  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-26 09:01:15.331  3398  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 09:01:15.331  3398  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-26 09:01:15.331  3398  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:15.331  3398  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
,09-26 09:01:15.331  3398  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:15.331  3398  3556 D DisplayPowerController: animateScreenStateChange[0]: target=3
,09-26 09:01:15.331  3398  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-26 09:01:15.331  3398  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:15.331  3398  3556 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:15.331  3398  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,09-26 09:01:15.331  3398  3556 D PowerManagerService: mDisplayReady: true
09-26 09:01:15.331  3398  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-26 09:01:15.341  9466  9466 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-26 09:01:15.361  3398  4550 V WindowStateAnimator: Finishing drawing window Window{3ff05c9 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-26 09:01:15.361  9466  9466 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-26 09:01:15.361  9466  9524 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-26 09:01:15.361  9466  9524 D libEGL  : eglInitialize EGLDisplay = 0xda96d3f4
,09-26 09:01:15.371  3398  4985 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3398
,09-26 09:01:15.371  3398  3552 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-26 09:01:15.371  3398  3398 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-26 09:01:15.371  3398  3552 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s170ms (total +1s587ms)
09-26 09:01:15.371  3398  3552 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2502035 u0 com.test.thalitest/.MainActivity t4} time:214522
,09-26 09:01:15.371  3398  3398 I KnoxTimeoutHandler: SD activityfalse
,09-26 09:01:15.371  3398  3453 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3398
,09-26 09:01:15.371  3398  3552 D ViewRootImpl: #3 mView = null
,09-26 09:01:15.371  3004  3013 I SurfaceFlinger: id=18 Removed uhalitest (6/11)
,09-26 09:01:15.371  3004  3013 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,09-26 09:01:15.381  3398  4279 V WindowStateAnimator: Finishing drawing window Window{3ff05c9 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-26 09:01:15.381  9466  9524 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-26 09:01:15.381  9466  9466 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e9684b5 time:214533
,09-26 09:01:15.401  3004  3004 D libEGL  : eglTerminate EGLDisplay = 0x7fed75b1a8
,09-26 09:01:15.421  9466  9466 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9466
,09-26 09:01:15.521  3398  3398 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3398 (0x0)
09-26 09:01:15.521  3398  3398 I libsuspend: !@autosuspend_wakeup_count_disable
09-26 09:01:15.521  3398  3398 D PowerManagerService: mDisplayReady: false
09-26 09:01:15.521  3398  3398 I libsuspend: !@autosuspend_wakeup_count_disable done
09-26 09:01:15.521  3398  3398 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-26 09:01:15.521  3398  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 09:01:15.521  3398  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 09:01:15.521  3398  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:15.521  3398  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:15.521  3398  3567 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
,09-26 09:01:15.521  3398  3552 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-26 09:01:15.521  3004  3004 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fac403c00
09-26 09:01:15.521  3398  3552 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-26 09:01:15.521  3004  3004 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
,09-26 09:01:15.541  3398  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 09:01:15.541  3398  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
,09-26 09:01:15.541  3398  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:15.541  3398  3556 I libsuspend: !@autosuspend_wakeup_count_enable
09-26 09:01:15.541  3398  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:15.541  3398  3556 I libsuspend: !@autosuspend_wakeup_count_enable done
,09-26 09:01:15.541  3398  3556 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-26 09:01:15.541  3398  3556 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-26 09:01:15.541  3398  3556 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-26 09:01:15.541  3398  3556 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-26 09:01:15.541  3398  3556 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-26 09:01:15.541  3398  3556 D PowerManagerService: mDisplayReady: true
,09-26 09:01:15.541  3398  3556 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-26 09:01:15.541  9466  9466 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-26 09:01:15.701  4026  4026 D Recents : onTaskStackChanged
,09-26 09:01:15.701  4026  4026 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,09-26 09:01:15.711  4026  4026 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:15.751  9466  9531 D jxcore_app_log: JniHelper::setJavaVM(0xf4c74000), pthread_self() = -635803344
,09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6664bd added. We now have 1 listener(s)
,09-26 09:01:15.761  9466  9531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-26 09:01:15.761  9466  9531 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-26 09:01:15.761  9466  9531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-26 09:01:15.761  9466  9531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-26 09:01:15.761  9466  9531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dad2d80 added. We now have 1 listener(s)
09-26 09:01:15.761  9466  9531 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 09:01:15.771  9466  9531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 09:01:15.771  9466  9531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-26 09:01:15.771  9466  9531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-26 09:01:15.771  9466  9531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-26 09:01:15.771  9466  9531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-26 09:01:15.771  9466  9531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 09:01:15.771  9466  9531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,09-26 09:01:15.781  9466  9531 D BluetoothAdapter: STATE_ON
,09-26 09:01:15.781  9466  9531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-26 09:01:15.781  9466  9531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 09:01:15.781  9466  9531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 09:01:15.781  9466  9531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 09:01:15.781  9466  9531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 09:01:15.781  9466  9531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 09:01:15.781  9466  9531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 09:01:15.781  9466  9531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 09:01:15.781  9466  9531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 09:01:15.781  9466  9531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-26 09:01:15.781  9466  9531 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 09:01:15.781  9466  9531 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-26 09:01:15.791  9466  9466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 09:01:15.791  9466  9466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 09:01:15.811  9466  9466 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-26 09:01:16.111  9466  9532 W jxcore-log: Initializing JXcore engine
09-26 09:01:16.111  9466  9532 W jxcore-log: JXcore engine is ready
,09-26 09:01:16.131  5021  5021 E audit   : type=1400 msg=audit(1474873276.131:264): avc:  denied  { ioctl } for  pid=9532 comm="Thread-156" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1201 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-26 09:01:16.131  5021  5021 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-26 09:01:16.131  5021  5021 E audit   : type=1300 msg=audit(1474873276.131:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=da0a13c8 items=0 ppid=3176 pid=9532 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-156" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-26 09:01:16.131  5021  5021 E audit   : type=1327 msg=audit(1474873276.131:264): proctitle="com.test.thalitest"
09-26 09:01:16.131  5021  5021 E audit   : type=1320 msg=audit(1474873276.131:264): 
09-26 09:01:16.131  5021  5021 E audit   : type=1400 msg=audit(1474873276.131:265): avc:  denied  { ioctl } for  pid=9532 comm="Thread-156" path="socket:[38084]" dev="sockfs" ino=38084 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-26 09:01:16.131  5021  5021 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-26 09:01:16.131  5021  5021 E audit   : type=1300 msg=audit(1474873276.131:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=da0a13c8 items=0 ppid=3176 pid=9532 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 tty=(none) ses=4294967295 comm="Thread-156" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-26 09:01:16.131  5021  5021 E audit   : type=1327 msg=audit(1474873276.131:265): proctitle="com.test.thalitest"
09-26 09:01:16.131  5021  5021 E audit   : type=1320 msg=audit(1474873276.131:265): 
,09-26 09:01:16.131  9466  9532 W jxcore-log: Starting JXcore engine
,09-26 09:01:16.171  9466  9532 W jxcore-log: Platform android
09-26 09:01:16.171  9466  9532 W jxcore-log: 
09-26 09:01:16.171  9466  9532 W jxcore-log: Process ARCH arm
09-26 09:01:16.171  9466  9532 W jxcore-log: 
,09-26 09:01:16.241  9466  9532 I jxcore-log: JXcore Cordova bridge is ready!
09-26 09:01:16.241  9466  9532 I jxcore-log: 
09-26 09:01:16.241  9466  9532 W jxcore-log: JXcore engine is started
,09-26 09:01:16.251  9466  9531 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-26 09:01:16.251  9466  9466 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-26 09:01:16.791  3398  3902 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/4_task.xml.bak
,09-26 09:01:17.221  3398  5983 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-26 09:01:20.281  3398  5983 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-26 09:01:20.501  9466  9532 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-26 09:01:20.501  9466  9532 I jxcore-log: 
,09-26 09:01:20.501  9466  9532 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-26 09:01:20.501  9466  9532 I jxcore-log: 
,09-26 09:01:20.511  9466  9532 D BluetoothAdapter: STATE_ON
,09-26 09:01:20.511  9466  9532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 09:01:20.511  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 09:01:20.511  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 09:01:20.511  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 09:01:20.511  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 09:01:20.511  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 09:01:20.511  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 09:01:20.511  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 09:01:20.521  9466  9532 D BluetoothAdapter: STATE_ON
,09-26 09:01:20.521  9466  9532 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 09:01:20.521  9466  9532 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-26 09:01:20.521  9466  9532 I jxcore-log: 
09-26 09:01:20.521  9466  9532 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-26 09:01:20.521  9466  9532 I jxcore-log: 
,09-26 09:01:20.751  9466  9532 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 09:01:20.751  9466  9532 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1eed77 added. We now have 2 listener(s)
09-26 09:01:20.751  9466  9532 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-26 09:01:20.751  9466  9532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 09:01:20.751  9466  9532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-26 09:01:20.751  9466  9532 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 09:01:20.751  9466  9532 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f8de4 added. We now have 2 listener(s)
09-26 09:01:20.751  9466  9532 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 09:01:20.751  9466  9532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 09:01:20.761  9466  9532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 09:01:20.771  9466  9532 D BluetoothAdapter: STATE_ON
,09-26 09:01:20.771  9466  9532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 09:01:20.771  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 09:01:20.771  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 09:01:20.771  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 09:01:20.771  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 09:01:20.771  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 09:01:20.771  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 09:01:20.771  9466  9532 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 09:01:20.771  9466  9532 D BluetoothAdapter: STATE_ON
,09-26 09:01:20.781  9466  9532 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 09:01:20.781  9466  9532 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 09:01:20.781  9466  9532 D ExecuteNativeTests: Running unit tests
09-26 09:01:20.781  9466  9532 D BluetoothAdapter: enable()
,09-26 09:01:20.781  9466  9466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 09:01:20.781  9466  9532 D BluetoothAdapter: enable(): BT is already enabled..!
,09-26 09:01:20.791  9466  9466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 09:01:20.801  3398  3517 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fd7f339 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c3b8959 5037:com.samsung.android.providers.context/u0a7}
,09-26 09:01:20.801  9466  9532 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-26 09:01:20.801  3398  3453 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-26 09:01:20.811  3398  3453 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-26 09:01:20.811  3398  3453 D WifiService: setWifiEnabled: true pid=9466, uid=10171
,09-26 09:01:20.811  3398  3453 W ActivityManager: Permission Denial: getCurrentUser() from pid=9466, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-26 09:01:20.821  3398  3855 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-26 09:01:20.821  3398  3453 W WifiService: Failed getting userId using ActivityManagerNative
09-26 09:01:20.821  3398  3453 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9466, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-26 09:01:20.821  3398  3453 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28247)
09-26 09:01:20.821  3398  3453 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
09-26 09:01:20.821  3398  3453 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
09-26 09:01:20.821  3398  3453 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-26 09:01:20.821  3398  3453 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,09-26 09:01:20.821  3398  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
09-26 09:01:20.821  3398  3453 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
09-26 09:01:20.821  3398  3453 D SettingsProvider: isChangeAllowed() : name = wifi_on
09-26 09:01:20.821  3398  3855 D WifiBigDataLog: init : 
,09-26 09:01:20.821  3398  3858 D WifiController: [FCC]setFccChannel() is called !!!
09-26 09:01:20.821  3398  3858 D WifiStateMachine: setFccChannel: channel = 0
09-26 09:01:20.821  3398  3858 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,09-26 09:01:20.821  3398  3855 D WifiStateMachine: setFccChannelNative: channel = 0
,09-26 09:01:20.821  3398  3855 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-26 09:01:20.831  3398  3517 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2241d7e u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c3b8959 5037:com.samsung.android.providers.context/u0a7}
,09-26 09:01:22.681  3398  5983 D SSRM:n  : SIOP:: AP = 300, PST = 255 (W:6), CP = 218, CUR = 7, LCD = 1
,09-26 09:01:23.831  3398  3573 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-26 09:01:23.861  3398  3573 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-26 09:01:24.021  3398  4128 E Watchdog: !@Sync 7 [09-26 09:01:24.031]
,09-26 09:01:29.601  3398  6018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-26 09:01:30.821  9466  9532 I com.test.thalitest.ThaliTestRunner: Running UT
,09-26 09:01:30.851  9466  9532 I jxcore-log: *Native tests were executed*
09-26 09:01:30.851  9466  9532 I jxcore-log: 
09-26 09:01:30.851  9466  9532 I jxcore-log: Total number of executed tests:  1
09-26 09:01:30.851  9466  9532 I jxcore-log: 
09-26 09:01:30.851  9466  9532 I jxcore-log: Number of passed tests:  1
09-26 09:01:30.851  9466  9532 I jxcore-log: 
09-26 09:01:30.851  9466  9532 I jxcore-log: Number of failed tests:  0
09-26 09:01:30.851  9466  9532 I jxcore-log: 
09-26 09:01:30.851  9466  9532 I jxcore-log: Number of ignored tests:  0
09-26 09:01:30.851  9466  9532 I jxcore-log: 
09-26 09:01:30.851  9466  9532 I jxcore-log: Total duration:  4
09-26 09:01:30.851  9466  9532 I jxcore-log: 
09-26 09:01:30.851  9466  9532 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-26 09:01:30.851  9466  9532 I jxcore-log: 
,09-26 09:01:30.851  9466  9532 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-26 09:01:30.851  9466  9532 I jxcore-log: 
09-26 09:01:30.851  9466  9532 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-26 09:01:30.851  9466  9532 I jxcore-log: 
,09-26 09:01:30.881  9466  9466 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-26 09:01:31.351  9534  9534 I FIPS_bssl: FIPS approved mode (1) | 9534 | app_process
,09-26 09:01:31.361  9534  9534 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-26 09:01:31.361  9534  9534 D AndroidRuntime: CheckJNI is OFF
09-26 09:01:31.361  9534  9534 D AndroidRuntime: readGMSProperty: start
09-26 09:01:31.361  9534  9534 D AndroidRuntime: readGMSProperty: already setted!!
09-26 09:01:31.361  9534  9534 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-26 09:01:31.361  9534  9534 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-26 09:01:31.361  9534  9534 D AndroidRuntime: readGMSProperty: end
09-26 09:01:31.361  9534  9534 D AndroidRuntime: addProductProperty: start
,09-26 09:01:31.381  9534  9534 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-26 09:01:31.401  9534  9534 I Radio-JNI: register_android_hardware_Radio DONE
,09-26 09:01:31.401  9534  9534 E AffinityControl: AffinityControl: registerfunction enter
,09-26 09:01:31.411  9534  9534 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-26 09:01:31.421  3398  3850 D PackageManager: START PACKAGE DELETE: observer{131146463}
09-26 09:01:31.421  3398  3850 D PackageManager: pkg{<packageName>}
09-26 09:01:31.421  3398  3850 D PackageManager: user{0}
09-26 09:01:31.421  3398  3850 D PackageManager: caller{2000}
09-26 09:01:31.421  3398  3850 D PackageManager: flags{2}
09-26 09:01:31.421  3398  3850 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-26 09:01:31.421  3398  3850 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-26 09:01:31.421  3398  3850 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-26 09:01:31.421  3398  3850 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-26 09:01:31.421  3398  3850 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-26 09:01:31.421  3398  3573 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-26 09:01:31.421  3398  3573 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-26 09:01:31.421  3398  3573 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-26 09:01:31.421  3398  3573 D ApplicationPolicy: getApplicationUninstallationEnabled
09-26 09:01:31.421  3398  3573 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-26 09:01:31.421  3398  3573 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,09-26 09:01:31.421  3398  3573 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-26 09:01:31.421  3398  3573 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
09-26 09:01:31.421  3398  3573 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-26 09:01:31.421  3398  3517 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
09-26 09:01:31.421  3398  3573 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-26 09:01:31.431  3398  3517 I ActivityManager: Killing 9466:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-26 09:01:31.431  3398  3517 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-26 09:01:31.441  3398  3517 D ActivityManager: mDVFSHelper.acquire()
,09-26 09:01:31.451  3398  3552 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-26 09:01:31.451  3398  3552 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-26 09:01:31.451  3398  3552 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
09-26 09:01:31.451  3398  3552 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-26 09:01:31.451  3398  3552 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-26 09:01:31.451  3398  3552 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-26 09:01:31.451  3398  3552 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 09:01:31.451  3398  3552 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-26 09:01:31.451  3398  3552 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 09:01:31.451  3398  3552 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-26 09:01:31.451  3398  3552 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-26 09:01:31.451  3398  3552 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{407d071 V.E...... R.....ID 0,0-0,0}
,09-26 09:01:31.451  3398  3552 W WindowManager: Failed looking up window
09-26 09:01:31.451  3398  3552 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@13c5e56 does not exist
09-26 09:01:31.451  3398  3552 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 09:01:31.451  3398  3552 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-26 09:01:31.451  3398  3552 W WindowManager: view not successfully added to wm, removing view
09-26 09:01:31.451  3398  3552 D ViewRootImpl: #3 mView = null
,09-26 09:01:31.461  9543  9543 E Zygote  : v2
09-26 09:01:31.461  9543  9543 I libpersona: KNOX_SDCARD checking this for 10171
09-26 09:01:31.461  3398  3573 D AASAinstall: there is not AASApackages.xml file
09-26 09:01:31.461  9543  9543 I libpersona: KNOX_SDCARD not a persona
09-26 09:01:31.461  9543  9543 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-26 09:01:31.461  9543  9543 E Zygote  : accessInfo : 0
09-26 09:01:31.461  9543  9543 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,09-26 09:01:31.461  3398  3517 I ActivityManager: Start proc 9543:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
,09-26 09:01:31.471  3398  3517 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
09-26 09:01:31.471  3398  3517 I ActivityManager:   Force finishing activity ActivityRecord{2502035 u0 com.test.thalitest/.MainActivity t4}
,09-26 09:01:31.471  9543  9543 D TimaKeyStoreProvider: TimaSignature is unavailable
09-26 09:01:31.471  9543  9543 D ActivityThread: Added TimaKeyStore provider
,09-26 09:01:31.521  3398  3850 D GraphicsStats: Buffer count: 5
09-26 09:01:31.521  3398  3452 I WindowState: WIN DEATH: Window{3ff05c9 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
09-26 09:01:31.521  3398  4768 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@7f68ed7)
,09-26 09:01:31.521  3398  3864 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-26 09:01:31.521  3398  3864 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-26 09:01:31.531  3398  3864 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-26 09:01:31.531  3004  4329 I SurfaceFlinger: id=19 Removed NainActivit (6/10)
,09-26 09:01:31.531  3004  3015 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
09-26 09:01:31.531  3004  4306 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,09-26 09:01:31.691  3398  3573 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-26 09:01:31.761  3398  3573 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-26 09:01:31.761  3164  3164 W keystore: ENTER clear_uid from uid 1000 for 10171
,09-26 09:01:31.761  3398  3573 I art     : Starting a blocking GC Explicit
,09-26 09:01:31.781  3398  3398 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-26 09:01:31.791  3398  3992 I ActivityManager: Killing 8314:com.samsung.storyservice/5004 (adj 15): DHA:empty #33
,09-26 09:01:31.801  3004  3004 I SurfaceFlinger: id=20 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-26 09:01:31.801  3398  3517 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-26 09:01:31.811  9543  9543 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,09-26 09:01:31.811  3398  3517 D InputDispatcher: Focused application released
,09-26 09:01:31.811  3398  4985 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-26 09:01:31.811  9543  9543 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-26 09:01:31.821  9543  9543 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
09-26 09:01:31.821  9543  9543 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
09-26 09:01:31.821  9543  9543 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
09-26 09:01:31.821  9543  9543 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,09-26 09:01:31.821  4281  4281 D Launcher: onRestart, Launcher: 46728519
,09-26 09:01:31.831  4281  4281 D Launcher: onStart, Launcher: 46728519
,09-26 09:01:31.831  4281  4281 D Launcher.HomeView: onStart
09-26 09:01:31.831  3398  4293 D ActivityManager: isAutoRunBlockedApp:: com.samsung.storyservice, Auto Run ON
09-26 09:01:31.831  9543  9543 I InjectionManager: Inside getClassLibPath caller 
09-26 09:01:31.831  4281  4281 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-26 09:01:31.831  4281  4281 V ActivityThread: updateVisibility : ActivityRecord{f8253b8 token=android.os.BinderProxy@2b00712 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-26 09:01:31.831  4281  4281 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
,09-26 09:01:31.831  4281  4281 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
09-26 09:01:31.831  4281  4281 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
,09-26 09:01:31.841  9543  9543 D AndroidRuntime: Shutting down VM
,09-26 09:01:31.841  4281  4281 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
09-26 09:01:31.841  4281  4281 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
09-26 09:01:31.841  4281  4281 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
,09-26 09:01:31.841  9543  9543 E AndroidRuntime: FATAL EXCEPTION: main
09-26 09:01:31.841  9543  9543 E AndroidRuntime: Process: com.test.thalitest, PID: 9543
09-26 09:01:31.841  9543  9543 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-26 09:01:31.841  9543  9543 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
09-26 09:01:31.841  9543  9543 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6294)
09-26 09:01:31.841  9543  9543 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:222)
09-26 09:01:31.841  9543  9543 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1861)
09-26 09:01:31.841  9543  9543 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 09:01:31.841  9543  9543 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
09-26 09:01:31.841  9543  9543 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7229)
09-26 09:01:31.841  9543  9543 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 09:01:31.841  9543  9543 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-26 09:01:31.841  9543  9543 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-26 09:01:31.841  9543  9543 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-26 09:01:31.841  9543  9543 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
09-26 09:01:31.841  9543  9543 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
09-26 09:01:31.841  9543  9543 E AndroidRuntime: 	... 9 more
09-26 09:01:31.841  4281  4281 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-26 09:01:31.841  4281  4281 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
,09-26 09:01:31.841  4281  4281 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
09-26 09:01:31.841  3398  5983 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
09-26 09:01:31.851  3004  3004 I SurfaceFlinger: id=21 createSurf (1440x2560),1 flag=4, MauncherAct
09-26 09:01:31.861  4281  4587 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-26 09:01:31.861  9558  9558 E Zygote  : v2
09-26 09:01:31.861  9558  9558 I libpersona: KNOX_SDCARD checking this for 1000
09-26 09:01:31.861  9558  9558 I libpersona: KNOX_SDCARD not a persona
09-26 09:01:31.861  9558  9558 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-26 09:01:31.861  3398  3517 I ActivityManager: Start proc 9558:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
09-26 09:01:31.861  3398  4004 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-26 09:01:31.861  9558  9558 E Zygote  : accessInfo : 0
09-26 09:01:31.861  3398  4004 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 09:01:31.861  3398  3398 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 09:01:31.871  9543  9543 I Process : Sending signal. PID: 9543 SIG: 9
09-26 09:01:31.871  3398  3398 I KnoxTimeoutHandler: Shared devices show user statefalse
09-26 09:01:31.871  3398  3398 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-26 09:01:31.891  3151  3630 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-26 09:01:31.901  9558  9558 D TimaKeyStoreProvider: TimaSignature is unavailable
09-26 09:01:31.891  3398  5983 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-26 09:01:31.901  9558  9558 D ActivityThread: Added TimaKeyStore provider
09-26 09:01:31.891  3398  5983 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
09-26 09:01:31.901  3398  4293 I ActivityManager: Process com.test.thalitest (pid 9543)(adj 9) has died(168,1809)
,09-26 09:01:31.901  3398  4293 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-26 09:01:31.911  3398  4293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26743 com.android.server.am.ActivityManagerService.appDiedLocked:7562 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1916 android.os.BinderProxy.sendDeathNotice:558 
,09-26 09:01:31.921  3398  5983 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-26 09:01:31.921  3398  3452 V WindowStateAnimator: Finishing drawing window Window{6a966d u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-26 09:01:31.921  3398  5983 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-26 09:01:31.921  3004  3004 D libEGL  : eglInitialize EGLDisplay = 0x7fed75b088
,09-26 09:01:31.921  3004  3004 D libEGL  : eglInitialize EGLDisplay = 0x7fed75b088
09-26 09:01:31.921  3398  5983 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,09-26 09:01:31.931  3398  4004 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4ca83c4 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf802ad 9558:com.samsung.android.sm/1000}
,09-26 09:01:31.931  3004  3004 I SurfaceFlinger: id=22 createSurf (1592x384),1 flag=4, VSBConnecti
,09-26 09:01:31.931  3398  3573 I art     : Explicit concurrent mark sweep GC freed 113221(7MB) AllocSpace objects, 7(1932KB) LOS objects, 32% free, 33MB/49MB, paused 1.783ms total 166.350ms
,09-26 09:01:31.931  3398  4711 V WindowStateAnimator: Finishing drawing window Window{2e0c7f7 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
,09-26 09:01:31.941  3398  3552 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-26 09:01:31.941  3398  3398 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-26 09:01:31.941  3398  3552 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1cc289f u0 com.samsung.android.MtpApplication/.USBConnection t3} time:231091
09-26 09:01:31.941  3398  3552 D ActivityManager: mDVFSHelper.release()
,09-26 09:01:31.941  6073  6073 V ActivityThread: updateVisibility : ActivityRecord{b9a0356 token=android.os.BinderProxy@489fd6b {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,09-26 09:01:31.941  9558  9558 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_NoIcon/SmartManager_v3_NoIcon.apk / 1.0 running in com.samsung.android.sm rsrc of package com.samsung.android.sm
,09-26 09:01:31.941  3398  3398 I KnoxTimeoutHandler: SD activityfalse
,09-26 09:01:31.941  3398  4004 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-26 09:01:31.951  9558  9558 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-26 09:01:31.951  4281  4281 D Launcher.HomeView: onStop
09-26 09:01:31.951  4281  4281 D capture : ----destroy
,09-26 09:01:31.951  3398  3573 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-26 09:01:31.951  3398  3573 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
09-26 09:01:31.951  3398  3573 D AASAinstall: there is not AASApackages.xml file
09-26 09:01:31.951  9558  9558 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:31.951  3398  3573 D PackageManager: result of delete: 1{131146463}
,09-26 09:01:31.951  9534  9534 I art     : System.exit called, status: 0
09-26 09:01:31.951  9534  9534 I AndroidRuntime: VM exiting with result code 0.
09-26 09:01:31.951  3398  3573 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-26 09:01:31.951  3398  3573 D PackageManager: userId{-1}
09-26 09:01:31.951  3398  3573 D PackageManager: andCode{true}
,09-26 09:01:31.961  3398  3552 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-26 09:01:31.961  3398  3552 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e80e4c5 u0 com.sec.android.app.launcher/.activities.LauncherActivity t1} time:231110
09-26 09:01:31.961  3398  3398 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-26 09:01:31.961  3398  3398 I KnoxTimeoutHandler: SD activityfalse
09-26 09:01:31.961  9558  9558 I InjectionManager: Inside getClassLibPath caller 
,09-26 09:01:31.961  3398  3573 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-26 09:01:31.991  3398  4280 V WindowStateAnimator: Finishing drawing window Window{90b5b33 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-26 09:01:31.991  9558  9558 D InjectionManager: InjectionManager
09-26 09:01:31.991  9558  9558 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm
,09-26 09:01:31.991  9558  9558 I InjectionManager: Constructor com.samsung.android.sm, Feature store :{}
09-26 09:01:31.991  9558  9558 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
09-26 09:01:31.991  9558  9558 I InjectionManager: featureStore :{}
09-26 09:01:31.991  6073  6073 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@489fd6b time:231142
,09-26 09:01:32.001  3004  3004 D libEGL  : eglInitialize EGLDisplay = 0x7fed75b088
,09-26 09:01:32.011  8891  9572 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-26 09:01:32.021  8891  9572 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-26 09:01:32.021  8891  9572 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-26 09:01:32.031  3398  3552 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-26 09:01:32.031  3398  3398 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-26 09:01:32.031  3398  3398 I KnoxTimeoutHandler: SD activityfalse
,09-26 09:01:32.041  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:32.041  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-26 09:01:32.051  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.051  3930  3930 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
09-26 09:01:32.051  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.051  3930  3930 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.test.thalitest
09-26 09:01:32.051  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.051  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.051  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.051  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.051  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.051  3398  3552 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
09-26 09:01:32.051  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.061  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.061  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
09-26 09:01:32.061  3398  3552 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.061  3398  3552 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
,09-26 09:01:32.061  3398  3826 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-26 09:01:32.061  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:32.061  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,09-26 09:01:32.061  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-26 09:01:32.071  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:32.071  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.071  4294  4775 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-26 09:01:32.071  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.071  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.071  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.071  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.071  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-26 09:01:32.071  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:32.071  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,09-26 09:01:32.081  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-26 09:01:32.081  5053  5342 D PresenceModule: onReceive: package removed
09-26 09:01:32.081  5053  5342 D PresenceModule: handleMessage: msg 50, Last Publish Info: null
09-26 09:01:32.081  5053  5342 D PresenceModule: Application package removed
09-26 09:01:32.081  5053  5342 D PresenceModule: onAppPkgRemoved: com.test.thalitest
09-26 09:01:32.081  5053  5342 D PresenceModule: onApplicationPackageRemoved: invalid package
,09-26 09:01:32.081  3398  3511 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:32.081  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
09-26 09:01:32.081  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-26 09:01:32.081  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:32.081  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,09-26 09:01:32.081  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:32.081  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:32.081  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,09-26 09:01:32.091  3398  3511 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.091  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:32.091  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-26 09:01:32.091  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-26 09:01:32.091  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,09-26 09:01:32.091  3398  3902 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/4_task.xml
,09-26 09:01:32.091  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.091  4026  4026 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
09-26 09:01:32.091  3398  4371 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4885, uid=10124 that is not exported from uid 10122
,09-26 09:01:32.091  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-26 09:01:32.091  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,09-26 09:01:32.091  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-26 09:01:32.091  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-26 09:01:32.091  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,09-26 09:01:32.091  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,09-26 09:01:32.101  3398  3511 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.101  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:32.101  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,09-26 09:01:32.101  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.101  3398  3511 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.101  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.101  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
09-26 09:01:32.101  3398  3852 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-26 09:01:32.101  3398  3852 D NtpTrustedTime: currentTimeMillis() cache hit
,09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.101  3398  3852 V NetworkStats: performPollLocked(flags=0x3)
09-26 09:01:32.101  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.111  3398  3511 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.111  3398  3853 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.111  3398  3853 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.111  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.111  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
09-26 09:01:32.111  3398  3511 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.111  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
09-26 09:01:32.111  3398  3511 D AccessibilityManagerService: onUserStateChangedLocked()
09-26 09:01:32.111  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.111  3398  3511 D AccessibilityManagerService: updateServicesLocked().mIsAccessibilityEnabled : false
,09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-26 09:01:32.111  3398  3852 D NetworkStatsRecorder: entry.iface is null
09-26 09:01:32.111  3398  3852 D NetworkStatsRecorder: entry.iface is null
09-26 09:01:32.111  3398  3852 D NetworkStatsRecorder: entry.iface is null
09-26 09:01:32.111  3398  3852 D NetworkStatsRecorder: entry.iface is null
,09-26 09:01:32.111  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-26 09:01:32.111  3398  3511 D EnterpriseDeviceManagerService: Package has changed for user 0
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
09-26 09:01:32.111  3398  3511 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
,09-26 09:01:32.111  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.121  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.121  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,09-26 09:01:32.121  3398  3852 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473847817708- -> /data/system/netstats/uid.1473847817708-.backup
,09-26 09:01:32.121  3398  3852 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473847817708-
09-26 09:01:32.121  3398  3852 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473847817708-.backup -> /data/system/netstats/uid.1473847817708-
,09-26 09:01:32.121  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
,09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:32.121  3398  3511 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:32.121  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:32.121  3398  3878 D MdnieScenarioControlService:  packageName : com.samsung.android.MtpApplication    className : com.samsung.android.MtpApplication.USBConnection
09-26 09:01:32.121  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
09-26 09:01:32.121  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
09-26 09:01:32.131  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.131  3398  3511 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.131  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
,09-26 09:01:32.131  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-26 09:01:32.131  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-26 09:01:32.131  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
09-26 09:01:32.131  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-26 09:01:32.131  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-26 09:01:32.131  4267  4267 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-26 09:01:32.131  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
09-26 09:01:32.131  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.131  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
09-26 09:01:32.131  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
09-26 09:01:32.131  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.131  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
09-26 09:01:32.131  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:32.131  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:32.131  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:32.131  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:32.131  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:32.141  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
09-26 09:01:32.141  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
09-26 09:01:32.141  3398  3511 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.141  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
09-26 09:01:32.141  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.141  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
09-26 09:01:32.141  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
09-26 09:01:32.141  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-26 09:01:32.141  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.141  3398  3511 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.141  3398  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
09-26 09:01:32.141  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
09-26 09:01:32.151  3398  3852 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop97.tmp
09-26 09:01:32.151  3398  3852 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1473847817708-
09-26 09:01:32.151  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-26 09:01:32.151  3398  3852 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid.1472201655233-1473847639678
09-26 09:01:32.151  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: Can't write: netstats_dump
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1222)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-26 09:01:32.151  3398  3852 E DropBoxManagerService: 	... 16 more
09-26 09:01:32.151  3398  3398 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.151  3398  3511 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.151  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-26 09:01:32.151  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
09-26 09:01:32.151  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-26 09:01:32.151  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
09-26 09:01:32.161  3398  4711 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{362ed9e u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{22d536b 6444:com.samsung.klmsagent/u0a26}
09-26 09:01:32.161  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
09-26 09:01:32.161  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-26 09:01:32.161  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
09-26 09:01:32.161  3398  3511 D ResourcesManager: For user 0 new overlays fetched Null
09-26 09:01:32.161  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-26 09:01:32.161  6444  6444 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Mon Sep 26 09:01:32 GMT+02:00 2016
09-26 09:01:32.161  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: Can't write: netstats_dump
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1223)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-26 09:01:32.161  3398  3852 E DropBoxManagerService: 	... 16 more
09-26 09:01:32.161  3398  3852 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop97.tmp
09-26 09:01:32.161  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
09-26 09:01:32.161  3398  3852 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1474285157707-1474873077928
09-26 09:01:32.161  3398  3852 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/uid_tag.1473847817708-1474285028441
09-26 09:01:32.161  3398  3852 V NetworkStats: performPollLocked() took 60ms
09-26 09:01:32.171  3398  3852 D NtpTrustedTime: currentTimeMillis() cache hit
09-26 09:01:32.171  3398  3511 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
09-26 09:01:32.171  3398  3398 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos

```
