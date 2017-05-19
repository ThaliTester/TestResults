#### Test 121460753250d573_thali03_samsung-SM-G935F Logs


```
--------- beginning of system
,05-19 12:11:28.792  3510  4518 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-19 12:11:28.792  3510  4518 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4348, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 12:11:28.792  3510  4518 D BatteryService: online:4, current avg:172, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:114
05-19 12:11:28.792  3510  3510 D BatteryService: Sending ACTION_BATTERY_CHANGED.
05-19 12:11:28.792  3510  3510 I MotionRecognitionService: Plugged
05-19 12:11:28.802  3510  3510 D MotionRecognitionService:   cableConnection= 1
05-19 12:11:28.802  3510  3510 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-19 12:11:28.802  3510  3510 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
05-19 12:11:28.802  3510  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
05-19 12:11:28.802  3942  3942 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-19 12:11:28.812  3942  3942 D KeyguardUpdateMonitor: handleBatteryUpdate
05-19 12:11:28.812  3942  3942 D PowerUI : priorPlugType = 2 mPlugType =  2
05-19 12:11:28.812  3942  3942 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-19 12:11:28.812  3942  3942 D PowerUI.Notification: There is no change about charging status, so return!
05-19 12:11:28.822  5067  5067 D CommonServiceConfiguration: getStringValueSetting
05-19 12:11:28.832  5021  5021 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-19 12:11:28.832  5021  5460 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-19 12:11:28.842  5067  5067 D BatteryMonitor: new battery level: 100
05-19 12:11:28.842  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-19 12:11:28.852  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-19 12:11:29.262  9656  9656 I FIPS_bssl: FIPS approved mode (1) | 9656 | app_process
05-19 12:11:29.262  9656  9656 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
05-19 12:11:29.272  9656  9656 D AndroidRuntime: CheckJNI is OFF
05-19 12:11:29.272  9656  9656 D AndroidRuntime: readGMSProperty: start
05-19 12:11:29.272  9656  9656 D AndroidRuntime: readGMSProperty: already setted!!
05-19 12:11:29.272  9656  9656 D AndroidRuntime: propertySet: couldn't set property (it is from app)
05-19 12:11:29.272  9656  9656 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
05-19 12:11:29.272  9656  9656 D AndroidRuntime: readGMSProperty: end
05-19 12:11:29.272  9656  9656 D AndroidRuntime: addProductProperty: start
05-19 12:11:29.282  9656  9656 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
05-19 12:11:29.312  9656  9656 I Radio-JNI: register_android_hardware_Radio DONE
05-19 12:11:29.312  9656  9656 E AffinityControl: AffinityControl: registerfunction enter
05-19 12:11:29.322  9656  9656 D AndroidRuntime: Calling main entry com.android.commands.am.Am
05-19 12:11:29.352  3510  4427 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
05-19 12:11:29.352  3510  4427 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in null rsrc of package com.rockwellautomation.thalitest
05-19 12:11:29.382  3510  4427 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:11:29.382  3510  4427 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-19 12:11:29.382  3510  4427 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.rockwellautomation.thalitest)
05-19 12:11:29.382  3510  4427 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3510  pkgName : ACTIVITY_RESUME_BOOSTER@7
05-19 12:11:29.392  3510  4427 D ActivityManager: mDVFSHelper.acquire()
05-19 12:11:29.392  3510  4427 V WindowManager: addAppToken: AppWindowToken{d0e0acb42 token=Token{e016d8d ActivityRecord{37d4e24 u0 com.rockwellautomation.thalitest/.MainActivity t19}}} to stack=2 task=19 at 0
05-19 12:11:29.392  3015  3828 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (174 us)
05-19 12:11:29.412  3510  3610 I InjectionManager: Inside getClassLibPath caller 
05-19 12:11:29.412  3510  4427 D InputDispatcher: Focused application set to: xxxx
05-19 12:11:29.412  3510  3610 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{98a809a V.E...... R.....ID 0,0-0,0}
05-19 12:11:29.412  3510  3610 D SecWifiDisplayUtil: Metadata value : SecSettings2
05-19 12:11:29.412  3510  4427 D InputDispatcher: Focus left window: 6316
05-19 12:11:29.412  3510  3599 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{5871dbf u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
05-19 12:11:29.412  3510  3610 D ISSUE_DEBUG: InputChannelName : 47b79a8 Starting com.rockwellautomation.thalitest
05-19 12:11:29.412  3942  3942 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
05-19 12:11:29.412  9656  9656 D AndroidRuntime: Shutting down VM
05-19 12:11:29.422  3510  3610 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3510 uid:1000
05-19 12:11:29.422  3510  3610 D PointerIcon: setMouseCustomIcon IconType is same.101
05-19 12:11:29.422  3015  3015 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
05-19 12:11:29.432  9666  9666 E Zygote  : v2
05-19 12:11:29.432  9666  9666 I libpersona: KNOX_SDCARD checking this for 10078
05-19 12:11:29.432  9666  9666 I libpersona: KNOX_SDCARD not a persona
05-19 12:11:29.432  9666  9666 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 12:11:29.432  9666  9666 E Zygote  : accessInfo : 0
05-19 12:11:29.432  9666  9666 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.rockwellautomation.thalitest 
05-19 12:11:29.432  3510  3529 I ActivityManager: Start proc 9666:com.rockwellautomation.thalitest/u0a78 for activity com.rockwellautomation.thalitest/.MainActivity
05-19 12:11:29.442  9666  9666 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:11:29.442  9666  9666 D ActivityThread: Added TimaKeyStore provider
05-19 12:11:29.452  3510  3610 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
05-19 12:11:29.452  3510  3857 D NetworkPolicy: isUidForegroundLocked: 10078, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
05-19 12:11:29.452  3510  4407 V WindowOrientationListener: setCurrentAppOrientation :-1
05-19 12:11:29.452  3510  4407 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
05-19 12:11:29.452  3510  4407 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
05-19 12:11:29.452  3510  4407 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
05-19 12:11:29.452  3510  4407 D ActivityManager:  Launching com.rockwellautomation.thalitest, updated priority
05-19 12:11:29.452  4300  4300 D Launcher.HomeView: onStop
05-19 12:11:29.452  4300  4300 D capture : ----destroy
05-19 12:11:29.452  4300  4300 V ActivityThread: updateVisibility : ActivityRecord{9617f26 token=android.os.BinderProxy@93036dd {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
05-19 12:11:29.452  3510  3510 D GameManagerService: NotifyRunnable. pkg: com.rockwellautomation.thalitest, type: 4, isMinimized: false, isTunableApp: false
05-19 12:11:29.462  3015  3026 D libEGL  : eglTerminate EGLDisplay = 0x7f8137ee78
05-19 12:11:29.462  3015  3026 D libEGL  : eglTerminate EGLDisplay = 0x7f8137ee78
05-19 12:11:29.472  3510  3598 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.rockwellautomation.thalitest
05-19 12:11:29.472  3510  3598 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
05-19 12:11:29.472  3510  3610 V WindowStateAnimator: Finishing drawing window Window{47b79a8 u0 d0 Starting com.rockwellautomation.thalitest}: mDrawState=DRAW_PENDING
05-19 12:11:29.472  3510  6241 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-19 12:11:29.472  3510  6241 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-19 12:11:29.472  4300  4300 D Launcher: onTrimMemory. Level: 20
05-19 12:11:29.472  3015  3015 D libEGL  : eglInitialize EGLDisplay = 0x7ffcdd1c68
05-19 12:11:29.472  9666  9666 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 12:11:29.472  9666  9666 D RelationGraph: garbageCollect()
05-19 12:11:29.482  3510  3599 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{47b79a8 u0 d0 Starting com.rockwellautomation.thalitest}
05-19 12:11:29.482  9666  9666 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in com.rockwellautomation.thalitest rsrc of package com.rockwellautomation.thalitest
05-19 12:11:29.482  3510  3530 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:11:29.482  9666  9666 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-19 12:11:29.482  3510  6241 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 12:11:29.492  3510  6241 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-19 12:11:29.492  9666  9666 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:11:29.492  3510  6241 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 12:11:29.492  3510  6241 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-19 12:11:29.492  3510  6241 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-19 12:11:29.492  9666  9666 I InjectionManager: Inside getClassLibPath caller 
05-19 12:11:29.502  3015  4460 D libEGL  : eglTerminate EGLDisplay = 0x7f7a600e78
05-19 12:11:29.502  3015  4460 D libEGL  : eglTerminate EGLDisplay = 0x7f7a600e78
05-19 12:11:29.502  9666  9666 D InjectionManager: InjectionManager
05-19 12:11:29.502  9666  9666 D InjectionManager: fillFeatureStoreMap com.rockwellautomation.thalitest
05-19 12:11:29.502  9666  9666 I InjectionManager: Constructor com.rockwellautomation.thalitest, Feature store :{}
05-19 12:11:29.502  9666  9666 I InjectionManager: featureStore :{}
05-19 12:11:29.512  9666  9666 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in com.rockwellautomation.thalitest rsrc of package com.rockwellautomation.thalitest
05-19 12:11:29.512  9666  9666 D RelationGraph: garbageCollect()
05-19 12:11:29.512  9666  9666 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in com.rockwellautomation.thalitest rsrc of package com.rockwellautomation.thalitest
05-19 12:11:29.532  9666  9666 I CordovaLog: Changing log level to DEBUG(3)
05-19 12:11:29.532  9666  9666 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
05-19 12:11:29.532  9666  9666 D CordovaActivity: CordovaActivity.onCreate()
05-19 12:11:29.542  9666  9666 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
05-19 12:11:29.562  3510  3521 I art     : Background partial concurrent mark sweep GC freed 325851(21MB) AllocSpace objects, 85(5MB) LOS objects, 31% free, 34MB/50MB, paused 1.278ms total 156.403ms
05-19 12:11:29.582  9666  9666 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.rockwellautomation.thalitest rsrc of package com.google.android.webview
05-19 12:11:29.582  9666  9666 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:11:29.582  9666  9666 I InjectionManager: Inside getClassLibPath caller 
05-19 12:11:29.592  9666  9666 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
05-19 12:11:29.632  9666  9666 I cr_LibraryLoader: Time to load native libraries: 23 ms (timestamps 5176-5199)
05-19 12:11:29.632  9666  9666 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,05-19 12:11:29.642  9666  9680 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.rockwellautomation.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,05-19 12:11:29.662  9666  9666 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dfb586d}
05-19 12:11:29.662  9666  9666 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,05-19 12:11:29.682  9666  9666 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,05-19 12:11:29.712  9666  9666 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,05-19 12:11:29.712  3510  3882 D MdnieScenarioControlService:  packageName : com.rockwellautomation.thalitest    className : com.rockwellautomation.thalitest.MainActivity
,05-19 12:11:29.792  9666  9666 D libEGL  : eglInitialize EGLDisplay = 0xffecf094
,05-19 12:11:29.812  3510  3882 I MdnieScenarioControlService: mGameModeLauncher : false
,05-19 12:11:29.832  3510  3882 I MdnieScenarioControlService: setUIMode
,05-19 12:11:29.832  3510  3529 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10078
05-19 12:11:29.832  3510  3529 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,05-19 12:11:29.852  3510  3857 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,05-19 12:11:29.852  3015  3827 I SurfaceFlinger: id=9 Removed MauncherAct (4/15)
,05-19 12:11:29.852  3015  3024 I SurfaceFlinger: id=17 Removed VSBConnecti (4/14)
,05-19 12:11:29.852  3015  3024 I SurfaceFlinger: id=9 Removed MauncherAct (-2/14)
,05-19 12:11:29.852  3015  4460 I SurfaceFlinger: id=16 Removed VSBConnecti (5/13)
05-19 12:11:29.852  3015  3024 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/13)
05-19 12:11:29.852  3015  4460 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/13)
,05-19 12:11:29.862  3942  3942 D ImageWallpaper: onVisibilityChanged:false
,05-19 12:11:29.862  3942  3942 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
05-19 12:11:29.862  3942  3942 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
05-19 12:11:29.862  3942  3942 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,05-19 12:11:29.862  3015  3015 D libEGL  : eglTerminate EGLDisplay = 0x7ffcdd1d88
,05-19 12:11:29.862  3015  3015 D libEGL  : eglTerminate EGLDisplay = 0x7ffcdd1d88
,05-19 12:11:29.862  3015  3015 D libEGL  : eglTerminate EGLDisplay = 0x7ffcdd1d88
,05-19 12:11:29.872  9666  9666 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10078, CallingPid : 9666
,05-19 12:11:29.872  3510  4407 D ConnectivityService: listenForNetwork for Listen from uid/pid:10078/9666 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:11:29.872  3510  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
05-19 12:11:29.872  3510  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-19 12:11:29.872  3510  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,05-19 12:11:29.882  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 12:11:29.882  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-19 12:11:29.882  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 12:11:29.882  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 12:11:29.882  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-19 12:11:29.882  3510  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:11:29.882  9666  9666 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,05-19 12:11:29.892  9666  9666 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,05-19 12:11:29.892  9666  9666 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,05-19 12:11:29.912  9666  9666 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,05-19 12:11:29.912  9666  9666 D PluginManager: init()
,05-19 12:11:29.922  9666  9666 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,05-19 12:11:29.922  9666  9666 I cr_Ime  : ImeThread is not enabled.
,05-19 12:11:29.932  9666  9666 D Activity: performCreate Call Injection manager
,05-19 12:11:29.932  9666  9666 D CordovaActivity: Started the activity.
05-19 12:11:29.932  9666  9666 I InjectionManager: dispatchOnViewCreated > Target : com.rockwellautomation.thalitest.MainActivity isFragment :false
05-19 12:11:29.932  9666  9666 D CordovaActivity: Resumed the activity.
,05-19 12:11:29.932  9666  9666 D SecWifiDisplayUtil: Metadata value : SecSettings2
,05-19 12:11:29.942  9666  9666 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5b2f549 I.E...... R.....ID 0,0-0,0}
,05-19 12:11:29.942  9666  9715 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,05-19 12:11:29.942  3510  4040 D ISSUE_DEBUG: InputChannelName : d449723 com.rockwellautomation.thalitest/com.rockwellautomation.thalitest.MainActivity
,05-19 12:11:29.952  3510  4059 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
05-19 12:11:29.952  3510  4059 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
05-19 12:11:29.952  3510  3510 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,05-19 12:11:29.952  3510  3510 I KnoxTimeoutHandler: Shared devices show user statefalse
,05-19 12:11:29.952  9666  9666 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10078, CallingPid : 9666
05-19 12:11:29.952  9666  9680 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.rockwellautomation.thalitest/shared_prefs/com.rockwellautomation.thalitest_preferences.xml.bak
,05-19 12:11:29.952  3510  4983 D ConnectivityService: listenForNetwork for Listen from uid/pid:10078/9666 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:11:29.952  3510  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
05-19 12:11:29.952  3510  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-19 12:11:29.952  3510  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,05-19 12:11:29.962  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 12:11:29.962  3510  3857 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,05-19 12:11:29.962  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-19 12:11:29.962  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-19 12:11:29.972  9666  9666 D SecWifiDisplayUtil: Metadata value : SecSettings2
05-19 12:11:29.972  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-19 12:11:29.972  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-19 12:11:29.972  3015  3015 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
05-19 12:11:29.972  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-19 12:11:29.972  3510  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:11:29.982  3510  4947 D InputDispatcher: Focus entered window: 9666
05-19 12:11:29.982  3510  3610 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3510 uid:1000
05-19 12:11:29.982  3510  3610 D PointerIcon: setMouseCustomIcon IconType is same.101
05-19 12:11:29.982  9666  9715 D libEGL  : eglInitialize EGLDisplay = 0xdc83f7c4
05-19 12:11:29.982  9666  9715 I OpenGLRenderer: Initialized EGL, version 1.4
05-19 12:11:29.982  9666  9715 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,05-19 12:11:29.992  9666  9666 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,05-19 12:11:30.012  9666  9719 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
05-19 12:11:30.012  9666  9719 D libEGL  : eglInitialize EGLDisplay = 0xd9eff3e4
,05-19 12:11:30.022  9666  9719 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.rockwellautomation.thalitest
,05-19 12:11:30.032  3510  4406 V WindowStateAnimator: Finishing drawing window Window{d449723 u0 d0 com.rockwellautomation.thalitest/com.rockwellautomation.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,05-19 12:11:30.032  9666  9666 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,05-19 12:11:30.032  3510  3530 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,05-19 12:11:30.042  3510  3610 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,05-19 12:11:30.042  3510  3510 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
05-19 12:11:30.042  3510  3610 I ActivityManager: Displayed com.rockwellautomation.thalitest/.MainActivity: +621ms
05-19 12:11:30.042  3510  3610 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3510  tag : ACTIVITY_RESUME_BOOSTER@7
05-19 12:11:30.042  3510  3610 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{37d4e24 u0 com.rockwellautomation.thalitest/.MainActivity t19} time:175613
05-19 12:11:30.042  3510  3610 D ActivityManager: mDVFSHelper.release()
05-19 12:11:30.042  3510  3610 D ViewRootImpl: #3 mView = null
,05-19 12:11:30.042  3510  3598 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3510  pkgName : ACTIVITY_RESUME_BOOSTER@13
,05-19 12:11:30.042  3510  3510 I KnoxTimeoutHandler: SD activityfalse
,05-19 12:11:30.042  3015  3015 D libEGL  : eglInitialize EGLDisplay = 0x7ffcdd1c68
,05-19 12:11:30.052  4814  4814 D SamsungIME: IMPL finishInput
05-19 12:11:30.052  4814  4814 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
05-19 12:11:30.052  4814  4814 D SamsungIME: saveAndClear +
05-19 12:11:30.052  4814  4814 D SamsungIME: saveAndClear -
,05-19 12:11:30.072  3510  3529 V WindowStateAnimator: Finishing drawing window Window{d449723 u0 d0 com.rockwellautomation.thalitest/com.rockwellautomation.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,05-19 12:11:30.072  9666  9666 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,05-19 12:11:30.082  9666  9666 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9666
,05-19 12:11:30.082  3015  3015 D libEGL  : eglInitialize EGLDisplay = 0x7ffcdd1c68
05-19 12:11:30.082  9666  9666 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
05-19 12:11:30.082  9666  9666 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,05-19 12:11:30.082  9666  9666 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ef9e6d8 time:175655
,05-19 12:11:30.082  6316  6316 V ActivityThread: updateVisibility : ActivityRecord{f53058 token=android.os.BinderProxy@cbe8dfa {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,05-19 12:11:30.092  3015  3015 D libEGL  : eglInitialize EGLDisplay = 0x7ffcdd1c68
,05-19 12:11:30.142  9666  9666 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,05-19 12:11:30.232  3015  4460 I SurfaceFlinger: id=18 Removed uhalitest (7/13)
,05-19 12:11:30.232  3015  3026 I SurfaceFlinger: id=18 Removed uhalitest (-2/13)
,05-19 12:11:30.242  3015  3015 D libEGL  : eglTerminate EGLDisplay = 0x7ffcdd1d88
,05-19 12:11:30.262  9666  9728 D jxcore_app_log: JniHelper::setJavaVM(0xf4c34000), pthread_self() = -701302480
,05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a334c80 added. We now have 1 listener(s)
,05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a334c80 added. We now have 1 listener(s)
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,05-19 12:11:30.272  9666  9728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
,05-19 12:11:30.272  9666  9728 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "A8:81:95:E9:5F:6F"Peer extra info: "256
05-19 12:11:30.272  9666  9728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-19 12:11:30.272  9666  9728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
,05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 12:11:30.272  9666  9728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f73e5f added. We now have 2 listener(s)
05-19 12:11:30.272  9666  9728 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,05-19 12:11:30.272  9666  9728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
05-19 12:11:30.272  9666  9728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 9601
05-19 12:11:30.272  9666  9728 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 133
05-19 12:11:30.272  9666  9728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
05-19 12:11:30.272  9666  9728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
05-19 12:11:30.272  9666  9728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
05-19 12:11:30.272  9666  9728 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 133
,05-19 12:11:30.282  9666  9728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 12:11:30.282  9666  9728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
,05-19 12:11:30.282  9666  9728 D BluetoothAdapter: STATE_ON
,05-19 12:11:30.282  9666  9728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
05-19 12:11:30.282  9666  9728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-19 12:11:30.282  9666  9728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:11:30.282  9666  9728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:11:30.282  9666  9728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:11:30.282  9666  9728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:11:30.282  9666  9728 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 12:11:30.282  9666  9728 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 12:11:30.282  9666  9728 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 12:11:30.282  9666  9728 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-19 12:11:30.282  9666  9728 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
05-19 12:11:30.282  9666  9728 D io.jxcore.node.ConnectivityMonitor: start: OK
,05-19 12:11:30.282  9666  9728 I io.jxcore.node.LifeCycleMonitor: start: OK
,05-19 12:11:30.292  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:30.292  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:30.292  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:30.292  9666  9666 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,05-19 12:11:30.302  9666  9666 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
05-19 12:11:30.302  9666  9666 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,05-19 12:11:30.342  3510  3510 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3510  tag : ACTIVITY_RESUME_BOOSTER@13
,05-19 12:11:30.352  3510  3882 D MdnieScenarioControlService:  packageName : com.rockwellautomation.thalitest    className : com.rockwellautomation.thalitest.MainActivity
,05-19 12:11:30.452  4025  4025 D Recents : onTaskStackChanged
,05-19 12:11:30.452  3510  3882 I MdnieScenarioControlService: mGameModeLauncher : false
,05-19 12:11:30.452  3510  3882 I MdnieScenarioControlService: setUIMode
,05-19 12:11:30.452  4025  4025 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.rockwellautomation.thalitest
,05-19 12:11:30.472  4025  4025 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:11:30.472  3510  6243 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in null rsrc of package com.rockwellautomation.thalitest
,05-19 12:11:30.592  3510  6241 D SSRM:n  : SIOP:: AP = 310, PST = 300 (W:6), CP = 253, CUR = 172, LCD = 30
,05-19 12:11:30.592  3510  6241 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 12:11:30.792  9666  9729 W jxcore-log: Initializing JXcore engine
05-19 12:11:30.792  9666  9729 W jxcore-log: JXcore engine is ready
,05-19 12:11:30.812  5027  5027 E audit   : type=1400 msg=audit(1495188690.812:264): avc:  denied  { ioctl } for  pid=9729 comm="Thread-134" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1061 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
05-19 12:11:30.812  5027  5027 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-19 12:11:30.812  5027  5027 E audit   : type=1300 msg=audit(1495188690.812:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d567f3c8 items=0 ppid=3183 pid=9729 auid=4294967295 uid=10078 gid=10078 euid=10078 suid=10078 fsuid=10078 egid=10078 sgid=10078 fsgid=10078 tty=(none) ses=4294967295 comm="Thread-134" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-19 12:11:30.812  5027  5027 E audit   : type=1327 msg=audit(1495188690.812:264): proctitle="com.rockwellautomation.thalitest"
05-19 12:11:30.812  5027  5027 E audit   : type=1320 msg=audit(1495188690.812:264): 
05-19 12:11:30.812  5027  5027 E audit   : type=1400 msg=audit(1495188690.812:265): avc:  denied  { ioctl } for  pid=9729 comm="Thread-134" path="socket:[43017]" dev="sockfs" ino=43017 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
05-19 12:11:30.812  5027  5027 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-19 12:11:30.812  5027  5027 E audit   : type=1300 msg=audit(1495188690.812:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=2 a3=d567f3c8 items=0 ppid=3183 pid=9729 auid=4294967295 uid=10078 gid=10078 euid=10078 suid=10078 fsuid=10078 egid=10078 sgid=10078 fsgid=10078 tty=(none) ses=4294967295 comm="Thread-134" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-19 12:11:30.812  5027  5027 E audit   : type=1327 msg=audit(1495188690.812:265): proctitle="com.rockwellautomation.thalitest"
05-19 12:11:30.812  5027  5027 E audit   : type=1320 msg=audit(1495188690.812:265): 
,05-19 12:11:30.812  9666  9729 W jxcore-log: Starting JXcore engine
,05-19 12:11:30.852  9666  9729 W jxcore-log: Platform android
05-19 12:11:30.852  9666  9729 W jxcore-log: 
05-19 12:11:30.852  9666  9729 W jxcore-log: Process ARCH arm
05-19 12:11:30.852  9666  9729 W jxcore-log: 
,05-19 12:11:30.982  9666  9729 I jxcore-log: JXcore Cordova bridge is ready!
05-19 12:11:30.982  9666  9729 I jxcore-log: 
05-19 12:11:30.982  9666  9729 W jxcore-log: JXcore engine is started
,05-19 12:11:30.992  9666  9728 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,05-19 12:11:30.992  9666  9666 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
05-19 12:11:30.992  9666  9666 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,05-19 12:11:32.402  3510  3909 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/19_task.xml.bak
,05-19 12:11:32.472  3510  6241 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
,05-19 12:11:35.512  3510  6241 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 12:11:38.022  9666  9729 I jxcore-log: 2017-05-19 10:11:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
05-19 12:11:38.022  9666  9729 I jxcore-log: 
,05-19 12:11:38.022  9666  9729 I jxcore-log: 2017-05-19 10:11:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
05-19 12:11:38.022  9666  9729 I jxcore-log: 
05-19 12:11:38.022  9666  9729 I jxcore-log: 2017-05-19 10:11:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
05-19 12:11:38.022  9666  9729 I jxcore-log: 
,05-19 12:11:38.032  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:38.032  9666  9729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-19 12:11:38.032  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:11:38.032  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:11:38.032  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:11:38.032  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:11:38.032  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 12:11:38.032  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 12:11:38.032  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 12:11:38.032  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 12:11:38.042  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:38.042  9666  9729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-19 12:11:38.042  9666  9729 I jxcore-log: 2017-05-19 10:11:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
05-19 12:11:38.042  9666  9729 I jxcore-log: 
05-19 12:11:38.042  9666  9729 I jxcore-log: 2017-05-19 10:11:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
05-19 12:11:38.042  9666  9729 I jxcore-log: 
,05-19 12:11:38.042  9666  9729 I jxcore-log: 2017-05-19 10:11:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
05-19 12:11:38.042  9666  9729 I jxcore-log: 
,05-19 12:11:38.312  9666  9729 D ExecuteNativeTests: Running unit tests
05-19 12:11:38.312  9666  9729 D BluetoothAdapter: enable()
,05-19 12:11:38.322  9666  9729 D BluetoothAdapter: enable(): BT is already enabled..!
,05-19 12:11:38.332  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d2be550 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:11:38.332  9666  9729 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 12:11:38.342  3510  4947 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 12:11:38.342  3510  4947 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 12:11:38.342  3510  4947 D WifiService: setWifiEnabled: true pid=9666, uid=10078
,05-19 12:11:38.342  3510  4947 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 12:11:38.352  3510  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-19 12:11:38.352  3510  4947 W WifiService: Failed getting userId using ActivityManagerNative
05-19 12:11:38.352  3510  4947 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:11:38.352  3510  4947 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:11:38.352  3510  4947 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 12:11:38.352  3510  4947 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 12:11:38.352  3510  4947 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 12:11:38.352  3510  4947 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 12:11:38.352  3510  4947 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 12:11:38.352  3510  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-19 12:11:38.352  3510  4947 D SettingsProvider: isChangeAllowed() : name = wifi_on
,05-19 12:11:38.352  3510  3863 D WifiStateMachine: setFccChannel: channel = 0
05-19 12:11:38.352  3510  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-19 12:11:38.352  3510  3860 D WifiBigDataLog: init : 
05-19 12:11:38.352  3510  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-19 12:11:38.362  3510  3860 D WifiStateMachine: setFccChannelNative: channel = 0
05-19 12:11:38.362  3510  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-19 12:11:38.362  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{76f3349 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:11:38.852  3510  3529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-19 12:11:38.852  3510  3529 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4340, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 12:11:38.852  3510  3529 D BatteryService: online:4, current avg:-210, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:205
05-19 12:11:38.852  3510  3510 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-19 12:11:38.862  3510  3510 I MotionRecognitionService: Plugged
,05-19 12:11:38.862  3510  3510 D MotionRecognitionService:   cableConnection= 1
05-19 12:11:38.862  3510  3510 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,05-19 12:11:38.862  3510  3510 D MotionRecognitionService: skip setTransmitPower. 
,05-19 12:11:38.862  3510  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-19 12:11:38.872  3942  3942 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-19 12:11:38.872  3942  3942 D KeyguardUpdateMonitor: handleBatteryUpdate
05-19 12:11:38.872  3942  3942 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-19 12:11:38.872  3942  3942 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-19 12:11:38.872  3942  3942 D PowerUI.Notification: There is no change about charging status, so return!
,05-19 12:11:38.892  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,05-19 12:11:38.902  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-19 12:11:38.902  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 12:11:38.902  5021  5021 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-19 12:11:38.902  5021  5460 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-19 12:11:38.912  5067  5067 D BatteryMonitor: new battery level: 100
,05-19 12:11:39.472  3510  3628 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,05-19 12:11:39.492  3510  3628 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,05-19 12:11:40.622  3510  6241 D SSRM:n  : SIOP:: AP = 360, PST = 305 (W:6), CP = 265, CUR = -210, LCD = 30
,05-19 12:11:40.642  3510  6241 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 12:11:44.402  3510  3612 I PowerManagerService: [PWL] On : 0 (189975 ms ago)
05-19 12:11:44.402  3510  3612 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,05-19 12:11:45.562  3510  6262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-19 12:11:48.322  3510  4150 E Watchdog: !@Sync 6 [05-19 12:11:48.329]
,05-19 12:11:48.372  9666  9729 I com.test.thalitest.ThaliTestRunner: Running UT
,05-19 12:11:48.432  9666  9729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-19 12:11:48.432  9666  9729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73fbabf added. We now have 2 listener(s)
05-19 12:11:48.432  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73fbabf added. We now have 3 listener(s)
05-19 12:11:48.432  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 12:11:48.432  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "A8:81:95:E9:5F:6F"Peer extra info: "256
05-19 12:11:48.432  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-19 12:11:48.432  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
05-19 12:11:48.432  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 12:11:48.432  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc2e58c added. We now have 4 listener(s)
05-19 12:11:48.432  9666  9729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,05-19 12:11:48.432  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-19 12:11:48.442  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:48.452  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,05-19 12:11:48.452  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-19 12:11:48.452  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-19 12:11:48.452  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-19 12:11:48.452  9666  9729 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
05-19 12:11:48.452  9666  9729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
05-19 12:11:48.452  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
05-19 12:11:48.452  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,05-19 12:11:48.452  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-19 12:11:48.452  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
05-19 12:11:48.452  9666  9729 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,05-19 12:11:48.452  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,05-19 12:11:48.462  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,05-19 12:11:48.462  9666  9729 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,05-19 12:11:48.462  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-19 12:11:48.482  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:48.482  9666  9729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-19 12:11:48.482  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:11:48.482  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:11:48.482  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:11:48.482  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:11:48.482  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 12:11:48.482  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 12:11:48.482  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 12:11:48.482  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 12:11:48.482  9666  9729 D io.jxcore.node.ConnectivityMonitor: start: OK
05-19 12:11:48.482  9666  9729 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
05-19 12:11:48.482  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
05-19 12:11:48.482  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 12:11:48.492  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
05-19 12:11:48.492  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
05-19 12:11:48.492  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:48.492  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-19 12:11:48.492  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:48.492  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:11:48.492  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
05-19 12:11:48.492  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:48.492  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-19 12:11:48.492  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 12:11:48.492  9666  9729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-19 12:11:48.492  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-19 12:11:48.492  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-19 12:11:48.502  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-19 12:11:48.502  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,05-19 12:11:48.502  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-19 12:11:48.502  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-19 12:11:48.502  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-19 12:11:48.502  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,05-19 12:11:48.502  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 12:11:48.502  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
05-19 12:11:48.502  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-19 12:11:48.502  9666  9666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,05-19 12:11:48.502  9666  9734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-19 12:11:48.512  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-19 12:11:48.512  9666  9729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-19 12:11:48.512  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-19 12:11:48.512  9666  9734 D BluetoothSocket: bindListen(): myUserId = 0
05-19 12:11:48.512  9666  9734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-19 12:11:48.512  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:48.512  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:48.512  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:48.522  9666  9734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-19 12:11:48.522  9666  9734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@1bf43db, port: 6, type: 1, local socket address: null, socket type: 0
,05-19 12:11:48.522  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:48.522  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-19 12:11:48.522  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:48.532  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:48.532  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-19 12:11:48.532  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-19 12:11:48.532  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
05-19 12:11:48.532  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:48.532  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:48.532  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:48.532  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-19 12:11:48.532  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-19 12:11:48.532  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "2c7c4446-495b-40f1-ba37-3ac33ac5ee28", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-19 12:11:48.532  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 A8 81 95 E9 5F 6F
,05-19 12:11:48.542  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-19 12:11:48.542  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 12:11:48.542  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:48.542  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:48.542  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-19 12:11:48.542  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 12:11:48.542  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:48.542  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:48.542  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:48.542  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:48.542  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:48.542  9666  9729 D BluetoothLeAdvertiser: start advertising
05-19 12:11:48.542  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:48.552  5021  5045 D BtGatt.GattService: registerClient() - UUID=3da9d330-8cb4-417d-95d5-337a17ff28b7
,05-19 12:11:48.602  5021  5159 D BtGatt.GattService: onClientRegistered() - UUID=3da9d330-8cb4-417d-95d5-337a17ff28b7, clientIf=7
,05-19 12:11:48.612  9666  9677 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-19 12:11:48.612  5021  5461 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-19 12:11:48.632  5021  5461 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 12:11:48.632  5021  5461 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:11:48.632  5021  5218 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
05-19 12:11:48.632  5021  5194 D BtGatt.AdvertiseManager: message : 0
05-19 12:11:48.632  5021  5218 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
,05-19 12:11:48.632  5021  5194 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-19 12:11:48.632  5021  5194 D BtGatt.AdvertiseManager: size of list is =0
,05-19 12:11:48.642  5021  5194 D BtGatt.AdvertiseManager: starting advertising
,05-19 12:11:48.652  5021  5194 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-19 12:11:48.652  5021  5218 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 6
05-19 12:11:48.652  5021  5218 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24919811
,05-19 12:11:48.652  5021  5218 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-19 12:11:48.652  5021  5218 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 12:11:48.652  5021  5218 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 12:11:48.662  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{2970e68: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:48.662  5021  5159 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-19 12:11:48.662  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{d250281: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:48.672  5021  5194 D BtGatt.AdvertiseManager: starting multi advertising
,05-19 12:11:48.672  5021  5159 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,05-19 12:11:48.672  5021  5194 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,05-19 12:11:48.672  5021  5194 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-19 12:11:48.672  5021  5194 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-19 12:11:48.672  5021  5194 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,05-19 12:11:48.672  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{4b8f26: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:48.682  9666  9676 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,05-19 12:11:48.682  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:48.682  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:48.682  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-19 12:11:48.682  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:48.682  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:48.682  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:48.682  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:48.682  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:48.682  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-19 12:11:48.692  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{32db767: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:48.692  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-19 12:11:48.692  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:48.692  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:48.692  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:48.692  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:48.692  9666  9729 I io.jxcore.node.ConnectionHelper: start: OK
,05-19 12:11:48.692  9666  9666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 12:11:48.692  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{902a914: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:48.702  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-19 12:11:48.702  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-19 12:11:48.702  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-19 12:11:48.702  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-19 12:11:48.702  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-19 12:11:48.702  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-19 12:11:48.702  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 12:11:48.702  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-19 12:11:48.702  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-19 12:11:48.702  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,05-19 12:11:48.702  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-19 12:11:48.702  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 12:11:48.702  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-19 12:11:48.702  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
05-19 12:11:48.702  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{f1e45bd: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:48.712  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
05-19 12:11:48.712  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-19 12:11:48.712  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-19 12:11:48.712  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-19 12:11:48.712  9666  9666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
05-19 12:11:48.712  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{65177b2: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:48.902  3510  4983 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-19 12:11:48.902  3510  4983 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4340, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 12:11:48.902  3510  4983 D BatteryService: online:4, current avg:18, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:96
05-19 12:11:48.912  3510  3510 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-19 12:11:48.912  3510  3510 I MotionRecognitionService: Plugged
,05-19 12:11:48.912  3510  3510 D MotionRecognitionService:   cableConnection= 1
05-19 12:11:48.912  3510  3510 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-19 12:11:48.912  3510  3510 D MotionRecognitionService: skip setTransmitPower. 
,05-19 12:11:48.922  3510  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-19 12:11:48.922  3942  3942 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-19 12:11:48.922  3942  3942 D KeyguardUpdateMonitor: handleBatteryUpdate
05-19 12:11:48.922  3942  3942 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-19 12:11:48.932  3942  3942 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-19 12:11:48.932  3942  3942 D PowerUI.Notification: There is no change about charging status, so return!
,05-19 12:11:48.942  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 12:11:48.942  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,05-19 12:11:48.952  5021  5021 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-19 12:11:48.952  5021  5460 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-19 12:11:48.962  5067  5067 D BatteryMonitor: new battery level: 100
,05-19 12:11:48.972  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 12:11:49.202  9666  9736 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-19 12:11:49.202  9666  9729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2,710:2710:2710:2710:2710]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
05-19 12:11:49.202  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
05-19 12:11:49.202  9666  9729 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
05-19 12:11:49.212  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-19 12:11:49.212  9666  9729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
05-19 12:11:49.212  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-19 12:11:49.212  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-19 12:11:49.212  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-19 12:11:49.212  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-19 12:11:49.212  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-19 12:11:49.212  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-19 12:11:49.212  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-19 12:11:49.212  9666  9734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-19 12:11:49.212  9666  9734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-19 12:11:49.212  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-19 12:11:49.212  9666  9734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-19 12:11:49.212  9666  9666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-19 12:11:49.212  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.212  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-19 12:11:49.212  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-19 12:11:49.212  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.212  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.212  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.212  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.212  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.222  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:49.222  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-19 12:11:49.222  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.222  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.222  9666  9729 D BluetoothLeScanner: could not find callback wrapper
05-19 12:11:49.222  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-19 12:11:49.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:49.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.232  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-19 12:11:49.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:49.232  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.232  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.232  9666  9729 D BluetoothLeAdvertiser: stop advertising
,05-19 12:11:49.242  5021  5036 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 12:11:49.242  5021  5036 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:11:49.242  5021  5194 D BtGatt.AdvertiseManager: message : 1
05-19 12:11:49.242  5021  5218 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
05-19 12:11:49.242  5021  5218 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 12:11:49.252  5021  5218 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 12:11:49.252  5021  5218 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 12:11:49.252  5021  5194 D BtGatt.AdvertiseManager: stop advertise for client =  7
,05-19 12:11:49.252  5021  5194 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
05-19 12:11:49.252  5021  5218 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,05-19 12:11:49.252  5021  5194 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-19 12:11:49.252  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{8d46303: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.252  5021  5159 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
05-19 12:11:49.252  5021  5159 D BtGatt.GattService: Client app is not null!
05-19 12:11:49.252  9666  9677 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-19 12:11:49.262  5021  5045 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-19 12:11:49.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-19 12:11:49.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-19 12:11:49.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:49.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.262  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{feb4280: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:49.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:49.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-19 12:11:49.262  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,05-19 12:11:49.272  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-19 12:11:49.272  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:49.272  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.272  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,05-19 12:11:49.272  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.272  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.272  9666  9666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,05-19 12:11:49.272  9666  9666 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-19 12:11:49.272  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{46e80b9: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.272  9666  9666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,05-19 12:11:49.272  9666  9666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-19 12:11:49.272  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 12:11:49.272  9666  9666 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,05-19 12:11:49.272  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 12:11:49.272  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-19 12:11:49.282  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-19 12:11:49.282  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-19 12:11:49.282  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-19 12:11:49.282  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 12:11:49.282  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,05-19 12:11:49.282  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 12:11:49.282  9666  9666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 12:11:49.282  9666  9739 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,05-19 12:11:49.282  9666  9729 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-19 12:11:49.282  9666  9729 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-19 12:11:49.282  9666  9729 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
05-19 12:11:49.282  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
05-19 12:11:49.282  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-19 12:11:49.282  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:11:49.282  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:11:49.282  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:49.282  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{65b5cfe: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}},
,05-19 12:11:49.282  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-19 12:11:49.292  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:11:49.292  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
05-19 12:11:49.292  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.292  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything,
05-19 12:11:49.292  9666  9729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,05-19 12:11:49.292  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{5b02c5f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:49.292  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-19 12:11:49.292  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 12:11:49.292  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-19 12:11:49.292  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-19 12:11:49.292  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-19 12:11:49.292  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-19 12:11:49.292  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,05-19 12:11:49.292  9666  9666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-19 12:11:49.292  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-19 12:11:49.292  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-19 12:11:49.292  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,05-19 12:11:49.292  9666  9740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-19 12:11:49.302  9666  9740 D BluetoothSocket: bindListen(): myUserId = 0
05-19 12:11:49.302  9666  9740 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 12:11:49.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-19 12:11:49.302  9666  9729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,05-19 12:11:49.302  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
05-19 12:11:49.302  9666  9740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-19 12:11:49.302  9666  9740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@66b898d, port: 6, type: 1, local socket address: null, socket type: 0
05-19 12:11:49.302  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{9552f7b: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.302  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.302  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.312  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.312  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{1dee198: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.312  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.312  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-19 12:11:49.312  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.312  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.312  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-19 12:11:49.312  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-19 12:11:49.312  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
05-19 12:11:49.312  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{8328df1: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.312  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:49.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.322  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-19 12:11:49.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-19 12:11:49.322  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "2c7c4446-495b-40f1-ba37-3ac33ac5ee28", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-19 12:11:49.322  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 A8 81 95 E9 5F 6F
05-19 12:11:49.322  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-19 12:11:49.322  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 12:11:49.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-19 12:11:49.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 12:11:49.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:49.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.322  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.322  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.322  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.322  9666  9729 D BluetoothLeAdvertiser: start advertising
,05-19 12:11:49.322  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.332  5021  5461 D BtGatt.GattService: registerClient() - UUID=56c67346-8335-4ad5-896e-578efd3277ae
,05-19 12:11:49.372  5021  5159 D BtGatt.GattService: onClientRegistered() - UUID=56c67346-8335-4ad5-896e-578efd3277ae, clientIf=7
,05-19 12:11:49.372  9666  9676 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-19 12:11:49.372  5021  5036 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-19 12:11:49.372  5021  5036 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 12:11:49.372  5021  5036 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:11:49.372  5021  5194 D BtGatt.AdvertiseManager: message : 0
05-19 12:11:49.372  5021  5218 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
05-19 12:11:49.372  5021  5218 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 12:11:49.382  5021  5194 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-19 12:11:49.382  5021  5194 D BtGatt.AdvertiseManager: size of list is =0
,05-19 12:11:49.382  5021  5194 D BtGatt.AdvertiseManager: starting advertising
,05-19 12:11:49.382  5021  5194 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-19 12:11:49.382  5021  5218 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 7
05-19 12:11:49.382  5021  5218 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24919811
,05-19 12:11:49.382  5021  5218 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-19 12:11:49.382  5021  5218 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 12:11:49.382  5021  5218 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 12:11:49.392  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{e2c0dd6: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.392  5021  5159 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-19 12:11:49.392  5021  5194 D BtGatt.AdvertiseManager: starting multi advertising
,05-19 12:11:49.392  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{e7d4857: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.392  5021  5159 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
05-19 12:11:49.392  5021  5194 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,05-19 12:11:49.392  5021  5194 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-19 12:11:49.392  5021  5194 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-19 12:11:49.392  5021  5194 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
05-19 12:11:49.392  9666  9677 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-19 12:11:49.392  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.392  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.392  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-19 12:11:49.392  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.392  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.392  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.392  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.392  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.392  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-19 12:11:49.402  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{1ac7f44: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:49.402  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,05-19 12:11:49.402  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.402  9666  9729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,05-19 12:11:49.402  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.402  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.402  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.402  9666  9729 I io.jxcore.node.ConnectionHelper: start: OK
05-19 12:11:49.402  9666  9666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 12:11:49.402  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-19 12:11:49.402  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-19 12:11:49.402  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,05-19 12:11:49.402  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{7d1182d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:49.402  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-19 12:11:49.402  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-19 12:11:49.402  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-19 12:11:49.402  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 12:11:49.402  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-19 12:11:49.402  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,05-19 12:11:49.402  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 12:11:49.402  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-19 12:11:49.402  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 12:11:49.402  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-19 12:11:49.402  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-19 12:11:49.412  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-19 12:11:49.412  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-19 12:11:49.412  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{9333162: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:49.412  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-19 12:11:49.412  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-19 12:11:49.412  9666  9666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-19 12:11:49.412  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{7a412f3: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.412  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{9944bb0: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.422  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{d540a29: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.722  4361  4472 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
05-19 12:11:49.722  4361  4472 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,05-19 12:11:49.862  4361  4472 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 138ms lastUpdatedAfter : 128135ms
,05-19 12:11:49.902  9666  9742 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-19 12:11:49.902  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
05-19 12:11:49.902  9666  9729 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-19 12:11:49.902  9666  9729 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-19 12:11:49.902  9666  9729 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
05-19 12:11:49.902  9666  9729 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
05-19 12:11:49.912  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
05-19 12:11:49.912  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 12:11:49.912  9666  9666 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,05-19 12:11:49.912  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:11:49.912  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-19 12:11:49.912  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:49.912  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 12:11:49.922  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:11:49.922  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-19 12:11:49.922  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:49.922  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
05-19 12:11:49.922  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 9601
05-19 12:11:49.922  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
05-19 12:11:49.922  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
05-19 12:11:49.922  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
05-19 12:11:49.922  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
05-19 12:11:49.922  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
05-19 12:11:49.922  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
05-19 12:11:49.922  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
05-19 12:11:49.922  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.922  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
05-19 12:11:49.922  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.922  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.922  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:49.922  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.932  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.932  9666  9729 D BluetoothLeAdvertiser: stop advertising
,05-19 12:11:49.932  5021  5541 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:11:49.932  5021  5541 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 12:11:49.932  5021  5194 D BtGatt.AdvertiseManager: message : 1
05-19 12:11:49.932  5021  5218 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
05-19 12:11:49.932  5021  5218 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 12:11:49.932  5021  5218 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 12:11:49.932  5021  5218 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 12:11:49.932  5021  5218 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-19 12:11:49.932  5021  5194 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-19 12:11:49.932  5021  5194 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-19 12:11:49.942  5021  5194 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-19 12:11:49.942  5021  5159 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,05-19 12:11:49.942  5021  5159 D BtGatt.GattService: Client app is not null!
,05-19 12:11:49.942  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{c9701ae: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:49.942  9666  9676 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-19 12:11:49.942  5021  5045 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-19 12:11:49.942  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-19 12:11:49.942  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.942  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-19 12:11:49.942  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:49.942  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.942  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.952  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-19 12:11:49.952  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.952  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.952  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:49.952  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-19 12:11:49.952  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-19 12:11:49.952  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{962eb4f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:49.952  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "2c7c4446-495b-40f1-ba37-3ac33ac5ee28", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-19 12:11:49.952  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 A8 81 95 E9 5F 6F
,05-19 12:11:49.952  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 12:11:49.952  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 12:11:49.952  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.952  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.952  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,05-19 12:11:49.952  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 12:11:49.952  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.952  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.952  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:49.952  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.952  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.952  9666  9729 D BluetoothLeAdvertiser: start advertising
05-19 12:11:49.952  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{ea72dc: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.962  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:49.962  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{4fa1fe5: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.962  5021  5036 D BtGatt.GattService: registerClient() - UUID=d148ee88-cc8c-4064-937b-ccccba6ebae3
,05-19 12:11:49.972  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{4558aba: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.972  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{e8ced6b: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.982  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{e19e0c8: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:49.982  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{631d561: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.002  5021  5159 D BtGatt.GattService: onClientRegistered() - UUID=d148ee88-cc8c-4064-937b-ccccba6ebae3, clientIf=7
,05-19 12:11:50.002  9666  9677 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-19 12:11:50.012  5021  5461 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-19 12:11:50.012  5021  5461 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:11:50.012  5021  5461 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:11:50.012  5021  5194 D BtGatt.AdvertiseManager: message : 0
,05-19 12:11:50.012  5021  5218 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
05-19 12:11:50.012  5021  5218 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 12:11:50.012  5021  5194 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-19 12:11:50.012  5021  5194 D BtGatt.AdvertiseManager: size of list is =0
,05-19 12:11:50.022  5021  5194 D BtGatt.AdvertiseManager: starting advertising
,05-19 12:11:50.022  5021  5194 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-19 12:11:50.022  5021  5218 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 8
,05-19 12:11:50.022  5021  5218 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24919811
05-19 12:11:50.022  5021  5218 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-19 12:11:50.022  5021  5218 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,05-19 12:11:50.022  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{c419886: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.022  5021  5218 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 12:11:50.022  5021  5159 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-19 12:11:50.032  5021  5194 D BtGatt.AdvertiseManager: starting multi advertising
,05-19 12:11:50.032  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{20af547: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.032  5021  5159 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
05-19 12:11:50.032  5021  5194 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-19 12:11:50.032  5021  5194 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,05-19 12:11:50.032  5021  5194 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-19 12:11:50.032  5021  5194 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,05-19 12:11:50.032  9666  9676 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-19 12:11:50.032  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.032  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.032  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,05-19 12:11:50.032  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.032  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.032  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.032  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.032  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.032  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.032  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-19 12:11:50.032  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.032  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-19 12:11:50.032  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
05-19 12:11:50.032  9666  9729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
05-19 12:11:50.032  9666  9729 I io.jxcore.node.ConnectionHelper: start: OK
05-19 12:11:50.032  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.032  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-19 12:11:50.032  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-19 12:11:50.032  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,05-19 12:11:50.032  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.032  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-19 12:11:50.032  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.032  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-19 12:11:50.032  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-19 12:11:50.032  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.032  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.032  9666  9744 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
05-19 12:11:50.042  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{1504174: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:50.032  9666  9729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
05-19 12:11:50.042  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-19 12:11:50.042  9666  9729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,05-19 12:11:50.042  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-19 12:11:50.042  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-19 12:11:50.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,05-19 12:11:50.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-19 12:11:50.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-19 12:11:50.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-19 12:11:50.042  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-19 12:11:50.042  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-19 12:11:50.042  9666  9666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-19 12:11:50.042  9666  9740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-19 12:11:50.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.042  9666  9740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-19 12:11:50.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-19 12:11:50.042  9666  9740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-19 12:11:50.052  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{6d5669d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:50.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-19 12:11:50.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.042  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:50.042  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:50.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
05-19 12:11:50.042  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:50.052  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:50.052  9666  9729 D BluetoothLeScanner: could not find callback wrapper
05-19 12:11:50.052  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-19 12:11:50.052  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.052  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.052  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.052  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-19 12:11:50.052  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.052  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:50.052  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:50.052  9666  9729 D BluetoothLeAdvertiser: stop advertising
05-19 12:11:50.052  5021  5036 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:11:50.052  5021  5036 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:11:50.062  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{88eb712: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:50.062  5021  5218 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
05-19 12:11:50.062  5021  5218 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 12:11:50.062  5021  5218 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 12:11:50.062  5021  5218 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 12:11:50.062  5021  5218 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-19 12:11:50.062  5021  5194 D BtGatt.AdvertiseManager: message : 1
05-19 12:11:50.062  5021  5194 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-19 12:11:50.062  5021  5194 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
05-19 12:11:50.062  5021  5194 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
05-19 12:11:50.062  5021  5159 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
05-19 12:11:50.062  5021  5159 D BtGatt.GattService: Client app is not null!
05-19 12:11:50.062  9666  9677 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
05-19 12:11:50.062  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{a779ee3: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:50.062  5021  5045 D BtGatt.GattService: unregisterClient() - clientIf=7
05-19 12:11:50.062  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-19 12:11:50.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-19 12:11:50.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-19 12:11:50.072  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-19 12:11:50.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-19 12:11:50.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.072  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{dea00e0: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:50.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 12:11:50.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.072  9666  9666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
05-19 12:11:50.072  9666  9666 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-19 12:11:50.072  9666  9666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-19 12:11:50.072  9666  9666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-19 12:11:50.072  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 12:11:50.072  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 12:11:50.072  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-19 12:11:50.072  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.072  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-19 12:11:50.072  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-19 12:11:50.072  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.072  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.072  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.072  9666  9666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 12:11:50.072  9666  9745 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
05-19 12:11:50.072  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
05-19 12:11:50.072  9666  9729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-19 12:11:50.072  9666  9729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a2d1af added. We now have 3 listener(s)
05-19 12:11:50.072  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a2d1af added. We now have 5 listener(s)
05-19 12:11:50.072  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 12:11:50.072  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{626cf99: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:11:50.082  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-19 12:11:50.082  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-19 12:11:50.082  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 12:11:50.082  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@590c9bc added. We now have 6 listener(s)
,05-19 12:11:50.082  9666  9729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-19 12:11:50.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
05-19 12:11:50.082  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{b1d325e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:50.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-19 12:11:50.092  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{186166a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.092  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:50.092  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{e8075b: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.092  9666  9729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-19 12:11:50.092  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:11:50.092  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:11:50.092  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:11:50.092  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:11:50.092  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 12:11:50.092  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 12:11:50.092  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 12:11:50.092  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-19 12:11:50.092  9666  9729 D io.jxcore.node.ConnectivityMonitor: start: OK
,05-19 12:11:50.092  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{6b0bf8: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.102  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:50.102  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{509d8d1: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.102  9666  9729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:50.102  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{7e72f36: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.102  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:50.112  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{795be37: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.112  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:50.112  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{40efa4: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.122  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:50.122  9666  9729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-19 12:11:50.122  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:11:50.122  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:11:50.122  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:11:50.122  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:11:50.122  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 12:11:50.122  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 12:11:50.122  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 12:11:50.122  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 12:11:50.122  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-19 12:11:50.122  9666  9729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-19 12:11:50.122  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-19 12:11:50.122  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-19 12:11:50.122  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,05-19 12:11:50.122  9666  9729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a2d1af removed from the list
05-19 12:11:50.122  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a2d1af removed from the list
05-19 12:11:50.122  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-19 12:11:50.122  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@590c9bc removed from the list
05-19 12:11:50.122  9666  9729 D io.jxcore.node.ConnectivityMonitor: stop
05-19 12:11:50.122  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,05-19 12:11:50.122  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,05-19 12:11:50.122  9666  9729 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,05-19 12:11:50.122  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,05-19 12:11:50.122  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,05-19 12:11:50.122  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
05-19 12:11:50.122  9666  9729 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,05-19 12:11:50.132  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
,05-19 12:11:50.132  9666  9729 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,05-19 12:11:50.132  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
05-19 12:11:50.132  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,05-19 12:11:50.132  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-19 12:11:50.132  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-19 12:11:50.132  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,05-19 12:11:50.132  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-19 12:11:50.132  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,05-19 12:11:50.132  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-19 12:11:50.132  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-19 12:11:50.132  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,05-19 12:11:50.132  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
05-19 12:11:50.132  9666  9729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-19 12:11:50.132  9666  9729 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
05-19 12:11:50.132  9666  9729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,05-19 12:11:50.132  9666  9729 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
,05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
,05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
,05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
,05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
,05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
,05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
,05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
,05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
,05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
05-19 12:11:50.132  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
05-19 12:11:50.132  9666  9729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,05-19 12:11:50.132  9666  9729 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-19 12:11:50.132  9666  9729 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
05-19 12:11:50.132  9666  9729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,05-19 12:11:50.132  9666  9729 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-19 12:11:50.132  9666  9729 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
05-19 12:11:50.132  9666  9729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-19 12:11:50.132  9666  9729 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-19 12:11:50.132  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
05-19 12:11:50.142  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
05-19 12:11:50.142  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
05-19 12:11:50.142  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
05-19 12:11:50.142  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
05-19 12:11:50.142  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,05-19 12:11:50.142  9666  9729 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
05-19 12:11:50.142  9666  9729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,05-19 12:11:50.142  9666  9729 E io.jxcore.node.ConnectionHelper: connect: Callback is null
05-19 12:11:50.142  9666  9746 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 206)
,05-19 12:11:50.142  9666  9746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
,05-19 12:11:50.142  9666  9746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
05-19 12:11:50.142  9666  9746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
,05-19 12:11:50.142  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
05-19 12:11:50.142  9666  9729 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
05-19 12:11:50.152  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,05-19 12:11:50.152  9666  9729 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
05-19 12:11:50.152  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
05-19 12:11:50.152  9666  9729 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,05-19 12:11:50.152  9666  9729 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
05-19 12:11:50.152  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-19 12:11:50.152  9666  9729 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
05-19 12:11:50.152  9666  9729 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,05-19 12:11:50.152  9666  9746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
05-19 12:11:50.152  9666  9729 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,05-19 12:11:50.152  9666  9746 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
05-19 12:11:50.152  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
05-19 12:11:50.152  9666  9729 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
05-19 12:11:50.152  9666  9729 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
05-19 12:11:50.152  9666  9729 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
05-19 12:11:50.152  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
05-19 12:11:50.152  9666  9729 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,05-19 12:11:50.152  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
05-19 12:11:50.152  9666  9729 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-19 12:11:50.152  9666  9729 V io.jxcore.node.ConnectivityMonitor: start: Already started
,05-19 12:11:50.152  9666  9729 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,05-19 12:11:50.152  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
05-19 12:11:50.152  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 12:11:50.152  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-19 12:11:50.152  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-19 12:11:50.152  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.152  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-19 12:11:50.162  9666  9746 D BluetoothSocket: connect(): myUserId = 0
,05-19 12:11:50.162  9666  9746 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 12:11:50.162  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-19 12:11:50.162  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-19 12:11:50.162  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.162  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 12:11:50.162  9666  9729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,05-19 12:11:50.162  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-19 12:11:50.162  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-19 12:11:50.162  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-19 12:11:50.162  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-19 12:11:50.162  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-19 12:11:50.162  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-19 12:11:50.162  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-19 12:11:50.162  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,05-19 12:11:50.162  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 12:11:50.162  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
05-19 12:11:50.162  9666  9666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-19 12:11:50.162  9666  9747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-19 12:11:50.162  9666  9747 D BluetoothSocket: bindListen(): myUserId = 0
05-19 12:11:50.162  9666  9747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 12:11:50.172  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-19 12:11:50.172  9666  9729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-19 12:11:50.172  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
05-19 12:11:50.172  9666  9747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-19 12:11:50.172  9666  9747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@b54d9cb, port: 6, type: 1, local socket address: null, socket type: 0
,05-19 12:11:50.172  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:50.172  3510  4059 D SecContentProvider: insert(), uri = 2
,05-19 12:11:50.172  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:50.172  5021  5414 W bt_btif : bta_dm_acl_change(), event : 2
,05-19 12:11:50.172  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{76f6210: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.172  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:50.182  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.182  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-19 12:11:50.182  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:50.182  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{2add109: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.182  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:50.182  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-19 12:11:50.182  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-19 12:11:50.182  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
,05-19 12:11:50.182  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:50.182  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{fa8ef0e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.182  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.182  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.182  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-19 12:11:50.182  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-19 12:11:50.182  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "2c7c4446-495b-40f1-ba37-3ac33ac5ee28", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-19 12:11:50.182  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 A8 81 95 E9 5F 6F
05-19 12:11:50.182  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 12:11:50.182  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-19 12:11:50.182  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.182  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.182  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-19 12:11:50.182  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-19 12:11:50.192  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.192  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.192  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.192  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:50.192  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:50.192  9666  9729 D BluetoothLeAdvertiser: start advertising
,05-19 12:11:50.192  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:50.192  5021  5045 D BtGatt.GattService: registerClient() - UUID=b1f765bd-6994-440e-9999-1cbdf70b1190
,05-19 12:11:50.232  5021  5159 D BtGatt.GattService: onClientRegistered() - UUID=b1f765bd-6994-440e-9999-1cbdf70b1190, clientIf=7
,05-19 12:11:50.232  9666  9677 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-19 12:11:50.242  5021  5036 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-19 12:11:50.242  5021  5036 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:11:50.242  5021  5036 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 12:11:50.242  5021  5194 D BtGatt.AdvertiseManager: message : 0
05-19 12:11:50.242  5021  5218 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
05-19 12:11:50.242  5021  5218 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 12:11:50.242  5021  5194 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-19 12:11:50.242  5021  5194 D BtGatt.AdvertiseManager: size of list is =0
,05-19 12:11:50.242  5021  5194 D BtGatt.AdvertiseManager: starting advertising
,05-19 12:11:50.252  5021  5194 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-19 12:11:50.252  5021  5218 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 9
,05-19 12:11:50.252  5021  5218 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24919811
05-19 12:11:50.252  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{6983d2f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:50.252  5021  5218 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-19 12:11:50.252  5021  5218 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 12:11:50.252  5021  5159 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
05-19 12:11:50.252  5021  5218 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 12:11:50.252  5021  5194 D BtGatt.AdvertiseManager: starting multi advertising
,05-19 12:11:50.262  5021  5159 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
05-19 12:11:50.262  5021  5194 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-19 12:11:50.262  5021  5194 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,05-19 12:11:50.262  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{2d08f3c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:50.262  5021  5194 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-19 12:11:50.262  5021  5194 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
05-19 12:11:50.262  9666  9676 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-19 12:11:50.262  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-19 12:11:50.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.262  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-19 12:11:50.262  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-19 12:11:50.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.262  9666  9729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,05-19 12:11:50.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.262  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.262  9666  9729 I io.jxcore.node.ConnectionHelper: start: OK
05-19 12:11:50.262  9666  9666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,05-19 12:11:50.262  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.262  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-19 12:11:50.262  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-19 12:11:50.262  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,05-19 12:11:50.262  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.262  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-19 12:11:50.262  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.262  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-19 12:11:50.262  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-19 12:11:50.262  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.262  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.272  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{2d974c5: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:50.262  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,05-19 12:11:50.262  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.262  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-19 12:11:50.272  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-19 12:11:50.272  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-19 12:11:50.272  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.272  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.272  9666  9666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-19 12:11:50.272  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{d88ee1a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.272  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{df57d4b: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.282  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{b56328: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.282  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{a619841: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.292  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{b37d1e6: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.672  3510  6241 D SSRM:n  : SIOP:: AP = 320, PST = 310 (W:14), CP = 266, CUR = 18, LCD = 30
,05-19 12:11:50.772  9666  9736 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-19 12:11:50.772  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-19 12:11:50.772  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-19 12:11:50.772  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,05-19 12:11:50.772  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-19 12:11:50.772  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-19 12:11:50.772  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,05-19 12:11:50.772  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-19 12:11:50.772  9666  9747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-19 12:11:50.772  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,05-19 12:11:50.772  9666  9747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-19 12:11:50.772  9666  9747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-19 12:11:50.772  9666  9666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,05-19 12:11:50.772  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
05-19 12:11:50.772  9666  9666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-19 12:11:50.772  9666  9666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-19 12:11:50.772  9666  9666 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,05-19 12:11:50.772  9666  9729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73fbabf removed from the list
05-19 12:11:50.772  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73fbabf removed from the list
05-19 12:11:50.772  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,05-19 12:11:50.772  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-19 12:11:50.772  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.772  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,05-19 12:11:50.772  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-19 12:11:50.772  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.772  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.772  9666  9749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 206
,05-19 12:11:50.772  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.772  9666  9749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
05-19 12:11:50.772  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.772  9666  9749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 206)
,05-19 12:11:50.772  9666  9749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 206)
05-19 12:11:50.772  5021  5525 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
05-19 12:11:50.782  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:50.782  9666  9746 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
05-19 12:11:50.782  9666  9746 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
05-19 12:11:50.782  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:50.782  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
05-19 12:11:50.782  9666  9746 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 206)
05-19 12:11:50.782  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:50.792  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:11:50.792  9666  9729 D BluetoothLeScanner: could not find callback wrapper
05-19 12:11:50.792  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-19 12:11:50.792  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.792  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.792  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.792  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-19 12:11:50.792  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.792  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:50.792  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:50.792  9666  9729 D BluetoothLeAdvertiser: stop advertising
,05-19 12:11:50.802  5021  5461 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 12:11:50.802  5021  5461 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:11:50.802  5021  5194 D BtGatt.AdvertiseManager: message : 1
05-19 12:11:50.802  5021  5218 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
,05-19 12:11:50.802  5021  5218 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 12:11:50.802  5021  5218 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 12:11:50.802  5021  5218 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 12:11:50.802  5021  5218 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-19 12:11:50.812  5021  5194 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-19 12:11:50.812  5021  5194 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-19 12:11:50.812  5021  5194 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-19 12:11:50.812  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{69ca327: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.812  5021  5159 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,05-19 12:11:50.812  5021  5159 D BtGatt.GattService: Client app is not null!
05-19 12:11:50.822  9666  9677 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-19 12:11:50.822  5021  5541 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-19 12:11:50.822  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{19189d4: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.822  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-19 12:11:50.822  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.822  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-19 12:11:50.822  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.822  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.822  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.822  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-19 12:11:50.822  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-19 12:11:50.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-19 12:11:50.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:50.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,05-19 12:11:50.832  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{ee777d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:50.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:50.832  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc2e58c removed from the list
05-19 12:11:50.832  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,05-19 12:11:50.832  9666  9729 D io.jxcore.node.ConnectivityMonitor: stop
05-19 12:11:50.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 12:11:50.832  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 12:11:50.832  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,05-19 12:11:50.832  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.832  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-19 12:11:50.832  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,05-19 12:11:50.832  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.832  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-19 12:11:50.832  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,05-19 12:11:50.832  9666  9666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,05-19 12:11:50.842  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{59f2672: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.852  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{a64ac3: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.862  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{7676f40: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.862  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{6700e79: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:50.872  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{cb537be: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:51.332  9666  9666 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-19 12:11:55.832  9666  9739 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,05-19 12:11:55.842  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,05-19 12:11:55.842  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-19 12:11:55.842  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-19 12:11:55.842  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-19 12:11:55.842  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,05-19 12:11:55.852  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-19 12:11:55.852  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-19 12:11:55.852  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,05-19 12:11:55.852  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-19 12:11:55.852  9666  9666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-19 12:11:55.852  9666  9750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-19 12:11:55.852  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,05-19 12:11:55.852  9666  9750 D BluetoothSocket: bindListen(): myUserId = 0
,05-19 12:11:55.852  9666  9750 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 12:11:55.852  9666  9729 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
05-19 12:11:55.852  9666  9729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
05-19 12:11:55.852  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,05-19 12:11:55.852  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-19 12:11:55.862  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,05-19 12:11:55.862  9666  9750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,05-19 12:11:55.862  9666  9750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@2123866, port: 6, type: 1, local socket address: null, socket type: 0
,05-19 12:11:55.872  9666  9729 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,05-19 12:11:55.872  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-19 12:11:55.872  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-19 12:11:55.872  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,05-19 12:11:55.872  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-19 12:11:55.872  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 12:11:55.872  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-19 12:11:55.882  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-19 12:11:55.882  9666  9750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,05-19 12:11:55.882  9666  9750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-19 12:11:55.882  9666  9750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-19 12:11:55.882  9666  9729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73fbabf not in the list
05-19 12:11:55.882  9666  9666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,05-19 12:11:55.882  9666  9729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73fbabf not in the list
05-19 12:11:55.882  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-19 12:11:55.882  9666  9666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-19 12:11:55.882  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-19 12:11:55.882  9666  9666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,05-19 12:11:55.882  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:55.882  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-19 12:11:55.882  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,05-19 12:11:55.882  9666  9729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-19 12:11:55.882  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 12:11:55.882  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:55.882  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:55.882  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 12:11:55.882  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:11:55.882  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:11:55.882  9666  9729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc2e58c not in the list
05-19 12:11:55.882  9666  9729 D io.jxcore.node.ConnectivityMonitor: stop
05-19 12:11:55.882  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,05-19 12:11:55.882  9666  9729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-19 12:11:55.882  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 12:11:55.882  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 12:11:55.882  9666  9666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,05-19 12:11:55.892  9666  9729 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
05-19 12:11:55.892  9666  9729 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
05-19 12:11:55.892  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-19 12:11:55.892  9666  9729 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,05-19 12:11:55.892  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-19 12:11:55.892  9666  9729 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
05-19 12:11:55.892  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,05-19 12:11:55.892  9666  9729 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,05-19 12:11:55.892  9666  9729 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,05-19 12:11:55.902  9666  9729 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,05-19 12:11:55.902  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,05-19 12:11:55.902  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,05-19 12:11:55.902  9666  9729 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
05-19 12:11:55.902  9666  9729 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
05-19 12:11:55.902  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,05-19 12:11:55.902  9666  9729 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
05-19 12:11:55.902  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
05-19 12:11:55.902  9666  9729 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
05-19 12:11:55.902  9666  9729 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,05-19 12:11:55.902  9666  9729 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
05-19 12:11:55.902  9666  9729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,05-19 12:11:55.902  9666  9729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,05-19 12:11:55.902  9666  9729 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
05-19 12:11:55.902  9666  9729 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
05-19 12:11:55.902  9666  9729 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
05-19 12:11:55.902  9666  9729 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
05-19 12:11:55.902  9666  9729 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,05-19 12:11:55.902  9666  9729 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,05-19 12:11:55.912  9666  9729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,05-19 12:11:55.912  9666  9729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d547a7 added. We now have 2 listener(s)
05-19 12:11:55.912  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d547a7 added. We now have 3 listener(s)
05-19 12:11:55.912  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-19 12:11:55.912  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:11:55.912  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-19 12:11:55.912  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-19 12:11:55.912  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 12:11:55.912  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fce9454 added. We now have 4 listener(s)
,05-19 12:11:55.912  9666  9729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-19 12:11:55.912  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-19 12:11:55.922  9666  9729 D BluetoothAdapter: enable()
,05-19 12:11:55.922  9666  9729 D BluetoothAdapter: enable(): BT is already enabled..!
,05-19 12:11:55.932  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b18d01f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:11:55.932  9666  9729 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 12:11:55.942  3510  4406 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
05-19 12:11:55.942  3510  4406 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 12:11:55.942  3510  4406 D WifiService: setWifiEnabled: true pid=9666, uid=10078
,05-19 12:11:55.942  3510  4406 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 12:11:55.942  3510  4406 W WifiService: Failed getting userId using ActivityManagerNative
05-19 12:11:55.942  3510  4406 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:11:55.942  3510  4406 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:11:55.942  3510  4406 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 12:11:55.942  3510  4406 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 12:11:55.942  3510  4406 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 12:11:55.942  3510  4406 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-19 12:11:55.942  3510  4406 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 12:11:55.942  3510  4406 D SettingsProvider: isChangeAllowed() : name = wifi_on
,05-19 12:11:55.942  3510  3863 D WifiStateMachine: setFccChannel: channel = 0
05-19 12:11:55.942  3510  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-19 12:11:55.942  3510  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-19 12:11:55.952  3510  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-19 12:11:55.952  9666  9729 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
05-19 12:11:55.952  3510  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-19 12:11:55.952  3510  3860 D WifiBigDataLog: init : 
,05-19 12:11:55.952  3510  3860 D WifiStateMachine: setFccChannelNative: channel = 0
,05-19 12:11:55.952  3510  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-19 12:11:55.952  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:55.962  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff43f6c u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
05-19 12:11:55.962  9666  9729 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,05-19 12:11:55.962  9666  9729 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
05-19 12:11:55.962  9666  9729 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,05-19 12:11:55.972  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:11:55.972  9666  9751 D BluetoothAdapter: disable()
,05-19 12:11:55.972  9666  9729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 12:11:55.972  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:11:55.972  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:11:55.972  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:11:55.972  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:11:55.972  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 12:11:55.972  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 12:11:55.972  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 12:11:55.972  9666  9729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 12:11:55.982  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fda1935 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:11:55.992  3510  4059 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 12:11:56.002  3510  3609 D SecContentProvider: insert(), uri = 2
,05-19 12:11:56.002  5021  5150 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,05-19 12:11:56.012  5021  5150 D BluetoothAdapterProperties: Setting state to 13
,05-19 12:11:56.012  5021  5150 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
05-19 12:11:56.012  5021  5150 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-19 12:11:56.012  5021  5150 D BluetoothAdapterService: updateAdapterState state is 13
,05-19 12:11:56.012  5021  5021 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
05-19 12:11:56.012  3510  3609 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
,05-19 12:11:56.012  5021  5150 D BluetoothAdapterService: Autoconnection is available 
,05-19 12:11:56.012  3510  3510 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:56.012  5021  5150 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
05-19 12:11:56.012  3510  3510 I InputMethodManagerService: [BT Setting State] State =13
,05-19 12:11:56.012  5021  5150 D BluetoothAdapterService: terminating service from this receiver
,05-19 12:11:56.012  3942  4148 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:56.012  3942  4148 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,05-19 12:11:56.022  4330  4330 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-19 12:11:56.022  4814  4814 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-19 12:11:56.022  3510  3510 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,05-19 12:11:56.022  3510  3510 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:56.022  3510  3510 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-19 12:11:56.032  9666  9666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,05-19 12:11:56.032  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 12:11:56.032  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:11:56.032  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:11:56.032  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:11:56.032  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
05-19 12:11:56.032  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 12:11:56.032  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 12:11:56.032  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 12:11:56.032  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 12:11:56.032  9666  9666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-19 12:11:56.032  9666  9666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-19 12:11:56.032  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5044f3b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cddfc12 9342:com.android.settings/1000}
,05-19 12:11:56.032  5021  5150 D BluetoothAdapterProperties: onBluetoothDisable()
,05-19 12:11:56.032  3942  3942 D BluetoothPbap: Proxy object disconnected
,05-19 12:11:56.032  3942  3942 D PbapServerProfile: Bluetooth service disconnected
,05-19 12:11:56.032  5021  5150 W bt_btif : btif_dm_cancel_discovery
,05-19 12:11:56.042  3510  3854 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,05-19 12:11:56.042  5021  5021 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
,05-19 12:11:56.042  5021  5021 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
,05-19 12:11:56.052  3510  4409 D SecContentProvider: insert(), uri = 2
,05-19 12:11:56.052  9342  9342 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
05-19 12:11:56.052  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{59be658: PendingIntentRecord{3a013b1 com.android.bluetooth broadcastIntent}}
05-19 12:11:56.052  5021  5150 I BluetoothAdapterState: Entering PendingCommandState
,05-19 12:11:56.052  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{45ea417: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:56.062  5021  5159 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-19 12:11:56.062  5021  5159 D BluetoothAdapterProperties: Scan Mode:20
,05-19 12:11:56.062  5021  5150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,05-19 12:11:56.062  9342  9342 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,05-19 12:11:56.072  3942  4233 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-19 12:11:56.072  3510  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5044f3b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
05-19 12:11:56.072  3510  3529 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,05-19 12:11:56.072  3942  3942 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,05-19 12:11:56.072  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:56.082  5021  5150 E BluetoothServiceJni: disableBrEdrNative:
05-19 12:11:56.082  5021  5150 E bt_bluedroid: disable_bredr
,05-19 12:11:56.082  5021  5155 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
05-19 12:11:56.082  5021  5155 E bt_btif : BTA_DisableBluetoothOnly
05-19 12:11:56.082  5021  5556 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-19 12:11:56.082  5021  5556 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
05-19 12:11:56.082  5021  5414 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
05-19 12:11:56.082  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-19 12:11:56.082  5021  5555 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-19 12:11:56.082  5021  5555 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,05-19 12:11:56.082  5021  5553 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,05-19 12:11:56.092  9342  9342 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,05-19 12:11:56.092  5021  5155 D IOP_DB_BT: db_close: nbr users 0
05-19 12:11:56.092  5021  5155 D IOP_DB_BT: db_close: free database
05-19 12:11:56.092  9342  9342 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,05-19 12:11:56.102  5021  5414 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
05-19 12:11:56.102  5021  5414 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
05-19 12:11:56.102  5021  5414 W bt_btif : bta_dm_acl_change(), event : 2
05-19 12:11:56.102  5021  5414 W bt_btif : bta_dm_acl_change(), event : 5
,05-19 12:11:56.102  3510  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5044f3b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{feb16e 4341:com.google.android.gms.persistent/u0a21}
,05-19 12:11:56.102  4341  4341 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-19 12:11:56.112  3510  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5044f3b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3c7fb0 8113:com.sec.android.app.shealth:remote/u0a39}
,05-19 12:11:56.122  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{e9f6ab3: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:56.132  3510  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5044f3b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cddfc12 9342:com.android.settings/1000}
,05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-19 12:11:56.142  5021  5414 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-19 12:11:56.152  5021  5021 D ObexServerSockets: shutdown(block = true)
,05-19 12:11:56.152  5021  5021 D ObexServerSockets: shutdown called from another thread - interrupt().
05-19 12:11:56.152  5021  5021 D ObexServerSockets: shutdown called from another thread - interrupt().
,05-19 12:11:56.152  5021  5021 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
05-19 12:11:56.152  5021  5021 D BluetoothSdpJni: SDP Remove record success - handle: 1
05-19 12:11:56.152  5021  5021 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
05-19 12:11:56.152  5021  5021 D BluetoothSdpJni: SDP Remove record success - handle: 0
05-19 12:11:56.152  5021  5021 I BtOppRfcommListener: stopping Accept Thread
05-19 12:11:56.152  5021  5553 I BtOppRfcommListener: BluetoothSocket listen thread finished
05-19 12:11:56.152  9342  9342 D LocalBluetoothProfileManager: PANU : true
05-19 12:11:56.152  5021  5150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
05-19 12:11:56.152  5021  5159 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,05-19 12:11:56.162  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{b3c5b9c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:56.162  3942  4148 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,05-19 12:11:56.162  5021  5159 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-19 12:11:56.162  5021  5159 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,05-19 12:11:56.162  5021  5021 V BluetoothOppManager: cleanUp...
,05-19 12:11:56.172  9342  9342 D BluetoothSap: Create BluetoothSap proxy object
,05-19 12:11:56.172  9342  9342 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
05-19 12:11:56.182  9342  9342 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,05-19 12:11:56.182  9342  9342 D DockEventReceiver: finishStartingService: stopping service
,05-19 12:11:56.192  9342  9342 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:56.192  9342  9342 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
,05-19 12:11:56.192  9342  9342 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,05-19 12:11:56.192  9342  9342 D BluetoothPan: BluetoothPAN Proxy object connected
,05-19 12:11:56.192  9342  9342 D PanProfile: Bluetooth service connected
,05-19 12:11:56.192  3510  4983 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5044f3b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10b237d 5021:com.android.bluetooth/1002}
05-19 12:11:56.202  9342  9342 D BluetoothSap: Proxy object connected
,05-19 12:11:56.202  9342  9342 D SapProfile: Bluetooth service connected
,05-19 12:11:56.212  3510  4983 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5044f3b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{818aca3 7218:com.google.android.apps.maps/u0a125}
,05-19 12:11:56.282  5021  5159 E BluetoothAdapterState: stateChangeCallback : 16
05-19 12:11:56.282  5021  5150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
05-19 12:11:56.282  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{521785d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:56.292  5021  5150 D BtConfig.SecureMode: isSecureModeOn:false
,05-19 12:11:56.292  5021  5150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,05-19 12:11:56.292  5021  5150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
05-19 12:11:56.292  5021  5021 D HeadsetService: Received stop request...Stopping profile...
,05-19 12:11:56.302  5021  5021 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
05-19 12:11:56.302  5021  5021 E HeadsetService: notifyProfileServiceStateChanged
,05-19 12:11:56.302  3942  3942 D HeadsetProfile: Bluetooth service disconnected
,05-19 12:11:56.302  5021  5150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-19 12:11:56.302  3510  3510 D BluetoothHeadset: unRegisterMessageListener : 11
,05-19 12:11:56.302  3510  3510 W BluetoothHeadset: Proxy not attached to service
05-19 12:11:56.302  3510  3510 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,05-19 12:11:56.302  3510  3510 I Telecom : BluetoothManager : unregister MessageListener
05-19 12:11:56.302  5021  5021 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 12:11:56.302  5021  5021 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
,05-19 12:11:56.312  5021  5150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
05-19 12:11:56.312  5021  5021 V BluetoothAdapterState: isTurningOff()=true
,05-19 12:11:56.312  5021  5021 V BluetoothAdapterState: isTurningOn()=false
05-19 12:11:56.312  5021  5021 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:56.312  5021  5021 V BluetoothAdapterState: isBleTurningOff()=false
,05-19 12:11:56.312  5021  5021 D A2dpService: Received stop request...Stopping profile...
,05-19 12:11:56.312  5021  5491 D A2dpStateMachine: Exit Disconnected: -1
,05-19 12:11:56.312  5021  5150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,05-19 12:11:56.312  5021  5021 D Avrcp   : unregisterContentObserver
,05-19 12:11:56.312  5021  5021 D Avrcp   : removeOnActiveSessionsChangedListener
,05-19 12:11:56.312  5021  5150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
05-19 12:11:56.312  5021  5021 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
05-19 12:11:56.312  5021  5021 E A2dpService: notifyProfileServiceStateChanged
,05-19 12:11:56.312  5021  5150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
05-19 12:11:56.312  3510  3510 D BluetoothA2dp: Proxy object disconnected
05-19 12:11:56.312  3942  3942 D BluetoothA2dp: Proxy object disconnected
05-19 12:11:56.312  3942  3942 D A2dpProfile: Bluetooth service disconnected
,05-19 12:11:56.312  5053  5053 D BluetoothA2dp: Proxy object disconnected
,05-19 12:11:56.322  5021  5150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,05-19 12:11:56.322  5021  5150 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
05-19 12:11:56.322  5021  5150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
05-19 12:11:56.322  5021  5150 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
05-19 12:11:56.322  5021  5150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-19 12:11:56.332  5021  5021 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,05-19 12:11:56.332  5021  5021 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
05-19 12:11:56.332  5021  5021 D HeadsetProvider: cleanup
05-19 12:11:56.332  5021  5021 I HeadsetProvider: clearAllHeadsetSettings(0)
,05-19 12:11:56.352  5021  5021 D HidService: Received stop request...Stopping profile...
,05-19 12:11:56.352  5021  5021 D HidService: Stopping Bluetooth HidService
05-19 12:11:56.352  5021  5021 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
05-19 12:11:56.352  5021  5021 W bt_btif : cleanup: HH disabling or disabled already, status = 0
05-19 12:11:56.352  5021  5021 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
05-19 12:11:56.352  5021  5021 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
05-19 12:11:56.352  5021  5021 E HidService: notifyProfileServiceStateChanged
,05-19 12:11:56.352  3942  3942 D BluetoothInputDevice: Proxy object disconnected
05-19 12:11:56.352  3942  3942 D HidProfile: Bluetooth service disconnected
,05-19 12:11:56.352  5021  5021 D HealthService: Received stop request...Stopping profile...
,05-19 12:11:56.352  5021  5021 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
05-19 12:11:56.352  5021  5021 E HealthService: notifyProfileServiceStateChanged
,05-19 12:11:56.352  5021  5021 D PanService: Received stop request...Stopping profile...
,05-19 12:11:56.362  5021  5021 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
05-19 12:11:56.362  5021  5021 E PanService: notifyProfileServiceStateChanged
,05-19 12:11:56.362  3510  3510 D BluetoothPan: BluetoothPAN Proxy object disconnected
05-19 12:11:56.362  3942  3942 D BluetoothPan: BluetoothPAN Proxy object disconnected
05-19 12:11:56.362  3942  3942 D PanProfile: Bluetooth service disconnected
,05-19 12:11:56.362  9342  9342 D BluetoothPan: BluetoothPAN Proxy object disconnected
05-19 12:11:56.362  9342  9342 D PanProfile: Bluetooth service disconnected
,05-19 12:11:56.362  5021  5021 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 12:11:56.362  5021  5021 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
,05-19 12:11:56.362  5021  5021 V BluetoothAdapterState: isTurningOff()=true
05-19 12:11:56.362  5021  5021 V BluetoothAdapterState: isTurningOn()=false
,05-19 12:11:56.362  5021  5021 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:56.362  5021  5021 V BluetoothAdapterState: isBleTurningOff()=false
05-19 12:11:56.362  5021  5021 D BluetoothMapService: Received stop request...Stopping profile...
,05-19 12:11:56.362  5021  5021 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
,05-19 12:11:56.362  5021  5021 E BluetoothMapService: notifyProfileServiceStateChanged
,05-19 12:11:56.372  3942  3942 D BluetoothMap: Proxy object disconnected
,05-19 12:11:56.372  3942  3942 D MapProfile: Bluetooth service disconnected
,05-19 12:11:56.372  5021  5021 D SapService: Received stop request...Stopping profile...
,05-19 12:11:56.372  5021  5021 V SapService: stop()
,05-19 12:11:56.372  5021  5021 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
05-19 12:11:56.372  5021  5021 E SapService: notifyProfileServiceStateChanged
,05-19 12:11:56.372  3942  3942 D BluetoothSap: Proxy object disconnected
05-19 12:11:56.372  3942  3942 D SapProfile: Bluetooth service disconnected
,05-19 12:11:56.372  9342  9342 D BluetoothSap: Proxy object disconnected
05-19 12:11:56.372  9342  9342 D SapProfile: Bluetooth service disconnected
05-19 12:11:56.372  5021  5021 D BleAudioService: Received stop request...Stopping profile...
05-19 12:11:56.372  5021  5512 E BleAudioStateMachine_R: Exit Disconnected: -1
05-19 12:11:56.372  5021  5511 E BleAudioStateMachine_L: Exit Disconnected: -1
05-19 12:11:56.372  5021  5021 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
,05-19 12:11:56.372  5021  5021 E BleAudioService: notifyProfileServiceStateChanged
,05-19 12:11:56.382  3942  3942 D BluetoothLeAudio: Proxy object disconnected
,05-19 12:11:56.382  3942  3942 D BleAudioProfile: Bluetooth service disconnected
,05-19 12:11:56.382  5021  5021 E BluetoothAdapterService: handleMessage() - Message: 1
,05-19 12:11:56.382  5021  5021 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
05-19 12:11:56.382  5021  5021 V BluetoothAdapterState: isTurningOff()=true
,05-19 12:11:56.382  5021  5021 V BluetoothAdapterState: isTurningOn()=false
05-19 12:11:56.382  5021  5021 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:56.382  5021  5021 V BluetoothAdapterState: isBleTurningOff()=false
05-19 12:11:56.382  5021  5021 D BluetoothAdapterService: HID Host service will be diabled
,05-19 12:11:56.382  5021  5021 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-19 12:11:56.382  9666  9666 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
05-19 12:11:56.382  5021  5021 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 12:11:56.382  5021  5021 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
,05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isTurningOff()=true
,05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isTurningOn()=false
05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isBleTurningOff()=false
05-19 12:11:56.392  5021  5021 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,05-19 12:11:56.392  5021  5021 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
05-19 12:11:56.392  5021  5021 E BluetoothAdapterService: handleMessage() - Message: 1
,05-19 12:11:56.392  5021  5021 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isTurningOff()=true
,05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isTurningOn()=false
05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isBleTurningOff()=false
05-19 12:11:56.392  5021  5021 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
05-19 12:11:56.392  5021  5021 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,05-19 12:11:56.392  5021  5021 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 12:11:56.392  5021  5021 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
,05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isTurningOff()=true
,05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isTurningOn()=false
,05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isBleTurningOff()=false
05-19 12:11:56.392  5021  5021 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 12:11:56.392  5021  5021 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isTurningOff()=true
05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isTurningOn()=false
05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isBleTurningOff()=false
05-19 12:11:56.392  5021  5021 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 12:11:56.392  5021  5021 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isTurningOff()=true
,05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isTurningOn()=false
,05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:56.392  5021  5021 V BluetoothAdapterState: isBleTurningOff()=false
05-19 12:11:56.392  5021  5150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
05-19 12:11:56.392  5021  5021 V BleAudioService: [unregisterCallStateListener]
05-19 12:11:56.402  5021  5150 D BluetoothAdapterProperties: Setting state to 15
,05-19 12:11:56.402  5021  5150 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
05-19 12:11:56.402  5021  5021 W BtBleAudio.JNI: WARNING: cleanupNative(L385): Cleaning up  Ble audio left callback object##
,05-19 12:11:56.402  5021  5021 W BtBleAudio.JNI: WARNING: cleanupNative(L403): Cleaning up Ble audio Interface...##
,05-19 12:11:56.402  5021  5021 W BtBleAudio.JNI: WARNING: cleanupNative(L391): Cleaning up  Ble audio right callback object##
05-19 12:11:56.402  5021  5021 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
05-19 12:11:56.402  5021  5150 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,05-19 12:11:56.402  5021  5150 D BluetoothAdapterService: updateAdapterState state is 15
05-19 12:11:56.402  5021  5150 D BluetoothAdapterService: Autoconnection is available 
05-19 12:11:56.402  5021  5150 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
,05-19 12:11:56.402  5021  5150 I BluetoothAdapterState: Entering BleOnState
,05-19 12:11:56.402  3942  3957 D BluetoothLeAudio: onBluetoothStateChange: up=false
05-19 12:11:56.402  3942  3957 D BluetoothLeAudio: Unbinding service...
05-19 12:11:56.402  9342  9353 D BluetoothSap: onBluetoothStateChange: up=false
,05-19 12:11:56.402  9342  9354 D BluetoothAdapter: onBluetoothStateChange: up=false
05-19 12:11:56.402  9342  9354 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-19 12:11:56.402  9342  9354 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 12:11:56.412  5021  5036 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-19 12:11:56.412  5021  5036 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-19 12:11:56.412  5021  5036 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 12:11:56.412  3942  3956 D BluetoothMap: onBluetoothStateChange: up=false
,05-19 12:11:56.412  3942  5084 D BluetoothInputDevice: onBluetoothStateChange: up=false
,05-19 12:11:56.412  4276  4286 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-19 12:11:56.412  4276  4286 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-19 12:11:56.412  4276  4286 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 12:11:56.412  3942  4372 D BluetoothAdapter: onBluetoothStateChange: up=false
05-19 12:11:56.412  3942  4372 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-19 12:11:56.412  3942  4372 D BluetoothAdapter: There are no active google scan apps, stop scan
05-19 12:11:56.422  3942  5552 D BluetoothPan: onBluetoothStateChange on: false
,05-19 12:11:56.422  7218  7424 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-19 12:11:56.422  7218  7424 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-19 12:11:56.422  7218  7424 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 12:11:56.422  4288  5440 D BluetoothAdapter: onBluetoothStateChange: up=false
05-19 12:11:56.422  4288  5440 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-19 12:11:56.422  4288  5440 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 12:11:56.422  5053  5130 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-19 12:11:56.422  3942  3957 D BluetoothSap: onBluetoothStateChange: up=false
,05-19 12:11:56.422  3510  3609 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-19 12:11:56.422  9666  9676 D BluetoothAdapter: onBluetoothStateChange: up=false
05-19 12:11:56.422  9666  9676 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-19 12:11:56.422  9666  9676 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
05-19 12:11:56.422  9666  9676 D BluetoothLeAdvertiser: Exit stop advertising
05-19 12:11:56.422  9666  9676 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 12:11:56.422  9666  9676 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
05-19 12:11:56.422  9666  9676 D BluetoothLeScanner: Exiting stopAllScan
05-19 12:11:56.422  3510  3609 D BluetoothPan: onBluetoothStateChange on: false
,05-19 12:11:56.432  4341  4715 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-19 12:11:56.432  4341  4715 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-19 12:11:56.432  4341  4715 D BluetoothAdapter: There are no active google scan apps, stop scan
05-19 12:11:56.432  4341  4715 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,05-19 12:11:56.432  4341  4715 D BluetoothLeScanner: Exiting stopAllScan
05-19 12:11:56.432  3510  3609 D BluetoothAdapter: onBluetoothStateChange: up=false
05-19 12:11:56.432  3510  3609 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-19 12:11:56.432  3510  3609 D BluetoothAdapter: There are no active google scan apps, stop scan
05-19 12:11:56.432  3942  5084 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-19 12:11:56.432  3942  4372 D BluetoothPbap: onBluetoothStateChange: up=false
,05-19 12:11:56.432  8113  8124 D BluetoothAdapter: onBluetoothStateChange: up=false
05-19 12:11:56.432  8113  8124 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-19 12:11:56.432  8113  8124 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 12:11:56.432  9342  9353 D BluetoothPan: onBluetoothStateChange on: false
,05-19 12:11:56.432  5053  5078 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-19 12:11:56.432  5053  5078 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-19 12:11:56.432  5053  5078 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-19 12:11:56.432  5021  5150 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,05-19 12:11:56.442  5021  5150 D BluetoothAdapterProperties: Setting state to 16
,05-19 12:11:56.442  5021  5150 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
05-19 12:11:56.442  3510  3510 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:56.442  5021  5150 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-19 12:11:56.442  3510  3510 I InputMethodManagerService: [BT Setting State] State =10
,05-19 12:11:56.442  5021  5150 D BluetoothAdapterService: updateAdapterState state is 16
05-19 12:11:56.442  3510  3510 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
05-19 12:11:56.442  3510  3609 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
05-19 12:11:56.442  5021  5150 D BluetoothAdapterService: Autoconnection is available 
05-19 12:11:56.442  5021  5150 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
05-19 12:11:56.442  5021  5150 D BluetoothAdapterProperties: onBleDisable
05-19 12:11:56.442  3942  4148 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:56.442  3942  4148 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
05-19 12:11:56.442  3510  3529 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,05-19 12:11:56.442  4330  4330 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-19 12:11:56.442  4814  4814 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-19 12:11:56.442  3510  4257 D SecContentProvider: insert(), uri = 2
,05-19 12:11:56.442  3510  3510 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-19 12:11:56.442  3510  3510 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
,05-19 12:11:56.442  3510  3510 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-19 12:11:56.452  5021  5150 I BluetoothAdapterState: Entering PendingCommandState
05-19 12:11:56.452  5021  5155 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
05-19 12:11:56.452  5021  5155 E bt_btif : btif_vhci_sock_cleanup
05-19 12:11:56.452  5021  5414 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,05-19 12:11:56.462  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{6dac5d2: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:56.462  9342  9342 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-19 12:11:56.462  9342  9342 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,05-19 12:11:56.472  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d866a3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cddfc12 9342:com.android.settings/1000}
,05-19 12:11:56.472  5021  5159 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-19 12:11:56.472  5021  5159 D BluetoothAdapterProperties: Scan Mode:20
,05-19 12:11:56.482  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{17b8da0: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:56.482  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:56.492  3942  4233 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-19 12:11:56.492  3510  4407 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,05-19 12:11:56.492  9342  9342 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-19 12:11:56.492  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:56.502  9666  9751 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-19 12:11:56.502  9666  9751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 12:11:56.502  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:11:56.502  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:11:56.502  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:11:56.502  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
05-19 12:11:56.502  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 12:11:56.502  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 12:11:56.502  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 12:11:56.502  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 12:11:56.502  9666  9751 D BluetoothAdapter: enable()
,05-19 12:11:56.512  3510  3975 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d866a3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:11:56.512  9666  9729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:56.512  9342  9342 D DockEventReceiver: finishStartingService: stopping service
,05-19 12:11:56.522  3510  3529 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d866a3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{feb16e 4341:com.google.android.gms.persistent/u0a21}
,05-19 12:11:56.522  4341  4341 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-19 12:11:56.532  3510  4312 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 12:11:56.532  3510  4312 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-19 12:11:56.532  3510  4312 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:11:56.532  3510  4312 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:11:56.532  3510  4312 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-19 12:11:56.532  3510  4312 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-19 12:11:56.532  3510  4312 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-19 12:11:56.532  3510  4312 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-19 12:11:56.532  3510  4312 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 12:11:56.532  3510  4312 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-19 12:11:56.532  3510  4312 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-19 12:11:56.532  3510  4312 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 12:11:56.542  3510  4409 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d866a3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3c7fb0 8113:com.sec.android.app.shealth:remote/u0a39}
,05-19 12:11:56.562  3510  4409 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d866a3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cddfc12 9342:com.android.settings/1000}
,05-19 12:11:56.562  9342  9342 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
,05-19 12:11:56.562  9342  9342 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,05-19 12:11:56.582  3510  4409 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d866a3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10b237d 5021:com.android.bluetooth/1002}
,05-19 12:11:56.592  5021  9760 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-19 12:11:56.592  5021  9760 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-19 12:11:56.602  5021  5150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
,05-19 12:11:56.602  3510  4409 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d866a3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{818aca3 7218:com.google.android.apps.maps/u0a125}
,05-19 12:11:56.612  5021  5150 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-19 12:11:56.622  3510  4409 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1fb6d1e u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:11:56.652  5021  5159 I bt_hci  : shut_down
05-19 12:11:56.652  5021  5223 D bt_hwcfg: hw_epilog_process
05-19 12:11:56.652  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{680c9ff: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:56.652  5021  5223 I bt_vendor: low_power_mode_cb
,05-19 12:11:56.652  5021  5150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
,05-19 12:11:56.652  5021  5223 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
05-19 12:11:56.652  5021  5223 I bt_vendor: epilog_cb
05-19 12:11:56.652  5021  5223 I bt_hci  : epilog_finished_callback
,05-19 12:11:56.652  5021  5159 I bt_hci_h4: hal_close
05-19 12:11:56.652  5021  5159 I bt_userial_vendor: device fd = 60 close
05-19 12:11:56.662  5021  5159 I bt_upio : upio_set_bluetooth_power(on: 0)
05-19 12:11:56.662  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{c9be3cc: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:56.662  5021  5155 D bt_stack_manager: event_shut_down_stack finished.
05-19 12:11:56.662  5021  5159 E BluetoothAdapterState: stateChangeCallback : 0
,05-19 12:11:56.662  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9905615 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:11:56.662  5021  5150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
,05-19 12:11:56.672  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{5ed3d2a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:56.672  5021  5021 D BtGatt.DebugUtils: handleDebugAction() action=null
05-19 12:11:56.672  5021  5150 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,05-19 12:11:56.672  5021  5021 D BtGatt.GattService: Received stop request...Stopping profile...
,05-19 12:11:56.672  5021  5021 D BtGatt.GattService: stop()
05-19 12:11:56.672  5021  5021 D BtGatt.GattService: [GSIM LOG]: saveLogPref
05-19 12:11:56.672  5021  5021 D BtGatt.GattService: [GSIM LOG]: saveLogPref END
05-19 12:11:56.672  5021  5021 D BtGatt.GattService: cleanup binder
,05-19 12:11:56.672  5021  5021 D BtGatt.AdvertiseManager: advertise clients cleared
05-19 12:11:56.672  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{722071b: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
05-19 12:11:56.672  5021  5021 D BtGatt.ScanManager: cleanup
,05-19 12:11:56.682  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{e2d3e91: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:56.682  5021  5021 D BtGatt.ScanManager: cleanup handler
05-19 12:11:56.682  5021  5021 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
,05-19 12:11:56.682  5021  5021 E BtGatt.GattService: notifyProfileServiceStateChanged
05-19 12:11:56.682  5021  5021 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 12:11:56.682  5021  5021 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
05-19 12:11:56.682  5021  5021 V BluetoothAdapterState: isTurningOff()=false
,05-19 12:11:56.682  5021  5021 V BluetoothAdapterState: isTurningOn()=false
05-19 12:11:56.682  5021  5021 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:56.682  5021  5021 V BluetoothAdapterState: isBleTurningOff()=true
,05-19 12:11:56.682  5021  5150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
,05-19 12:11:56.682  5021  5150 D BluetoothAdapterProperties: Setting state to 10
,05-19 12:11:56.682  5021  5150 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
05-19 12:11:56.682  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{77a01f6: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:56.682  5021  5150 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-19 12:11:56.682  5021  5150 D BluetoothAdapterService: updateAdapterState state is 10
05-19 12:11:56.682  5021  5150 D BluetoothAdapterService: Autoconnection is available 
05-19 12:11:56.682  5021  5150 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
,05-19 12:11:56.682  5021  5150 D BluetoothAdapterService: BT on, init HID DEV count : 0
05-19 12:11:56.682  5021  5150 I BluetoothAdapterState: Entering OffState
05-19 12:11:56.682  3510  3609 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,05-19 12:11:56.692  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{5cff9f7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:56.692  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{c3c4782: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:56.702  5021  5021 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,05-19 12:11:56.702  5021  5021 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,05-19 12:11:56.702  5021  5021 I BluetoothServiceJni: cleanupNative: return from cleanup
05-19 12:11:56.702  5021  5155 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,05-19 12:11:56.712  5021  5021 I art     : System.exit called, status: 0
05-19 12:11:56.712  5021  5021 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,05-19 12:11:56.712  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{fdd9ed0: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:56.732  3510  4059 I ActivityManager: Process com.android.bluetooth (pid 5021)(adj -11) has died(82,1821)
05-19 12:11:56.732  3510  4059 D ActivityManager: cleanUpApplicationRecord -- 5021
,05-19 12:11:56.742  3510  4059 D ActivityManager: isAutoRunBlockedApp:: com.android.bluetooth, Auto Run ON
05-19 12:11:56.742  3510  4059 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,05-19 12:11:57.102  9666  9751 D BluetoothAdapter: enable()
,05-19 12:11:57.102  3510  4947 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 12:11:57.112  3510  4947 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-19 12:11:57.112  3510  4947 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:11:57.112  3510  4947 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:11:57.112  3510  4947 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-19 12:11:57.112  3510  4947 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-19 12:11:57.112  3510  4947 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-19 12:11:57.112  3510  4947 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-19 12:11:57.112  3510  4947 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 12:11:57.112  3510  4947 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-19 12:11:57.112  3510  4947 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-19 12:11:57.112  3510  4947 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 12:11:57.622  9666  9751 D BluetoothAdapter: enable()
,05-19 12:11:57.632  3510  3530 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 12:11:57.632  3510  3530 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-19 12:11:57.632  3510  3530 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:11:57.632  3510  3530 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:11:57.632  3510  3530 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-19 12:11:57.632  3510  3530 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-19 12:11:57.632  3510  3530 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-19 12:11:57.632  3510  3530 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-19 12:11:57.632  3510  3530 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 12:11:57.632  3510  3530 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-19 12:11:57.632  3510  3530 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-19 12:11:57.632  3510  3530 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 12:11:57.782  9763  9763 E Zygote  : v2
05-19 12:11:57.782  9763  9763 I libpersona: KNOX_SDCARD checking this for 1002
05-19 12:11:57.782  9763  9763 I libpersona: KNOX_SDCARD not a persona
,05-19 12:11:57.782  9763  9763 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:11:57.782  9763  9763 E Zygote  : accessInfo : 0
,05-19 12:11:57.782  3510  3598 I ActivityManager: Start proc 9763:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,05-19 12:11:57.832  9763  9763 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:11:57.832  9763  9763 D ActivityThread: Added TimaKeyStore provider
,05-19 12:11:57.872  9763  9763 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 12:11:57.872  9763  9763 D RelationGraph: garbageCollect()
,05-19 12:11:57.872  9763  9763 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in com.android.bluetooth rsrc of package com.android.bluetooth
,05-19 12:11:57.872  3510  4518 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 12:11:57.872  9763  9763 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:11:57.882  9763  9763 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:11:57.882  9763  9763 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:11:57.922  9763  9763 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,05-19 12:11:57.962  9763  9763 D BtSettings.ProfileConfig: Adding GattService
,05-19 12:11:57.962  9763  9763 D BtSettings.ProfileConfig: Adding HeadsetService
05-19 12:11:57.962  9763  9763 D BtSettings.ProfileConfig: Adding A2dpService
,05-19 12:11:57.962  9763  9763 D BtSettings.ProfileConfig: Adding HidService
,05-19 12:11:57.962  9763  9763 D BtSettings.ProfileConfig: Adding HealthService
05-19 12:11:57.962  9763  9763 D BtSettings.ProfileConfig: Adding PanService
,05-19 12:11:57.962  9763  9763 D BtSettings.ProfileConfig: Adding BluetoothMapService
,05-19 12:11:57.962  9763  9763 D BtSettings.ProfileConfig: Adding SapService
,05-19 12:11:57.962  9763  9763 D BtSettings.ProfileConfig: Adding HeadsetClientService
,05-19 12:11:57.962  9763  9763 D BtSettings.ProfileConfig: Adding A2dpSinkService
,05-19 12:11:57.962  9763  9763 D BtSettings.ProfileConfig: Adding BleAudioService
05-19 12:11:57.962  9763  9763 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,05-19 12:11:57.972  3510  4983 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.gatt.GattService
,05-19 12:11:57.972  3510  4983 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 12:11:57.972  3510  4983 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 12:11:57.972  3510  4983 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 12:11:57.972  3510  4983 D SettingsProvider: selectionArgs: false
,05-19 12:11:57.972  3510  4983 D SettingsProvider: selectionArgs: 1002
05-19 12:11:57.972  3510  4983 D SettingsProvider: ret = -1
,05-19 12:11:57.972  3510  3529 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
05-19 12:11:57.972  3510  3529 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 12:11:57.972  3510  3529 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 12:11:57.972  3510  3529 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,05-19 12:11:57.972  3510  3529 D SettingsProvider: selectionArgs: false
05-19 12:11:57.972  3510  3529 D SettingsProvider: selectionArgs: 1002
05-19 12:11:57.972  3510  3529 D SettingsProvider: ret = -1
,05-19 12:11:57.972  3510  4947 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,05-19 12:11:57.972  3510  4947 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 12:11:57.972  3510  4947 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 12:11:57.972  3510  4947 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 12:11:57.972  3510  4947 D SettingsProvider: selectionArgs: false
05-19 12:11:57.972  3510  4947 D SettingsProvider: selectionArgs: 1002
,05-19 12:11:57.972  3510  4947 D SettingsProvider: ret = -1
,05-19 12:11:57.982  3510  4313 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hid.HidService
05-19 12:11:57.982  3510  4313 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 12:11:57.982  3510  4313 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 12:11:57.982  3510  4313 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,05-19 12:11:57.982  3510  4313 D SettingsProvider: selectionArgs: false
05-19 12:11:57.982  3510  4313 D SettingsProvider: selectionArgs: 1002
05-19 12:11:57.982  3510  4313 D SettingsProvider: ret = -1
,05-19 12:11:57.982  3510  4406 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hdp.HealthService
05-19 12:11:57.982  3510  4406 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 12:11:57.982  3510  4406 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,05-19 12:11:57.982  3510  4406 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 12:11:57.982  3510  4406 D SettingsProvider: selectionArgs: false
05-19 12:11:57.982  3510  4406 D SettingsProvider: selectionArgs: 1002
05-19 12:11:57.982  3510  4406 D SettingsProvider: ret = -1
,05-19 12:11:57.982  3510  4312 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.pan.PanService
,05-19 12:11:57.982  3510  4312 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 12:11:57.982  3510  4312 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 12:11:57.982  3510  4312 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 12:11:57.982  3510  4312 D SettingsProvider: selectionArgs: false
05-19 12:11:57.982  3510  4312 D SettingsProvider: selectionArgs: 1002
,05-19 12:11:57.982  3510  4312 D SettingsProvider: ret = -1
,05-19 12:11:57.982  3510  4427 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,05-19 12:11:57.982  3510  4427 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 12:11:57.982  3510  4427 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 12:11:57.982  3510  4427 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 12:11:57.982  3510  4427 D SettingsProvider: selectionArgs: false
,05-19 12:11:57.982  3510  4427 D SettingsProvider: selectionArgs: 1002
05-19 12:11:57.982  3510  4427 D SettingsProvider: ret = -1
,05-19 12:11:57.992  3510  4518 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.sap.SapService
,05-19 12:11:57.992  3510  4518 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 12:11:57.992  3510  4518 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 12:11:57.992  3510  4518 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 12:11:57.992  3510  4518 D SettingsProvider: selectionArgs: false
05-19 12:11:57.992  3510  4518 D SettingsProvider: selectionArgs: 1002
05-19 12:11:57.992  3510  4518 D SettingsProvider: ret = -1
,05-19 12:11:57.992  3510  4407 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
05-19 12:11:57.992  3510  4407 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,05-19 12:11:57.992  3510  4407 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 12:11:57.992  3510  4407 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 12:11:57.992  3510  4407 D SettingsProvider: selectionArgs: false
05-19 12:11:57.992  3510  4407 D SettingsProvider: selectionArgs: 1002
05-19 12:11:57.992  3510  4407 D SettingsProvider: ret = -1
,05-19 12:11:57.992  3510  3975 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,05-19 12:11:57.992  3510  3975 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 12:11:57.992  3510  3975 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 12:11:57.992  3510  3975 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 12:11:57.992  3510  3975 D SettingsProvider: selectionArgs: false
05-19 12:11:57.992  3510  3975 D SettingsProvider: selectionArgs: 1002
,05-19 12:11:57.992  3510  3975 D SettingsProvider: ret = -1
,05-19 12:11:57.992  3510  3530 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.broadcom.bt.service.bleaudio.BleAudioService
,05-19 12:11:57.992  3510  3530 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-19 12:11:57.992  3510  3530 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 12:11:57.992  3510  3530 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 12:11:57.992  3510  3530 D SettingsProvider: selectionArgs: false
05-19 12:11:57.992  3510  3530 D SettingsProvider: selectionArgs: 1002
,05-19 12:11:57.992  3510  3530 D SettingsProvider: ret = -1
,05-19 12:11:57.992  9763  9763 D InjectionManager: InjectionManager
05-19 12:11:57.992  9763  9763 D InjectionManager: fillFeatureStoreMap com.android.bluetooth
,05-19 12:11:58.002  9763  9763 I InjectionManager: Constructor com.android.bluetooth, Feature store :{}
05-19 12:11:58.002  9763  9763 I InjectionManager: featureStore :{}
,05-19 12:11:58.042  9763  9763 D BluetoothAdapterState: make() - Creating AdapterState
,05-19 12:11:58.042  9763  9763 I bt_bluedroid: init
,05-19 12:11:58.042  9763  9776 I BluetoothAdapterState: Entering OffState
,05-19 12:11:58.052  9763  9777 E bt_core_counter: counter_init unable to open counter port
05-19 12:11:58.052  9763  9777 E bt_core_module: module_init failed to initialize "counter_module"
05-19 12:11:58.052  9763  9777 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
05-19 12:11:58.052  9763  9777 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
05-19 12:11:58.052  9763  9777 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
05-19 12:11:58.052  9763  9777 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,05-19 12:11:58.052  9763  9763 I bt_bluedroid: get_profile_interface socket
,05-19 12:11:58.052  9763  9763 W bt_btif : btif_get_adapter_property 2
05-19 12:11:58.052  9763  9763 W bt_btif : btif_get_adapter_property 1
,05-19 12:11:58.052  9763  9780 D BluetoothAdapterProperties: Address is:A8:81:95:E9:5F:6F
,05-19 12:11:58.052  9763  9780 E BluetoothServiceJni: populateRssiValuesNative
05-19 12:11:58.052  9763  9780 I bt_bluedroid: getModelRssiValues
05-19 12:11:58.052  9763  9780 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
,05-19 12:11:58.052  9763  9763 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
05-19 12:11:58.052  9763  9780 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,05-19 12:11:58.062  9763  9780 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7 edge
05-19 12:11:58.062  3510  3510 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,05-19 12:11:58.062  9763  9763 I bt_bluedroid: get_profile_interface sdp
,05-19 12:11:58.072  9763  9773 I bt_bluedroid: config_hci_snoop_log
,05-19 12:11:58.072  3510  3609 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,05-19 12:11:58.072  9763  9776 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,05-19 12:11:58.082  9763  9776 D BluetoothAdapterProperties: Setting state to 14
,05-19 12:11:58.082  9763  9776 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
05-19 12:11:58.082  9763  9776 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-19 12:11:58.082  9763  9776 D BluetoothAdapterService: updateAdapterState state is 14
05-19 12:11:58.082  3510  3609 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
05-19 12:11:58.082  9763  9776 D BluetoothAdapterService: Autoconnection is available 
05-19 12:11:58.082  9763  9776 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
,05-19 12:11:58.082  9763  9776 D BluetoothSecureManager: getInstant: null
,05-19 12:11:58.082  9763  9776 D BluetoothSecureManager: calling getMethod for getService
05-19 12:11:58.082  9763  9776 D BluetoothSecureManager: calling getService
,05-19 12:11:58.082  9763  9776 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@efa50ee
,05-19 12:11:58.082  3510  3530 D BluetoothSecureManagerService: isSecureModeEnabled
05-19 12:11:58.082  3510  3530 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
05-19 12:11:58.082  9763  9776 D BtConfig.SecureMode: isSecureModeOn:false
05-19 12:11:58.082  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,05-19 12:11:58.082  9763  9776 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
05-19 12:11:58.082  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,05-19 12:11:58.082  9763  9776 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,05-19 12:11:58.082  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,05-19 12:11:58.092  9763  9776 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
05-19 12:11:58.092  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-19 12:11:58.092  9763  9776 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
05-19 12:11:58.092  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-19 12:11:58.092  9763  9776 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,05-19 12:11:58.092  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
05-19 12:11:58.092  9763  9776 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,05-19 12:11:58.092  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,05-19 12:11:58.092  9763  9776 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
05-19 12:11:58.092  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,05-19 12:11:58.092  9763  9776 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
05-19 12:11:58.092  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,05-19 12:11:58.092  9763  9776 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
05-19 12:11:58.092  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,05-19 12:11:58.092  9763  9776 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
05-19 12:11:58.092  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-19 12:11:58.092  9763  9776 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.bleaudio.BleAudioService
,05-19 12:11:58.092  9763  9776 D BluetoothBondStateMachine: make
,05-19 12:11:58.102  9763  9781 I BluetoothBondStateMachine: StableState(): Entering Off State
,05-19 12:11:58.112  9763  9776 I BluetoothAdapterState: Entering PendingCommandState
,05-19 12:11:58.112  9763  9763 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
,05-19 12:11:58.112  9763  9763 D BtGatt.DebugUtils: handleDebugAction() action=null
,05-19 12:11:58.112  9763  9763 D BtGatt.GattService: Received start request. Starting profile...
05-19 12:11:58.112  9763  9763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
05-19 12:11:58.112  9763  9763 D BtGatt.GattService: start()
05-19 12:11:58.112  9763  9763 I bt_bluedroid: get_profile_interface gatt
,05-19 12:11:58.122  9763  9763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
05-19 12:11:58.122  9763  9763 D BtGatt.AdvertiseManager: advertise manager created
,05-19 12:11:58.122  9763  9763 D BtGatt.AdvertiseManager: start
,05-19 12:11:58.122  9763  9763 D BtGatt.ScanManager: start
,05-19 12:11:58.122  9763  9763 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,05-19 12:11:58.142  9666  9751 D BluetoothAdapter: enable()
,05-19 12:11:58.152  3510  4983 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 12:11:58.152  3510  4983 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-19 12:11:58.152  3510  4983 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:11:58.152  3510  4983 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:11:58.152  3510  4983 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-19 12:11:58.152  3510  4983 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-19 12:11:58.152  3510  4983 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-19 12:11:58.152  3510  4983 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-19 12:11:58.152  3510  4983 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 12:11:58.152  3510  4983 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-19 12:11:58.152  3510  4983 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-19 12:11:58.152  3510  4983 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 12:11:58.162  9763  9763 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
05-19 12:11:58.162  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b955c39 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:11:58.172  9763  9776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
05-19 12:11:58.172  9763  9763 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
05-19 12:11:58.172  9763  9763 E BtGatt.GattService: notifyProfileServiceStateChanged
,05-19 12:11:58.182  9763  9776 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-19 12:11:58.182  9763  9763 E BluetoothAdapterService: handleMessage() - Message: 1
,05-19 12:11:58.182  9763  9763 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
,05-19 12:11:58.182  9763  9763 V BluetoothAdapterState: isTurningOff()=false
,05-19 12:11:58.182  9763  9763 V BluetoothAdapterState: isTurningOn()=false
05-19 12:11:58.182  9763  9763 V BluetoothAdapterState: isBleTurningOn()=true
05-19 12:11:58.182  9763  9763 V BluetoothAdapterState: isBleTurningOff()=false
05-19 12:11:58.182  9763  9776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,05-19 12:11:58.182  9763  9776 I bt_bluedroid: bt_bluedroid
,05-19 12:11:58.182  9763  9777 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,05-19 12:11:58.192  9763  9777 I bt_hci  : start_up
,05-19 12:11:58.192  9763  9777 I bt_vendor: alloc value 0xf37dd171
,05-19 12:11:58.192  9763  9777 I bt_vendor: init
05-19 12:11:58.192  9763  9777 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
05-19 12:11:58.192  9763  9777 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
05-19 12:11:58.192  9763  9777 I bt_upio : upio_set_bluetooth_power(on: 0)
05-19 12:11:58.192  9763  9777 I bt_upio : upio_set_bluetooth_power(on: 1)
,05-19 12:11:58.302  9763  9777 D bt_hci  : start_up starting async portion
,05-19 12:11:58.302  9763  9793 I bt_hci  : event_finish_startup
05-19 12:11:58.302  9763  9793 I bt_hci_h4: hal_open
05-19 12:11:58.302  9763  9793 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
,05-19 12:11:58.302  9763  9793 I bt_userial_vendor: userial_vendor_open():UART is setup
,05-19 12:11:58.302  9763  9793 I bt_userial_vendor: device fd = 60 open
05-19 12:11:58.302  9763  9793 E bt_hwcfg: Start CFG HW, HCI reset
,05-19 12:11:58.312  9763  9793 E bt_hwcfg: Read Local Name after HCI reset
,05-19 12:11:58.312  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{b6682f5: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.332  9763  9793 D bt_hwcfg: Chipset BCM4359C0
05-19 12:11:58.332  9763  9793 D bt_hwcfg: Target name = [BCM4359C0]
,05-19 12:11:58.342  9763  9793 I bt_hwcfg: module_type[semco_b90s_c0].
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG . BCM4359C0
,05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG .. BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0061_murata.hcd BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG companion_2l1_master_setfile.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG companion_2l1_mode_setfile.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG companion_fw_2l1.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG companion_fw_imx260.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG companion_imx260_master_setfile.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG companion_imx260_mode_setfile.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG fimc_is_fw2_2l1.bin BCM4359C0
,05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG fimc_is_fw2_imx260.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG mfc_fw.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG ois_fw_dom.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG ois_fw_sec.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG sec_s3nrn81_firmware.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG seiren_fw_dram.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG seiren_fw_sram.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG setfile_2l1.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG setfile_4e6.bin BCM4359C0
,05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG setfile_imx260.bin BCM4359C0
05-19 12:11:58.342  9763  9793 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0062_semco.hcd BCM4359C0
05-19 12:11:58.342  9763  9793 I bt_hwcfg: patch(org) : bcm4359C0_V0044.0062_semco.hcd
05-19 12:11:58.342  9763  9793 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
05-19 12:11:58.342  9763  9793 E bt_hwcfg: ORG patchram base 0044
05-19 12:11:58.342  9763  9793 E bt_hwcfg: ORG patchram minor 0062
05-19 12:11:58.342  9763  9793 E bt_hwcfg: fw ver (org)44.62
05-19 12:11:58.342  9763  9793 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
,05-19 12:11:58.352  9763  9793 I bt_hwcfg: Axi patch failure or not include AXI patching
,05-19 12:11:58.352  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{50a988a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.352  9763  9793 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,05-19 12:11:58.352  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{4b92efb: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.452  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{4bab18: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.462  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{ae95971: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.502  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{d01b356: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.512  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{8e1bfd7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.512  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{7dc60c4: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.522  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{9e91bad: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.532  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{37daee2: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.532  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{c988273: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.542  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{ca0c530: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.552  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{fa8c5a9: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.552  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{cbd72e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.562  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{deed2cf: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.572  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{e05045c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.572  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{a9f1365: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.582  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{2c2383a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.592  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{afcceb: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.592  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{40c0a48: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.602  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{ff280e1: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.602  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{c8b9e06: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.612  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{3c4cc7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.622  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{1fb82f4: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.632  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{6b54a1d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.632  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{7339492: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.642  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{326ee63: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.652  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{7c7da60: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.652  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{ae16b19: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.662  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{ef267de: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.662  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{c900dbf: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.672  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{e403c8c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.672  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{4149fd5: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.682  9666  9751 D BluetoothAdapter: enable()
,05-19 12:11:58.682  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{93923ea: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.692  9763  9793 I bt_hwcfg: bt vendor lib: set UART baud 115200,
05-19 12:11:58.692  9763  9793 I bt_hwcfg: FW Download delta = 380327
05-19 12:11:58.692  9763  9793 D bt_hwcfg: Settlement delay -- 100 ms
05-19 12:11:58.692  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{741c6db u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
05-19 12:11:58.692  9763  9793 I bt_hwcfg: Setting fw settlement delay to 100 
,05-19 12:11:58.692  3510  4059 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 12:11:58.692  3510  4059 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-19 12:11:58.692  3510  4059 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:11:58.692  3510  4059 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:11:58.692  3510  4059 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-19 12:11:58.692  3510  4059 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-19 12:11:58.692  3510  4059 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-19 12:11:58.692  3510  4059 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-19 12:11:58.692  3510  4059 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 12:11:58.692  3510  4059 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-19 12:11:58.702  3510  4059 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-19 12:11:58.702  3510  4059 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 12:11:58.702  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{9fa9578: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.712  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{c0c6451: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.712  9763  9776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
,05-19 12:11:58.712  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{f7d94b6: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.712  9763  9776 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-19 12:11:58.722  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{68bf5b7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.722  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{ff9124: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.732  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{e1f48d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.732  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{ac64642: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.742  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{8e03653: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.742  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{f369b90: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.752  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{f064c89: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.752  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{bf6848e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.762  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{82de4af: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.762  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{591e0bc: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.772  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{efe2845: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.782  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{cda5b9a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.782  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{3fe1ccb: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.792  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{ffa4ca8: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.792  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{2de03c1: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.802  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{5f29766: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.812  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{14fbaa7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.812  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{dfb8b54: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.822  9763  9793 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,05-19 12:11:58.822  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{f861afd: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.822  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{500c3f2: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.832  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{c335a43: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.842  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{a3008c0: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.852  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{d9e69f9: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.862  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{532d3e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.872  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{727579f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.882  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{c6cf0ec: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.892  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{e52acb5: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.902  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{2d0df4a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.912  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{433cebb: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.922  9763  9793 I bt_hwcfg: vendor lib fwcfg completed
,05-19 12:11:58.922  9763  9793 I bt_vendor: firmware callback
05-19 12:11:58.922  9763  9793 I bt_hci  : firmware_config_callback
,05-19 12:11:58.922  9763  9797 I bt_btu_task: Bluetooth chip preload is complete
,05-19 12:11:58.922  9763  9797 I         : BTE_InitTraceLevels -- TRC_HCI
,05-19 12:11:58.932  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{2ae2fd8: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:58.922  9763  9797 I         : BTE_InitTraceLevels -- TRC_L2CAP
05-19 12:11:58.922  9763  9797 I         : BTE_InitTraceLevels -- TRC_RFCOMM
05-19 12:11:58.922  9763  9797 I         : BTE_InitTraceLevels -- TRC_AVDT
,05-19 12:11:58.922  9763  9797 I         : BTE_InitTraceLevels -- TRC_AVRC
05-19 12:11:58.932  9763  9797 I         : BTE_InitTraceLevels -- TRC_A2D
05-19 12:11:58.932  9763  9797 I         : BTE_InitTraceLevels -- TRC_BNEP
05-19 12:11:58.932  9763  9797 I         : BTE_InitTraceLevels -- TRC_BTM
,05-19 12:11:58.932  9763  9797 I         : BTE_InitTraceLevels -- TRC_GAP
05-19 12:11:58.932  9763  9797 I         : BTE_InitTraceLevels -- TRC_PAN
05-19 12:11:58.932  9763  9797 I         : BTE_InitTraceLevels -- TRC_SDP
,05-19 12:11:58.932  9763  9797 I         : BTE_InitTraceLevels -- TRC_GATT
05-19 12:11:58.932  9763  9797 I         : BTE_InitTraceLevels -- TRC_SMP
05-19 12:11:58.932  9763  9797 I         : BTE_InitTraceLevels -- TRC_BTAPP
05-19 12:11:58.932  9763  9797 I         : BTE_InitTraceLevels -- TRC_BTIF
05-19 12:11:58.932  9763  9797 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,05-19 12:11:58.942  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{fce5f31: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.952  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{cc5a616: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.952  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{3c69b97: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.962  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{cc27184: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.962  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{d78bd6d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.972  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{56e0da2: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.972  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{54f5a33: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:58.982  3510  4947 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-19 12:11:58.982  3510  4947 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4334, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
,05-19 12:11:58.982  3510  4947 D BatteryService: online:4, current avg:84, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:127
05-19 12:11:58.982  3510  3510 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-19 12:11:58.982  3510  3510 I MotionRecognitionService: Plugged
,05-19 12:11:58.982  3510  3510 D MotionRecognitionService:   cableConnection= 1
05-19 12:11:58.982  3510  3510 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-19 12:11:58.982  3510  3510 D MotionRecognitionService: skip setTransmitPower. 
,05-19 12:11:58.992  3510  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-19 12:11:58.992  3942  3942 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-19 12:11:58.992  3942  3942 D KeyguardUpdateMonitor: handleBatteryUpdate
05-19 12:11:58.992  3942  3942 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-19 12:11:58.992  3942  3942 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-19 12:11:58.992  3942  3942 D PowerUI.Notification: There is no change about charging status, so return!
05-19 12:11:58.992  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 12:11:59.002  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,05-19 12:11:59.002  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{6b721f0: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.012  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{7f0c369: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.012  5067  5067 D BatteryMonitor: new battery level: 100
,05-19 12:11:59.012  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{94361ee: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.022  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 12:11:59.022  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{59b668f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.032  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{e046d1c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.032  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{c92d25: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.032  9763  9797 W bt_l2cap: l2c_link_processs_ble_num_bufs 15
,05-19 12:11:59.032  9763  9797 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf372d7ad
05-19 12:11:59.032  9763  9797 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf372d7ad 
05-19 12:11:59.032  9763  9797 E bt_btm  : btm_ble_set_search_if search_if=4
,05-19 12:11:59.042  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{107aefa: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.042  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{6f1dcab: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.052  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{d793f08: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.052  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{60476a1: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.062  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{d91c0c6: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.062  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{eef9887: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.062  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{be743b4: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.072  9763  9780 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = false mAobleSupported = 1
,05-19 12:11:59.072  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{950dbdd: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.082  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{4592352: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.082  9763  9780 E bt_btif : bta_dm_sm_execute event:0x2
,05-19 12:11:59.082  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{6233623: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.082  9763  9780 D bt_hci  : do_postload posting postload work item
,05-19 12:11:59.082  9763  9780 E bt_btif_sock: btif_sock_init: !vhci_init
,05-19 12:11:59.092  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{98ee720: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.082  9763  9780 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
05-19 12:11:59.082  9763  9793 I bt_hci  : event_postload
05-19 12:11:59.082  9763  9793 D bt_hwcfg: hw_sco_config
05-19 12:11:59.082  9763  9793 I bt_vendor: sco_config_cb
05-19 12:11:59.082  9763  9793 I bt_hci  : sco_config_callback postload finished.
05-19 12:11:59.082  9763  9780 D bt_bte_conf: Device ID record 1 : primary
05-19 12:11:59.082  9763  9780 D bt_bte_conf:   vendorId            = 0075
05-19 12:11:59.082  9763  9780 D bt_bte_conf:   vendorIdSource      = 0001
05-19 12:11:59.082  9763  9780 D bt_bte_conf:   product             = 0100
05-19 12:11:59.082  9763  9780 D bt_bte_conf:   version             = 0200
05-19 12:11:59.082  9763  9780 D bt_bte_conf:   clientExecutableURL = 
05-19 12:11:59.082  9763  9780 D bt_bte_conf:   serviceDescription  = 
05-19 12:11:59.102  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{8c2229e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.082  9763  9780 D bt_bte_conf:   documentationURL    = 
,05-19 12:11:59.082  9763  9780 D bt_bte_conf: bte_load_did_conf no section named DID2.
05-19 12:11:59.082  9763  9777 D bt_stack_manager: event_start_up_stack finished
,05-19 12:11:59.092  9763  9780 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
05-19 12:11:59.092  9763  9780 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
05-19 12:11:59.092  9763  9780 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
05-19 12:11:59.092  9763  9780 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Hero SWB-B90S eLNA-0044
05-19 12:11:59.092  9763  9780 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0044.0062_semco.hcd
05-19 12:11:59.092  9763  9780 E BluetoothAdapterState: stateChangeCallback : 1
05-19 12:11:59.092  9763  9776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
05-19 12:11:59.092  9763  9776 D BluetoothAdapterProperties: Setting state to 15
05-19 12:11:59.092  9763  9776 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,05-19 12:11:59.092  9763  9776 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-19 12:11:59.092  9763  9776 D BluetoothAdapterService: updateAdapterState state is 15
05-19 12:11:59.092  9763  9776 D BluetoothAdapterService: Autoconnection is available 
05-19 12:11:59.092  9763  9776 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
05-19 12:11:59.092  9763  9776 I BluetoothAdapterState: Entering BleOnState
05-19 12:11:59.102  9763  9793 I bt_vendor: low_power_mode_cb
,05-19 12:11:59.102  3510  3609 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
05-19 12:11:59.102  3510  3609 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-19 12:11:59.112  9763  9776 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,05-19 12:11:59.112  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{569117f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.112  9763  9776 D BluetoothAdapterProperties: Setting state to 11
05-19 12:11:59.112  9763  9776 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,05-19 12:11:59.112  9763  9776 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-19 12:11:59.112  9763  9776 D BluetoothAdapterService: updateAdapterState state is 11
05-19 12:11:59.112  3510  3609 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
,05-19 12:11:59.112  9763  9776 D BluetoothAdapterService: Autoconnection is available 
,05-19 12:11:59.112  9763  9776 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
05-19 12:11:59.112  9763  9776 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
05-19 12:11:59.112  9763  9776 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
05-19 12:11:59.112  3510  3510 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,05-19 12:11:59.112  3510  3510 I InputMethodManagerService: [BT Setting State] State =11
05-19 12:11:59.112  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,05-19 12:11:59.112  3942  4148 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:59.112  3942  4148 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,05-19 12:11:59.112  4330  4330 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:59.122  4814  4814 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-19 12:11:59.122  3510  3510 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-19 12:11:59.122  3510  3510 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:59.122  3510  3510 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-19 12:11:59.122  9342  9342 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:59.122  9342  9342 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,05-19 12:11:59.132  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84b554c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cddfc12 9342:com.android.settings/1000}
,05-19 12:11:59.132  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:59.142  3510  4257 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84b554c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:11:59.152  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{e29caaa: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.152  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,05-19 12:11:59.162  9763  9763 D HeadsetService: Received start request. Starting profile...
,05-19 12:11:59.162  9763  9763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
05-19 12:11:59.162  3942  4233 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
05-19 12:11:59.162  3510  3854 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,05-19 12:11:59.162  9763  9763 D HeadsetProvider: make
05-19 12:11:59.162  9763  9763 D HeadsetProvider: HeadsetProvider
,05-19 12:11:59.162  9763  9763 I HeadsetProvider: clearAllHeadsetSettings(0)
,05-19 12:11:59.162  3942  3942 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,05-19 12:11:59.162  3510  4257 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84b554c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{feb16e 4341:com.google.android.gms.persistent/u0a21}
,05-19 12:11:59.162  4341  4341 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-19 12:11:59.172  9763  9763 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,05-19 12:11:59.172  9763  9763 D HeadsetStateMachine: make
,05-19 12:11:59.172  9763  9763 E HeadsetStateMachine: # of Max HF connection is 3
,05-19 12:11:59.182  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-19 12:11:59.182  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{a7e7a38: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.192  3510  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84b554c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3c7fb0 8113:com.sec.android.app.shealth:remote/u0a39}
,05-19 12:11:59.212  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-19 12:11:59.212  9666  9751 D BluetoothAdapter: enable()
,05-19 12:11:59.222  3510  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84b554c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cddfc12 9342:com.android.settings/1000}
,05-19 12:11:59.222  9342  9342 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:59.222  9342  9342 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,05-19 12:11:59.232  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,05-19 12:11:59.232  9763  9763 I bt_bluedroid: get_profile_interface handsfree
,05-19 12:11:59.242  3510  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84b554c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{674a11 9763:com.android.bluetooth/1002}
,05-19 12:11:59.252  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{3a02a49: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.252  3510  4407 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 12:11:59.252  3510  4407 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-19 12:11:59.252  3510  4407 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:11:59.252  3510  4407 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:11:59.252  3510  4407 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-19 12:11:59.252  3510  4407 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-19 12:11:59.252  3510  4407 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-19 12:11:59.252  3510  4407 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-19 12:11:59.252  3510  4407 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 12:11:59.262  3510  4407 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-19 12:11:59.262  3510  4407 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-19 12:11:59.262  3510  4407 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-19 12:11:59.262  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,05-19 12:11:59.272  9763  9763 I DualScoManager: Instantiating Dual Sco Manager
,05-19 12:11:59.272  9763  9763 I DualScoManager: Set HeadsetServiceHelper
,05-19 12:11:59.272  9763  9763 D BluetoothAtMessage: createCMTIContentObservers
,05-19 12:11:59.272  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,05-19 12:11:59.282  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
05-19 12:11:59.282  9763  9776 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
05-19 12:11:59.282  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
05-19 12:11:59.282  9763  9776 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
05-19 12:11:59.282  9763  9776 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-19 12:11:59.282  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{bf4a97c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.292  9763  9776 I BluetoothAdapterState: Entering PendingCommandState
,05-19 12:11:59.292  9763  9776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
05-19 12:11:59.302  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{1a2325a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.302  9763  9776 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-19 12:11:59.302  9763  9763 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@9097676
,05-19 12:11:59.302  9763  9763 D HeadsetProvider: setHeadsetDB - Can't find 300 for A8:81:95:E9:5F:XX
,05-19 12:11:59.312  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{9030c8b: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.312  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{2a0e168: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.312  9763  9763 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 300, 1, true
,05-19 12:11:59.312  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{19dd981: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.322  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{3411a26: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.322  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{813e667: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.322  9763  9763 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@551914d
,05-19 12:11:59.332  9763  9763 D HeadsetProvider: setHeadsetDB - Can't find 400 for A8:81:95:E9:5F:XX
,05-19 12:11:59.332  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{b56ac14: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.332  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{7cd8cbd: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.332  9763  9763 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 400, 1, true
,05-19 12:11:59.342  9763  9802 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,05-19 12:11:59.342  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{a94b2b2: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.342  9763  9763 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
,05-19 12:11:59.342  9763  9763 E HeadsetService: notifyProfileServiceStateChanged
,05-19 12:11:59.342  9763  9802 D HeadsetStateMachine: Clear mHeadsetBrsf
,05-19 12:11:59.342  9763  9802 D HeadsetStateMachine: map size, before remove : 0
05-19 12:11:59.342  9763  9802 D HeadsetStateMachine: map size, after remove: 0
,05-19 12:11:59.342  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{b1747fe: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.342  9763  9763 D A2dpService: Received start request. Starting profile...
05-19 12:11:59.342  9763  9763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
,05-19 12:11:59.352  9763  9763 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,05-19 12:11:59.352  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{d4d3b5f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.352  9763  9763 I bt_bluedroid: get_profile_interface avrcp
,05-19 12:11:59.352  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{c7369ac: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.362  9763  9763 I Avrcp   : No of Audio players :: 1
,05-19 12:11:59.362  9763  9763 I Avrcp   : App Package name is GM
,05-19 12:11:59.362  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{d837498: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.362  9763  9763 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.music
,05-19 12:11:59.362  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{40f24f1: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.372  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{b1a58d6: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.372  9763  9763 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:11:59.372  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{ccd3757: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.372  9763  9763 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,05-19 12:11:59.372  9763  9763 I Avrcp   : No of Video players :: 2
,05-19 12:11:59.372  9763  9763 I Avrcp   : Video App Package name is others
,05-19 12:11:59.382  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{e874244: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.382  9763  9763 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.apps.photos
,05-19 12:11:59.382  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{a601f2d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.382  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{e3b2c62: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.382  9763  9763 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:11:59.392  9763  9763 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,05-19 12:11:59.392  9763  9763 I Avrcp   : Video App Package name is VP
,05-19 12:11:59.392  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{c83f1f3: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.392  9763  9763 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungVideoPlayer/SamsungVideoPlayer.apk / 1.0 running in com.android.bluetooth rsrc of package com.samsung.android.video
,05-19 12:11:59.392  9763  9763 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:11:59.392  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{cd83eb0: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.402  9763  9763 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,05-19 12:11:59.402  9763  9763 I Avrcp   : Add tempPlayer
05-19 12:11:59.402  9763  9763 V Avrcp   : MediaPlayerInfo: mPlayerId=4
05-19 12:11:59.402  9763  9763 V Avrcp   : no_of_players : 4
05-19 12:11:59.402  9763  9763 I Avrcp   : Total no of players: 4
05-19 12:11:59.402  9763  9763 V Avrcp   : Samsung player is the 1st player
05-19 12:11:59.402  9763  9763 D Avrcp   : Compose Browsing Service Candidate
,05-19 12:11:59.402  9763  9763 D Avrcp   : ResolveInfo info ResolveInfo{364de4e com.google.android.music/.browse.MediaBrowserService m=0x108000}
,05-19 12:11:59.402  9763  9763 D Avrcp   : Initialize Media Controller
05-19 12:11:59.402  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{74c8129: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.402  9763  9763 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,05-19 12:11:59.402  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{9a3acae: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.402  9763  9763 E Avrcp   : getActiveSessions
,05-19 12:11:59.402  9763  9763 D Avrcp   : pick active media Controller
,05-19 12:11:59.402  9763  9763 D Avrcp   : Get the active Media Controller 
05-19 12:11:59.402  9763  9763 I BluetoothA2dpServiceJni: classInitNative: succeeds
05-19 12:11:59.402  9763  9763 D A2dpStateMachine: make
,05-19 12:11:59.412  9763  9763 I bt_bluedroid: get_profile_interface a2dp
,05-19 12:11:59.412  9763  9763 E bt_btif : warning : media task started media_task_refcnt 1 
05-19 12:11:59.412  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{5e1ba4f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.412  9763  9806 D A2dpStateMachine: Enter Disconnected: -2
,05-19 12:11:59.412  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{ffa95dc: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.412  9763  9763 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
05-19 12:11:59.412  9763  9763 E A2dpService: notifyProfileServiceStateChanged
,05-19 12:11:59.422  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{18933c8: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.422  9763  9763 D HeadsetStateMachine: Try to query the phonestate on bind
,05-19 12:11:59.422  3510  4407 I Telecom : BluetoothPhoneService: queryPhoneState
05-19 12:11:59.422  3510  4407 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,05-19 12:11:59.422  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{9e22c61: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.422  9763  9763 I BluetoothHidServiceJni: classInitNative: succeeds
,05-19 12:11:59.422  9763  9763 D HidService: Received start request. Starting profile...
,05-19 12:11:59.422  9763  9763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
05-19 12:11:59.422  9763  9763 I bt_bluedroid: get_profile_interface hidhost
05-19 12:11:59.422  9763  9763 D HidService: setHidService(): set to: null
05-19 12:11:59.422  9763  9763 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
,05-19 12:11:59.422  9763  9763 E HidService: notifyProfileServiceStateChanged
05-19 12:11:59.422  9763  9763 I BluetoothHealthServiceJni: classInitNative: succeeds
,05-19 12:11:59.432  9763  9763 D HealthService: Received start request. Starting profile...
,05-19 12:11:59.432  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{2d8a386: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.432  9763  9763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
,05-19 12:11:59.432  9763  9763 I bt_bluedroid: get_profile_interface health
05-19 12:11:59.432  9763  9763 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
,05-19 12:11:59.432  9763  9763 E HealthService: notifyProfileServiceStateChanged
05-19 12:11:59.432  9763  9763 D HeadsetStateMachine: Proxy object connected
,05-19 12:11:59.432  9763  9763 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,05-19 12:11:59.432  9763  9763 D HeadsetPhoneState: sendDeviceDataStateChanged
05-19 12:11:59.432  9763  9802 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-19 12:11:59.432  9763  9763 D HeadsetPhoneState: Signal level : previous=0 curr=0
05-19 12:11:59.432  9763  9802 E HeadsetStateMachine: Unknown message: 11
05-19 12:11:59.432  9763  9802 D HeadsetStateMachine: Disconnected process message: 19, size: 0
,05-19 12:11:59.432  9763  9802 E HeadsetStateMachine: Unknown message: 19
05-19 12:11:59.432  9763  9763 I BluetoothPanServiceJni: classInitNative(L113): succeeds
,05-19 12:11:59.432  9763  9763 D PanService: Received start request. Starting profile...
,05-19 12:11:59.432  9763  9763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
05-19 12:11:59.432  9763  9763 D BluetoothPanServiceJni: initializeNative(L118): pan
05-19 12:11:59.432  9763  9763 I bt_bluedroid: get_profile_interface pan
,05-19 12:11:59.432  9763  9763 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
05-19 12:11:59.432  9763  9763 E PanService: notifyProfileServiceStateChanged
,05-19 12:11:59.432  9763  9763 D BluetoothMapService: Received start request. Starting profile...
,05-19 12:11:59.432  9763  9763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
,05-19 12:11:59.442  3510  4427 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84b554c u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{818aca3 7218:com.google.android.apps.maps/u0a125}
,05-19 12:11:59.452  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{90b7212: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.452  9763  9763 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
05-19 12:11:59.452  9763  9763 E BluetoothMapService: notifyProfileServiceStateChanged
,05-19 12:11:59.462  9763  9763 V SapService: SapBinder()
,05-19 12:11:59.462  3510  3530 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f90b3e0 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:11:59.462  9763  9763 D SapService: Received start request. Starting profile...
05-19 12:11:59.462  9763  9763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
05-19 12:11:59.462  9763  9763 V SapService: start()
,05-19 12:11:59.462  9763  9763 D SapService: Disable sap : false
,05-19 12:11:59.472  9763  9763 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
05-19 12:11:59.472  9763  9763 E SapService: notifyProfileServiceStateChanged
,05-19 12:11:59.472  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{f7d2e0c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.482  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{59c7355: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.492  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{77f316a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.492  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{432865b: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.492  9763  9763 D BleAudioService: Received start request. Starting profile...
,05-19 12:11:59.492  9763  9763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
05-19 12:11:59.492  9763  9763 E DualScoManager: Dual Sco Manager already instantiated
05-19 12:11:59.492  9763  9763 I BtBleAudio.JNI: classInitNative(L304): succeeds
05-19 12:11:59.492  9763  9763 D BleAudioStateMachine: make
,05-19 12:11:59.492  9763  9763 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,05-19 12:11:59.502  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{3d51ef8: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.502  9763  9763 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 0
,05-19 12:11:59.502  9763  9763 I bt_bluedroid: get_profile_interface bleaudio_source
,05-19 12:11:59.502  9763  9763 D BleAudioStateMachine: make
05-19 12:11:59.502  9763  9811 E BleAudioStateMachine_L: Enter Disconnected: -2
,05-19 12:11:59.502  9763  9763 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,05-19 12:11:59.502  9763  9763 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 1
,05-19 12:11:59.502  9763  9763 V BleAudioService: [registerCallStateListener]
05-19 12:11:59.502  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{cfdefd1: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.502  9763  9812 E BleAudioStateMachine_R: Enter Disconnected: -2
,05-19 12:11:59.502  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{3d6fa36: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.512  9763  9763 V BleAudioService: [registerAobleStateChangeListener]
,05-19 12:11:59.512  9763  9763 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Message sending
05-19 12:11:59.512  9763  9763 E BleAudioService: notifyProfileServiceStateChanged
,05-19 12:11:59.512  9763  9763 E BluetoothAdapterService: handleMessage() - Message: 1
,05-19 12:11:59.512  9763  9763 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
,05-19 12:11:59.512  9763  9763 V BluetoothAdapterState: isTurningOff()=false
,05-19 12:11:59.512  9763  9763 V BluetoothAdapterState: isTurningOn()=true
05-19 12:11:59.512  9763  9763 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:59.512  9763  9763 V BluetoothAdapterState: isBleTurningOff()=false
,05-19 12:11:59.512  9763  9763 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-19 12:11:59.512  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{f1083c2: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.512  9763  9763 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 12:11:59.512  9763  9763 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
05-19 12:11:59.512  9763  9802 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-19 12:11:59.512  9763  9763 V BluetoothAdapterState: isTurningOff()=false
,05-19 12:11:59.512  9763  9802 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
05-19 12:11:59.512  9763  9763 V BluetoothAdapterState: isTurningOn()=true
05-19 12:11:59.512  9763  9763 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:59.512  9763  9763 V BluetoothAdapterState: isBleTurningOff()=false
,05-19 12:11:59.512  9763  9763 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
05-19 12:11:59.512  9763  9802 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-19 12:11:59.512  9763  9802 E HeadsetStateMachine: Unknown message: 11
05-19 12:11:59.512  9763  9763 D HeadsetPhoneState: sendDeviceDataStateChanged
05-19 12:11:59.512  9763  9802 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-19 12:11:59.512  9763  9802 E HeadsetStateMachine: Unknown message: 11
05-19 12:11:59.512  9763  9802 D HeadsetStateMachine: Disconnected process message: 19, size: 0
05-19 12:11:59.512  9763  9802 E HeadsetStateMachine: Unknown message: 19
05-19 12:11:59.512  9763  9763 D HeadsetPhoneState: Signal level : previous=0 curr=0
05-19 12:11:59.512  9763  9763 E BluetoothAdapterService: handleMessage() - Message: 1
,05-19 12:11:59.512  9763  9763 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
05-19 12:11:59.512  9763  9763 V BluetoothAdapterState: isTurningOff()=false
05-19 12:11:59.512  9763  9763 V BluetoothAdapterState: isTurningOn()=true
05-19 12:11:59.512  9763  9763 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:59.512  9763  9763 V BluetoothAdapterState: isBleTurningOff()=false
05-19 12:11:59.512  9763  9763 D BluetoothAdapterService: HID Host service started
05-19 12:11:59.522  3942  4148 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,05-19 12:11:59.522  3942  4148 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
05-19 12:11:59.522  3942  4148 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
05-19 12:11:59.522  3942  4148 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-19 12:11:59.522  3942  4148 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-19 12:11:59.522  3942  4148 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-19 12:11:59.522  3942  4148 D HidProfile: mService is null. need to get proxy again!!
05-19 12:11:59.522  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{5a8d510: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.522  9342  9342 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,05-19 12:11:59.522  9342  9342 D BluetoothMap: Create BluetoothMap proxy object
,05-19 12:11:59.522  9763  9763 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-19 12:11:59.522  9763  9763 E BluetoothAdapterService: handleMessage() - Message: 1
,05-19 12:11:59.522  9763  9763 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
,05-19 12:11:59.532  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{a671a0e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isTurningOff()=false
05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isTurningOn()=true
05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isBleTurningOff()=false
05-19 12:11:59.532  9763  9763 E BluetoothAdapterService: handleMessage() - Message: 1
,05-19 12:11:59.532  9763  9763 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
,05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isTurningOff()=false
05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isTurningOn()=true
05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isBleTurningOff()=false
,05-19 12:11:59.532  9763  9763 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 12:11:59.532  9763  9763 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isTurningOff()=false
05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isTurningOn()=true
05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isBleTurningOff()=false
,05-19 12:11:59.532  9763  9763 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 12:11:59.532  9763  9763 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,05-19 12:11:59.532  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{d7ec91a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isTurningOff()=false
,05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isTurningOn()=true
05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:59.532  9763  9763 V BluetoothAdapterState: isBleTurningOff()=false
05-19 12:11:59.532  9763  9763 D BleAudioService: [onCallStateChanged] ENTER -- State: (0)
05-19 12:11:59.532  9763  9763 D BleAudioService: [onCallStateChanged] No devices in connected state
,05-19 12:11:59.532  9763  9763 D BleAudioService: [onCallStateChanged][PHONECALL STATE Changed]: EXIT
05-19 12:11:59.532  9763  9763 E BluetoothAdapterService: handleMessage() - Message: 1
05-19 12:11:59.532  9763  9763 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Before synchronized
,05-19 12:11:59.542  9763  9763 V BluetoothAdapterState: isTurningOff()=false
05-19 12:11:59.542  9763  9763 V BluetoothAdapterState: isTurningOn()=true
05-19 12:11:59.542  9763  9763 V BluetoothAdapterState: isBleTurningOn()=false
05-19 12:11:59.542  9763  9763 V BluetoothAdapterState: isBleTurningOff()=false
05-19 12:11:59.542  9763  9776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,05-19 12:11:59.542  9342  9342 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,05-19 12:11:59.542  9763  9776 E BluetoothServiceJni: enableBrEdrNative:
05-19 12:11:59.542  9763  9776 I bt_bluedroid: enable_bredr
,05-19 12:11:59.542  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{4c9d227: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.542  3942  3942 D BluetoothInputDevice: Proxy object connected
,05-19 12:11:59.542  3942  3942 D HidProfile: Bluetooth service connected
,05-19 12:11:59.552  9763  9780 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf36fef29
,05-19 12:11:59.552  9763  9780 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
05-19 12:11:59.552  9763  9780 D BluetoothAdapterProperties: Address is:A8:81:95:E9:5F:6F
,05-19 12:11:59.552  9763  9780 E BluetoothServiceJni: populateRssiValuesNative
05-19 12:11:59.552  9763  9780 I bt_bluedroid: getModelRssiValues
05-19 12:11:59.552  9763  9780 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
05-19 12:11:59.552  9763  9797 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
05-19 12:11:59.552  9763  9780 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,05-19 12:11:59.552  9342  9342 D LocalBluetoothProfileManager: Adding local BleAudio profile
05-19 12:11:59.552  9763  9780 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7 edge
,05-19 12:11:59.552  9342  9342 D BluetoothLeAudio: getProfileProxy()
,05-19 12:11:59.552  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{5f769c3: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.562  9763  9780 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-19 12:11:59.562  9763  9780 D BluetoothAdapterProperties: Scan Mode:20
05-19 12:11:59.562  9763  9780 D BluetoothAdapterProperties: Discoverable Timeout:-1
05-19 12:11:59.562  9763  9780 E bt_btif : btif_handle_bluetooth_enable_evt
05-19 12:11:59.562  9763  9780 E bt_btif : ANT+ socket does not initialize.
,05-19 12:11:59.562  9763  9797 D CODEC_IF_MOD: codec_open: codec_open
05-19 12:11:59.562  9763  9797 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
05-19 12:11:59.562  9763  9797 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
05-19 12:11:59.562  9763  9797 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
05-19 12:11:59.562  9763  9797 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-19 12:11:59.562  9763  9797 D CODEC_IF: codec_if_close: codec_if_close hdl -290713596
05-19 12:11:59.562  9763  9797 D CODEC_IF_MOD: codec_close: codec_close
05-19 12:11:59.562  9763  9780 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
05-19 12:11:59.562  9763  9797 D CODEC_IF_MOD: codec_close: freed apt-x encoder
05-19 12:11:59.562  9763  9797 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
05-19 12:11:59.562  9763  9797 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
05-19 12:11:59.562  9763  9780 D IOP_DB_BT: db_open: db_open : handle 4083683344l, read 18483 bytes onto local cache
05-19 12:11:59.562  9763  9780 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
05-19 12:11:59.562  9763  9780 D IOP_DB_BT: db_query: result 1
05-19 12:11:59.562  9763  9780 I         : iop_db_open: iop_db_open status 0
05-19 12:11:59.562  9763  9780 E BluetoothAdapterState: stateChangeCallback : 17
05-19 12:11:59.562  9763  9780 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
05-19 12:11:59.562  9763  9780 E bt_btif : btif_sm_dispatch : Invalid handle
05-19 12:11:59.562  9763  9776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
,05-19 12:11:59.562  3510  3510 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,05-19 12:11:59.562  3942  4148 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,05-19 12:11:59.562  9763  9776 D BluetoothAdapterProperties: ScanMode =  20
05-19 12:11:59.562  9763  9776 D BluetoothAdapterProperties: State =  11
,05-19 12:11:59.562  9763  9797 D CODEC_IF_SSHD: codec_open: codec_open
05-19 12:11:59.562  9763  9797 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
05-19 12:11:59.562  9763  9797 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
05-19 12:11:59.562  9763  9797 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-19 12:11:59.562  9763  9797 D CODEC_IF: codec_if_close: codec_if_close hdl -583930496
05-19 12:11:59.562  9763  9797 D CODEC_IF_SSHD: codec_close: codec_close
05-19 12:11:59.562  9763  9797 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
,05-19 12:11:59.572  9763  9797 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
05-19 12:11:59.572  9763  9797 D CODEC_IF_MOD: codec_open: codec_open
05-19 12:11:59.572  9763  9797 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
05-19 12:11:59.572  9763  9797 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
05-19 12:11:59.572  9763  9797 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
,05-19 12:11:59.572  9763  9797 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-19 12:11:59.572  9763  9797 D CODEC_IF: codec_if_close: codec_if_close hdl -290713596
05-19 12:11:59.572  9763  9797 D CODEC_IF_MOD: codec_close: codec_close
05-19 12:11:59.572  9763  9797 D CODEC_IF_MOD: codec_close: freed apt-x encoder
05-19 12:11:59.572  9763  9797 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
05-19 12:11:59.572  9763  9797 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
05-19 12:11:59.572  9763  9797 D CODEC_IF_SSHD: codec_open: codec_open
05-19 12:11:59.572  9763  9797 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
,05-19 12:11:59.572  9763  9797 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
05-19 12:11:59.572  9763  9797 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-19 12:11:59.572  9763  9797 D CODEC_IF: codec_if_close: codec_if_close hdl -583930496
05-19 12:11:59.572  9763  9797 D CODEC_IF_SSHD: codec_close: codec_close
05-19 12:11:59.572  9763  9780 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
05-19 12:11:59.572  9763  9797 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
05-19 12:11:59.572  9763  9780 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
05-19 12:11:59.572  9763  9780 E bt_btif : no av control block available at state:3
05-19 12:11:59.572  9763  9780 E bt_btif : no av control block available at state:3
05-19 12:11:59.572  9763  9780 E bt_btif : no av control block available at state:2
,05-19 12:11:59.572  9763  9780 E bt_btif : BTA got event 0x518
05-19 12:11:59.572  9763  9780 E bt_btif : no av control block available at state:3
05-19 12:11:59.572  9763  9780 E bt_btif : no av control block available at state:2
05-19 12:11:59.572  9763  9780 W bt_btif : Adding UUID=0x1112 into EIR: unhandled event:BTA_AV_REGISTER_EVT
05-19 12:11:59.572  9763  9780 E bt_btif : btif_sm_dispatch : Invalid handle
05-19 12:11:59.572  9763  9780 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
05-19 12:11:59.572  9763  9780 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
05-19 12:11:59.572  9763  9780 E bt_btif : no av control block available at state:3
05-19 12:11:59.572  9763  9780 E bt_btif : bta_dm_eir_update_uuid UUID bit mask=0x0
05-19 12:11:59.572  9763  9780 E bt_btif : BTM_SEC_REG[7]: id 12, is_orig 0, psm 0x
,05-19 12:11:59.572  9763  9780 E bt_btif : warning : no command pending, ignore ack
05-19 12:11:59.572  9763  9780 E bt_btif : no av control block availabl, service na
05-19 12:11:59.572  9763  9780 E bt_btif : no av control block available at state:2
05-19 12:11:59.572  9763  9780 W bt_btif : BTM_SEC_REG[7]: id 12, is_orig 0: 0x36
05-19 12:11:59.572  9763  9780 E bt_btif : BTM_SEC_REG[8]: id 29, is_orig 0,
05-19 12:11:59.572  9763  9780 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,05-19 12:11:59.582  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{4d422be: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.582  3510  4406 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,05-19 12:11:59.582  3510  4059 D SecContentProvider: insert(), uri = 2
,05-19 12:11:59.582  9342  9342 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,05-19 12:11:59.592  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:59.592  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{a2bacca: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.592  9342  9342 D BluetoothMap: Proxy object connected
,05-19 12:11:59.592  9342  9342 D MapProfile: Bluetooth service connected
05-19 12:11:59.592  9342  9342 D BluetoothMap: getConnectedDevices()
05-19 12:11:59.592  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,05-19 12:11:59.592  9763  9780 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-19 12:11:59.592  9763  9780 D BluetoothAdapterProperties: Scan Mode:21
05-19 12:11:59.592  9763  9780 D BluetoothAdapterProperties: Discoverable Timeout:-1
05-19 12:11:59.592  9763  9776 D BluetoothAdapterProperties: Setting state to 12
05-19 12:11:59.592  9763  9776 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
05-19 12:11:59.592  9763  9776 D HeadsetService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@2a79cdc
05-19 12:11:59.592  9763  9776 D A2dpService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@2a79cdc
05-19 12:11:59.592  9763  9776 D BleAudioService: setHeadsetService: setting HeadsetService
05-19 12:11:59.592  9763  9776 D BleAudioService: setA2dpService: setting A2dpService
,05-19 12:11:59.602  9763  9776 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,05-19 12:11:59.602  9763  9776 D BluetoothAdapterService: updateAdapterState state is 12
,05-19 12:11:59.602  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{18b7958: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.612  9666  9666 D BluetoothAdapter: STATE_ON
,05-19 12:11:59.612  9763  9776 V BluetoothAdapterService: start opp service
,05-19 12:11:59.612  9666  9666 D BluetoothAdapter: STATE_ON
05-19 12:11:59.622  9666  9666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,05-19 12:11:59.622  9342  9342 D BluetoothInputDevice: Proxy object connected
,05-19 12:11:59.622  9342  9342 D HidProfile: Bluetooth service connected
05-19 12:11:59.622  9666  9666 D BluetoothAdapter: STATE_ON
,05-19 12:11:59.632  9763  9763 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,05-19 12:11:59.632  9763  9776 D BluetoothAdapterService: Autoconnection is available 
05-19 12:11:59.632  9763  9776 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
05-19 12:11:59.632  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{6bfcb96: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.632  9763  9776 D BluetoothAdapterService: starting service from this receiver
,05-19 12:11:59.632  3942  5084 D BluetoothLeAudio: onBluetoothStateChange: up=true
05-19 12:11:59.632  3942  5084 D BluetoothLeAudio: Binding service...
05-19 12:11:59.632  9763  9763 I BluetoothPbapService: Handler(): got msg=1
,05-19 12:11:59.632  9666  9666 D BluetoothAdapter: STATE_ON
,05-19 12:11:59.642  3510  3529 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,05-19 12:11:59.642  9666  9666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,05-19 12:11:59.642  9763  9776 D BluetoothAdapterService: BT on, init HID DEV count : 0
05-19 12:11:59.642  9763  9776 I BluetoothAdapterState: Entering OnState,
05-19 12:11:59.642  3942  3942 D BluetoothLeAudio: Proxy object connected
05-19 12:11:59.642  3942  3942 D BleAudioProfile: Bluetooth service connected
05-19 12:11:59.642  3942  3942 D BluetoothLeAudio: getConnectedDevices()
,05-19 12:11:59.652  3942  5084 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,05-19 12:11:59.652  9342  9354 D BluetoothSap: onBluetoothStateChange: up=true
,05-19 12:11:59.652  9342  9354 D BluetoothSap: Binding service...
,05-19 12:11:59.652  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{e5f40ed: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.652  9763  9818 V BluetoothPbapService: PBAP Service initSocket try: 0
,05-19 12:11:59.652  9342  9342 D BluetoothLeAudio: Proxy object connected
,05-19 12:11:59.652  9342  9342 D BleAudioProfile: Bluetooth service connected
,05-19 12:11:59.652  9342  9342 D BluetoothLeAudio: getConnectedDevices()
,05-19 12:11:59.662  9342  9342 D BluetoothPbap: Proxy object connected
,05-19 12:11:59.662  9342  9342 D PbapServerProfile: Bluetooth service connected
,05-19 12:11:59.662  9342  9353 D BluetoothPbap: onBluetoothStateChange: up=true
,05-19 12:11:59.662  9342  9354 D BluetoothAdapter: onBluetoothStateChange: up=true
05-19 12:11:59.662  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{7c41b70: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.662  9342  9354 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-19 12:11:59.672  9763  9763 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-19 12:11:59.672  9666  9666 D BluetoothAdapter: STATE_ON
05-19 12:11:59.672  9763  9818 D BluetoothSocket: bindListen(): myUserId = 0
05-19 12:11:59.672  9763  9818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 12:11:59.672  9763  9763 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-19 12:11:59.672  3942  3956 D BluetoothMap: onBluetoothStateChange: up=true
05-19 12:11:59.672  3942  3956 D BluetoothMap: Binding service...
,05-19 12:11:59.682  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{77bfee9: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.682  9763  9818 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,05-19 12:11:59.682  9763  9763 V BtOppService: isOwner == true
,05-19 12:11:59.682  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 12:11:59.682  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:11:59.682  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:11:59.682  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:11:59.682  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:11:59.682  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 12:11:59.682  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 12:11:59.682  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 12:11:59.682  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 12:11:59.682  3942  3942 D BluetoothMap: Proxy object connected
,05-19 12:11:59.682  3942  3942 D MapProfile: Bluetooth service connected
05-19 12:11:59.682  3942  3942 D BluetoothMap: getConnectedDevices()
,05-19 12:11:59.682  3942  5552 D BluetoothInputDevice: onBluetoothStateChange: up=true
,05-19 12:11:59.682  3942  5552 D BluetoothInputDevice: Binding service...
05-19 12:11:59.692  9666  9666 D BluetoothAdapter: STATE_ON
,05-19 12:11:59.692  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{8a77e9c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.692  3942  3942 D BluetoothInputDevice: Proxy object connected
05-19 12:11:59.692  3942  3942 D HidProfile: Bluetooth service connected
,05-19 12:11:59.702  4276  4287 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-19 12:11:59.702  4276  4287 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-19 12:11:59.702  9666  9666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-19 12:11:59.702  9342  9353 D BluetoothMap: onBluetoothStateChange: up=true
,05-19 12:11:59.702  3942  5084 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-19 12:11:59.702  3942  5084 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-19 12:11:59.702  4163  7409 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.android.bluetooth,id=0,extra=Bundle[mParcelledData.dataSize=160]
05-19 12:11:59.702  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=com.android.bluetooth, samsung.notification.remove_all=true}]
05-19 12:11:59.702  3942  4372 D BluetoothPan: onBluetoothStateChange on: true
,05-19 12:11:59.702  3942  4372 D BluetoothPan: onBluetoothStateChange calling doBind()
05-19 12:11:59.702  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
,05-19 12:11:59.702  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,05-19 12:11:59.702  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{b204646: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.702  4163  4163 I PeopleDataManager: removeNotification
05-19 12:11:59.702  4163  4163 I NotificationParser: getNotiType:com.android.bluetooth,null
05-19 12:11:59.702  4163  4163 D PeopleDataManager: removeNotiInfo: id =0,packageName=com.android.bluetooth,isEdgeNotification=false,key=null,removeAll=true
05-19 12:11:59.702  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-19 12:11:59.712  7218  7229 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-19 12:11:59.712  7218  7229 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-19 12:11:59.712  4288  5440 D BluetoothAdapter: onBluetoothStateChange: up=true
05-19 12:11:59.712  4288  5440 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-19 12:11:59.712  5053  5065 D BluetoothA2dp: onBluetoothStateChange: up=true
,05-19 12:11:59.712  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{e7858ff: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.712  5053  5065 D BluetoothA2dp: Binding service...
,05-19 12:11:59.722  5053  5065 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-19 12:11:59.722  9342  9342 D BluetoothSap: Proxy object connected
,05-19 12:11:59.722  9342  9342 D SapProfile: Bluetooth service connected
,05-19 12:11:59.722  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{2b42364: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.722  3942  3956 D BluetoothSap: onBluetoothStateChange: up=true
05-19 12:11:59.722  3942  3956 D BluetoothSap: Binding service...
,05-19 12:11:59.732  3510  4983 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,05-19 12:11:59.732  3942  3942 D BluetoothSap: Proxy object connected
,05-19 12:11:59.732  3942  3942 D SapProfile: Bluetooth service connected
,05-19 12:11:59.732  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{2329d93: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.732  9763  9817 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-19 12:11:59.732  9763  9817 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-19 12:11:59.732  3510  3609 D BluetoothA2dp: onBluetoothStateChange: up=true
05-19 12:11:59.732  3510  3609 D BluetoothA2dp: Binding service...
,05-19 12:11:59.732  3510  3609 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-19 12:11:59.732  9666  9677 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-19 12:11:59.732  9666  9677 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-19 12:11:59.742  3510  3609 D BluetoothPan: onBluetoothStateChange on: true
,05-19 12:11:59.742  3510  3609 D BluetoothPan: onBluetoothStateChange calling doBind()
,05-19 12:11:59.742  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{a7e7afc: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.742  9342  9353 D BluetoothInputDevice: onBluetoothStateChange: up=true
05-19 12:11:59.742  3510  3510 D BluetoothPan: BluetoothPAN Proxy object connected
,05-19 12:11:59.742  3942  3942 D BluetoothPan: BluetoothPAN Proxy object connected
,05-19 12:11:59.742  3942  3942 D PanProfile: Bluetooth service connected
,05-19 12:11:59.742  3510  3510 D BluetoothA2dp: Proxy object connected
,05-19 12:11:59.742  5053  5053 D BluetoothA2dp: Proxy object connected
,05-19 12:11:59.752  9763  9801 D A2dpStateMachine: getConnectedDevices : size=0
,05-19 12:11:59.752  4341  7514 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-19 12:11:59.752  4341  7514 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-19 12:11:59.752  9763  9823 D BluetoothSocket: bindListen(): myUserId = 0
05-19 12:11:59.752  9763  9823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 12:11:59.752  3942  3957 D BluetoothInputDevice: onBluetoothStateChange: up=true
05-19 12:11:59.752  3510  3609 D BluetoothAdapter: onBluetoothStateChange: up=true
05-19 12:11:59.752  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{c3b5585: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.752  3510  3609 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-19 12:11:59.752  3942  3956 D BluetoothA2dp: onBluetoothStateChange: up=true
,05-19 12:11:59.752  3942  3956 D BluetoothA2dp: Binding service...
,05-19 12:11:59.762  9763  9823 I BtOppRfcommListener: Accept thread started.
,05-19 12:11:59.762  3942  3956 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
05-19 12:11:59.762  9763  9822 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-19 12:11:59.762  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{1b64ae8: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.762  9763  9822 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-19 12:11:59.762  3942  3942 D BluetoothA2dp: Proxy object connected
05-19 12:11:59.762  3942  3942 D A2dpProfile: Bluetooth service connected
,05-19 12:11:59.762  3942  4372 D BluetoothPbap: onBluetoothStateChange: up=true
05-19 12:11:59.762  3942  4372 D BluetoothPbap: Binding service...
,05-19 12:11:59.762  9763  9816 D A2dpStateMachine: getConnectedDevices : size=0
,05-19 12:11:59.772  3942  3942 D BluetoothPbap: Proxy object connected
05-19 12:11:59.772  3942  3942 D PbapServerProfile: Bluetooth service connected
,05-19 12:11:59.772  8113  8123 D BluetoothAdapter: onBluetoothStateChange: up=true
05-19 12:11:59.772  8113  8123 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-19 12:11:59.772  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{f317de7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.772  9342  9354 D BluetoothPan: onBluetoothStateChange on: true
05-19 12:11:59.772  9342  9354 D BluetoothPan: onBluetoothStateChange calling doBind()
,05-19 12:11:59.782  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{742d032: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.782  9342  9342 D BluetoothPan: BluetoothPAN Proxy object connected
05-19 12:11:59.782  9342  9342 D PanProfile: Bluetooth service connected
,05-19 12:11:59.782  9342  9353 D BluetoothLeAudio: onBluetoothStateChange: up=true
,05-19 12:11:59.782  5053  5078 D BluetoothAdapter: onBluetoothStateChange: up=true
05-19 12:11:59.782  5053  5078 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-19 12:11:59.792  3510  3510 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,05-19 12:11:59.792  3510  3510 I InputMethodManagerService: [BT Setting State] State =12
05-19 12:11:59.792  3510  3510 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
05-19 12:11:59.792  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{b8e1183: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.792  3510  3510 I Telecom : BluetoothPhoneService: queryPhoneState
,05-19 12:11:59.792  3510  3510 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,05-19 12:11:59.792  4330  4330 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:59.792  3942  4148 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-19 12:11:59.792  9666  9751 D BluetoothAdapter: STATE_ON
05-19 12:11:59.792  3942  4148 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
05-19 12:11:59.792  4814  4814 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-19 12:11:59.802  3510  3510 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-19 12:11:59.802  3510  3510 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:59.802  3510  3510 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-19 12:11:59.802  9666  9751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 12:11:59.802  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:11:59.802  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:11:59.802  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:11:59.802  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:11:59.802  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 12:11:59.802  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 12:11:59.802  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 12:11:59.802  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 12:11:59.802  9666  9729 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
05-19 12:11:59.802  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
05-19 12:11:59.802  9342  9342 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:59.802  9342  9342 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,05-19 12:11:59.812  3510  3975 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 12:11:59.812  3510  3975 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
05-19 12:11:59.812  9666  9729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:59.812  3510  3975 D WifiService: setWifiEnabled: false pid=9666, uid=10078
,05-19 12:11:59.812  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:11:59.822  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3258f00 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cddfc12 9342:com.android.settings/1000}
,05-19 12:11:59.842  9825  9825 E Zygote  : v2
05-19 12:11:59.842  9825  9825 I libpersona: KNOX_SDCARD checking this for 10052
05-19 12:11:59.842  9825  9825 E Zygote  : isSdpEnabledProcess - SDP enabled
05-19 12:11:59.842  9825  9825 I libpersona: KNOX_SDCARD not a persona
,05-19 12:11:59.842  9825  9825 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:11:59.842  3510  4040 I ActivityManager: Start proc 9825:com.samsung.android.email.provider/u0a52 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
05-19 12:11:59.842  9825  9825 E Zygote  : accessInfo : 64
05-19 12:11:59.842  9825  9825 E Zygote  : isSdpEnabledProcess - SDP enabled
05-19 12:11:59.842  9825  9825 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
05-19 12:11:59.842  9825  9825 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
05-19 12:11:59.842  3510  3975 D SettingsProvider: isChangeAllowed() : name = wifi_on
,05-19 12:11:59.852  3510  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-19 12:11:59.852  9342  9342 D LocalBluetoothProfileManager: Adding local A2DP profile
,05-19 12:11:59.852  3510  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-19 12:11:59.852  3510  3863 D WifiStateMachine: setFccChannel: channel = 0
05-19 12:11:59.852  3510  3863 D WifiController: [FCC]setFccChannel() is called !!!
,05-19 12:11:59.852  3510  3863 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
05-19 12:11:59.852  3510  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-19 12:11:59.852  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{449bd7e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:11:59.852  3942  4148 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-19 12:11:59.852  3942  4148 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-19 12:11:59.852  3942  4148 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-19 12:11:59.852  3942  4148 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
05-19 12:11:59.852  3942  4148 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,05-19 12:11:59.862  3510  3860 D WifiBigDataLog: init : 
,05-19 12:11:59.862  3510  3863 D SecContentProvider: insert(), uri = 2
,05-19 12:11:59.862  3510  3857 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,05-19 12:11:59.862  9342  9342 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-19 12:11:59.862  3510  3857 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: true, uidstate: 16, mProxSensorScreenOff: false
,05-19 12:11:59.862  3510  3860 D WifiStateMachine: setFccChannelNative: channel = 0
,05-19 12:11:59.862  3510  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
05-19 12:11:59.872  9342  9342 D LocalBluetoothProfileManager: Adding local HEADSET profile
,05-19 12:11:59.872  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{6c62dfb: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.872  9342  9342 E BluetoothHeadset: BTStateChangeCB is registed
,05-19 12:11:59.872  9342  9342 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
,05-19 12:11:59.872  9342  9342 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-19 12:11:59.872  9342  9342 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,05-19 12:11:59.872  9342  9342 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
05-19 12:11:59.872  9342  9342 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
05-19 12:11:59.882  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{e75fe56: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.892  9825  9825 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:11:59.892  9825  9825 D ActivityThread: Added TimaKeyStore provider
05-19 12:11:59.892  3510  3860 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,05-19 12:11:59.902  9342  9342 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-19 12:11:59.902  3942  4233 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
05-19 12:11:59.902  3510  4312 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f02049a) visible user=0 )
05-19 12:11:59.902  3510  4427 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,05-19 12:11:59.912  3510  3860 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 12:11:59.912  3510  3860 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 12:11:59.912  3510  3860 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-19 12:11:59.912  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{83faed7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.912  3942  4148 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:11:59.912  3942  4148 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,05-19 12:11:59.922  9342  9342 D BluetoothA2dp: Proxy object connected
,05-19 12:11:59.922  9342  9342 D A2dpProfile: Bluetooth service connected
,05-19 12:11:59.932  3510  4983 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3258f00 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:11:59.932  9825  9825 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:11:59.932  9825  9825 D RelationGraph: garbageCollect()
,05-19 12:11:59.932  9825  9825 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,05-19 12:11:59.942  3510  4518 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:11:59.942  9825  9825 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:11:59.942  3510  3860 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-19 12:11:59.942  3510  3860 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 12:11:59.942  3510  3860 D SecContentProvider: insert(), uri = 2
,05-19 12:11:59.942  9763  9773 D A2dpStateMachine: getConnectedDevices : size=0
,05-19 12:11:59.942  9825  9825 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:11:59.952  9825  9825 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:11:59.952  3510  3530 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3258f00 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{feb16e 4341:com.google.android.gms.persistent/u0a21}
,05-19 12:11:59.952  4341  4341 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-19 12:11:59.952  3510  3860 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-19 12:11:59.962  3510  3530 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3258f00 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3c7fb0 8113:com.sec.android.app.shealth:remote/u0a39}
,05-19 12:11:59.962  3510  3860 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 12:11:59.962  3510  3860 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-19 12:11:59.972  3510  3860 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-19 12:11:59.972  3510  3860 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 12:11:59.972  3942  4148 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 12:11:59.972  3510  3860 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,05-19 12:11:59.972  3942  4148 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
05-19 12:11:59.972  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{73622ad: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:11:59.972  9342  9342 D DockEventReceiver: finishStartingService: stopping service
,05-19 12:11:59.972  3510  3858 D WifiP2pService: InactiveState{ what=143375 }
05-19 12:11:59.972  9825  9825 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
05-19 12:11:59.972  3510  3858 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-19 12:11:59.982  3510  4409 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3258f00 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cddfc12 9342:com.android.settings/1000}
,05-19 12:11:59.982  9342  9342 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:11:59.982  9342  9342 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,05-19 12:11:59.982  3510  4761 V AlarmManager:  remove PendingIntent] PendingIntent{5666173: PendingIntentRecord{997efa8 android broadcastIntent}}
,05-19 12:11:59.982  3158  3625 D CommandListener: Clearing all IP addresses on wlan0
,05-19 12:11:59.992  3510  3815 V AlarmManager: Expired Alarm result :8
,05-19 12:11:59.992  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:12:00.002  4341  5995 V NativeCrypto: Read error: ssl=0x7f64b08c80: I/O error during system call, Connection timed out
,05-19 12:12:00.012  3510  3869 E ConnectivityService: updateNetworkInfo()
05-19 12:12:00.012  3510  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]
05-19 12:12:00.012  3510  3869 E ConnectivityService: updateNetworkInfo()
05-19 12:12:00.012  3510  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
05-19 12:12:00.012  3510  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 6
,05-19 12:12:00.012  3510  3869 V NetworkStats: updateIfacesLocked()
05-19 12:12:00.012  3510  3869 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:00.012  3510  3869 V NetworkStats: performPollLocked(flags=0x1)
,05-19 12:12:00.022  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{23f3ca9: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.022  4341  5995 V NativeCrypto: SSL shutdown failed: ssl=0x7f64b08c80: I/O error during system call, Broken pipe
,05-19 12:12:00.022  3510  3869 D NetworkStatsRecorder: entry.iface is null
05-19 12:12:00.022  3510  3869 D NetworkStatsRecorder: entry.iface is null
05-19 12:12:00.022  3510  3869 D NetworkStatsRecorder: entry.iface is null
05-19 12:12:00.022  3510  3869 D NetworkStatsRecorder: entry.iface is null
,05-19 12:12:00.022  3510  3869 V NetworkStats: performPollLocked() took 10ms
05-19 12:12:00.022  3510  3869 D NtpTrustedTime: currentTimeMillis() cache hit
,05-19 12:12:00.032  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{d1e822e: PendingIntentRecord{e0901b com.google.android.gms broadcastIntent}}
,05-19 12:12:00.032  4341  5995 E GCM     : Wifi connection closed with errorCode 20
,05-19 12:12:00.032  3510  3854 D RCPManagerService: exchangeData() failure , invalid userId
,05-19 12:12:00.042  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:12:00.052  3510  3860 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,05-19 12:12:00.052  3510  3858 D WifiP2pService: InactiveState{ what=131204 }
,05-19 12:12:00.052  3510  3858 D WifiP2pService: P2pEnabledState{ what=131204 }
,05-19 12:12:00.052  4288  4288 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
05-19 12:12:00.052  4126  4126 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
05-19 12:12:00.052  4126  4126 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
,05-19 12:12:00.052  3510  3858 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,05-19 12:12:00.062  3510  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:00.062  3510  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]
05-19 12:12:00.062  3510  3869 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
05-19 12:12:00.062  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:00.062  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:00.062  3510  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:00.062  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
05-19 12:12:00.062  3510  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-19 12:12:00.072  3510  3510 I WifiTrafficPoller: evaluateTrafficStatsPolling
,05-19 12:12:00.072  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:00.072  3510  3510 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-19 12:12:00.072  3510  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:00.072  3510  3510 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.072  3510  3510 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
05-19 12:12:00.072  3510  3510 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-19 12:12:00.072  3510  3510 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
05-19 12:12:00.072  3510  3867 I WifiHs20Service: Message received 5007
,05-19 12:12:00.082  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:00.082  3510  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:00.082  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:00.082  3510  3869 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:00.082  3510  3530 D ConnectivityService: getVpnConfig > userId : 0
,05-19 12:12:00.092  3510  4759 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
05-19 12:12:00.092  3510  3869 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:00.092  3510  3860 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:00.092  3510  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:00.092  3510  3895 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:00.092  3510  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 12:12:00.092  3510  3860 D WIFI    : evalRequest
05-19 12:12:00.092  3510  3895 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-19 12:12:00.092  3510  3860 D WIFI    :   done
05-19 12:12:00.092  3510  3895 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 12:12:00.092  3510  3895 D Ethernet: evalRequest
05-19 12:12:00.092  3510  3895 D Ethernet:   done
05-19 12:12:00.092  3510  3860 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:00.092  3510  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:00.092  3510  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 12:12:00.092  3510  3860 D WIFI    : evalRequest
05-19 12:12:00.092  3510  3860 D WIFI    :   needNetworkFor
05-19 12:12:00.092  3510  3860 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:00.092  3510  3860 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:00.092  3510  3860 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 12:12:00.092  3510  3860 D WIFI_UT : evalRequest
05-19 12:12:00.092  3510  3860 D WIFI_UT :   done
,05-19 12:12:00.102  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:00.102  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-19 12:12:00.102  3510  3609 D EntConnectivity: Not allowed due to - mEnabled false
,05-19 12:12:00.112  3510  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3258f00 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{674a11 9763:com.android.bluetooth/1002}
,05-19 12:12:00.112  3942  3942 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
05-19 12:12:00.112  3942  3942 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
05-19 12:12:00.112  3942  3942 D KeyguardUpdateMonitor: handleTimeUpdate
,05-19 12:12:00.122  3942  3942 D Clock   : received broadcast android.intent.action.TIME_TICK
,05-19 12:12:00.122  3510  3510 D RttService: SCAN_AVAILABLE : 1
05-19 12:12:00.122  3510  3894 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,05-19 12:12:00.132  3510  4409 D RCPManagerService: exchangeData() failure , invalid userId
,05-19 12:12:00.132  9825  9825 D InjectionManager: InjectionManager
,05-19 12:12:00.132  9825  9825 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,05-19 12:12:00.132  3510  3610 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.132  3510  3610 I WifiDisplayAdapter: onP2pDisconnected
05-19 12:12:00.132  3510  3610 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-19 12:12:00.132  3510  3610 D IpRemoteDisplayController: WfdBridgeServer is already null
,05-19 12:12:00.132  3158  3625 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-19 12:12:00.142  3510  3510 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
,05-19 12:12:00.142  9825  9825 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
05-19 12:12:00.142  3510  3510 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
05-19 12:12:00.142  9825  9825 I InjectionManager: featureStore :{}
05-19 12:12:00.142  3510  3858 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
05-19 12:12:00.142  4163  4173 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
05-19 12:12:00.142  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
,05-19 12:12:00.142  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 12:12:00.142  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 12:12:00.142  4163  4163 I PeopleDataManager: removeNotification
,05-19 12:12:00.142  4163  4163 I NotificationParser: getNotiType:android,null
05-19 12:12:00.142  4163  4163 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 12:12:00.142  4163  4163 D PeopleDataManager: removeNotiInfo =null
05-19 12:12:00.142  3510  3510 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
05-19 12:12:00.142  3510  3610 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,05-19 12:12:00.142  3510  3610 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
,05-19 12:12:00.142  3510  3610 D WifiDisplayController: disconnect
05-19 12:12:00.142  3510  3610 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-19 12:12:00.142  3510  3858 D SecContentProvider: insert(), uri = 2
,05-19 12:12:00.152  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{f3ba1cf: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.152  3510  3858 D WifiP2pService: P2pDisablingState
,05-19 12:12:00.152  3510  3858 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:00.152  3510  3858 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:00.152  3510  3858 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 12:12:00.152  3510  3858 D WIFI_P2P: evalRequest
05-19 12:12:00.152  3510  3858 D WIFI_P2P:   done
,05-19 12:12:00.152  3510  3858 D WifiP2pService: P2pDisablingState{ what=147458 }
05-19 12:12:00.152  3510  3858 D WifiP2pService: p2p socket connection lost
,05-19 12:12:00.152  3510  3858 D SecContentProvider: insert(), uri = 2
,05-19 12:12:00.152  3510  3610 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
,05-19 12:12:00.152  3510  3610 I WifiDisplayAdapter: onP2pDisconnected
05-19 12:12:00.152  3510  3860 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,05-19 12:12:00.152  3510  3610 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-19 12:12:00.152  3510  3610 D IpRemoteDisplayController: WfdBridgeServer is already null
05-19 12:12:00.152  3158  3625 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-19 12:12:00.152  3510  3858 D WifiP2pService: P2pDisabledState
,05-19 12:12:00.162  3510  3869 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -25]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
05-19 12:12:00.162  3510  3869 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,05-19 12:12:00.162  3510  3869 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
05-19 12:12:00.162  9763  9763 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
05-19 12:12:00.162  9763  9763 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is12
05-19 12:12:00.162  9763  9811 D BleAudioStateMachine_L: [Disconnected] Disconnected process message: 41
05-19 12:12:00.162  9763  9811 D BleAudioStateMachine_L: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,05-19 12:12:00.162  9763  9812 D BleAudioStateMachine_R: [Disconnected] Disconnected process message: 41
05-19 12:12:00.162  3510  3858 D WifiP2pService: P2pDisabledState{ what=143375 }
05-19 12:12:00.162  9763  9812 D BleAudioStateMachine_R: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
05-19 12:12:00.162  3510  3858 D WifiP2pService: DefaultState{ what=143375 }
,05-19 12:12:00.162  9763  9811 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 1
,05-19 12:12:00.162  9763  9811 D BleAudioService: NotifyEvents: n : 0
05-19 12:12:00.162  9763  9812 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 2
05-19 12:12:00.162  9763  9812 D BleAudioService: NotifyEvents: n : 0
,05-19 12:12:00.172  3510  3609 D EntConnectivity: Not allowed due to - mEnabled false
,05-19 12:12:00.172  3942  3942 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,05-19 12:12:00.172  3942  3942 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
05-19 12:12:00.172  3942  3942 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-19 12:12:00.172  3942  3942 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-19 12:12:00.172  3942  3942 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-19 12:12:00.172  3510  4040 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
05-19 12:12:00.172  3942  3942 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,05-19 12:12:00.182  9851  9851 E Zygote  : v2
05-19 12:12:00.182  9851  9851 I libpersona: KNOX_SDCARD checking this for 10004
05-19 12:12:00.182  9851  9851 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:00.182  9851  9851 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 12:12:00.182  3510  4312 I ActivityManager: Start proc 9851:com.sec.android.provider.badge/u0a4 for content provider com.sec.android.provider.badge/.BadgeProvider
,05-19 12:12:00.192  3158  3625 D CommandListener: Clearing all IP addresses on wlan0
05-19 12:12:00.192  9851  9851 E Zygote  : accessInfo : 0
05-19 12:12:00.192  9851  9851 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,05-19 12:12:00.192  9763  9763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
05-19 12:12:00.192  9763  9763 D BtConfig.SecureMode: isSecureModeOn:false
,05-19 12:12:00.192  3942  3942 D HeadsetProfile: Bluetooth service connected
,05-19 12:12:00.202  9342  9342 D HeadsetProfile: Bluetooth service connected
,05-19 12:12:00.202  3510  3510 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@ccb275c
05-19 12:12:00.202  3510  3510 D BluetoothHeadset: registerMessageListener
,05-19 12:12:00.222  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:12:00.232  9851  9851 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:00.232  9851  9851 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:00.232  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 12:12:00.232  3510  3594 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,05-19 12:12:00.232  3510  3594 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:00.232  3510  3594 D GpsLocationProvider: updateNetworkState unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:00.242  4814  4814 D SamsungIME: EngineType = SWIFTKEY
,05-19 12:12:00.252  5067  5141 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
05-19 12:12:00.252  5067  5141 I CellLocationSupport: onCellLocationChanged
,05-19 12:12:00.252  4814  4814 D SamsungIME: mNetworkChangeReceiver isWLANConnected : false
05-19 12:12:00.252  3158  3625 E Netd    : netlink response contains error (No such file or directory)
,05-19 12:12:00.252  3510  3869 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
,05-19 12:12:00.252  3510  3869 D ConnectivityService: nai.networkMonitor.doQuit()
05-19 12:12:00.252  3510  3869 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
05-19 12:12:00.252  3510  3869 E ConnectivityService: updateNetworkInfo()
,05-19 12:12:00.252  3510  3869 E ConnectivityService: updateNetworkInfo()
05-19 12:12:00.252  3510  3869 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:00.252  3158  3621 D EnterpriseController: netId is 0
05-19 12:12:00.252  3510  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
05-19 12:12:00.252  3158  3621 D Netd    : getNetworkForDns: using netid 0 for uid 10002
,05-19 12:12:00.262  4592  9867 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
05-19 12:12:00.262  4592  9867 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
05-19 12:12:00.262  4592  9867 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
05-19 12:12:00.262  4592  9867 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
05-19 12:12:00.262  4592  9867 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
05-19 12:12:00.262  4592  9867 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
05-19 12:12:00.262  4592  9867 E         : 	at java.lang.Thread.run(Thread.java:818)
05-19 12:12:00.262  4592  9867 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-19 12:12:00.262  4592  9867 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
05-19 12:12:00.262  4592  9867 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
05-19 12:12:00.262  4592  9867 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
05-19 12:12:00.262  4592  9867 E         : 	... 9 more
05-19 12:12:00.262  4592  9867 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
05-19 12:12:00.262  4592  9867 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
05-19 12:12:00.262  4592  9867 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
05-19 12:12:00.262  4592  9867 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
05-19 12:12:00.262  4592  9867 E         : 	... 24 more
05-19 12:12:00.262  4592  9867 E         : 
,05-19 12:12:00.262  4592  9867 E         : Unable to fetch advertisement frequency.
05-19 12:12:00.262  4592  9867 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
05-19 12:12:00.262  4592  9867 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
05-19 12:12:00.262  4592  9867 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
05-19 12:12:00.262  4592  9867 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
05-19 12:12:00.262  4592  9867 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
05-19 12:12:00.262  4592  9867 E         : 	at java.lang.Thread.run(Thread.java:818)
05-19 12:12:00.262  4592  9867 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-19 12:12:00.262  4592  9867 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
05-19 12:12:00.262  4592  9867 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
05-19 12:12:00.262  4592  9867 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
05-19 12:12:00.262  4592  9867 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
05-19 12:12:00.262  4592  9867 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
05-19 12:12:00.262  4592  9867 E         : 	... 9 more
05-19 12:12:00.262  4592  9867 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
05-19 12:12:00.262  4592  9867 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
05-19 12:12:00.262  4592  9867 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
05-19 12:12:00.262  4592  9867 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
05-19 12:12:00.262  4592  9867 E         : 	... 24 more
05-19 12:12:00.262  4592  9867 E         : 
,05-19 12:12:00.262  5067  5067 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
05-19 12:12:00.262  5067  5067 D PdnController: isSuspended [false] networktype [1]
05-19 12:12:00.262  3510  3530 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:00.262  5067  5067 D PdnController: isPdnUp  [false] networktype [1]
05-19 12:12:00.262  5067  5067 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [false] 
,05-19 12:12:00.272  4288  5440 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-19 12:12:00.272  4288  5440 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-19 12:12:00.272  3510  3594 D TelephonyManager: getDataEnabled: retVal=true
,05-19 12:12:00.272  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:00.272  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:00.272  3510  3857 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:00.272  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:00.272  3510  3857 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
05-19 12:12:00.272  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-19 12:12:00.282  5067  5141 I CellLocationSupport: Block to update PANI information in non VoWIFI
05-19 12:12:00.282  5067  5141 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,05-19 12:12:00.282  3510  4040 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:00.282  5444  5444 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@4a0cc29 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 12:12:00.282  5067  5141 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
05-19 12:12:00.282  5067  5141 D PdnController: isPdnUp  [false] networktype [0]
05-19 12:12:00.282  5067  5141 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,05-19 12:12:00.282  3510  3530 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:00.282  6976  6976 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1060/IIllllIIlIIllIIIIlll)] WiFi network Connected : false
05-19 12:12:00.282  5067  5141 D RegistrationManager: handleMessage(): 5
,05-19 12:12:00.292  4437  4437 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,05-19 12:12:00.292  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.292  3510  4040 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:00.292  5067  5141 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
05-19 12:12:00.292  5067  5141 D PdnController: isPdnUp  [false] networktype [11]
05-19 12:12:00.292  5067  5141 D RegistrationManager: setEPDGIPSecConnected [false]
05-19 12:12:00.292  5067  5141 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [false] IPAddresses [[]] DNSAddresses [[]] 
05-19 12:12:00.292  5067  5141 D RegistrationManager: isEPDGAvailable [false]
05-19 12:12:00.292  5067  5141 D CoreController: setState [DEREGISTERED]
,05-19 12:12:00.302  9666  9666 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,05-19 12:12:00.302  3510  4313 I ActivityManager: Killing 9051:com.samsung.android.themestore/u0a68 (adj 15): DHA:empty #33
,05-19 12:12:00.312  9666  9666 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,05-19 12:12:00.322  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{5a5fa65: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.332  3510  4983 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3258f00 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{818aca3 7218:com.google.android.apps.maps/u0a125}
,05-19 12:12:00.332  9763  9763 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,05-19 12:12:00.332  9666  9666 D BluetoothAdapter: STATE_ON
,05-19 12:12:00.342  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 12:12:00.342  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:12:00.342  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:12:00.342  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:12:00.342  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:12:00.342  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-19 12:12:00.342  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-19 12:12:00.342  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-19 12:12:00.342  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-19 12:12:00.342  3510  3975 I ActivityManager: Killing 9097:com.samsung.android.scloud:contentsync/5009 (adj 15): DHA:empty #33
,05-19 12:12:00.342  9666  9666 D BluetoothAdapter: STATE_ON
,05-19 12:12:00.352  9666  9666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-19 12:12:00.352  3510  3854 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 12:12:00.352  3510  3854 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 12:12:00.352  3510  3854 D WifiService: setWifiEnabled: false pid=9666, uid=10078
,05-19 12:12:00.362  3510  3860 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,05-19 12:12:00.362  4126  4126 I wpa_supplicant: Blacklist: Clear (all) 
05-19 12:12:00.362  4126  4126 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,05-19 12:12:00.362  7218  7380 I SQLiteDatabase: can't enable WAL for memory databases.
,05-19 12:12:00.372  5067  5141 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-19 12:12:00.372  5067  5141 D RegistrationManager: getNetworkType [0]
05-19 12:12:00.372  5067  5141 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [false] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
05-19 12:12:00.372  5067  5141 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-19 12:12:00.372  5067  5141 D CoreStackAdaptor2: ipList =  Null
05-19 12:12:00.372  5067  5141 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
05-19 12:12:00.372  5067  5141 D RegistrationManager: isPreconditionProperToGoOn
05-19 12:12:00.372  5067  5141 D RegistrationManager: isDeviceShutdown [false]
05-19 12:12:00.372  5067  5141 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
05-19 12:12:00.372  5067  5141 D RegistrationManager: isDmVoLTEUpdated [false]
05-19 12:12:00.372  5067  5141 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
05-19 12:12:00.372  5067  5141 D RegistrationManager: tryRegister : Not all preconditions are met!
,05-19 12:12:00.372  9763  9817 D HeadsetService: registerMessageListener
,05-19 12:12:00.372  9763  9817 D HeadsetService: registerMessageListener
05-19 12:12:00.372  7218  7380 I SQLiteDatabase: can't enable WAL for memory databases.
05-19 12:12:00.372  9763  9802 D HeadsetStateMachine: Disconnected process message: 70, size: 0
05-19 12:12:00.372  9763  9802 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@6f9f50c
05-19 12:12:00.372  9851  9851 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:00.372  3510  3510 I Telecom : BluetoothManager : register MessageListener
,05-19 12:12:00.372  3510  3510 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,05-19 12:12:00.372  4288  4605 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@5cdb270, selection=nullselectionArgs=null, sort=name ASC
05-19 12:12:00.372  9851  9851 D RelationGraph: garbageCollect()
05-19 12:12:00.372  3510  4313 D ActivityManager: cleanUpApplicationRecord -- 9051
,05-19 12:12:00.382  3510  4313 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themestore, Auto Run ON
,05-19 12:12:00.382  3510  3854 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-19 12:12:00.382  3510  3863 D WifiStateMachine: setFccChannel: channel = 0
05-19 12:12:00.382  3510  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-19 12:12:00.382  3510  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-19 12:12:00.392  9851  9851 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package com.sec.android.provider.badge
,05-19 12:12:00.392  9763  9871 D BluetoothSocket: bindListen(): myUserId = 0
05-19 12:12:00.392  9763  9871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 12:12:00.392  9763  9763 D BluetoothSocket: bindListen(): myUserId = 0
05-19 12:12:00.392  9763  9763 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-19 12:12:00.392  3510  3530 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 12:12:00.392  9851  9851 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:00.392  9851  9851 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:00.392  4288  4605 D TelephonyProvider: query: match = 5
05-19 12:12:00.392  4288  4605 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
,05-19 12:12:00.392  4288  4605 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,05-19 12:12:00.402  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:12:00.402  4288  4288 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-19 12:12:00.402  9851  9851 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:00.412  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b7a8beb u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:12:00.412  9851  9851 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
05-19 12:12:00.412  3510  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-19 12:12:00.412  3510  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-19 12:12:00.422  3510  4409 D ActivityManager: cleanUpApplicationRecord -- 9097
,05-19 12:12:00.422  3510  4409 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,05-19 12:12:00.422  9851  9851 D BadgeProvider: onCreate
,05-19 12:12:00.422  9851  9851 D BadgeProvider: DatabaseHelper
,05-19 12:12:00.422  4659  9873 D MdnsClient: Multicast lock held. Releasing
,05-19 12:12:00.432  3158  3618 D Netd    : Iface p2p0 link up
,05-19 12:12:00.432  3510  3601 D Tethering: interfaceLinkStateChanged p2p0, true
05-19 12:12:00.432  3510  3601 D Tethering: interfaceStatusChanged p2p0, true
,05-19 12:12:00.432  5067  5077 D PdnController: Interface Changed p2p0 link up
,05-19 12:12:00.432  3510  3510 D Tethering: Tethering got CONNECTIVITY_ACTION
,05-19 12:12:00.432  3510  3510 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.432  3510  3510 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
05-19 12:12:00.432  3510  3510 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.432  3510  3510 I CLocInfoService: CLoinfo wifi false
,05-19 12:12:00.432  3510  4235 W SLocation: No Active Data Connection
,05-19 12:12:00.432  3510  3510 V MARsPolicyManager: DataConnection: false
05-19 12:12:00.432  3510  3510 I WifiTrafficPoller: evaluateTrafficStatsPolling
05-19 12:12:00.432  3510  4235 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.432  3510  3510 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-19 12:12:00.432  3510  3510 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-19 12:12:00.432  3510  3510 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
05-19 12:12:00.432  3510  4236 V AlarmManager:  remove PendingIntent] PendingIntent{22c613b: PendingIntentRecord{1279058 android broadcastIntent}}
05-19 12:12:00.432  3510  3510 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-19 12:12:00.432  3510  3867 I WifiHs20Service: Message received 5007
05-19 12:12:00.432  3510  3609 D Tethering: MasterInitialState.processMessage what=3
,05-19 12:12:00.432  3510  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-19 12:12:00.442  4288  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-19 12:12:00.442  4288  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-19 12:12:00.442  3510  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-19 12:12:00.442  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:12:00.442  3942  3942 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,05-19 12:12:00.442  3942  3942 I HotspotTile: Provider is not defined returning false
,05-19 12:12:00.442  3942  3942 D HotspotTile: onReceive : 0, 0
,05-19 12:12:00.442  3942  3942 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-19 12:12:00.442  9666  9666 D BluetoothAdapter: STATE_ON
,05-19 12:12:00.452  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 12:12:00.452  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:12:00.452  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:12:00.452  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
05-19 12:12:00.452  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:12:00.452  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-19 12:12:00.452  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-19 12:12:00.452  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-19 12:12:00.452  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-19 12:12:00.452  3510  3860 D WifiBigDataLog: init : 
,05-19 12:12:00.452  9763  9817 D A2dpStateMachine: getConnectedDevices : size=0
,05-19 12:12:00.452  3510  3510 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-19 12:12:00.452  3510  3510 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-19 12:12:00.452  3510  3867 I WifiHs20Service: Message received 5011
05-19 12:12:00.452  3510  3510 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
,05-19 12:12:00.452  3510  3510 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-19 12:12:00.452  3510  3510 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
05-19 12:12:00.452  3510  9874 I ApplicationPolicy: updateDataUsageMap
05-19 12:12:00.452  3510  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
05-19 12:12:00.452  3510  3594 E GpsLocationProvider: No APN found to select.
05-19 12:12:00.452  4163  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=84]
05-19 12:12:00.452  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=android}]
05-19 12:12:00.452  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 12:12:00.452  9851  9851 D InjectionManager: InjectionManager
05-19 12:12:00.452  9851  9851 D InjectionManager: fillFeatureStoreMap com.sec.android.provider.badge
,05-19 12:12:00.452  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 12:12:00.452  4163  4163 I PeopleDataManager: removeNotification
05-19 12:12:00.452  4163  4163 I NotificationParser: getNotiType:android,null
05-19 12:12:00.452  4163  4163 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 12:12:00.452  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-19 12:12:00.462  4163  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
,05-19 12:12:00.462  9666  9666 D BluetoothAdapter: STATE_ON
05-19 12:12:00.462  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
05-19 12:12:00.462  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 12:12:00.462  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 12:12:00.462  4163  4163 I PeopleDataManager: removeNotification
05-19 12:12:00.462  4163  4163 I NotificationParser: getNotiType:android,null
,05-19 12:12:00.462  4163  4163 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 12:12:00.462  4163  4163 D PeopleDataManager: removeNotiInfo =null
05-19 12:12:00.462  9851  9851 I InjectionManager: Constructor com.sec.android.provider.badge, Feature store :{}
,05-19 12:12:00.462  9851  9851 I InjectionManager: featureStore :{}
05-19 12:12:00.472  3510  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-19 12:12:00.472  4288  5440 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-19 12:12:00.472  4288  5440 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-19 12:12:00.472  3510  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-19 12:12:00.482  4126  4126 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,05-19 12:12:00.482  4126  4126 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,05-19 12:12:00.482  3158  3618 D Netd    : Iface wlan0 link up
,05-19 12:12:00.482  3510  3601 D Tethering: interfaceLinkStateChanged wlan0, true
,05-19 12:12:00.482  3510  3601 D Tethering: interfaceStatusChanged wlan0, true
,05-19 12:12:00.482  5067  5360 D PdnController: Interface Changed wlan0 link up
,05-19 12:12:00.532  3510  3594 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,05-19 12:12:00.532  9763  9871 D BluetoothSdpJni: sdpCreateSapsRecordNative:
05-19 12:12:00.532  9763  9871 D BluetoothSdpJni: SDP Create record success - handle: 0
,05-19 12:12:00.542  9763  9763 D BluetoothSocket: bindListen(): myUserId = 0
05-19 12:12:00.542  9763  9763 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-19 12:12:00.542  9666  9666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-19 12:12:00.542  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{c915d48: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:00.542  9763  9763 D ObexServerSockets: Succeed to create listening sockets 
05-19 12:12:00.542  9763  9763 D ObexServerSockets: startAccept()
,05-19 12:12:00.542  9763  9875 D ObexServerSockets: Accepting socket connection for masId0
,05-19 12:12:00.542  9763  9876 D ObexServerSockets: Accepting socket connection for masId0
,05-19 12:12:00.552  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:12:00.562  9763  9763 D BluetoothMapMasInstance: set MAP SDP message type : 1
,05-19 12:12:00.562  9763  9763 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
05-19 12:12:00.562  9763  9763 D BluetoothSdpJni: SDP Create record success - handle: 1
,05-19 12:12:00.562  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{200d7e1 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{332c515 6617:com.enhance.gameservice/u0a111}
,05-19 12:12:00.572  3942  3942 D DateView: received broadcast android.intent.action.TIME_TICK
05-19 12:12:00.572  3510  4518 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3510  pkgName : BADGE_UPDATE@CPU_MIN@1
,05-19 12:12:00.582  4126  4126 I wpa_supplicant: Blacklist: Clear (all) 
05-19 12:12:00.582  4126  4126 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,05-19 12:12:00.582  9851  9864 D BaseReflect: null getOwnClass TEST
05-19 12:12:00.582  9851  9864 D MethodReflector: android.content.ContentResolver getClass TEST
05-19 12:12:00.582  9851  9864 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
05-19 12:12:00.582  9851  9864 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,05-19 12:12:00.582  4151  4151 D CatchNotificationsService: Update badge
,05-19 12:12:00.582  5913  5913 D BadgeManager: onChange
05-19 12:12:00.582  4300  4300 D Launcher.Model: reloadBadges entered.
,05-19 12:12:00.582  9851  9864 D MethodReflector: notifyChange is called
,05-19 12:12:00.592  4300  4300 D Launcher.Model: reloadBadges entered.
,05-19 12:12:00.592  9851  9864 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
05-19 12:12:00.592  9851  9864 D BadgeProvider: sendNotify, [notify] : null
05-19 12:12:00.592  5913  5913 D BadgeManager: onChange
,05-19 12:12:00.592  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{528a906: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.592  3510  6241 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:00.602  9851  9864 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
05-19 12:12:00.602  9851  9864 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
05-19 12:12:00.602  9851  9864 D BadgeProvider: update, [uri.query] : null
05-19 12:12:00.602  9851  9864 D BadgeProvider: update, [BadgeCount] : badgecount=0
05-19 12:12:00.602  9851  9864 D BadgeProvider: update, [UpdateCount] : 1
,05-19 12:12:00.632  3510  3598 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:00.642  3158  3618 D Netd    : Iface wlan0 link up
,05-19 12:12:00.642  3158  3618 D Netd    : Iface wlan0 link up
,05-19 12:12:00.642  3510  3601 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 12:12:00.642  3510  3601 D Tethering: interfaceStatusChanged wlan0, true
05-19 12:12:00.642  5067  5079 D PdnController: Interface Changed wlan0 link up
,05-19 12:12:00.642  3510  3601 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 12:12:00.642  3510  3601 D Tethering: interfaceStatusChanged wlan0, true
,05-19 12:12:00.642  5067  5358 D PdnController: Interface Changed wlan0 link up
,05-19 12:12:00.642  3158  3618 D Netd    : Iface p2p0 link down
,05-19 12:12:00.652  3510  3601 D Tethering: interfaceLinkStateChanged p2p0, false
05-19 12:12:00.652  3510  3601 D Tethering: interfaceStatusChanged p2p0, false
,05-19 12:12:00.652  5067  5077 D PdnController: Interface Changed p2p0 link down
,05-19 12:12:00.652  3510  3598 I ActivityManager: Start proc 9877:com.google.android.talk/u0a117 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,05-19 12:12:00.662  9877  9877 E Zygote  : v2
05-19 12:12:00.662  9877  9877 I libpersona: KNOX_SDCARD checking this for 10117
05-19 12:12:00.662  9877  9877 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:00.662  9877  9877 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:00.662  9877  9877 E Zygote  : accessInfo : 0
,05-19 12:12:00.662  9877  9877 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,05-19 12:12:00.682  4722  4722 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,05-19 12:12:00.682  4722  4722 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,05-19 12:12:00.682  4722  4722 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,05-19 12:12:00.682  4722  4722 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,05-19 12:12:00.682  4722  4722 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0A076401BE06F4E826A7580C814FC1B1906151CE3B0473FD800199023346D7A029DDB25A1F2C9F2C6ACCAE9F5F7FFF36C]}
05-19 12:12:00.682  4722  4722 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,05-19 12:12:00.682  9851  9864 D BadgeProvider: query, [selection] : null
,05-19 12:12:00.692  9851  9862 D BadgeProvider: query, [selection] : null
,05-19 12:12:00.692  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{673fbc7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:00.692  3510  6241 D SSRM:n  : SIOP:: AP = 320, PST = 317 (W:14), CP = 262, CUR = 84, LCD = 30
,05-19 12:12:00.692  4300  4373 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
05-19 12:12:00.692  4300  4373 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
05-19 12:12:00.692  4300  4373 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-19 12:12:00.692  4300  4373 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
05-19 12:12:00.692  4300  4373 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-19 12:12:00.692  4300  4373 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
05-19 12:12:00.692  4300  4373 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
05-19 12:12:00.692  4300  4373 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,05-19 12:12:00.702  9877  9877 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:00.702  9877  9877 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:00.702  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{90305f4: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.712  3510  4518 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d2111d u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4164f92 9877:com.google.android.talk/u0a117}
,05-19 12:12:00.712  4151  4151 D CatchNotificationsService: Update badge
,05-19 12:12:00.712  9877  9877 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:00.712  9877  9877 D RelationGraph: garbageCollect()
,05-19 12:12:00.712  9877  9877 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-19 12:12:00.722  3510  4312 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:12:00.722  9877  9877 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:00.722  9877  9877 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:00.722  9851  9890 D BadgeProvider: query, [selection] : null
,05-19 12:12:00.722  9877  9877 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:00.722  9851  9889 D BadgeProvider: query, [selection] : null
,05-19 12:12:00.722  3510  6241 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:00.732  9763  9892 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-19 12:12:00.732  9763  9892 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-19 12:12:00.732  9877  9877 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,05-19 12:12:00.732  9893  9893 E Zygote  : v2
05-19 12:12:00.732  9893  9893 I libpersona: KNOX_SDCARD checking this for 10052
05-19 12:12:00.732  9893  9893 E Zygote  : isSdpEnabledProcess - SDP enabled
05-19 12:12:00.732  9893  9893 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:00.732  9893  9893 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:00.732  9893  9893 E Zygote  : accessInfo : 64
05-19 12:12:00.732  9893  9893 E Zygote  : isSdpEnabledProcess - SDP enabled
05-19 12:12:00.732  9893  9893 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
,05-19 12:12:00.732  9893  9893 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,05-19 12:12:00.732  3510  4427 I ActivityManager: Start proc 9893:com.samsung.android.email.provider:service/u0a52 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
,05-19 12:12:00.742  4300  4373 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
05-19 12:12:00.742  4300  4373 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
05-19 12:12:00.742  4300  4373 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-19 12:12:00.742  4300  4373 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
05-19 12:12:00.742  4300  4373 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-19 12:12:00.742  4300  4373 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
05-19 12:12:00.742  4300  4373 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
05-19 12:12:00.742  4300  4373 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,05-19 12:12:00.742  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{6aa8d63: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.752  9877  9877 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-19 12:12:00.752  9893  9893 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:00.752  9893  9893 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:00.752  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{b448d60: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.762  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{6c5d2de: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.762  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{e2e9cbf: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.762  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{8551f8c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.762  9893  9893 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:00.762  9893  9893 D RelationGraph: garbageCollect()
05-19 12:12:00.762  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{e2346d5: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.762  9893  9893 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,05-19 12:12:00.762  3510  3530 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:12:00.762  9893  9893 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:00.762  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{2583eea: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.762  9893  9893 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:00.772  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{5ba45db: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.772  9893  9893 I InjectionManager: Inside getClassLibPath caller 
05-19 12:12:00.772  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{3faa878: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.772  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{5de7b51: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.782  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{af35fb6: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.782  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{d8d64b7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.782  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{66dd424: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.782  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{b3e7b8d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.782  9893  9893 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,05-19 12:12:00.782  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{f4dc142: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.782  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{99553: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.792  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{c60e90: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.792  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{244389: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.792  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{faaf8e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.792  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{20e33af: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.792  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{c2583bc: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.792  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{9848f45: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.802  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{576369a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.802  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{bf12266: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.812  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{f0ae9a7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.812  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{9008e54: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.812  9893  9893 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,05-19 12:12:00.812  9893  9893 I QBNRClientHelper: init SyncClientHelper : Email
,05-19 12:12:00.812  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{99261fd: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.822  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{3dcfef2: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.822  9877  9877 I Babel_telephony: TeleModule.onApplicationCreate
,05-19 12:12:00.822  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{bf27943: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.822  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{4023bc0: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.832  9877  9914 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
05-19 12:12:00.832  9877  9914 I Babel_SMS: MmsConfig.loadMmsSettings
,05-19 12:12:00.832  9877  9914 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
05-19 12:12:00.832  9877  9914 I Babel_SMS: MmsConfig.loadFromDatabase
,05-19 12:12:00.842  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{9a820f9: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.842  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{d39669f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.852  9877  9877 I Babel_Crash: Startup - clean
,05-19 12:12:00.862  3510  4312 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10117
05-19 12:12:00.862  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{caf53ec: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:00.862  9877  9914 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
05-19 12:12:00.862  9877  9914 I Babel_SMS: MmsConfig.loadFromResources
05-19 12:12:00.862  9877  9914 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
05-19 12:12:00.862  9877  9914 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,05-19 12:12:00.872  3510  3854 D RCPManagerService: exchangeData() failure , invalid userId
,05-19 12:12:00.872  9893  9893 D InjectionManager: InjectionManager
05-19 12:12:00.872  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{6c0d3b5: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:00.872  9893  9893 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,05-19 12:12:00.882  9893  9893 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
05-19 12:12:00.882  9893  9893 I InjectionManager: featureStore :{}
,05-19 12:12:00.882  3510  3529 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10117
,05-19 12:12:00.882  3510  3975 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10117
,05-19 12:12:00.882  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{3997a4a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.882  3510  4312 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10117
,05-19 12:12:00.882  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{ad7cdbb: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.892  3510  4040 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10117
,05-19 12:12:00.892  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{833c2d8: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.892  9666  9751 D BluetoothAdapter: STATE_ON
,05-19 12:12:00.902  9877  9877 I Babel_Prime: startMemoryMonitor
,05-19 12:12:00.902  9877  9877 I Babel_Prime: isMemoryEnabled=false
05-19 12:12:00.902  9877  9877 I Babel_Prime: isTimerEnabled=true
,05-19 12:12:00.902  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{8e3484: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.902  9666  9751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 12:12:00.902  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:12:00.902  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:12:00.902  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
05-19 12:12:00.902  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:12:00.902  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-19 12:12:00.902  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-19 12:12:00.902  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-19 12:12:00.902  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-19 12:12:00.902  9666  9751 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 12:12:00.902  9666  9729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:12:00.902  3510  4059 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 12:12:00.902  3510  4059 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 12:12:00.902  3510  4059 D WifiService: setWifiEnabled: true pid=9666, uid=10078
,05-19 12:12:00.912  3510  4059 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:12:00.912  3510  4059 W WifiService: Failed getting userId using ActivityManagerNative
05-19 12:12:00.912  3510  4059 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:12:00.912  3510  4059 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:12:00.912  3510  4059 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 12:12:00.912  3510  4059 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 12:12:00.912  3510  4059 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 12:12:00.912  3510  4059 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-19 12:12:00.912  3510  4059 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 12:12:00.912  3510  4059 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-19 12:12:00.912  3510  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-19 12:12:00.912  9877  9877 D InjectionManager: InjectionManager
05-19 12:12:00.912  9877  9877 D InjectionManager: fillFeatureStoreMap com.google.android.talk
,05-19 12:12:00.912  3510  3863 D WifiStateMachine: setFccChannel: channel = 0
05-19 12:12:00.912  3510  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-19 12:12:00.912  3510  3863 D SecContentProvider: insert(), uri = 2
05-19 12:12:00.912  3510  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-19 12:12:00.912  3510  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-19 12:12:00.912  3510  3860 D WifiBigDataLog: init : 
,05-19 12:12:00.922  9877  9877 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
05-19 12:12:00.922  9877  9877 I InjectionManager: featureStore :{}
,05-19 12:12:00.922  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{2a4c46d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.932  3510  4312 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e943933 9666:com.rockwellautomation.thalitest/u0a78}
,05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:00.932  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:00.932  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:00.942  3510  3530 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{38ffe8f 3510:system/1000}
,05-19 12:12:00.942  3510  3598 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:00.952  3510  3510 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d14e56 4659:com.google.android.gms/u0a21}
,05-19 12:12:00.962  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{7cf358f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.962  9877  9877 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,05-19 12:12:00.962  3510  4257 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d14e56 4659:com.google.android.gms/u0a21}
,05-19 12:12:00.962  9877  9877 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,05-19 12:12:00.962  4659  4659 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,05-19 12:12:00.962  4659  5658 I iu.UploadsManager: num queued entries: 0
,05-19 12:12:00.962  9877  9877 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:00.962  4659  5658 I iu.UploadsManager: num updated entries: 0
,05-19 12:12:00.962  9877  9877 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:00.962  4659  5658 I iu.SyncManager: NEXT; no task
,05-19 12:12:00.972  3510  4257 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d14e56 4659:com.google.android.gms/u0a21}
,05-19 12:12:00.972  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{125901c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.972  3510  4257 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{feb16e 4341:com.google.android.gms.persistent/u0a21}
05-19 12:12:00.972  9877  9877 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,05-19 12:12:00.982  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{8f1425: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:00.992  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ead09fa u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{332c515 6617:com.enhance.gameservice/u0a111}
,05-19 12:12:01.002  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a139bab u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e943933 9666:com.rockwellautomation.thalitest/u0a78}
,05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.002  3510  4257 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:01.002  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{5099208: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.012  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9c1cda1 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:12:01.012  3510  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fb1cbc6 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:12:01.022  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{bee4787: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.022  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{7a9c6b4: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.022  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{10ca2dd: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.022  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{feede52: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.022  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{5ddd523: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.022  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{2769a20: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.032  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{4358fd9: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.032  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{7788d9e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.032  9877  9877 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,05-19 12:12:01.032  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{faea07f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.032  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{37b384c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.032  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{d665095: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.032  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{95be5aa: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.032  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{796c59b: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.042  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{c498d38: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.042  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{5a86111: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.042  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{a6ab276: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.042  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{f122077: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.042  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{3a644e4: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.042  9877  9877 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,05-19 12:12:01.042  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{320fd4d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.042  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{f0d2149: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.042  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{319a4e: PendingIntentRecord{876a76f com.google.android.talk startService}}
,05-19 12:12:01.052  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{634c7c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.052  9877  9877 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,05-19 12:12:01.052  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{f7d8905: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.052  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{7110d5a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.052  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{1f04b8b: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.052  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{2d6b468: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.052  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{d2b081: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.052  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{42a526: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.052  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{c161567: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.052  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{496af14: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.062  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{af8d3bd: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.062  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{da3edb2: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.062  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{ae4a103: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.062  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{7b9a880: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.062  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{e63eeb9: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.062  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{f5f32fe: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.062  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{b864a5f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.062  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{750ccac: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.062  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{4cbbd75: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.062  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{bf7810a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.062  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{96f2d7b: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.062  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{c540798: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.062  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{1a7bbf1: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.072  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{d14a3d6: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.072  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{9392657: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.072  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{54e0544: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.072  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{e6b262d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.072  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{d0f2762: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.072  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{53fd0f3: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.072  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{cc831b0: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.072  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{e80f829: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.072  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{13c57ae: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.072  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{7fc894f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.072  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{a76b8dc: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.082  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{707ede5: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:01.182  3158  3618 D Netd    : Iface wlan0 link down
,05-19 12:12:01.182  3510  3601 D Tethering: interfaceLinkStateChanged wlan0, false
05-19 12:12:01.182  3510  3601 D Tethering: interfaceStatusChanged wlan0, false
,05-19 12:12:01.182  5067  5358 D PdnController: Interface Changed wlan0 link down
05-19 12:12:01.182  5067  5358 D PdnController: Removed Interface [wlan0] For Network [1]
,05-19 12:12:01.182  3510  3601 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:01.182  5067  5358 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
05-19 12:12:01.182  5067  5358 D PdnController: isSuspended [false] networktype [1]
,05-19 12:12:01.182  3510  3601 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.182  5067  5358 D PdnController: isPdnUp  [false] networktype [1]
05-19 12:12:01.182  5067  5358 D PdnController: Ignore Notifying Same Result to LocalIP Registrants!
,05-19 12:12:01.222  4126  4126 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,05-19 12:12:01.242  3510  3598 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:01.322  3510  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,05-19 12:12:01.322  3510  3510 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,05-19 12:12:01.322  4163  4173 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
05-19 12:12:01.322  3510  3510 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
05-19 12:12:01.322  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
05-19 12:12:01.322  3510  3510 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
05-19 12:12:01.322  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
,05-19 12:12:01.322  4163  7409 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041473,extra=Bundle[mParcelledData.dataSize=84]
,05-19 12:12:01.322  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 12:12:01.322  4163  4163 I PeopleDataManager: removeNotification
05-19 12:12:01.322  4163  4163 I NotificationParser: getNotiType:android,null
05-19 12:12:01.322  4163  4163 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 12:12:01.322  4163  4163 D PeopleDataManager: removeNotiInfo =null
05-19 12:12:01.322  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041473, samsung.notification.type=normal, samsung.people.package_name=android}]
,05-19 12:12:01.322  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 12:12:01.322  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 12:12:01.322  4163  4163 I PeopleDataManager: removeNotification
05-19 12:12:01.322  4163  4163 I NotificationParser: getNotiType:android,null
,05-19 12:12:01.322  4163  4163 D PeopleDataManager: removeNotiInfo: id =17041473,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 12:12:01.322  4163  4163 D PeopleDataManager: removeNotiInfo =null
05-19 12:12:01.322  3510  3510 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-19 12:12:01.322  3510  3864 D HS20StateMachine: WIFI_STATE_DISABLED
05-19 12:12:01.322  3510  3864 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
05-19 12:12:01.322  3510  3864 D HS20StateMachine: enter : DisablingState
05-19 12:12:01.332  3510  3866 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
05-19 12:12:01.332  3510  3510 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,05-19 12:12:01.332  3510  3864 D HS20StateMachine: enter : DisabledState
05-19 12:12:01.332  3510  3867 I WifiHs20Service: Message received 5011
,05-19 12:12:01.332  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:12:01.332  3510  3510 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,05-19 12:12:01.332  3510  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-19 12:12:01.332  3942  3942 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,05-19 12:12:01.332  3942  3942 I HotspotTile: Provider is not defined returning false
05-19 12:12:01.332  3942  3942 D HotspotTile: onReceive : 1, 0
,05-19 12:12:01.332  4288  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-19 12:12:01.332  4288  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-19 12:12:01.332  3510  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-19 12:12:01.342  4341  5137 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,05-19 12:12:01.342  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-19 12:12:01.342  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cfa40ba u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e943933 9666:com.rockwellautomation.thalitest/u0a78}
,05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.342  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:01.412  9666  9751 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 12:12:01.422  3510  4406 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 12:12:01.422  3510  4406 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 12:12:01.422  3510  4406 D WifiService: setWifiEnabled: true pid=9666, uid=10078
,05-19 12:12:01.422  3510  4406 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:12:01.422  3510  4406 W WifiService: Failed getting userId using ActivityManagerNative
05-19 12:12:01.422  3510  4406 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:12:01.422  3510  4406 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:12:01.422  3510  4406 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 12:12:01.422  3510  4406 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 12:12:01.422  3510  4406 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 12:12:01.422  3510  4406 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-19 12:12:01.422  3510  4406 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 12:12:01.422  3510  4406 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-19 12:12:01.422  3510  3863 D WifiStateMachine: setFccChannel: channel = 0
05-19 12:12:01.422  3510  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-19 12:12:01.422  3510  3863 E WifiController: illegal state found both WifiController and WifiStateMachine
05-19 12:12:01.422  3510  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-19 12:12:01.522  3510  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,05-19 12:12:01.522  3510  3860 E WifiStateMachine: Error! unhandled message{ when=-3m27s95ms what=131156 target=com.android.internal.util.StateMachine$SmHandler }
05-19 12:12:01.522  3510  3860 E WifiHW  : ##################### set firmware type 0 #####################
,05-19 12:12:01.522  3158  3625 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,05-19 12:12:01.522  3158  3625 I WifiHW  : module is semco
05-19 12:12:01.522  3158  3625 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
05-19 12:12:01.522  3158  3625 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
,05-19 12:12:01.522  3158  3625 E WifiHW  : TEMP_FAILURE_RETRY complete
05-19 12:12:01.522  3158  3625 D SoftapController: Softap fwReload - Ok
,05-19 12:12:01.532  3158  3625 D CommandListener: Setting iface cfg
05-19 12:12:01.532  3158  3625 D CommandListener: Trying to bring down wlan0
05-19 12:12:01.532  3158  3625 D CommandListener: Clearing all IP addresses on wlan0
,05-19 12:12:01.532  3510  3860 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,05-19 12:12:01.532  3510  3860 D wifi    : Can not initialize the vendor function pointer table
05-19 12:12:01.532  3510  3860 E WifiNative-HAL: Could not start hal
05-19 12:12:01.532  3510  3860 E WifiStateMachine: Failed to start HAL
05-19 12:12:01.532  3510  3860 E WifiHW  : supplicant_name : p2p_supplicant
,05-19 12:12:01.532  3510  3594 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
,05-19 12:12:01.532  3510  3594 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-19 12:12:01.532  3510  3594 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
05-19 12:12:01.532  3510  3594 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,05-19 12:12:01.542  3510  3598 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:01.562  3510  3598 I ActivityManager: Start proc 9931:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
05-19 12:12:01.562  9931  9931 E Zygote  : v2
05-19 12:12:01.562  9931  9931 I libpersona: KNOX_SDCARD checking this for 1000
05-19 12:12:01.562  9931  9931 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:01.562  9931  9931 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:01.562  9931  9931 E Zygote  : accessInfo : 0
,05-19 12:12:01.602  9931  9931 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:01.602  9931  9931 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:01.612  3510  3529 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{200d7e1 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{226b6b 9931:com.sec.android.diagmonagent/1000}
,05-19 12:12:01.622  9931  9931 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:01.622  9931  9931 D RelationGraph: garbageCollect()
,05-19 12:12:01.622  9931  9931 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package com.sec.android.diagmonagent
,05-19 12:12:01.622  3510  4427 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:12:01.622  9931  9931 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:01.632  9931  9931 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:01.632  9931  9931 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:01.632  3510  3860 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,05-19 12:12:01.632  3510  3510 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,05-19 12:12:01.632  3510  3510 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-19 12:12:01.632  3510  3867 I WifiHs20Service: Message received 5011
05-19 12:12:01.632  9931  9931 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,05-19 12:12:01.642  3510  3510 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,05-19 12:12:01.642  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 12:12:01.642  3942  3942 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-19 12:12:01.642  3942  3942 I HotspotTile: Provider is not defined returning false
,05-19 12:12:01.642  3942  3942 D HotspotTile: onReceive : 2, 0
,05-19 12:12:01.642  3510  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-19 12:12:01.642  4288  4299 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-19 12:12:01.642  4288  4299 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-19 12:12:01.642  3510  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-19 12:12:01.652  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-19 12:12:01.652  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2486c8 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e943933 9666:com.rockwellautomation.thalitest/u0a78}
,05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:01.652  3510  4427 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:01.652  9931  9931 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,05-19 12:12:01.702  9930  9930 I FIPS_bssl: FIPS approved mode (1) | 9930 | /system/bin/wpa_supplicant
,05-19 12:12:01.702  9930  9930 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
05-19 12:12:01.702  9930  9930 I wpa_supplicant: Successfully initialized wpa_supplicant
05-19 12:12:01.702  9930  9930 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
,05-19 12:12:01.702  9930  9930 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,05-19 12:12:01.722  9930  9930 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,05-19 12:12:01.722  3020  3020 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9930
05-19 12:12:01.722  3020  3020 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
05-19 12:12:01.722  9930  9930 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
05-19 12:12:01.722  9930  9930 I wpa_supplicant: ssSupport state is = 1
05-19 12:12:01.722  9930  9930 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
05-19 12:12:01.722  9930  9930 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,05-19 12:12:01.722  3020  3020 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9930
05-19 12:12:01.722  3020  3020 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,05-19 12:12:01.732  9930  9930 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,05-19 12:12:01.742  9931  9931 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,05-19 12:12:01.742  9931  9931 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
05-19 12:12:01.742  9931  9931 D InjectionManager: InjectionManager
05-19 12:12:01.742  9931  9931 D InjectionManager: fillFeatureStoreMap com.sec.android.diagmonagent
,05-19 12:12:01.752  9931  9931 I InjectionManager: Constructor com.sec.android.diagmonagent, Feature store :{}
05-19 12:12:01.752  9931  9931 I InjectionManager: featureStore :{}
,05-19 12:12:01.752  9931  9931 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-19 12:12:01.752  9931  9931 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-19 12:12:01.752  9931  9931 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
05-19 12:12:01.752  9931  9931 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-19 12:12:01.782  3510  4409 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:01.792  3510  4409 I ActivityManager: Start proc 9944:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
05-19 12:12:01.792  3510  4409 I ActivityManager: Killing 9110:com.osp.app.signin/u0a44 (adj 15): DHA:empty #33
05-19 12:12:01.802  9944  9944 E Zygote  : v2
05-19 12:12:01.802  9944  9944 I libpersona: KNOX_SDCARD checking this for 1000
05-19 12:12:01.802  9944  9944 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:01.802  9944  9944 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 12:12:01.802  9944  9944 E Zygote  : accessInfo : 0
,05-19 12:12:01.812  3510  4406 D ActivityManager: cleanUpApplicationRecord -- 9110
,05-19 12:12:01.812  3510  4406 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,05-19 12:12:01.812  9944  9944 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:01.812  9944  9944 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:01.822  3510  3854 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{200d7e1 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{64e8361 9944:com.sec.knox.switcher/1000}
,05-19 12:12:01.832  9944  9944 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 12:12:01.832  9944  9944 D RelationGraph: garbageCollect()
,05-19 12:12:01.832  9944  9944 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package com.sec.knox.switcher
,05-19 12:12:01.832  3510  4409 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:12:01.832  9944  9944 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:01.832  9944  9944 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:01.832  9944  9944 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:01.832  9944  9944 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,05-19 12:12:01.832  9944  9944 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
05-19 12:12:01.832  9944  9944 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,05-19 12:12:01.842  9944  9944 D InjectionManager: InjectionManager
05-19 12:12:01.842  9944  9944 D InjectionManager: fillFeatureStoreMap com.sec.knox.switcher
,05-19 12:12:01.842  9944  9944 I InjectionManager: Constructor com.sec.knox.switcher, Feature store :{}
05-19 12:12:01.842  9944  9944 I InjectionManager: featureStore :{}
05-19 12:12:01.842  9944  9944 I usagelog: received in receiver
05-19 12:12:01.842  9944  9944 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,05-19 12:12:01.842  9944  9944 I KnoxUsageLogPro: premStatus:2
,05-19 12:12:01.842  9944  9944 I KnoxUsageLogPro: isEulaShown : false
05-19 12:12:01.842  9944  9944 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-19 12:12:01.842  3510  4427 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:01.852  9956  9956 E Zygote  : v2
05-19 12:12:01.852  9956  9956 I libpersona: KNOX_SDCARD checking this for 10142
05-19 12:12:01.852  9956  9956 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:01.852  9956  9956 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:01.852  9956  9956 E Zygote  : accessInfo : 0
05-19 12:12:01.852  9956  9956 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,05-19 12:12:01.852  3510  4427 I ActivityManager: Start proc 9956:com.samsung.android.sm.policy/u0a142 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
,05-19 12:12:01.852  3510  4427 I ActivityManager: Killing 8245:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,05-19 12:12:01.862  9956  9956 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:01.862  9956  9956 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:01.872  3510  4518 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{200d7e1 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97bae86 9956:com.samsung.android.sm.policy/u0a142}
,05-19 12:12:01.872  9956  9956 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:01.872  9956  9956 D RelationGraph: garbageCollect()
,05-19 12:12:01.872  9956  9956 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package com.samsung.android.sm.policy
05-19 12:12:01.872  3510  4409 D ActivityManager: cleanUpApplicationRecord -- 8245
05-19 12:12:01.872  3510  4409 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,05-19 12:12:01.872  3510  4947 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:12:01.872  9956  9956 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:01.872  9956  9956 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:01.882  9956  9956 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:01.882  9956  9956 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm64
,05-19 12:12:01.892  9956  9956 D InjectionManager: InjectionManager
05-19 12:12:01.892  9956  9956 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.policy
,05-19 12:12:01.892  9956  9956 I InjectionManager: Constructor com.samsung.android.sm.policy, Feature store :{}
05-19 12:12:01.892  9956  9956 I InjectionManager: featureStore :{}
,05-19 12:12:01.892  3510  4312 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:01.892  9968  9968 E Zygote  : v2
05-19 12:12:01.892  9968  9968 I libpersona: KNOX_SDCARD checking this for 5005
05-19 12:12:01.892  9968  9968 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:01.892  9968  9968 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:01.892  9968  9968 E Zygote  : accessInfo : 0
05-19 12:12:01.892  9968  9968 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,05-19 12:12:01.902  3510  4312 I ActivityManager: Start proc 9968:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,05-19 12:12:01.902  3510  4312 I ActivityManager: Killing 8787:com.android.providers.calendar/u0a50 (adj 15): DHA:empty #33
,05-19 12:12:01.912  9968  9968 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:01.912  9968  9968 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:01.912  3510  4407 D ActivityManager: cleanUpApplicationRecord -- 8787
,05-19 12:12:01.912  3510  4407 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,05-19 12:12:01.922  9666  9751 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 12:12:01.922  3510  4518 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
05-19 12:12:01.922  3510  4518 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 12:12:01.922  3510  4518 D WifiService: setWifiEnabled: true pid=9666, uid=10078
,05-19 12:12:01.922  3510  4406 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{a7a5347 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5f4774 9968:com.samsung.android.app.FileShareClient/5005}
,05-19 12:12:01.922  3510  4518 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 12:12:01.922  3510  4518 W WifiService: Failed getting userId using ActivityManagerNative
05-19 12:12:01.922  3510  4518 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:12:01.922  3510  4518 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:12:01.922  3510  4518 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 12:12:01.922  3510  4518 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 12:12:01.922  3510  4518 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 12:12:01.922  3510  4518 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-19 12:12:01.932  3510  4518 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 12:12:01.932  3510  4518 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-19 12:12:01.932  3510  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-19 12:12:01.932  3510  3863 D WifiStateMachine: setFccChannel: channel = 0
05-19 12:12:01.932  3510  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-19 12:12:01.932  9968  9968 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:01.932  9968  9968 D RelationGraph: garbageCollect()
,05-19 12:12:01.932  9968  9968 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,05-19 12:12:01.932  3510  3530 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:12:01.932  9968  9968 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:01.932  9968  9968 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:01.942  9968  9968 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:01.942  9968  9968 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,05-19 12:12:01.942  9968  9968 D InjectionManager: InjectionManager
05-19 12:12:01.942  9968  9968 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
,05-19 12:12:01.942  9968  9968 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{}
05-19 12:12:01.942  9968  9968 I InjectionManager: featureStore :{}
,05-19 12:12:01.952  9968  9968 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-19 12:12:01.952  9968  9968 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,05-19 12:12:01.962  9968  9968 D FileShare-Client: Outbound.stopDelayTimer - 
,05-19 12:12:01.962  3510  4406 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:01.982  3510  4406 I ActivityManager: Start proc 9980:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
,05-19 12:12:01.982  9980  9980 E Zygote  : v2
05-19 12:12:01.982  9980  9980 I libpersona: KNOX_SDCARD checking this for 5005
05-19 12:12:01.982  9980  9980 I libpersona: KNOX_SDCARD not a persona
05-19 12:12:01.982  9980  9980 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 12:12:01.982  3510  4406 I ActivityManager: Killing 9149:com.google.android.apps.photos/u0a135 (adj 15): DHA:empty #33
,05-19 12:12:01.982  9980  9980 E Zygote  : accessInfo : 0
05-19 12:12:01.982  9980  9980 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
,05-19 12:12:02.002  9980  9980 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:02.002  9980  9980 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:02.002  3510  4518 D ActivityManager: cleanUpApplicationRecord -- 9149
,05-19 12:12:02.012  3510  4518 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,05-19 12:12:02.012  9930  9930 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
05-19 12:12:02.012  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,05-19 12:12:02.022  3510  3530 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{a7a5347 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{70ef49d 9980:com.samsung.android.app.FileShareServer/5005}
,05-19 12:12:02.022  9930  9930 I wpa_supplicant: Ctrl_iface: loading system cred
05-19 12:12:02.022  9930  9930 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-19 12:12:02.022  9980  9980 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:02.022  9980  9980 D RelationGraph: garbageCollect()
,05-19 12:12:02.022  9980  9980 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareServer/AllshareFileShareServer.apk / 1.0 running in com.samsung.android.app.FileShareServer rsrc of package com.samsung.android.app.FileShareServer
,05-19 12:12:02.032  3510  4406 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:12:02.032  9980  9980 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:02.032  9980  9980 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:02.032  9980  9980 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:02.032  9980  9980 D InjectionManager: InjectionManager
05-19 12:12:02.032  9980  9980 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareServer
,05-19 12:12:02.032  9980  9980 I InjectionManager: Constructor com.samsung.android.app.FileShareServer, Feature store :{}
05-19 12:12:02.032  9980  9980 I InjectionManager: featureStore :{}
,05-19 12:12:02.042  9980  9980 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-19 12:12:02.042  9980  9980 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
05-19 12:12:02.042  9980  9980 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-19 12:12:02.042  9930  9930 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-19 12:12:02.042  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9930
05-19 12:12:02.042  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-19 12:12:02.042  9930  9930 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-19 12:12:02.042  9930  9930 I wpa_supplicant: ssSupport state is = 1
,05-19 12:12:02.042  9930  9930 I wpa_supplicant: Blacklist: Clear (all) 
,05-19 12:12:02.042  9930  9930 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
05-19 12:12:02.042  9930  9930 I wpa_supplicant: [getIMSI]: sim_num 0
,05-19 12:12:02.042  3510  4407 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:02.042  9930  9930 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-19 12:12:02.052  9993  9993 E Zygote  : v2
05-19 12:12:02.052  9993  9993 I libpersona: KNOX_SDCARD checking this for 1000
05-19 12:12:02.052  9993  9993 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:02.052  9993  9993 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 12:12:02.052  3510  4407 I ActivityManager: Start proc 9993:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
,05-19 12:12:02.062  9993  9993 E Zygote  : accessInfo : 0
05-19 12:12:02.062  3510  4407 I ActivityManager: Killing 8936:com.android.defcontainer/u0a10 (adj 15): DHA:empty #33
,05-19 12:12:02.082  3510  4409 D ActivityManager: cleanUpApplicationRecord -- 8936
,05-19 12:12:02.082  3510  4409 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,05-19 12:12:02.082  9993  9993 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:02.082  9993  9993 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:02.092  3510  4312 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e542d12 9993:com.policydm/1000}
,05-19 12:12:02.102  9993  9993 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 12:12:02.102  9993  9993 D RelationGraph: garbageCollect()
,05-19 12:12:02.102  9993  9993 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package com.policydm
,05-19 12:12:02.102  3510  4407 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 12:12:02.102  9993  9993 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:02.102  9993  9993 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:02.112  9993  9993 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:02.112  9993  9993 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,05-19 12:12:02.132  9993  9993 I FOTA    : [lIlIIlIIlIlllIIIIlll(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
05-19 12:12:02.132  9993  9993 I FOTA    : [lIlIIlIIlIlllIIIIlll(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,05-19 12:12:02.142  9993  9993 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,05-19 12:12:02.152  9993  9993 I DBG_POLICYDM: [com.policydm.db.XDB(1600/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,05-19 12:12:02.152  9993  9993 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(142/llIIIIlllllIIllIIllI)] try read dbString
,05-19 12:12:02.202  9993  9993 I DBG_POLICYDM: [com.policydm.XDMService(161/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,05-19 12:12:02.212  9993  9993 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(52/<init>)] 
,05-19 12:12:02.212  9993  9993 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:56 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:19 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:25 
,05-19 12:12:02.222 10009 10009 E Zygote  : v2
05-19 12:12:02.222 10009 10009 I libpersona: KNOX_SDCARD checking this for 1000
05-19 12:12:02.222 10009 10009 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 12:12:02.222 10009 10009 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:02.222 10009 10009 E Zygote  : accessInfo : 0
,05-19 12:12:02.232  3510  3530 I ActivityManager: Start proc 10009:com.samsung.aasaservice/1000 for service com.samsung.aasaservice/.AASAService
,05-19 12:12:02.232  9993  9993 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(28/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,05-19 12:12:02.232  9993  9993 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-19 12:12:02.242  9993  9993 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-19 12:12:02.242  9993  9993 D InjectionManager: InjectionManager
05-19 12:12:02.242  9993  9993 D InjectionManager: fillFeatureStoreMap com.policydm
05-19 12:12:02.242  9993  9993 I InjectionManager: Constructor com.policydm, Feature store :{}
05-19 12:12:02.242  9993  9993 I InjectionManager: featureStore :{}
,05-19 12:12:02.242 10009 10009 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:02.242 10009 10009 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:02.252  9993  9993 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,05-19 12:12:02.252  9993  9993 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-19 12:12:02.252  9993  9993 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-19 12:12:02.252  3510  4257 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:02.252  3510  4257 I ActivityManager: Killing 8806:com.samsung.android.app.appsedge/u0a1 (adj 15): DHA:empty #33
,05-19 12:12:02.262 10009 10009 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:02.262 10009 10009 D RelationGraph: garbageCollect()
,05-19 12:12:02.262 10009 10009 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package com.samsung.aasaservice
,05-19 12:12:02.262  3510  4947 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:12:02.262 10009 10009 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:02.262 10009 10009 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:02.272 10009 10009 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:02.272 10009 10009 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm64
,05-19 12:12:02.272 10009 10009 D InjectionManager: InjectionManager
,05-19 12:12:02.272 10009 10009 D InjectionManager: fillFeatureStoreMap com.samsung.aasaservice
05-19 12:12:02.272 10009 10009 I InjectionManager: Constructor com.samsung.aasaservice, Feature store :{}
05-19 12:12:02.272 10009 10009 I InjectionManager: featureStore :{}
,05-19 12:12:02.272  3510  4406 D ActivityManager: cleanUpApplicationRecord -- 8806
05-19 12:12:02.272  3510  4406 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.appsedge, Auto Run ON
,05-19 12:12:02.272 10009 10009 D AASAservice: onCreate()
,05-19 12:12:02.282  9993  9993 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(38/onServiceConnected)] AASA: onServiceConnected
,05-19 12:12:02.282  3510  4312 I ActivityManager: Killing 9243:com.samsung.android.app.galaxylabs/u0a17 (adj 15): DHA:empty #33
,05-19 12:12:02.302  3510  4257 D ActivityManager: cleanUpApplicationRecord -- 9243
05-19 12:12:02.302  3510  4257 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.galaxylabs, Auto Run ON
,05-19 12:12:02.432  9666  9751 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 12:12:02.432  3510  4427 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 12:12:02.432  3510  4427 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 12:12:02.442  3510  4427 D WifiService: setWifiEnabled: true pid=9666, uid=10078
05-19 12:12:02.442  3510  4427 W WifiService: Failed getting userId using ActivityManagerNative
05-19 12:12:02.442  3510  4427 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:12:02.442  3510  4427 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:12:02.442  3510  4427 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 12:12:02.442  3510  4427 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 12:12:02.442  3510  4427 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 12:12:02.442  3510  4427 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 12:12:02.442  3510  4427 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-19 12:12:02.442  3510  4427 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 12:12:02.442  3510  4427 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-19 12:12:02.442  3510  3863 D WifiStateMachine: setFccChannel: channel = 0
05-19 12:12:02.442  3510  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-19 12:12:02.442  3510  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-19 12:12:02.542  3510  3594 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
05-19 12:12:02.542  3510  3594 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-19 12:12:02.542  3510  3594 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,05-19 12:12:02.552  3510  3598 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:02.562  3510  3598 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e542d12 9993:com.policydm/1000}
,05-19 12:12:02.562  9993  9993 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,05-19 12:12:02.572  3510  4407 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:02.572  3510  4313 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3510  tag : BADGE_UPDATE@CPU_MIN@1
,05-19 12:12:02.602  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{6c4085e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:02.612  3510  4407 I ActivityManager: Start proc 10022:com.osp.app.signin/u0a44 for broadcast-5 com.osp.app.signin/.OspReceiver
,05-19 12:12:02.632  3510  6241 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:02.722 10022 10022 E Zygote  : v2
05-19 12:12:02.722 10022 10022 I libpersona: KNOX_SDCARD checking this for 10044
,05-19 12:12:02.722 10022 10022 I libpersona: KNOX_SDCARD not a persona
05-19 12:12:02.722 10022 10022 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:02.722 10022 10022 E Zygote  : accessInfo : 0
,05-19 12:12:02.732 10022 10022 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.osp.app.signin 
,05-19 12:12:02.782 10022 10022 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:02.782 10022 10022 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:02.812  3510  4059 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b8643f 10022:com.osp.app.signin/u0a44}
,05-19 12:12:02.822 10022 10022 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:02.822 10022 10022 D RelationGraph: garbageCollect()
,05-19 12:12:02.822 10022 10022 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in com.osp.app.signin rsrc of package com.osp.app.signin
,05-19 12:12:02.832  3510  4407 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 12:12:02.832 10022 10022 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:02.842 10022 10022 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:02.842 10022 10022 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:02.862 10022 10022 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungAccount_Hero/lib/arm64
,05-19 12:12:02.872  3158  3618 D Netd    : Iface wlan0 link up
05-19 12:12:02.872 10022 10022 I SA      : [SSP] onCreated
,05-19 12:12:02.872  3158  3618 D Netd    : Iface wlan0 link up
05-19 12:12:02.872  3158  3618 D Netd    : Iface wlan0 link up
05-19 12:12:02.872  3510  3601 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 12:12:02.872  3510  3601 D Tethering: interfaceStatusChanged wlan0, true
,05-19 12:12:02.882  5067  5079 D PdnController: Interface Changed wlan0 link up
,05-19 12:12:02.882  3510  3601 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 12:12:02.882  3510  3601 D Tethering: interfaceStatusChanged wlan0, true
,05-19 12:12:02.882  5067  5358 D PdnController: Interface Changed wlan0 link up
05-19 12:12:02.882  3510  3601 D Tethering: interfaceLinkStateChanged wlan0, true
,05-19 12:12:02.882  3510  3601 D Tethering: interfaceStatusChanged wlan0, true
,05-19 12:12:02.882  5067  5077 D PdnController: Interface Changed wlan0 link up
,05-19 12:12:02.902 10022 10022 D SamsungAnalytics: [Tracker] Tracker start:1.2.00
,05-19 12:12:02.922 10022 10022 I SA      : [TPM] There is no property file
,05-19 12:12:02.922 10022 10022 I SA      : [SCU] isHaveSA() - false
,05-19 12:12:02.922 10022 10022 I SA      : [TPM] getModelProperty : null
,05-19 12:12:02.922 10022 10022 I SA      : [TPM] getCSCProperty : null
05-19 12:12:02.932 10022 10022 I SA      : [DM] FLOATING AMOLED FEATURE: true
05-19 12:12:02.932 10022 10022 I SA      : [DM] PRODUCT AMOLED FEATURE: false
05-19 12:12:02.932 10022 10022 I SA      : [DM] TFT FEATURE: false
,05-19 12:12:02.932 10022 10022 I SA      : [SCU] isHaveSA() - false
,05-19 12:12:02.932 10022 10022 I SA      : [SCU] == networkStateCheck == false
,05-19 12:12:02.932 10022 10022 I SA      : [SS] network off, couldn't connect to DIR
05-19 12:12:02.932 10022 10022 D InjectionManager: InjectionManager
05-19 12:12:02.932 10022 10022 D InjectionManager: fillFeatureStoreMap com.osp.app.signin
05-19 12:12:02.932 10022 10022 I InjectionManager: Constructor com.osp.app.signin, Feature store :{}
05-19 12:12:02.932 10022 10022 I InjectionManager: featureStore :{}
,05-19 12:12:02.932 10022 10022 I SA      : [DM] init START
,05-19 12:12:02.942 10022 10022 I SA      : [DM] This device is not a Vodafone
,05-19 12:12:02.942  9666  9751 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 12:12:02.942  3510  3529 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 12:12:02.942 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.942 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 12:12:02.942  3510  3529 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
05-19 12:12:02.942 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.942 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: Failure getting entry for 0x7f0a0002 (t=9 e=2) (error -75)
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 12:12:02.952  3510  3529 D WifiService: setWifiEnabled: true pid=9666, uid=10078
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952  3510  3529 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952  3510  3529 W WifiService: Failed getting userId using ActivityManagerNative
05-19 12:12:02.952  3510  3529 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:12:02.952  3510  3529 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:12:02.952  3510  3529 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 12:12:02.952  3510  3529 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 12:12:02.952  3510  3529 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 12:12:02.952  3510  3529 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 12:12:02.952  3510  3529 D SettingsProvider: isChangeAllowed() : name = wifi_on
,05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952  3510  3863 D WifiController: [FCC]setFccChannel() is called !!!
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952  3510  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-19 12:12:02.952  3510  3529 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952  3510  3863 D WifiStateMachine: setFccChannel: channel = 0
,05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: Failure getting entry for 0x7f0a0005 (t=9 e=5) (error -75)
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.952 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-19 12:12:02.962 10022 10022 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-19 12:12:02.962 10022 10022 I SA      : support phone number id : true
,05-19 12:12:02.962 10022 10022 I SA      : [DM] Supports Ref Jpn : true
05-19 12:12:02.962 10022 10022 I SA      : [DM] init END
,05-19 12:12:02.972 10022 10022 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hero2lte P = hero2ltexx I = MMB29K M = SM-G935F OKLEFT false DIS MMB29K.G935FXXU1BPJG PSS = 5.460694751064798  ]
05-19 12:12:02.972 10022 10022 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
05-19 12:12:02.972 10022 10022 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,05-19 12:12:02.972 10022 10022 I SA      : [SLFUCHKMGR] constructor called
,05-19 12:12:02.982 10022 10022 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-19 12:12:02.992 10022 10022 I SA      : [OR] == isSIMCardReady false ==
,05-19 12:12:02.992 10022 10022 I SA      : [SCU] == networkStateCheck == false
05-19 12:12:02.992 10022 10022 I SA      : [OR] onReceive END
,05-19 12:12:03.002  9930  9930 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
05-19 12:12:03.002  9930  9930 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-19 12:12:03.032  9930  9930 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-19 12:12:03.032  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9930
05-19 12:12:03.032  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-19 12:12:03.032  9930  9930 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-19 12:12:03.032  9930  9930 I wpa_supplicant: ssSupport state is = 1
,05-19 12:12:03.042  9930  9930 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-19 12:12:03.042  9930  9930 E wpa_supplicant: nl80211: Could not configure driver mode
05-19 12:12:03.042  9930  9930 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
05-19 12:12:03.042  9930  9930 E wpa_supplicant: p2p0: Failed to initialize driver interface
05-19 12:12:03.042  9930  9930 I wpa_supplicant: Blacklist: Clear (all) 
,05-19 12:12:03.042  9930  9930 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,05-19 12:12:03.042  9930  9930 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-19 12:12:03.052  3510  4040 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:03.052  3510  4040 I ActivityManager: Killing 9260:com.google.android.partnersetup/u0a25 (adj 15): DHA:empty #33
,05-19 12:12:03.062  3510  4040 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{37a15b2 6976:com.wssyncmldm/1000}
,05-19 12:12:03.062  3510  4257 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:03.072  9930  9930 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-19 12:12:03.072  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9930
05-19 12:12:03.072  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-19 12:12:03.072  9930  9930 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-19 12:12:03.072  9930  9930 I wpa_supplicant: ssSupport state is = 1
05-19 12:12:03.072  9930  9930 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-19 12:12:03.072  3510  4257 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2890fed 7120:com.samsung.fresco.logging/5015}
,05-19 12:12:03.082  3510  3530 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:03.082  3510  4983 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:03.082  9930  9930 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,05-19 12:12:03.082  3510  4518 D ActivityManager: cleanUpApplicationRecord -- 9260
05-19 12:12:03.082  3510  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
05-19 12:12:03.082  3510  4518 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,05-19 12:12:03.092  3510  3860 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,05-19 12:12:03.092  3510  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-19 12:12:03.092  3510  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-19 12:12:03.092  3510  4257 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:03.102  3510  4257 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{175e416 7489:com.sec.spp.push/u0a42}
,05-19 12:12:03.102  7489  7489 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,05-19 12:12:03.102  7489  7489 E SPPClientService: [SystemStateMoniter] Current Time : 208676
,05-19 12:12:03.102  7489  7489 E SPPClientService: [SystemStateMoniter] No Connect : true
,05-19 12:12:03.112  3510  3860 D WifiBigDataLog: init : 
,05-19 12:12:03.112  3510  3860 E WifiStateMachine: Deffering msg in Supplicant Starting State131083
,05-19 12:12:03.112  3510  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,05-19 12:12:03.112  3510  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-19 12:12:03.112  3510  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-19 12:12:03.112  3510  4257 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:03.122  7489 10043 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,05-19 12:12:03.122  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ba91a55 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:12:03.122  3510  3860 D WifiBigDataLog: init : 
,05-19 12:12:03.132  3510  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-19 12:12:03.132  3510  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-19 12:12:03.132  3510  3860 D WifiBigDataLog: init : 
,05-19 12:12:03.132  3510  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-19 12:12:03.132  3510  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-19 12:12:03.142  3510  4257 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fc44c6a u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:12:03.142  3510  3860 D WifiBigDataLog: init : 
,05-19 12:12:03.152  3510  3860 D WifiNative-wlan0: callSECApiBoolean - ID [301]
,05-19 12:12:03.152  9930  9930 I wpa_supplicant: HOTSPOT20_ENABLE called ON
05-19 12:12:03.152  9930  9930 I wpa_supplicant: Blacklist: Clear (all) 
,05-19 12:12:03.152  9930  9930 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,05-19 12:12:03.152  3510  4257 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9d9055b u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:12:03.162  9930  9930 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,05-19 12:12:03.162  3510  3860 D WifiNative-wlan0: callSECApiInt - ID [210]
,05-19 12:12:03.162  3510  3510 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,05-19 12:12:03.162  3510  3864 D HS20StateMachine: WIFI_STATE_ENABLED
05-19 12:12:03.162  3510  3864 D HS20StateMachine: reloadCredentialsToSupplicant
05-19 12:12:03.162  3510  3864 D HotspotDBHandler: getCredentialIds
05-19 12:12:03.162  3510  3510 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-19 12:12:03.162  3510  3867 I WifiHs20Service: Message received 5011
,05-19 12:12:03.172  3510  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-19 12:12:03.172  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 12:12:03.172  3510  3510 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-19 12:12:03.172  3510  4235 W SLocation: No Active Data Connection
,05-19 12:12:03.172  4288  4299 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-19 12:12:03.172  4288  4299 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-19 12:12:03.172  3942  3942 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-19 12:12:03.172  3942  3942 I HotspotTile: Provider is not defined returning false
05-19 12:12:03.172  3510  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-19 12:12:03.172  3942  3942 D HotspotTile: onReceive : 3, 0
,05-19 12:12:03.182  3942  3942 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-19 12:12:03.192  9666  9666 D BluetoothAdapter: STATE_ON
,05-19 12:12:03.192  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 12:12:03.192  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:12:03.192  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:12:03.192  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:12:03.192  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:12:03.192  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-19 12:12:03.192  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-19 12:12:03.192  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-19 12:12:03.192  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-19 12:12:03.192  9666  9666 D BluetoothAdapter: STATE_ON
,05-19 12:12:03.202  9666  9666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-19 12:12:03.202  9930  9930 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,05-19 12:12:03.202 10045 10045 E Zygote  : v2
05-19 12:12:03.202 10045 10045 I libpersona: KNOX_SDCARD checking this for 10119
05-19 12:12:03.202 10045 10045 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:03.202 10045 10045 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:03.202  3510  3860 D WifiConfigStore: Loading config and enabling all networks 
,05-19 12:12:03.202 10045 10045 E Zygote  : accessInfo : 0
,05-19 12:12:03.212 10045 10045 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,05-19 12:12:03.212  3510  3864 I ActivityManager: Start proc 10045:com.samsung.hs20provider/u0a119 for content provider com.samsung.hs20provider/.Hs20Provider
,05-19 12:12:03.212  3510  4257 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4ae06d1 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:12:03.222  3510  3860 I WifiConfigStore: "NG700" is a verified password AP: true
05-19 12:12:03.222  3510  3860 E WifiConfigStore: Not a HS20
,05-19 12:12:03.222  3510  3860 D WifiConfigStore: loaded 0 passpoint configs
,05-19 12:12:03.222  3510  3860 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,05-19 12:12:03.232  3510  3860 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
05-19 12:12:03.232  3510  3860 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,05-19 12:12:03.232  3510  4257 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad2c536 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e943933 9666:com.rockwellautomation.thalitest/u0a78}
,05-19 12:12:03.232  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:03.232  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:03.232  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:03.232  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:03.232  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:03.232  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:03.232  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:03.232  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:03.232  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:03.242 10045 10045 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:03.242  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:03.242 10045 10045 D ActivityThread: Added TimaKeyStore provider
05-19 12:12:03.242  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:03.242  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-19 12:12:03.242  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:03.242  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:03.242  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:03.242  3510  3860 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
,05-19 12:12:03.242  3510  3860 D WifiNative-wlan0: callSECApiInt - ID [65]
,05-19 12:12:03.252  3510  3860 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,05-19 12:12:03.252  9930  9930 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
05-19 12:12:03.252  9930  9930 I wpa_supplicant: resume autoscan
05-19 12:12:03.252  9930  9930 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
05-19 12:12:03.252  9930  9930 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
05-19 12:12:03.252  9930  9930 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,05-19 12:12:03.252  9930  9930 I wpa_supplicant: reset timer : RESET_TIMER 0
05-19 12:12:03.252  9930  9930 I wpa_supplicant: P2P: Current p2p state = IDLE
,05-19 12:12:03.252  9930  9930 I wpa_supplicant: First Scan Start
,05-19 12:12:03.252  3510  3510 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
,05-19 12:12:03.252  3510  3510 D WifiHs20Service: reason: 2
05-19 12:12:03.252  3510  3867 I WifiHs20Service: Message received 5014
,05-19 12:12:03.252  3510  3867 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
05-19 12:12:03.252  3510  3867 E WifiHs20Service: The changed config is NULL
05-19 12:12:03.252  9930  9930 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,05-19 12:12:03.262  3510  3860 D WifiNative-wlan0: Setting external_sim to 1
,05-19 12:12:03.262  3510  3860 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
,05-19 12:12:03.262  3510  3860 D WifiStateMachine: Setting OUI to DA-A1-19
,05-19 12:12:03.262  9930  9930 I wpa_supplicant: bt_status is set be DISCONNECTED
,05-19 12:12:03.262 10045 10045 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:03.262 10045 10045 D RelationGraph: garbageCollect()
,05-19 12:12:03.272 10045 10045 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
,05-19 12:12:03.272  3510  4983 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 12:12:03.272 10045 10045 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:03.272  3510  3860 E WifiNative-wlan0: do suspend false
,05-19 12:12:03.272 10045 10045 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:03.272 10045 10045 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:03.282  3510  3860 D WifiStateMachine:  p2p Needed be enabled 
,05-19 12:12:03.282  3510  3858 D WifiP2pService: P2pDisabledState{ what=131203 }
,05-19 12:12:03.282  3510  3860 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
05-19 12:12:03.282  3510  3860 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
05-19 12:12:03.282  3510  3860 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
05-19 12:12:03.282  3510  3860 D WifiStateMachine: setFccChannelNative: channel = 0
05-19 12:12:03.282  3510  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
05-19 12:12:03.282  3510  3510 D RttService: SCAN_AVAILABLE : 3
,05-19 12:12:03.282  3510  3893 E WifiScanningService: could not start HAL
05-19 12:12:03.282 10045 10045 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
05-19 12:12:03.282  3510  3894 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,05-19 12:12:03.282  3158  3625 D CommandListener: Setting iface cfg
,05-19 12:12:03.282  3158  3625 D CommandListener: Trying to bring up p2p0
05-19 12:12:03.282  3158  3618 D Netd    : Iface p2p0 link up
,05-19 12:12:03.292  3510  3601 D Tethering: interfaceLinkStateChanged p2p0, true
05-19 12:12:03.292  3510  3601 D Tethering: interfaceStatusChanged p2p0, true
,05-19 12:12:03.292  5067  5360 D PdnController: Interface Changed p2p0 link up
,05-19 12:12:03.292  3510  3858 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
05-19 12:12:03.292  3510  3858 D SecContentProvider: insert(), uri = 2
,05-19 12:12:03.292 10045 10045 D InjectionManager: InjectionManager
05-19 12:12:03.292  3510  3858 D WifiP2pService: P2pEnablingState
05-19 12:12:03.292 10045 10045 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
,05-19 12:12:03.292  3510  3858 D WifiP2pService: P2pEnablingState{ what=147457 }
,05-19 12:12:03.292  3510  3858 D WifiP2pService: P2p socket connection successful
,05-19 12:12:03.292  3510  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-19 12:12:03.302  3510  3858 D WifiP2pService: P2pEnabledState
05-19 12:12:03.302  3510  3858 D SecContentProvider: insert(), uri = 2
,05-19 12:12:03.302 10045 10045 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
,05-19 12:12:03.302 10045 10045 I InjectionManager: featureStore :{}
,05-19 12:12:03.302 10045 10056 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
,05-19 12:12:03.302 10045 10056 D HotspotProvider: CREDENTIAL
05-19 12:12:03.302 10045 10056 D HotspotProvider: No prepend tags
05-19 12:12:03.302  3510  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-19 12:12:03.312  3510  3869 E ConnectivityService: updateNetworkInfo()
,05-19 12:12:03.312  3510  3858 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
05-19 12:12:03.312  3510  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,05-19 12:12:03.312  3510  3510 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
05-19 12:12:03.312  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:12:03.312  3510  3610 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
05-19 12:12:03.312  3510  3610 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
05-19 12:12:03.312  3510  3610 D WifiDisplayController: disconnect
05-19 12:12:03.312  3510  3610 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-19 12:12:03.312  3942  3942 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-19 12:12:03.312  3942  3942 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-19 12:12:03.322  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:12:03.322  3942  3942 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-19 12:12:03.322  3510  4313 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-19 12:12:03.322  3942  3942 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,05-19 12:12:03.322  3510  3610 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:03.322  9930  9930 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,05-19 12:12:03.322  3510  3610 I WifiDisplayAdapter: onP2pDisconnected
05-19 12:12:03.322  9930  9930 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,05-19 12:12:03.322  3510  3610 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-19 12:12:03.322  3942  3942 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
05-19 12:12:03.322  3510  3610 D IpRemoteDisplayController: WfdBridgeServer is already null
,05-19 12:12:03.332  4288  5440 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,05-19 12:12:03.332  3510  3864 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
,05-19 12:12:03.332  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{71d75a4 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5f4774 9968:com.samsung.android.app.FileShareClient/5005}
05-19 12:12:03.332  3510  3864 D HS20StateMachine: enter : DiscoveringState
05-19 12:12:03.332  9968  9968 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-19 12:12:03.332  9968  9968 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
05-19 12:12:03.332  9968  9968 D FileShare-Client: Outbound.stopDelayTimer - 
,05-19 12:12:03.352  3510  3529 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{71d75a4 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{70ef49d 9980:com.samsung.android.app.FileShareServer/5005}
,05-19 12:12:03.362  9980  9980 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-19 12:12:03.362  9980  9980 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-19 12:12:03.362  9980  9980 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-19 12:12:03.372  3510  4427 I ActivityManager: Killing 9280:com.samsung.android.asksmanager/u0a177 (adj 15): DHA:empty #33
,05-19 12:12:03.382  3510  3858 E WifiP2pService: Failed to set my phone number info into probe response
,05-19 12:12:03.382  3510  3858 D WifiNative-p2p0: p2pGetDeviceAddress
,05-19 12:12:03.382  3510  3858 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a6:c7:2d
,05-19 12:12:03.382  3510  3858 D WifiP2pService: DeviceAddress: 4e:c7:2d
05-19 12:12:03.382  3510  3610 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7 edge
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  deviceAddress: 4e:66:41:a6:c7:2d
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  primary type: 10-0050F204-5
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  secondary type: null
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  wps: 0
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  grpcapab: 0
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  devcapab: 0
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  status: 3
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  wfdInfo: null
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  groupownerAddress: null
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  GOdeviceName: null
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  interfaceAddress: 
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  SConnectInfo : null
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  contactInfoHash : null
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  ssDevInfo : 0
05-19 12:12:03.382  3510  3610 D WifiDisplayController:  iconIdx : 0
,05-19 12:12:03.392  3510  4518 D ActivityManager: cleanUpApplicationRecord -- 9280
,05-19 12:12:03.392  3510  4518 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.asksmanager, Auto Run ON
,05-19 12:12:03.392  3510  3858 D WifiP2pService: sending p2p persistent groups changed broadcast
,05-19 12:12:03.402  3510  3858 D WifiP2pService: InactiveState
,05-19 12:12:03.402  3510  3858 D WifiP2pService: InactiveState{ what=143376 }
05-19 12:12:03.402  3510  3858 D WifiP2pService: P2pEnabledState{ what=143376 }
05-19 12:12:03.402  3510  3858 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,05-19 12:12:03.412  3510  3598 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:03.422  3510  3598 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bebefe2 4914:android.process.media/u0a51}
,05-19 12:12:03.422  4914  4914 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,05-19 12:12:03.422  3510  3854 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:03.442 10057 10057 E Zygote  : v2
05-19 12:12:03.442 10057 10057 I libpersona: KNOX_SDCARD checking this for 1000
05-19 12:12:03.442 10057 10057 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:03.442 10057 10057 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:03.442  3510  3854 I ActivityManager: Start proc 10057:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
,05-19 12:12:03.442 10057 10057 E Zygote  : accessInfo : 0
,05-19 12:12:03.462  9666  9751 D BluetoothAdapter: STATE_ON
,05-19 12:12:03.462  9666  9751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 12:12:03.462  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:12:03.462  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:12:03.462  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:12:03.462  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:12:03.462  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-19 12:12:03.462  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-19 12:12:03.462  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-19 12:12:03.462  9666  9751 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-19 12:12:03.462  9666  9729 D BluetoothAdapter: enable()
,05-19 12:12:03.462  9666  9729 D BluetoothAdapter: enable(): BT is already enabled..!
,05-19 12:12:03.472  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{23b3f0d u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:12:03.472  9666  9729 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-19 12:12:03.472  3510  4407 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-19 12:12:03.472  3510  4407 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-19 12:12:03.482 10057 10057 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-19 12:12:03.482 10057 10057 D ActivityThread: Added TimaKeyStore provider
05-19 12:12:03.482  3510  4407 D WifiService: setWifiEnabled: true pid=9666, uid=10078
,05-19 12:12:03.482  3510  4407 W ActivityManager: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:12:03.482  3510  4407 W WifiService: Failed getting userId using ActivityManagerNative
05-19 12:12:03.482  3510  4407 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9666, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-19 12:12:03.482  3510  4407 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-19 12:12:03.482  3510  4407 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-19 12:12:03.482  3510  4407 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-19 12:12:03.482  3510  4407 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-19 12:12:03.482  3510  4407 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-19 12:12:03.482  3510  4407 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-19 12:12:03.482  3510  4407 D SettingsProvider: isChangeAllowed() : name = wifi_on
,05-19 12:12:03.482  3510  3860 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-19 12:12:03.482  3510  3863 D WifiController: [FCC]setFccChannel() is called !!!
,05-19 12:12:03.482  3510  3863 D WifiStateMachine: setFccChannel: channel = 0
05-19 12:12:03.482  3510  3863 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-19 12:12:03.482  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-19 12:12:03.482  3510  3860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-19 12:12:03.482  9666  9729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-19 12:12:03.482  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 12:12:03.482  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-19 12:12:03.482  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,05-19 12:12:03.482  9666  9729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d547a7 removed from the list
05-19 12:12:03.482  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d547a7 removed from the list
05-19 12:12:03.482  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-19 12:12:03.482  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fce9454 removed from the list
05-19 12:12:03.482  9666  9729 D io.jxcore.node.ConnectivityMonitor: stop
05-19 12:12:03.482  9666  9729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-19 12:12:03.482  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 12:12:03.482  9666  9729 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,05-19 12:12:03.492  9666 10069 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,05-19 12:12:03.492  9666 10069 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
05-19 12:12:03.492  3510  4406 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{17dfec2 10057:com.samsung.android.SettingsReceiver/1000}
,05-19 12:12:03.492  3510  3860 D WifiBigDataLog: init : 
,05-19 12:12:03.502  3510  3860 D WifiStateMachine: setFccChannelNative: channel = 0
,05-19 12:12:03.502  3510  3860 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-19 12:12:03.502  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{250c4d3 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ef56d9 5053:com.samsung.android.providers.context/u0a9}
,05-19 12:12:03.512 10057 10057 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 12:12:03.512 10057 10057 D RelationGraph: garbageCollect()
,05-19 12:12:03.512 10057 10057 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
,05-19 12:12:03.512  3510  4518 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 12:12:03.512 10057 10057 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:03.522 10057 10057 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:03.522 10057 10057 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:03.532 10057 10057 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
,05-19 12:12:03.532 10057 10057 D InjectionManager: InjectionManager
05-19 12:12:03.532 10057 10057 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
,05-19 12:12:03.532 10057 10057 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
05-19 12:12:03.532 10057 10057 I InjectionManager: featureStore :{}
,05-19 12:12:03.532 10057 10057 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.android.settings
,05-19 12:12:03.542 10057 10057 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:03.542 10057 10057 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,05-19 12:12:03.552  3510  4427 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:03.562 10072 10072 E Zygote  : v2
05-19 12:12:03.562 10072 10072 I libpersona: KNOX_SDCARD checking this for 10068
05-19 12:12:03.562 10072 10072 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:03.562 10072 10072 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:03.572  3510  4427 I ActivityManager: Start proc 10072:com.samsung.android.themestore/u0a68 for broadcast-5 com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
05-19 12:12:03.572 10072 10072 E Zygote  : accessInfo : 0
05-19 12:12:03.572  3510  4427 I ActivityManager: Killing 9306:com.samsung.svoice.sync/u0a43 (adj 15): DHA:empty #33
05-19 12:12:03.572 10072 10072 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,05-19 12:12:03.592  3510  3530 D ActivityManager: cleanUpApplicationRecord -- 9306
,05-19 12:12:03.592  3510  3530 D ActivityManager: isAutoRunBlockedApp:: com.samsung.svoice.sync, Auto Run ON
,05-19 12:12:03.602 10072 10072 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:03.602 10072 10072 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:03.612  3510  3854 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{68e4810 10072:com.samsung.android.themestore/u0a68}
,05-19 12:12:03.622 10072 10072 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 12:12:03.622 10072 10072 D RelationGraph: garbageCollect()
,05-19 12:12:03.632 10072 10072 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeStore_3xh/ThemeStore_3xh.apk / 1.0 running in com.samsung.android.themestore rsrc of package com.samsung.android.themestore
,05-19 12:12:03.632  3510  4040 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:12:03.632 10072 10072 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:03.632 10072 10072 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:03.642 10072 10072 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:03.652 10072 10072 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeStore_3xh/lib/arm64
,05-19 12:12:03.662 10072 10072 D a       : Exist Config : false
05-19 12:12:03.662 10072 10072 D a       : getMcc
,05-19 12:12:03.662 10072 10072 D ai      : isQaMode
,05-19 12:12:03.672 10072 10072 D a       : getMnc
05-19 12:12:03.672 10072 10072 D a       : getCsc
,05-19 12:12:03.672 10072 10072 D a       : getSystemCountryCode
05-19 12:12:03.672 10072 10072 D a       : getImei
,05-19 12:12:03.672 10072 10072 D ai      : getMd5HashString
,05-19 12:12:03.682 10072 10072 D ai      : getSha256HashString
,05-19 12:12:03.682 10072 10072 D a       : getMsisdn
,05-19 12:12:03.682  4288  4613 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,05-19 12:12:03.692 10072 10072 D a       : getModelName
,05-19 12:12:03.692 10072 10072 D a       : getVirtualModelName
05-19 12:12:03.692 10072 10072 D a       : getAndroidSDKVersion
05-19 12:12:03.692 10072 10072 D a       : getLanguageCode
05-19 12:12:03.692 10072 10072 D a       : getCountryCode
,05-19 12:12:03.692 10072 10072 D a       : getNetworkType
,05-19 12:12:03.702 10072 10072 D t       : isSupportedAodSystemFeature
,05-19 12:12:03.712 10072 10072 D a       : isLogPrintMode
,05-19 12:12:03.712 10072 10072 D ai      : isQaMode
,05-19 12:12:03.722 10072 10072 D a       : getVerName
,05-19 12:12:03.722 10072 10072 D a       : getVerCode
,05-19 12:12:03.722 10072 10072 D a       : getPackageName
05-19 12:12:03.722 10072 10072 D a       : getAutoUpgradeInterval
,05-19 12:12:03.722 10072 10072 D a       : loadCountrySearchEx
,05-19 12:12:03.732 10072 10072 I a       : voCountrySearchEx loaded.
,05-19 12:12:03.732 10072 10072 I a       : # initConfig Time : 80
,05-19 12:12:03.732 10072 10072 I a       : ● MCCNNC : 260 0
05-19 12:12:03.732 10072 10072 I a       : ● Model : SM-G935F_TM
05-19 12:12:03.732 10072 10072 I a       : ● MyApp Vertion : 1.03.22(20160524)
05-19 12:12:03.732 10072 10072 I a       : ● OS Vertion : 23
,05-19 12:12:03.752 10072 10072 D InjectionManager: InjectionManager
05-19 12:12:03.752 10072 10072 D InjectionManager: fillFeatureStoreMap com.samsung.android.themestore
,05-19 12:12:03.762 10072 10072 I InjectionManager: Constructor com.samsung.android.themestore, Feature store :{}
05-19 12:12:03.762 10072 10072 I InjectionManager: featureStore :{}
,05-19 12:12:03.762 10072 10072 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,05-19 12:12:03.762  3510  4983 D ActivityManager:  getDeferredInfo final delay 80
,05-19 12:12:03.762  3510  4983 I ActivityManager: Killing 9362:com.samsung.android.provider.shootingmodeprovider/u0a60 (adj 15): DHA:empty #33
,05-19 12:12:03.792  3510  4518 D ActivityManager: cleanUpApplicationRecord -- 9362
,05-19 12:12:03.792  3510  4518 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,05-19 12:12:03.832  3158  3618 D Netd    : Iface wlan0 link up
,05-19 12:12:03.832  9930  9930 I wpa_supplicant: nl80211: Received scan results (4 BSSes)
05-19 12:12:03.832  9930  9930 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
05-19 12:12:03.832  9930  9930 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
05-19 12:12:03.832  9930  9930 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
05-19 12:12:03.832  9930  9930 I wpa_supplicant:    allow  - level is under -85dBm [-31] or selected nid [-1] [0]
05-19 12:12:03.832  3510  3601 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 12:12:03.832  3510  3601 D Tethering: interfaceStatusChanged wlan0, true
05-19 12:12:03.832  9930  9930 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
05-19 12:12:03.832  9930  9930 I wpa_supplicant:    allow  - level is under -85dBm [-31] or selected nid [-1] [0]
05-19 12:12:03.832  9930  9930 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2442 MHz level=-31) 
,05-19 12:12:03.832  5067  5077 D PdnController: Interface Changed wlan0 link up
,05-19 12:12:03.842  3510  3598 D ActivityManager:  getDeferredInfo final delay 80
,05-19 12:12:03.862  3510  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-19 12:12:03.862  3510  3510 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,05-19 12:12:03.872  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e9bf09 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c3d756 3942:com.android.systemui/u0a65}
,05-19 12:12:03.882  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:12:03.922  3510  3598 D ActivityManager:  getDeferredInfo final delay 80
,05-19 12:12:03.972  9930  9930 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,05-19 12:12:03.982  3158  3618 D Netd    : Iface wlan0 link up
05-19 12:12:03.982  3158  3618 D Netd    : Iface wlan0 link up
05-19 12:12:03.982  3158  3618 D Netd    : Iface wlan0 link up
,05-19 12:12:03.982  3510  3601 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 12:12:03.982  3510  3601 D Tethering: interfaceStatusChanged wlan0, true
,05-19 12:12:03.992  5067  5360 D PdnController: Interface Changed wlan0 link up
,05-19 12:12:03.992  3510  3601 D Tethering: interfaceLinkStateChanged wlan0, true
,05-19 12:12:03.992  9930  9930 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,05-19 12:12:03.992  3510  3601 D Tethering: interfaceStatusChanged wlan0, true
,05-19 12:12:03.992  5067  5079 D PdnController: Interface Changed wlan0 link up
,05-19 12:12:04.002  3510  3601 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 12:12:04.002  3510  3601 D Tethering: interfaceStatusChanged wlan0, true
05-19 12:12:04.002  9930  9930 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
05-19 12:12:04.002  5067  5358 D PdnController: Interface Changed wlan0 link up
,05-19 12:12:04.002  9930  9930 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
05-19 12:12:04.002  3158  3621 D EnterpriseController: netId is 0
05-19 12:12:04.002  3158  3621 D Netd    : getNetworkForDns: using netid 0 for uid 10078
,05-19 12:12:04.012  9666 10091 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
05-19 12:12:04.012  9930  9930 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
05-19 12:12:04.012  9666 10091 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-19 12:12:04.012  9666 10091 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-19 12:12:04.012  9666 10091 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 12:12:04.012  9666 10069 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-19 12:12:04.012  9666 10069 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-19 12:12:04.012  9666 10091 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-19 12:12:04.012  9666 10069 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-19 12:12:04.022  9666 10093 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 233, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.022  9666 10093 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 12:12:04.022  9666 10093 D io.jxcore.node.StreamCopyingThread:  id: 74
,05-19 12:12:04.022  9666 10069 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-19 12:12:04.022  9930  9930 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 234, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread:  id: 74
,05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 235, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread:  id: 75
,05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 234, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread:  id: 74
,05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread:  id: 74
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,05-19 12:12:04.022  9666 10093 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 233, thread name: IncomingSocketThread/Sender): Socket closed
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,05-19 12:12:04.022  9666 10069 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
05-19 12:12:04.022  9666 10094 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,05-19 12:12:04.022  9666 10093 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 233, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.022  9666 10093 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 12:12:04.022  9666 10093 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 234, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 12:12:04.022  9666 10094 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-19 12:12:04.022  9666 10093 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
05-19 12:12:04.022  9666 10093 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,05-19 12:12:04.022  9666 10093 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 233, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.022  9666 10093 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 12:12:04.022  9666 10093 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 235, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread:  id: 75
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread:  id: 75
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 12:12:04.022  9666 10095 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 235, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:04.022  9666 10095 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-19 12:12:04.032  9930  9930 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
05-19 12:12:04.032  9930  9930 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
05-19 12:12:04.032  3158  3618 D Netd    : Iface wlan0 link up
05-19 12:12:04.032  9930  9930 I wpa_supplicant: Blacklist: Clear (temp) 
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 236, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread:  id: 75
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 236, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread:  id: 75
,05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread:  id: 75
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 12:12:04.032  9666 10096 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-19 12:12:04.032  3510  3601 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 12:12:04.032  3510  3601 D Tethering: interfaceStatusChanged wlan0, true
,05-19 12:12:04.032  5067  5077 D PdnController: Interface Changed wlan0 link up
05-19 12:12:04.032  9666 10096 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 236, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:04.032  9666 10096 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,05-19 12:12:04.042  3510  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-19 12:12:04.062  3510  3598 D ActivityManager:  getDeferredInfo final delay 80
,05-19 12:12:04.072  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:12:04.072  3510  3860 D WifiNative-wlan0: callSECApiVoid - ID [50]
,05-19 12:12:04.082  3510  3860 V AlarmManager:  remove PendingIntent] PendingIntent{ad502a4: PendingIntentRecord{258480d android broadcastIntent}}
,05-19 12:12:04.082  3510  3860 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,05-19 12:12:04.082  3510  3510 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-19 12:12:04.082  3510  3510 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 12:12:04.082  3510  3510 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-19 12:12:04.082  3510  3860 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-19 12:12:04.082  3510  3867 I WifiHs20Service: Message received 5007
05-19 12:12:04.082  3510  3510 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
05-19 12:12:04.082  3510  3869 E ConnectivityService: updateNetworkInfo()
05-19 12:12:04.082  3510  3869 D ConnectivityService: Got NetworkAgent Messenger
05-19 12:12:04.082  3510  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:04.082  3510  3869 D ConnectivityService: NetworkAgent connected
,05-19 12:12:04.092  3158  3625 D CommandListener: Setting iface cfg
,05-19 12:12:04.102  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:12:04.102  4288  4288 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-19 12:12:04.102  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{107057d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{226b6b 9931:com.sec.android.diagmonagent/1000}
,05-19 12:12:04.112  3510  3860 D WifiStateMachine: Start Dhcp Watchdog 2
,05-19 12:12:04.112  9931  9931 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-19 12:12:04.112  9931  9931 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-19 12:12:04.112  9931  9931 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-19 12:12:04.112  9931  9931 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-19 12:12:04.112  3510  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-19 12:12:04.122  3510  4983 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{107057d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{332c515 6617:com.enhance.gameservice/u0a111}
,05-19 12:12:04.142  3510  4983 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{107057d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{64e8361 9944:com.sec.knox.switcher/1000}
,05-19 12:12:04.142  9944  9944 I usagelog: received in receiver
05-19 12:12:04.142  9944  9944 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,05-19 12:12:04.142  9944  9944 I KnoxUsageLogPro: premStatus:2
05-19 12:12:04.142  9944  9944 I KnoxUsageLogPro: isEulaShown : false
05-19 12:12:04.142  9944  9944 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-19 12:12:04.142  3510  3598 D ActivityManager:  getDeferredInfo final delay 80
,05-19 12:12:04.142  3510  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-19 12:12:04.152  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:12:04.162  3510  4518 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{107057d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97bae86 9956:com.samsung.android.sm.policy/u0a142}
,05-19 12:12:04.172  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:12:04.172  3510  3860 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,05-19 12:12:04.172  3510  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
05-19 12:12:04.172  3510  3869 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-19 12:12:04.172  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:12:04.182  3510  3869 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-19 12:12:04.182  3510  3860 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-19 12:12:04.192  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-19 12:12:04.222  3510  3598 D ActivityManager:  getDeferredInfo final delay 80
,05-19 12:12:04.282  3510  3860 E WifiNative-wlan0: do suspend false
,05-19 12:12:04.292  3510  3858 D WifiP2pService: InactiveState{ what=143375 }
,05-19 12:12:04.302  3510  3858 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-19 12:12:04.312  3510  3598 D ActivityManager:  getDeferredInfo final delay 80
,05-19 12:12:04.342 10099 10099 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,05-19 12:12:04.342 10099 10099 I dhcpcd  : version 5.5.6 starting
,05-19 12:12:04.352 10099 10099 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,05-19 12:12:04.392  3510  3598 D ActivityManager:  getDeferredInfo final delay 80
,05-19 12:12:04.432 10099 10099 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
05-19 12:12:04.432 10099 10099 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,05-19 12:12:04.432 10099 10099 I dhcpcd  : bssid match
,05-19 12:12:04.432 10099 10099 I dhcpcd  : wlan0: rebinding lease of 192.168.1.107
,05-19 12:12:04.472  3510  3598 D ActivityManager:  getDeferredInfo final delay 80
,05-19 12:12:04.482 10099 10099 I dhcpcd  : wlan0: acknowledged 192.168.1.107 from 192.168.1.1
,05-19 12:12:04.542 10099 10099 I dhcpcd  : wlan0: leased 192.168.1.107 for 172800 seconds
,05-19 12:12:04.552  3510  3869 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
05-19 12:12:04.552  3510  3598 D ActivityManager:  getDeferredInfo final delay 80
,05-19 12:12:04.632  3510  3598 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:04.662 10113 10113 E Zygote  : v2
05-19 12:12:04.662 10113 10113 I libpersona: KNOX_SDCARD checking this for 5009
05-19 12:12:04.662 10113 10113 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:04.662 10113 10113 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:04.662 10113 10113 E Zygote  : accessInfo : 0
05-19 12:12:04.662 10113 10113 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud:contentsync 
,05-19 12:12:04.672  3510  3598 I ActivityManager: Start proc 10113:com.samsung.android.scloud:contentsync/5009 for broadcast-5 com.samsung.android.scloud/.cloudagent.detector.DetectorReceiver
,05-19 12:12:04.692 10113 10113 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:04.692 10113 10113 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:04.712  3510  4406 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca70c58 10113:com.samsung.android.scloud:contentsync/5009}
,05-19 12:12:04.722 10113 10113 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 12:12:04.722 10113 10113 D RelationGraph: garbageCollect()
,05-19 12:12:04.732 10113 10113 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.scloud
,05-19 12:12:04.732  3510  4059 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:12:04.732 10113 10113 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:04.732 10113 10113 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:04.742 10113 10113 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:04.742 10113 10113 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungCloud/lib/arm64
,05-19 12:12:04.772 10113 10113 I [SC]CloudManager: requestInit
,05-19 12:12:04.812 10113 10113 I [SC]Utils: folder : cachecreate fail, try again.
05-19 12:12:04.812 10113 10113 I [SC]Utils: folder : cache create fail.
,05-19 12:12:04.812 10113 10113 I [SC]Utils: folder : thumbnailcreate fail, try again.
05-19 12:12:04.812 10113 10113 I [SC]Utils: folder : thumbnail create fail.
05-19 12:12:04.812 10113 10113 I [SC]Utils: folder : sharecreate fail, try again.
05-19 12:12:04.812 10113 10113 I [SC]Utils: folder : share create fail.
05-19 12:12:04.812 10113 10113 I [SC]Utils: folder : scratchcreate fail, try again.
,05-19 12:12:04.812 10113 10113 I [SC]Utils: folder : scratch create fail.
,05-19 12:12:04.822 10113 10113 I [SC]Utils: folder : eventSynccreate fail, try again.
05-19 12:12:04.822 10113 10113 I [SC]Utils: folder : eventSync create fail.
,05-19 12:12:04.842 10113 10113 V SamsungCloudLogs:  set Log level [4->4]act[false]
,05-19 12:12:04.842 10113 10113 I [SC]CommonUtil: isSemAvailable:0
,05-19 12:12:04.852 10113 10113 I [SC]SamsungCloudApp: AppVer[2.1.14][L:4]Sem[false]V21MAIN_R slog[false]com.samsung.android.scloud:contentsync
,05-19 12:12:04.852 10113 10113 D InjectionManager: InjectionManager
05-19 12:12:04.852 10113 10113 D InjectionManager: fillFeatureStoreMap com.samsung.android.scloud
05-19 12:12:04.852 10113 10113 I InjectionManager: Constructor com.samsung.android.scloud, Feature store :{}
,05-19 12:12:04.852 10113 10113 I InjectionManager: featureStore :{}
,05-19 12:12:04.852 10113 10113 I [SC]FeatureManager: FeatureManager 
05-19 12:12:04.852 10113 10113 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_CONFIG_CLOUD_USAGE_MENU_TREE]str 
05-19 12:12:04.852 10113 10113 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_ENABLE_SETTING_MENU]bln true
,05-19 12:12:04.852 10113 10113 E [SC]SCLOUD_ERR-Utils: isShipMode : 1 
,05-19 12:12:04.862 10113 10113 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
05-19 12:12:04.862 10113 10113 I [SC]CloudManager: requestInit
05-19 12:12:04.862 10113 10113 I [SC]Utils: folder : cachecreate fail, try again.
,05-19 12:12:04.862 10113 10113 I [SC]Utils: folder : cache create fail.
05-19 12:12:04.862 10113 10113 I [SC]Utils: folder : thumbnailcreate fail, try again.
05-19 12:12:04.862 10113 10113 I [SC]Utils: folder : thumbnail create fail.
05-19 12:12:04.862 10113 10113 I [SC]Utils: folder : sharecreate fail, try again.
05-19 12:12:04.862 10113 10113 I [SC]Utils: folder : share create fail.
05-19 12:12:04.862 10113 10113 I [SC]Utils: folder : scratchcreate fail, try again.
,05-19 12:12:04.862 10113 10113 I [SC]Utils: folder : scratch create fail.
05-19 12:12:04.862 10113 10113 I [SC]Utils: folder : eventSynccreate fail, try again.
05-19 12:12:04.862 10113 10113 I [SC]Utils: folder : eventSync create fail.
,05-19 12:12:04.882 10022 10033 I SA      : [SCU] isHaveSA() - false
05-19 12:12:04.882 10022 10033 I SA      : [OCP] Samsung account is not Signed-in
,05-19 12:12:04.882 10022 10033 I SA      : [OCP] Delete DB (TNC data)
,05-19 12:12:04.892 10113 10113 I [SC]CommonUtil: Samsung Account Not Logged in
,05-19 12:12:04.892  3510  4427 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:04.892  3510  4312 I ActivityManager: Killing 9133:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #33
,05-19 12:12:04.952 10141 10141 E Zygote  : v2
05-19 12:12:04.952 10141 10141 I libpersona: KNOX_SDCARD checking this for 5011
05-19 12:12:04.952 10141 10141 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:04.952 10141 10141 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:04.952  3510  4427 I ActivityManager: Start proc 10141:com.samsung.android.coreapps/5011 for broadcast-5 com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener
05-19 12:12:04.952 10141 10141 E Zygote  : accessInfo : 0
,05-19 12:12:04.952 10141 10141 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.coreapps 
,05-19 12:12:04.962  3510  3530 D ActivityManager: cleanUpApplicationRecord -- 9133
,05-19 12:12:04.972  3510  3530 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
05-19 12:12:04.972  3510  3858 D WifiP2pService: InactiveState{ what=143375 }
,05-19 12:12:04.972  3510  3858 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-19 12:12:04.972  3510  3869 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-19 12:12:04.982  3510  3860 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,05-19 12:12:04.982  3510  3860 D WifiStateMachine: VerifyingLinkState enter
05-19 12:12:04.982  3510  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
,05-19 12:12:04.982  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:12:04.992 10141 10141 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-19 12:12:04.992 10141 10141 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:04.992  3510  3869 E ConnectivityService: updateNetworkInfo()
05-19 12:12:04.992  3510  3510 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
05-19 12:12:04.992  3510  3869 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}, oldLp = null
05-19 12:12:04.992  3510  3869 D ConnectivityService: Adding iface wlan0 to network 503
05-19 12:12:04.992  4163  4173 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
,05-19 12:12:05.002  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
05-19 12:12:05.002  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 12:12:05.002  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 12:12:05.002  4163  4163 I PeopleDataManager: removeNotification
05-19 12:12:05.002  4163  4163 I NotificationParser: getNotiType:android,null
,05-19 12:12:05.002  4163  4163 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 12:12:05.002  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-19 12:12:05.012  3510  4409 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ac9604 10141:com.samsung.android.coreapps/5011}
,05-19 12:12:05.012  3510  3510 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-19 12:12:05.012  3510  3510 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 12:12:05.012  3510  3510 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-19 12:12:05.012  3510  3867 I WifiHs20Service: Message received 5007
,05-19 12:12:05.012  3510  3510 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-19 12:12:05.022  3510  3886 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,05-19 12:12:05.022  3510  3886 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-19 12:12:05.022  3510  3886 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,05-19 12:12:05.022  3510  3886 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-19 12:12:05.022  3510  3886 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,05-19 12:12:05.022  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:12:05.022  3510  3869 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,05-19 12:12:05.022  4288  4288 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
05-19 12:12:05.022  3510  3869 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,05-19 12:12:05.032 10141 10141 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:05.032 10141 10141 D RelationGraph: garbageCollect()
05-19 12:12:05.032  3510  3869 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,05-19 12:12:05.032  3510  3869 E ConnectivityService: Unexpected mtu value: 0, wlan0
,05-19 12:12:05.032 10141 10141 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.samsung.android.coreapps
05-19 12:12:05.032  3510  3869 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,05-19 12:12:05.032  3510  3530 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 12:12:05.032 10141 10141 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:05.042  3510  3886 I WifiManager: isCaptivePortalException
,05-19 12:12:05.042 10141 10141 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:05.042  3510  3869 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:05.042  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84947ed u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{226b6b 9931:com.sec.android.diagmonagent/1000}
05-19 12:12:05.042  9931  9931 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-19 12:12:05.042  3510  3869 V NetworkStats: updateIfacesLocked()
05-19 12:12:05.042  3510  3869 V NetworkStats: performPollLocked(flags=0x1)
,05-19 12:12:05.042  9931  9931 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:,
05-19 12:12:05.042  9931  9931 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-19 12:12:05.042  9931  9931 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
05-19 12:12:05.042  3510  3869 D NetworkStatsRecorder: entry.iface is null
05-19 12:12:05.042  3510  3869 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:05.042  3510  3869 D NetworkStatsRecorder: entry.iface is null
,05-19 12:12:05.042  3510  3869 D NetworkStatsRecorder: entry.iface is null
05-19 12:12:05.042  3510  3869 D NetworkStatsRecorder: entry.iface is null
05-19 12:12:05.042  3510  3869 V NetworkStats: performPollLocked() took 6ms
,05-19 12:12:05.062 10141 10141 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:05.062  3510  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84947ed u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{332c515 6617:com.enhance.gameservice/u0a111}
,05-19 12:12:05.072 10141 10141 W System  : ClassLoader referenced unknown path: /system/app/CoreApps/lib/arm64
,05-19 12:12:05.072  3510  3886 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 12:12:05.072  3510  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:05.072  3510  3886 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 12:12:05.072  3510  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
05-19 12:12:05.072  3510  3886 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
05-19 12:12:05.072  3510  3869 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-19 12:12:05.072  3510  3886 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {1a87266}
05-19 12:12:05.072  3510  3869 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
05-19 12:12:05.072  3510  3886 I WifiManager: isCaptivePortalException
05-19 12:12:05.072  3510  3869 D ConnectivityService: Not required to send intent.
,05-19 12:12:05.072  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:05.072  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:05.072  3510  3886 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 12:12:05.072  3510  3886 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-19 12:12:05.082  3510  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84947ed u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{64e8361 9944:com.sec.knox.switcher/1000}
,05-19 12:12:05.082  9944  9944 I usagelog: received in receiver
05-19 12:12:05.082  9944  9944 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-19 12:12:05.082  9944  9944 I KnoxUsageLogPro: premStatus:2
,05-19 12:12:05.082  9944  9944 I KnoxUsageLogPro: isEulaShown : false
05-19 12:12:05.082  9944  9944 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-19 12:12:05.082 10141 10141 D CoreApps: SEC_LOG - true
,05-19 12:12:05.092  3510  3860 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,05-19 12:12:05.102  3510  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84947ed u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97bae86 9956:com.samsung.android.sm.policy/u0a142}
,05-19 12:12:05.102  3510  3860 D SecContentProvider: insert(), uri = 2
,05-19 12:12:05.102  3510  3869 E ConnectivityService: updateNetworkInfo()
,05-19 12:12:05.102  3510  3510 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
05-19 12:12:05.112  4163  7409 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
,05-19 12:12:05.112  3510  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
05-19 12:12:05.112  3510  3869 D NtpTrustedTime: currentTimeMillis() cache hit
,05-19 12:12:05.112  3510  3869 V NetworkStats: updateIfacesLocked()
05-19 12:12:05.112  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
,05-19 12:12:05.112  3510  3869 V NetworkStats: performPollLocked(flags=0x1)
05-19 12:12:05.112  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
,05-19 12:12:05.112  3510  3869 D NetworkStatsRecorder: entry.iface is null
05-19 12:12:05.112  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 12:12:05.112  3510  3869 D NetworkStatsRecorder: entry.iface is null
05-19 12:12:05.112  4163  4163 I PeopleDataManager: removeNotification
,05-19 12:12:05.112  3510  3869 D NetworkStatsRecorder: entry.iface is null
05-19 12:12:05.112  4163  4163 I NotificationParser: getNotiType:android,null
05-19 12:12:05.112  3510  3869 D NetworkStatsRecorder: entry.iface is null
05-19 12:12:05.112  4163  4163 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 12:12:05.112  3510  3869 V NetworkStats: performPollLocked() took 7ms
05-19 12:12:05.112  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-19 12:12:05.122  3510  3510 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
05-19 12:12:05.112  3510  3860 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,05-19 12:12:05.112  3510  3510 I WifiTrafficPoller: evaluateTrafficStatsPolling
05-19 12:12:05.112  3510  3860 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
05-19 12:12:05.112  3510  3510 D WifiNative-wlan0: callSECApiVoid - ID [212]
05-19 12:12:05.112  3510  3869 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:05.112  9930  9930 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
05-19 12:12:05.112  9930  9930 I wpa_supplicant: P2P: Current p2p state = IDLE
05-19 12:12:05.122  9930  9930 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,05-19 12:12:05.122  3510  3510 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-19 12:12:05.122  3510  3510 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.122  3510  3510 D HS20StateMachine: SSID : "NG700"
05-19 12:12:05.122  3510  3510 D HS20StateMachine: NetId : 0
05-19 12:12:05.122  3510  3510 D HS20StateMachine: checkifOSUAP  null
05-19 12:12:05.122  3510  3510 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-19 12:12:05.122  3510  3867 I WifiHs20Service: Message received 5007
,05-19 12:12:05.122  4288  4288 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-19 12:12:05.122  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:12:05.132  3510  3530 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,05-19 12:12:05.132  3510  4983 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,05-19 12:12:05.132  3510  3975 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d2928b3 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{226b6b 9931:com.sec.android.diagmonagent/1000}
,05-19 12:12:05.132  9931  9931 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-19 12:12:05.132  9931  9931 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-19 12:12:05.132  9931  9931 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-19 12:12:05.142  3510  4947 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
05-19 12:12:05.142  9931  9931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3635 
,05-19 12:12:05.142  3510  4406 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,05-19 12:12:05.142  3510  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:05.142  3510 10097 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
05-19 12:12:05.142  3510  3869 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
05-19 12:12:05.142  3510  3860 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
05-19 12:12:05.142  3510  3869 D ConnectivityService: scheduleUnvalidatedPrompt 503
05-19 12:12:05.142  3510 10097 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
,05-19 12:12:05.142  3510  3869 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
05-19 12:12:05.142  3510 10097 D NetworkMonitor: registerReceiver Captive portal receiver
05-19 12:12:05.142  3510  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
05-19 12:12:05.142  3510 10097 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
05-19 12:12:05.142  3510  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-19 12:12:05.142  3510 10097 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
05-19 12:12:05.142  3510  3860 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
05-19 12:12:05.142  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:05.142  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-19 12:12:05.152 10141 10141 E GooglePlayServicesUtil: The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,05-19 12:12:05.152  3510  3869 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-19 12:12:05.152  3510  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d2928b3 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{332c515 6617:com.enhance.gameservice/u0a111}
05-19 12:12:05.152  4288  4299 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-19 12:12:05.152  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
05-19 12:12:05.152  4288  4299 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-19 12:12:05.152  3510  3869 D ConnectivityService: currentScore = 0, newScore = 20
05-19 12:12:05.152  3510  3869 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
05-19 12:12:05.152  3510  3869 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
05-19 12:12:05.152  3510  3858 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.152  3510  3869 D ConnectivityService:    accepting network in place of null
05-19 12:12:05.152  3510  3858 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,05-19 12:12:05.152  3510  3869 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.152  3510  3895 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.152  3510  3858 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 12:12:05.152  3510  3858 D WIFI_P2P: evalRequest
05-19 12:12:05.152  3510  3858 D WIFI_P2P:   done
05-19 12:12:05.152  3510  3895 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-19 12:12:05.152  3510  3895 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 12:12:05.152  3510  3895 D Ethernet: evalRequest
05-19 12:12:05.152  3510  3895 D Ethernet:   done
,05-19 12:12:05.162  3510  3860 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.162  3510  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:05.162  3510  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 12:12:05.162  3510  3860 D WIFI    : evalRequest
05-19 12:12:05.162  3510  3860 D WIFI    :   done
,05-19 12:12:05.162  3510  3860 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.162  3510  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:05.162  3510  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 12:12:05.162  3510  3860 D WIFI    : evalRequest
05-19 12:12:05.162  3510  3860 D WIFI    :   done
,05-19 12:12:05.162  3510  3860 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.162  3510  3860 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:05.162  3510  3860 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 12:12:05.162  3510  3860 D WIFI_UT : evalRequest
05-19 12:12:05.162  3510  3860 D WIFI_UT :   done
05-19 12:12:05.162  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-19 12:12:05.172  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
05-19 12:12:05.172  3942  4148 D ViewRootImpl: #1 mView = android.widget.LinearLayout{eb46d75 V.E...... ......I. 0,0-0,0 #102039c android:id/toast_layout_root}
05-19 12:12:05.172  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-19 12:12:05.192  3942  3942 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
05-19 12:12:05.192  3510  4518 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d2928b3 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{64e8361 9944:com.sec.knox.switcher/1000}
05-19 12:12:05.192  9944  9944 I usagelog: received in receiver
05-19 12:12:05.192  9944  9944 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-19 12:12:05.192  9944  9944 I KnoxUsageLogPro: premStatus:2
,05-19 12:12:05.202  9944  9944 I KnoxUsageLogPro: isEulaShown : false
05-19 12:12:05.202  9944  9944 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
05-19 12:12:05.202  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-19 12:12:05.212  3510  4407 D ISSUE_DEBUG: InputChannelName : 6bc377a Toast
05-19 12:12:05.212  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-19 12:12:05.212  3510  4518 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d2928b3 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97bae86 9956:com.samsung.android.sm.policy/u0a142}
05-19 12:12:05.222  3510  4407 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
05-19 12:12:05.232  3015  3015 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=4, Uoast
,05-19 12:12:05.242  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-19 12:12:05.242  3510  3869 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-19 12:12:05.252  3510  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fa23b88 u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{226b6b 9931:com.sec.android.diagmonagent/1000}
,05-19 12:12:05.252  9931  9931 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
,05-19 12:12:05.252  9931  9931 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-19 12:12:05.252  9931  9931 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,05-19 12:12:05.262  3510  3906 D lights  : lcd : 40 +
05-19 12:12:05.262  3510  4983 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3510
05-19 12:12:05.262  3510  4983 D PowerManagerService: mDisplayReady: false
05-19 12:12:05.262  3510  3612 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 12:12:05.262  3510  3612 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-19 12:12:05.262  3510  3612 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
05-19 12:12:05.262  3510  3612 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
05-19 12:12:05.262  3510  3612 D DisplayPowerController: Tracking Direct to etc : 40
05-19 12:12:05.262  3510  3612 D DisplayPowerController: Animating brightness: target=40, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
05-19 12:12:05.262  3510  3612 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 12:12:05.262  3510  3612 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-19 12:12:05.262  3510  3612 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
05-19 12:12:05.262  3510  3612 D DisplayPowerController: Animating brightness: target=40, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
05-19 12:12:05.262  3510  3612 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
05-19 12:12:05.262  3510  3612 D PowerManagerService: mDisplayReady: true
,05-19 12:12:05.272  3510  3906 D lights  : lcd : 40 -
05-19 12:12:05.272  3510  3906 D DisplayPowerState: Tracking!!: 40
05-19 12:12:05.272  3510  3906 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
,05-19 12:12:05.282  3510  3612 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 12:12:05.282  3510  3612 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-19 12:12:05.282  3510  3612 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
05-19 12:12:05.282  3510  3612 D DisplayPowerController: Animating brightness: target=40, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,05-19 12:12:05.282  3158  3625 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-19 12:12:05.282  3942  4128 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1033x201]-format:1
,05-19 12:12:05.292  3942  4148 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,05-19 12:12:05.302  3942  4148 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,05-19 12:12:05.302  3158  3625 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-19 12:12:05.312  3510  3869 D ConnectivityService: 503 network ip type : v4
,05-19 12:12:05.312  3510  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:05.312  3510  4409 V WindowStateAnimator: Finishing drawing window Window{6bc377a u0 d0 Toast}: mDrawState=DRAW_PENDING
05-19 12:12:05.312  3510  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.312  3015  3015 D libEGL  : eglInitialize EGLDisplay = 0x7ffcdd1c68
,05-19 12:12:05.312  3510  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.312  3510  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:05.322  3510  3869 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-19 12:12:05.322  3510  3609 D EntConnectivity: Not allowed due to - mEnabled false
,05-19 12:12:05.322  3510  3869 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1,
05-19 12:12:05.322  3510  3869 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,05-19 12:12:05.332  3510  3869 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,05-19 12:12:05.332  3510  3854 D ConnectivityService: getVpnConfig > userId : 0
,05-19 12:12:05.342  3510  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-19 12:12:05.342  3510  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-19 12:12:05.342  3510  3869 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3510 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.342  3510  3869 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
05-19 12:12:05.342  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.342  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.342  3510  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.342  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-19 12:12:05.342  3510  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
05-19 12:12:05.342  3510  3609 D EntConnectivity: Not allowed due to - mEnabled false
05-19 12:12:05.342  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.342  3510  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.342  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.352  3510  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.352  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.352  3510  3869 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.352  3510  3869 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
05-19 12:12:05.352  3510  3869 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation  passed
05-19 12:12:05.352  3510  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
05-19 12:12:05.352  3510  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
05-19 12:12:05.352  3510  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-19 12:12:05.352  4163  4173 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=503,extra=Bundle[mParcelledData.dataSize=84]
05-19 12:12:05.352  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=503, samsung.notification.type=normal, samsung.people.package_name=android}]
05-19 12:12:05.352  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 12:12:05.352  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 12:12:05.352  4163  4163 I PeopleDataManager: removeNotification
05-19 12:12:05.352  4163  4163 I NotificationParser: getNotiType:android,null
05-19 12:12:05.352  4163  4163 D PeopleDataManager: removeNotiInfo: id =503,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-19 12:12:05.352  4163  4163 D PeopleDataManager: removeNotiInfo =null
05-19 12:12:05.362  3510  3510 D Tethering: Tethering got CONNECTIVITY_ACTION
05-19 12:12:05.362  3510  3609 D Tethering: MasterInitialState.processMessage what=3
05-19 12:12:05.362  3510  3510 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.362  3510  3510 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
05-19 12:12:05.362  3510  3510 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.362  3510  3510 I CLocInfoService: CLocinfo wifi true 
05-19 12:12:05.372  3510  3871 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-19 12:12:05.372  4288  4299 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-19 12:12:05.372  4288  4299 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-19 12:12:05.372  3510  3871 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
05-19 12:12:05.372  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 12:12:05.372  3510  3594 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
05-19 12:12:05.372  3510  3594 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.372  3510  3594 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.372  3510  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
05-19 12:12:05.372  3510  4236 V AlarmManager:  remove PendingIntent] PendingIntent{22c613b: PendingIntentRecord{1279058 android broadcastIntent}}
,05-19 12:12:05.392  3510  3510 V MARsPolicyManager: DataConnection: true
05-19 12:12:05.392  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-19 12:12:05.392  4814  4814 D SamsungIME: EngineType = SWIFTKEY
05-19 12:12:05.392  5067  5141 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
05-19 12:12:05.392  5067  5141 I CellLocationSupport: onCellLocationChanged
05-19 12:12:05.402  3510  3890 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
05-19 12:12:05.402  4814  4814 D SamsungIME: mNetworkChangeReceiver isWLANConnected : true
05-19 12:12:05.412  5067  5067 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected true
05-19 12:12:05.412  5067  5067 D PdnController: isSuspended [false] networktype [1]
05-19 12:12:05.412  5067  5067 D PdnController: Updated Interface [wlan0] For Network [1]
05-19 12:12:05.412  3510  3854 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.412  5067  5067 D PdnController: isPdnUp  [true] networktype [1]
05-19 12:12:05.412  5067  5067 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [true] 
,05-19 12:12:05.422  5067  5141 I CellLocationSupport: Block to update PANI information in non VoWIFI
05-19 12:12:05.422  5067  5141 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
05-19 12:12:05.422  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-19 12:12:05.422  3510  4313 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.422  5067  5141 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
05-19 12:12:05.422  5067  5141 D PdnController: isPdnUp  [false] networktype [0]
05-19 12:12:05.422  5067  5141 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,05-19 12:12:05.432  5444  5444 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@4a0cc29 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 12:12:05.432  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:05.432  3510  3857 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:05.432  3510  3857 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
,05-19 12:12:05.432  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:05.432  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:05.432  3510  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-19 12:12:05.432  3510  3857 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,05-19 12:12:05.442  5444  5444 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,05-19 12:12:05.452  5067  5141 D RegistrationManager: handleMessage(): 5
,05-19 12:12:05.452  3510  4312 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:05.452  5067  5141 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
05-19 12:12:05.452  5067  5141 D PdnController: isPdnUp  [false] networktype [11]
05-19 12:12:05.452  5067  5141 D RegistrationManager: setEPDGIPSecConnected [false]
05-19 12:12:05.452  5067  5141 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [true] IPAddresses [[/192.168.1.107]] DNSAddresses [[/192.168.1.1]] 
05-19 12:12:05.452  5067  5141 D RegistrationManager: isEPDGAvailable [false]
05-19 12:12:05.452  5067  5141 D RegistrationManager: setWifiPreparedOnAPM [true]
,05-19 12:12:05.462  3510  4235 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.462  4288  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-19 12:12:05.462  4288  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-19 12:12:05.462  3510  4518 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 12:12:05.462  6976  6976 I FOTA_AGENT: [lIlIIlIlIlIllllllIII(91/llllIIIllIlIIIIllllI)] WiFi Network is connected
,05-19 12:12:05.472  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 12:12:05.472  9321  9321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
,05-19 12:12:05.482  3510  4518 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 12:12:05.482  4226  4226 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with b729f9d , interval = 1800000 through LocationManagerService
,05-19 12:12:05.492  3510  3594 D TelephonyManager: getDataEnabled: retVal=true
,05-19 12:12:05.512  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 12:12:05.522  3158  3621 D EnterpriseController: netId is 0
05-19 12:12:05.522  3158  3621 D Netd    : getNetworkForDns: using netid 503 for uid 10002
,05-19 12:12:05.532  5067  5141 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-19 12:12:05.532  5067  5141 D RegistrationManager: getNetworkType [0]
05-19 12:12:05.532  5067  5141 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [true] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
05-19 12:12:05.532  5067  5141 D CellLocationSupport: Siso Stack not called RegisterAN yet on XAN_NWK_TYPE_WLAN
05-19 12:12:05.532  4437  4437 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-19 12:12:05.532  5067  5141 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-19 12:12:05.532  3510  3521 I art     : Background sticky concurrent mark sweep GC freed 167233(12MB) AllocSpace objects, 65(1300KB) LOS objects, 29% free, 35MB/50MB, paused 3.324ms total 105.437ms
05-19 12:12:05.532  5067  5141 D CoreStackAdaptor2: ipList Not Null[/192.168.1.107]
05-19 12:12:05.532  5067  5141 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
05-19 12:12:05.532  5067  5141 D RegistrationManager: isPreconditionProperToGoOn
05-19 12:12:05.532  5067  5141 D RegistrationManager: isDeviceShutdown [false]
05-19 12:12:05.532  5067  5141 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
05-19 12:12:05.532  5067  5141 D RegistrationManager: isDmVoLTEUpdated [false]
05-19 12:12:05.532  5067  5141 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
05-19 12:12:05.532  5067  5141 D RegistrationManager: tryRegister : Not all preconditions are met!
,05-19 12:12:05.542 10141 10141 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.android.mms
05-19 12:12:05.542  9666  9666 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-19 12:12:05.552 10141 10141 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:05.552  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 12:12:05.562  3510  6262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-19 12:12:05.572  3510  3889 D WifiWatchdogStateMachine: response code : 204
,05-19 12:12:05.572  3510  3890 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,05-19 12:12:05.582 10141 10141 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.google.android.talk
,05-19 12:12:05.582  9993 10004 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-19 12:12:05.592  9993 10004 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-19 12:12:05.592  9993 10004 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
05-19 12:12:05.592 10141 10141 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:05.602  5027  5027 E audit   : type=1400 msg=audit(1495188725.602:278): avc:  denied  { ioctl } for  pid=7156 comm="ChromiumNet" path="socket:[37257]" dev="sockfs" ino=37257 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
05-19 12:12:05.602  5027  5027 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-19 12:12:05.602  5027  5027 E audit   : type=1300 msg=audit(1495188725.602:278): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f66483cc8 a3=7f66483c90 items=0 ppid=3182 pid=7156 auid=4294967295 uid=10072 gid=10072 euid=10072 suid=10072 fsuid=10072 egid=10072 sgid=10072 fsgid=10072 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-19 12:12:05.602  5027  5027 E audit   : type=1327 msg=audit(1495188725.602:278): proctitle="com.google.android.googlequicksearchbox:search"
05-19 12:12:05.602  5027  5027 E audit   : type=1320 msg=audit(1495188725.602:278): 
05-19 12:12:05.602  5027  5027 E audit   : type=1400 msg=audit(1495188725.602:279): avc:  denied  { ioctl } for  pid=7156 comm="ChromiumNet" path="socket:[37258]" dev="sockfs" ino=37258 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
05-19 12:12:05.602  5027  5027 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-19 12:12:05.602  5027  5027 E audit   : type=1300 msg=audit(1495188725.602:279): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f66483cc8 a3=7f66483c90 items=0 ppid=3182 pid=7156 auid=4294967295 uid=10072 gid=10072 euid=10072 suid=10072 fsuid=10072 egid=10072 sgid=10072 fsgid=10072 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-19 12:12:05.602  5027  5027 E audit   : type=1327 msg=audit(1495188725.602:279): proctitle="com.google.android.googlequicksearchbox:search"
05-19 12:12:05.602  5027  5027 E audit   : type=1320 msg=audit(1495188725.602:279): 
,05-19 12:12:05.612  9993 10003 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
05-19 12:12:05.612  9993 10003 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
05-19 12:12:05.612  9993 10003 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,05-19 12:12:05.612  9666  9666 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-19 12:12:05.622  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-19 12:12:05.622  3510  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-19 12:12:05.622  3510  3869 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-19 12:12:05.622  3510  3869 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3510 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.622  3510  3869 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-19 12:12:05.622  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.622  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.622  3510  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.622  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-19 12:12:05.622  3510  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-19 12:12:05.622  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:05.622  3510  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.622 10141 10141 D InjectionManager: InjectionManager
,05-19 12:12:05.622 10141 10141 D InjectionManager: fillFeatureStoreMap com.samsung.android.coreapps
,05-19 12:12:05.622  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.622  3510  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:05.632  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:05.632  3510  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:05.642 10141 10141 I InjectionManager: Constructor com.samsung.android.coreapps, Feature store :{}
05-19 12:12:05.642 10141 10141 I InjectionManager: featureStore :{}
,05-19 12:12:05.642  3510  3858 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.642  3510  3869 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.642  3510  3860 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.642  3510  3858 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:05.642  3510  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:05.642  3510  3858 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 12:12:05.642  3510  3858 D WIFI_P2P: evalRequest
05-19 12:12:05.642  3510  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-19 12:12:05.642  3510  3858 D WIFI_P2P:   done
,05-19 12:12:05.642  3510  3860 D WIFI    : evalRequest
05-19 12:12:05.642  3510  3860 D WIFI    :   done
05-19 12:12:05.642  3510  3860 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.642  3510  3860 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:05.642  3510  3860 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,05-19 12:12:05.642  3510  3860 D WIFI    : evalRequest
05-19 12:12:05.642  3510  3860 D WIFI    :   done
05-19 12:12:05.642  3510  3860 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:05.642  3510  3860 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-19 12:12:05.642  3510  3860 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,05-19 12:12:05.642  3510  3860 D WIFI_UT : evalRequest
05-19 12:12:05.642  3510  3860 D WIFI_UT :   done
05-19 12:12:05.642  3510  3895 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:05.642  3510  3895 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-19 12:12:05.642  3510  3895 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-19 12:12:05.642  3510  3895 D Ethernet: evalRequest
05-19 12:12:05.642  3510  3895 D Ethernet:   done
05-19 12:12:05.642 10186 10186 I libpersona: KNOX_SDCARD checking this for 1000
05-19 12:12:05.642 10186 10186 E Zygote  : v2
05-19 12:12:05.642 10186 10186 I libpersona: KNOX_SDCARD not a persona
05-19 12:12:05.642  3510  3869 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
05-19 12:12:05.642 10186 10186 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:05.652 10186 10186 E Zygote  : accessInfo : 0
,05-19 12:12:05.652  3510  4947 I ActivityManager: Start proc 10186:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
,05-19 12:12:05.662  3510  3860 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
05-19 12:12:05.662  3510  3860 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,05-19 12:12:05.662  3510  3860 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 12:12:05.662  3510  3860 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 12:12:05.662  3510  3860 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-19 12:12:05.672  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:12:05.672  3510  3860 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-19 12:12:05.672  3510  3860 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-19 12:12:05.672  4288  4613 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@79349e9, selection=nullselectionArgs=null, sort=name ASC
,05-19 12:12:05.682  9666  9666 D BluetoothAdapter: STATE_ON
,05-19 12:12:05.692  3942  4148 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-19 12:12:05.692  3942  4148 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,05-19 12:12:05.692  9666  9666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-19 12:12:05.692  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-19 12:12:05.692  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-19 12:12:05.692  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-19 12:12:05.692  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-19 12:12:05.692  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-19 12:12:05.692  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-19 12:12:05.692  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-19 12:12:05.692  9666  9666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-19 12:12:05.692  4288  4613 D TelephonyProvider: query: match = 5
,05-19 12:12:05.692  4288  4613 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
05-19 12:12:05.692  4288  4613 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
05-19 12:12:05.702  9666  9666 D BluetoothAdapter: STATE_ON
,05-19 12:12:05.712 10186 10186 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:05.712 10186 10186 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:05.722  9666  9666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-19 12:12:05.722  3510  4427 D ActivityManager:  getDeferredInfo final delay 420
,05-19 12:12:05.752  3510  3594 E GpsLocationProvider: No APN found to select.
,05-19 12:12:05.762 10186 10186 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:05.762 10186 10186 D RelationGraph: garbageCollect()
,05-19 12:12:05.772 10186 10186 W ResourcesManager: getTopLevelResources: /system/priv-app/SOAgent/SOAgent.apk / 1.0 running in com.sec.android.soagent rsrc of package com.sec.android.soagent
,05-19 12:12:05.772  3510  3530 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 12:12:05.772 10186 10186 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:05.782 10186 10186 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:05.782  3510  3594 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,05-19 12:12:05.782 10186 10186 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:05.792 10186 10186 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,05-19 12:12:05.812 10186 10186 D InjectionManager: InjectionManager
05-19 12:12:05.812 10186 10186 D InjectionManager: fillFeatureStoreMap com.sec.android.soagent
,05-19 12:12:05.812 10186 10186 I InjectionManager: Constructor com.sec.android.soagent, Feature store :{}
05-19 12:12:05.812 10186 10186 I InjectionManager: featureStore :{}
,05-19 12:12:05.832  3510  4312 I ActivityManager: Killing 9388:com.samsung.android.themecenter/1000 (adj 15): DHA:empty #33
,05-19 12:12:05.832  3510  4312 I ActivityManager: Killing 9376:com.samsung.android.app.taskedge/u0a67 (adj 15): DHA:empty #33
,05-19 12:12:05.842  3510  4312 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e943933 9666:com.rockwellautomation.thalitest/u0a78}
,05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true],
,05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:05.852  3510  4947 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-19 12:12:05.882  3510  4983 D ActivityManager: cleanUpApplicationRecord -- 9376
,05-19 12:12:05.882  3510  4983 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.taskedge, Auto Run ON
,05-19 12:12:05.892  3510  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{38ffe8f 3510:system/1000}
,05-19 12:12:05.902  3510  4313 D ActivityManager: cleanUpApplicationRecord -- 9388
,05-19 12:12:05.902  3510  4313 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themecenter, Auto Run ON
,05-19 12:12:05.922  3510  3510 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d14e56 4659:com.google.android.gms/u0a21}
,05-19 12:12:05.922  4659  4659 E MDM     : [1] SitrepService.a: No Google accounts; deferring server state update.
,05-19 12:12:05.932  3510  4312 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.mdm.receivers.ConnectivityReceiver newState = 2 callingPackage = 10021
,05-19 12:12:05.942  3510  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d14e56 4659:com.google.android.gms/u0a21}
,05-19 12:12:05.942  4659  4659 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,05-19 12:12:05.952  4659  5658 I iu.UploadsManager: num queued entries: 0
,05-19 12:12:05.952  4659  5658 I iu.UploadsManager: num updated entries: 0
,05-19 12:12:05.952  4659  5658 I iu.SyncManager: NEXT; no task
,05-19 12:12:05.952  3510  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d14e56 4659:com.google.android.gms/u0a21}
,05-19 12:12:05.962  3510  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{feb16e 4341:com.google.android.gms.persistent/u0a21}
,05-19 12:12:05.982  3158  3621 D EnterpriseController: netId is 0
05-19 12:12:05.982  3158  3621 D Netd    : getNetworkForDns: using netid 503 for uid 10021
,05-19 12:12:06.052  9877  9877 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,05-19 12:12:06.052  3510  4409 I ActivityManager: Killing 9401:com.samsung.android.scloud/5009 (adj 15): DHA:empty #33
,05-19 12:12:06.082  3510  4983 D ActivityManager: cleanUpApplicationRecord -- 9401
,05-19 12:12:06.082  3510  4983 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,05-19 12:12:06.132  3510  3628 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,05-19 12:12:06.142  3510  3598 D ActivityManager:  getDeferredInfo final delay 420
,05-19 12:12:06.152  3510  3628 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,05-19 12:12:06.322  3510  3869 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,05-19 12:12:06.562  3510  3598 D ActivityManager:  getDeferredInfo final delay 120
,05-19 12:12:06.732  3510  3598 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:06.742  3510  3598 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ac9604 10141:com.samsung.android.coreapps/5011}
,05-19 12:12:06.762  3510  3530 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:06.772  3510  3530 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ac9604 10141:com.samsung.android.coreapps/5011}
,05-19 12:12:06.782  3510  3530 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:06.782  3510  3594 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
05-19 12:12:06.782  3510  3594 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
,05-19 12:12:06.782  3510  3594 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
05-19 12:12:06.782  3510  3594 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
05-19 12:12:06.782  3510  3530 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a87173 4846:com.microsoft.skydrive/u0a130}
,05-19 12:12:06.802  3510  4313 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,05-19 12:12:06.802  3510  4947 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:06.862  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eaba415 u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4164f92 9877:com.google.android.talk/u0a117}
,05-19 12:12:06.862  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{851732a: PendingIntentRecord{e0901b com.google.android.gms broadcastIntent}}
,05-19 12:12:07.102  3510  3598 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:07.122 10205 10205 E Zygote  : v2
05-19 12:12:07.122 10205 10205 I libpersona: KNOX_SDCARD checking this for 10135
05-19 12:12:07.122 10205 10205 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:07.132 10205 10205 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-19 12:12:07.132  3510  3598 I ActivityManager: Start proc 10205:com.google.android.apps.photos/u0a135 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,05-19 12:12:07.132  3510  3857 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,05-19 12:12:07.132 10205 10205 E Zygote  : accessInfo : 0
05-19 12:12:07.132 10205 10205 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,05-19 12:12:07.162 10205 10205 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-19 12:12:07.162 10205 10205 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:07.182  3942  4148 D ViewRootImpl: #3 mView = null
,05-19 12:12:07.192  3510  3869 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -24]
05-19 12:12:07.192  3510  3869 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
05-19 12:12:07.192  3510  4409 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3510) eventTime = 212762
,05-19 12:12:07.192  3510  4409 D PowerManagerService: [s] UserActivityState : 4 -> 1
05-19 12:12:07.192  3510  4409 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3510 (0x0)
05-19 12:12:07.192  3510  4409 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3510, ws=WorkSource{10065}) (elapsedTime=1929)
,05-19 12:12:07.192  3510  3869 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -24]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-19 12:12:07.202  3510  4040 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4af6c91 10205:com.google.android.apps.photos/u0a135}
05-19 12:12:07.202  3510  3857 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: true, uidstate: 11, mProxSensorScreenOff: false
,05-19 12:12:07.202  3510  3869 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,05-19 12:12:07.202  3942  4148 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-19 12:12:07.212  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 12:12:07.222  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
05-19 12:12:07.222 10205 10205 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:07.222 10205 10205 D RelationGraph: garbageCollect()
,05-19 12:12:07.222 10205 10205 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,05-19 12:12:07.222  3510  4947 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:12:07.222  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 12:12:07.232 10205 10205 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:07.232  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 12:12:07.232 10205 10205 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:07.242 10205 10205 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:07.242  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-19 12:12:07.252  3510  3869 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-19 12:12:07.252  3510  3869 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-19 12:12:07.252  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:07.252  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:07.252  3510  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:07.252  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,05-19 12:12:07.252  3510  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
05-19 12:12:07.252  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:07.252  3510  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:07.262  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:07.262  3510  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:07.262  3510  3869 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-19 12:12:07.262  3510  3869 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-19 12:12:07.262 10205 10205 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm64
,05-19 12:12:07.472 10205 10205 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,05-19 12:12:07.692 10205 10205 D InjectionManager: InjectionManager
,05-19 12:12:07.692 10205 10205 D InjectionManager: fillFeatureStoreMap com.google.android.apps.photos
,05-19 12:12:07.702 10205 10205 I InjectionManager: Constructor com.google.android.apps.photos, Feature store :{}
05-19 12:12:07.702 10205 10205 I InjectionManager: featureStore :{}
,05-19 12:12:07.712  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b5284d0 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4af6c91 10205:com.google.android.apps.photos/u0a135}
,05-19 12:12:07.732  3015  3024 I SurfaceFlinger: id=20 Removed Uoast (11/13)
,05-19 12:12:07.732  3015  3828 I SurfaceFlinger: id=20 Removed Uoast (-2/13)
,05-19 12:12:07.742  3015  3015 D libEGL  : eglTerminate EGLDisplay = 0x7ffcdd1d88
,05-19 12:12:07.752  3510  4059 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:07.762  3510  4059 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4af6c91 10205:com.google.android.apps.photos/u0a135}
,05-19 12:12:07.782  3510  4059 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{839afce u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4af6c91 10205:com.google.android.apps.photos/u0a135}
,05-19 12:12:07.792  3510  3594 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
05-19 12:12:07.792  3510  3594 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-19 12:12:07.792  3510  3594 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,05-19 12:12:07.802  3510  4059 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:07.822  3510  4406 I ActivityManager: Killing 9423:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #33
,05-19 12:12:07.832  4163  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.apps.photos,id=10436,extra=Bundle[mParcelledData.dataSize=84]
,05-19 12:12:07.832  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.apps.photos}]
05-19 12:12:07.832  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 12:12:07.832  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 12:12:07.832  4163  4163 I PeopleDataManager: removeNotification
05-19 12:12:07.832  4163  4163 I NotificationParser: getNotiType:com.google.android.apps.photos,null
05-19 12:12:07.832  4163  4163 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.apps.photos,isEdgeNotification=false,key=null,removeAll=false
05-19 12:12:07.832  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-19 12:12:07.842  3510  3529 D ActivityManager: cleanUpApplicationRecord -- 9423
,05-19 12:12:07.842  3510  3529 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,05-19 12:12:08.102  3510  3598 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:08.122  3510  3598 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3403c8 4722:com.sec.android.daemonapp/u0a166}
,05-19 12:12:08.132  4722  4722 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,05-19 12:12:08.132  4722  4722 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
05-19 12:12:08.132  3510  3854 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:08.142  3510  3854 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d4f08a2 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{38e7040 7981:com.sec.android.app.samsungapps/u0a16}
,05-19 12:12:08.152  7981  7981 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,05-19 12:12:08.172  7981  7981 D [SAUI]  : Global::recovered::false
,05-19 12:12:08.172  3510  4313 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:08.172  7981  7981 D [SAUI]  : AutoUpdateService::onStartCommand
05-19 12:12:08.172  7981  7981 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,05-19 12:12:08.172  7981  7981 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,05-19 12:12:08.172  7981  7981 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
05-19 12:12:08.172  7981  7981 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,05-19 12:12:08.182  7981  9180 D [SA_INIT]: createTaskForServiceInitialize()
,05-19 12:12:08.182  7981  9180 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,05-19 12:12:08.182  7981  9180 D [SA_INIT]: NetworkStateCheckUnit result : 1
,05-19 12:12:08.182  7981  7981 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 161483452_0] [END] FINISHED
05-19 12:12:08.182  7981  7981 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
05-19 12:12:08.182  7981  7981 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
,05-19 12:12:08.182  7981  7981 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,05-19 12:12:08.182  7981  7981 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,05-19 12:12:08.472  3510  3598 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:08.782 10099 10099 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-19 12:12:08.822  3510  3598 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:08.832  3510  3598 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ead09fa u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{226b6b 9931:com.sec.android.diagmonagent/1000}
,05-19 12:12:08.832  9931  9931 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-19 12:12:08.832  9931  9931 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-19 12:12:08.832  9931  9931 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-19 12:12:08.832  3510  4983 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:08.842  3510  4983 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ead09fa u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{64e8361 9944:com.sec.knox.switcher/1000}
,05-19 12:12:08.842  9944  9944 I usagelog: received in receiver
05-19 12:12:08.842  9944  9944 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-19 12:12:08.842  9944  9944 I KnoxUsageLogPro: premStatus:2
,05-19 12:12:08.842  9944  9944 I KnoxUsageLogPro: isEulaShown : false
05-19 12:12:08.842  9944  9944 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-19 12:12:08.852  3510  4983 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:08.862  3510  4983 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ead09fa u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97bae86 9956:com.samsung.android.sm.policy/u0a142}
,05-19 12:12:08.872  3510  4983 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:08.892 10234 10234 E Zygote  : v2
05-19 12:12:08.892 10234 10234 I libpersona: KNOX_SDCARD checking this for 1000
05-19 12:12:08.892 10234 10234 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:08.892 10234 10234 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:08.892 10234 10234 E Zygote  : accessInfo : 0
,05-19 12:12:08.892  3510  4983 I ActivityManager: Start proc 10234:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,05-19 12:12:08.922 10234 10234 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:08.922 10234 10234 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:08.942  3510  4947 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ad2c536 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c021de8 10234:com.samsung.android.securitylogagent/1000}
,05-19 12:12:08.952 10234 10234 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 12:12:08.952 10234 10234 D RelationGraph: garbageCollect()
,05-19 12:12:08.952 10234 10234 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package com.samsung.android.securitylogagent
,05-19 12:12:08.952  3510  3975 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-19 12:12:08.952 10234 10234 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:08.962 10234 10234 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:08.962 10234 10234 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:08.972 10234 10234 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,05-19 12:12:08.972 10234 10234 D InjectionManager: InjectionManager
,05-19 12:12:08.972 10234 10234 D InjectionManager: fillFeatureStoreMap com.samsung.android.securitylogagent
05-19 12:12:08.972 10234 10234 I InjectionManager: Constructor com.samsung.android.securitylogagent, Feature store :{}
05-19 12:12:08.972 10234 10234 I InjectionManager: featureStore :{}
,05-19 12:12:08.972 10234 10234 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
05-19 12:12:08.972 10234 10234 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
,05-19 12:12:09.002 10234 10234 D SecurityLogAgent: KnoxConfiguration : Current State = 0
,05-19 12:12:09.012 10234 10234 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
05-19 12:12:09.012 10234 10234 D SecurityLogAgent: StateMachine : Initialized
,05-19 12:12:09.012 10234 10234 D SecurityLogAgent: StateMachine : Changed Current State = 0
,05-19 12:12:09.012 10234 10234 D SecurityLogAgent: StateMachine : Current State = 0
,05-19 12:12:09.012  3510  3854 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:09.022  3510  3854 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e542d12 9993:com.policydm/1000}
,05-19 12:12:09.032  3510  4406 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-19 12:12:09.032  3510  4406 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 12:12:09.032  3510  4406 D BatteryService: online:4, current avg:-6, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-117
05-19 12:12:09.032  3510  3510 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-19 12:12:09.032  3510  3510 I MotionRecognitionService: Plugged
05-19 12:12:09.032  3510  3510 D MotionRecognitionService:   cableConnection= 1
05-19 12:12:09.032  3510  3510 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-19 12:12:09.032  3510  3510 D MotionRecognitionService: skip setTransmitPower. 
,05-19 12:12:09.042  3510  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-19 12:12:09.042  3942  3942 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-19 12:12:09.042  3942  3942 D PowerUI : priorPlugType = 2 mPlugType =  2
05-19 12:12:09.042  3942  3942 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-19 12:12:09.042  3942  3942 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-19 12:12:09.042  3942  3942 D PowerUI.Notification: There is no change about charging status, so return!
,05-19 12:12:09.042  9993  9993 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
05-19 12:12:09.052  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 12:12:09.052  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,05-19 12:12:09.052  5067  5067 D BatteryMonitor: new battery level: 100
,05-19 12:12:09.062  9993  9993 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-19 12:12:09.062  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 12:12:09.062  9993  9993 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-19 12:12:09.062  3510  4983 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:09.062  9763  9763 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-19 12:12:09.062  9763  9802 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-19 12:12:09.072  3510  4983 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e542d12 9993:com.policydm/1000}
,05-19 12:12:09.072  9993  9993 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,05-19 12:12:09.102  9993  9993 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,05-19 12:12:09.112  9993  9993 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,05-19 12:12:09.112  9993  9993 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,05-19 12:12:09.122  3158  3618 D Netd    : Iface wlan0 link up
05-19 12:12:09.122  9930  9930 I wpa_supplicant: nl80211: Received scan results (19 BSSes)
05-19 12:12:09.122  3510  3601 D Tethering: interfaceLinkStateChanged wlan0, true
05-19 12:12:09.122  3510  3601 D Tethering: interfaceStatusChanged wlan0, true
,05-19 12:12:09.122  5067  5358 D PdnController: Interface Changed wlan0 link up
,05-19 12:12:09.122  3510  3858 D WifiP2pService: InactiveState{ what=147461 }
,05-19 12:12:09.132  3510  3858 D WifiP2pService: P2pEnabledState{ what=147461 }
,05-19 12:12:09.132  9993  9993 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(342/lllIlIlIIIllIIlIllIl)] OMC not Supported model
05-19 12:12:09.132  3510  3858 D WifiP2pService: DefaultState{ what=147461 }
,05-19 12:12:09.132  9993  9993 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(111/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,05-19 12:12:09.132  9993  9993 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(281/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,05-19 12:12:09.132  9993  9993 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] Next heartbeat time:2017/05/23/13:22:44
,05-19 12:12:09.132  9993  9993 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(55/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,05-19 12:12:09.132  3510  3530 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:09.142  3510  3530 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b8643f 10022:com.osp.app.signin/u0a44}
,05-19 12:12:09.142 10022 10022 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hero2lte P = hero2ltexx I = MMB29K M = SM-G935F OKLEFT false DIS MMB29K.G935FXXU1BPJG PSS = 5.460694751064798  ]
,05-19 12:12:09.142 10022 10022 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
05-19 12:12:09.142 10022 10022 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,05-19 12:12:09.152  3510  3510 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,05-19 12:12:09.162 10022 10022 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-19 12:12:09.162 10022 10022 I SA      : [OR] == isSIMCardReady false ==
,05-19 12:12:09.162 10022 10022 I SA      : [SCU] == networkStateCheck == true
,05-19 12:12:09.162 10022 10022 I SA      : [DM] getCountryCodeFromCSC : PL
05-19 12:12:09.162 10022 10022 I SA      : isChinaCountryCode : false
05-19 12:12:09.162 10022 10022 I SA      : [SCU] is ChinestModel Data Restricted   : false
05-19 12:12:09.162 10022 10022 I SA      : [OR] == networkStateCheck true ==
,05-19 12:12:09.162  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b739c01 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c3d756 3942:com.android.systemui/u0a65}
,05-19 12:12:09.162 10022 10022 I SA      : [OR] GetMyCountryZoneTask
,05-19 12:12:09.162 10022 10022 I SA      : [OR] onReceive END
05-19 12:12:09.162 10022 10248 I SA      : [SRS] prepareGetMyCountryZone
,05-19 12:12:09.172  3510  3529 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:09.172  3510  3529 I ActivityManager: Killing 9435:com.google.android.apps.docs/u0a98 (adj 15): DHA:empty #33
,05-19 12:12:09.182 10022 10248 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-19 12:12:09.182  3510  3529 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{37a15b2 6976:com.wssyncmldm/1000}
,05-19 12:12:09.182 10022 10248 I SA      : [SSP] query invoked
,05-19 12:12:09.182 10022 10248 I SA      : [TPMU] GetMccFromDB : null
05-19 12:12:09.182 10022 10248 I SA      : [SCU] getMccFromPreferece mcc = 260
05-19 12:12:09.182 10022 10248 I SA      : [LBE] isSupportCheckDomainRegion : true
05-19 12:12:09.182 10022 10248 I SA      : [TPM] isNoProxy(default) : true
,05-19 12:12:09.192  3510  4059 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:09.202  6976 10250 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,05-19 12:12:09.212  3510  4257 D ActivityManager: cleanUpApplicationRecord -- 9435
,05-19 12:12:09.212  3510  4257 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,05-19 12:12:09.462 10022 10248 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,05-19 12:12:09.472 10022 10248 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,05-19 12:12:09.472 10022 10248 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
05-19 12:12:09.472 10022 10248 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,05-19 12:12:09.482  3158  3621 D EnterpriseController: netId is 0
05-19 12:12:09.482  3158  3621 D Netd    : getNetworkForDns: using netid 503 for uid 10044
,05-19 12:12:09.492  3510  3598 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:09.492  9666  9729 I io.jxcore.node.IncomingSocketThreadTest: testRun
,05-19 12:12:09.492  9666  9729 I !!      :  finally closed
,05-19 12:12:09.502  9666  9729 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,05-19 12:12:09.502  9666  9729 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,05-19 12:12:09.502  9666  9729 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
05-19 12:12:09.502  9666  9729 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,05-19 12:12:09.502  9666  9729 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,05-19 12:12:09.502  9666  9729 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,05-19 12:12:09.502  9666  9729 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.rockwellautomation.thalitest.MainActivity@d669aa Bundle[{}]
,05-19 12:12:09.502  9666  9729 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
05-19 12:12:09.502  9666  9729 I io.jxcore.node.LifeCycleMonitor: start: OK
,05-19 12:12:09.502  9666  9729 I io.jxcore.node.LifeCycleMonitor: stop: OK
05-19 12:12:09.502  3510  3598 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2890fed 7120:com.samsung.fresco.logging/5015}
05-19 12:12:09.502  9666  9729 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,05-19 12:12:09.502  9666  9729 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
05-19 12:12:09.502  3510  4313 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 12:12:09.502  9666  9729 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
05-19 12:12:09.502  9666  9729 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,05-19 12:12:09.502  3510  4518 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-19 12:12:09.512  9666  9729 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,05-19 12:12:09.512  9666  9729 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
05-19 12:12:09.512  3510  4427 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:09.512  9666  9729 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
05-19 12:12:09.512  9666  9729 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,05-19 12:12:09.512  9666  9729 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,05-19 12:12:09.512  9666  9729 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,05-19 12:12:09.512  9666  9729 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,05-19 12:12:09.512  9666  9729 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,05-19 12:12:09.512  9666  9729 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,05-19 12:12:09.522  9666  9729 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,05-19 12:12:09.522  9666  9729 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
05-19 12:12:09.522  3510  4427 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{175e416 7489:com.sec.spp.push/u0a42}
,05-19 12:12:09.522  7489  7489 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
05-19 12:12:09.522  7489  7489 E SPPClientService: [SystemStateMoniter] Current Time : 215093
05-19 12:12:09.522  7489  7489 E SPPClientService: [SystemStateMoniter] No Connect : false
,05-19 12:12:09.522  9666 10254 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,05-19 12:12:09.522  9666 10254 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-19 12:12:09.522  3158  3621 D EnterpriseController: netId is 0
05-19 12:12:09.522  3158  3621 D Netd    : getNetworkForDns: using netid 503 for uid 10078
,05-19 12:12:09.532  3510  4427 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:09.532  9666 10256 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,05-19 12:12:09.532  9666 10256 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-19 12:12:09.532  9666 10256 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 12:12:09.532  9666 10256 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-19 12:12:09.532  9666 10256 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-19 12:12:09.532  9666 10254 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
05-19 12:12:09.532  9666 10254 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,05-19 12:12:09.532  9666 10254 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-19 12:12:09.532  9666 10258 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 241, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:09.532  9666 10258 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 12:12:09.532  9666 10258 D io.jxcore.node.StreamCopyingThread:  id: 77
,05-19 12:12:09.532  9666 10254 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-19 12:12:09.532  9666 10259 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 242, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:09.532  9666 10259 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 12:12:09.532  9666 10259 D io.jxcore.node.StreamCopyingThread:  id: 77
,05-19 12:12:09.532  9666 10254 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-19 12:12:09.532  9666 10260 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 243, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:09.532  9666 10260 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:09.532  9666 10260 D io.jxcore.node.StreamCopyingThread:  id: 78
,05-19 12:12:09.532  3510  4427 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bebefe2 4914:android.process.media/u0a51}
,05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 244, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread:  id: 78
,05-19 12:12:09.542  4914  4914 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 244, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread:  id: 78
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread:  id: 78
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 12:12:09.542  9666 10259 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 242, thread name: IncomingSocketThread/Receiver): sendto failed: EPIPE (Broken pipe)
05-19 12:12:09.542  9666 10258 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 241, thread name: IncomingSocketThread/Sender): recvfrom failed: ECONNRESET (Connection reset by peer)
05-19 12:12:09.542  9666 10259 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 242, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:09.542  9666 10259 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 12:12:09.542  9666 10259 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 200704 and the total number of bytes written 196608
05-19 12:12:09.542  9666 10258 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 241, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:09.542  9666 10258 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 12:12:09.542  9666 10258 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-19 12:12:09.542  9666 10258 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: ECONNRESET (Connection reset by peer)
05-19 12:12:09.542  9666 10259 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)", this is likely due to peer having disconnected
05-19 12:12:09.542  9666 10258 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-19 12:12:09.542  9666 10259 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
05-19 12:12:09.542  9666 10258 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 241, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:09.542  9666 10258 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 12:12:09.542  9666 10258 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-19 12:12:09.542  9666 10259 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 242, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:09.542  9666 10259 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-19 12:12:09.542  9666 10259 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 200704 and the total number of bytes written 196608
05-19 12:12:09.,542  9666 10260 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 243, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-19 12:12:09.542  9666 10260 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 243, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:09.542  9666 10260 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:09.542  9666 10260 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 24576 and the total number of bytes written 24576
05-19 12:12:09.542  9666 10260 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-19 12:12:09.542  9666 10260 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-19 12:12:09.542  9666 10260 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 243, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:09.542  9666 10260 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:09.542  9666 10260 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 24576 and the total number of bytes written 24576
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 12:12:09.542  9666 10261 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 244, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:09.542  9666 10261 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-19 12:12:09.552  3510  4040 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:09.562  3510  4407 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,05-19 12:12:09.882  3510  3598 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:09.892  3510  3598 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{17dfec2 10057:com.samsung.android.SettingsReceiver/1000}
,05-19 12:12:09.892 10057 10057 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,05-19 12:12:09.892  3510  4407 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:09.902  3510  4407 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{68e4810 10072:com.samsung.android.themestore/u0a68}
,05-19 12:12:09.902 10072 10072 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,05-19 12:12:09.912  3510  4313 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:09.922 10072 10072 D AutoSelfUpgradeService: onCreate() 
,05-19 12:12:09.922 10072 10072 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
,05-19 12:12:09.922 10072 10263 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
,05-19 12:12:09.922 10072 10263 D AutoSelfUpgradeService: getAlarmIntent() 
,05-19 12:12:09.932 10072 10263 D AutoSelfUpgradeService: isAlarmActivated() true
,05-19 12:12:09.932 10072 10072 D AutoSelfUpgradeService: onDestroy()
,05-19 12:12:10.122 10022 10248 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 651
,05-19 12:12:10.142 10022 10248 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,05-19 12:12:10.152 10022 10248 I SA      : [OCP] update openData : PL
,05-19 12:12:10.162 10022 10248 I SA      : [TPMU] getNetworkMcc : 
,05-19 12:12:10.182 10022 10248 I SA      : [SCU] saveMccToPreferece Start
,05-19 12:12:10.182 10022 10248 I SA      : [SCU] RegionMCC : 260
05-19 12:12:10.182 10022 10248 I SA      : [SSP] query invoked
,05-19 12:12:10.192 10022 10248 I SA      : [TPMU] GetMccFromDB : null
05-19 12:12:10.192 10022 10248 I SA      : [SCU] getMccFromPreferece mcc = 260
,05-19 12:12:10.192 10022 10248 I SA      : [SCU] saveMccToPreferece End
05-19 12:12:10.192 10022 10248 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 729
05-19 12:12:10.192 10022 10248 I SA_HTTPURLCONNECTION: [RC New] Execute end
05-19 12:12:10.192 10022 10022 I SA      : [OR] GetMyCountryZoneTask mcc = 260
05-19 12:12:10.192 10022 10022 I SA      : [OR] GetMyCountryZoneTask Success
,05-19 12:12:10.212  3510  3598 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:10.222  3510  3598 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca70c58 10113:com.samsung.android.scloud:contentsync/5009}
,05-19 12:12:10.222 10113 10113 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
05-19 12:12:10.222 10113 10113 I [SC]CloudManager: requestInit
,05-19 12:12:10.232 10113 10113 I [SC]Utils: folder : cachecreate fail, try again.
05-19 12:12:10.232 10113 10113 I [SC]Utils: folder : cache create fail.
05-19 12:12:10.232 10113 10113 I [SC]Utils: folder : thumbnailcreate fail, try again.
05-19 12:12:10.232 10113 10113 I [SC]Utils: folder : thumbnail create fail.
,05-19 12:12:10.232 10113 10113 I [SC]Utils: folder : sharecreate fail, try again.
05-19 12:12:10.232 10113 10113 I [SC]Utils: folder : share create fail.
05-19 12:12:10.232 10113 10113 I [SC]Utils: folder : scratchcreate fail, try again.
05-19 12:12:10.232 10113 10113 I [SC]Utils: folder : scratch create fail.
,05-19 12:12:10.232 10113 10113 I [SC]Utils: folder : eventSynccreate fail, try again.
,05-19 12:12:10.232 10113 10113 I [SC]Utils: folder : eventSync create fail.
,05-19 12:12:10.252 10022 10033 I SA      : [SCU] isHaveSA() - false
05-19 12:12:10.252 10022 10033 I SA      : [OCP] Samsung account is not Signed-in
,05-19 12:12:10.252 10022 10033 I SA      : [OCP] Delete DB (TNC data)
,05-19 12:12:10.262 10113 10113 I [SC]CommonUtil: Samsung Account Not Logged in
,05-19 12:12:10.262  3510  4427 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:10.272  3510  4427 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ac9604 10141:com.samsung.android.coreapps/5011}
,05-19 12:12:10.332  3510  4407 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:10.342  3510  4407 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ac9604 10141:com.samsung.android.coreapps/5011}
,05-19 12:12:10.352  3510  4518 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:10.362  3510  4518 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6ac9604 10141:com.samsung.android.coreapps/5011}
,05-19 12:12:10.372  3510  4518 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:10.382  3510  4518 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a87173 4846:com.microsoft.skydrive/u0a130}
,05-19 12:12:10.392  3510  4409 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,05-19 12:12:10.402  3510  4407 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:10.702  3510  3598 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:10.722  3510  3598 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4af6c91 10205:com.google.android.apps.photos/u0a135}
,05-19 12:12:10.742  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3723083 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4af6c91 10205:com.google.android.apps.photos/u0a135}
,05-19 12:12:10.742  3510  4947 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:10.752  3510  4947 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4af6c91 10205:com.google.android.apps.photos/u0a135}
,05-19 12:12:10.752  3510  6241 D SSRM:n  : SIOP:: AP = 320, PST = 320 (W:14), CP = 263, CUR = -6, LCD = 40
,05-19 12:12:10.782  3510  6241 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-19 12:12:10.802  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7c6ca39 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4af6c91 10205:com.google.android.apps.photos/u0a135}
05-19 12:12:10.802  3510  4409 D ActivityManager:  getDeferredInfo final delay 300
,05-19 12:12:11.152  3510  3598 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:11.162  3510  3598 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3403c8 4722:com.sec.android.daemonapp/u0a166}
,05-19 12:12:11.162  4722  4722 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,05-19 12:12:11.162  4722  4722 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
,05-19 12:12:11.172  3510  4983 D ActivityManager:  getDeferredInfo final delay 0
,05-19 12:12:11.182  3510  4983 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b68431e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{38e7040 7981:com.sec.android.app.samsungapps/u0a16}
,05-19 12:12:11.182  7981  7981 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,05-19 12:12:11.192  7981  7981 D [SAUI]  : Global::recovered::false
,05-19 12:12:11.192  3510  4407 D ActivityManager:  getDeferredInfo final delay 300
05-19 12:12:11.192  7981  7981 D [SAUI]  : AutoUpdateService::onStartCommand
,05-19 12:12:11.192  7981  7981 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,05-19 12:12:11.202  7981  7981 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,05-19 12:12:11.202  7981  7981 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
05-19 12:12:11.202  7981  7981 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,05-19 12:12:11.202  7981  9507 D [SA_INIT]: createTaskForServiceInitialize()
05-19 12:12:11.202  7981  9507 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,05-19 12:12:11.202  7981  9507 D [SA_INIT]: NetworkStateCheckUnit result : 1
,05-19 12:12:11.202  7981  7981 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 182046411_0] [END] FINISHED
05-19 12:12:11.202  7981  7981 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
05-19 12:12:11.202  7981  7981 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
,05-19 12:12:11.212  7981  7981 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,05-19 12:12:11.212  7981  7981 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,05-19 12:12:12.802 10099 10099 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-19 12:12:13.152  3510  3869 D ConnectivityService: handlePromptUnvalidated 503
,05-19 12:12:15.032  9666  9729 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,05-19 12:12:15.032  9666  9729 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,05-19 12:12:15.032  9666  9729 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,05-19 12:12:15.742  3510  3598 I ActivityManager: Waited long enough for: ServiceRecord{783a219 u0 com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService}
,05-19 12:12:15.822  9877  9909 W Babel   : ayr TOOK TOO LONG! (15000ms > 10000ms)
,05-19 12:12:15.822  9877  9911 W Babel   : ayr TOOK TOO LONG! (15000ms > 10000ms)
,05-19 12:12:15.832  3510  3530 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10117
,05-19 12:12:15.872  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{440d0f5 u0 register_intent_action qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9616e 9557:com.google.android.talk:matchstick/u0a117}
,05-19 12:12:15.902  3510  4518 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,05-19 12:12:15.922  9877  9922 W Babel   : ayr TOOK TOO LONG! (15007ms > 10000ms)
,05-19 12:12:15.922  9557 10270 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } isPeriodic:false
,05-19 12:12:15.932  9877  9877 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
05-19 12:12:15.932  9877  9877 W Babel   : BAM#gBA: invalid account id: -1
05-19 12:12:15.932  9877  9877 W Babel   : BAM#gBA: invalid account id: -1
05-19 12:12:15.932  9877  9877 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,05-19 12:12:15.942  9557 10270 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,05-19 12:12:15.942  3510  4059 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,05-19 12:12:15.952  9557 10270 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:15.972  9557 10270 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,05-19 12:12:15.982  3510  3628 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,05-19 12:12:15.982  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-19 12:12:15.992  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
,05-19 12:12:15.992  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.002  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-19 12:12:16.002  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,05-19 12:12:16.002  3942  3942 D ShortcutManager: onReceive : android.intent.action.PACKAGE_CHANGED
,05-19 12:12:16.002  4151  4151 I CatchNotificationsService: mPackageChangedReceiver : onReceive action = android.intent.action.PACKAGE_CHANGED
,05-19 12:12:16.002  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.002  4151  4151 D CatchNotificationsSupportedAppsDBHelper: Package doesn't have start activity, skip
,05-19 12:12:16.002  3510  3610 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
,05-19 12:12:16.012  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.012  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,05-19 12:12:16.012  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.012  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,05-19 12:12:16.012  3510  3610 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.012  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.012  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,05-19 12:12:16.012  3510  3610 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
,05-19 12:12:16.022  3510  3831 I InputReader: Reconfiguring input devices.  changes=0x00000010
05-19 12:12:16.022  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.022  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
05-19 12:12:16.022  4288  4288 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.android.phone rsrc of package com.android.mms
,05-19 12:12:16.022  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,05-19 12:12:16.032  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.032  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,05-19 12:12:16.032  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.032  4288  4288 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.032  4163  4163 I PeoplePackageManager: onReceive:android.intent.action.PACKAGE_CHANGED
,05-19 12:12:16.042  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.042  9666  9729 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,05-19 12:12:16.042  9666  9729 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,05-19 12:12:16.042  9666  9729 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
05-19 12:12:16.042  9666  9729 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 252)
,05-19 12:12:16.042  9666  9729 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,05-19 12:12:16.042  9666  9729 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
05-19 12:12:16.042  9666  9729 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 253)
,05-19 12:12:16.042  9666  9729 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,05-19 12:12:16.042  9666  9729 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,05-19 12:12:16.042  9666  9729 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,05-19 12:12:16.042  9666  9729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,05-19 12:12:16.042  9666  9729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaa1c0 added. We now have 2 listener(s)
05-19 12:12:16.042  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaa1c0 added. We now have 3 listener(s)
05-19 12:12:16.042  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-19 12:12:16.052  4163  4163 D CircleReceiver:  CircleReceiver intentAction : android.intent.action.PACKAGE_CHANGED
,05-19 12:12:16.052  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.052  4163  4163 D CircleReceiver: actionFilter-action : android.intent.action.PACKAGE_CHANGED
05-19 12:12:16.052  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.052  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:12:16.052  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.052  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-19 12:12:16.052  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.052  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:12:16.052  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.052  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-19 12:12:16.052  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.052  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f8ef9 added. We now have 4 listener(s)
,05-19 12:12:16.052  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
05-19 12:12:16.052  9666  9729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-19 12:12:16.052  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
05-19 12:12:16.052  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
05-19 12:12:16.052  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.052  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-19 12:12:16.052  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
05-19 12:12:16.052  3510  3628 D PackageManager: com.google.android.gms.permission.CAR_FUEL is a new runtime permission
05-19 12:12:16.052  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
05-19 12:12:16.052  3510  3628 D PackageManager: com.google.android.gms.permission.CAR_MILEAGE is a new runtime permission
05-19 12:12:16.062  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-19 12:12:16.052  3510  3628 D PackageManager: com.google.android.gms.permission.CAR_SPEED is a new runtime permission
,05-19 12:12:16.052  3510  3628 D PackageManager: com.google.android.gms.permission.CAR_VENDOR_EXTENSION is a new runtime permission
05-19 12:12:16.062  3510  3628 D PackageManager: Permission Group is null for permission com.sec.smartcard.permission.SMARTCARD_ADAPTER
05-19 12:12:16.062  3510  3628 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_READ
05-19 12:12:16.062  3510  3628 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_WRITE
05-19 12:12:16.062  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.062  3510  3628 D ApplicationPolicy: groups[android.permission-group.SMS, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.LOCATION, android.permission-group.MESSAGES, android.permission-group.SMS, android.permission-group.CAMERA, android.permission-group.SENSORS, android.permission-group.LOCATION, android.permission-group.SMS, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.MESSAGES, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.SMS, android.permission-group.PHONE, android.permission-group.CONTACTS, android.permission-group.CAMERA, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.SMS, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, android.permission-group.CONTACTS, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.STORAGE, com.samsung.android.memo.EXTRA_READ, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.MICROPHONE, android.permission-group.CONTACTS, com.samsung.android.memo.EXTRA_WRITE, android.permission-group.PHONE]
,05-19 12:12:16.062  3510  3628 D ApplicationPolicy: Permission GRoups [android.permission-group.CONTACTS, android.permission-group.CALENDAR, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.MICROPHONE, android.permission-group.CAMERA, android.permission-group.SENSORS, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, com.samsung.android.memo.EXTRA_READ, com.samsung.android.memo.EXTRA_WRITE]
05-19 12:12:16.062  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,05-19 12:12:16.062  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
,05-19 12:12:16.062  4163  4163 D CircleReceiver: checkContactState() => true
,05-19 12:12:16.062  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.062  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.072  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,05-19 12:12:16.072  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-19 12:12:16.072  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
,05-19 12:12:16.072  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-19 12:12:16.072  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,05-19 12:12:16.072  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
05-19 12:12:16.072  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,05-19 12:12:16.072  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
05-19 12:12:16.072  3510  3598 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39d9ba7 4437:com.google.android.googlequicksearchbox:search/u0a72}
05-19 12:12:16.072  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.082  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:16.072  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
05-19 12:12:16.072  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.072  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
,05-19 12:12:16.082  3510  4313 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4846, uid=10130 that is not exported from uid 10128
05-19 12:12:16.082  4288  4288 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.phone rsrc of package com.google.android.talk
05-19 12:12:16.082  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,05-19 12:12:16.082  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,05-19 12:12:16.082  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.082  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
,05-19 12:12:16.082  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
,05-19 12:12:16.082  4025  4025 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_CHANGED
,05-19 12:12:16.082  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.082  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.082  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
,05-19 12:12:16.082  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
05-19 12:12:16.082  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
05-19 12:12:16.082  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
,05-19 12:12:16.092  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.092  4288  4288 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.092  9666  9729 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
05-19 12:12:16.092  9666  9729 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.092  9666  9729 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
05-19 12:12:16.092  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.092  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-19 12:12:16.092  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.092  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:12:16.092  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
,05-19 12:12:16.092  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.092  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.092  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-19 12:12:16.092  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.102  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.102  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.102  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-19 12:12:16.102  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.102  9666  9729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-19 12:12:16.102  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.102  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-19 12:12:16.102  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.102  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-19 12:12:16.112  9666 10276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.112  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.112  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.112  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.112  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.112  9666  9666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.112  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.112  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-19 12:12:16.122  9666 10276 D BluetoothSocket: bindListen(): myUserId = 0
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.122  9666 10276 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.092  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.092  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
05-19 12:12:16.092  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
05-19 12:12:16.102  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.102  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.102  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
,05-19 12:12:16.102  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
05-19 12:12:16.102  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.102  3510  4427 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4164f92 9877:com.google.android.talk/u0a117}
05-19 12:12:16.102  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.102  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
,05-19 12:12:16.102  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.102  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.102  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in null rsrc of package com.sec.android.app.launcher
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.102  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
,05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,05-19 12:12:16.102  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.112  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.112  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.112  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-19 12:12:16.112  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.112  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-19 12:12:16.112  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-19 12:12:16.112  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-19 12:12:16.112  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-19 12:12:16.112  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,05-19 12:12:16.132  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
05-19 12:12:16.112  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
05-19 12:12:16.132  9666  9729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-19 12:12:16.132  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-19 12:12:16.112  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-19 12:12:16.112  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
05-19 12:12:16.132  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-19 12:12:16.112  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
05-19 12:12:16.112  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
05-19 12:12:16.112  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
,05-19 12:12:16.122  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
05-19 12:12:16.122  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
05-19 12:12:16.122  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.122  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
05-19 12:12:16.122  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
05-19 12:12:16.122  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
05-19 12:12:16.122  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.122  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
05-19 12:12:16.122  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
05-19 12:12:16.122  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.122  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
,05-19 12:12:16.122  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
05-19 12:12:16.122  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
05-19 12:12:16.122  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
05-19 12:12:16.122  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
05-19 12:12:16.122  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
05-19 12:12:16.122  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
05-19 12:12:16.122  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
05-19 12:12:16.122  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
05-19 12:12:16.122  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
05-19 12:12:16.122  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
05-19 12:12:16.132  3510  3510 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.132  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.132  3510  3510 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
05-19 12:12:16.132  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
05-19 12:12:16.132  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
05-19 12:12:16.142  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:16.132  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.132  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
05-19 12:12:16.132  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
05-19 12:12:16.132  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
05-19 12:12:16.132  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
05-19 12:12:16.132  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
05-19 12:12:16.132  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
,05-19 12:12:16.132  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
05-19 12:12:16.132  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,05-19 12:12:16.142  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:16.142  3510  3510 D UcmService: onReceive android.intent.action.PACKAGE_CHANGED
05-19 12:12:16.142  3510  3510 D UcmService: Package update in userId-0 and uid-10021
,05-19 12:12:16.142  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.142  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-19 12:12:16.142  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:16.152  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:16.152  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-19 12:12:16.152  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-19 12:12:16.152  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,05-19 12:12:16.152  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,05-19 12:12:16.152  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.152  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,05-19 12:12:16.152  9666 10276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-19 12:12:16.152  9666 10276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@931849f, port: 6, type: 1, local socket address: null, socket type: 0
,05-19 12:12:16.152  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,05-19 12:12:16.152  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
,05-19 12:12:16.152  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,05-19 12:12:16.152  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.152  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,05-19 12:12:16.162  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,05-19 12:12:16.162  3510  3510 D CocktailBarManagerServiceContainer: onReceive : android.intent.action.PACKAGE_CHANGED
,05-19 12:12:16.162  3510  3510 D UcmService: *****refreshAgentList userId-0 is called***
05-19 12:12:16.162  3510  3510 D UcmService: resolveAllowedAgents for user 0
,05-19 12:12:16.162  3510  3510 D UcmService: found com.sec.smartcard.manager
05-19 12:12:16.162  3510  3510 D UcmService: found com.samsung.ucs.agent.ese
05-19 12:12:16.162  3510  3510 D UcmService: found com.samsung.ucs.agent.boot
05-19 12:12:16.162  3510  3510 D UcmService: mPersistentServices size is 3
05-19 12:12:16.162  3510  3510 D UcmService: -------Processing started for agentPackageName----- -com.sec.smartcard.manager
05-19 12:12:16.162  3510  3510 D UcmService:   agentPackageName -com.sec.smartcard.manager is an active plugin
05-19 12:12:16.162  3510  3510 D UcmService:   Check if caller has UCS Plugin permission...
05-19 12:12:16.162  3510  3510 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
05-19 12:12:16.162  3510  3510 D UcmService: -------Processing started for agentPackageName----- -com.samsung.ucs.agent.ese
05-19 12:12:16.162  3510  3510 D UcmService:   agentPackageName -com.samsung.ucs.agent.ese is an active plugin
05-19 12:12:16.162  3510  3510 D UcmService:   Check if caller has UCS Plugin permission...
05-19 12:12:16.162  3510  3510 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
05-19 12:12:16.162  3510  3510 D UcmService:   agentPackageName com.samsung.ucs.agent.ese is system storage. Checking system signature
,05-19 12:12:16.162  3510  3510 D UcmService:   Signature match
05-19 12:12:16.162  3510  3510 D UcmService:   Valid system storage found is com.samsung.ucs.agent.ese
05-19 12:12:16.162  3510  3510 D UcmService: -------Processing started for agentPackageName----- -com.samsung.ucs.agent.boot
05-19 12:12:16.162  3510  3510 D UcmService:   agentPackageName -com.samsung.ucs.agent.boot is an active plugin
05-19 12:12:16.162  3510  3510 D UcmService:   Check if caller has UCS Plugin permission...
05-19 12:12:16.162  3510  3510 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
05-19 12:12:16.162  3510  3510 D UcmService:   agentPackageName com.samsung.ucs.agent.boot is system storage. Checking system signature
05-19 12:12:16.162  3510  3510 D UcmService:   Signature match
05-19 12:12:16.162  3510  3510 D UcmService:   Valid system storage found is com.samsung.ucs.agent.boot
05-19 12:12:16.162  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:16.162  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,05-19 12:12:16.162  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,05-19 12:12:16.172  3510  3510 D UcmService: readPersistentServicesLocked is called...
05-19 12:12:16.172  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
05-19 12:12:16.172  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.172  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.172  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-19 12:12:16.172  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-19 12:12:16.172  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "2c7c4446-495b-40f1-ba37-3ac33ac5ee28", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-19 12:12:16.172  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 A8 81 95 E9 5F 6F
05-19 12:12:16.172  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 12:12:16.172  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 12:12:16.172  3510  3510 D UcmService: PersistentServices  key-com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot
05-19 12:12:16.172  3510  3510 D UcmService: PersistentServices  value-1000
05-19 12:12:16.172  3510  3510 D UcmService: PersistentServices  key-com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile
05-19 12:12:16.172  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.172  3510  3510 D UcmService: PersistentServices  value-10062
05-19 12:12:16.172  3510  3510 D UcmService: PersistentServices  key-com.samsung.ucs.agent.ese:eSE Credential Storage
05-19 12:12:16.172  3510  3510 D UcmService: PersistentServices  value-10099
05-19 12:12:16.172  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.172  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-19 12:12:16.172  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 12:12:16.172  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-134,7,main], id: 13,4
05-19 12:12:16.172  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.172  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.172  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-19 12:12:16.172  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
05-19 12:12:16.172  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
05-19 12:12:16.172  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
05-19 12:12:16.172  4163  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.talk,id=10436,extra=Bundle[mParcelledData.dataSize=84]
,05-19 12:12:16.172  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.talk}]
05-19 12:12:16.172  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 12:12:16.172  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 12:12:16.172  4163  4163 I PeopleDataManager: removeNotification
05-19 12:12:16.172  4163  4163 I NotificationParser: getNotiType:com.google.android.talk,null
05-19 12:12:16.172  4163  4163 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.talk,isEdgeNotification=false,key=null,removeAll=false
05-19 12:12:16.172  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
05-19 12:12:16.172  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-19 12:12:16.172  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:16.172  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage
,05-19 12:12:16.172  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.172  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage
05-19 12:12:16.172  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:16.172  9666  9729 D BluetoothLeAdvertiser: start advertising
,05-19 12:12:16.182  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage
,05-19 12:12:16.182  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/QuickConnect_40/QuickConnect_40.apk / 1.0 running in null rsrc of package com.samsung.android.qconnect
,05-19 12:12:16.182  3510  3594 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.182  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/QuickConnect_40/QuickConnect_40.apk / 1.0 running in null rsrc of package com.samsung.android.qconnect
,05-19 12:12:16.182  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,05-19 12:12:16.182  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
,05-19 12:12:16.182  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
,05-19 12:12:16.182  3510  3594 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
,05-19 12:12:16.192 10281 10281 E Zygote  : v2
,05-19 12:12:16.192 10281 10281 I libpersona: KNOX_SDCARD checking this for 10001
05-19 12:12:16.192 10281 10281 I libpersona: KNOX_SDCARD not a persona
05-19 12:12:16.192  3510  4040 I ActivityManager: Start proc 10281:com.samsung.android.app.appsedge/u0a1 for broadcast-3 com.samsung.android.app.appsedge/.AppsEdgeBroadcastReceiver
,05-19 12:12:16.192 10281 10281 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:16.192 10281 10281 E Zygote  : accessInfo : 0
,05-19 12:12:16.192  3510  3594 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-19 12:12:16.192 10281 10281 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.appsedge 
05-19 12:12:16.192  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:16.202  9763  9816 D BtGatt.GattService: registerClient() - UUID=46b1cadd-ef89-4566-a846-a09183ada3d5
,05-19 12:12:16.212  4276 10278 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
,05-19 12:12:16.212  4276 10278 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
,05-19 12:12:16.212  4276 10278 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
05-19 12:12:16.212  4276 10278 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
05-19 12:12:16.212  4276 10278 D RegisteredComponentCache: Collect Tech packages for Knox
,05-19 12:12:16.222 10281 10281 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:16.222 10281 10281 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:16.222  9877  9877 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,05-19 12:12:16.222  4341  4341 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,05-19 12:12:16.222  9877  9877 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,05-19 12:12:16.232  4163  4173 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.talk,id=8,extra=Bundle[mParcelledData.dataSize=84]
05-19 12:12:16.232  4163  4163 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=8, samsung.notification.type=normal, samsung.people.package_name=com.google.android.talk}]
05-19 12:12:16.232  4163  4163 I PeopleStripeService: PeopleNotificationReceiver:3
05-19 12:12:16.232  4163  4163 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-19 12:12:16.232  4163  4163 I PeopleDataManager: removeNotification
05-19 12:12:16.232  4163  4163 I NotificationParser: getNotiType:com.google.android.talk,null
05-19 12:12:16.232  4163  4163 D PeopleDataManager: removeNotiInfo: id =8,packageName=com.google.android.talk,isEdgeNotification=false,key=null,removeAll=false
05-19 12:12:16.232  4163  4163 D PeopleDataManager: removeNotiInfo =null
,05-19 12:12:16.242  9877  9877 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.242  3510  4406 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c11557 10281:com.samsung.android.app.appsedge/u0a1}
,05-19 12:12:16.252  9763  9780 D BtGatt.GattService: onClientRegistered() - UUID=46b1cadd-ef89-4566-a846-a09183ada3d5, clientIf=7
,05-19 12:12:16.252  9666  9676 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-19 12:12:16.252  9763  9869 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-19 12:12:16.262 10281 10281 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 12:12:16.262 10281 10281 D RelationGraph: garbageCollect()
,05-19 12:12:16.262  9877 10297 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,05-19 12:12:16.262  9763  9869 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:12:16.262  9763  9869 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 12:12:16.262  9763  9791 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
05-19 12:12:16.262  9763  9782 D BtGatt.AdvertiseManager: message : 0
05-19 12:12:16.262  9763  9791 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 12:12:16.262 10281 10281 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.appsedge rsrc of package com.samsung.android.app.appsedge
,05-19 12:12:16.262  9763  9782 D BtGatt.AdvertiseManager: number of adv instance running = 0
,05-19 12:12:16.262  9763  9782 D BtGatt.AdvertiseManager: size of list is =0
,05-19 12:12:16.262  3510  3530 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 12:12:16.262  3510  4312 D SettingsProvider: isChangeAllowed() : name = assisted_gps_enabled
05-19 12:12:16.262  3510  4312 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-19 12:12:16.262  3510  4312 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
05-19 12:12:16.262  3510  4312 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-19 12:12:16.262  3510  4312 D SettingsProvider: selectionArgs: false
,05-19 12:12:16.272 10281 10281 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-19 12:12:16.262  3510  4312 D SettingsProvider: selectionArgs: 10021
,05-19 12:12:16.272  3510  4312 D SettingsProvider: ret = -1
,05-19 12:12:16.272  9763  9791 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 10
05-19 12:12:16.272  9763  9791 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24919812
05-19 12:12:16.272 10281 10281 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.272  9763  9791 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-19 12:12:16.272  9763  9791 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 12:12:16.272  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 12:12:16.272  9763  9782 D BtGatt.AdvertiseManager: starting advertising
,05-19 12:12:16.282 10281 10281 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:16.282  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{36102ae: PendingIntentRecord{876a76f com.google.android.talk startService}}
,05-19 12:12:16.282  9763  9782 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-19 12:12:16.282 10281 10281 W System  : ClassLoader referenced unknown path: /system/priv-app/AppsEdgePanel/lib/arm64
,05-19 12:12:16.282 10281 10281 D InjectionManager: InjectionManager
,05-19 12:12:16.282 10281 10281 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.appsedge
,05-19 12:12:16.292 10281 10281 I InjectionManager: Constructor com.samsung.android.app.appsedge, Feature store :{}
,05-19 12:12:16.292 10281 10281 I InjectionManager: featureStore :{}
05-19 12:12:16.292 10281 10281 I AppsEdgeBroadcastReceiver: onReceive: android.intent.action.PACKAGE_CHANGED
,05-19 12:12:16.292  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{fb3584f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.292  9763  9780 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-19 12:12:16.292  9763  9782 D BtGatt.AdvertiseManager: starting multi advertising
,05-19 12:12:16.292  9763  9780 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,05-19 12:12:16.302  9763  9782 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-19 12:12:16.302  9763  9782 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-19 12:12:16.302  9763  9782 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
,05-19 12:12:16.302  9763  9782 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
05-19 12:12:16.302  9666 10185 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-19 12:12:16.302  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,05-19 12:12:16.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.302  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-19 12:12:16.302  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,05-19 12:12:16.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:16.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:16.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:16.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.302  9666  9666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-19 12:12:16.302  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-19 12:12:16.302  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-19 12:12:16.302  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-19 12:12:16.302  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-19 12:12:16.302  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-19 12:12:16.302  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-19 12:12:16.302  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 12:12:16.302  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-19 12:12:16.302  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-19 12:12:16.302  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,05-19 12:12:16.302  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-19 12:12:16.302  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 12:12:16.302  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-19 12:12:16.302  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-19 12:12:16.312  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{df72a6b: PendingIntentRecord{b8bfd42 com.google.android.gms broadcastIntent}}
,05-19 12:12:16.312  9877  9877 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
05-19 12:12:16.312  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{aebd9c8: PendingIntentRecord{8e0ab8e com.google.android.gms broadcastIntent}}
,05-19 12:12:16.312  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{b76da61: PendingIntentRecord{6fb3ba8 com.google.android.gms broadcastIntent}}
,05-19 12:12:16.312  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{2ab986: PendingIntentRecord{59c6a54 com.google.android.gms broadcastIntent}}
,05-19 12:12:16.312  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{a5c0247: PendingIntentRecord{a223af2 com.google.android.gms broadcastIntent}}
,05-19 12:12:16.312  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{bc8ca74: PendingIntentRecord{cab8cf9 com.google.android.gms broadcastIntent}}
05-19 12:12:16.312  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{be5bb9d: PendingIntentRecord{98b29f com.google.android.gms broadcastIntent}}
,05-19 12:12:16.312  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{868e812: PendingIntentRecord{dca364a com.google.android.gms broadcastIntent}}
,05-19 12:12:16.322  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{b4c7be3: PendingIntentRecord{f48ded8 com.google.android.gms broadcastIntent}}
,05-19 12:12:16.322  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-19 12:12:16.322  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-19 12:12:16.322  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-19 12:12:16.322  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{1e219e0: PendingIntentRecord{37d6d16 com.google.android.gms broadcastIntent}}
05-19 12:12:16.322  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,05-19 12:12:16.322  9666  9666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
05-19 12:12:16.322  4341  4981 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.gms/files/nlp_state
05-19 12:12:16.322  4341  4981 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.gms/cache/nlp_devices
05-19 12:12:16.322  4341  4981 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.gms/files/nlp_ioh
05-19 12:12:16.322  4341  4981 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.gms/cache/nlp_s
,05-19 12:12:16.322  4341  4981 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.gms/cache/nlp_GlsPlatformKey
,05-19 12:12:16.322  3510  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{feb16e 4341:com.google.android.gms.persistent/u0a21}
,05-19 12:12:16.332  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{4677499: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.352  4300  4300 E Launcher.Model: onPackageChanged :com.google.android.gms
,05-19 12:12:16.352  4300  4373 D LauncherApps: getActivityList callingUid: 0 user: 0
,05-19 12:12:16.352  4300  4373 D LauncherApps: getActivityList callingUid: 0 user: 0
,05-19 12:12:16.362  4300  4373 D Launcher.MenuWidgetsLoader: packageChanged : com.google.android.gms
05-19 12:12:16.362  4300  4300 D Launcher.MenuWidgetsLoader: MenuWidgetLoade-loadMenuWidgets : false
,05-19 12:12:16.362  4300  4300 D MenuView: packageChanged:
,05-19 12:12:16.362  4300 10299 D Launcher.MenuWidgetsLoader: MenuWidgetLoader-start : com.android.launcher2.MenuWidgetsLoader$LoadMenuWidgetsTask@7e0f5bd , false
,05-19 12:12:16.372  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{a55676a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.382  4659 10301 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
05-19 12:12:16.382  4659 10301 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,05-19 12:12:16.382  3510  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b010df5 8824:com.android.vending/u0a35}
,05-19 12:12:16.402  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{c1a1dd1: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.412  4659 10301 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,05-19 12:12:16.422  4659  7438 I Icing   : updateResources: need to parse f{com.google.android.gms}
,05-19 12:12:16.422  4659  7438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
05-19 12:12:16.422  4659  7438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-19 12:12:16.432  3510  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b010df5 8824:com.android.vending/u0a35}
,05-19 12:12:16.442  4659  7438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-19 12:12:16.452  4659  7438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-19 12:12:16.452  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{a4423d3: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.472  3510  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3c7fb0 8113:com.sec.android.app.shealth:remote/u0a39}
,05-19 12:12:16.482  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{a1fbb10: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.482  4300  4300 D Launcher.MenuWidgetsLoader: MenuWidgetLoader-done : com.android.launcher2.MenuWidgetsLoader$LoadMenuWidgetsTask@7e0f5bd , update : false , size : 47
,05-19 12:12:16.482  4659  7438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-19 12:12:16.492  3510  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{928b7f3 4361:android.process.acore/u0a5}
,05-19 12:12:16.492  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{8e1b609: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.502  4659  7438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-19 12:12:16.512  4659  7438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-19 12:12:16.512  3510  3854 I ActivityManager: Start proc 10305:com.samsung.android.app.taskedge/u0a67 for broadcast-3 com.samsung.android.app.taskedge/.TaskEdgeBroadcastReceiver
,05-19 12:12:16.512 10305 10305 E Zygote  : v2
,05-19 12:12:16.512 10305 10305 I libpersona: KNOX_SDCARD checking this for 10067
05-19 12:12:16.512 10305 10305 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:16.512 10305 10305 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:16.512 10305 10305 E Zygote  : accessInfo : 0
,05-19 12:12:16.522 10305 10305 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.taskedge 
05-19 12:12:16.522  4659  7438 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-19 12:12:16.522  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{187700e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.542 10305 10305 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:16.542 10305 10305 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:16.572  3510  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5423a4b 10305:com.samsung.android.app.taskedge/u0a67}
,05-19 12:12:16.582 10305 10305 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-19 12:12:16.582 10305 10305 D RelationGraph: garbageCollect()
,05-19 12:12:16.582 10305 10305 W ResourcesManager: getTopLevelResources: /system/priv-app/TaskEdgePanel/TaskEdgePanel.apk / 1.0 running in com.samsung.android.app.taskedge rsrc of package com.samsung.android.app.taskedge
,05-19 12:12:16.592  3510  4427 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 12:12:16.592 10305 10305 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:16.592 10305 10305 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.592 10305 10305 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:16.602 10305 10305 W System  : ClassLoader referenced unknown path: /system/priv-app/TaskEdgePanel/lib/arm64
,05-19 12:12:16.622 10305 10305 D InjectionManager: InjectionManager
05-19 12:12:16.622 10305 10305 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.taskedge
,05-19 12:12:16.622 10305 10305 I InjectionManager: Constructor com.samsung.android.app.taskedge, Feature store :{}
05-19 12:12:16.622 10305 10305 I InjectionManager: featureStore :{}
,05-19 12:12:16.622 10305 10305 I TaskEdgeBroadcastReceiver: onReceive:android.intent.action.PACKAGE_CHANGED
,05-19 12:12:16.632  3510  3530 I ActivityManager: Killing 9463:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #33
,05-19 12:12:16.632  3510  3530 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39d9ba7 4437:com.google.android.googlequicksearchbox:search/u0a72}
,05-19 12:12:16.652  4437 10318 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,05-19 12:12:16.652  3510  4406 D ActivityManager: cleanUpApplicationRecord -- 9463
,05-19 12:12:16.652  3510  4406 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,05-19 12:12:16.672  3510  4312 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39d9ba7 4437:com.google.android.googlequicksearchbox:search/u0a72}
,05-19 12:12:16.682  3510  4312 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{70ef49d 9980:com.samsung.android.app.FileShareServer/5005}
,05-19 12:12:16.692  9980  9980 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,05-19 12:12:16.702  3510  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{332c515 6617:com.enhance.gameservice/u0a111}
,05-19 12:12:16.712  4437 10318 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 63 ms] updated apps [took 63 ms] 
,05-19 12:12:16.732 10319 10319 E Zygote  : v2
05-19 12:12:16.732 10319 10319 I libpersona: KNOX_SDCARD checking this for 10112
05-19 12:12:16.732 10319 10319 I libpersona: KNOX_SDCARD not a persona
,05-19 12:12:16.732 10319 10319 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-19 12:12:16.732 10319 10319 E Zygote  : accessInfo : 0
,05-19 12:12:16.732 10319 10319 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.watchmanagerstub 
05-19 12:12:16.732  3510  4427 I ActivityManager: Start proc 10319:com.samsung.android.app.watchmanagerstub/u0a112 for broadcast-3 com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver
,05-19 12:12:16.762 10319 10319 D TimaKeyStoreProvider: TimaSignature is unavailable
05-19 12:12:16.762 10319 10319 D ActivityThread: Added TimaKeyStore provider
,05-19 12:12:16.772  3510  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d1b406 u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c8d1d41 10319:com.samsung.android.app.watchmanagerstub/u0a112}
,05-19 12:12:16.792 10319 10319 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-19 12:12:16.792 10319 10319 D RelationGraph: garbageCollect()
,05-19 12:12:16.792 10319 10319 W ResourcesManager: getTopLevelResources: /system/app/GearManagerStub/GearManagerStub.apk / 1.0 running in com.samsung.android.app.watchmanagerstub rsrc of package com.samsung.android.app.watchmanagerstub
,05-19 12:12:16.792  3510  3529 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-19 12:12:16.792 10319 10319 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-19 12:12:16.792 10319 10319 D ResourcesManager: For user 0 new overlays fetched Null
,05-19 12:12:16.802 10319 10319 I InjectionManager: Inside getClassLibPath caller 
,05-19 12:12:16.802 10099 10099 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
05-19 12:12:16.802 10099 10099 I dhcpcd  : wlan0: no IPv6 Routers available
,05-19 12:12:16.802  9666  9729 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
05-19 12:12:16.802  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-19 12:12:16.802  9666  9729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
05-19 12:12:16.802  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-19 12:12:16.802  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,05-19 12:12:16.802  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-19 12:12:16.802  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,05-19 12:12:16.802  9666 10276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-19 12:12:16.802  9666 10276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-19 12:12:16.802  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-19 12:12:16.802  9666 10276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,05-19 12:12:16.802  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-19 12:12:16.802  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-19 12:12:16.802  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-19 12:12:16.802  9666  9666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-19 12:12:16.802  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:16.802  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-19 12:12:16.802  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-19 12:12:16.802  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.802  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.802  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:16.802  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.812  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:16.812  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:16.812  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
05-19 12:12:16.812 10319 10319 W System  : ClassLoader referenced unknown path: /system/app/GearManagerStub/lib/arm64
,05-19 12:12:16.812  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:16.812 10319 10319 D InjectionManager: InjectionManager
05-19 12:12:16.812 10319 10319 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.watchmanagerstub
05-19 12:12:16.812  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:16.812  9666  9729 D BluetoothLeScanner: could not find callback wrapper
05-19 12:12:16.812  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-19 12:12:16.812  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.812  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:16.812  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.812  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-19 12:12:16.812 10319 10319 I InjectionManager: Constructor com.samsung.android.app.watchmanagerstub, Feature store :{}
05-19 12:12:16.812 10319 10319 I InjectionManager: featureStore :{}
05-19 12:12:16.812  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.812  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:16.812  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:16.812  9666  9729 D BluetoothLeAdvertiser: stop advertising
,05-19 12:12:16.822 10319 10319 D PackageIntentReceiver: onReceive::android.intent.action.PACKAGE_CHANGED
,05-19 12:12:16.822 10319 10319 D PackageIntentReceiver: ACTION_PACKAGE_CHANGED : com.google.android.gms
05-19 12:12:16.822 10319 10319 D PackageIntentReceiver: Not GearManger package! 
05-19 12:12:16.822  9763  9870 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:12:16.822  9763  9870 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:12:16.822  9763  9782 D BtGatt.AdvertiseManager: message : 1
05-19 12:12:16.822  9763  9791 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
05-19 12:12:16.822  9763  9791 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
,05-19 12:12:16.822  9763  9791 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 12:12:16.822  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 12:12:16.822  9763  9791 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-19 12:12:16.822  9763  9782 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-19 12:12:16.822  9763  9782 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-19 12:12:16.822  9763  9782 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
05-19 12:12:16.822  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{84572e6: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:16.832  9763  9780 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,05-19 12:12:16.832  9763  9780 D BtGatt.GattService: Client app is not null!
05-19 12:12:16.832  9666  9677 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
05-19 12:12:16.832  9763  9773 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-19 12:12:16.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-19 12:12:16.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-19 12:12:16.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:16.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.832  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-19 12:12:16.832  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,05-19 12:12:16.832  3510  4947 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2783027 u0 register_intent_action qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9616e 9557:com.google.android.talk:matchstick/u0a117}
,05-19 12:12:16.842  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,05-19 12:12:16.842  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:16.852  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:16.852  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 12:12:16.852  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.852  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:16.852  9666  9666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,05-19 12:12:16.852  9666  9666 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-19 12:12:16.852  9666  9666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-19 12:12:16.852  9666  9666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-19 12:12:16.852  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 12:12:16.852  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 12:12:16.852  9666  9666 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,05-19 12:12:16.852  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-19 12:12:16.852  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 12:12:16.852  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-19 12:12:16.852  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-19 12:12:16.852  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 12:12:16.852  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-19 12:12:16.852  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 12:12:16.852  9666  9666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,05-19 12:12:16.862  9557 10331 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } isPeriodic:false
,05-19 12:12:16.862  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{acd4c7d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.872  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{c65d772: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.872  9557 10331 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,05-19 12:12:16.872  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{32da7c3: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.872  3510  3529 I ActivityManager: Killing 9478:com.sec.android.widgetapp.samsungapps/u0a110 (adj 15): DHA:empty #33
,05-19 12:12:16.882  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{7600840: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.882  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{7e73379: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.892  3510  4312 D ActivityManager: cleanUpApplicationRecord -- 9478
,05-19 12:12:16.892  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{7b5f8be: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:16.902  3510  4312 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.samsungapps, Auto Run ON
,05-19 12:12:16.912  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{b38fd1f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:17.352  9666  9666 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-19 12:12:17.582  4659  7438 I Icing   : Indexing E1051AF754FD4764B2B13213EB917898AAC96AFB from com.google.android.gms
,05-19 12:12:17.592  4659  7438 I Icing   : Indexing done E1051AF754FD4764B2B13213EB917898AAC96AFB
,05-19 12:12:18.202  7981  7981 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
05-19 12:12:18.202  7981  7981 D PreloadUpdateManagerStateMachine: exit::IDLE
05-19 12:12:18.202  7981  7981 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,05-19 12:12:18.202  7981  7981 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,05-19 12:12:18.202  7981  7981 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,05-19 12:12:18.202  7981  7981 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
05-19 12:12:18.202  7981  7981 D PreloadUpdateManagerStateMachine: entry::IDLE
,05-19 12:12:18.322  3510  4150 E Watchdog: !@Sync 7 [05-19 12:12:18.331]
,05-19 12:12:19.092  3510  3975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-19 12:12:19.092  3510  3975 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4349, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 12:12:19.092  3510  3975 D BatteryService: online:4, current avg:73, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:189
05-19 12:12:19.092  3510  3510 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-19 12:12:19.102  3510  3510 I MotionRecognitionService: Plugged
,05-19 12:12:19.102  3510  3510 D MotionRecognitionService:   cableConnection= 1
05-19 12:12:19.102  3510  3510 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-19 12:12:19.102  3510  3510 D MotionRecognitionService: skip setTransmitPower. 
,05-19 12:12:19.102  3510  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-19 12:12:19.102  3942  3942 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-19 12:12:19.112  3942  3942 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-19 12:12:19.112  3942  3942 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-19 12:12:19.112  3942  3942 D KeyguardUpdateMonitor: handleBatteryUpdate
05-19 12:12:19.112  3942  3942 D PowerUI.Notification: There is no change about charging status, so return!
,05-19 12:12:19.132  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,05-19 12:12:19.142  9763  9763 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-19 12:12:19.142  5067  5067 D BatteryMonitor: new battery level: 100
05-19 12:12:19.142  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-19 12:12:19.142  9763  9802 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-19 12:12:19.142  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-19 12:12:19.852  9666  9729 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
05-19 12:12:19.852  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
05-19 12:12:19.852  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
05-19 12:12:19.852  9666  9729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
05-19 12:12:19.852  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
05-19 12:12:19.852  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 12:12:19.852  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,05-19 12:12:19.872  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-19 12:12:19.872  9666  9729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-19 12:12:19.872  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-19 12:12:19.872  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:19.882  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:19.882  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:19.892  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:19.892  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-19 12:12:19.892  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:19.902  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:19.902  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-19 12:12:19.902  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-19 12:12:19.902  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,05-19 12:12:19.902  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:19.912  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:19.922  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:19.922  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:19.922  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:19.922  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
05-19 12:12:19.922  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
05-19 12:12:19.922  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 9601
05-19 12:12:19.922  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=9601, mManufacturerData=null, mManufacturerDataMask=null]
,05-19 12:12:19.932  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:19.932  9666  9729 D BluetoothLeScanner: Start Scan
,05-19 12:12:19.932  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:19.932  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:19.942  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:19.942  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:19.952  9763  9816 D BtGatt.GattService: registerClient() - UUID=28f90d69-268d-4cc8-9525-acc887f8effd
,05-19 12:12:19.992  9763  9780 D BtGatt.GattService: onClientRegistered() - UUID=28f90d69-268d-4cc8-9525-acc887f8effd, clientIf=7
,05-19 12:12:19.992  9666  9677 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,05-19 12:12:19.992  9763  9869 D BtGatt.GattService: start scan with filters
,05-19 12:12:20.002  9763  9869 D BtGatt.GattService: getScanSettings
,05-19 12:12:20.022  9763  9869 D BtGatt.GattService: Is it foreground application = true
,05-19 12:12:20.022  9763  9869 D BtGatt.GattService: not a background application
,05-19 12:12:20.032  9763  9869 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,05-19 12:12:20.042  9763  9869 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 12:12:20.042  9763  9869 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:12:20.042  9763  9791 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_SCAN
05-19 12:12:20.042  9763  9791 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
,05-19 12:12:20.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
05-19 12:12:20.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:20.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
05-19 12:12:20.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:20.042  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-19 12:12:20.042  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-19 12:12:20.042  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 12:12:20.052  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
05-19 12:12:20.052  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-19 12:12:20.052  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 12:12:20.052  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
05-19 12:12:20.052  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,05-19 12:12:20.052  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
05-19 12:12:20.052  9763  9783 D BtGatt.ScanManager: handling starting scan
05-19 12:12:20.052  9763  9783 D BtGatt.ScanManager: isFilteringSupported
,05-19 12:12:20.052  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-19 12:12:20.052  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:20.052  9763  9783 D BluetoothAdapter: enableStandAloneBleMode=
,05-19 12:12:20.062  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:20.062  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,05-19 12:12:20.062  9763  9783 D BluetoothAdapter: STATE_ON
05-19 12:12:20.062  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:20.062  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:20.062  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-19 12:12:20.062  9763  9783 D BluetoothAdapter: STATE_ON
05-19 12:12:20.062  9763  9791 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.rockwellautomation.thalitest : 2
05-19 12:12:20.062  9763  9791 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.rockwellautomation.thalitest, com.rockwellautomation.thalitest
05-19 12:12:20.072  9763  9783 D BluetoothAdapter: STATE_ON
05-19 12:12:20.072  9763  9783 D BluetoothAdapter: STATE_ON
,05-19 12:12:20.072  9763  9783 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dfb586d
,05-19 12:12:20.072  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-19 12:12:20.072  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{6ee9f58: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:20.072  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-19 12:12:20.072  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-19 12:12:20.072  9666  9666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,05-19 12:12:20.072  9763  9791 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.rockwellautomation.thalitest : 1
,05-19 12:12:20.072  9763  9791 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.rockwellautomation.thalitest : 24919812
05-19 12:12:20.072  9763  9791 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.rockwellautomation.thalitest : 2
05-19 12:12:20.082  9763  9791 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.rockwellautomation.thalitest : 2
,05-19 12:12:20.082  9763  9791 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-19 12:12:20.082  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 12:12:20.082  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, A time : 0 => 0
05-19 12:12:20.082  9763  9791 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-19 12:12:20.082  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 12:12:20.082  9763  9780 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,05-19 12:12:20.082  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-19 12:12:20.082  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{e36d8b1: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:20.082  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, A time : 0 => 0
05-19 12:12:20.082  9763  9791 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.rockwellautomation.thalitest : 2
,05-19 12:12:20.082  9763  9791 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-19 12:12:20.082  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 12:12:20.082  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, A time : 0 => 0
05-19 12:12:20.082  9763  9791 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.rockwellautomation.thalitest : 24919812
05-19 12:12:20.082  9763  9783 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
,05-19 12:12:20.082  9763  9783 D BtGatt.ScanManager: High Rssi Filter value is = -128
05-19 12:12:20.082  9763  9783 D BtGatt.ScanManager: Low Rssi Filter value is = -128
05-19 12:12:20.082  9763  9783 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
05-19 12:12:20.082  9763  9780 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
,05-19 12:12:20.082  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 12:12:20.082  9763  9783 D BtGatt.ScanManager: Starting BLE batch scan
,05-19 12:12:20.082  9763  9783 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
05-19 12:12:20.082  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{d466196: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:20.092  9763  9780 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,05-19 12:12:20.092  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-19 12:12:20.092  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{8b77117: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:20.092  9763  9780 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,05-19 12:12:20.092  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-19 12:12:20.092  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{95a5904: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
,05-19 12:12:20.092  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{faf4eed: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:20.102  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{fff0122: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:20.102  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{43807b3: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:20.112  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{5a60170: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:20.112  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{8beece9: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:20.122  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{ab00d6e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:20.122  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{2216c0f: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:20.132  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{9c1c49c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:20.132  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{e106ea5: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:20.142  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{753927a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:20.572  9666  9666 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,05-19 12:12:20.572  9666  9666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
05-19 12:12:20.572  9666  9666 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,05-19 12:12:20.822  3510  6241 D SSRM:n  : SIOP:: AP = 310, PST = 321 (W:14), CP = 261, CUR = 73, LCD = 40
,05-19 12:12:21.092  3510  3815 V AlarmManager: Expired Alarm result :4
,05-19 12:12:21.102  9763  9763 D BtGatt.ScanManager: awakened up at time 226672
,05-19 12:12:21.102  9763  9783 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-19 12:12:21.102  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{748e88: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:21.102  9763  9780 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
05-19 12:12:21.102  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-19 12:12:21.102  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{a3e5021: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
,05-19 12:12:21.132  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{3785c46: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:21.132  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{a80ce07: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:21.212  7981  7981 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
05-19 12:12:21.212  7981  7981 D PreloadUpdateManagerStateMachine: exit::IDLE
05-19 12:12:21.212  7981  7981 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,05-19 12:12:21.212  7981  7981 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,05-19 12:12:21.212  7981  7981 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,05-19 12:12:21.212  7981  7981 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
05-19 12:12:21.212  7981  7981 D PreloadUpdateManagerStateMachine: entry::IDLE
,05-19 12:12:21.312  9877  9877 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,05-19 12:12:21.312  3510  3975 I ActivityManager: Killing 9493:com.samsung.android.app.mirrorlink/1000 (adj 15): DHA:empty #33
,05-19 12:12:21.342  3510  3530 D ActivityManager: cleanUpApplicationRecord -- 9493
,05-19 12:12:21.342  3510  3530 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.mirrorlink, Auto Run ON
,05-19 12:12:22.112  3510  3815 V AlarmManager: Expired Alarm result :4
,05-19 12:12:22.112  9763  9763 D BtGatt.ScanManager: awakened up at time 227686
,05-19 12:12:22.112  9763  9783 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-19 12:12:22.122  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{4cdf6d2: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:22.122  9763  9780 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
05-19 12:12:22.122  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-19 12:12:22.132  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{55243a3: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
,05-19 12:12:22.142  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{7b4a6a0: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:22.152  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{26fe259: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.062  9666  9729 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
05-19 12:12:23.062  9666  9729 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
05-19 12:12:23.062  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
05-19 12:12:23.062  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 12:12:23.072  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:12:23.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:12:23.072  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:23.072  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-19 12:12:23.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"A8:81:95:E9:5F:6F"}
,05-19 12:12:23.082  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"A8:81:95:E9:5F:6F"}
05-19 12:12:23.082  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
05-19 12:12:23.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 9601
05-19 12:12:23.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
05-19 12:12:23.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
05-19 12:12:23.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
05-19 12:12:23.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
05-19 12:12:23.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
05-19 12:12:23.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
05-19 12:12:23.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
05-19 12:12:23.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:23.082  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
05-19 12:12:23.082  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.082  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:23.082  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-19 12:12:23.082  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-19 12:12:23.082  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:23.082  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.082  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:23.082  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:23.092  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:23.092  9763  9869 D BtGatt.GattService: flushPendingBatchResults - clientIf=7, isServer=false
05-19 12:12:23.092  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-19 12:12:23.092  9763  9783 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-19 12:12:23.092  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:23.092  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{a70ae1e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.092  9763  9780 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
05-19 12:12:23.092  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{3b76ff: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.092  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 12:12:23.092  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:23.092  9666  9729 D BluetoothLeScanner: Stop Scan
,05-19 12:12:23.112  9763  9817 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:12:23.112  9763  9817 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:12:23.112  9763  9817 D BtGatt.GattService: stopScan() - queue size =1
05-19 12:12:23.112  9763  9791 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_SCAN
05-19 12:12:23.112  9763  9791 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 12:12:23.112  9763  9791 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-19 12:12:23.112  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 12:12:23.112  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, A time : 0 => 0
05-19 12:12:23.112  9763  9791 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest at  BLE_SCAN_ACTUAL_DB
,05-19 12:12:23.112  9763  9791 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest at  BLE_SCAN_REQUESTED_DB
05-19 12:12:23.112  9763  9774 D BtGatt.GattService: unregisterClient() - clientIf=7
05-19 12:12:23.112  9763  9783 D BtGatt.ScanManager: filter size is 1
,05-19 12:12:23.112  9763  9783 D BtGatt.ScanManager: delete FilterIndex - 3
05-19 12:12:23.112  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-19 12:12:23.112  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{fcd8ccc: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.112  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.112  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,05-19 12:12:23.112  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.112  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,05-19 12:12:23.112  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.112  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.112  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
05-19 12:12:23.112  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
05-19 12:12:23.112  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 9601
,05-19 12:12:23.112  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=9601, mManufacturerData=null, mManufacturerDataMask=null]
05-19 12:12:23.112  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.112  9666  9729 D BluetoothLeScanner: Start Scan
05-19 12:12:23.112  9763  9780 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
05-19 12:12:23.112  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 12:12:23.112  9763  9783 D BtGatt.ScanManager: stopping BLe Batch
,05-19 12:12:23.122  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:23.122  9763  9780 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
05-19 12:12:23.122  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 12:12:23.122  9763  9783 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-19 12:12:23.122  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:23.122  9763  9780 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
05-19 12:12:23.122  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 12:12:23.122  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:23.122  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{d334b15: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.132  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:23.132  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{6f58e2a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.132  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{65a841b: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.132  9763  9801 D BtGatt.GattService: registerClient() - UUID=1ef61b63-62b4-48c6-bf29-40b628b30942
,05-19 12:12:23.132  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{aca9b8: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.142  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{18a8391: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.152  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{f3662f6: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.152  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{c9346f7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.162  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{45ea964: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.162  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{b42c7cd: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.172  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{9ddb882: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.172  9763  9780 D BtGatt.GattService: onClientRegistered() - UUID=1ef61b63-62b4-48c6-bf29-40b628b30942, clientIf=7
,05-19 12:12:23.172  9666 10185 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,05-19 12:12:23.172  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{82b5b93: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:23.172  9763  9816 D BtGatt.GattService: start scan with filters
,05-19 12:12:23.182  9763  9816 D BtGatt.GattService: getScanSettings
,05-19 12:12:23.182  9763  9816 D BtGatt.GattService: Is it foreground application = true
05-19 12:12:23.182  9763  9816 D BtGatt.GattService: not a background application
,05-19 12:12:23.182  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{70ef7d0: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.182  9763  9816 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,05-19 12:12:23.192  9763  9816 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 12:12:23.192  9763  9816 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:12:23.192  9763  9791 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_SCAN
,05-19 12:12:23.192  9763  9791 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 12:12:23.192  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
05-19 12:12:23.192  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.192  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,05-19 12:12:23.192  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.192  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.192  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-19 12:12:23.192  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
05-19 12:12:23.192  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-19 12:12:23.192  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
05-19 12:12:23.192  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
05-19 12:12:23.192  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 12:12:23.192  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,05-19 12:12:23.192  9666  9729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-19 12:12:23.192  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-19 12:12:23.192  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-19 12:12:23.192  9763  9783 D BtGatt.ScanManager: handling starting scan
05-19 12:12:23.192  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-19 12:12:23.192  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,05-19 12:12:23.192  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-19 12:12:23.192  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-19 12:12:23.192  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-19 12:12:23.192  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
05-19 12:12:23.192  9666  9666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-19 12:12:23.192  9763  9783 D BluetoothAdapter: STATE_ON
05-19 12:12:23.192  9666 10338 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-19 12:12:23.202  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-19 12:12:23.202  9666  9729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-19 12:12:23.202  9666 10338 D BluetoothSocket: bindListen(): myUserId = 0
05-19 12:12:23.202  9666 10338 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-19 12:12:23.202  9763  9783 D BluetoothAdapter: STATE_ON
,05-19 12:12:23.202  9763  9791 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.rockwellautomation.thalitest : 3
05-19 12:12:23.202  9763  9791 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.rockwellautomation.thalitest, com.rockwellautomation.thalitest
,05-19 12:12:23.202  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:23.212  9666 10338 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,05-19 12:12:23.212  9666 10338 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@48f8716, port: 6, type: 1, local socket address: null, socket type: 0
,05-19 12:12:23.212  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:23.212  9763  9780 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,05-19 12:12:23.212  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{bc113c9: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:23.212  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 12:12:23.212  9763  9783 D BtGatt.ScanManager: set filter index= 4 for clientIf= 7
,05-19 12:12:23.212  9763  9783 D BtGatt.ScanManager: High Rssi Filter value is = -128
05-19 12:12:23.212  9763  9783 D BtGatt.ScanManager: Low Rssi Filter value is = -128
05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.rockwellautomation.thalitest : 2,
05-19 12:12:23.212  9763  9783 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.rockwellautomation.thalitest : 24919812
05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.rockwellautomation.thalitest : 2
05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.rockwellautomation.thalitest : 2
05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 12:12:23.212  9763  9780 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, A time : 0 => 0
05-19 12:12:23.212  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-19 12:12:23.212  9763  9783 D BtGatt.ScanManager: Starting BLE batch scan
05-19 12:12:23.212  9763  9783 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,05-19 12:12:23.222  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{bb2dace: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 12:12:23.222  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{3261def: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, A time : 0 => 0
05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.rockwellautomation.thalitest : 2
,05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, A time : 0 => 0
05-19 12:12:23.212  9763  9791 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.rockwellautomation.thalitest : 24919812
05-19 12:12:23.212  9763  9780 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
05-19 12:12:23.212  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-19 12:12:23.222  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:23.222  9763  9780 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
05-19 12:12:23.222  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 12:12:23.222  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:23.222  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:23.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:23.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.232  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,05-19 12:12:23.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-19 12:12:23.232  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "2c7c4446-495b-40f1-ba37-3ac33ac5ee28", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-19 12:12:23.232  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 A8 81 95 E9 5F 6F
05-19 12:12:23.232  9666  9729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-19 12:12:23.232  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-19 12:12:23.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-19 12:12:23.232  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{a33c0fc: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:23.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-19 12:12:23.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.232  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.232  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[2c7c4446-495b-40f1-ba37-3ac33ac5ee28], mManufacturerSpecificData={}, mServiceData={2c7c4446-495b-40f1-ba37-3ac33ac5ee28=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.232  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:23.232  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:23.232  9666  9729 D BluetoothLeAdvertiser: start advertising
,05-19 12:12:23.232  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:23.232  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{bbe2385: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.242  9763  9801 D BtGatt.GattService: registerClient() - UUID=109231f2-df2f-46af-9a75-f482b7b3de44
,05-19 12:12:23.242  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{ca5d5da: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.242  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{a60aa0b: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.252  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{e79f0e8: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.252  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{cc27301: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.262  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{19b75a6: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.262  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{16ddbe7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.262  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{713394: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.272  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{6623e3d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.272  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{6f94632: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.282  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{8324f83: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.282  9763  9780 D BtGatt.GattService: onClientRegistered() - UUID=109231f2-df2f-46af-9a75-f482b7b3de44, clientIf=8
,05-19 12:12:23.282  9666  9676 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,05-19 12:12:23.282  9763  9774 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-19 12:12:23.292  9763  9774 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 12:12:23.292  9763  9774 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 12:12:23.292  9763  9791 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
05-19 12:12:23.292  9763  9791 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 12:12:23.292  9763  9782 D BtGatt.AdvertiseManager: message : 0
05-19 12:12:23.292  9763  9782 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-19 12:12:23.292  9763  9782 D BtGatt.AdvertiseManager: size of list is =0
,05-19 12:12:23.292  9763  9782 D BtGatt.AdvertiseManager: starting advertising
,05-19 12:12:23.292  9763  9782 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-19 12:12:23.292  9763  9791 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 11
05-19 12:12:23.292  9763  9791 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24919812
,05-19 12:12:23.292  9763  9791 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-19 12:12:23.292  9763  9791 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 12:12:23.302  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 12:12:23.302  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{3f7f500: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.302  9763  9780 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,05-19 12:12:23.302  9763  9782 D BtGatt.AdvertiseManager: starting multi advertising
,05-19 12:12:23.302  9763  9780 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,05-19 12:12:23.302  9763  9782 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-19 12:12:23.302  9763  9782 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-19 12:12:23.302  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{b398139: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.302  9763  9782 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
05-19 12:12:23.302  9763  9782 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
05-19 12:12:23.302  9666  9677 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-19 12:12:23.302  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:23.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-19 12:12:23.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.302  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:23.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:23.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
05-19 12:12:23.302  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
05-19 12:12:23.302  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-19 12:12:23.312  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-19 12:12:23.312  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:23.312  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{7f1937e: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.312  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:23.312  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.312  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:23.312  9666  9666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,05-19 12:12:23.312  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-19 12:12:23.312  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-19 12:12:23.312  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-19 12:12:23.312  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{e4060df: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:23.312  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,05-19 12:12:23.312  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-19 12:12:23.312  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-19 12:12:23.312  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 12:12:23.312  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
05-19 12:12:23.312  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
05-19 12:12:23.312  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 12:12:23.312  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-19 12:12:23.312  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 12:12:23.312  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-19 12:12:23.312  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-19 12:12:23.322  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-19 12:12:23.322  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
05-19 12:12:23.322  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-19 12:12:23.322  9666  9666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-19 12:12:23.322  9666  9666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,05-19 12:12:23.322  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{a67612c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.322  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{1a7f7f5: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.332  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{e8f698a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.332  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{ff42bfb: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:23.832  9666  9666 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
05-19 12:12:23.832  9666  9666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
05-19 12:12:23.832  9666  9666 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,05-19 12:12:24.222  3510  3815 V AlarmManager: Expired Alarm result :4
,05-19 12:12:24.232  9763  9763 D BtGatt.ScanManager: awakened up at time 229802
,05-19 12:12:24.232  9763  9783 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-19 12:12:24.232  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{c4d1e71: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:24.232  9763  9780 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,05-19 12:12:24.232  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-19 12:12:24.242  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{8829456: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
,05-19 12:12:24.252  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{94f8cd7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:24.262  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{912a9c4: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:25.242  3510  3815 V AlarmManager: Expired Alarm result :4
,05-19 12:12:25.242  9763  9763 D BtGatt.ScanManager: awakened up at time 230817
,05-19 12:12:25.242  9763  9783 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-19 12:12:25.252  9763  9780 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,05-19 12:12:25.252  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{cab9fe2: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:25.252  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 12:12:25.252  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{a961f73: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
,05-19 12:12:25.272  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{5729e30: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:25.282  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{7202aa9: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:25.562  3510  6262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-19 12:12:26.252  3510  3815 V AlarmManager: Expired Alarm result :4
,05-19 12:12:26.262  9763  9763 D BtGatt.ScanManager: awakened up at time 231834
,05-19 12:12:26.262  9763  9783 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,05-19 12:12:26.262  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{aa93fcf: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:26.272  9763  9780 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,05-19 12:12:26.272  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 12:12:26.272  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{49b6d5c: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.292  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{2a7c865: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.302  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{39d493a: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.322  9666  9729 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,05-19 12:12:26.322  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-19 12:12:26.322  9666  9729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-19 12:12:26.322  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,05-19 12:12:26.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-19 12:12:26.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,05-19 12:12:26.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-19 12:12:26.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-19 12:12:26.322  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,05-19 12:12:26.322  9666  9729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaa1c0 removed from the list
05-19 12:12:26.322  9666 10338 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-19 12:12:26.322  9666 10338 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-19 12:12:26.322  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aaa1c0 removed from the list
,05-19 12:12:26.322  9666 10338 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,05-19 12:12:26.322  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-19 12:12:26.322  9666  9729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-19 12:12:26.322  9666  9666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,05-19 12:12:26.332  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{32409eb: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:26.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.322  9666  9666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-19 12:12:26.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,05-19 12:12:26.322  9666  9666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-19 12:12:26.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-19 12:12:26.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:26.332  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{8200348: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
05-19 12:12:26.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.322  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
05-19 12:12:26.322  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.322  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:26.322  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:26.332  9763  9816 D BtGatt.GattService: flushPendingBatchResults - clientIf=7, isServer=false
05-19 12:12:26.332  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
05-19 12:12:26.332  9763  9783 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
05-19 12:12:26.332  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:26.332  9763  9780 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
05-19 12:12:26.332  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-19 12:12:26.332  9666  9729 D BluetoothAdapter: STATE_ON
05-19 12:12:26.332  9666  9729 D BluetoothLeScanner: Stop Scan
05-19 12:12:26.342  9763  9773 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:12:26.342  9763  9773 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 12:12:26.342  9763  9773 D BtGatt.GattService: stopScan() - queue size =1
05-19 12:12:26.342  9763  9791 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_SCAN
05-19 12:12:26.342  9763  9791 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 12:12:26.342  9763  9791 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-19 12:12:26.342  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-19 12:12:26.342  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, A time : 0 => 0
05-19 12:12:26.342  9763  9791 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest at  BLE_SCAN_ACTUAL_DB
05-19 12:12:26.342  9763  9791 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest at  BLE_SCAN_REQUESTED_DB
,05-19 12:12:26.342  9763  9816 D BtGatt.GattService: unregisterClient() - clientIf=7
05-19 12:12:26.342  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{85185e1: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.352  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-19 12:12:26.352  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.352  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,05-19 12:12:26.352  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.352  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.352  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.352  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-19 12:12:26.352  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.352  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:26.352  9666  9729 D BluetoothAdapter: STATE_ON
,05-19 12:12:26.352  9763  9783 D BtGatt.ScanManager: filter size is 1
,05-19 12:12:26.352  9666  9729 D BluetoothLeAdvertiser: stop advertising
05-19 12:12:26.352  9763  9783 D BtGatt.ScanManager: delete FilterIndex - 4
05-19 12:12:26.352  9763  9780 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
05-19 12:12:26.352  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,05-19 12:12:26.362  9763  9783 D BtGatt.ScanManager: stopping BLe Batch
,05-19 12:12:26.362  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{e86bf06: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:26.362  9763  9870 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-19 12:12:26.362  9763  9870 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-19 12:12:26.362  9763  9782 D BtGatt.AdvertiseManager: message : 1
05-19 12:12:26.362  9763  9791 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
05-19 12:12:26.362  9763  9791 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 19, currDate: 19
05-19 12:12:26.362  9763  9791 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-19 12:12:26.362  9763  9791 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-19 12:12:26.362  9763  9780 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
05-19 12:12:26.362  9763  9791 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-19 12:12:26.362  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 12:12:26.362  9763  9783 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
05-19 12:12:26.362  9763  9780 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,05-19 12:12:26.362  9763  9780 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
05-19 12:12:26.362  9763  9782 D BtGatt.AdvertiseManager: stop advertise for client =  8
05-19 12:12:26.362  9763  9782 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
05-19 12:12:26.362  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{23759c7: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.362  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{5d60bf4: PendingIntentRecord{18970b8 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.372  9763  9782 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-19 12:12:26.372  9763  9780 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
05-19 12:12:26.372  9763  9780 D BtGatt.GattService: Client app is not null!
05-19 12:12:26.372  9666  9677 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-19 12:12:26.372  9763  9816 D BtGatt.GattService: unregisterClient() - clientIf=8
05-19 12:12:26.372  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{67f9f1d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.372  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-19 12:12:26.372  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.372  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-19 12:12:26.372  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.372  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:26.372  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.372  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-19 12:12:26.372  9666  9729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-19 12:12:26.372  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 12:12:26.372  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:26.382  3510  4518 V AlarmManager:  remove PendingIntent] PendingIntent{43fc592: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:26.382  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-134,7,main], id: 134
,05-19 12:12:26.382  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 12:12:26.382  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.382  9666  9729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-134,7,main], id: 134
05-19 12:12:26.382  9666  9729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f8ef9 removed from the list
05-19 12:12:26.382  9666  9729 D io.jxcore.node.ConnectivityMonitor: stop
,05-19 12:12:26.382  9666  9729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-19 12:12:26.382  9666  9729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-19 12:12:26.382  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 12:12:26.382  9666  9666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-19 12:12:26.382  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-19 12:12:26.382  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 12:12:26.382  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-19 12:12:26.382  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,05-19 12:12:26.382  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-19 12:12:26.382  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-19 12:12:26.382  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 12:12:26.382  9666  9666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-19 12:12:26.382  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-19 12:12:26.382  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-19 12:12:26.382  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-19 12:12:26.382  3510  4427 V AlarmManager:  remove PendingIntent] PendingIntent{e45cb63: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:26.382  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,05-19 12:12:26.382  9666  9666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-19 12:12:26.382  9666  9666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-19 12:12:26.382  9666  9729 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
05-19 12:12:26.382  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
05-19 12:12:26.382  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
05-19 12:12:26.382  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
05-19 12:12:26.382  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,05-19 12:12:26.382  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
05-19 12:12:26.382  9666  9729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
05-19 12:12:26.382  9666  9729 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,05-19 12:12:26.392  9666  9729 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,05-19 12:12:26.392  3510  4313 V AlarmManager:  remove PendingIntent] PendingIntent{941f360: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
05-19 12:12:26.392  9666  9729 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,05-19 12:12:26.392  9666  9729 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,05-19 12:12:26.392  9666  9729 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,05-19 12:12:26.392  9666  9729 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
05-19 12:12:26.392  3510  4059 V AlarmManager:  remove PendingIntent] PendingIntent{57c1019: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.392  9666  9729 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,05-19 12:12:26.402  9666  9729 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,05-19 12:12:26.402  3510  4983 V AlarmManager:  remove PendingIntent] PendingIntent{f10a8de: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.402  3510  3529 V AlarmManager:  remove PendingIntent] PendingIntent{73fbabf: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.412  3510  4947 V AlarmManager:  remove PendingIntent] PendingIntent{fc2e58c: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.412  3510  3975 V AlarmManager:  remove PendingIntent] PendingIntent{e3494d5: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.412  3510  4409 V AlarmManager:  remove PendingIntent] PendingIntent{37a74ea: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.422  3510  4406 V AlarmManager:  remove PendingIntent] PendingIntent{1bf43db: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.422  3510  4312 V AlarmManager:  remove PendingIntent] PendingIntent{b7ece78: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.432  3510  4257 V AlarmManager:  remove PendingIntent] PendingIntent{b6a951: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.432  3510  4040 V AlarmManager:  remove PendingIntent] PendingIntent{b02f5b6: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.442  3510  3854 V AlarmManager:  remove PendingIntent] PendingIntent{7e442b7: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.442  3510  3530 V AlarmManager:  remove PendingIntent] PendingIntent{90e5a24: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.452  3510  4407 V AlarmManager:  remove PendingIntent] PendingIntent{66b898d: PendingIntentRecord{e67c7a3 com.android.bluetooth broadcastIntent}}
,05-19 12:12:26.882  9666  9666 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-19 12:12:28.402  9666  9729 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,05-19 12:12:28.572  9666 10341 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 266, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:28.572  9666 10341 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:28.572  9666 10341 D io.jxcore.node.StreamCopyingThread:  id: 83
,05-19 12:12:29.132  3510  3854 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-19 12:12:29.132  3510  3854 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4252, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-19 12:12:29.132  3510  3854 D BatteryService: online:4, current avg:98, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-433
05-19 12:12:29.132  3510  3510 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-19 12:12:29.142  3510  3510 I MotionRecognitionService: Plugged
05-19 12:12:29.142  3510  3510 D MotionRecognitionService:   cableConnection= 1
05-19 12:12:29.142  3510  3510 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-19 12:12:29.142  3510  3510 D MotionRecognitionService: skip setTransmitPower. 
,05-19 12:12:29.142  3510  3863 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-19 12:12:29.142  3942  3942 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-19 12:12:29.142  3942  3942 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-19 12:12:29.152  3942  3942 D KeyguardUpdateMonitor: handleBatteryUpdate
05-19 12:12:29.152  3942  3942 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-19 12:12:29.152  3942  3942 D PowerUI.Notification: There is no change about charging status, so return!
,05-19 12:12:29.162  5067  5067 D CommonServiceConfiguration: getStringValueSetting
,05-19 12:12:29.172  5067  5067 D BatteryMonitor: new battery level: 100
,05-19 12:12:29.172  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-19 12:12:29.172  9763  9763 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-19 12:12:29.172  3942  3942 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-19 12:12:29.172  9763  9802 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-19 12:12:29.332  9666 10341 W !!      : call onHalfStreamCopied
,05-19 12:12:29.332  9666 10341 I testCopyDataAndClose: closing input stream
,05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 266, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread:  id: 83
05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread:  id: 83
05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 266, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:30.032  9666 10341 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,05-19 12:12:30.842  3510  6241 D SSRM:n  : SIOP:: AP = 330, PST = 322 (W:6), CP = 258, CUR = 98, LCD = 40
,05-19 12:12:31.192  3510  3612 D PowerManagerService: [s] UserActivityState : 1 -> 2
05-19 12:12:31.192  3510  3612 D PowerManagerService: mDisplayReady: false
05-19 12:12:31.192  3510  3612 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 12:12:31.192  3510  3612 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-19 12:12:31.192  3510  3612 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
05-19 12:12:31.192  3510  3612 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,05-19 12:12:31.192  3510  3612 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,05-19 12:12:31.192  3510  3612 D PowerManagerService: mDisplayReady: true
,05-19 12:12:31.212  3510  3906 D lights  : lcd : 33 +
,05-19 12:12:31.212  3510  3906 D lights  : lcd : 33 -
,05-19 12:12:31.212  3510  3612 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 12:12:31.212  3510  3612 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-19 12:12:31.212  3510  3612 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
,05-19 12:12:31.212  3510  3612 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,05-19 12:12:31.222  3510  3906 D lights  : lcd : 30 +
05-19 12:12:31.222  3510  3612 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 12:12:31.222  3510  3612 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-19 12:12:31.222  3510  3612 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
,05-19 12:12:31.222  3510  3906 D lights  : lcd : 30 -
05-19 12:12:31.222  3510  3612 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
05-19 12:12:31.222  3510  3612 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-19 12:12:31.222  3510  3612 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-19 12:12:31.222  3510  3612 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
,05-19 12:12:31.222  3510  3612 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,05-19 12:12:32.462  9666  9729 I StreamCopyingThreadTest: Starting test: testCopyBigData
,05-19 12:12:32.502  9666 10346 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 269, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:32.502  9666 10346 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:32.502  9666 10346 D io.jxcore.node.StreamCopyingThread:  id: 85
,05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 269, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread:  id: 85
05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread:  id: 85
05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 269, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-19 12:12:34.022  9666 10346 D io.jxcore.node.StreamCopyingThread:  id: 85 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520

```
