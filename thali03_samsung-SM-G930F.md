#### Test 107380351ee7f847_thali03_samsung-SM-G930F Logs


```
--------- beginning of system
,02-23 11:45:51.801  3509  6386 D SSRM:n  : SIOP:: AP = 310, PST = 325 (W:14), CP = 274, CUR = 112, LCD = 99
02-23 11:45:52.041  3509  4426 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:45:52.041  3509  4426 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:45:52.041  3509  4426 D BatteryService: online:4, current avg:124, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:140
02-23 11:45:52.041  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
02-23 11:45:52.041  3509  3509 I MotionRecognitionService: Plugged
02-23 11:45:52.041  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:45:52.041  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:45:52.041  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
02-23 11:45:52.051  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
02-23 11:45:52.051  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:45:52.051  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
02-23 11:45:52.061  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:45:52.061  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:45:52.061  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
02-23 11:45:52.071  5384  5384 D CommonServiceConfiguration: getStringValueSetting
02-23 11:45:52.071  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:45:52.071  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
02-23 11:45:52.081  5384  5384 D BatteryMonitor: new battery level: 100
02-23 11:45:52.081  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
02-23 11:45:52.081  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
02-23 11:45:52.261  9836  9836 I FIPS_bssl: FIPS approved mode (1) | 9836 | app_process
02-23 11:45:52.271  9836  9836 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
02-23 11:45:52.271  9836  9836 D AndroidRuntime: CheckJNI is OFF
02-23 11:45:52.271  9836  9836 D AndroidRuntime: readGMSProperty: start
02-23 11:45:52.271  9836  9836 D AndroidRuntime: readGMSProperty: already setted!!
02-23 11:45:52.271  9836  9836 D AndroidRuntime: propertySet: couldn't set property (it is from app)
02-23 11:45:52.271  9836  9836 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
02-23 11:45:52.271  9836  9836 D AndroidRuntime: readGMSProperty: end
02-23 11:45:52.271  9836  9836 D AndroidRuntime: addProductProperty: start
02-23 11:45:52.291  9836  9836 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
02-23 11:45:52.311  9836  9836 I Radio-JNI: register_android_hardware_Radio DONE
02-23 11:45:52.321  9836  9836 E AffinityControl: AffinityControl: registerfunction enter
02-23 11:45:52.321  9836  9836 D AndroidRuntime: Calling main entry com.android.commands.am.Am
02-23 11:45:52.351  3509  4299 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
02-23 11:45:52.351  3509  4299 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
02-23 11:45:52.391  3509  4299 D ResourcesManager: For user 0 new overlays fetched Null
02-23 11:45:52.391  3509  4299 D GameManagerService: identifyGamePackage. com.test.thalitest
02-23 11:45:52.391  3509  4299 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
02-23 11:45:52.391  3509  4299 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3509  pkgName : ACTIVITY_RESUME_BOOSTER@3
02-23 11:45:52.391  3509  4299 D ActivityManager: mDVFSHelper.acquire()
02-23 11:45:52.391  3509  4299 V WindowManager: addAppToken: AppWindowToken{d02e2febe token=Token{b2c9179 ActivityRecord{d081e40 u0 com.test.thalitest/.MainActivity t5}}} to stack=2 task=5 at 0
02-23 11:45:52.411  3509  4299 D InputDispatcher: Focused application set to: xxxx
02-23 11:45:52.411  3509  4299 D InputDispatcher: Focus left window: 6467
02-23 11:45:52.411  3509  3579 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{57c0788 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
02-23 11:45:52.421  3944  3944 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
02-23 11:45:52.421  3509  3600 I InjectionManager: Inside getClassLibPath caller 
02-23 11:45:52.421  3509  3600 D SecWifiDisplayUtil: Metadata value : SecSettings2
02-23 11:45:52.421  3509  3600 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{44e2796 V.E...... R.....ID 0,0-0,0}
02-23 11:45:52.421  3509  3600 D ISSUE_DEBUG: InputChannelName : 4a68f04 Starting com.test.thalitest
02-23 11:45:52.421  9836  9836 D AndroidRuntime: Shutting down VM
02-23 11:45:52.431  3509  3600 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3509 uid:1000
02-23 11:45:52.431  3509  3600 D PointerIcon: setMouseCustomIcon IconType is same.101
02-23 11:45:52.431  9847  9847 E Zygote  : v2
02-23 11:45:52.431  9847  9847 I libpersona: KNOX_SDCARD checking this for 10074
02-23 11:45:52.431  9847  9847 I libpersona: KNOX_SDCARD not a persona
02-23 11:45:52.431  9847  9847 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
02-23 11:45:52.431  3509  3842 I ActivityManager: Start proc 9847:com.test.thalitest/u0a74 for activity com.test.thalitest/.MainActivity
02-23 11:45:52.431  9847  9847 E Zygote  : accessInfo : 0
02-23 11:45:52.431  9847  9847 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
02-23 11:45:52.431  3509  3859 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
02-23 11:45:52.431  3011  3011 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
02-23 11:45:52.451  9847  9847 D TimaKeyStoreProvider: TimaSignature is unavailable
02-23 11:45:52.451  9847  9847 D ActivityThread: Added TimaKeyStore provider
02-23 11:45:52.451  3509  3600 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
02-23 11:45:52.451  3509  4300 V WindowOrientationListener: setCurrentAppOrientation :-1
02-23 11:45:52.451  3509  4300 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
02-23 11:45:52.451  3509  4300 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
02-23 11:45:52.451  3509  4300 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
02-23 11:45:52.461  4287  4287 D Launcher.HomeView: onStop
02-23 11:45:52.461  4287  4287 D capture : ----destroy
02-23 11:45:52.461  3509  4300 D ActivityManager:  Launching com.test.thalitest, updated priority
02-23 11:45:52.461  4287  4287 V ActivityThread: updateVisibility : ActivityRecord{2f01796 token=android.os.BinderProxy@43447c3 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
02-23 11:45:52.461  3509  3509 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
02-23 11:45:52.471  3509  3578 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
02-23 11:45:52.471  3509  6386 D GameManagerService: identifyGamePackage. com.test.thalitest
02-23 11:45:52.471  3509  6386 D GameManagerService: identifyGamePackage. com.test.thalitest
02-23 11:45:52.471  9847  9847 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
02-23 11:45:52.471  3509  4843 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
02-23 11:45:52.471  9847  9847 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
02-23 11:45:52.471  3011  4330 D libEGL  : eglTerminate EGLDisplay = 0x7f770ffe78
02-23 11:45:52.471  3011  4330 D libEGL  : eglTerminate EGLDisplay = 0x7f770ffe78
02-23 11:45:52.481  3509  3600 V WindowStateAnimator: Finishing drawing window Window{4a68f04 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
02-23 11:45:52.481  9847  9847 D ResourcesManager: For user 0 new overlays fetched Null
02-23 11:45:52.481  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fdb4a8878
02-23 11:45:52.481  3509  3596 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
02-23 11:45:52.491  3509  6386 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
02-23 11:45:52.491  3509  6386 D GameManagerService: identifyGamePackage. com.test.thalitest
02-23 11:45:52.491  3509  3579 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{4a68f04 u0 d0 Starting com.test.thalitest}
02-23 11:45:52.491  9847  9847 I InjectionManager: Inside getClassLibPath caller 
02-23 11:45:52.491  3509  6386 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
02-23 11:45:52.491  3509  6386 D GameManagerService: identifyGamePackage. com.test.thalitest
02-23 11:45:52.491  3509  6386 D GameManagerService: identifyGamePackage. com.test.thalitest
02-23 11:45:52.491  4287  4287 D Launcher: onTrimMemory. Level: 20
02-23 11:45:52.501  3011  3021 D libEGL  : eglTerminate EGLDisplay = 0x7f7efc0e78
02-23 11:45:52.501  3011  3021 D libEGL  : eglTerminate EGLDisplay = 0x7f7efc0e78
02-23 11:45:52.501  9847  9847 D InjectionManager: InjectionManager
02-23 11:45:52.501  9847  9847 D InjectionManager: fillFeatureStoreMap com.test.thalitest
02-23 11:45:52.501  9847  9847 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
02-23 11:45:52.501  9847  9847 I InjectionManager: featureStore :{}
02-23 11:45:52.511  9847  9847 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
02-23 11:45:52.511  9847  9847 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
02-23 11:45:52.511  9847  9847 D RelationGraph: garbageCollect()
02-23 11:45:52.511  9847  9847 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
02-23 11:45:52.521  9847  9847 I CordovaLog: Changing log level to DEBUG(3)
02-23 11:45:52.521  9847  9847 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
02-23 11:45:52.521  9847  9847 D CordovaActivity: CordovaActivity.onCreate()
02-23 11:45:52.531  9847  9847 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
02-23 11:45:52.541  3509  3518 I art     : Background partial concurrent mark sweep GC freed 159164(14MB) AllocSpace objects, 72(1440KB) LOS objects, 30% free, 35MB/51MB, paused 1.281ms total 126.854ms
02-23 11:45:52.571  9847  9847 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
02-23 11:45:52.571  9847  9847 D ResourcesManager: For user 0 new overlays fetched Null
02-23 11:45:52.571  9847  9847 I InjectionManager: Inside getClassLibPath caller 
02-23 11:45:52.571  9847  9847 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
02-23 11:45:52.601  9847  9847 I cr_LibraryLoader: Time to load native libraries: 18 ms (timestamps 8249-8267)
02-23 11:45:52.601  9847  9847 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
02-23 11:45:52.621  9847  9862 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,02-23 11:45:52.651  9847  9847 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d5d8a4}
02-23 11:45:52.651  9847  9847 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,02-23 11:45:52.661  9847  9847 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,02-23 11:45:52.701  9847  9847 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,02-23 11:45:52.721  3509  3883 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,02-23 11:45:52.781  9847  9847 D libEGL  : eglInitialize EGLDisplay = 0xffbed7d4
,02-23 11:45:52.821  3509  3883 I MdnieScenarioControlService: mGameModeLauncher : false
,02-23 11:45:52.821  3509  4435 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10074
,02-23 11:45:52.821  3509  4435 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,02-23 11:45:52.831  3509  3883 I MdnieScenarioControlService: setUIMode
,02-23 11:45:52.841  3509  3859 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,02-23 11:45:52.861  9847  9847 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9847
,02-23 11:45:52.861  3011  4330 I SurfaceFlinger: id=9 Removed MauncherAct (4/13)
02-23 11:45:52.861  3011  3021 I SurfaceFlinger: id=9 Removed MauncherAct (-2/13)
,02-23 11:45:52.861  3011  3904 I SurfaceFlinger: id=17 Removed VSBConnecti (4/12)
02-23 11:45:52.861  3509  4435 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9847 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-23 11:45:52.861  3509  3870 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
02-23 11:45:52.861  3011  3023 I SurfaceFlinger: id=16 Removed VSBConnecti (5/11)
,02-23 11:45:52.861  3011  3023 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
02-23 11:45:52.861  3011  3023 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/11)
02-23 11:45:52.861  3509  3870 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,02-23 11:45:52.871  3944  3944 D ImageWallpaper: onVisibilityChanged:false
,02-23 11:45:52.871  3944  3944 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
02-23 11:45:52.871  3944  3944 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
02-23 11:45:52.871  3944  3944 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,02-23 11:45:52.871  3509  3870 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,02-23 11:45:52.871  3509  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-23 11:45:52.871  3509  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,02-23 11:45:52.871  3509  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-23 11:45:52.881  9847  9847 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,02-23 11:45:52.881  3509  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-23 11:45:52.881  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fdb4a8998
,02-23 11:45:52.881  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fdb4a8998
02-23 11:45:52.881  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fdb4a8998
,02-23 11:45:52.881  3509  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
02-23 11:45:52.881  3509  3870 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-23 11:45:52.891  9847  9847 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,02-23 11:45:52.891  9847  9847 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,02-23 11:45:52.911  9847  9847 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,02-23 11:45:52.911  9847  9847 D PluginManager: init()
,02-23 11:45:52.921  9847  9847 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,02-23 11:45:52.931  9847  9847 I cr_Ime  : ImeThread is not enabled.
,02-23 11:45:52.931  9847  9847 D Activity: performCreate Call Injection manager
,02-23 11:45:52.931  9847  9847 D CordovaActivity: Started the activity.
02-23 11:45:52.931  9847  9847 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
02-23 11:45:52.931  9847  9847 D CordovaActivity: Resumed the activity.
,02-23 11:45:52.931  9847  9847 D SecWifiDisplayUtil: Metadata value : SecSettings2
,02-23 11:45:52.941  9847  9847 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{426a7b3 I.E...... R.....ID 0,0-0,0}
,02-23 11:45:52.941  9847  9897 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,02-23 11:45:52.951  3509  4299 D ISSUE_DEBUG: InputChannelName : 5c3b6fc com.test.thalitest/com.test.thalitest.MainActivity
,02-23 11:45:52.951  3509  4411 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
02-23 11:45:52.951  3509  4411 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
02-23 11:45:52.951  3509  3509 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,02-23 11:45:52.951  3509  3509 I KnoxTimeoutHandler: Shared devices show user statefalse
,02-23 11:45:52.951  9847  9862 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
02-23 11:45:52.951  9847  9847 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9847
,02-23 11:45:52.951  3509  3856 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9847 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-23 11:45:52.961  3509  3870 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
02-23 11:45:52.961  3509  3870 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,02-23 11:45:52.961  3509  3870 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
02-23 11:45:52.961  3509  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
02-23 11:45:52.961  3509  3859 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
02-23 11:45:52.961  3509  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
02-23 11:45:52.971  3509  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
02-23 11:45:52.971  9847  9847 D SecWifiDisplayUtil: Metadata value : SecSettings2
02-23 11:45:52.971  3509  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
02-23 11:45:52.971  3509  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
02-23 11:45:52.971  3509  3870 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
02-23 11:45:52.971  3509  3870 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-23 11:45:52.981  3011  3011 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
02-23 11:45:52.981  3509  4172 D InputDispatcher: Focus entered window: 9847
02-23 11:45:52.981  3509  3600 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3509 uid:1000
02-23 11:45:52.981  3509  3600 D PointerIcon: setMouseCustomIcon IconType is same.101
02-23 11:45:52.981  9847  9897 D libEGL  : eglInitialize EGLDisplay = 0xdc3ff7c4
02-23 11:45:52.981  9847  9897 I OpenGLRenderer: Initialized EGL, version 1.4
02-23 11:45:52.991  9847  9897 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,02-23 11:45:52.991  9847  9847 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,02-23 11:45:53.021  9847  9901 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
02-23 11:45:53.021  9847  9901 D libEGL  : eglInitialize EGLDisplay = 0xd9d7f3e4
,02-23 11:45:53.021  9847  9901 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,02-23 11:45:53.031  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fdb4a8878
,02-23 11:45:53.031  3509  4300 V WindowStateAnimator: Finishing drawing window Window{5c3b6fc u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,02-23 11:45:53.031  9847  9847 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
02-23 11:45:53.031  3509  4411 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,02-23 11:45:53.031  3509  3600 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,02-23 11:45:53.041  3509  3600 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +619ms
02-23 11:45:53.041  3509  3509 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
02-23 11:45:53.041  3509  3600 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3509  tag : ACTIVITY_RESUME_BOOSTER@3
,02-23 11:45:53.041  3509  3600 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{d081e40 u0 com.test.thalitest/.MainActivity t5} time:178701
02-23 11:45:53.041  3509  3600 D ActivityManager: mDVFSHelper.release()
02-23 11:45:53.041  3509  3600 D ViewRootImpl: #3 mView = null
,02-23 11:45:53.041  3509  3578 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3509  pkgName : ACTIVITY_RESUME_BOOSTER@9
02-23 11:45:53.041  3509  3509 I KnoxTimeoutHandler: SD activityfalse
,02-23 11:45:53.041  4766  4766 D SamsungIME: IMPL finishInput
,02-23 11:45:53.041  4766  4766 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
02-23 11:45:53.041  4766  4766 D SamsungIME: saveAndClear +
02-23 11:45:53.041  4766  4766 D SamsungIME: saveAndClear -
,02-23 11:45:53.051  3509  3526 V WindowStateAnimator: Finishing drawing window Window{5c3b6fc u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,02-23 11:45:53.051  9847  9847 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,02-23 11:45:53.051  9847  9847 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f46245b time:178717
,02-23 11:45:53.051  6467  6467 V ActivityThread: updateVisibility : ActivityRecord{ef24951 token=android.os.BinderProxy@294da4b {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,02-23 11:45:53.061  9847  9847 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9847
,02-23 11:45:53.061  9847  9847 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
02-23 11:45:53.061  9847  9847 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,02-23 11:45:53.061  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fdb4a8878
,02-23 11:45:53.081  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fdb4a8878
,02-23 11:45:53.171  9847  9847 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,02-23 11:45:53.231  3011  4176 I SurfaceFlinger: id=18 Removed uhalitest (7/11)
,02-23 11:45:53.231  3011  3021 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,02-23 11:45:53.251  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fdb4a8998
,02-23 11:45:53.261  9847  9910 D jxcore_app_log: JniHelper::setJavaVM(0xf4c34000), pthread_self() = -702056144
,02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65b16d2 added. We now have 1 listener(s)
,02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65b16d2 added. We now have 1 listener(s)
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
02-23 11:45:53.261  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,02-23 11:45:53.271  9847  9910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:2C:E6
,02-23 11:45:53.271  9847  9910 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:2C:E6"Peer extra info: "256
02-23 11:45:53.271  9847  9910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,02-23 11:45:53.271  9847  9910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
,02-23 11:45:53.271  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-23 11:45:53.271  9847  9910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb78259 added. We now have 2 listener(s)
02-23 11:45:53.271  9847  9910 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,02-23 11:45:53.271  9847  9910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
02-23 11:45:53.271  9847  9910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 37329
,02-23 11:45:53.271  9847  9910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 137
02-23 11:45:53.271  9847  9910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
02-23 11:45:53.271  9847  9910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
02-23 11:45:53.271  9847  9910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
02-23 11:45:53.271  9847  9910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 137
,02-23 11:45:53.271  9847  9910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-23 11:45:53.271  9847  9910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:2C:E6
,02-23 11:45:53.281  9847  9910 D BluetoothAdapter: STATE_ON
,02-23 11:45:53.281  9847  9910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,02-23 11:45:53.281  9847  9910 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-23 11:45:53.281  9847  9910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-23 11:45:53.281  9847  9910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-23 11:45:53.281  9847  9910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-23 11:45:53.281  9847  9910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-23 11:45:53.281  9847  9910 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-23 11:45:53.281  9847  9910 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-23 11:45:53.281  9847  9910 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-23 11:45:53.281  9847  9910 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
02-23 11:45:53.281  9847  9910 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
02-23 11:45:53.281  9847  9910 D io.jxcore.node.ConnectivityMonitor: start: OK
02-23 11:45:53.281  9847  9910 I io.jxcore.node.LifeCycleMonitor: start: OK
,02-23 11:45:53.281  9847  9847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:45:53.281  9847  9847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:45:53.291  9847  9847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:45:53.291  9847  9847 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,02-23 11:45:53.291  9847  9847 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
02-23 11:45:53.291  9847  9847 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,02-23 11:45:53.321  3509  3883 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,02-23 11:45:53.341  3509  3509 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3509  tag : ACTIVITY_RESUME_BOOSTER@9
,02-23 11:45:53.421  3509  3883 I MdnieScenarioControlService: mGameModeLauncher : false
,02-23 11:45:53.431  3509  3883 I MdnieScenarioControlService: setUIMode
,02-23 11:45:53.431  4031  4031 D Recents : onTaskStackChanged
,02-23 11:45:53.441  4031  4031 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,02-23 11:45:53.451  4031  4031 D ResourcesManager: For user 0 new overlays fetched Null
,02-23 11:45:53.481  3509  6387 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,02-23 11:45:53.771  9847  9911 W jxcore-log: Initializing JXcore engine
02-23 11:45:53.771  9847  9911 W jxcore-log: JXcore engine is ready
,02-23 11:45:53.791  5354  5354 E audit   : type=1400 msg=audit(1487846753.791:264): avc:  denied  { ioctl } for  pid=9911 comm="Thread-138" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3194 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
02-23 11:45:53.791  5354  5354 E audit   :  SEPF_SECMOBILE_6.0.1_0031
02-23 11:45:53.791  5354  5354 E audit   : type=1300 msg=audit(1487846753.791:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d55ff3c8 items=0 ppid=3185 pid=9911 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
02-23 11:45:53.791  5354  5354 E audit   : type=1327 msg=audit(1487846753.791:264): proctitle="com.test.thalitest"
02-23 11:45:53.791  5354  5354 E audit   : type=1320 msg=audit(1487846753.791:264): 
02-23 11:45:53.791  5354  5354 E audit   : type=1400 msg=audit(1487846753.791:265): avc:  denied  { ioctl } for  pid=9911 comm="Thread-138" path="socket:[40284]" dev="sockfs" ino=40284 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
02-23 11:45:53.791  5354  5354 E audit   :  SEPF_SECMOBILE_6.0.1_0031
02-23 11:45:53.791  5354  5354 E audit   : type=1300 msg=audit(1487846753.791:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=2 a3=d55ff3c8 items=0 ppid=3185 pid=9911 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
02-23 11:45:53.791  5354  5354 E audit   : type=1327 msg=audit(1487846753.791:265): proctitle="com.test.thalitest"
02-23 11:45:53.791  5354  5354 E audit   : type=1320 msg=audit(1487846753.791:265): 
,02-23 11:45:53.801  9847  9911 W jxcore-log: Starting JXcore engine
,02-23 11:45:53.831  9847  9911 W jxcore-log: Platform android
02-23 11:45:53.831  9847  9911 W jxcore-log: 
02-23 11:45:53.831  9847  9911 W jxcore-log: Process ARCH arm
02-23 11:45:53.831  9847  9911 W jxcore-log: 
,02-23 11:45:53.961  9847  9911 I jxcore-log: JXcore Cordova bridge is ready!
02-23 11:45:53.961  9847  9911 I jxcore-log: 
02-23 11:45:53.961  9847  9911 W jxcore-log: JXcore engine is started
,02-23 11:45:53.971  9847  9910 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,02-23 11:45:53.971  9847  9847 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
02-23 11:45:53.971  9847  9847 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,02-23 11:45:55.411  3509  3913 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/5_task.xml.bak
,02-23 11:45:55.471  3509  6386 D GameManagerService: identifyGamePackage. com.test.thalitest
,02-23 11:45:58.521  3509  6386 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,02-23 11:45:59.991  3509  3814 V AlarmManager: Expired Alarm result :8
,02-23 11:46:00.001  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
02-23 11:46:00.001  3944  3944 D KeyguardUpdateMonitor: handleTimeUpdate
,02-23 11:46:00.011  3944  3944 D Clock   : received broadcast android.intent.action.TIME_TICK
,02-23 11:46:00.081  3944  3944 D DateView: received broadcast android.intent.action.TIME_TICK
,02-23 11:46:00.101  4734  4734 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,02-23 11:46:00.111  4734  4734 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,02-23 11:46:00.111  4734  4734 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,02-23 11:46:00.111  4734  4734 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
02-23 11:46:00.111  4734  4734 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0608352BBBA44ED61A9FF53156343D2423B8D5D1650C9F395597052A680A2D99E34862742E5D4BBA906D2B32986C91FA5]}
02-23 11:46:00.111  4734  4734 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,02-23 11:46:00.941  9847  9911 I jxcore-log: 2017-02-23 10:46:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
02-23 11:46:00.941  9847  9911 I jxcore-log: 
,02-23 11:46:00.941  9847  9911 I jxcore-log: 2017-02-23 10:46:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
02-23 11:46:00.941  9847  9911 I jxcore-log: 
02-23 11:46:00.941  9847  9911 I jxcore-log: 2017-02-23 10:46:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
02-23 11:46:00.941  9847  9911 I jxcore-log: 
,02-23 11:46:00.951  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:00.951  9847  9911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-23 11:46:00.951  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-23 11:46:00.951  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-23 11:46:00.951  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-23 11:46:00.951  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-23 11:46:00.951  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-23 11:46:00.951  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-23 11:46:00.951  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-23 11:46:00.951  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,02-23 11:46:00.951  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:00.961  9847  9911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
02-23 11:46:00.961  9847  9911 I jxcore-log: 2017-02-23 10:46:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
02-23 11:46:00.961  9847  9911 I jxcore-log: 
02-23 11:46:00.961  9847  9911 I jxcore-log: 2017-02-23 10:46:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
02-23 11:46:00.961  9847  9911 I jxcore-log: 
02-23 11:46:00.961  9847  9911 I jxcore-log: 2017-02-23 10:46:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
02-23 11:46:00.961  9847  9911 I jxcore-log: 
,02-23 11:46:01.221  9847  9911 D ExecuteNativeTests: Running unit tests
,02-23 11:46:01.221  9847  9911 D BluetoothAdapter: enable()
,02-23 11:46:01.231  9847  9911 D BluetoothAdapter: enable(): BT is already enabled..!
,02-23 11:46:01.241  3509  3578 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{55335f5 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{77fb42b 5374:com.samsung.android.providers.context/u0a7}
,02-23 11:46:01.241  9847  9911 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,02-23 11:46:01.241  3509  4411 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,02-23 11:46:01.251  3509  4411 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,02-23 11:46:01.251  3509  4411 D WifiService: setWifiEnabled: true pid=9847, uid=10074
,02-23 11:46:01.251  3509  4411 W ActivityManager: Permission Denial: getCurrentUser() from pid=9847, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,02-23 11:46:01.251  3509  3861 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,02-23 11:46:01.261  3509  3861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,02-23 11:46:01.261  3509  4411 W WifiService: Failed getting userId using ActivityManagerNative
02-23 11:46:01.261  3509  4411 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9847, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
02-23 11:46:01.261  3509  4411 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-23 11:46:01.261  3509  4411 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
02-23 11:46:01.261  3509  4411 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
02-23 11:46:01.261  3509  4411 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
02-23 11:46:01.261  3509  4411 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
02-23 11:46:01.261  3509  3861 D WifiBigDataLog: init : 
02-23 11:46:01.261  3509  4411 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
02-23 11:46:01.261  3509  4411 D SettingsProvider: isChangeAllowed() : name = wifi_on
02-23 11:46:01.261  3509  3864 D WifiStateMachine: setFccChannel: channel = -1
,02-23 11:46:01.261  3509  3864 D WifiController: [FCC]setFccChannel() is called !!!
02-23 11:46:01.261  3509  3864 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,02-23 11:46:01.261  3509  3861 D WifiStateMachine: setFccChannelNative: channel = -1
,02-23 11:46:01.261  3509  3861 D WifiNative-wlan0: callSECApiInt - ID [230]
,02-23 11:46:01.271  3509  3578 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f5ccf8a u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{77fb42b 5374:com.samsung.android.providers.context/u0a7}
,02-23 11:46:01.781  3509  4172 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:01.781  3509  4172 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:01.781  3509  4172 D BatteryService: online:4, current avg:-266, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:171
02-23 11:46:01.781  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:01.781  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:01.781  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:01.781  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:01.781  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:01.781  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:01.791  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:01.791  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:01.791  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:01.791  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:01.791  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:01.801  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:01.801  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:01.801  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
02-23 11:46:01.811  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:01.811  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
02-23 11:46:01.811  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:01.821  3509  6386 D SSRM:n  : SIOP:: AP = 400, PST = 329 (W:6), CP = 284, CUR = -266, LCD = 99
,02-23 11:46:01.831  3509  6386 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,02-23 11:46:01.861  3509  4299 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:01.861  3509  4299 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:01.861  3509  4299 D BatteryService: online:4, current avg:-266, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:28
02-23 11:46:01.861  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:01.861  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:01.861  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:01.861  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:01.861  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:01.861  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:01.871  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:01.871  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:01.871  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:01.871  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:01.871  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:01.881  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:01.881  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:01.881  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:01.891  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:01.891  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:01.891  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:02.301  3509  4065 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:02.301  3509  4065 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:02.301  3509  4065 D BatteryService: online:4, current avg:-251, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:169
02-23 11:46:02.301  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:02.301  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:02.301  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:02.301  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:02.301  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:02.311  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:02.311  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:02.311  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:02.311  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:02.311  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:02.311  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
02-23 11:46:02.321  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:02.321  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:02.321  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:02.331  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:02.331  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:02.331  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:02.381  3509  4843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:02.471  3509  3620 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,02-23 11:46:02.491  3509  3620 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,02-23 11:46:02.941  3509  4065 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:02.941  3509  4065 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:02.941  3509  4065 D BatteryService: online:4, current avg:-235, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:139
02-23 11:46:02.941  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:02.951  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:02.951  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:02.951  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:02.951  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:02.951  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:02.951  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:02.951  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:02.961  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:02.961  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:02.961  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:02.961  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:02.961  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:02.961  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:02.971  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:02.981  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:02.981  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:03.021  3509  4843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:03.021  3509  4843 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:03.021  3509  4843 D BatteryService: online:4, current avg:-229, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:139
02-23 11:46:03.021  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:03.021  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:03.021  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:03.021  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:03.021  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:03.021  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:03.031  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:03.031  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:03.031  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2,
02-23 11:46:03.031  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:03.031  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:03.041  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:03.041  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:03.041  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:03.041  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:03.051  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:03.051  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:03.321  3509  4426 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:03.321  3509  4426 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:03.321  3509  4426 D BatteryService: online:4, current avg:-218, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:166
02-23 11:46:03.321  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:03.321  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:03.321  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:03.321  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:03.321  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:03.331  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:03.331  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:03.331  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:03.331  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:03.331  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:03.331  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:03.351  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:03.351  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:03.351  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:03.351  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:03.361  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
02-23 11:46:03.361  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:03.401  3509  4172 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:03.751  3509  4299 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:03.751  3509  4299 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4322, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:03.751  3509  4299 D BatteryService: online:4, current avg:-207, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:108
02-23 11:46:03.751  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:03.751  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:03.751  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:03.751  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:03.751  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:03.761  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:03.761  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:03.761  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:03.761  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:03.761  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:03.761  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:03.781  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:03.781  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:03.781  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
02-23 11:46:03.781  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:03.791  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
02-23 11:46:03.791  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:03.831  3509  3842 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:03.831  3509  3842 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:03.831  3509  3842 D BatteryService: online:4, current avg:-207, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:146
02-23 11:46:03.831  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:03.831  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:03.831  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:03.831  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:03.831  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:03.831  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:03.831  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:03.841  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:03.841  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:03.841  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:03.841  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:03.851  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:03.851  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:03.851  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:03.851  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:03.861  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:03.861  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:04.161  3509  4434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:04.161  3509  4434 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:04.161  3509  4434 D BatteryService: online:4, current avg:-197, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:133
02-23 11:46:04.161  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:04.161  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:04.161  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:04.161  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:04.161  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:04.171  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:04.171  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:04.171  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:04.171  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:04.181  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:04.181  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:04.191  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:04.201  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:04.201  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:04.201  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:04.221  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:04.221  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:04.251  3509  3526 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:04.251  3509  3526 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:04.251  3509  3526 D BatteryService: online:4, current avg:-192, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:133
02-23 11:46:04.251  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:04.261  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:04.261  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:04.261  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:04.261  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:04.261  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:04.261  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:04.261  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:04.261  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:04.271  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:04.271  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:04.281  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:04.281  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:04.281  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:04.281  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:04.291  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:04.291  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:04.561  3509  4435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:04.561  3509  4435 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:04.561  3509  4435 D BatteryService: online:4, current avg:-183, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:143
02-23 11:46:04.561  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:04.561  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:04.561  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:04.561  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,02-23 11:46:04.561  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:04.571  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:04.571  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:04.571  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:04.571  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:04.581  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:04.581  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:04.601  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:04.601  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:04.601  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
02-23 11:46:04.601  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:04.611  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:04.611  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:04.641  3509  4436 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:04.851  3509  4411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:04.851  3509  4411 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4322, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:04.851  3509  4411 D BatteryService: online:4, current avg:-180, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:170
02-23 11:46:04.851  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:04.851  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:04.851  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:04.851  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:04.851  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:04.851  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:04.851  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:04.861  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:04.861  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:04.861  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:04.861  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:04.871  5384  5384 D CommonServiceConfiguration: getStringValueSetting
02-23 11:46:04.871  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:04.871  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:04.881  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
02-23 11:46:04.881  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:04.891  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:04.931  3509  3856 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:04.931  3509  3856 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:04.931  3509  3856 D BatteryService: online:4, current avg:-174, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:170
02-23 11:46:04.931  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:04.931  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:04.931  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:04.931  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:04.931  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:04.941  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:04.941  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:04.941  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:04.941  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:04.941  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:04.941  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:04.951  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:04.961  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:04.961  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
02-23 11:46:04.961  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:04.971  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:04.971  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:05.211  3509  3525 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:05.211  3509  3525 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4324, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:05.211  3509  3525 D BatteryService: online:4, current avg:-170, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:171
02-23 11:46:05.211  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:05.221  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:05.221  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:05.221  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:05.221  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:05.221  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:05.231  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:05.231  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:05.231  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:05.231  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:05.231  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:05.241  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:05.241  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:05.241  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:05.251  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:05.261  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:05.261  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:05.301  3509  4843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:05.301  3509  4843 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4324, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:05.301  3509  4843 D BatteryService: online:4, current avg:-164, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:171
02-23 11:46:05.301  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:05.301  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:05.301  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:05.301  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:05.301  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:05.301  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:05.301  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:05.311  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:05.311  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:05.311  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:05.311  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:05.321  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:05.321  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:05.321  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:05.321  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:05.341  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:05.341  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:05.581  3509  4300 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:05.581  3509  4300 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:05.581  3509  4300 D BatteryService: online:4, current avg:-161, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:124
02-23 11:46:05.581  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:05.581  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:05.591  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:05.591  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:05.591  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:05.591  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:05.591  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:05.591  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:05.591  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:05.601  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:05.601  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:05.611  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:05.611  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:05.611  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:05.611  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:05.621  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:05.621  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:05.671  3509  4426 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:05.671  3509  4426 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
,02-23 11:46:05.671  3509  4426 D BatteryService: online:4, current avg:-156, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:124
,02-23 11:46:05.671  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:05.681  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:05.681  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:05.681  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:05.681  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:05.681  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:05.681  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:05.681  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:05.681  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:05.681  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:05.681  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:05.691  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:05.701  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:05.701  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:05.701  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:05.701  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:05.701  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:05.941  3509  4172 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:05.941  3509  4172 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:05.941  3509  4172 D BatteryService: online:4, current avg:-149, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:141
02-23 11:46:05.941  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:05.941  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:05.941  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:05.941  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:05.941  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:05.951  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:05.951  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:05.951  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:05.951  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:05.951  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:05.951  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:05.961  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:05.961  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:05.961  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:05.971  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:05.971  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:05.971  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:06.481  3509  3856 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:06.481  3509  3856 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:06.481  3509  3856 D BatteryService: online:4, current avg:-136, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:92
02-23 11:46:06.481  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:06.501  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:06.501  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:06.501  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:06.501  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
02-23 11:46:06.501  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
02-23 11:46:06.501  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:06.501  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
02-23 11:46:06.511  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:06.511  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:06.511  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
02-23 11:46:06.521  5384  5384 D CommonServiceConfiguration: getStringValueSetting
02-23 11:46:06.521  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:06.521  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
02-23 11:46:06.521  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:06.541  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:06.541  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:06.601  3509  6434 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,02-23 11:46:06.911  3509  4436 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:06.911  3509  4436 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4319, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:06.911  3509  4436 D BatteryService: online:4, current avg:-130, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:47
02-23 11:46:06.911  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:06.911  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:06.911  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:06.911  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:06.911  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:06.921  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:06.921  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:06.921  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
02-23 11:46:06.921  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:06.921  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:06.921  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:06.941  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:06.941  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:06.941  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:06.951  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:06.961  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:06.961  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:07.211  3509  4299 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:07.211  3509  4299 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4315, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:07.211  3509  4299 D BatteryService: online:4, current avg:-125, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-58
02-23 11:46:07.211  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:07.211  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:07.211  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:07.211  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:07.211  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:07.221  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
02-23 11:46:07.221  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:07.221  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:07.221  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:07.221  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:07.221  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:07.231  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:07.231  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:07.231  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:07.231  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:07.241  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
02-23 11:46:07.241  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:08.241  3509  4136 E Watchdog: !@Sync 6 [02-23 11:46:08.245]
,02-23 11:46:09.531  4387  4453 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
02-23 11:46:09.531  4387  4453 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,02-23 11:46:09.641  4387  4453 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 106ms lastUpdatedAfter : 128454ms
,02-23 11:46:09.691  3509  4172 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:09.691  3509  4172 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:09.691  3509  4172 D BatteryService: online:4, current avg:-71, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:169
02-23 11:46:09.691  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:09.701  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:09.701  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:09.701  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:09.701  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:09.701  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
02-23 11:46:09.711  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:09.711  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:09.711  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:09.711  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:09.711  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:09.721  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:09.731  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:09.731  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:09.731  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:09.741  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:09.741  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:10.001  3509  3856 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:10.011  3509  3856 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:10.011  3509  3856 D BatteryService: online:4, current avg:-66, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:153
02-23 11:46:10.011  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:10.011  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:10.011  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:10.011  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:10.011  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:10.011  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:10.021  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:10.021  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:10.021  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:10.021  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:10.021  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:10.041  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:10.041  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:10.041  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:10.051  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:10.051  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:10.051  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:11.261  9847  9911 I com.test.thalitest.ThaliTestRunner: Running UT
,02-23 11:46:11.331  9847  9911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
02-23 11:46:11.331  9847  9911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f812260 added. We now have 2 listener(s)
02-23 11:46:11.331  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f812260 added. We now have 3 listener(s)
02-23 11:46:11.331  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-23 11:46:11.331  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:2C:E6"Peer extra info: "256
02-23 11:46:11.331  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
02-23 11:46:11.331  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
02-23 11:46:11.331  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-23 11:46:11.331  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b51319 added. We now have 4 listener(s)
02-23 11:46:11.331  9847  9911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,02-23 11:46:11.331  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,02-23 11:46:11.341  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:11.351  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,02-23 11:46:11.351  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
02-23 11:46:11.351  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,02-23 11:46:11.351  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
02-23 11:46:11.351  9847  9911 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
,02-23 11:46:11.351  9847  9911 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
02-23 11:46:11.351  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
02-23 11:46:11.351  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
02-23 11:46:11.351  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
02-23 11:46:11.351  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,02-23 11:46:11.351  9847  9911 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,02-23 11:46:11.361  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,02-23 11:46:11.361  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,02-23 11:46:11.361  9847  9911 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,02-23 11:46:11.361  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,02-23 11:46:11.381  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:11.391  9847  9911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-23 11:46:11.391  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-23 11:46:11.391  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-23 11:46:11.391  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-23 11:46:11.391  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-23 11:46:11.391  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-23 11:46:11.391  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-23 11:46:11.391  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-23 11:46:11.391  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,02-23 11:46:11.391  9847  9911 D io.jxcore.node.ConnectivityMonitor: start: OK
,02-23 11:46:11.391  9847  9847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:46:11.401  9847  9911 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
,02-23 11:46:11.401  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
02-23 11:46:11.401  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
02-23 11:46:11.401  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:2C:E6"}
02-23 11:46:11.401  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:2C:E6"}
02-23 11:46:11.401  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.401  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
02-23 11:46:11.401  9847  9847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:46:11.411  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:2C:E6"}
,02-23 11:46:11.411  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:2C:E6"}
,02-23 11:46:11.411  9847  9847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
02-23 11:46:11.411  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.411  9847  9911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-23 11:46:11.411  9847  9911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
02-23 11:46:11.411  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,02-23 11:46:11.411  9847  9856 I art     : Background partial concurrent mark sweep GC freed 50262(2MB) AllocSpace objects, 10(5MB) LOS objects, 39% free, 7MB/12MB, paused 8.522ms total 83.689ms
02-23 11:46:11.411  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-23 11:46:11.411  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,02-23 11:46:11.411  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,02-23 11:46:11.411  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,02-23 11:46:11.411  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
02-23 11:46:11.411  9847  9957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,02-23 11:46:11.411  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
02-23 11:46:11.411  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,02-23 11:46:11.411  9847  9847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,02-23 11:46:11.411  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-23 11:46:11.411  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,02-23 11:46:11.421  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,02-23 11:46:11.421  9847  9911 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
02-23 11:46:11.421  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,02-23 11:46:11.421  9847  9957 D BluetoothSocket: bindListen(): myUserId = 0
,02-23 11:46:11.421  9847  9957 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,02-23 11:46:11.421  3509  4434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:11.431  3509  4434 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4328, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:11.431  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:11.431  3509  4434 D BatteryService: online:4, current avg:-40, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:167
02-23 11:46:11.431  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:11.431  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:11.431  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:11.431  9847  9957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,02-23 11:46:11.431  9847  9957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@c46048c, port: 6, type: 1, local socket address: null, socket type: 0
02-23 11:46:11.431  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:11.431  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:11.431  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,02-23 11:46:11.431  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:11.441  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:11.441  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:11.441  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:11.441  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.441  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,02-23 11:46:11.441  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:11.441  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:11.441  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:11.441  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:11.441  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:11.441  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,02-23 11:46:11.451  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,02-23 11:46:11.451  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,02-23 11:46:11.451  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:11.451  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:11.451  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:11.451  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:11.451  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:11.451  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.451  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.451  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
02-23 11:46:11.451  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,02-23 11:46:11.451  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "6ad45288-6074-487c-b683-03a4a8e47a45", Bluetooth MAC address: "44:78:3E:94:2C:E6"
02-23 11:46:11.451  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 2C E6
,02-23 11:46:11.461  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,02-23 11:46:11.461  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:11.461  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:11.461  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.461  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-23 11:46:11.461  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,02-23 11:46:11.461  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.461  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.461  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:11.461  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:11.461  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:11.461  9847  9911 D BluetoothLeAdvertiser: start advertising
,02-23 11:46:11.461  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:11.471  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:11.471  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:11.471  5348  5359 D BtGatt.GattService: registerClient() - UUID=178421c7-1a0a-4e93-a9b5-3cccac61096c
,02-23 11:46:11.511  5348  5421 D BtGatt.GattService: onClientRegistered() - UUID=178421c7-1a0a-4e93-a9b5-3cccac61096c, clientIf=8
,02-23 11:46:11.521  9847  9858 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,02-23 11:46:11.521  5348  5666 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,02-23 11:46:11.531  5348  5666 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-23 11:46:11.531  5348  5666 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:11.531  5348  5481 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
02-23 11:46:11.531  5348  5481 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
02-23 11:46:11.531  5348  5435 D BtGatt.AdvertiseManager: message : 0
,02-23 11:46:11.531  5348  5435 D BtGatt.AdvertiseManager: number of adv instance running = 0
,02-23 11:46:11.531  5348  5435 D BtGatt.AdvertiseManager: size of list is =0
,02-23 11:46:11.531  5348  5435 D BtGatt.AdvertiseManager: starting advertising
,02-23 11:46:11.541  5348  5435 D BtGatt.AdvertiseManager: isStandardAdv = false
,02-23 11:46:11.541  5348  5481 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 1
02-23 11:46:11.541  5348  5481 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24797446
02-23 11:46:11.541  5348  5481 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
02-23 11:46:11.541  5348  5481 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,02-23 11:46:11.541  3509  4411 V AlarmManager:  remove PendingIntent] PendingIntent{6d23430: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:11.551  5348  5481 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,02-23 11:46:11.581  3509  4426 V AlarmManager:  remove PendingIntent] PendingIntent{8708a9: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:11.581  5348  5421 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,02-23 11:46:11.581  5348  5435 D BtGatt.AdvertiseManager: starting multi advertising
,02-23 11:46:11.581  5348  5421 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,02-23 11:46:11.581  5348  5435 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
02-23 11:46:11.581  3509  4435 V AlarmManager:  remove PendingIntent] PendingIntent{9d85e2e: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}},
02-23 11:46:11.581  5348  5435 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,02-23 11:46:11.581  5348  5435 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
02-23 11:46:11.581  5348  5435 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
02-23 11:46:11.591  9847  9857 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,02-23 11:46:11.591  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.591  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.591  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
02-23 11:46:11.591  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:11.591  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.591  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.591  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:11.591  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.591  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,02-23 11:46:11.591  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,02-23 11:46:11.591  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:11.591  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.591  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.591  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:11.591  3509  4299 V AlarmManager:  remove PendingIntent] PendingIntent{3664dcf: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:11.601  9847  9911 I io.jxcore.node.ConnectionHelper: start: OK
02-23 11:46:11.601  9847  9847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,02-23 11:46:11.601  9847  9847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-23 11:46:11.601  9847  9847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,02-23 11:46:11.601  3509  3526 V AlarmManager:  remove PendingIntent] PendingIntent{b5e635c: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,02-23 11:46:11.601  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
02-23 11:46:11.611  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,02-23 11:46:11.611  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:11.611  9847  9847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,02-23 11:46:11.611  3509  4933 V AlarmManager:  remove PendingIntent] PendingIntent{e9e8665: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:11.611  3509  4435 V AlarmManager:  remove PendingIntent] PendingIntent{d902f3a: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:11.851  3509  6386 D SSRM:n  : SIOP:: AP = 350, PST = 336 (W:14), CP = 287, CUR = -40, LCD = 99
,02-23 11:46:11.911  3509  4436 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:11.911  3509  4436 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4326, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:11.911  3509  4436 D BatteryService: online:4, current avg:-37, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:117
02-23 11:46:11.921  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:11.921  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:11.921  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:11.921  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:11.921  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:11.921  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:11.921  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:11.921  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:11.931  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:11.931  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:11.931  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:11.941  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:11.941  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:11.941  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:11.951  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:11.951  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:11.961  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:12.101  9847  9960 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,02-23 11:46:12.101  9847  9911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
,02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
,02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
,02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
,02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
,02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
,02-23 11:46:12.101  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
02-23 11:46:12.111  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
02-23 11:46:12.111  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
,02-23 11:46:12.111  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
02-23 11:46:12.111  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
02-23 11:46:12.111  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
02-23 11:46:12.111  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
,02-23 11:46:12.111  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
02-23 11:46:12.111  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
02-23 11:46:12.111  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
02-23 11:46:12.111  9847  9911 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,02-23 11:46:12.111  9847  9911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
02-23 11:46:12.111  9847  9911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
02-23 11:46:12.111  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
02-23 11:46:12.111  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,02-23 11:46:12.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
02-23 11:46:12.111  9847  9847 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
02-23 11:46:12.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
02-23 11:46:12.111  9847  9957 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,02-23 11:46:12.111  9847  9957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
02-23 11:46:12.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
02-23 11:46:12.111  9847  9957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
02-23 11:46:12.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,02-23 11:46:12.111  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
02-23 11:46:12.111  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
02-23 11:46:12.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:12.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
02-23 11:46:12.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
02-23 11:46:12.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.121  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:12.121  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:12.121  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
02-23 11:46:12.121  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:12.131  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:12.131  9847  9911 D BluetoothLeScanner: could not find callback wrapper
02-23 11:46:12.131  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
02-23 11:46:12.131  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.131  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:12.131  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.131  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
02-23 11:46:12.131  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:12.131  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:12.131  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:12.131  9847  9911 D BluetoothLeAdvertiser: stop advertising
,02-23 11:46:12.141  5348  5666 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-23 11:46:12.141  5348  5666 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:12.141  5348  5481 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
02-23 11:46:12.141  5348  5435 D BtGatt.AdvertiseManager: message : 1
02-23 11:46:12.141  5348  5481 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,02-23 11:46:12.141  5348  5481 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-23 11:46:12.141  5348  5481 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-23 11:46:12.141  5348  5481 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,02-23 11:46:12.141  5348  5435 D BtGatt.AdvertiseManager: stop advertise for client =  8
02-23 11:46:12.141  5348  5435 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,02-23 11:46:12.151  5348  5435 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,02-23 11:46:12.151  3509  3990 V AlarmManager:  remove PendingIntent] PendingIntent{5a3f7eb: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.151  5348  5421 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
02-23 11:46:12.151  5348  5421 D BtGatt.GattService: Client app is not null!
,02-23 11:46:12.151  9847  9857 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,02-23 11:46:12.151  5348  5612 D BtGatt.GattService: unregisterClient() - clientIf=8
,02-23 11:46:12.151  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,02-23 11:46:12.151  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.151  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
02-23 11:46:12.151  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.151  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:12.161  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.161  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
02-23 11:46:12.161  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
02-23 11:46:12.161  3509  4299 V AlarmManager:  remove PendingIntent] PendingIntent{71c5948: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:12.161  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,02-23 11:46:12.161  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:12.161  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.161  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
02-23 11:46:12.161  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.161  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:12.161  9847  9847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
02-23 11:46:12.161  9847  9847 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,02-23 11:46:12.161  9847  9847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
02-23 11:46:12.161  9847  9847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,02-23 11:46:12.161  9847  9847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
02-23 11:46:12.161  9847  9847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-23 11:46:12.161  9847  9847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,02-23 11:46:12.161  9847  9847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:12.161  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.161  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
02-23 11:46:12.161  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
02-23 11:46:12.161  3509  3525 V AlarmManager:  remove PendingIntent] PendingIntent{ff623e1: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:12.161  9847  9964 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
02-23 11:46:12.161  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.161  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.161  9847  9911 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
02-23 11:46:12.161  9847  9911 V io.jxcore.node.ConnectivityMonitor: start: Already started
02-23 11:46:12.161  9847  9911 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
02-23 11:46:12.161  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.161  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
02-23 11:46:12.161  9847  9847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
02-23 11:46:12.171  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-23 11:46:12.171  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:2C:E6"}
02-23 11:46:12.171  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:2C:E6"}
02-23 11:46:12.171  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.171  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
02-23 11:46:12.171  3509  3990 V AlarmManager:  remove PendingIntent] PendingIntent{bc20506: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:12.171  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:2C:E6"}
02-23 11:46:12.171  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:2C:E6"}
02-23 11:46:12.171  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.171  9847  9911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-23 11:46:12.181  9847  9911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
02-23 11:46:12.181  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
02-23 11:46:12.181  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-23 11:46:12.181  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
02-23 11:46:12.181  3509  4843 V AlarmManager:  remove PendingIntent] PendingIntent{7c827c7: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:12.181  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
02-23 11:46:12.181  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
02-23 11:46:12.181  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
02-23 11:46:12.181  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
02-23 11:46:12.181  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
02-23 11:46:12.181  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-23 11:46:12.181  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
02-23 11:46:12.181  9847  9847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
02-23 11:46:12.181  9847  9965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
02-23 11:46:12.181  9847  9965 D BluetoothSocket: bindListen(): myUserId = 0
02-23 11:46:12.181  9847  9965 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
02-23 11:46:12.191  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
02-23 11:46:12.191  9847  9911 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
02-23 11:46:12.191  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
02-23 11:46:12.191  9847  9965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
02-23 11:46:12.191  3509  3856 V AlarmManager:  remove PendingIntent] PendingIntent{7157963: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:12.191  9847  9965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@a151cb6, port: 6, type: 1, local socket address: null, socket type: 0
02-23 11:46:12.191  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:12.191  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:12.191  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:12.201  3509  4426 V AlarmManager:  remove PendingIntent] PendingIntent{4b30960: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:12.201  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.201  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
02-23 11:46:12.201  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:12.201  3509  4411 V AlarmManager:  remove PendingIntent] PendingIntent{d566e19: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:12.201  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:12.201  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
02-23 11:46:12.201  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
02-23 11:46:12.201  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
02-23 11:46:12.201  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:12.211  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.211  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.211  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
02-23 11:46:12.211  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
02-23 11:46:12.211  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "6ad45288-6074-487c-b683-03a4a8e47a45", Bluetooth MAC address: "44:78:3E:94:2C:E6"
02-23 11:46:12.211  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 2C E6
02-23 11:46:12.211  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:12.211  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:12.211  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.211  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.211  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-23 11:46:12.211  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:12.211  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.211  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.211  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.211  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:12.211  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:12.211  9847  9911 D BluetoothLeAdvertiser: start advertising
02-23 11:46:12.211  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:12.221  5348  5359 D BtGatt.GattService: registerClient() - UUID=fae1979b-be40-41c3-addb-0c3ffcf9a494
,02-23 11:46:12.261  5348  5421 D BtGatt.GattService: onClientRegistered() - UUID=fae1979b-be40-41c3-addb-0c3ffcf9a494, clientIf=8
,02-23 11:46:12.261  9847  9858 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,02-23 11:46:12.261  5348  5612 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,02-23 11:46:12.261  5348  5612 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-23 11:46:12.261  5348  5612 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:12.261  5348  5435 D BtGatt.AdvertiseManager: message : 0
02-23 11:46:12.261  5348  5481 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
02-23 11:46:12.261  5348  5481 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
02-23 11:46:12.261  5348  5435 D BtGatt.AdvertiseManager: number of adv instance running = 0
02-23 11:46:12.261  5348  5435 D BtGatt.AdvertiseManager: size of list is =0
,02-23 11:46:12.271  5348  5435 D BtGatt.AdvertiseManager: starting advertising
,02-23 11:46:12.271  5348  5435 D BtGatt.AdvertiseManager: isStandardAdv = false
,02-23 11:46:12.271  5348  5481 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 2
02-23 11:46:12.271  5348  5481 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24797446
,02-23 11:46:12.271  3509  4065 V AlarmManager:  remove PendingIntent] PendingIntent{3aeaede: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.271  5348  5481 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
02-23 11:46:12.271  5348  5481 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-23 11:46:12.271  5348  5481 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,02-23 11:46:12.281  3509  3842 V AlarmManager:  remove PendingIntent] PendingIntent{85c48bf: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.331  3509  3856 V AlarmManager:  remove PendingIntent] PendingIntent{2f5b8c: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.331  5348  5421 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,02-23 11:46:12.331  5348  5435 D BtGatt.AdvertiseManager: starting multi advertising
,02-23 11:46:12.331  3509  3526 V AlarmManager:  remove PendingIntent] PendingIntent{c56d2d5: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.331  5348  5421 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
02-23 11:46:12.331  5348  5435 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,02-23 11:46:12.331  5348  5435 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
02-23 11:46:12.331  5348  5435 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
02-23 11:46:12.331  5348  5435 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
,02-23 11:46:12.331  9847  9857 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
02-23 11:46:12.331  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.331  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:12.331  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,02-23 11:46:12.331  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.341  3509  4065 V AlarmManager:  remove PendingIntent] PendingIntent{af2daea: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:12.331  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.331  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.331  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.331  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.331  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
02-23 11:46:12.331  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,02-23 11:46:12.341  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.341  9847  9911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
02-23 11:46:12.341  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.341  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.341  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.341  9847  9911 I io.jxcore.node.ConnectionHelper: start: OK
02-23 11:46:12.341  9847  9847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.341  9847  9847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,02-23 11:46:12.341  9847  9847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.341  3509  4434 V AlarmManager:  remove PendingIntent] PendingIntent{316b1db: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.341  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.341  9847  9847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,02-23 11:46:12.351  3509  4300 V AlarmManager:  remove PendingIntent] PendingIntent{53ca478: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.351  3509  4436 V AlarmManager:  remove PendingIntent] PendingIntent{1bec751: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.371  3509  4065 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:12.371  3509  4065 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:12.371  3509  4065 D BatteryService: online:4, current avg:-33, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:68
02-23 11:46:12.371  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:12.371  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:12.371  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:12.371  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:12.371  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:12.371  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:12.371  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:12.371  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:12.381  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:12.381  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:12.381  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:12.381  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:12.381  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:12.381  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:12.391  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:12.391  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:12.391  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:12.631  3509  4300 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:12.631  3509  4300 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:12.631  3509  4300 D BatteryService: online:4, current avg:-28, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:157
02-23 11:46:12.631  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:12.631  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:12.631  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:12.631  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:12.631  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:12.631  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:12.631  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:12.641  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:12.641  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:12.641  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:12.641  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:12.641  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:12.651  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:12.651  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:12.651  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:12.661  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
02-23 11:46:12.661  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:12.781  3509  3856 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:12.781  3509  3856 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4320, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:12.781  3509  3856 D BatteryService: online:4, current avg:-27, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:38
02-23 11:46:12.781  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:12.781  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:12.781  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:12.781  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:12.781  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:12.791  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:12.791  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:12.791  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:12.791  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:12.791  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:12.791  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:12.811  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:12.811  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:12.811  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:12.821  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:12.831  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:12.831  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:12.841  9847  9967 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,02-23 11:46:12.841  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,02-23 11:46:12.841  9847  9911 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
02-23 11:46:12.841  9847  9911 V io.jxcore.node.ConnectivityMonitor: start: Already started
02-23 11:46:12.841  9847  9911 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
02-23 11:46:12.841  9847  9911 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
02-23 11:46:12.841  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,02-23 11:46:12.841  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-23 11:46:12.851  9847  9847 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,02-23 11:46:12.851  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
02-23 11:46:12.851  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,02-23 11:46:12.851  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.851  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-23 11:46:12.851  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,02-23 11:46:12.851  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
02-23 11:46:12.851  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.851  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
02-23 11:46:12.851  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 37329
02-23 11:46:12.851  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
02-23 11:46:12.851  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
02-23 11:46:12.851  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
02-23 11:46:12.851  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
02-23 11:46:12.851  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
02-23 11:46:12.851  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
02-23 11:46:12.851  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
02-23 11:46:12.851  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:12.851  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
02-23 11:46:12.851  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.851  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.851  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.861  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:12.861  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:12.861  9847  9911 D BluetoothLeAdvertiser: stop advertising
,02-23 11:46:12.861  5348  5665 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:12.861  5348  5665 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-23 11:46:12.861  5348  5435 D BtGatt.AdvertiseManager: message : 1
02-23 11:46:12.861  5348  5481 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
02-23 11:46:12.861  5348  5481 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
02-23 11:46:12.861  5348  5481 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,02-23 11:46:12.861  5348  5481 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-23 11:46:12.861  5348  5481 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
02-23 11:46:12.861  5348  5435 D BtGatt.AdvertiseManager: stop advertise for client =  8
02-23 11:46:12.861  5348  5435 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,02-23 11:46:12.871  5348  5435 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,02-23 11:46:12.871  5348  5421 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
,02-23 11:46:12.871  5348  5421 D BtGatt.GattService: Client app is not null!
02-23 11:46:12.871  9847  9858 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
02-23 11:46:12.871  3509  3990 V AlarmManager:  remove PendingIntent] PendingIntent{89bbbb6: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.871  5348  5359 D BtGatt.GattService: unregisterClient() - clientIf=8
,02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.871  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.871  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
02-23 11:46:12.881  3509  4300 V AlarmManager:  remove PendingIntent] PendingIntent{24490b7: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,02-23 11:46:12.871  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "6ad45288-6074-487c-b683-03a4a8e47a45", Bluetooth MAC address: "44:78:3E:94:2C:E6"
02-23 11:46:12.871  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 2C E6
02-23 11:46:12.871  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:12.871  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.871  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.871  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.881  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:12.881  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:12.881  9847  9911 D BluetoothLeAdvertiser: start advertising
,02-23 11:46:12.881  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:12.881  3509  4411 V AlarmManager:  remove PendingIntent] PendingIntent{fd39024: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.891  3509  4299 V AlarmManager:  remove PendingIntent] PendingIntent{2d7878d: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.891  5348  5359 D BtGatt.GattService: registerClient() - UUID=9dd67038-7f97-4d8d-ad48-44755c0bdcf1
,02-23 11:46:12.891  3509  4300 V AlarmManager:  remove PendingIntent] PendingIntent{51fdd42: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.901  3509  4065 V AlarmManager:  remove PendingIntent] PendingIntent{7078153: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.901  3509  3856 V AlarmManager:  remove PendingIntent] PendingIntent{cb8a90: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.911  3509  3842 V AlarmManager:  remove PendingIntent] PendingIntent{6420f89: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.931  5348  5421 D BtGatt.GattService: onClientRegistered() - UUID=9dd67038-7f97-4d8d-ad48-44755c0bdcf1, clientIf=8
,02-23 11:46:12.931  9847  9857 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,02-23 11:46:12.931  5348  5665 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,02-23 11:46:12.941  5348  5665 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-23 11:46:12.941  5348  5665 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:12.941  5348  5435 D BtGatt.AdvertiseManager: message : 0
,02-23 11:46:12.941  5348  5481 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
02-23 11:46:12.941  5348  5481 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
02-23 11:46:12.941  5348  5435 D BtGatt.AdvertiseManager: number of adv instance running = 0
02-23 11:46:12.941  5348  5435 D BtGatt.AdvertiseManager: size of list is =0
,02-23 11:46:12.941  5348  5435 D BtGatt.AdvertiseManager: starting advertising
,02-23 11:46:12.951  5348  5481 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 3
02-23 11:46:12.951  5348  5481 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24797446
,02-23 11:46:12.951  5348  5481 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
02-23 11:46:12.951  5348  5481 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-23 11:46:12.951  5348  5481 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-23 11:46:12.951  5348  5435 D BtGatt.AdvertiseManager: isStandardAdv = false
,02-23 11:46:12.951  3509  4172 V AlarmManager:  remove PendingIntent] PendingIntent{7d28b8e: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.951  5348  5421 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,02-23 11:46:12.961  5348  5435 D BtGatt.AdvertiseManager: starting multi advertising
,02-23 11:46:12.961  5348  5421 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,02-23 11:46:12.961  5348  5435 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
02-23 11:46:12.961  5348  5435 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
02-23 11:46:12.961  3509  4426 V AlarmManager:  remove PendingIntent] PendingIntent{8fedfaf: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.961  5348  5435 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
02-23 11:46:12.961  5348  5435 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
02-23 11:46:12.961  9847  9858 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
02-23 11:46:12.961  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.961  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.961  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
02-23 11:46:12.961  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.961  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.961  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.961  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.961  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.961  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.961  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,02-23 11:46:12.961  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.961  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
02-23 11:46:12.961  9847  9911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
02-23 11:46:12.961  9847  9911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,02-23 11:46:12.961  9847  9911 I io.jxcore.node.ConnectionHelper: start: OK
02-23 11:46:12.961  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.961  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:12.961  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
02-23 11:46:12.961  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.961  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,02-23 11:46:12.961  9847  9847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:12.961  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.961  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
02-23 11:46:12.961  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
02-23 11:46:12.971  3509  4300 V AlarmManager:  remove PendingIntent] PendingIntent{d06bfbc: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:12.961  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,02-23 11:46:12.961  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-23 11:46:12.961  9847  9973 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
02-23 11:46:12.961  9847  9911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
02-23 11:46:12.961  9847  9911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
02-23 11:46:12.961  9847  9911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,02-23 11:46:12.961  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
02-23 11:46:12.961  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
02-23 11:46:12.961  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
02-23 11:46:12.961  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,02-23 11:46:12.961  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
02-23 11:46:12.961  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
02-23 11:46:12.961  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
02-23 11:46:12.961  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,02-23 11:46:12.961  9847  9847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
02-23 11:46:12.971  9847  9965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
02-23 11:46:12.971  9847  9965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
02-23 11:46:12.971  9847  9965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,02-23 11:46:12.971  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.971  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
02-23 11:46:12.971  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
02-23 11:46:12.971  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.971  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:12.971  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.971  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.971  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:12.971  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:12.971  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
02-23 11:46:12.971  3509  3856 V AlarmManager:  remove PendingIntent] PendingIntent{1b31b45: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.981  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:12.981  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:12.981  9847  9911 D BluetoothLeScanner: could not find callback wrapper
02-23 11:46:12.981  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
02-23 11:46:12.981  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.981  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:12.981  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:12.981  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
02-23 11:46:12.981  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:12.981  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:12.981  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:12.981  9847  9911 D BluetoothLeAdvertiser: stop advertising
02-23 11:46:12.981  3509  4435 V AlarmManager:  remove PendingIntent] PendingIntent{7efd29a: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:12.991  5348  5359 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:12.991  5348  5359 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:12.991  5348  5481 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
02-23 11:46:12.991  5348  5481 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
,02-23 11:46:12.991  3509  4411 V AlarmManager:  remove PendingIntent] PendingIntent{63c7cb: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:12.991  5348  5481 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-23 11:46:12.991  5348  5481 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,02-23 11:46:12.991  5348  5481 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
02-23 11:46:12.991  5348  5435 D BtGatt.AdvertiseManager: message : 1
02-23 11:46:12.991  5348  5435 D BtGatt.AdvertiseManager: stop advertise for client =  8
,02-23 11:46:12.991  5348  5435 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,02-23 11:46:12.991  5348  5421 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
,02-23 11:46:12.991  5348  5421 D BtGatt.GattService: Client app is not null!
02-23 11:46:12.991  9847  9857 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
02-23 11:46:12.991  5348  5435 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,02-23 11:46:12.991  5348  5665 D BtGatt.GattService: unregisterClient() - clientIf=8
02-23 11:46:12.991  3509  4299 V AlarmManager:  remove PendingIntent] PendingIntent{35e1ba8: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.001  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
02-23 11:46:13.001  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:13.001  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
02-23 11:46:13.001  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.001  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.001  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.001  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
02-23 11:46:13.001  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,02-23 11:46:13.001  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
02-23 11:46:13.001  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:13.001  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.001  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
02-23 11:46:13.001  3509  4411 V AlarmManager:  remove PendingIntent] PendingIntent{76f26c1: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.001  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.001  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:13.001  9847  9847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
02-23 11:46:13.001  9847  9847 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
02-23 11:46:13.001  9847  9847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,02-23 11:46:13.001  9847  9847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
02-23 11:46:13.001  9847  9847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-23 11:46:13.001  9847  9847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-23 11:46:13.001  9847  9847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:13.001  9847  9974 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,02-23 11:46:13.001  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.001  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
02-23 11:46:13.001  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,02-23 11:46:13.001  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.001  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.001  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.001  9847  9847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,02-23 11:46:13.011  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
,02-23 11:46:13.011  3509  4172 V AlarmManager:  remove PendingIntent] PendingIntent{2687e66: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.011  9847  9911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
02-23 11:46:13.011  9847  9911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd1e390 added. We now have 3 listener(s)
,02-23 11:46:13.011  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd1e390 added. We now have 5 listener(s)
02-23 11:46:13.011  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,02-23 11:46:13.011  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,02-23 11:46:13.011  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
02-23 11:46:13.011  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
02-23 11:46:13.011  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-23 11:46:13.011  3509  4426 V AlarmManager:  remove PendingIntent] PendingIntent{5e515a7: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.011  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d13f489 added. We now have 6 listener(s)
,02-23 11:46:13.011  9847  9911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
02-23 11:46:13.011  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,02-23 11:46:13.021  3509  3990 V AlarmManager:  remove PendingIntent] PendingIntent{4436543: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.021  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,02-23 11:46:13.021  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:13.021  3509  4843 V AlarmManager:  remove PendingIntent] PendingIntent{e5eb7c0: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.031  9847  9911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-23 11:46:13.031  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-23 11:46:13.031  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-23 11:46:13.031  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-23 11:46:13.031  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-23 11:46:13.031  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-23 11:46:13.031  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-23 11:46:13.031  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-23 11:46:13.031  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,02-23 11:46:13.031  9847  9911 D io.jxcore.node.ConnectivityMonitor: start: OK
,02-23 11:46:13.031  3509  3856 V AlarmManager:  remove PendingIntent] PendingIntent{8d0ecf9: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.031  9847  9847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:46:13.031  3509  4172 V AlarmManager:  remove PendingIntent] PendingIntent{abef43e: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.041  9847  9911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:46:13.041  3509  3842 V AlarmManager:  remove PendingIntent] PendingIntent{7ad129f: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.041  9847  9847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:46:13.051  3509  4065 V AlarmManager:  remove PendingIntent] PendingIntent{6578fec: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.051  9847  9847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-23 11:46:13.061  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:13.061  9847  9911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-23 11:46:13.061  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-23 11:46:13.061  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-23 11:46:13.061  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-23 11:46:13.061  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-23 11:46:13.061  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-23 11:46:13.061  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-23 11:46:13.061  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-23 11:46:13.061  9847  9911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
02-23 11:46:13.061  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,02-23 11:46:13.061  9847  9911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
02-23 11:46:13.061  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
02-23 11:46:13.061  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
02-23 11:46:13.061  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
02-23 11:46:13.061  9847  9911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd1e390 removed from the list
,02-23 11:46:13.061  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd1e390 removed from the list
02-23 11:46:13.061  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
02-23 11:46:13.061  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d13f489 removed from the list
02-23 11:46:13.061  9847  9911 D io.jxcore.node.ConnectivityMonitor: stop
02-23 11:46:13.061  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,02-23 11:46:13.061  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
02-23 11:46:13.061  9847  9911 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,02-23 11:46:13.061  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,02-23 11:46:13.061  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,02-23 11:46:13.061  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,02-23 11:46:13.061  9847  9911 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,02-23 11:46:13.061  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
02-23 11:46:13.061  9847  9911 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,02-23 11:46:13.071  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
,02-23 11:46:13.071  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
02-23 11:46:13.071  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
02-23 11:46:13.071  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
02-23 11:46:13.071  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,02-23 11:46:13.071  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
02-23 11:46:13.071  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
02-23 11:46:13.071  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
02-23 11:46:13.071  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,02-23 11:46:13.071  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
02-23 11:46:13.071  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
02-23 11:46:13.071  9847  9911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
02-23 11:46:13.071  9847  9911 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
02-23 11:46:13.071  9847  9911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
02-23 11:46:13.071  9847  9911 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
,02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
,02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
,02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
,02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
,02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
,02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
02-23 11:46:13.071  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
02-23 11:46:13.071  9847  9911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
02-23 11:46:13.071  9847  9911 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,02-23 11:46:13.071  9847  9911 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
02-23 11:46:13.071  9847  9911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
02-23 11:46:13.071  9847  9911 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
02-23 11:46:13.071  9847  9911 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
02-23 11:46:13.071  9847  9911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,02-23 11:46:13.071  9847  9911 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
02-23 11:46:13.071  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
02-23 11:46:13.081  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
02-23 11:46:13.081  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
,02-23 11:46:13.081  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,02-23 11:46:13.081  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
02-23 11:46:13.081  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,02-23 11:46:13.081  9847  9911 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
02-23 11:46:13.081  9847  9911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
02-23 11:46:13.081  9847  9911 E io.jxcore.node.ConnectionHelper: connect: Callback is null
02-23 11:46:13.081  9847  9976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 210)
,02-23 11:46:13.081  9847  9976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
02-23 11:46:13.081  9847  9976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
02-23 11:46:13.081  9847  9976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
02-23 11:46:13.081  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
02-23 11:46:13.081  9847  9911 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,02-23 11:46:13.081  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,02-23 11:46:13.081  9847  9911 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,02-23 11:46:13.081  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
02-23 11:46:13.081  9847  9911 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
02-23 11:46:13.081  9847  9911 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,02-23 11:46:13.081  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
02-23 11:46:13.081  9847  9911 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
02-23 11:46:13.081  9847  9911 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
02-23 11:46:13.081  9847  9911 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
02-23 11:46:13.081  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
02-23 11:46:13.081  9847  9911 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
02-23 11:46:13.081  9847  9911 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
02-23 11:46:13.081  9847  9911 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
02-23 11:46:13.081  9847  9911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
02-23 11:46:13.081  9847  9911 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
02-23 11:46:13.091  9847  9911 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
02-23 11:46:13.091  9847  9911 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
02-23 11:46:13.091  9847  9911 V io.jxcore.node.ConnectivityMonitor: start: Already started
02-23 11:46:13.091  9847  9911 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
02-23 11:46:13.091  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
02-23 11:46:13.091  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
02-23 11:46:13.091  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
02-23 11:46:13.091  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
02-23 11:46:13.091  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.091  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
02-23 11:46:13.091  9847  9976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
02-23 11:46:13.091  9847  9976 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
,02-23 11:46:13.091  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,02-23 11:46:13.091  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
02-23 11:46:13.091  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.091  9847  9911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,02-23 11:46:13.091  9847  9911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
02-23 11:46:13.091  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
02-23 11:46:13.091  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-23 11:46:13.091  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,02-23 11:46:13.091  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,02-23 11:46:13.091  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
02-23 11:46:13.091  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
02-23 11:46:13.091  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
02-23 11:46:13.091  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
02-23 11:46:13.091  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-23 11:46:13.091  9847  9847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
02-23 11:46:13.091  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,02-23 11:46:13.101  9847  9977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,02-23 11:46:13.101  9847  9977 D BluetoothSocket: bindListen(): myUserId = 0
,02-23 11:46:13.101  9847  9977 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,02-23 11:46:13.101  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
02-23 11:46:13.101  9847  9911 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,02-23 11:46:13.101  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
02-23 11:46:13.101  9847  9976 D BluetoothSocket: connect(): myUserId = 0
,02-23 11:46:13.101  9847  9976 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,02-23 11:46:13.101  9847  9977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,02-23 11:46:13.101  9847  9977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@499a8bc, port: 6, type: 1, local socket address: null, socket type: 0
02-23 11:46:13.101  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:13.111  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:13.111  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:13.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:13.111  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,02-23 11:46:13.111  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:13.111  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:13.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,02-23 11:46:13.111  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
02-23 11:46:13.111  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
02-23 11:46:13.111  3509  3525 D SecContentProvider: insert(), uri = 2
,02-23 11:46:13.111  5348  5594 W bt_btif : bta_dm_acl_change(), event : 2
,02-23 11:46:13.121  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:13.121  3509  4426 V AlarmManager:  remove PendingIntent] PendingIntent{a23bed8: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.121  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:13.121  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.121  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
02-23 11:46:13.121  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,02-23 11:46:13.121  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "6ad45288-6074-487c-b683-03a4a8e47a45", Bluetooth MAC address: "44:78:3E:94:2C:E6"
,02-23 11:46:13.121  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 2C E6
02-23 11:46:13.121  3509  3526 V AlarmManager:  remove PendingIntent] PendingIntent{86e4231: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:13.121  9847  9911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,02-23 11:46:13.121  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:13.121  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.121  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.121  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-23 11:46:13.121  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-23 11:46:13.121  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:13.121  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.121  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[6ad45288-6074-487c-b683-03a4a8e47a45], mManufacturerSpecificData={}, mServiceData={6ad45288-6074-487c-b683-03a4a8e47a45=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.121  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:13.121  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:13.121  9847  9911 D BluetoothLeAdvertiser: start advertising
,02-23 11:46:13.121  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:13.131  3509  4426 V AlarmManager:  remove PendingIntent] PendingIntent{2034d16: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.131  5348  5666 D BtGatt.GattService: registerClient() - UUID=53eaa866-dbef-4ed1-b705-a3cd4715fdec
,02-23 11:46:13.171  5348  5421 D BtGatt.GattService: onClientRegistered() - UUID=53eaa866-dbef-4ed1-b705-a3cd4715fdec, clientIf=8
,02-23 11:46:13.171  9847  9857 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,02-23 11:46:13.171  5348  5612 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,02-23 11:46:13.181  5348  5612 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-23 11:46:13.181  5348  5612 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:13.181  5348  5481 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
02-23 11:46:13.181  5348  5481 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
02-23 11:46:13.181  5348  5435 D BtGatt.AdvertiseManager: message : 0
,02-23 11:46:13.181  5348  5435 D BtGatt.AdvertiseManager: number of adv instance running = 0
02-23 11:46:13.181  5348  5435 D BtGatt.AdvertiseManager: size of list is =0
,02-23 11:46:13.181  5348  5435 D BtGatt.AdvertiseManager: starting advertising
,02-23 11:46:13.181  5348  5435 D BtGatt.AdvertiseManager: isStandardAdv = false
,02-23 11:46:13.181  5348  5481 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 4
02-23 11:46:13.181  5348  5481 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24797446
02-23 11:46:13.181  5348  5481 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
02-23 11:46:13.181  5348  5481 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-23 11:46:13.181  5348  5481 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,02-23 11:46:13.191  3509  3990 V AlarmManager:  remove PendingIntent] PendingIntent{1e8b697: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.191  5348  5421 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,02-23 11:46:13.191  5348  5435 D BtGatt.AdvertiseManager: starting multi advertising
,02-23 11:46:13.191  5348  5421 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,02-23 11:46:13.191  5348  5435 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
02-23 11:46:13.191  5348  5435 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
02-23 11:46:13.191  3509  4065 V AlarmManager:  remove PendingIntent] PendingIntent{781f084: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.191  5348  5435 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
,02-23 11:46:13.191  5348  5435 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
02-23 11:46:13.191  9847  9858 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
02-23 11:46:13.191  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.191  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:13.191  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
02-23 11:46:13.191  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.191  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.191  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.191  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:13.191  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.191  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
02-23 11:46:13.191  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,02-23 11:46:13.191  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.191  9847  9911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,02-23 11:46:13.201  3509  4434 V AlarmManager:  remove PendingIntent] PendingIntent{3b3d06d: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.201  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.201  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:13.201  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.201  9847  9911 I io.jxcore.node.ConnectionHelper: start: OK
02-23 11:46:13.201  9847  9847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.201  9847  9847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.201  9847  9847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,02-23 11:46:13.201  3509  3990 V AlarmManager:  remove PendingIntent] PendingIntent{e5f24a2: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.201  9847  9847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.201  9847  9847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,02-23 11:46:13.211  3509  3856 V AlarmManager:  remove PendingIntent] PendingIntent{2f82533: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.211  3509  4933 V AlarmManager:  remove PendingIntent] PendingIntent{76f90f0: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.211  3509  3842 V AlarmManager:  remove PendingIntent] PendingIntent{24a0669: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.221  3509  4299 V AlarmManager:  remove PendingIntent] PendingIntent{5aee8ee: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.461  3509  4172 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:13.471  3509  4172 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:13.471  3509  4172 D BatteryService: online:4, current avg:-24, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:121
02-23 11:46:13.471  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:13.471  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:13.471  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:13.471  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:13.471  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:13.471  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:13.471  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:13.471  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:13.471  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:13.471  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:13.471  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:13.481  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:13.481  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:13.481  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:13.491  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:13.501  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
02-23 11:46:13.501  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:13.521  3509  4933 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:13.701  9847  9960 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
02-23 11:46:13.701  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
02-23 11:46:13.701  9847  9911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
02-23 11:46:13.701  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
02-23 11:46:13.701  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
02-23 11:46:13.701  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
02-23 11:46:13.701  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
02-23 11:46:13.701  9847  9911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
02-23 11:46:13.701  9847  9977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
02-23 11:46:13.701  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
02-23 11:46:13.701  9847  9977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
02-23 11:46:13.701  9847  9977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
02-23 11:46:13.701  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,02-23 11:46:13.701  9847  9911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f812260 removed from the list
,02-23 11:46:13.701  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f812260 removed from the list
,02-23 11:46:13.701  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
02-23 11:46:13.701  9847  9911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,02-23 11:46:13.701  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.701  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,02-23 11:46:13.701  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
02-23 11:46:13.701  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.701  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:13.701  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.701  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.701  9847  9982 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 210
,02-23 11:46:13.701  9847  9982 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,02-23 11:46:13.701  9847  9982 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 210)
02-23 11:46:13.701  5348  5660 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
02-23 11:46:13.701  9847  9847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
02-23 11:46:13.701  9847  9982 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 210)
02-23 11:46:13.701  9847  9847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,02-23 11:46:13.701  9847  9847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
02-23 11:46:13.701  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:13.711  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:13.711  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,02-23 11:46:13.711  9847  9976 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
02-23 11:46:13.711  9847  9976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
02-23 11:46:13.711  9847  9976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 210)
,02-23 11:46:13.711  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:13.711  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:13.711  9847  9911 D BluetoothLeScanner: could not find callback wrapper
02-23 11:46:13.711  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
02-23 11:46:13.711  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.711  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.711  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.711  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
02-23 11:46:13.711  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.711  9847  9911 D BluetoothAdapter: STATE_ON
,02-23 11:46:13.721  9847  9911 D BluetoothAdapter: STATE_ON
02-23 11:46:13.721  9847  9911 D BluetoothLeAdvertiser: stop advertising
,02-23 11:46:13.721  5348  5360 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-23 11:46:13.721  5348  5360 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-23 11:46:13.721  5348  5435 D BtGatt.AdvertiseManager: message : 1
02-23 11:46:13.721  5348  5481 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
02-23 11:46:13.721  5348  5481 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 23, currDate: 23
02-23 11:46:13.721  5348  5481 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,02-23 11:46:13.721  5348  5481 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-23 11:46:13.721  5348  5481 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
02-23 11:46:13.721  5348  5435 D BtGatt.AdvertiseManager: stop advertise for client =  8
02-23 11:46:13.721  5348  5435 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
02-23 11:46:13.731  5348  5435 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,02-23 11:46:13.731  5348  5421 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
,02-23 11:46:13.731  5348  5421 D BtGatt.GattService: Client app is not null!
,02-23 11:46:13.731  9847  9858 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,02-23 11:46:13.731  3509  4300 V AlarmManager:  remove PendingIntent] PendingIntent{c85e18f: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:13.731  5348  5359 D BtGatt.GattService: unregisterClient() - clientIf=8
02-23 11:46:13.731  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,02-23 11:46:13.731  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.731  3509  4411 V AlarmManager:  remove PendingIntent] PendingIntent{354cc1c: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
02-23 11:46:13.731  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
02-23 11:46:13.731  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.731  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.731  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
,02-23 11:46:13.731  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
02-23 11:46:13.731  9847  9911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
02-23 11:46:13.731  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
02-23 11:46:13.731  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.741  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.741  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,02-23 11:46:13.741  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.741  9847  9911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-23 11:46:13.741  9847  9911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b51319 removed from the list
02-23 11:46:13.741  9847  9911 D io.jxcore.node.ConnectivityMonitor: stop
02-23 11:46:13.741  9847  9911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,02-23 11:46:13.741  9847  9847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-23 11:46:13.741  9847  9847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-23 11:46:13.741  9847  9847 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
02-23 11:46:13.741  9847  9847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
02-23 11:46:13.741  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,02-23 11:46:13.741  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
02-23 11:46:13.741  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
02-23 11:46:13.741  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.741  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.741  9847  9847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-23 11:46:13.741  9847  9847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,02-23 11:46:13.741  3509  3525 V AlarmManager:  remove PendingIntent] PendingIntent{af3a025: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.751  3509  4300 V AlarmManager:  remove PendingIntent] PendingIntent{624a5fa: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.751  3509  4426 V AlarmManager:  remove PendingIntent] PendingIntent{18907ab: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.761  3509  4435 V AlarmManager:  remove PendingIntent] PendingIntent{f08e08: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.761  3509  4411 V AlarmManager:  remove PendingIntent] PendingIntent{3e319a1: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.761  3509  3525 V AlarmManager:  remove PendingIntent] PendingIntent{d0727c6: PendingIntentRecord{8735618 com.android.bluetooth broadcastIntent}}
,02-23 11:46:13.791  3509  4300 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:13.791  3509  4300 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4321, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:13.791  3509  4300 D BatteryService: online:4, current avg:-22, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:16
02-23 11:46:13.791  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:13.791  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:13.791  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:13.791  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:13.791  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:13.801  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:13.801  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:13.801  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:13.801  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:13.801  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:13.801  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:13.801  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:13.811  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:13.811  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:13.811  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:13.811  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
02-23 11:46:13.821  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:13.851  3509  4411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:14.061  3509  3525 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:14.061  3509  3525 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:14.061  3509  3525 D BatteryService: online:4, current avg:-20, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:123
02-23 11:46:14.061  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:14.071  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:14.071  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:14.071  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:14.071  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:14.071  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:14.071  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:14.071  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:14.071  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:14.071  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:14.071  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:14.081  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:14.081  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:14.081  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:14.081  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:14.101  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:14.101  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:14.171  3509  4843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:14.171  3509  4843 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4320, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:14.171  3509  4843 D BatteryService: online:4, current avg:-18, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:65
02-23 11:46:14.171  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:14.171  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:14.171  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:14.171  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:14.171  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:14.181  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:14.181  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:14.181  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:14.191  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:14.191  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:14.191  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:14.201  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:14.211  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:14.211  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:14.211  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:14.231  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:14.231  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:14.241  9847  9847 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,02-23 11:46:14.471  3509  4172 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:14.471  3509  4172 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4320, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:14.471  3509  4172 D BatteryService: online:4, current avg:-16, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:28
02-23 11:46:14.481  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:14.481  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:14.481  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:14.481  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:14.481  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:14.481  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:14.481  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:14.481  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:14.491  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:14.491  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:14.491  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:14.501  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:14.501  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:14.501  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:14.501  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:14.521  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:14.521  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:14.561  3509  3526 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:14.561  3509  3526 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4320, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:14.561  3509  3526 D BatteryService: online:4, current avg:-15, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:28
02-23 11:46:14.561  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:14.571  3509  3509 I MotionRecognitionService: Plugged
,02-23 11:46:14.571  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:14.571  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:14.571  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:14.571  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:14.571  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-23 11:46:14.571  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:14.571  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:14.571  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:14.571  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:14.581  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:14.581  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-23 11:46:14.581  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:14.591  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:14.601  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
02-23 11:46:14.601  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:14.891  3509  3856 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:14.891  3509  3856 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4328, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:14.891  3509  3856 D BatteryService: online:4, current avg:-12, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:132
02-23 11:46:14.891  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:14.891  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:14.891  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:14.891  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:14.891  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:14.891  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:14.891  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:14.901  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:14.901  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:14.901  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:14.901  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:14.911  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:14.911  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:14.911  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:14.911  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:14.921  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:14.921  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:14.961  3509  4299 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-23 11:46:15.261  3509  4172 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:15.271  3509  4172 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:15.271  3509  4172 D BatteryService: online:4, current avg:-7, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:138
02-23 11:46:15.271  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:15.271  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:15.271  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:15.271  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:15.271  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:15.281  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:15.281  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:15.281  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
02-23 11:46:15.281  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
02-23 11:46:15.281  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
02-23 11:46:15.281  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:15.301  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:15.311  5384  5384 D BatteryMonitor: new battery level: 100
02-23 11:46:15.311  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:15.311  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:15.311  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
02-23 11:46:15.311  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:15.391  3509  4065 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-23 11:46:15.391  3509  4065 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4324, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-23 11:46:15.391  3509  4065 D BatteryService: online:4, current avg:-6, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:81
02-23 11:46:15.391  3509  3509 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-23 11:46:15.391  3509  3509 I MotionRecognitionService: Plugged
02-23 11:46:15.401  3509  3509 D MotionRecognitionService:   cableConnection= 1
02-23 11:46:15.401  3509  3509 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-23 11:46:15.401  3509  3509 D MotionRecognitionService: skip setTransmitPower. 
,02-23 11:46:15.401  3509  3864 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-23 11:46:15.401  3944  3944 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-23 11:46:15.401  3944  3944 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-23 11:46:15.401  3944  3944 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-23 11:46:15.401  3944  3944 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,02-23 11:46:15.401  3944  3944 D PowerUI.Notification: There is no change about charging status, so return!
,02-23 11:46:15.411  5384  5384 D CommonServiceConfiguration: getStringValueSetting
,02-23 11:46:15.421  5348  5348 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-23 11:46:15.421  5348  5616 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-23 11:46:15.421  5384  5384 D BatteryMonitor: new battery level: 100
,02-23 11:46:15.431  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,02-23 11:46:15.431  3944  3944 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2

```
