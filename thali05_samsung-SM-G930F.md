#### Test 856066048ca4f27_thali05_samsung-SM-G930F Logs


```
--------- beginning of main
09-21 10:30:33.339  3153  3637 D EnterpriseController: netId is 0
09-21 10:30:33.339  3153  3637 D Netd    : getNetworkForDns: using netid 0 for uid 10001
09-21 10:30:33.349  4545  4720 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/categories
09-21 10:30:33.349  4545  4720 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-21 10:30:33.349  4545  4720 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
09-21 10:30:33.349  4545  4720 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
09-21 10:30:33.349  4545  4720 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
09-21 10:30:33.349  4545  4720 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
09-21 10:30:33.349  4545  4720 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-21 10:30:33.349  4545  4720 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-21 10:30:33.349  4545  4720 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-21 10:30:33.349  4545  4720 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-21 10:30:33.349  4545  4720 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
09-21 10:30:33.349  4545  4720 E         : 	at java.lang.Thread.run(Thread.java:818)
09-21 10:30:33.349  4545  4720 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-21 10:30:33.349  4545  4720 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
09-21 10:30:33.349  4545  4720 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
09-21 10:30:33.349  4545  4720 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
09-21 10:30:33.349  4545  4720 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
09-21 10:30:33.349  4545  4720 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
09-21 10:30:33.349  4545  4720 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
09-21 10:30:33.349  4545  4720 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
09-21 10:30:33.349  4545  4720 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
09-21 10:30:33.349  4545  4720 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
09-21 10:30:33.349  4545  4720 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
09-21 10:30:33.349  4545  4720 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
09-21 10:30:33.349  4545  4720 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
09-21 10:30:33.349  4545  4720 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
09-21 10:30:33.349  4545  4720 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
09-21 10:30:33.349  4545  4720 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
09-21 10:30:33.349  4545  4720 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
09-21 10:30:33.349  4545  4720 E         : 	... 9 more
09-21 10:30:33.349  4545  4720 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
09-21 10:30:33.349  4545  4720 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
09-21 10:30:33.349  4545  4720 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
09-21 10:30:33.349  4545  4720 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
09-21 10:30:33.349  4545  4720 E         : 	... 24 more
09-21 10:30:33.349  4545  4720 E         : 
--------- beginning of system
09-21 10:30:33.429  3403  3516 I ActivityManager: Waited long enough for: ServiceRecord{72ad8ca u0 com.sec.android.daemonapp/.appservice.WeatherService}
09-21 10:30:33.619  3403  4290 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-21 10:30:33.619  3403  4290 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4316, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
09-21 10:30:33.619  3403  4290 D BatteryService: online:4, current avg:-8, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:53
09-21 10:30:33.619  3403  3403 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-21 10:30:33.629  3403  3403 I MotionRecognitionService: Plugged
09-21 10:30:33.629  3403  3403 D MotionRecognitionService:   cableConnection= 1
09-21 10:30:33.629  3403  3403 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-21 10:30:33.629  3403  3403 D MotionRecognitionService: skip setTransmitPower. 
09-21 10:30:33.639  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-21 10:30:33.639  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
09-21 10:30:33.649  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
09-21 10:30:33.649  3931  3931 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
09-21 10:30:33.649  3931  3931 D PowerUI.Notification: There is no change about charging status, so return!
09-21 10:30:33.669  4962  4962 D CommonServiceConfiguration: getStringValueSetting
09-21 10:30:33.679  4962  4962 D BatteryMonitor: new battery level: 100
09-21 10:30:33.689  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-21 10:30:33.689  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-21 10:30:35.189  9042  9042 I FIPS_bssl: FIPS approved mode (1) | 9042 | app_process
09-21 10:30:35.199  9042  9042 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 10:30:35.199  9042  9042 D AndroidRuntime: CheckJNI is OFF
09-21 10:30:35.199  9042  9042 D AndroidRuntime: readGMSProperty: start
09-21 10:30:35.199  9042  9042 D AndroidRuntime: readGMSProperty: already setted!!
09-21 10:30:35.199  9042  9042 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-21 10:30:35.199  9042  9042 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-21 10:30:35.199  9042  9042 D AndroidRuntime: readGMSProperty: end
09-21 10:30:35.199  9042  9042 D AndroidRuntime: addProductProperty: start
09-21 10:30:35.219  9042  9042 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 10:30:35.239  9042  9042 I Radio-JNI: register_android_hardware_Radio DONE
09-21 10:30:35.249  9042  9042 E AffinityControl: AffinityControl: registerfunction enter
09-21 10:30:35.249  9042  9042 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-21 10:30:35.289  3403  3979 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
09-21 10:30:35.289  3403  3979 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
09-21 10:30:35.309  3403  3979 D ResourcesManager: For user 0 new overlays fetched Null
09-21 10:30:35.319  3403  3979 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 10:30:35.319  3403  3979 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
09-21 10:30:35.319  3403  3979 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3403  pkgName : ACTIVITY_RESUME_BOOSTER@3
09-21 10:30:35.319  3403  3979 D ActivityManager: mDVFSHelper.acquire()
09-21 10:30:35.319  3403  3979 D FocusedStackFrame: Set to : 0
09-21 10:30:35.319  3403  3979 V WindowManager: addAppToken: AppWindowToken{d0a3f9e7 token=Token{d7f4ba6 ActivityRecord{917e101 u0 com.test.thalitest/.MainActivity t4}}} to stack=2 task=4 at 0
09-21 10:30:35.319  4263  4263 D Launcher: onPause, Launcher: 126871873
09-21 10:30:35.319  4263  4263 D Launcher.HomeView: onPause
09-21 10:30:35.319  4263  4263 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
09-21 10:30:35.319  3403  3979 D InputDispatcher: Focused application set to: xxxx
09-21 10:30:35.319  3403  3979 D InputDispatcher: Focus left window: 4263
09-21 10:30:35.319  9042  9042 D AndroidRuntime: Shutting down VM
09-21 10:30:35.329  3403  3546 I InjectionManager: Inside getClassLibPath caller 
09-21 10:30:35.329  3403  3546 D SecWifiDisplayUtil: Metadata value : SecSettings2
09-21 10:30:35.329  3403  3546 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{e5c3edf V.E...... R.....ID 0,0-0,0}
09-21 10:30:35.329  3403  3546 D ISSUE_DEBUG: InputChannelName : ca205f5 Starting com.test.thalitest
09-21 10:30:35.329  3403  3546 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3403 uid:1000
09-21 10:30:35.329  3403  3546 D PointerIcon: setMouseCustomIcon IconType is same.101
09-21 10:30:35.329  3005  3005 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
09-21 10:30:35.339  9051  9051 E Zygote  : v2
09-21 10:30:35.339  9051  9051 I libpersona: KNOX_SDCARD checking this for 10171
09-21 10:30:35.339  9051  9051 I libpersona: KNOX_SDCARD not a persona
09-21 10:30:35.339  9051  9051 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0013
09-21 10:30:35.339  3403  4378 I ActivityManager: Start proc 9051:com.test.thalitest/u0a171 for activity com.test.thalitest/.MainActivity
09-21 10:30:35.339  9051  9051 E Zygote  : accessInfo : 0
09-21 10:30:35.339  9051  9051 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-21 10:30:35.349  3403  3546 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
09-21 10:30:35.349  4397  4408 W SearchService: Abort, client detached.
09-21 10:30:35.359  4397  9026 I DeviceStateChecker: DeviceStateChecker cancelled
09-21 10:30:35.359  4397  4397 I MicroDetector: Keeping mic open: false
09-21 10:30:35.359  4397  4397 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@69fe1ed
09-21 10:30:35.359  4397  9028 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-21 10:30:35.359  9051  9051 D TimaKeyStoreProvider: TimaSignature is unavailable
09-21 10:30:35.359  9051  9051 D ActivityThread: Added TimaKeyStore provider
09-21 10:30:35.369  3403  4712 V WindowOrientationListener: setCurrentAppOrientation :-1
09-21 10:30:35.369  3403  4712 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
09-21 10:30:35.369  3403  4712 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
09-21 10:30:35.369  3403  4712 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
09-21 10:30:35.369  3403  4712 D ActivityManager:  Launching com.test.thalitest, updated priority
09-21 10:30:35.369  3161  4452 I APM::AudioPolicyManager: stopInput() input 28
09-21 10:30:35.369  4397  9010 I MicroRecognitionRunner: Stopping hotword detection.
09-21 10:30:35.369  3403  3403 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
09-21 10:30:35.369  4397  9027 I MicroRecognitionRunner: Detection finished
09-21 10:30:35.369  3161  9030 I audio_hw_primary: do_in_standby : in->standby 0
09-21 10:30:35.369  3403  3546 V WindowStateAnimator: Finishing drawing window Window{ca205f5 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-21 10:30:35.379  3403  3516 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-21 10:30:35.379  3161  9030 V audio_hw_primary: select_devices output_scenario:-1 input_scenario:-1 out_snd_device 0x0 in_snd_device:0x0
09-21 10:30:35.379  3161  9030 I audio_route: 
09-21 10:30:35.379  3161  9030 I audio_route: > audio_route_reset :
09-21 10:30:35.379  3161  9030 I audio_route: 
09-21 10:30:35.379  3161  9030 I audio_route: > audio_route_update_mixer : +
09-21 10:30:35.379  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7fe1b3ee58
09-21 10:30:35.379  3403  3516 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7da0c71 u0 update-hint qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d1ed21d 4397:com.google.android.googlequicksearchbox:search/u0a68}
09-21 10:30:35.379  3403  3518 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{ca205f5 u0 d0 Starting com.test.thalitest}
09-21 10:30:35.379  3403  3857 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
09-21 10:30:35.389  9051  9051 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 10:30:35.389  3005  4427 I SurfaceFlinger: Modify Choreographer's phase offset to 0
09-21 10:30:35.389  3403  4275 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
09-21 10:30:35.389  9051  9051 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
09-21 10:30:35.389  3005  3072 I SurfaceFlinger: Modify SurfaceFlinger's phase offset to 0
09-21 10:30:35.389  3403  5797 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 10:30:35.389  3005  3014 D libEGL  : eglTerminate EGLDisplay = 0x7f77c00e78
09-21 10:30:35.389  3403  5797 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 10:30:35.389  3005  3014 D libEGL  : eglTerminate EGLDisplay = 0x7f77c00e78
09-21 10:30:35.399  9051  9051 D ResourcesManager: For user 0 new overlays fetched Null
09-21 10:30:35.399  9051  9051 I InjectionManager: Inside getClassLibPath caller 
09-21 10:30:35.409  3161  9030 I audio_route: > audio_route_update_mixer : changed(5) -
09-21 10:30:35.409  3161  9030 I audio_hw_primary: select_devices - 
09-21 10:30:35.409  3161  3652 V audio_hw_primary: stop_voice_note_recording
09-21 10:30:35.409  3161  3652 E audio_hw_primary: adev_close_input_stream, set jack_in to null
09-21 10:30:35.409  9051  9051 D InjectionManager: InjectionManager
09-21 10:30:35.409  9051  9051 D InjectionManager: fillFeatureStoreMap com.test.thalitest
09-21 10:30:35.409  3403  5797 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-21 10:30:35.409  9051  9051 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
09-21 10:30:35.409  9051  9051 I InjectionManager: featureStore :{}
09-21 10:30:35.409  3403  5797 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 10:30:35.409  3403  5797 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
09-21 10:30:35.409  3403  5797 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 10:30:35.409  3403  5797 D GameManagerService: identifyGamePackage. com.test.thalitest
09-21 10:30:35.419  9051  9051 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 10:30:35.419  9051  9051 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
09-21 10:30:35.419  9051  9051 D RelationGraph: garbageCollect()
09-21 10:30:35.419  9051  9051 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
09-21 10:30:35.439  9051  9051 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310550)
09-21 10:30:35.459  9051  9051 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
09-21 10:30:35.459  9051  9051 D ResourcesManager: For user 0 new overlays fetched Null
09-21 10:30:35.459  9051  9051 I InjectionManager: Inside getClassLibPath caller 
09-21 10:30:35.459  9051  9051 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-21 10:30:35.499  9051  9051 I cr_LibraryLoader: Time to load native libraries: 23 ms (timestamps 6248-6271)
09-21 10:30:35.499  9051  9051 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
09-21 10:30:35.529  9051  9065 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-21 10:30:35.539  9051  9051 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ccf6c12}
09-21 10:30:35.539  9051  9051 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,09-21 10:30:35.559  9051  9051 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,09-21 10:30:35.569  9051  9051 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,09-21 10:30:35.629  3403  3881 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,09-21 10:30:35.699  9051  9067 W chromium: [WARNING:dns_config_service_posix.cc(306)] Failed to read DnsConfig.
,09-21 10:30:35.729  9051  9051 D libEGL  : eglInitialize EGLDisplay = 0xffaa54dc
,09-21 10:30:35.729  3403  3881 I MdnieScenarioControlService: mGameModeLauncher : false
,09-21 10:30:35.729  3403  3881 I MdnieScenarioControlService: setUIMode
,09-21 10:30:35.749  3005  4427 I SurfaceFlinger: id=9 Removed MauncherAct (4/10)
09-21 10:30:35.749  3005  3014 I SurfaceFlinger: id=9 Removed MauncherAct (-2/10)
,09-21 10:30:35.749  3931  3931 D ImageWallpaper: onVisibilityChanged:false
,09-21 10:30:35.759  3931  3931 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
09-21 10:30:35.759  3931  3931 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
09-21 10:30:35.759  3931  3931 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,09-21 10:30:35.759  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fe1b3ef78
,09-21 10:30:35.779  3403  4275 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10171
,09-21 10:30:35.779  3403  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29734 com.android.server.am.ActivityManagerService.registerReceiver:22599 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,09-21 10:30:35.789  3403  3857 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,09-21 10:30:35.819  9051  9051 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-21 10:30:35.829  9051  9051 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-21 10:30:35.829  9051  9051 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-21 10:30:35.839  9051  9051 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-21 10:30:35.859  9051  9051 D Activity: performCreate Call Injection manager
,09-21 10:30:35.869  9051  9051 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,09-21 10:30:35.869  9051  9051 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-21 10:30:35.879  9051  9051 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{db62c40 I.E...... R.....ID 0,0-0,0}
,09-21 10:30:35.879  9051  9102 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-21 10:30:35.879  3403  4712 D ISSUE_DEBUG: InputChannelName : 815a024 com.test.thalitest/com.test.thalitest.MainActivity
,09-21 10:30:35.879  3403  4405 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,09-21 10:30:35.889  3403  4405 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 10:30:35.889  3403  3403 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-21 10:30:35.889  3403  3403 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-21 10:30:35.889  9051  9065 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,09-21 10:30:35.899  9051  9051 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10171, CallingPid : 9051
,09-21 10:30:35.899  3403  4275 D ConnectivityService: listenForNetwork for Listen from uid/pid:10171/9051 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-21 10:30:35.909  3403  3857 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,09-21 10:30:35.909  9051  9051 D SecWifiDisplayUtil: Metadata value : SecSettings2
,09-21 10:30:35.919  3005  3005 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,09-21 10:30:35.929  3403  4874 D InputDispatcher: Focus entered window: 9051
,09-21 10:30:35.929  3403  3546 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3403 uid:1000
09-21 10:30:35.929  3403  3546 D PointerIcon: setMouseCustomIcon IconType is same.101
09-21 10:30:35.929  9051  9102 D libEGL  : eglInitialize EGLDisplay = 0xdc17f7c4
09-21 10:30:35.929  9051  9102 I OpenGLRenderer: Initialized EGL, version 1.4
,09-21 10:30:35.939  9051  9102 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,09-21 10:30:35.939  9051  9051 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-21 10:30:35.979  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7fe1b3ee58
,09-21 10:30:35.979  3403  4217 V WindowStateAnimator: Finishing drawing window Window{815a024 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-21 10:30:35.979  9051  9051 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,09-21 10:30:35.979  3403  4405 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-21 10:30:35.989  3403  3546 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-21 10:30:35.989  3403  3403 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-21 10:30:35.989  3403  3546 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +655ms
09-21 10:30:35.989  3403  3546 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3403  tag : ACTIVITY_RESUME_BOOSTER@3
,09-21 10:30:35.989  3403  3546 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{917e101 u0 com.test.thalitest/.MainActivity t4} time:186763
09-21 10:30:35.989  3403  3546 D ActivityManager: mDVFSHelper.release()
09-21 10:30:35.989  3403  3546 D ViewRootImpl: #3 mView = null
09-21 10:30:35.989  3403  3516 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3403  pkgName : ACTIVITY_RESUME_BOOSTER@9
09-21 10:30:35.989  3403  3403 I KnoxTimeoutHandler: SD activityfalse
,09-21 10:30:35.999  7108  7108 D SamsungIME: IMPL finishInput
09-21 10:30:35.999  7108  7108 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
09-21 10:30:35.999  7108  7108 D SamsungIME: saveAndClear +
09-21 10:30:35.999  7108  7108 D SamsungIME: saveAndClear -
,09-21 10:30:35.999  9051  9108 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 10:30:35.999  9051  9108 D libEGL  : eglInitialize EGLDisplay = 0xdb63f3f4
,09-21 10:30:35.999  3403  4756 V WindowStateAnimator: Finishing drawing window Window{815a024 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,09-21 10:30:35.999  9051  9051 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@79bae61 time:186779
,09-21 10:30:36.009  4263  4263 D Launcher.HomeView: onStop
09-21 10:30:36.009  4263  4263 D capture : ----destroy
,09-21 10:30:36.009  4263  4263 V ActivityThread: updateVisibility : ActivityRecord{4dad0c0 token=android.os.BinderProxy@3ccced4 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
,09-21 10:30:36.009  9051  9108 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,09-21 10:30:36.009  3403  3857 D NetworkPolicy: isUidForegroundLocked: 10068, mScreenOn: true, uidstate: 3, mProxSensorScreenOff: false
,09-21 10:30:36.019  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7fe1b3ee58
,09-21 10:30:36.019  4263  4263 D Launcher: onTrimMemory. Level: 20
,09-21 10:30:36.019  9051  9051 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9051
,09-21 10:30:36.049  3005  3005 D libEGL  : eglInitialize EGLDisplay = 0x7fe1b3ee58
,09-21 10:30:36.149  9051  9051 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-21 10:30:36.189  3005  3016 I SurfaceFlinger: id=20 Removed uhalitest (6/10)
,09-21 10:30:36.189  3005  3014 I SurfaceFlinger: id=20 Removed uhalitest (-2/10)
,09-21 10:30:36.199  3005  3005 D libEGL  : eglTerminate EGLDisplay = 0x7fe1b3ef78
,09-21 10:30:36.209  9051  9115 D jxcore_app_log: JniHelper::setJavaVM(0xf4874000), pthread_self() = -761231056
,09-21 10:30:36.209  9051  9115 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 10:30:36.209  9051  9115 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 10:30:36.209  9051  9115 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 10:30:36.209  9051  9115 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 10:30:36.209  9051  9115 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-21 10:30:36.209  9051  9115 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3208522 added. We now have 1 listener(s)
,09-21 10:30:36.219  9051  9115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,09-21 10:30:36.219  9051  9115 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:78:3E:94:4A:3E"
09-21 10:30:36.219  9051  9115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 10:30:36.219  9051  9115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:78:3E:94:4A:3E
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-21 10:30:36.219  9051  9115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9 added. We now have 1 listener(s)
09-21 10:30:36.219  9051  9115 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 10:30:36.219  9051  9115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 10:30:36.219  9051  9115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-21 10:30:36.219  9051  9115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-21 10:30:36.219  9051  9115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 10:30:36.219  9051  9115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-21 10:30:36.219  9051  9115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 10:30:36.219  9051  9115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
09-21 10:30:36.219  9051  9115 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:30:36.219  9051  9115 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:30:36.219  9051  9115 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:30:36.219  9051  9115 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-21 10:30:36.219  9051  9115 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 10:30:36.219  9051  9115 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:30:36.219  9051  9115 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:30:36.219  9051  9115 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:30:36.219  9051  9115 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:30:36.219  9051  9115 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-21 10:30:36.219  9051  9115 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 10:30:36.219  9051  9115 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-21 10:30:36.239  9051  9051 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-21 10:30:36.269  3403  3881 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,09-21 10:30:36.289  3403  3403 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3403  tag : ACTIVITY_RESUME_BOOSTER@9
,09-21 10:30:36.349  4022  4022 D Recents : onTaskStackChanged
,09-21 10:30:36.349  3153  3637 D EnterpriseController: netId is 0
09-21 10:30:36.349  3153  3637 D Netd    : getNetworkForDns: using netid 0 for uid 10001
,09-21 10:30:36.359  4545  4720 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/categories
09-21 10:30:36.359  4545  4720 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-21 10:30:36.359  4545  4720 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
09-21 10:30:36.359  4545  4720 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
09-21 10:30:36.359  4545  4720 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
09-21 10:30:36.359  4545  4720 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
09-21 10:30:36.359  4545  4720 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-21 10:30:36.359  4545  4720 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-21 10:30:36.359  4545  4720 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-21 10:30:36.359  4545  4720 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-21 10:30:36.359  4545  4720 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
09-21 10:30:36.359  4545  4720 E         : 	at java.lang.Thread.run(Thread.java:818)
09-21 10:30:36.359  4545  4720 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
09-21 10:30:36.359  4545  4720 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
09-21 10:30:36.359  4545  4720 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
09-21 10:30:36.359  4545  4720 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
09-21 10:30:36.359  4545  4720 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
09-21 10:30:36.359  4545  4720 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
09-21 10:30:36.359  4545  4720 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
09-21 10:30:36.359  4545  4720 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
09-21 10:30:36.359  4545  4720 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
09-21 10:30:36.359  4545  4720 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
09-21 10:30:36.359  4545  4720 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
09-21 10:30:36.359  4545  4720 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
09-21 10:30:36.359  4545  4720 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
09-21 10:30:36.359  4545  4720 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
09-21 10:30:36.359  4545  4720 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
09-21 10:30:36.359  4545  4720 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
09-21 10:30:36.359  4545  4720 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
09-21 10:30:36.359  4545  4720 E         : 	... 9 more
09-21 10:30:36.359  4545  4720 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
09-21 10:30:36.359  4545  4720 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
09-21 10:30:36.359  4545  4720 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
09-21 10:30:36.359  4545  4720 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
09-21 10:30:36.359  4545  4720 E         : 	... 24 more
09-21 10:30:36.359  4545  4720 E         : 
,09-21 10:30:36.359  4022  4022 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest

```
