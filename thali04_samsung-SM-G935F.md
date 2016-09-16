#### Test 8504691131acdd6_thali04_samsung-SM-G935F Logs


```
--------- beginning of main
,09-16 12:18:06.519  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:06.589  3152  3790 D EnterpriseController: netId is 0
09-16 12:18:06.589  3152  3790 D Netd    : getNetworkForDns: using netid 0 for uid 10002
09-16 12:18:06.589  4575  4755 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/categories
09-16 12:18:06.589  4575  4755 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 12:18:06.589  4575  4755 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
09-16 12:18:06.589  4575  4755 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
09-16 12:18:06.589  4575  4755 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
09-16 12:18:06.589  4575  4755 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
09-16 12:18:06.589  4575  4755 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-16 12:18:06.589  4575  4755 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-16 12:18:06.589  4575  4755 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-16 12:18:06.589  4575  4755 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-16 12:18:06.589  4575  4755 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
09-16 12:18:06.589  4575  4755 E         : 	at java.lang.Thread.run(Thread.java:818)
09-16 12:18:06.589  4575  4755 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 12:18:06.589  4575  4755 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
09-16 12:18:06.589  4575  4755 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
09-16 12:18:06.589  4575  4755 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
09-16 12:18:06.589  4575  4755 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
09-16 12:18:06.589  4575  4755 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
09-16 12:18:06.589  4575  4755 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
09-16 12:18:06.589  4575  4755 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
09-16 12:18:06.589  4575  4755 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
09-16 12:18:06.589  4575  4755 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
09-16 12:18:06.589  4575  4755 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
09-16 12:18:06.589  4575  4755 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
09-16 12:18:06.589  4575  4755 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
09-16 12:18:06.589  4575  4755 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
09-16 12:18:06.589  4575  4755 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
09-16 12:18:06.589  4575  4755 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
09-16 12:18:06.589  4575  4755 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
09-16 12:18:06.589  4575  4755 E         : 	... 9 more
09-16 12:18:06.589  4575  4755 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
09-16 12:18:06.589  4575  4755 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
09-16 12:18:06.589  4575  4755 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
09-16 12:18:06.589  4575  4755 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
09-16 12:18:06.589  4575  4755 E         : 	... 24 more
09-16 12:18:06.589  4575  4755 E         : 
09-16 12:18:06.699  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:06.879  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:06.989  9176  9176 I FIPS_bssl: FIPS approved mode (1) | 9176 | app_process
09-16 12:18:06.999  9176  9176 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 12:18:06.999  9176  9176 D AndroidRuntime: CheckJNI is OFF
09-16 12:18:06.999  9176  9176 D AndroidRuntime: readGMSProperty: start
09-16 12:18:06.999  9176  9176 D AndroidRuntime: readGMSProperty: already setted!!
09-16 12:18:06.999  9176  9176 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-16 12:18:06.999  9176  9176 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-16 12:18:06.999  9176  9176 D AndroidRuntime: readGMSProperty: end
09-16 12:18:06.999  9176  9176 D AndroidRuntime: addProductProperty: start
09-16 12:18:07.019  9176  9176 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 12:18:07.039  9176  9176 I Radio-JNI: register_android_hardware_Radio DONE
09-16 12:18:07.039  9176  9176 E AffinityControl: AffinityControl: registerfunction enter
09-16 12:18:07.049  9176  9176 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-16 12:18:07.059  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:07.079  3436  4394 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
--------- beginning of system
09-16 12:18:07.079  3436  4394 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-16 12:18:07.099  3436  4394 D ResourcesManager: For user 0 new overlays fetched Null
09-16 12:18:07.099  3436  4394 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 12:18:07.099  3436  4394 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-16 12:18:07.109  3436  4394 D ActivityManager: mDVFSHelper.acquire()
09-16 12:18:07.109  3436  4394 V WindowManager: addAppToken: AppWindowToken{d0108f157 token=Token{468bad6 ActivityRecord{5f1cef1 u0 com.test.thalitest/.MainActivity t75}}} to stack=2 task=75 at 0
09-16 12:18:07.119  3436  3536 I InjectionManager: Inside getClassLibPath caller 
09-16 12:18:07.129  3436  3536 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-16 12:18:07.129  3436  3536 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a9ab44f V.E...... R.....ID 0,0-0,0}
09-16 12:18:07.139  9186  9186 E Zygote  : v2
09-16 12:18:07.139  9186  9186 I libpersona: KNOX_SDCARD checking this for 10177
09-16 12:18:07.139  9186  9186 I libpersona: KNOX_SDCARD not a persona
09-16 12:18:07.139  9186  9186 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-16 12:18:07.139  3436  3536 W WindowManager: Failed looking up window
09-16 12:18:07.139  3436  3536 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@ae907dc does not exist
09-16 12:18:07.139  3436  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 12:18:07.139  3436  3536 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 12:18:07.139  9186  9186 E Zygote  : accessInfo : 0
09-16 12:18:07.139  3436  4394 I ActivityManager: Start proc 9186:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-16 12:18:07.139  9186  9186 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-16 12:18:07.139  3436  3536 D ISSUE_DEBUG: InputChannelName : 5c590e5 Starting com.test.thalitest
09-16 12:18:07.139  3436  4394 D InputDispatcher: Focused application set to: xxxx
09-16 12:18:07.149  9176  9176 D AndroidRuntime: Shutting down VM
09-16 12:18:07.149  3436  3860 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-16 12:18:07.159  3009  3009 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
09-16 12:18:07.169  9186  9186 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 12:18:07.169  9186  9186 D ActivityThread: Added TimaKeyStore provider
09-16 12:18:07.179  6023  6023 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 12:18:07.199  3436  4566 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3436
09-16 12:18:07.199  3436  4566 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 12:18:07.199  3436  4566 D PowerManagerService: mDisplayReady: false
09-16 12:18:07.199  3436  4566 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 12:18:07.199  3436  3540 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 12:18:07.199  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa2543c00
09-16 12:18:07.199  3436  3540 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 12:18:07.199  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-16 12:18:07.199  3436  4566 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 12:18:07.199  3436  3540 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 12:18:07.199  3436  3540 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 12:18:07.199  3436  3554 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-16 12:18:07.199  6023  6023 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 12:18:07.199  3436  3540 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 12:18:07.199  3436  4565 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3436
09-16 12:18:07.199  3436  3540 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 12:18:07.199  3436  3540 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 12:18:07.199  3436  3540 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 12:18:07.199  3436  3540 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 12:18:07.199  3436  3540 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 12:18:07.199  3436  3540 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 12:18:07.199  3436  3540 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 12:18:07.199  3436  3540 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 12:18:07.199  3436  3540 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 12:18:07.199  3436  3540 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 12:18:07.199  3436  3540 D PowerManagerService: mDisplayReady: true
09-16 12:18:07.199  3436  3540 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-16 12:18:07.209  3436  4329 D ActivityManager:  Launching com.test.thalitest, updated priority
09-16 12:18:07.209  3436  4174 V WindowStateAnimator: Finishing drawing window Window{7c12c81 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-16 12:18:07.219  4317  4317 V ActivityThread: updateVisibility : ActivityRecord{76f4ee token=android.os.BinderProxy@aa56b27 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
09-16 12:18:07.229  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:07.239  3436  3436 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-16 12:18:07.239  3436  3510 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-16 12:18:07.239  5689  8626 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} Intent { flg=0x10000000 cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
09-16 12:18:07.249  3009  4641 D libEGL  : eglTerminate EGLDisplay = 0x7f91ffee78
09-16 12:18:07.249  3009  4641 D libEGL  : eglTerminate EGLDisplay = 0x7f91ffee78
09-16 12:18:07.249  3009  3557 I SurfaceFlinger: id=9 Removed MauncherAct (3/13)
09-16 12:18:07.249  3009  4641 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
09-16 12:18:07.259  3436  4512 V WindowStateAnimator: Finishing drawing window Window{43678b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
09-16 12:18:07.259  6023  6023 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 12:18:07.259  6023  6023 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-16 12:18:07.259  4317  4317 D Launcher: onTrimMemory. Level: 20
09-16 12:18:07.259  6023  6023 V ActivityThread: updateVisibility : ActivityRecord{48f8bea token=android.os.BinderProxy@2a0b73c {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-16 12:18:07.269  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fe4d68628
09-16 12:18:07.269  3009  3020 I SurfaceFlinger: id=17 Removed VSBConnecti (7/12)
09-16 12:18:07.269  3009  4641 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/12)
09-16 12:18:07.269  3009  3557 D libEGL  : eglTerminate EGLDisplay = 0x7f9baffe78
09-16 12:18:07.279  3009  4641 I SurfaceFlinger: id=18 Removed VSBConnecti (5/11)
09-16 12:18:07.279  3009  3556 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/11)
09-16 12:18:07.299  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fe4d68628
09-16 12:18:07.299  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fe4d68628
09-16 12:18:07.349  3436  3436 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3436 (0x0)
09-16 12:18:07.349  3436  3436 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection uid=1000 pid=3436 (0x0)
09-16 12:18:07.349  3436  3436 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 12:18:07.349  3436  3436 D PowerManagerService: mDisplayReady: false
09-16 12:18:07.349  3436  3436 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 12:18:07.349  3436  3540 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 12:18:07.349  3436  3540 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 12:18:07.349  3436  3436 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 12:18:07.349  3436  3540 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 12:18:07.349  3436  3540 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 12:18:07.349  3436  3554 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-16 12:18:07.359  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa2543c00
09-16 12:18:07.359  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-16 12:18:07.359  3436  3540 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 12:18:07.359  3436  3540 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 12:18:07.359  3436  3540 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 12:18:07.359  3436  3540 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 12:18:07.359  3436  3540 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 12:18:07.359  3436  3540 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 12:18:07.359  3436  3540 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 12:18:07.359  3436  3540 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 12:18:07.359  3436  3540 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 12:18:07.359  3436  3540 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 12:18:07.359  3436  3540 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 12:18:07.359  3436  3540 D PowerManagerService: mDisplayReady: true
09-16 12:18:07.359  3436  3540 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-16 12:18:07.409  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:07.539  5689  5689 I TrayVisibilityController: handleMessage : msg.what = 1
09-16 12:18:07.549  3436  4329 I WindowManager: Screenshot max retries 4 of Token{468bad6 ActivityRecord{5f1cef1 u0 com.test.thalitest/.MainActivity t75}} appWin=Window{5c590e5 u0 d0 Starting com.test.thalitest} drawState=1
09-16 12:18:07.549  5689  5700 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity}
09-16 12:18:07.549  3436  3536 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 12:18:07.549  3436  3436 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 12:18:07.549  3436  3536 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-16 12:18:07.559  3436  3860 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
09-16 12:18:07.559  3436  5955 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 12:18:07.559  3436  5955 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 12:18:07.569  5689  5689 I Utils   : isCurrentUser current = 0, ownerId = 0
09-16 12:18:07.569  5689  5689 I TrayVisibilityController: getComputedTrayVisible : keyguardState = 3
09-16 12:18:07.569  5689  5689 I TrayVisibilityController: updateTrayVisible : State : 3 visible = 2 mCurrentVisible = 2
09-16 12:18:07.569  3436  3436 I KnoxTimeoutHandler: SD activityfalse
09-16 12:18:07.589  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:07.589  3436  5955 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 12:18:07.599  9186  9186 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-16 12:18:07.599  9186  9186 D RelationGraph: garbageCollect()
09-16 12:18:07.599  3436  5955 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 12:18:07.599  9186  9186 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-16 12:18:07.599  3436  5007 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-16 12:18:07.599  3436  3536 V WindowStateAnimator: Finishing drawing window Window{5c590e5 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-16 12:18:07.599  9186  9186 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-16 12:18:07.599  3436  3536 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 12:18:07.599  3436  3436 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 12:18:07.609  3436  3436 I KnoxTimeoutHandler: SD activityfalse
09-16 12:18:07.609  3436  5955 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-16 12:18:07.609  3436  5955 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 12:18:07.609  3436  5955 D GameManagerService: identifyGamePackage. com.test.thalitest
09-16 12:18:07.619  3436  3536 D ActivityManager: mDVFSHelper.release()
09-16 12:18:07.619  3436  3536 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{734394d u0 com.samsung.android.MtpApplication/.USBConnection t74} time:176410
09-16 12:18:07.619  9186  9186 D ResourcesManager: For user 0 new overlays fetched Null
09-16 12:18:07.619  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe4d68508
09-16 12:18:07.619  9186  9186 I InjectionManager: Inside getClassLibPath caller 
09-16 12:18:07.639  9186  9186 D InjectionManager: InjectionManager
09-16 12:18:07.639  9186  9186 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-16 12:18:07.639  9186  9186 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-16 12:18:07.639  9186  9186 I InjectionManager: featureStore :{}
09-16 12:18:07.649  9186  9186 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-16 12:18:07.649  9186  9186 D RelationGraph: garbageCollect()
09-16 12:18:07.649  9186  9186 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-16 12:18:07.679  9186  9186 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-16 12:18:07.709  9186  9186 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-16 12:18:07.719  9186  9186 D ResourcesManager: For user 0 new overlays fetched Null
09-16 12:18:07.719  9186  9186 I InjectionManager: Inside getClassLibPath caller 
09-16 12:18:07.719  9186  9186 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-16 12:18:07.769  9186  9186 I cr_LibraryLoader: Time to load native libraries: 31 ms (timestamps 6533-6564)
09-16 12:18:07.769  9186  9186 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-16 12:18:07.769  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:07.809  3436  3883 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
09-16 12:18:07.839  9186  9201 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-16 12:18:07.869  9186  9186 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {94730c}
09-16 12:18:07.869  9186  9186 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-16 12:18:07.889  9186  9186 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
09-16 12:18:07.909  3436  3883 I MdnieScenarioControlService: mGameModeLauncher : false
09-16 12:18:07.909  3436  3883 I MdnieScenarioControlService: setUIMode
09-16 12:18:07.929  9186  9186 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-16 12:18:07.949  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:08.049  3436  3510 W ActivityManager: Activity pause timeout for ActivityRecord{5f1cef1 u0 com.test.thalitest/.MainActivity t75}
09-16 12:18:08.109  9186  9203 W chromium: [WARNING:dns_config_service_posix.cc(306)] Failed to read DnsConfig.
09-16 12:18:08.129  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:08.189  9186  9186 D libEGL  : eglInitialize EGLDisplay = 0xffe60f1c
09-16 12:18:08.279  3436  3453 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10177
09-16 12:18:08.279  3436  3453 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
09-16 12:18:08.309  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:08.379  9186  9186 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-16 12:18:08.409  9186  9186 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-16 12:18:08.409  9186  9186 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-16 12:18:08.449  9186  9186 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-16 12:18:08.489  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:08.509  9186  9186 D Activity: performCreate Call Injection manager
09-16 12:18:08.509  9186  9186 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
09-16 12:18:08.519  9186  9186 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-16 12:18:08.529  9186  9186 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ce379ca I.E...... R.....ID 0,0-0,0}
09-16 12:18:08.529  9186  9238 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-16 12:18:08.539  3436  3766 W WindowManager: Failed looking up window
09-16 12:18:08.539  3436  3766 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@5bda43c does not exist
09-16 12:18:08.539  3436  3766 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-16 12:18:08.539  3436  3766 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-16 12:18:08.539  3436  3766 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-16 12:18:08.539  3436  3766 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:688)
09-16 12:18:08.539  3436  3766 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:139)
09-16 12:18:08.539  3436  3766 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-16 12:18:08.539  3436  5007 D ISSUE_DEBUG: InputChannelName : c3165c5 com.test.thalitest/com.test.thalitest.MainActivity
09-16 12:18:08.549  3436  3857 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-16 12:18:08.549  3436  3857 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 12:18:08.549  3436  3436 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 12:18:08.549  3436  3436 I KnoxTimeoutHandler: Shared devices show user statefalse
09-16 12:18:08.549  9186  9186 V ActivityThread: updateVisibility : ActivityRecord{a408e58 token=android.os.BinderProxy@d01f12 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-16 12:18:08.559  3436  5956 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-16 12:18:08.559  9186  9201 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-16 12:18:08.579  9186  9186 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10177, CallingPid : 9186
09-16 12:18:08.579  3436  4166 D ConnectivityService: listenForNetwork for Listen from uid/pid:10177/9186 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-16 12:18:08.599  9186  9186 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-16 12:18:08.609  3009  3009 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, NainActivit
09-16 12:18:08.649  9186  9238 D libEGL  : eglInitialize EGLDisplay = 0xdc3bf7c4
09-16 12:18:08.649  9186  9238 I OpenGLRenderer: Initialized EGL, version 1.4
09-16 12:18:08.649  9186  9238 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-16 12:18:08.649  3436  3981 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3436
09-16 12:18:08.649  3436  3981 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 12:18:08.649  3436  3981 D PowerManagerService: mDisplayReady: false
09-16 12:18:08.649  3436  3981 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 12:18:08.649  3436  3540 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 12:18:08.649  3436  3981 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 12:18:08.649  3436  3540 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 12:18:08.649  3436  3540 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 12:18:08.649  3436  3540 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 12:18:08.649  3009  3009 D SurfaceFlinger: Set power mode=1, type=0 flinger=0x7fa2543c00
09-16 12:18:08.649  3436  3554 D DisplayManagerService: !@display_state: DOZE_SUSPEND -> DOZE brightness: 1 -> 1
09-16 12:18:08.649  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(1)
09-16 12:18:08.649  3436  3536 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE
09-16 12:18:08.659  3436  3536 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE
09-16 12:18:08.659  9186  9186 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-16 12:18:08.669  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:08.669  3436  3540 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 12:18:08.669  3436  3540 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 12:18:08.669  3436  3540 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 12:18:08.669  3436  3540 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 12:18:08.669  3436  3540 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 12:18:08.669  3436  3540 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 12:18:08.669  3436  3540 D DisplayPowerController: animateScreenStateChange[0]: target=3
09-16 12:18:08.669  3436  3540 D DisplayPowerController: [Dual Screen Compatible] state[0] :3
09-16 12:18:08.669  3436  3540 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 12:18:08.669  3436  3540 D DisplayPowerController: Animating brightness: target=1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 12:18:08.669  3436  3540 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 12:18:08.669  3436  3540 D PowerManagerService: mDisplayReady: true
09-16 12:18:08.669  3436  3540 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-16 12:18:08.689  5689  5689 E CocktailBarPositionManager: Window direction: 0
09-16 12:18:08.689  5689  5689 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-16 12:18:08.699  3436  4394 V WindowStateAnimator: Finishing drawing window Window{c3165c5 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-16 12:18:08.699  9186  9186 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-16 12:18:08.699  3436  4329 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3436
09-16 12:18:08.709  3436  3536 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 12:18:08.709  3436  3436 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-16 12:18:08.709  3436  3536 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s155ms (total +1s589ms)
09-16 12:18:08.709  3436  3536 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5f1cef1 u0 com.test.thalitest/.MainActivity t75} time:177502
09-16 12:18:08.709  3436  3536 D ViewRootImpl: #3 mView = null
09-16 12:18:08.709  3436  4512 D PowerManagerService: [api] acquire WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3436
09-16 12:18:08.709  3009  3557 I SurfaceFlinger: id=19 Removed uhalitest (6/11)
09-16 12:18:08.709  3436  3436 I KnoxTimeoutHandler: SD activityfalse
09-16 12:18:08.709  3009  3557 I SurfaceFlinger: id=19 Removed uhalitest (-2/11)
09-16 12:18:08.719  9186  9242 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-16 12:18:08.719  9186  9242 D libEGL  : eglInitialize EGLDisplay = 0xda83f3f4
09-16 12:18:08.719  3436  4565 V WindowStateAnimator: Finishing drawing window Window{c3165c5 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
09-16 12:18:08.719  9186  9186 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d01f12 time:177516
09-16 12:18:08.729  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fe4d68628
09-16 12:18:08.729  9186  9242 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
09-16 12:18:08.769  9186  9186 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9186
09-16 12:18:08.849  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:08.859  3436  3436 D PowerManagerService: [api] release WakeLock flags=0x80 tag=Window:com.test.thalitest/com.test.thalitest.MainActivity uid=1000 pid=3436 (0x0)
09-16 12:18:08.859  3436  3436 D PowerManagerService: mDisplayReady: false
09-16 12:18:08.859  3436  3436 I libsuspend: !@autosuspend_wakeup_count_disable
09-16 12:18:08.859  3436  3540 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 12:18:08.859  3436  3436 I libsuspend: !@autosuspend_wakeup_count_disable done
09-16 12:18:08.859  3436  3436 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-16 12:18:08.859  3436  3540 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 12:18:08.859  3436  3540 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 12:18:08.859  3436  3540 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 12:18:08.859  3436  3554 D DisplayManagerService: !@display_state: DOZE -> DOZE_SUSPEND brightness: 1 -> 1
09-16 12:18:08.859  3436  3536 I DisplayManagerService: Display device changed state: "Wbudowany ekran", DOZE_SUSPEND
09-16 12:18:08.859  3436  3536 I DisplayManagerService: Display device changed state: "ActivityViewVirtualDisplay", DOZE_SUSPEND
09-16 12:18:08.859  3009  3009 D SurfaceFlinger: Set power mode=3, type=0 flinger=0x7fa2543c00
09-16 12:18:08.859  3009  3009 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(3)
09-16 12:18:08.879  3436  3540 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 12:18:08.879  3436  3540 I libsuspend: !@autosuspend_wakeup_count_enable
09-16 12:18:08.879  3436  3540 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 12:18:08.879  3436  3540 I libsuspend: !@autosuspend_wakeup_count_enable done
09-16 12:18:08.879  3436  3540 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 12:18:08.879  3436  3540 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 12:18:08.879  3436  3540 D DisplayPowerController: animateScreenStateChange[0]: target=4
09-16 12:18:08.879  3436  3540 D DisplayPowerController: [Dual Screen Compatible] state[0] :4
09-16 12:18:08.879  3436  3540 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
09-16 12:18:08.879  3436  3540 D DisplayPowerController: Animating brightness: target=1, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
09-16 12:18:08.879  3436  3540 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-16 12:18:08.879  3436  3540 D PowerManagerService: mDisplayReady: true
09-16 12:18:08.879  3436  3540 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
09-16 12:18:08.889  5689  5689 E CocktailBarPositionManager: Window direction: 0
09-16 12:18:08.889  5689  5689 I CocktailBarPositionManager: updateAlphaScreenPosition position is dirty 0
09-16 12:18:09.009  9186  9186 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-16 12:18:09.029  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:09.049  4024  4024 D Recents : onTaskStackChanged
09-16 12:18:09.059  4024  4024 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
09-16 12:18:09.069  4024  4024 D ResourcesManager: For user 0 new overlays fetched Null
,09-16 12:18:09.109  9186  9249 D jxcore_app_log: JniHelper::setJavaVM(0xf4b34000), pthread_self() = -638584528
,09-16 12:18:09.109  9186  9249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-16 12:18:09.109  9186  9249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-16 12:18:09.109  9186  9249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-16 12:18:09.109  9186  9249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-16 12:18:09.109  9186  9249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-16 12:18:09.109  9186  9249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@640839c added. We now have 1 listener(s)
,09-16 12:18:09.109  9186  9249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
,09-16 12:18:09.109  9186  9249 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
09-16 12:18:09.109  9186  9249 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 12:18:09.109  9186  9249 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: A8:81:95:E9:5F:6F
09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-16 12:18:09.119  9186  9249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@673c52b added. We now have 1 listener(s)
09-16 12:18:09.119  9186  9249 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 12:18:09.119  9186  9249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 12:18:09.119  9186  9249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-16 12:18:09.119  9186  9249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-16 12:18:09.119  9186  9249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-16 12:18:09.119  9186  9249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-16 12:18:09.119  9186  9249 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:18:09.119  9186  9249 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
,09-16 12:18:09.119  9186  9249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 12:18:09.119  9186  9249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:18:09.119  9186  9249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:18:09.119  9186  9249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-16 12:18:09.119  9186  9249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 12:18:09.119  9186  9249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 12:18:09.119  9186  9249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 12:18:09.119  9186  9249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 12:18:09.119  9186  9249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 12:18:09.119  9186  9249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-16 12:18:09.119  9186  9249 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 12:18:09.119  9186  9249 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-16 12:18:09.149  9186  9186 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-16 12:18:09.209  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:09.389  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:09.459  9186  9250 W jxcore-log: Initializing JXcore engine
09-16 12:18:09.459  9186  9250 W jxcore-log: JXcore engine is ready
,09-16 12:18:09.479  4956  4956 E audit   : type=1400 msg=audit(1474021089.479:256): avc:  denied  { ioctl } for  pid=9250 comm="Thread-132" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4121 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-16 12:18:09.479  4956  4956 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-16 12:18:09.479  4956  4956 E audit   : type=1300 msg=audit(1474021089.479:256): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d94ff3c8 items=0 ppid=3177 pid=9250 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-132" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-16 12:18:09.479  4956  4956 E audit   : type=1327 msg=audit(1474021089.479:256): proctitle="com.test.thalitest"
09-16 12:18:09.479  4956  4956 E audit   : type=1320 msg=audit(1474021089.479:256): 
09-16 12:18:09.479  4956  4956 E audit   : type=1400 msg=audit(1474021089.479:257): avc:  denied  { ioctl } for  pid=9250 comm="Thread-132" path="socket:[35990]" dev="sockfs" ino=35990 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-16 12:18:09.479  4956  4956 E audit   :  SEPF_SECMOBILE_6.0.1_0013
09-16 12:18:09.479  4956  4956 E audit   : type=1300 msg=audit(1474021089.479:257): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3b a1=5451 a2=2 a3=d94ff3c8 items=0 ppid=3177 pid=9250 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 tty=(none) ses=4294967295 comm="Thread-132" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-16 12:18:09.479  4956  4956 E audit   : type=1327 msg=audit(1474021089.479:257): proctitle="com.test.thalitest"
09-16 12:18:09.479  4956  4956 E audit   : type=1320 msg=audit(1474021089.479:257): 
,09-16 12:18:09.479  9186  9250 W jxcore-log: Starting JXcore engine
,09-16 12:18:09.519  9186  9250 W jxcore-log: Platform android
09-16 12:18:09.519  9186  9250 W jxcore-log: 
09-16 12:18:09.519  9186  9250 W jxcore-log: Process ARCH arm
09-16 12:18:09.519  9186  9250 W jxcore-log: 
,09-16 12:18:09.569  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:09.589  9186  9250 I jxcore-log: JXcore Cordova bridge is ready!
09-16 12:18:09.589  9186  9250 I jxcore-log: 
09-16 12:18:09.589  9186  9250 W jxcore-log: JXcore engine is started
,09-16 12:18:09.599  9186  9249 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-16 12:18:09.599  9186  9186 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-16 12:18:09.599  3152  3790 D EnterpriseController: netId is 0
09-16 12:18:09.599  3152  3790 D Netd    : getNetworkForDns: using netid 0 for uid 10002
,09-16 12:18:09.599  4575  4755 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/categories
09-16 12:18:09.599  4575  4755 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 12:18:09.599  4575  4755 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
09-16 12:18:09.599  4575  4755 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
09-16 12:18:09.599  4575  4755 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
09-16 12:18:09.599  4575  4755 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
09-16 12:18:09.599  4575  4755 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-16 12:18:09.599  4575  4755 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-16 12:18:09.599  4575  4755 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-16 12:18:09.599  4575  4755 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-16 12:18:09.599  4575  4755 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
09-16 12:18:09.599  4575  4755 E         : 	at java.lang.Thread.run(Thread.java:818)
09-16 12:18:09.599  4575  4755 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 12:18:09.599  4575  4755 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
09-16 12:18:09.599  4575  4755 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
09-16 12:18:09.599  4575  4755 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
09-16 12:18:09.599  4575  4755 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
09-16 12:18:09.599  4575  4755 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
09-16 12:18:09.599  4575  4755 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
09-16 12:18:09.599  4575  4755 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
09-16 12:18:09.599  4575  4755 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
09-16 12:18:09.599  4575  4755 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
09-16 12:18:09.599  4575  4755 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
09-16 12:18:09.599  4575  4755 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
09-16 12:18:09.599  4575  4755 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
09-16 12:18:09.599  4575  4755 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
09-16 12:18:09.599  4575  4755 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
09-16 12:18:09.599  4575  4755 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
09-16 12:18:09.599  4575  4755 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
09-16 12:18:09.599  4575  4755 E         : 	... 9 more
09-16 12:18:09.599  4575  4755 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
09-16 12:18:09.599  4575  4755 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
09-16 12:18:09.599  4575  4755 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
09-16 12:18:09.599  4575  4755 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
09-16 12:18:09.599  4575  4755 E         : 	... 24 more
09-16 12:18:09.599  4575  4755 E         : 
,09-16 12:18:09.749  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:09.929  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:10.109  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:10.119  3436  3909 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/75_task.xml.bak
,09-16 12:18:10.289  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:10.469  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:10.569  3436  5955 D GameManagerService: identifyGamePackage. com.test.thalitest
,09-16 12:18:10.649  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:10.829  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:11.009  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:11.189  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:11.369  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:11.549  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:11.729  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:11.849  3436  5955 D SSRM:n  : SIOP:: AP = 320, PST = 286 (W:6), CP = 242, CUR = 145, LCD = 1
,09-16 12:18:11.909  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:12.089  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:12.269  3436  5956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,09-16 12:18:12.269  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:12.279  3436  3510 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d09eeca u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b48e4fd 8769:com.samsung.android.sm.provider/1000}
,09-16 12:18:12.359  3436  5956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,09-16 12:18:12.369  3436  3510 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6688b58 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b48e4fd 8769:com.samsung.android.sm.provider/1000}
,09-16 12:18:12.449  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:12.609  3152  3790 D EnterpriseController: netId is 0
09-16 12:18:12.609  3152  3790 D Netd    : getNetworkForDns: using netid 0 for uid 10002
,09-16 12:18:12.619  4575  4755 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/categories
09-16 12:18:12.619  4575  4755 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 12:18:12.619  4575  4755 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
09-16 12:18:12.619  4575  4755 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
09-16 12:18:12.619  4575  4755 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
09-16 12:18:12.619  4575  4755 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
09-16 12:18:12.619  4575  4755 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-16 12:18:12.619  4575  4755 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-16 12:18:12.619  4575  4755 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-16 12:18:12.619  4575  4755 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-16 12:18:12.619  4575  4755 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
09-16 12:18:12.619  4575  4755 E         : 	at java.lang.Thread.run(Thread.java:818)
09-16 12:18:12.619  4575  4755 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-16 12:18:12.619  4575  4755 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
09-16 12:18:12.619  4575  4755 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
09-16 12:18:12.619  4575  4755 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
09-16 12:18:12.619  4575  4755 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
09-16 12:18:12.619  4575  4755 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
09-16 12:18:12.619  4575  4755 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
09-16 12:18:12.619  4575  4755 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
09-16 12:18:12.619  4575  4755 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
09-16 12:18:12.619  4575  4755 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
09-16 12:18:12.619  4575  4755 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
09-16 12:18:12.619  4575  4755 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
09-16 12:18:12.619  4575  4755 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
09-16 12:18:12.619  4575  4755 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
09-16 12:18:12.619  4575  4755 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
09-16 12:18:12.619  4575  4755 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
09-16 12:18:12.619  4575  4755 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
09-16 12:18:12.619  4575  4755 E         : 	... 9 more
09-16 12:18:12.619  4575  4755 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
09-16 12:18:12.619  4575  4755 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
09-16 12:18:12.619  4575  4755 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
09-16 12:18:12.619  4575  4755 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
09-16 12:18:12.619  4575  4755 E         : 	... 24 more
09-16 12:18:12.619  4575  4755 E         : 
,09-16 12:18:12.629  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:12.809  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:12.989  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:13.169  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:13.349  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:13.529  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:13.619  3436  5955 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,09-16 12:18:13.709  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:13.759  9186  9250 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 12:18:13.759  9186  9250 I jxcore-log: 
,09-16 12:18:13.759  9186  9250 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 12:18:13.759  9186  9250 I jxcore-log: 
,09-16 12:18:13.759  9186  9250 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 12:18:13.759  9186  9250 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:18:13.759  9186  9250 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:18:13.759  9186  9250 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-16 12:18:13.759  9186  9250 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 12:18:13.759  9186  9250 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 12:18:13.759  9186  9250 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 12:18:13.759  9186  9250 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 12:18:13.759  9186  9250 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 12:18:13.759  9186  9250 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:18:13.759  9186  9250 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 12:18:13.759  9186  9250 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 12:18:13.759  9186  9250 I jxcore-log: 
,09-16 12:18:13.759  9186  9250 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 12:18:13.759  9186  9250 I jxcore-log: 
,09-16 12:18:13.889  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:13.979  9186  9250 D executeNativeTests: Running unit tests
,09-16 12:18:13.989  9186  9250 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
,09-16 12:18:13.989  9186  9250 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-16 12:18:13.989  9186  9250 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-16 12:18:13.989  9186  9250 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-16 12:18:13.989  9186  9250 D com.test.thalitest.ThaliTestRunner: Total duration: 1 ms
09-16 12:18:13.989  9186  9250 I jxcore-log: *Native tests were executed*
09-16 12:18:13.989  9186  9250 I jxcore-log: 
,09-16 12:18:13.989  9186  9250 I jxcore-log: Total number of executed tests:  1
09-16 12:18:13.989  9186  9250 I jxcore-log: 
09-16 12:18:13.989  9186  9250 I jxcore-log: Number of passed tests:  1
09-16 12:18:13.989  9186  9250 I jxcore-log: 
09-16 12:18:13.989  9186  9250 I jxcore-log: Number of failed tests:  0
09-16 12:18:13.989  9186  9250 I jxcore-log: 
,09-16 12:18:13.989  9186  9250 I jxcore-log: Number of ignored tests:  0
09-16 12:18:13.989  9186  9250 I jxcore-log: 
09-16 12:18:13.989  9186  9250 I jxcore-log: Total duration:  1
09-16 12:18:13.989  9186  9250 I jxcore-log: 
09-16 12:18:13.989  9186  9250 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-16 12:18:13.989  9186  9250 I jxcore-log: 
09-16 12:18:13.989  9186  9250 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 12:18:13.989  9186  9250 I jxcore-log: 
,09-16 12:18:14.009  9186  9186 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-16 12:18:14.069  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:14.249  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:14.429  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:14.459  9256  9256 I FIPS_bssl: FIPS approved mode (1) | 9256 | app_process
,09-16 12:18:14.469  9256  9256 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-16 12:18:14.469  9256  9256 D AndroidRuntime: CheckJNI is OFF
09-16 12:18:14.469  9256  9256 D AndroidRuntime: readGMSProperty: start
09-16 12:18:14.469  9256  9256 D AndroidRuntime: readGMSProperty: already setted!!
09-16 12:18:14.469  9256  9256 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-16 12:18:14.469  9256  9256 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-16 12:18:14.469  9256  9256 D AndroidRuntime: readGMSProperty: end
09-16 12:18:14.469  9256  9256 D AndroidRuntime: addProductProperty: start
,09-16 12:18:14.489  3436  4512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-16 12:18:14.489  9256  9256 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 12:18:14.489  3436  4512 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-16 12:18:14.489  3436  4512 D BatteryService: online:4, current avg:-77, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-261
09-16 12:18:14.489  3436  4512 D BatteryService: stay LED for fully charged
09-16 12:18:14.489  3436  3436 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-16 12:18:14.489  3436  3436 I MotionRecognitionService: Plugged
,09-16 12:18:14.489  3436  3436 D MotionRecognitionService:   cableConnection= 1
09-16 12:18:14.489  3436  3436 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-16 12:18:14.489  3436  3436 D MotionRecognitionService: skip setTransmitPower. 
,09-16 12:18:14.499  3950  3950 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-16 12:18:14.499  3950  3950 D KeyguardUpdateMonitor: handleBatteryUpdate
09-16 12:18:14.499  3950  3950 D PowerUI : priorPlugType = 2 mPlugType =  2
,09-16 12:18:14.509  9256  9256 I Radio-JNI: register_android_hardware_Radio DONE
,09-16 12:18:14.509  9256  9256 E AffinityControl: AffinityControl: registerfunction enter
,09-16 12:18:14.509  4990  4990 D CommonServiceConfiguration: getStringValueSetting
,09-16 12:18:14.519  4721  4721 D BatteryController: saveBatteryData : level[100], status[5]
,09-16 12:18:14.519  9256  9256 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-16 12:18:14.519  4990  4990 D BatteryMonitor: new battery level: 100
,09-16 12:18:14.529  3436  3857 D PackageManager: START PACKAGE DELETE: observer{104869270}
09-16 12:18:14.529  3436  3857 D PackageManager: pkg{<packageName>}
09-16 12:18:14.529  3436  3857 D PackageManager: user{0}
09-16 12:18:14.529  3436  3857 D PackageManager: caller{2000}
09-16 12:18:14.529  3436  3857 D PackageManager: flags{2}
,09-16 12:18:14.529  3436  3857 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-16 12:18:14.529  3436  3857 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-16 12:18:14.529  3436  3857 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-16 12:18:14.529  3436  3857 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-16 12:18:14.529  3436  3857 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-16 12:18:14.529  3436  3562 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-16 12:18:14.529  3436  3562 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,09-16 12:18:14.529  3436  3562 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-16 12:18:14.529  3436  3562 D ApplicationPolicy: getApplicationUninstallationEnabled
09-16 12:18:14.529  3436  3562 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-16 12:18:14.529  3436  3562 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-16 12:18:14.539  3436  3562 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-16 12:18:14.539  3436  3562 D PackageManager: !@killApplicatoin: 10177, uninstall pkg
09-16 12:18:14.539  3436  3562 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-16 12:18:14.539  3436  3510 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=-1: uninstall pkg
09-16 12:18:14.539  3436  3562 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
09-16 12:18:14.539  3436  3510 I ActivityManager: Killing 9186:com.test.thalitest/u0a177 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-16 12:18:14.549  3436  3510 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
09-16 12:18:14.549  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-16 12:18:14.549  3950  3950 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-16 12:18:14.549  3436  3510 D ActivityManager: mDVFSHelper.acquire()
,09-16 12:18:14.569  3436  3562 D AASAinstall: there is not AASApackages.xml file
,09-16 12:18:14.569  9266  9266 E Zygote  : v2
09-16 12:18:14.569  9266  9266 I libpersona: KNOX_SDCARD checking this for 10177
09-16 12:18:14.569  9266  9266 I libpersona: KNOX_SDCARD not a persona
,09-16 12:18:14.579  9266  9266 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
,09-16 12:18:14.579  9266  9266 E Zygote  : accessInfo : 0
09-16 12:18:14.579  3436  3510 I ActivityManager: Start proc 9266:com.test.thalitest/u0a177 for activity com.test.thalitest/.MainActivity
09-16 12:18:14.579  9266  9266 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,09-16 12:18:14.579  3436  3510 I ActivityManager:   Force finishing activity ActivityRecord{5f1cef1 u0 com.test.thalitest/.MainActivity t75}
09-16 12:18:14.579  3436  3510 W VirtualScreenManagerService: moveTaskBackToDisplayIfNeeded(): top activity or app is null
,09-16 12:18:14.599  9266  9266 D TimaKeyStoreProvider: TimaSignature is unavailable
09-16 12:18:14.599  9266  9266 D ActivityThread: Added TimaKeyStore provider
,09-16 12:18:14.609  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:14.679  3436  4393 D GraphicsStats: Buffer count: 7
09-16 12:18:14.679  3436  5007 I WindowState: WIN DEATH: Window{c3165c5 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-16 12:18:14.679  3436  4166 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@61c8aed)
,09-16 12:18:14.679  3436  3871 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-16 12:18:14.679  3436  3871 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-16 12:18:14.689  3009  3020 I SurfaceFlinger: id=20 Removed NainActivit (6/10)
,09-16 12:18:14.689  3436  3871 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-16 12:18:14.789  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:14.839  3436  3562 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-16 12:18:14.899  3436  3562 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-16 12:18:14.909  3165  3165 W keystore: ENTER clear_uid from uid 1000 for 10177
,09-16 12:18:14.909  3436  3562 I art     : Starting a blocking GC Explicit
09-16 12:18:14.909  3436  3536 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-16 12:18:14.919  3436  3536 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-16 12:18:14.919  3436  3536 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
09-16 12:18:14.919  3436  3536 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
,09-16 12:18:14.919  3436  3536 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4338)
09-16 12:18:14.919  3436  3536 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
,09-16 12:18:14.919  3436  3536 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,09-16 12:18:14.919  3436  3536 W System.err: 	at android.os.Looper.loop(Looper.java:158)
,09-16 12:18:14.919  3436  3536 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 12:18:14.919  3436  3536 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-16 12:18:14.919  3436  3536 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 12:18:14.919  3436  3536 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ec3e8e9 V.E...... R.....ID 0,0-0,0}
09-16 12:18:14.929  3009  3009 I SurfaceFlinger: id=21 createSurf (1528x2641),1 flag=4, VSBConnecti
,09-16 12:18:14.939  3436  3536 W WindowManager: Failed looking up window
09-16 12:18:14.939  3436  3536 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@797596e does not exist
09-16 12:18:14.939  3436  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService.pokeDrawLock(WindowManagerService.java:5176)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at com.android.server.wm.Session.pokeDrawLock(Session.java:505)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at android.view.ViewRootImpl.pokeDrawLockIfNeeded(ViewRootImpl.java:1203)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at android.view.ViewRootImpl.scheduleTraversals(ViewRootImpl.java:1415)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at android.view.ViewRootImpl.requestLayout(ViewRootImpl.java:1222)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:800)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:337)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:91)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4378)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13481)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 12:18:14.939  3436  3536 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-16 12:18:14.939  3436  3536 D ISSUE_DEBUG: InputChannelName : 1c4c80f Starting com.test.thalitest
,09-16 12:18:14.959  4317  4317 D Launcher: onRestart, Launcher: 23071528
,09-16 12:18:14.969  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:14.989  3436  3857 V WindowStateAnimator: Finishing drawing window Window{43678b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-16 12:18:14.989  6023  6023 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,09-16 12:18:14.989  6023  6023 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,09-16 12:18:15.019  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe4d68508
,09-16 12:18:15.119  3436  3562 I art     : Explicit concurrent mark sweep GC freed 272492(17MB) AllocSpace objects, 66(3MB) LOS objects, 32% free, 33MB/49MB, paused 1.640ms total 209.079ms
,09-16 12:18:15.149  3436  3562 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-16 12:18:15.149  3436  3562 D AASAuninstall: userId = 0, info.removedAppID = 10177, info.uid = 10177, packageName = com.test.thalitest
,09-16 12:18:15.149  3436  3562 D AASAinstall: there is not AASApackages.xml file
09-16 12:18:15.149  3436  3562 D PackageManager: result of delete: 1{104869270}
,09-16 12:18:15.149  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
09-16 12:18:15.149  9256  9256 I art     : System.exit called, status: 0
09-16 12:18:15.149  9256  9256 I AndroidRuntime: VM exiting with result code 0.
09-16 12:18:15.149  3436  3562 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-16 12:18:15.149  3436  3562 D PackageManager: userId{-1}
09-16 12:18:15.149  3436  3562 D PackageManager: andCode{true}
,09-16 12:18:15.259  3436  3510 I WindowManager: Screenshot max retries 4 of Token{9400c02 ActivityRecord{734394d u0 com.samsung.android.MtpApplication/.USBConnection t74}} appWin=Window{43678b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=2
,09-16 12:18:15.259  5689  5700 I TrayUsageStatesWatcher: notePauseComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,09-16 12:18:15.259  3436  3436 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,09-16 12:18:15.259  5689  5699 I TrayUsageStatesWatcher: noteResumeComponent : ComponentInfo{com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} Intent { flg=0x10800000 cmp=com.samsung.android.MtpApplication/.USBConnection VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,09-16 12:18:15.279  3436  3510 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-16 12:18:15.279  3436  4512 I ActivityManager: Killing 7753:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,09-16 12:18:15.299  4317  4317 D Launcher: onStart, Launcher: 23071528
09-16 12:18:15.299  4317  4317 D Launcher.HomeView: onStart
,09-16 12:18:15.309  4317  4317 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
,09-16 12:18:15.309  4317  4317 V ActivityThread: updateVisibility : ActivityRecord{76f4ee token=android.os.BinderProxy@aa56b27 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,09-16 12:18:15.309  4317  4317 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 684 440 span 2 1 (widgetid 2) [current Gridsize : GRID_4x4]
09-16 12:18:15.309  4317  4317 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Pogoda(widget id = 2) result hostview size = 684 x 440
09-16 12:18:15.309  4317  4317 D LauncherAppWidgetHostView: setResizeScaleResult() 684/ 440 scaleToResize = 1.0(widget id = 2)
,09-16 12:18:15.309  4317  4317 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 3) [current Gridsize : GRID_4x4]
,09-16 12:18:15.309  9266  9266 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,09-16 12:18:15.309  4317  4317 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Aplikacja Google(widget id = 3) result hostview size = 1372 x 440
09-16 12:18:15.309  4317  4317 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 3)
,09-16 12:18:15.309  4317  4317 V LauncherAppWidgetHostView: calculateWidgetSize: (target widgetsize)  using w/h 1372 440 span 4 1 (widgetid 4) [current Gridsize : GRID_4x4]
09-16 12:18:15.309  4317  4317 D LauncherAppWidgetHostView: calculateWidgetSize() widget = Galaxy Essentials(widget id = 4) result hostview size = 1372 x 440
09-16 12:18:15.309  9266  9266 D RelationGraph: garbageCollect()
09-16 12:18:15.319  9266  9266 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-16 12:18:15.309  4317  4317 D LauncherAppWidgetHostView: setResizeScaleResult() 1372/ 440 scaleToResize = 1.0(widget id = 4)
,09-16 12:18:15.319  3436  3981 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,09-16 12:18:15.319  3436  3510 D InputDispatcher: Focused application released
09-16 12:18:15.319  9266  9266 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,09-16 12:18:15.329  9266  9266 W asset   : Asset path /data/app/com.test.thalitest-1/base.apk is neither a directory nor file (type=1).
,09-16 12:18:15.329  9266  9266 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
09-16 12:18:15.329  9266  9266 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,09-16 12:18:15.329  3009  3009 I SurfaceFlinger: id=22 createSurf (1440x2560),1 flag=4, MauncherAct
09-16 12:18:15.329  3436  3798 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=545460846592, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
,09-16 12:18:15.339  9266  9266 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
09-16 12:18:15.339  9266  9266 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,09-16 12:18:15.339  3436  4565 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,09-16 12:18:15.349  3436  3452 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-16 12:18:15.349  3436  3452 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 12:18:15.349  3436  3436 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-16 12:18:15.349  3436  3562 I ActivityManager: Force stopping com.test.thalitest appid=10177 user=0: pkg removed
,09-16 12:18:15.349  3436  3562 I ActivityManager: Killing 9266:com.test.thalitest/u0a177 (adj 9): stop com.test.thalitest cause pkg removed
,09-16 12:18:15.349  8708  9281 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-16 12:18:15.349  3436  4566 V WindowStateAnimator: Finishing drawing window Window{43678b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
09-16 12:18:15.359  3436  3536 W WindowManager: Failed looking up window
09-16 12:18:15.359  3436  3536 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@797596e does not exist
09-16 12:18:15.359  3436  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14795)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService.relayoutWindow(WindowManagerService.java:5208)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at com.android.server.wm.Session.relayout(Session.java:208)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.view.ViewRootImpl.relayoutWindow(ViewRootImpl.java:6690)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1994)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1437)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:7403)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:920)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.view.Choreographer.doCallbacks(Choreographer.java:695)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.view.Choreographer.doFrame(Choreographer.java:631)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:906)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.os.Handler.handleCallback(Handler.java:739)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 12:18:15.359  3436  3536 E ViewSystem: ViewRootImpl #2 Surface is not valid.
09-16 12:18:15.359  3436  3536 D ViewRootImpl: #3 mView = null
09-16 12:18:15.359  3436  3536 W WindowManager: Failed looking up window
09-16 12:18:15.359  3436  3536 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@797596e does not exist
09-16 12:18:15.359  3436  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14804)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14795)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:4612)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:196)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3754)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:6893)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:4238)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 12:18:15.359  3436  3536 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 12:18:15.359  4317  4596 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
09-16 12:18:15.359  3436  3436 I KnoxTimeoutHandler: Shared devices show user statefalse
09-16 12:18:15.359  3436  3436 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
09-16 12:18:15.359  3009  3009 I SurfaceFlinger: id=23 createSurf (1592x384),1 flag=4, VSBConnecti
09-16 12:18:15.359  8708  9281 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
09-16 12:18:15.369  8708  9281 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
09-16 12:18:15.369  3436  3562 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON

```
