#### Test 124853546fd55b4f_thali05_samsung-SM-G930F Logs


```
--------- beginning of system
,06-09 17:15:17.404  3503  4403 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-09 17:15:17.404  3503  4403 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-09 17:15:17.404  3503  4403 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-09 17:15:17.404  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-09 17:15:17.404  3503  3503 I MotionRecognitionService: Plugged
06-09 17:15:17.404  3503  3503 D MotionRecognitionService:   cableConnection= 1
06-09 17:15:17.404  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-09 17:15:17.404  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
06-09 17:15:17.414  3503  3857 D WifiController: ApOrStaEnabledState  msg.what= 155652
06-09 17:15:17.414  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-09 17:15:17.414  3933  3933 D KeyguardUpdateMonitor: handleBatteryUpdate
06-09 17:15:17.414  3933  3933 D PowerUI : priorPlugType = 2 mPlugType =  2
06-09 17:15:17.424  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-09 17:15:17.434  5001  5001 D CommonServiceConfiguration: getStringValueSetting
06-09 17:15:17.434  4953  4953 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-09 17:15:17.434  4953  5386 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-09 17:15:17.444  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-09 17:15:17.444  5001  5001 D BatteryMonitor: new battery level: 100
06-09 17:15:17.884  9360  9360 I FIPS_bssl: FIPS approved mode (1) | 9360 | app_process
06-09 17:15:17.894  9360  9360 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-09 17:15:17.894  9360  9360 D AndroidRuntime: CheckJNI is OFF
06-09 17:15:17.894  9360  9360 D AndroidRuntime: readGMSProperty: start
06-09 17:15:17.894  9360  9360 D AndroidRuntime: readGMSProperty: already setted!!
06-09 17:15:17.894  9360  9360 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-09 17:15:17.894  9360  9360 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-09 17:15:17.894  9360  9360 D AndroidRuntime: readGMSProperty: end
06-09 17:15:17.894  9360  9360 D AndroidRuntime: addProductProperty: start
06-09 17:15:17.914  9360  9360 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-09 17:15:17.944  9360  9360 I Radio-JNI: register_android_hardware_Radio DONE
06-09 17:15:17.944  9360  9360 E AffinityControl: AffinityControl: registerfunction enter
06-09 17:15:17.954  9360  9360 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-09 17:15:17.984  3503  4293 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
06-09 17:15:17.984  3503  4293 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in null rsrc of package com.thaliproject.thalitest
06-09 17:15:18.014  3503  4293 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:15:18.014  3503  4293 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
06-09 17:15:18.014  3503  4293 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.thaliproject.thalitest)
06-09 17:15:18.014  3503  4293 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3503  pkgName : ACTIVITY_RESUME_BOOSTER@3
06-09 17:15:18.014  3503  4293 D ActivityManager: mDVFSHelper.acquire()
06-09 17:15:18.024  3503  4293 V WindowManager: addAppToken: AppWindowToken{d01f5466c token=Token{5ed931f ActivityRecord{ca726be u0 com.thaliproject.thalitest/.MainActivity t5}}} to stack=2 task=5 at 0
06-09 17:15:18.034  3503  3602 I InjectionManager: Inside getClassLibPath caller 
06-09 17:15:18.034  3503  4293 D InputDispatcher: Focused application set to: xxxx
06-09 17:15:18.034  3503  4293 D InputDispatcher: Focus left window: 6104
06-09 17:15:18.034  9360  9360 D AndroidRuntime: Shutting down VM
06-09 17:15:18.034  3503  3594 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{10115df u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
06-09 17:15:18.044  3933  3933 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
06-09 17:15:18.044  3503  3602 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{54ff704 V.E...... R.....ID 0,0-0,0}
06-09 17:15:18.044  3503  3602 D SecWifiDisplayUtil: Metadata value : SecSettings2
06-09 17:15:18.044  3503  3602 D ISSUE_DEBUG: InputChannelName : 4c8cf22 Starting com.thaliproject.thalitest
06-09 17:15:18.044  3503  3602 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3503 uid:1000
06-09 17:15:18.044  3503  3602 D PointerIcon: setMouseCustomIcon IconType is same.101
06-09 17:15:18.044  3011  3011 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
06-09 17:15:18.054  9370  9370 E Zygote  : v2
06-09 17:15:18.054  9370  9370 I libpersona: KNOX_SDCARD checking this for 10074
06-09 17:15:18.054  9370  9370 I libpersona: KNOX_SDCARD not a persona
06-09 17:15:18.054  9370  9370 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-09 17:15:18.054  3503  4408 I ActivityManager: Start proc 9370:com.thaliproject.thalitest/u0a74 for activity com.thaliproject.thalitest/.MainActivity
06-09 17:15:18.054  9370  9370 E Zygote  : accessInfo : 0
06-09 17:15:18.054  9370  9370 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.thaliproject.thalitest 
06-09 17:15:18.064  3503  3602 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
06-09 17:15:18.064  3503  3852 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
06-09 17:15:18.074  9370  9370 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:18.074  9370  9370 D ActivityThread: Added TimaKeyStore provider
06-09 17:15:18.074  3503  3525 V WindowOrientationListener: setCurrentAppOrientation :-1
06-09 17:15:18.074  3503  3525 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
06-09 17:15:18.074  3503  3525 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-09 17:15:18.074  3503  3525 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
06-09 17:15:18.074  3503  3525 D ActivityManager:  Launching com.thaliproject.thalitest, updated priority
06-09 17:15:18.074  4267  4267 D Launcher.HomeView: onStop
06-09 17:15:18.074  4267  4267 D capture : ----destroy
06-09 17:15:18.074  6677  6677 V ActivityThread: updateVisibility : ActivityRecord{3053e02 token=android.os.BinderProxy@528871d {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
06-09 17:15:18.084  4267  4267 V ActivityThread: updateVisibility : ActivityRecord{c9ea9a3 token=android.os.BinderProxy@9980970 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
06-09 17:15:18.084  3503  3503 D GameManagerService: NotifyRunnable. pkg: com.thaliproject.thalitest, type: 4, isMinimized: false, isTunableApp: false
06-09 17:15:18.084  3011  4541 D libEGL  : eglTerminate EGLDisplay = 0x7f8effee78
06-09 17:15:18.084  3011  4541 D libEGL  : eglTerminate EGLDisplay = 0x7f8effee78
06-09 17:15:18.094  3011  4296 D libEGL  : eglTerminate EGLDisplay = 0x7f991fee78
06-09 17:15:18.094  3011  4296 D libEGL  : eglTerminate EGLDisplay = 0x7f991fee78
06-09 17:15:18.094  3503  3592 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.thaliproject.thalitest
06-09 17:15:18.094  3503  3592 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
06-09 17:15:18.094  3503  3592 E MARsPolicyManager: getPackageInfo package com.rockwellautomation.thalitest not installed!
06-09 17:15:18.094  3503  6040 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
06-09 17:15:18.094  3503  6040 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
06-09 17:15:18.094  9370  9370 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
06-09 17:15:18.094  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd9b88708
06-09 17:15:18.094  3503  3981 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-09 17:15:18.094  3503  3602 V WindowStateAnimator: Finishing drawing window Window{4c8cf22 u0 d0 Starting com.thaliproject.thalitest}: mDrawState=DRAW_PENDING
06-09 17:15:18.094  9370  9370 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
06-09 17:15:18.094  4267  4267 D Launcher: onTrimMemory. Level: 20
06-09 17:15:18.104  3503  3594 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{4c8cf22 u0 d0 Starting com.thaliproject.thalitest}
06-09 17:15:18.104  9370  9370 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:15:18.104  9370  9370 I InjectionManager: Inside getClassLibPath caller 
06-09 17:15:18.114  3503  6040 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-09 17:15:18.114  3503  6040 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
06-09 17:15:18.114  9370  9370 D InjectionManager: InjectionManager
06-09 17:15:18.114  9370  9370 D InjectionManager: fillFeatureStoreMap com.thaliproject.thalitest
06-09 17:15:18.114  9370  9370 I InjectionManager: Constructor com.thaliproject.thalitest, Feature store :{}
06-09 17:15:18.114  3503  6040 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-09 17:15:18.114  9370  9370 I InjectionManager: featureStore :{}
06-09 17:15:18.124  3011  3021 D libEGL  : eglTerminate EGLDisplay = 0x7fa063ee78
06-09 17:15:18.124  3503  6040 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
06-09 17:15:18.124  3503  6040 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
06-09 17:15:18.124  3011  3021 D libEGL  : eglTerminate EGLDisplay = 0x7fa063ee78
06-09 17:15:18.124  9370  9370 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
06-09 17:15:18.124  9370  9370 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
06-09 17:15:18.124  9370  9370 D RelationGraph: garbageCollect()
06-09 17:15:18.124  9370  9370 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
06-09 17:15:18.144  9370  9370 I CordovaLog: Changing log level to DEBUG(3)
06-09 17:15:18.144  9370  9370 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
06-09 17:15:18.144  9370  9370 D CordovaActivity: CordovaActivity.onCreate()
06-09 17:15:18.154  9370  9370 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
06-09 17:15:18.154  3503  3515 I art     : Background partial concurrent mark sweep GC freed 85435(5MB) AllocSpace objects, 112(2MB) LOS objects, 31% free, 35MB/51MB, paused 1.206ms total 121.057ms
06-09 17:15:18.194  9370  9370 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.google.android.webview
06-09 17:15:18.194  9370  9370 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:15:18.194  9370  9370 I InjectionManager: Inside getClassLibPath caller 
06-09 17:15:18.204  9370  9370 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
06-09 17:15:18.234  9370  9370 I cr_LibraryLoader: Time to load native libraries: 17 ms (timestamps 4424-4441)
06-09 17:15:18.234  9370  9370 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
06-09 17:15:18.254  9370  9384 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.thaliproject.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,06-09 17:15:18.274  9370  9370 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {de8cfc3}
06-09 17:15:18.274  9370  9370 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,06-09 17:15:18.284  9370  9370 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,06-09 17:15:18.324  9370  9370 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,06-09 17:15:18.344  3503  3878 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,06-09 17:15:18.404  9370  9370 D libEGL  : eglInitialize EGLDisplay = 0xffacf004
,06-09 17:15:18.444  3503  3878 I MdnieScenarioControlService: mGameModeLauncher : false
,06-09 17:15:18.444  3503  3878 I MdnieScenarioControlService: setUIMode
,06-09 17:15:18.444  3503  3975 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10074
06-09 17:15:18.444  3503  3975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,06-09 17:15:18.464  3503  3852 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,06-09 17:15:18.484  3011  3021 I SurfaceFlinger: id=9 Removed MauncherAct (4/15)
06-09 17:15:18.484  3011  4296 I SurfaceFlinger: id=9 Removed MauncherAct (-2/15)
,06-09 17:15:18.484  3011  3974 I SurfaceFlinger: id=15 Removed YUIInstallC (4/14)
06-09 17:15:18.484  3011  3019 I SurfaceFlinger: id=15 Removed YUIInstallC (-2/14)
06-09 17:15:18.484  3011  3021 I SurfaceFlinger: id=14 Removed YUIInstallC (4/13)
,06-09 17:15:18.484  3011  4541 I SurfaceFlinger: id=14 Removed YUIInstallC (-2/13)
06-09 17:15:18.484  3011  3974 I SurfaceFlinger: id=17 Removed VSBConnecti (4/12)
06-09 17:15:18.484  3011  4296 I SurfaceFlinger: id=16 Removed VSBConnecti (5/11)
06-09 17:15:18.484  3011  4296 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
,06-09 17:15:18.484  3011  4541 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/11)
,06-09 17:15:18.484  3933  3933 D ImageWallpaper: onVisibilityChanged:false
,06-09 17:15:18.484  3933  3933 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
06-09 17:15:18.484  3933  3933 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
06-09 17:15:18.484  3933  3933 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,06-09 17:15:18.484  9370  9370 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9370
,06-09 17:15:18.484  3503  4413 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9370 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:18.484  3503  3863 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,06-09 17:15:18.484  3503  3863 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,06-09 17:15:18.494  3503  3863 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,06-09 17:15:18.494  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-09 17:15:18.494  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd9b88828
06-09 17:15:18.494  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd9b88828
06-09 17:15:18.494  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd9b88828
,06-09 17:15:18.494  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd9b88828
,06-09 17:15:18.494  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,06-09 17:15:18.494  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-09 17:15:18.504  9370  9370 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,06-09 17:15:18.504  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-09 17:15:18.504  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,06-09 17:15:18.504  3503  3863 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:18.514  9370  9370 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-09 17:15:18.514  9370  9370 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,06-09 17:15:18.544  9370  9370 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,06-09 17:15:18.544  9370  9370 D PluginManager: init()
,06-09 17:15:18.544  9370  9370 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,06-09 17:15:18.554  9370  9370 I cr_Ime  : ImeThread is not enabled.
,06-09 17:15:18.564  9370  9370 D Activity: performCreate Call Injection manager
,06-09 17:15:18.564  9370  9370 D CordovaActivity: Started the activity.
06-09 17:15:18.564  9370  9370 I InjectionManager: dispatchOnViewCreated > Target : com.thaliproject.thalitest.MainActivity isFragment :false
06-09 17:15:18.564  9370  9370 D CordovaActivity: Resumed the activity.
,06-09 17:15:18.564  9370  9370 D SecWifiDisplayUtil: Metadata value : SecSettings2
,06-09 17:15:18.574  9370  9370 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{567f61e I.E...... R.....ID 0,0-0,0}
,06-09 17:15:18.574  9370  9419 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-09 17:15:18.574  3503  3525 D ISSUE_DEBUG: InputChannelName : 8fa63da com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity
,06-09 17:15:18.574  3503  4209 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
06-09 17:15:18.584  3503  4209 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-09 17:15:18.584  3503  3503 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-09 17:15:18.584  3503  3503 I KnoxTimeoutHandler: Shared devices show user statefalse
,06-09 17:15:18.584  9370  9384 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.thaliproject.thalitest/shared_prefs/com.thaliproject.thalitest_preferences.xml.bak
,06-09 17:15:18.584  9370  9370 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9370
,06-09 17:15:18.584  3503  4408 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9370 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:18.584  3503  3863 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
06-09 17:15:18.584  3503  3863 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-09 17:15:18.584  3503  3863 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
06-09 17:15:18.594  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
06-09 17:15:18.594  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
06-09 17:15:18.594  3503  3852 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
06-09 17:15:18.594  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
06-09 17:15:18.594  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
06-09 17:15:18.604  9370  9370 D SecWifiDisplayUtil: Metadata value : SecSettings2
06-09 17:15:18.604  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
06-09 17:15:18.604  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
06-09 17:15:18.604  3503  3863 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:18.604  3011  3011 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
06-09 17:15:18.614  3503  4408 D InputDispatcher: Focus entered window: 9370
,06-09 17:15:18.614  3503  3602 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3503 uid:1000
06-09 17:15:18.614  3503  3602 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-09 17:15:18.614  9370  9419 D libEGL  : eglInitialize EGLDisplay = 0xdc96d7c4
06-09 17:15:18.614  9370  9419 I OpenGLRenderer: Initialized EGL, version 1.4
,06-09 17:15:18.614  9370  9419 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,06-09 17:15:18.624  9370  9370 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-09 17:15:18.644  9370  9423 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-09 17:15:18.644  9370  9423 D libEGL  : eglInitialize EGLDisplay = 0xd9c2c3e4
,06-09 17:15:18.654  9370  9423 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.thaliproject.thalitest
,06-09 17:15:18.664  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd9b88708
,06-09 17:15:18.664  3503  4845 V WindowStateAnimator: Finishing drawing window Window{8fa63da u0 d0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,06-09 17:15:18.664  9370  9370 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,06-09 17:15:18.664  3503  3848 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-09 17:15:18.664  3503  3602 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-09 17:15:18.664  3503  3503 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-09 17:15:18.664  3503  3602 I ActivityManager: Displayed com.thaliproject.thalitest/.MainActivity: +629ms
06-09 17:15:18.664  3503  3602 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3503  tag : ACTIVITY_RESUME_BOOSTER@3
,06-09 17:15:18.664  3503  3602 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ca726be u0 com.thaliproject.thalitest/.MainActivity t5} time:274879
06-09 17:15:18.664  3503  3602 D ActivityManager: mDVFSHelper.release()
06-09 17:15:18.674  3503  3602 D ViewRootImpl: #3 mView = null
06-09 17:15:18.674  3503  3592 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3503  pkgName : ACTIVITY_RESUME_BOOSTER@9
,06-09 17:15:18.674  3503  3503 I KnoxTimeoutHandler: SD activityfalse
,06-09 17:15:18.674  4746  4746 D SamsungIME: IMPL finishInput
,06-09 17:15:18.674  4746  4746 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
06-09 17:15:18.674  4746  4746 D SamsungIME: saveAndClear +
06-09 17:15:18.674  4746  4746 D SamsungIME: saveAndClear -
,06-09 17:15:18.684  3503  4414 V WindowStateAnimator: Finishing drawing window Window{8fa63da u0 d0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,06-09 17:15:18.684  9370  9370 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
06-09 17:15:18.684  9370  9370 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@cf7bae6 time:274895
,06-09 17:15:18.684  6104  6104 V ActivityThread: updateVisibility : ActivityRecord{77defa7 token=android.os.BinderProxy@50f40b1 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,06-09 17:15:18.684  9370  9370 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9370
,06-09 17:15:18.684  9370  9370 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
,06-09 17:15:18.694  9370  9370 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,06-09 17:15:18.694  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd9b88708
,06-09 17:15:18.734  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd9b88708
,06-09 17:15:18.804  9370  9370 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,06-09 17:15:18.864  3011  4296 I SurfaceFlinger: id=18 Removed uhalitest (7/11)
,06-09 17:15:18.864  3011  3019 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,06-09 17:15:18.874  9370  9432 D jxcore_app_log: JniHelper::setJavaVM(0xf4d34000), pthread_self() = -704644816
,06-09 17:15:18.884  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd9b88828
,06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3127bc9 added. We now have 1 listener(s)
,06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3127bc9 added. We now have 1 listener(s)
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-09 17:15:18.884  9370  9432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:2C:E6
06-09 17:15:18.884  9370  9432 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:2C:E6"Peer extra info: "256
,06-09 17:15:18.884  9370  9432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-09 17:15:18.884  9370  9432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-09 17:15:18.884  9370  9432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72248fc added. We now have 2 listener(s)
06-09 17:15:18.884  9370  9432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-09 17:15:18.884  9370  9432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-09 17:15:18.884  9370  9432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 38436
,06-09 17:15:18.884  9370  9432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 137
06-09 17:15:18.884  9370  9432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
06-09 17:15:18.884  9370  9432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
06-09 17:15:18.884  9370  9432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
06-09 17:15:18.884  9370  9432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 137
,06-09 17:15:18.894  9370  9432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-09 17:15:18.894  9370  9432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:2C:E6
,06-09 17:15:18.894  9370  9432 D BluetoothAdapter: STATE_ON
,06-09 17:15:18.894  9370  9432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
06-09 17:15:18.894  9370  9432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-09 17:15:18.894  9370  9432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:18.894  9370  9432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:18.894  9370  9432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-09 17:15:18.894  9370  9432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-09 17:15:18.894  9370  9432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-09 17:15:18.894  9370  9432 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-09 17:15:18.894  9370  9432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-09 17:15:18.894  9370  9432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-09 17:15:18.894  9370  9432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-09 17:15:18.894  9370  9432 D io.jxcore.node.ConnectivityMonitor: start: OK
06-09 17:15:18.894  9370  9432 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-09 17:15:18.894  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:18.904  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:18.904  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:18.904  9370  9370 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,06-09 17:15:18.904  9370  9370 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
06-09 17:15:18.904  9370  9370 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,06-09 17:15:18.954  3503  3878 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,06-09 17:15:18.974  3503  3503 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3503  tag : ACTIVITY_RESUME_BOOSTER@9
,06-09 17:15:19.054  3503  3878 I MdnieScenarioControlService: mGameModeLauncher : false
,06-09 17:15:19.064  3503  3878 I MdnieScenarioControlService: setUIMode
,06-09 17:15:19.064  4023  4023 D Recents : onTaskStackChanged
,06-09 17:15:19.074  4023  4023 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.thaliproject.thalitest
,06-09 17:15:19.094  4023  4023 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:19.094  3503  6042 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in null rsrc of package com.thaliproject.thalitest
,06-09 17:15:19.244  3503  6040 D SSRM:n  : SIOP:: AP = 320, PST = 300 (W:6), CP = 255, LCD = 40
,06-09 17:15:19.244  3503  6040 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-09 17:15:19.384  9370  9433 W jxcore-log: Initializing JXcore engine
06-09 17:15:19.384  9370  9433 W jxcore-log: JXcore engine is ready
,06-09 17:15:19.404  4962  4962 E audit   : type=1400 msg=audit(1497021319.404:264): avc:  denied  { ioctl } for  pid=9433 comm="Thread-138" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-09 17:15:19.404  4962  4962 E audit   :  SEPF_SECMOBILE_6.0.1_0031
06-09 17:15:19.404  4962  4962 E audit   : type=1300 msg=audit(1497021319.404:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=1 a3=d53bf3c8 items=0 ppid=3179 pid=9433 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-09 17:15:19.404  4962  4962 E audit   : type=1327 msg=audit(1497021319.404:264): proctitle="com.thaliproject.thalitest"
06-09 17:15:19.404  4962  4962 E audit   : type=1320 msg=audit(1497021319.404:264): 
06-09 17:15:19.404  4962  4962 E audit   : type=1400 msg=audit(1497021319.404:265): avc:  denied  { ioctl } for  pid=9433 comm="Thread-138" path="socket:[34604]" dev="sockfs" ino=34604 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-09 17:15:19.404  4962  4962 E audit   :  SEPF_SECMOBILE_6.0.1_0031
06-09 17:15:19.404  4962  4962 E audit   : type=1300 msg=audit(1497021319.404:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=1 a3=d53bf3c8 items=0 ppid=3179 pid=9433 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-09 17:15:19.404  4962  4962 E audit   : type=1327 msg=audit(1497021319.404:265): proctitle="com.thaliproject.thalitest"
06-09 17:15:19.404  4962  4962 E audit   : type=1320 msg=audit(1497021319.404:265): 
,06-09 17:15:19.404  9370  9433 W jxcore-log: Starting JXcore engine
,06-09 17:15:19.444  9370  9433 W jxcore-log: Platform android
06-09 17:15:19.444  9370  9433 W jxcore-log: 
06-09 17:15:19.444  9370  9433 W jxcore-log: Process ARCH arm
06-09 17:15:19.444  9370  9433 W jxcore-log: 
,06-09 17:15:19.574  9370  9433 I jxcore-log: JXcore Cordova bridge is ready!
06-09 17:15:19.574  9370  9433 I jxcore-log: 
06-09 17:15:19.574  9370  9433 W jxcore-log: JXcore engine is started
,06-09 17:15:19.584  9370  9432 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-09 17:15:19.584  9370  9370 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
06-09 17:15:19.584  9370  9370 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-09 17:15:21.034  3503  3903 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/5_task.xml.bak
,06-09 17:15:21.094  3503  6040 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,06-09 17:15:24.144  3503  6040 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-09 17:15:26.594  9370  9433 I jxcore-log: 2017-06-09 15:15:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
06-09 17:15:26.594  9370  9433 I jxcore-log: 
,06-09 17:15:26.594  9370  9433 I jxcore-log: 2017-06-09 15:15:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
06-09 17:15:26.594  9370  9433 I jxcore-log: 
06-09 17:15:26.594  9370  9433 I jxcore-log: 2017-06-09 15:15:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
06-09 17:15:26.594  9370  9433 I jxcore-log: 
,06-09 17:15:26.604  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:26.604  9370  9433 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-09 17:15:26.604  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:26.604  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:26.604  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-09 17:15:26.604  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-09 17:15:26.604  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-09 17:15:26.604  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-09 17:15:26.604  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-09 17:15:26.604  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-09 17:15:26.604  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:26.614  9370  9433 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
06-09 17:15:26.614  9370  9433 I jxcore-log: 2017-06-09 15:15:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
06-09 17:15:26.614  9370  9433 I jxcore-log: 
06-09 17:15:26.614  9370  9433 I jxcore-log: 2017-06-09 15:15:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
06-09 17:15:26.614  9370  9433 I jxcore-log: 
,06-09 17:15:26.614  9370  9433 I jxcore-log: 2017-06-09 15:15:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
06-09 17:15:26.614  9370  9433 I jxcore-log: 
,06-09 17:15:26.874  9370  9433 D ExecuteNativeTests: Running unit tests
,06-09 17:15:26.874  9370  9433 D BluetoothAdapter: enable()
,06-09 17:15:26.884  9370  9433 D BluetoothAdapter: enable(): BT is already enabled..!
,06-09 17:15:26.904  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{44221fb u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:26.904  9370  9433 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-09 17:15:26.904  3503  3525 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-09 17:15:26.904  3503  3525 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-09 17:15:26.914  3503  3525 D WifiService: setWifiEnabled: true pid=9370, uid=10074
,06-09 17:15:26.914  3503  3525 W ActivityManager: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,06-09 17:15:26.914  3503  3854 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,06-09 17:15:26.914  3503  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,06-09 17:15:26.924  3503  3525 W WifiService: Failed getting userId using ActivityManagerNative
06-09 17:15:26.924  3503  3525 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:26.924  3503  3525 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-09 17:15:26.924  3503  3525 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-09 17:15:26.924  3503  3525 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-09 17:15:26.924  3503  3525 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-09 17:15:26.924  3503  3525 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
06-09 17:15:26.924  3503  3525 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-09 17:15:26.924  3503  3854 D WifiBigDataLog: init : 
06-09 17:15:26.924  3503  3525 D SettingsProvider: isChangeAllowed() : name = wifi_on
06-09 17:15:26.924  3503  3857 D WifiStateMachine: setFccChannel: channel = -1
06-09 17:15:26.924  3503  3857 D WifiController: [FCC]setFccChannel() is called !!!
,06-09 17:15:26.924  3503  3857 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,06-09 17:15:26.934  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9a52218 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:26.934  3503  3854 D WifiStateMachine: setFccChannelNative: channel = -1
,06-09 17:15:26.934  3503  3854 D WifiNative-wlan0: callSECApiInt - ID [230]
,06-09 17:15:27.604  3503  4130 E Watchdog: !@Sync 9 [06-09 17:15:27.613]
,06-09 17:15:28.094  3503  3620 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-09 17:15:28.114  3503  3620 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,06-09 17:15:29.264  3503  6040 D SSRM:n  : SIOP:: AP = 370, PST = 311 (W:6), CP = 268, LCD = 40
,06-09 17:15:29.294  3503  6040 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-09 17:15:33.774  3503  6076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-09 17:15:36.924  9370  9433 I com.test.thalitest.ThaliTestRunner: Running UT
,06-09 17:15:36.994  9370  9433 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
06-09 17:15:36.994  9370  9433 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35f95ba added. We now have 2 listener(s)
06-09 17:15:36.994  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35f95ba added. We now have 3 listener(s)
06-09 17:15:36.994  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-09 17:15:36.994  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:2C:E6"Peer extra info: "256
06-09 17:15:36.994  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-09 17:15:36.994  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
06-09 17:15:36.994  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-09 17:15:36.994  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72d9c6b added. We now have 4 listener(s)
06-09 17:15:36.994  9370  9433 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-09 17:15:36.994  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-09 17:15:37.004  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.014  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,06-09 17:15:37.014  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
06-09 17:15:37.014  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
06-09 17:15:37.014  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
06-09 17:15:37.014  9370  9433 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
06-09 17:15:37.014  9370  9433 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
06-09 17:15:37.014  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
06-09 17:15:37.014  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
06-09 17:15:37.014  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,06-09 17:15:37.014  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,06-09 17:15:37.014  9370  9433 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,06-09 17:15:37.014  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,06-09 17:15:37.024  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
06-09 17:15:37.024  9370  9433 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,06-09 17:15:37.024  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-09 17:15:37.044  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.044  9370  9433 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-09 17:15:37.044  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:37.044  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:37.044  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-09 17:15:37.044  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-09 17:15:37.044  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-09 17:15:37.044  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-09 17:15:37.044  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-09 17:15:37.044  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-09 17:15:37.044  9370  9433 D io.jxcore.node.ConnectivityMonitor: start: OK
06-09 17:15:37.044  9370  9433 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
06-09 17:15:37.044  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
06-09 17:15:37.044  9370  9379 I art     : Background sticky concurrent mark sweep GC freed 39872(1801KB) AllocSpace objects, 8(208KB) LOS objects, 11% free, 13MB/15MB, paused 10.214ms total 60.405ms
06-09 17:15:37.044  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-09 17:15:37.054  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:37.054  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:37.054  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:37.054  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.054  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-09 17:15:37.054  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:37.054  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:37.054  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:37.054  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.054  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
06-09 17:15:37.054  9370  9433 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
06-09 17:15:37.054  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
06-09 17:15:37.054  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-09 17:15:37.064  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,06-09 17:15:37.064  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,06-09 17:15:37.064  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
06-09 17:15:37.064  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
06-09 17:15:37.064  9370  9436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
06-09 17:15:37.064  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
06-09 17:15:37.064  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
06-09 17:15:37.064  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-09 17:15:37.064  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,06-09 17:15:37.064  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:37.064  9370  9370 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,06-09 17:15:37.074  9370  9436 D BluetoothSocket: bindListen(): myUserId = 0
06-09 17:15:37.074  9370  9436 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-09 17:15:37.074  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
06-09 17:15:37.074  9370  9433 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
06-09 17:15:37.074  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,06-09 17:15:37.074  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.074  9370  9436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,06-09 17:15:37.074  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:37.074  9370  9436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@9615386, port: 6, type: 1, local socket address: null, socket type: 0
,06-09 17:15:37.084  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.084  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.084  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,06-09 17:15:37.094  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.094  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:37.094  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,06-09 17:15:37.094  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,06-09 17:15:37.094  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,06-09 17:15:37.094  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.094  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.094  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.094  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
06-09 17:15:37.094  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
06-09 17:15:37.094  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d35cbc72-f199-41c1-9eeb-d4ccb56ee509", Bluetooth MAC address: "44:78:3E:94:2C:E6"
06-09 17:15:37.094  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 2C E6
,06-09 17:15:37.104  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:15:37.104  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:15:37.104  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.104  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.104  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
06-09 17:15:37.104  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:15:37.104  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.104  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.104  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.104  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:37.104  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:37.104  9370  9433 D BluetoothLeAdvertiser: start advertising
06-09 17:15:37.104  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.114  4953  4969 D BtGatt.GattService: registerClient() - UUID=0a78ebf6-518e-4570-a809-75f2f4ace9eb
,06-09 17:15:37.164  4953  5083 D BtGatt.GattService: onClientRegistered() - UUID=0a78ebf6-518e-4570-a809-75f2f4ace9eb, clientIf=8
,06-09 17:15:37.174  9370  9381 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,06-09 17:15:37.174  4953  4967 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,06-09 17:15:37.184  4953  4967 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:15:37.184  4953  4967 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:15:37.184  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
06-09 17:15:37.184  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
06-09 17:15:37.184  4953  5144 D BtGatt.AdvertiseManager: message : 0
,06-09 17:15:37.184  4953  5144 D BtGatt.AdvertiseManager: number of adv instance running = 0
,06-09 17:15:37.184  4953  5144 D BtGatt.AdvertiseManager: size of list is =0
,06-09 17:15:37.194  4953  5144 D BtGatt.AdvertiseManager: starting advertising
,06-09 17:15:37.194  4953  5144 D BtGatt.AdvertiseManager: isStandardAdv = false
,06-09 17:15:37.204  4953  5171 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 29
,06-09 17:15:37.204  4953  5171 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24950355
06-09 17:15:37.204  4953  5171 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
06-09 17:15:37.204  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,06-09 17:15:37.204  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
,06-09 17:15:37.204  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{fecd573: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.204  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{ad21c30: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.204  4953  5083 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,06-09 17:15:37.214  4953  5144 D BtGatt.AdvertiseManager: starting multi advertising
,06-09 17:15:37.214  3503  3981 V AlarmManager:  remove PendingIntent] PendingIntent{d2cd0a9: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.214  4953  5083 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
06-09 17:15:37.214  4953  5144 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
06-09 17:15:37.214  4953  5144 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
06-09 17:15:37.214  4953  5144 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
06-09 17:15:37.214  4953  5144 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
,06-09 17:15:37.214  9370  9380 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,06-09 17:15:37.214  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,06-09 17:15:37.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.214  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
06-09 17:15:37.214  3503  4293 V AlarmManager:  remove PendingIntent] PendingIntent{f5e862e: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.224  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,06-09 17:15:37.224  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.224  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.224  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{db555cf: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:37.224  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.224  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.224  9370  9433 I io.jxcore.node.ConnectionHelper: start: OK
06-09 17:15:37.224  9370  9370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
06-09 17:15:37.224  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,06-09 17:15:37.224  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
06-09 17:15:37.224  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
06-09 17:15:37.224  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.224  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,06-09 17:15:37.224  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,06-09 17:15:37.224  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.224  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
06-09 17:15:37.224  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
06-09 17:15:37.224  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.224  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,06-09 17:15:37.224  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,06-09 17:15:37.224  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.224  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,06-09 17:15:37.234  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{374cb5c: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.234  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,06-09 17:15:37.234  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
06-09 17:15:37.234  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.234  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.234  9370  9370 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,06-09 17:15:37.234  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{3d8ce65: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.724  9370  9438 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,06-09 17:15:37.734  9370  9433 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
,06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
,06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
,06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
,06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
,06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
,06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
,06-09 17:15:37.734  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
06-09 17:15:37.734  9370  9433 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
06-09 17:15:37.734  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
06-09 17:15:37.734  9370  9433 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
06-09 17:15:37.734  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
06-09 17:15:37.734  9370  9370 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
06-09 17:15:37.734  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
06-09 17:15:37.734  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,06-09 17:15:37.734  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
06-09 17:15:37.734  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
06-09 17:15:37.734  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
06-09 17:15:37.734  9370  9436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
06-09 17:15:37.734  9370  9436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
06-09 17:15:37.734  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,06-09 17:15:37.734  9370  9436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
06-09 17:15:37.734  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
06-09 17:15:37.734  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.734  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
06-09 17:15:37.734  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
06-09 17:15:37.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.744  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.744  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,06-09 17:15:37.754  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.754  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.754  9370  9433 D BluetoothLeScanner: could not find callback wrapper
06-09 17:15:37.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
06-09 17:15:37.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.754  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
06-09 17:15:37.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.754  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.754  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.754  9370  9433 D BluetoothLeAdvertiser: stop advertising
,06-09 17:15:37.764  4953  5387 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-09 17:15:37.764  4953  5387 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-09 17:15:37.764  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
06-09 17:15:37.764  4953  5144 D BtGatt.AdvertiseManager: message : 1
06-09 17:15:37.764  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
06-09 17:15:37.764  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-09 17:15:37.764  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
,06-09 17:15:37.764  4953  5144 D BtGatt.AdvertiseManager: stop advertise for client =  8
06-09 17:15:37.764  4953  5144 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
06-09 17:15:37.764  4953  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,06-09 17:15:37.764  4953  5144 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,06-09 17:15:37.764  3503  3981 V AlarmManager:  remove PendingIntent] PendingIntent{950d73a: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.764  4953  5083 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
06-09 17:15:37.764  4953  5083 D BtGatt.GattService: Client app is not null!
,06-09 17:15:37.774  9370  9381 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,06-09 17:15:37.774  4953  5382 D BtGatt.GattService: unregisterClient() - clientIf=8
,06-09 17:15:37.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,06-09 17:15:37.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
06-09 17:15:37.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.774  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{9db7feb: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:37.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,06-09 17:15:37.774  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
06-09 17:15:37.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
06-09 17:15:37.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
06-09 17:15:37.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.784  9370  9370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
06-09 17:15:37.784  9370  9370 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
06-09 17:15:37.784  9370  9370 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,06-09 17:15:37.784  9370  9370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
06-09 17:15:37.784  9370  9370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-09 17:15:37.784  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-09 17:15:37.784  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-09 17:15:37.784  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
06-09 17:15:37.784  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{e314148: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.784  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,06-09 17:15:37.784  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
06-09 17:15:37.784  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
06-09 17:15:37.784  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.784  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.784  3503  3981 V AlarmManager:  remove PendingIntent] PendingIntent{28cebe1: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:37.784  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.784  9370  9370 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
06-09 17:15:37.784  9370  9439 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
06-09 17:15:37.784  9370  9433 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
06-09 17:15:37.784  9370  9433 V io.jxcore.node.ConnectivityMonitor: start: Already started
06-09 17:15:37.784  9370  9433 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,06-09 17:15:37.784  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
06-09 17:15:37.784  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-09 17:15:37.794  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:37.794  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:37.794  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.794  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-09 17:15:37.794  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{6e52d06: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.794  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:37.794  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:37.794  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.794  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
06-09 17:15:37.794  9370  9433 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,06-09 17:15:37.794  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
06-09 17:15:37.794  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-09 17:15:37.794  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,06-09 17:15:37.794  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
06-09 17:15:37.794  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,06-09 17:15:37.794  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,06-09 17:15:37.794  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,06-09 17:15:37.794  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{bf02fc7: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:37.794  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
06-09 17:15:37.794  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-09 17:15:37.794  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,06-09 17:15:37.794  9370  9440 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
06-09 17:15:37.794  9370  9370 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
06-09 17:15:37.804  9370  9440 D BluetoothSocket: bindListen(): myUserId = 0
06-09 17:15:37.804  9370  9440 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-09 17:15:37.804  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
06-09 17:15:37.804  9370  9433 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
06-09 17:15:37.804  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,06-09 17:15:37.804  9370  9440 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
06-09 17:15:37.804  9370  9440 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@e53e3e0, port: 6, type: 1, local socket address: null, socket type: 0
,06-09 17:15:37.804  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.804  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{9b60163: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:37.804  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.814  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.814  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{c7cf160: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.814  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.814  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,06-09 17:15:37.814  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.814  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.814  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
06-09 17:15:37.814  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
06-09 17:15:37.814  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
,06-09 17:15:37.814  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.824  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
06-09 17:15:37.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,06-09 17:15:37.824  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d35cbc72-f199-41c1-9eeb-d4ccb56ee509", Bluetooth MAC address: "44:78:3E:94:2C:E6"
06-09 17:15:37.824  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 2C E6
06-09 17:15:37.824  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,06-09 17:15:37.824  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:15:37.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
06-09 17:15:37.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:15:37.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:37.824  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.824  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.824  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.824  9370  9433 D BluetoothLeAdvertiser: start advertising
06-09 17:15:37.824  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:37.834  4953  4967 D BtGatt.GattService: registerClient() - UUID=a049f936-a830-4f02-a868-81f7948492b4
,06-09 17:15:37.874  4953  5083 D BtGatt.GattService: onClientRegistered() - UUID=a049f936-a830-4f02-a868-81f7948492b4, clientIf=8
,06-09 17:15:37.874  9370  9380 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,06-09 17:15:37.874  4953  5387 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,06-09 17:15:37.874  4953  5387 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-09 17:15:37.874  4953  5387 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:15:37.874  4953  5144 D BtGatt.AdvertiseManager: message : 0
06-09 17:15:37.874  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
06-09 17:15:37.874  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
06-09 17:15:37.874  4953  5144 D BtGatt.AdvertiseManager: number of adv instance running = 0
,06-09 17:15:37.874  4953  5144 D BtGatt.AdvertiseManager: size of list is =0
,06-09 17:15:37.884  4953  5144 D BtGatt.AdvertiseManager: starting advertising
,06-09 17:15:37.884  4953  5144 D BtGatt.AdvertiseManager: isStandardAdv = false
,06-09 17:15:37.884  4953  5171 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 30
,06-09 17:15:37.884  4953  5171 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24950355
06-09 17:15:37.884  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{2fe3619: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:37.884  4953  5171 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
06-09 17:15:37.884  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-09 17:15:37.884  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
,06-09 17:15:37.894  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{b0ed6de: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.924  3503  3981 V AlarmManager:  remove PendingIntent] PendingIntent{87d50bf: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.924  4953  5083 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,06-09 17:15:37.924  4953  5144 D BtGatt.AdvertiseManager: starting multi advertising
,06-09 17:15:37.924  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{eafc38c: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.924  4953  5083 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
06-09 17:15:37.924  4953  5144 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
06-09 17:15:37.924  4953  5144 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
06-09 17:15:37.924  4953  5144 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
06-09 17:15:37.924  4953  5144 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
,06-09 17:15:37.924  9370  9381 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
06-09 17:15:37.924  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.924  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.924  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
06-09 17:15:37.924  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.924  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.924  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.924  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.924  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.924  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,06-09 17:15:37.934  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
06-09 17:15:37.934  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.934  9370  9433 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,06-09 17:15:37.934  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.934  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.934  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{8b31ad5: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:37.934  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:37.934  9370  9433 I io.jxcore.node.ConnectionHelper: start: OK
06-09 17:15:37.934  9370  9370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.934  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.934  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.934  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
06-09 17:15:37.934  9370  9370 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,06-09 17:15:37.944  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{c2d82ea: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.944  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{84039db: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:37.944  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{f5b8c78: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.434  9370  9442 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,06-09 17:15:38.434  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,06-09 17:15:38.444  9370  9433 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
06-09 17:15:38.444  9370  9433 V io.jxcore.node.ConnectivityMonitor: start: Already started
06-09 17:15:38.444  9370  9433 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
06-09 17:15:38.444  9370  9370 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,06-09 17:15:38.444  9370  9433 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
06-09 17:15:38.444  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
06-09 17:15:38.444  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-09 17:15:38.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,06-09 17:15:38.454  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:38.454  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-09 17:15:38.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,06-09 17:15:38.454  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:38.454  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
06-09 17:15:38.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 38436
06-09 17:15:38.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
06-09 17:15:38.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
06-09 17:15:38.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
06-09 17:15:38.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
06-09 17:15:38.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
06-09 17:15:38.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
06-09 17:15:38.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
06-09 17:15:38.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:38.454  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
06-09 17:15:38.454  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.464  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.464  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:38.464  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:38.464  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:38.464  9370  9433 D BluetoothLeAdvertiser: stop advertising
,06-09 17:15:38.474  4953  5382 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-09 17:15:38.474  4953  5382 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:15:38.474  4953  5144 D BtGatt.AdvertiseManager: message : 1
,06-09 17:15:38.474  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
06-09 17:15:38.474  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
06-09 17:15:38.474  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,06-09 17:15:38.474  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
06-09 17:15:38.474  4953  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
06-09 17:15:38.474  4953  5144 D BtGatt.AdvertiseManager: stop advertise for client =  8
06-09 17:15:38.474  4953  5144 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,06-09 17:15:38.484  4953  5144 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,06-09 17:15:38.484  3503  4209 V AlarmManager:  remove PendingIntent] PendingIntent{b978f51: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.484  4953  5083 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
06-09 17:15:38.484  4953  5083 D BtGatt.GattService: Client app is not null!
06-09 17:15:38.484  9370  9380 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,06-09 17:15:38.494  4953  4969 D BtGatt.GattService: unregisterClient() - clientIf=8
,06-09 17:15:38.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,06-09 17:15:38.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,06-09 17:15:38.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:38.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.494  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{6d8e3b6: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.494  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
06-09 17:15:38.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:38.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:38.494  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,06-09 17:15:38.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
06-09 17:15:38.494  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d35cbc72-f199-41c1-9eeb-d4ccb56ee509", Bluetooth MAC address: "44:78:3E:94:2C:E6"
06-09 17:15:38.494  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 2C E6
06-09 17:15:38.494  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:15:38.504  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{47e98b7: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.494  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:15:38.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
06-09 17:15:38.504  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,06-09 17:15:38.504  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.504  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.504  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.504  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.504  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.504  9370  9433 D BluetoothLeAdvertiser: start advertising
,06-09 17:15:38.514  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:38.514  3503  4415 V AlarmManager:  remove PendingIntent] PendingIntent{f8f824: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.514  4953  4969 D BtGatt.GattService: registerClient() - UUID=cd75ee2e-9993-4ed8-b250-86d1d4ab821b
,06-09 17:15:38.514  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{574cf8d: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.524  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{e078542: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.524  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{6da0953: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.534  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{2df7290: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.564  4953  5083 D BtGatt.GattService: onClientRegistered() - UUID=cd75ee2e-9993-4ed8-b250-86d1d4ab821b, clientIf=8
,06-09 17:15:38.564  9370  9381 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,06-09 17:15:38.564  4953  5382 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,06-09 17:15:38.564  4953  5382 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:15:38.564  4953  5382 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-09 17:15:38.574  4953  5144 D BtGatt.AdvertiseManager: message : 0
06-09 17:15:38.574  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
06-09 17:15:38.574  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
,06-09 17:15:38.574  4953  5144 D BtGatt.AdvertiseManager: number of adv instance running = 0
06-09 17:15:38.574  4953  5144 D BtGatt.AdvertiseManager: size of list is =0
,06-09 17:15:38.574  4953  5144 D BtGatt.AdvertiseManager: starting advertising
,06-09 17:15:38.574  4953  5144 D BtGatt.AdvertiseManager: isStandardAdv = false
,06-09 17:15:38.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 31
,06-09 17:15:38.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24950355
06-09 17:15:38.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
06-09 17:15:38.584  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{96bd789: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-09 17:15:38.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
,06-09 17:15:38.584  4953  5083 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,06-09 17:15:38.584  4953  5144 D BtGatt.AdvertiseManager: starting multi advertising
,06-09 17:15:38.584  3503  4415 V AlarmManager:  remove PendingIntent] PendingIntent{b8cb38e: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.594  4953  5083 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,06-09 17:15:38.594  4953  5144 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
06-09 17:15:38.594  4953  5144 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
06-09 17:15:38.594  4953  5144 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
,06-09 17:15:38.594  4953  5144 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
06-09 17:15:38.594  9370  9380 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
06-09 17:15:38.594  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.594  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.594  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,06-09 17:15:38.594  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{771e7af: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.594  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
06-09 17:15:38.594  9370  9433 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
06-09 17:15:38.594  9370  9433 I io.jxcore.node.ConnectionHelper: start: OK
06-09 17:15:38.594  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,06-09 17:15:38.594  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
06-09 17:15:38.594  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
06-09 17:15:38.594  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.594  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,06-09 17:15:38.594  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,06-09 17:15:38.594  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.594  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,06-09 17:15:38.594  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
06-09 17:15:38.594  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.594  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,06-09 17:15:38.594  9370  9444 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
06-09 17:15:38.594  9370  9433 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
06-09 17:15:38.594  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,06-09 17:15:38.594  9370  9433 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
06-09 17:15:38.594  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
06-09 17:15:38.594  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
06-09 17:15:38.594  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
06-09 17:15:38.594  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
06-09 17:15:38.594  9370  9370 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
06-09 17:15:38.594  9370  9440 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
06-09 17:15:38.604  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{7127bc: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.594  9370  9440 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,06-09 17:15:38.594  9370  9440 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:38.604  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.604  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.604  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
06-09 17:15:38.604  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.604  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.604  9370  9433 D BluetoothLeScanner: could not find callback wrapper
06-09 17:15:38.604  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
06-09 17:15:38.604  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.604  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.604  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.604  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
06-09 17:15:38.604  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.604  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.614  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.614  9370  9433 D BluetoothLeAdvertiser: stop advertising
06-09 17:15:38.614  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{1b16345: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.614  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{1247a9a: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.614  4953  5387 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:15:38.614  4953  5387 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:15:38.614  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,06-09 17:15:38.614  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
06-09 17:15:38.614  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-09 17:15:38.614  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
06-09 17:15:38.614  4953  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
06-09 17:15:38.624  4953  5144 D BtGatt.AdvertiseManager: message : 1
06-09 17:15:38.624  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{6ff4fcb: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.624  4953  5144 D BtGatt.AdvertiseManager: stop advertise for client =  8
06-09 17:15:38.624  4953  5144 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
06-09 17:15:38.624  4953  5144 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
06-09 17:15:38.624  4953  5083 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
06-09 17:15:38.624  4953  5083 D BtGatt.GattService: Client app is not null!
06-09 17:15:38.624  9370  9381 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
06-09 17:15:38.624  4953  4967 D BtGatt.GattService: unregisterClient() - clientIf=8
06-09 17:15:38.624  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
06-09 17:15:38.624  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.624  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
06-09 17:15:38.624  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.624  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.624  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.624  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
06-09 17:15:38.624  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
06-09 17:15:38.634  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
06-09 17:15:38.634  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{70703a8: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.634  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.634  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.634  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
06-09 17:15:38.634  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.634  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.634  9370  9445 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
06-09 17:15:38.634  9370  9370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
06-09 17:15:38.634  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{d09eec1: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.634  9370  9370 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
06-09 17:15:38.634  9370  9370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
06-09 17:15:38.634  9370  9370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-09 17:15:38.634  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-09 17:15:38.634  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-09 17:15:38.634  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
06-09 17:15:38.634  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.634  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
06-09 17:15:38.634  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
06-09 17:15:38.634  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.634  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.634  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.634  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
06-09 17:15:38.634  9370  9370 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
06-09 17:15:38.634  9370  9433 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
06-09 17:15:38.634  9370  9433 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a8e16a added. We now have 3 listener(s)
06-09 17:15:38.634  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a8e16a added. We now have 5 listener(s)
06-09 17:15:38.634  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-09 17:15:38.644  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{e3fa666: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.644  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:38.644  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-09 17:15:38.644  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityS,tring: {"generation":2,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:38.644  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-09 17:15:38.644  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@692765b added. We now have 6 listener(s)
06-09 17:15:38.644  9370  9433 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-09 17:15:38.644  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-09 17:15:38.644  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{e9cb254: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.644  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-09 17:15:38.654  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{1c7ed43: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.654  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.654  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{13c9fc0: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.654  9370  9433 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-09 17:15:38.654  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:38.654  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:38.654  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-09 17:15:38.654  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-09 17:15:38.654  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-09 17:15:38.654  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-09 17:15:38.654  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-09 17:15:38.654  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-09 17:15:38.654  9370  9433 D io.jxcore.node.ConnectivityMonitor: start: OK
06-09 17:15:38.664  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{dfcb4f9: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.664  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-09 17:15:38.664  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{5531c3e: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.664  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-09 17:15:38.664  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{cf21a9f: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.674  9370  9433 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-09 17:15:38.674  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:38.684  9370  9433 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-09 17:15:38.684  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:38.684  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:38.684  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-09 17:15:38.684  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-09 17:15:38.684  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-09 17:15:38.684  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-09 17:15:38.684  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-09 17:15:38.684  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-09 17:15:38.684  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-09 17:15:38.684  9370  9433 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-09 17:15:38.684  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
06-09 17:15:38.684  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-09 17:15:38.684  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-09 17:15:38.684  9370  9433 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a8e16a removed from the list
06-09 17:15:38.684  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a8e16a removed from the list
,06-09 17:15:38.684  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-09 17:15:38.684  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@692765b removed from the list
,06-09 17:15:38.684  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:38.684  9370  9433 D io.jxcore.node.ConnectivityMonitor: stop
06-09 17:15:38.684  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,06-09 17:15:38.684  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,06-09 17:15:38.684  9370  9433 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,06-09 17:15:38.684  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,06-09 17:15:38.684  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,06-09 17:15:38.694  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,06-09 17:15:38.694  9370  9433 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,06-09 17:15:38.694  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
06-09 17:15:38.694  9370  9433 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,06-09 17:15:38.694  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
06-09 17:15:38.694  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,06-09 17:15:38.694  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,06-09 17:15:38.694  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
06-09 17:15:38.694  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
06-09 17:15:38.694  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,06-09 17:15:38.694  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
06-09 17:15:38.694  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
06-09 17:15:38.694  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
06-09 17:15:38.694  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
06-09 17:15:38.694  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
06-09 17:15:38.694  9370  9433 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
06-09 17:15:38.694  9370  9433 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
06-09 17:15:38.694  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
06-09 17:15:38.694  9370  9433 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
06-09 17:15:38.704  9370  9433 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
,06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
,06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
,06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
,06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
,06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
,06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
,06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
,06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
,06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
,06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
,06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
06-09 17:15:38.704  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
,06-09 17:15:38.704  9370  9433 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
06-09 17:15:38.704  9370  9433 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
06-09 17:15:38.704  9370  9433 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,06-09 17:15:38.704  9370  9433 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
06-09 17:15:38.704  9370  9433 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
06-09 17:15:38.704  9370  9433 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
06-09 17:15:38.704  9370  9433 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
06-09 17:15:38.704  9370  9433 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
06-09 17:15:38.704  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
,06-09 17:15:38.704  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
06-09 17:15:38.704  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
06-09 17:15:38.704  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,06-09 17:15:38.704  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
06-09 17:15:38.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,06-09 17:15:38.704  9370  9433 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
06-09 17:15:38.704  9370  9433 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,06-09 17:15:38.704  9370  9433 E io.jxcore.node.ConnectionHelper: connect: Callback is null
06-09 17:15:38.704  9370  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 210)
06-09 17:15:38.704  9370  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
06-09 17:15:38.704  9370  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
,06-09 17:15:38.704  9370  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
06-09 17:15:38.714  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
06-09 17:15:38.714  9370  9433 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,06-09 17:15:38.714  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
06-09 17:15:38.714  9370  9433 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
06-09 17:15:38.714  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,06-09 17:15:38.714  9370  9433 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
06-09 17:15:38.714  9370  9433 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
06-09 17:15:38.714  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
06-09 17:15:38.714  9370  9433 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
06-09 17:15:38.714  9370  9433 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,06-09 17:15:38.714  9370  9433 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,06-09 17:15:38.714  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
06-09 17:15:38.714  9370  9433 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
06-09 17:15:38.714  9370  9433 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
06-09 17:15:38.714  9370  9433 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
06-09 17:15:38.714  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
06-09 17:15:38.714  9370  9433 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
06-09 17:15:38.714  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
06-09 17:15:38.714  9370  9446 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
06-09 17:15:38.714  9370  9433 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
06-09 17:15:38.714  9370  9433 V io.jxcore.node.ConnectivityMonitor: start: Already started
06-09 17:15:38.714  9370  9446 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
06-09 17:15:38.714  9370  9433 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
06-09 17:15:38.714  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
06-09 17:15:38.714  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
06-09 17:15:38.724  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:38.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:38.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.724  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
06-09 17:15:38.724  9370  9446 D BluetoothSocket: connect(): myUserId = 0
06-09 17:15:38.724  9370  9446 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-09 17:15:38.724  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:38.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:38.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.724  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
06-09 17:15:38.724  9370  9433 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
06-09 17:15:38.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
06-09 17:15:38.724  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-09 17:15:38.724  9370  9433 I org,.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
06-09 17:15:38.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
06-09 17:15:38.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
06-09 17:15:38.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
06-09 17:15:38.724  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
06-09 17:15:38.724  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
06-09 17:15:38.724  9370  9370 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
06-09 17:15:38.724  9370  9447 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
06-09 17:15:38.724  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-09 17:15:38.734  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
06-09 17:15:38.734  9370  9447 D BluetoothSocket: bindListen(): myUserId = 0
06-09 17:15:38.734  9370  9447 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-09 17:15:38.734  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
06-09 17:15:38.734  9370  9433 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
06-09 17:15:38.734  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
06-09 17:15:38.734  9370  9447 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
06-09 17:15:38.734  9370  9447 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@5ebaa36, port: 6, type: 1, local socket address: null, socket type: 0
06-09 17:15:38.734  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.734  3503  4412 D SecContentProvider: insert(), uri = 2
06-09 17:15:38.734  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.744  4953  5314 W bt_btif : bta_dm_acl_change(), event : 2
06-09 17:15:38.744  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.744  3503  4293 V AlarmManager:  remove PendingIntent] PendingIntent{f67c1bb: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.744  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
06-09 17:15:38.744  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.744  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{dd6a6d8: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.744  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
06-09 17:15:38.744  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
06-09 17:15:38.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
06-09 17:15:38.744  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.744  3503  4415 V AlarmManager:  remove PendingIntent] PendingIntent{e4b0a31: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.754  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
06-09 17:15:38.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
06-09 17:15:38.754  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d35cbc72-f199-41c1-9eeb-d4ccb56ee509", Bluetooth MAC address: "44:78:3E:94:2C:E6"
06-09 17:15:38.754  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 2C E6
06-09 17:15:38.754  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:15:38.754  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:15:38.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
06-09 17:15:38.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:15:38.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.754  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.754  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.754  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.754  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.754  9370  9433 D BluetoothLeAdvertiser: start advertising
06-09 17:15:38.754  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:15:38.764  4953  4967 D BtGatt.GattService: registerClient() - UUID=da41545c-edc0-4699-a294-340e7e00125f
,06-09 17:15:38.804  4953  5083 D BtGatt.GattService: onClientRegistered() - UUID=da41545c-edc0-4699-a294-340e7e00125f, clientIf=8
06-09 17:15:38.804  9370  9380 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
06-09 17:15:38.804  4953  5382 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
06-09 17:15:38.804  4953  5382 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:15:38.804  4953  5382 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:15:38.804  4953  5144 D BtGatt.AdvertiseManager: message : 0
06-09 17:15:38.804  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
06-09 17:15:38.804  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
06-09 17:15:38.804  4953  5144 D BtGatt.AdvertiseManager: number of adv instance running = 0
,06-09 17:15:38.804  4953  5144 D BtGatt.AdvertiseManager: size of list is =0
,06-09 17:15:38.814  4953  5144 D BtGatt.AdvertiseManager: starting advertising
,06-09 17:15:38.814  4953  5144 D BtGatt.AdvertiseManager: isStandardAdv = false
,06-09 17:15:38.814  4953  5171 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 32
,06-09 17:15:38.814  4953  5171 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24950355
06-09 17:15:38.814  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{5f47516: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.814  4953  5171 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
06-09 17:15:38.814  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-09 17:15:38.814  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
,06-09 17:15:38.814  4953  5083 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,06-09 17:15:38.814  4953  5144 D BtGatt.AdvertiseManager: starting multi advertising
,06-09 17:15:38.814  4953  5083 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,06-09 17:15:38.814  4953  5144 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,06-09 17:15:38.814  4953  5144 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
06-09 17:15:38.814  4953  5144 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
06-09 17:15:38.824  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{9c6be97: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.814  4953  5144 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
06-09 17:15:38.824  9370  9381 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
06-09 17:15:38.824  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
06-09 17:15:38.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.824  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
06-09 17:15:38.824  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
06-09 17:15:38.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.824  9370  9433 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,06-09 17:15:38.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:38.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:38.824  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{77b5884: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.824  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:38.824  9370  9433 I io.jxcore.node.ConnectionHelper: start: OK
06-09 17:15:38.824  9370  9370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
06-09 17:15:38.824  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.824  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
06-09 17:15:38.824  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
06-09 17:15:38.824  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.824  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,06-09 17:15:38.824  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
06-09 17:15:38.824  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.824  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
06-09 17:15:38.824  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
06-09 17:15:38.824  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.824  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.824  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,06-09 17:15:38.824  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.824  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,06-09 17:15:38.824  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{e95186d: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:38.834  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.834  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
06-09 17:15:38.834  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.834  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
06-09 17:15:38.834  9370  9370 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,06-09 17:15:38.834  3503  4293 V AlarmManager:  remove PendingIntent] PendingIntent{43acca2: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.834  3503  4415 V AlarmManager:  remove PendingIntent] PendingIntent{eaead33: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.844  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{19778f0: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:38.844  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{df7ce69: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:39.324  3503  6040 D SSRM:n  : SIOP:: AP = 330, PST = 316 (W:14), CP = 269, LCD = 40
,06-09 17:15:39.324  9370  9438 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
06-09 17:15:39.324  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-09 17:15:39.324  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
06-09 17:15:39.324  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
06-09 17:15:39.324  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,06-09 17:15:39.324  9370  9447 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
06-09 17:15:39.324  9370  9447 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,06-09 17:15:39.324  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
06-09 17:15:39.324  9370  9447 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,06-09 17:15:39.324  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
06-09 17:15:39.324  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
06-09 17:15:39.324  9370  9370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
06-09 17:15:39.324  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,06-09 17:15:39.324  9370  9370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-09 17:15:39.324  9370  9370 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
06-09 17:15:39.324  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,06-09 17:15:39.334  9370  9370 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
06-09 17:15:39.334  9370  9433 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35f95ba removed from the list
06-09 17:15:39.334  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35f95ba removed from the list
06-09 17:15:39.334  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,06-09 17:15:39.334  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
06-09 17:15:39.334  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.334  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,06-09 17:15:39.334  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
06-09 17:15:39.334  9370  9449 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 210
06-09 17:15:39.334  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.334  9370  9449 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
06-09 17:15:39.334  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.334  9370  9449 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 210)
06-09 17:15:39.334  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.334  4953  5426 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
06-09 17:15:39.334  9370  9449 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 210)
,06-09 17:15:39.334  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.334  9370  9446 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
06-09 17:15:39.344  9370  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
06-09 17:15:39.344  9370  9446 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 210)
,06-09 17:15:39.344  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:39.344  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:39.344  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,06-09 17:15:39.344  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:39.344  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:39.344  9370  9433 D BluetoothLeScanner: could not find callback wrapper
06-09 17:15:39.344  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
06-09 17:15:39.344  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.344  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.344  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:39.344  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
06-09 17:15:39.344  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:39.354  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:39.354  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:39.354  9370  9433 D BluetoothLeAdvertiser: stop advertising
,06-09 17:15:39.354  4953  5387 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-09 17:15:39.354  4953  5387 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:15:39.354  4953  5144 D BtGatt.AdvertiseManager: message : 1
06-09 17:15:39.354  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
06-09 17:15:39.354  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
06-09 17:15:39.354  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,06-09 17:15:39.354  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
06-09 17:15:39.354  4953  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
06-09 17:15:39.364  4953  5144 D BtGatt.AdvertiseManager: stop advertise for client =  8
06-09 17:15:39.364  4953  5144 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,06-09 17:15:39.364  4953  5144 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,06-09 17:15:39.364  4953  5083 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
,06-09 17:15:39.364  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{19d10ee: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:39.364  4953  5083 D BtGatt.GattService: Client app is not null!
06-09 17:15:39.364  9370  9380 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
06-09 17:15:39.364  4953  4969 D BtGatt.GattService: unregisterClient() - clientIf=8
,06-09 17:15:39.364  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,06-09 17:15:39.374  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.374  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
06-09 17:15:39.374  3503  4414 V AlarmManager:  remove PendingIntent] PendingIntent{11ce98f: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:39.374  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.374  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.374  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.374  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,06-09 17:15:39.374  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
06-09 17:15:39.374  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
06-09 17:15:39.374  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:39.374  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.374  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,06-09 17:15:39.374  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.374  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:39.374  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72d9c6b removed from the list
,06-09 17:15:39.374  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-09 17:15:39.374  9370  9433 D io.jxcore.node.ConnectivityMonitor: stop
06-09 17:15:39.374  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,06-09 17:15:39.374  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-09 17:15:39.374  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
06-09 17:15:39.374  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{c13341c: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:39.374  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-09 17:15:39.374  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
06-09 17:15:39.374  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
06-09 17:15:39.374  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,06-09 17:15:39.374  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,06-09 17:15:39.374  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-09 17:15:39.374  9370  9370 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
06-09 17:15:39.384  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{7b5e825: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:39.384  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{6cd4dfa: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:39.394  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{c888fab: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:39.394  3503  4293 V AlarmManager:  remove PendingIntent] PendingIntent{b2d7608: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:39.404  3503  4209 V AlarmManager:  remove PendingIntent] PendingIntent{e81e1a1: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:39.874  9370  9370 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,06-09 17:15:44.374  9370  9439 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,06-09 17:15:44.384  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,06-09 17:15:44.384  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
06-09 17:15:44.384  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-09 17:15:44.384  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,06-09 17:15:44.384  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
06-09 17:15:44.384  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,06-09 17:15:44.384  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
06-09 17:15:44.384  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
06-09 17:15:44.384  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,06-09 17:15:44.384  9370  9370 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
06-09 17:15:44.394  9370  9450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
06-09 17:15:44.394  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,06-09 17:15:44.394  9370  9433 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
,06-09 17:15:44.394  9370  9433 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,06-09 17:15:44.394  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,06-09 17:15:44.394  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
06-09 17:15:44.394  9370  9450 D BluetoothSocket: bindListen(): myUserId = 0
06-09 17:15:44.394  9370  9450 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-09 17:15:44.394  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,06-09 17:15:44.404  9370  9450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,06-09 17:15:44.404  9370  9450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@401280d, port: 6, type: 1, local socket address: null, socket type: 0
,06-09 17:15:44.414  9370  9433 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
06-09 17:15:44.414  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,06-09 17:15:44.414  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
06-09 17:15:44.414  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,06-09 17:15:44.414  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
06-09 17:15:44.414  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-09 17:15:44.414  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,06-09 17:15:44.414  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
06-09 17:15:44.414  9370  9433 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35f95ba not in the list
,06-09 17:15:44.414  9370  9450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
06-09 17:15:44.414  9370  9450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
06-09 17:15:44.414  9370  9433 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35f95ba not in the list
,06-09 17:15:44.414  9370  9370 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,06-09 17:15:44.414  9370  9450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
06-09 17:15:44.414  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-09 17:15:44.414  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,06-09 17:15:44.414  9370  9370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
06-09 17:15:44.414  9370  9370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-09 17:15:44.414  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:44.414  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
06-09 17:15:44.414  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,06-09 17:15:44.414  9370  9433 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-09 17:15:44.414  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-09 17:15:44.414  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:44.424  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:15:44.424  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
06-09 17:15:44.424  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:44.424  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:15:44.424  9370  9433 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72d9c6b not in the list
,06-09 17:15:44.424  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-09 17:15:44.424  9370  9433 D io.jxcore.node.ConnectivityMonitor: stop
06-09 17:15:44.424  9370  9433 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-09 17:15:44.424  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,06-09 17:15:44.424  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-09 17:15:44.424  9370  9370 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
06-09 17:15:44.424  9370  9433 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,06-09 17:15:44.424  9370  9433 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,06-09 17:15:44.424  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
06-09 17:15:44.424  9370  9433 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
06-09 17:15:44.424  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
06-09 17:15:44.424  9370  9433 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
06-09 17:15:44.424  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,06-09 17:15:44.424  9370  9433 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
06-09 17:15:44.434  9370  9433 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
06-09 17:15:44.434  9370  9433 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,06-09 17:15:44.434  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
06-09 17:15:44.434  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
06-09 17:15:44.434  9370  9433 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,06-09 17:15:44.434  9370  9433 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
06-09 17:15:44.434  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,06-09 17:15:44.434  9370  9433 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
06-09 17:15:44.434  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
06-09 17:15:44.434  9370  9433 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,06-09 17:15:44.434  9370  9433 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
06-09 17:15:44.434  9370  9433 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,06-09 17:15:44.434  9370  9433 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,06-09 17:15:44.434  9370  9433 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
06-09 17:15:44.444  9370  9433 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
06-09 17:15:44.444  9370  9433 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,06-09 17:15:44.444  9370  9433 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
06-09 17:15:44.444  9370  9433 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
06-09 17:15:44.444  9370  9433 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,06-09 17:15:44.444  9370  9433 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
06-09 17:15:44.444  9370  9433 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
06-09 17:15:44.444  9370  9433 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c033c2 added. We now have 2 listener(s)
06-09 17:15:44.444  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c033c2 added. We now have 3 listener(s)
,06-09 17:15:44.444  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,06-09 17:15:44.444  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,06-09 17:15:44.444  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-09 17:15:44.444  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
06-09 17:15:44.444  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,06-09 17:15:44.444  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca755d3 added. We now have 4 listener(s)
06-09 17:15:44.444  9370  9433 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-09 17:15:44.444  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-09 17:15:44.454  9370  9433 D BluetoothAdapter: enable()
,06-09 17:15:44.454  9370  9433 D BluetoothAdapter: enable(): BT is already enabled..!
,06-09 17:15:44.464  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3924fc6 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:44.464  9370  9433 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-09 17:15:44.474  3503  4403 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-09 17:15:44.474  3503  4403 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-09 17:15:44.474  3503  4403 D WifiService: setWifiEnabled: true pid=9370, uid=10074
,06-09 17:15:44.474  3503  4403 W ActivityManager: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,06-09 17:15:44.474  3503  4403 W WifiService: Failed getting userId using ActivityManagerNative
06-09 17:15:44.474  3503  4403 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:44.474  3503  4403 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-09 17:15:44.474  3503  4403 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-09 17:15:44.474  3503  4403 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-09 17:15:44.474  3503  4403 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-09 17:15:44.474  3503  4403 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
06-09 17:15:44.484  3503  4403 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-09 17:15:44.484  3503  4403 D SettingsProvider: isChangeAllowed() : name = wifi_on
06-09 17:15:44.484  3503  3857 D WifiStateMachine: setFccChannel: channel = -1
06-09 17:15:44.484  3503  3857 D WifiController: [FCC]setFccChannel() is called !!!
06-09 17:15:44.484  3503  3854 D WifiBigDataLog: getJsonFormat() - feature : ONOF
06-09 17:15:44.484  3503  3857 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
06-09 17:15:44.484  9370  9433 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
06-09 17:15:44.484  3503  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,06-09 17:15:44.484  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:44.484  3503  3854 D WifiBigDataLog: init : 
,06-09 17:15:44.494  3503  3854 D WifiStateMachine: setFccChannelNative: channel = -1
,06-09 17:15:44.494  3503  3854 D WifiNative-wlan0: callSECApiInt - ID [230]
,06-09 17:15:44.494  9370  9433 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,06-09 17:15:44.494  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2be7b87 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:44.504  9370  9433 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,06-09 17:15:44.504  9370  9433 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,06-09 17:15:44.514  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:15:44.514  9370  9433 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-09 17:15:44.514  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:44.514  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:44.514  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-09 17:15:44.514  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-09 17:15:44.514  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-09 17:15:44.514  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-09 17:15:44.514  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-09 17:15:44.514  9370  9433 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-09 17:15:44.514  9370  9451 D BluetoothAdapter: disable()
,06-09 17:15:44.534  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{627eab4 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:44.534  3503  4209 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,06-09 17:15:44.544  3503  3601 D SecContentProvider: insert(), uri = 2
,06-09 17:15:44.544  4953  5076 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,06-09 17:15:44.544  4953  5076 D BluetoothAdapterProperties: Setting state to 13
06-09 17:15:44.544  4953  5076 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
06-09 17:15:44.544  4953  5076 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-09 17:15:44.544  4953  5076 D BluetoothAdapterService: updateAdapterState state is 13
,06-09 17:15:44.554  4953  4953 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
06-09 17:15:44.554  3503  3601 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 2, mBLE count: 2, s BLE count: 2
,06-09 17:15:44.554  4953  5076 D BluetoothAdapterService: Autoconnection is available 
06-09 17:15:44.554  3503  3503 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:44.554  4953  5076 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,06-09 17:15:44.554  3503  3503 I InputMethodManagerService: [BT Setting State] State =13
06-09 17:15:44.554  4953  5076 D BluetoothAdapterService: terminating service from this receiver
06-09 17:15:44.554  3933  3933 D BluetoothPbap: Proxy object disconnected
06-09 17:15:44.554  3933  3933 D PbapServerProfile: Bluetooth service disconnected
06-09 17:15:44.554  4953  5076 D BluetoothAdapterProperties: onBluetoothDisable()
06-09 17:15:44.554  3933  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,06-09 17:15:44.564  3933  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
06-09 17:15:44.564  4298  4298 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:44.564  4953  5076 W bt_btif : btif_dm_cancel_discovery
,06-09 17:15:44.564  3503  4415 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,06-09 17:15:44.564  4746  4746 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,06-09 17:15:44.574  3503  3525 D SecContentProvider: insert(), uri = 2
,06-09 17:15:44.574  4953  5076 I BluetoothAdapterState: Entering PendingCommandState
,06-09 17:15:44.574  3503  3503 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
06-09 17:15:44.574  3503  3503 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:44.574  3503  3503 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
06-09 17:15:44.574  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{b53a252: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:44.584  9370  9370 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,06-09 17:15:44.584  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b7d4923 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6c9d1a2 9069:com.android.settings/1000}
06-09 17:15:44.584  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-09 17:15:44.584  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:44.584  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:44.584  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-09 17:15:44.584  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-09 17:15:44.584  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-09 17:15:44.584  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-09 17:15:44.584  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-09 17:15:44.584  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-09 17:15:44.594  4953  5083 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,06-09 17:15:44.594  4953  5083 D BluetoothAdapterProperties: Scan Mode:20
06-09 17:15:44.594  4953  5076 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,06-09 17:15:44.594  9370  9370 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
06-09 17:15:44.594  9370  9370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,06-09 17:15:44.604  4953  5076 E BluetoothServiceJni: disableBrEdrNative:
,06-09 17:15:44.604  4953  5076 E bt_bluedroid: disable_bredr
,06-09 17:15:44.604  4953  5445 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,06-09 17:15:44.604  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{4b2fe20: PendingIntentRecord{66423d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:44.604  4953  5077 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
06-09 17:15:44.604  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{e65919e: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:44.604  4953  5077 E bt_btif : BTA got event 0xe0b
06-09 17:15:44.604  9069  9069 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
06-09 17:15:44.604  4953  5464 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
06-09 17:15:44.604  4953  5314 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
06-09 17:15:44.604  4953  5464 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
06-09 17:15:44.604  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-09 17:15:44.614  4953  5463 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
06-09 17:15:44.614  4953  5463 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,06-09 17:15:44.614  4953  5077 D IOP_DB_BT: db_close: nbr users 0
,06-09 17:15:44.614  4953  5077 D IOP_DB_BT: db_close: free database
06-09 17:15:44.614  4953  5314 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,06-09 17:15:44.614  4953  5314 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
06-09 17:15:44.614  4953  5314 W bt_btif : bta_dm_acl_change(), event : 2
06-09 17:15:44.614  4953  5314 W bt_btif : bta_dm_acl_change(), event : 5
06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
06-09 17:15:44.614  4953  5314 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,06-09 17:15:44.634  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{719dc4c: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:44.634  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:44.634  9069  9069 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,06-09 17:15:44.634  4953  5076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@de8cfc3
,06-09 17:15:44.634  4953  5083 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,06-09 17:15:44.644  3503  3524 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b7d4923 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
06-09 17:15:44.644  3933  4163 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
06-09 17:15:44.644  3503  4208 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
06-09 17:15:44.644  3933  3933 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,06-09 17:15:44.644  3933  4129 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,06-09 17:15:44.654  4953  5083 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
06-09 17:15:44.654  4953  5083 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,06-09 17:15:44.654  9069  9069 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,06-09 17:15:44.654  9069  9069 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,06-09 17:15:44.654  3503  3524 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b7d4923 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{270f4ef 4226:com.google.android.gms.persistent/u0a19}
,06-09 17:15:44.654  4226  4226 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,06-09 17:15:44.664  3503  3524 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b7d4923 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff468ad 8694:com.sec.android.app.shealth:remote/u0a36}
,06-09 17:15:44.674  4953  4953 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:44.674  4953  4953 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
06-09 17:15:44.674  4953  4953 D ObexServerSockets: shutdown(block = true)
06-09 17:15:44.674  4953  4953 D ObexServerSockets: shutdown called from another thread - interrupt().
06-09 17:15:44.674  4953  4953 D ObexServerSockets: shutdown called from another thread - interrupt().
06-09 17:15:44.674  4953  4953 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
06-09 17:15:44.674  4953  4953 D BluetoothSdpJni: SDP Remove record success - handle: 1
,06-09 17:15:44.684  4953  4953 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
06-09 17:15:44.684  4953  4953 D BluetoothSdpJni: SDP Remove record success - handle: 0
06-09 17:15:44.684  4953  4953 I BtOppRfcommListener: stopping Accept Thread
06-09 17:15:44.684  4953  5445 I BtOppRfcommListener: BluetoothSocket listen thread finished
,06-09 17:15:44.684  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{4575477: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:44.684  9069  9069 D LocalBluetoothProfileManager: PANU : true
,06-09 17:15:44.694  3503  3524 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b7d4923 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6c9d1a2 9069:com.android.settings/1000}
,06-09 17:15:44.704  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{fe2c113: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:44.704  4953  4953 V BluetoothOppManager: cleanUp...
,06-09 17:15:44.714  9069  9069 D BluetoothSap: Create BluetoothSap proxy object
,06-09 17:15:44.714  9069  9069 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
06-09 17:15:44.714  9069  9069 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,06-09 17:15:44.724  9069  9069 D DockEventReceiver: finishStartingService: stopping service
,06-09 17:15:44.724  9069  9069 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
,06-09 17:15:44.724  9069  9069 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
06-09 17:15:44.724  9069  9069 D BluetoothPan: BluetoothPAN Proxy object connected
,06-09 17:15:44.724  9069  9069 D PanProfile: Bluetooth service connected
,06-09 17:15:44.734  9069  9069 D BluetoothSap: Proxy object connected
,06-09 17:15:44.734  9069  9069 D SapProfile: Bluetooth service connected
,06-09 17:15:44.734  3503  4208 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b7d4923 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12753ec 4953:com.android.bluetooth/1002}
,06-09 17:15:44.764  3503  4208 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b7d4923 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3a11a8 7033:com.google.android.apps.maps/u0a119}
,06-09 17:15:44.804  4953  5083 E BluetoothAdapterState: stateChangeCallback : 16
,06-09 17:15:44.804  4953  5076 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
06-09 17:15:44.804  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{ca3515a: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:44.814  4953  5076 D BtConfig.SecureMode: isSecureModeOn:false
,06-09 17:15:44.814  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,06-09 17:15:44.814  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,06-09 17:15:44.814  4953  4953 D HeadsetService: Received stop request...Stopping profile...
,06-09 17:15:44.814  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-09 17:15:44.814  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
06-09 17:15:44.814  4953  4953 E HeadsetService: notifyProfileServiceStateChanged
,06-09 17:15:44.814  3933  3933 D HeadsetProfile: Bluetooth service disconnected
,06-09 17:15:44.824  3503  3503 D BluetoothHeadset: unRegisterMessageListener : 11
06-09 17:15:44.824  3503  3503 W BluetoothHeadset: Proxy not attached to service
06-09 17:15:44.824  3503  3503 I Telecom : BluetoothManager : unregister MessageListener
06-09 17:15:44.824  3503  3503 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,06-09 17:15:44.824  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,06-09 17:15:44.824  4953  4953 D A2dpService: Received stop request...Stopping profile...
,06-09 17:15:44.824  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,06-09 17:15:44.824  4953  5410 D A2dpStateMachine: Exit Disconnected: -1
06-09 17:15:44.824  4953  4953 D Avrcp   : unregisterContentObserver
,06-09 17:15:44.824  4953  4953 D Avrcp   : removeOnActiveSessionsChangedListener
,06-09 17:15:44.824  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
06-09 17:15:44.824  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-09 17:15:44.824  4953  4953 E A2dpService: notifyProfileServiceStateChanged
,06-09 17:15:44.824  3933  3933 D BluetoothA2dp: Proxy object disconnected
06-09 17:15:44.824  3933  3933 D A2dpProfile: Bluetooth service disconnected
,06-09 17:15:44.824  3503  3503 D BluetoothA2dp: Proxy object disconnected
06-09 17:15:44.834  4990  4990 D BluetoothA2dp: Proxy object disconnected
,06-09 17:15:44.834  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
,06-09 17:15:44.834  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
06-09 17:15:44.834  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
06-09 17:15:44.834  4953  4953 V BluetoothAdapterState: isTurningOff()=true
06-09 17:15:44.834  4953  4953 V BluetoothAdapterState: isTurningOn()=false
,06-09 17:15:44.834  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:44.834  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
,06-09 17:15:44.834  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
06-09 17:15:44.834  4953  5076 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,06-09 17:15:44.834  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
06-09 17:15:44.834  4953  5076 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
06-09 17:15:44.834  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,06-09 17:15:44.844  4953  4953 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,06-09 17:15:44.844  4953  4953 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
06-09 17:15:44.844  4953  4953 D HeadsetProvider: cleanup
06-09 17:15:44.844  4953  4953 I HeadsetProvider: clearAllHeadsetSettings(0)
,06-09 17:15:44.864  4953  4953 D HidService: Received stop request...Stopping profile...
,06-09 17:15:44.864  4953  4953 D HidService: Stopping Bluetooth HidService
06-09 17:15:44.864  4953  4953 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
06-09 17:15:44.864  4953  4953 W bt_btif : cleanup: HH disabling or disabled already, status = 0
06-09 17:15:44.864  4953  4953 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
06-09 17:15:44.864  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
06-09 17:15:44.864  4953  4953 E HidService: notifyProfileServiceStateChanged
,06-09 17:15:44.864  3933  3933 D BluetoothInputDevice: Proxy object disconnected
06-09 17:15:44.864  3933  3933 D HidProfile: Bluetooth service disconnected
,06-09 17:15:44.864  4953  4953 D HealthService: Received stop request...Stopping profile...
,06-09 17:15:44.864  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
06-09 17:15:44.864  4953  4953 E HealthService: notifyProfileServiceStateChanged
,06-09 17:15:44.864  4953  4953 D PanService: Received stop request...Stopping profile...
,06-09 17:15:44.864  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
06-09 17:15:44.864  4953  4953 E PanService: notifyProfileServiceStateChanged
,06-09 17:15:44.874  3503  3503 D BluetoothPan: BluetoothPAN Proxy object disconnected
06-09 17:15:44.874  3933  3933 D BluetoothPan: BluetoothPAN Proxy object disconnected
06-09 17:15:44.874  3933  3933 D PanProfile: Bluetooth service disconnected
,06-09 17:15:44.874  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
,06-09 17:15:44.874  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
,06-09 17:15:44.874  9069  9069 D BluetoothPan: BluetoothPAN Proxy object disconnected
06-09 17:15:44.874  4953  4953 V BluetoothAdapterState: isTurningOff()=true
06-09 17:15:44.874  4953  4953 V BluetoothAdapterState: isTurningOn()=false
,06-09 17:15:44.874  9069  9069 D PanProfile: Bluetooth service disconnected
06-09 17:15:44.874  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:44.874  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
,06-09 17:15:44.874  4953  4953 D BluetoothMapService: Received stop request...Stopping profile...
,06-09 17:15:44.874  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
,06-09 17:15:44.874  4953  4953 E BluetoothMapService: notifyProfileServiceStateChanged
,06-09 17:15:44.884  3933  3933 D BluetoothMap: Proxy object disconnected
06-09 17:15:44.884  3933  3933 D MapProfile: Bluetooth service disconnected
,06-09 17:15:44.884  4953  4953 D SapService: Received stop request...Stopping profile...
,06-09 17:15:44.884  4953  4953 V SapService: stop()
,06-09 17:15:44.884  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
06-09 17:15:44.884  4953  4953 E SapService: notifyProfileServiceStateChanged
,06-09 17:15:44.884  3933  3933 D BluetoothSap: Proxy object disconnected
,06-09 17:15:44.884  3933  3933 D SapProfile: Bluetooth service disconnected
06-09 17:15:44.884  9069  9069 D BluetoothSap: Proxy object disconnected
06-09 17:15:44.884  9069  9069 D SapProfile: Bluetooth service disconnected
06-09 17:15:44.884  4953  4953 D BleAudioService: Received stop request...Stopping profile...
06-09 17:15:44.884  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
,06-09 17:15:44.884  4953  5420 E BleAudioStateMachine_R: Exit Disconnected: -1
06-09 17:15:44.884  4953  5419 E BleAudioStateMachine_L: Exit Disconnected: -1
06-09 17:15:44.884  4953  4953 E BleAudioService: notifyProfileServiceStateChanged
06-09 17:15:44.884  3933  3933 D BluetoothLeAudio: Proxy object disconnected
06-09 17:15:44.884  3933  3933 D BleAudioProfile: Bluetooth service disconnected
,06-09 17:15:44.894  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
,06-09 17:15:44.894  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
06-09 17:15:44.894  4953  4953 V BluetoothAdapterState: isTurningOff()=true
06-09 17:15:44.894  4953  4953 V BluetoothAdapterState: isTurningOn()=false
06-09 17:15:44.894  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
,06-09 17:15:44.894  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
06-09 17:15:44.894  4953  4953 D BluetoothAdapterService: HID Host service will be diabled
,06-09 17:15:44.894  4953  4953 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,06-09 17:15:44.894  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
06-09 17:15:44.894  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
,06-09 17:15:44.894  4953  4953 V BluetoothAdapterState: isTurningOff()=true
06-09 17:15:44.894  4953  4953 V BluetoothAdapterState: isTurningOn()=false
06-09 17:15:44.894  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:44.894  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
06-09 17:15:44.894  4953  4953 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,06-09 17:15:44.894  4953  4953 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,06-09 17:15:44.894  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
06-09 17:15:44.894  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
,06-09 17:15:44.894  4953  4953 V BluetoothAdapterState: isTurningOff()=true
06-09 17:15:44.894  4953  4953 V BluetoothAdapterState: isTurningOn()=false
06-09 17:15:44.894  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:44.894  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
,06-09 17:15:44.894  4953  4953 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
06-09 17:15:44.904  4953  4953 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,06-09 17:15:44.904  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
,06-09 17:15:44.904  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
06-09 17:15:44.904  4953  4953 V BluetoothAdapterState: isTurningOff()=true
06-09 17:15:44.904  4953  4953 V BluetoothAdapterState: isTurningOn()=false
,06-09 17:15:44.904  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:44.904  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
06-09 17:15:44.904  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
06-09 17:15:44.904  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
06-09 17:15:44.904  4953  4953 V BluetoothAdapterState: isTurningOff()=true
06-09 17:15:44.904  4953  4953 V BluetoothAdapterState: isTurningOn()=false
,06-09 17:15:44.904  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:44.904  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
06-09 17:15:44.904  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
,06-09 17:15:44.904  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
06-09 17:15:44.904  4953  4953 V BluetoothAdapterState: isTurningOff()=true
,06-09 17:15:44.904  4953  4953 V BluetoothAdapterState: isTurningOn()=false
06-09 17:15:44.904  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:44.904  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
06-09 17:15:44.904  4953  5076 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
06-09 17:15:44.904  4953  4953 V BleAudioService: [unregisterCallStateListener]
,06-09 17:15:44.904  4953  4953 W BtBleAudio.JNI: WARNING: cleanupNative(L385): Cleaning up  Ble audio left callback object##
,06-09 17:15:44.904  4953  5076 D BluetoothAdapterProperties: Setting state to 15
06-09 17:15:44.904  4953  4953 W BtBleAudio.JNI: WARNING: cleanupNative(L403): Cleaning up Ble audio Interface...##
06-09 17:15:44.904  4953  5076 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
06-09 17:15:44.904  4953  4953 W BtBleAudio.JNI: WARNING: cleanupNative(L391): Cleaning up  Ble audio right callback object##
06-09 17:15:44.904  4953  4953 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
,06-09 17:15:44.914  4953  5076 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,06-09 17:15:44.914  4953  5076 D BluetoothAdapterService: updateAdapterState state is 15
,06-09 17:15:44.914  4953  5076 D BluetoothAdapterService: Autoconnection is available 
06-09 17:15:44.914  4953  5076 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
06-09 17:15:44.914  4953  5076 I BluetoothAdapterState: Entering BleOnState
06-09 17:15:44.914  4226  4237 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-09 17:15:44.914  4226  4237 D BluetoothAdapter: Bluetooth is turned off, stop adv
06-09 17:15:44.914  4226  4237 D BluetoothAdapter: There are no active google scan apps, stop scan
,06-09 17:15:44.914  4226  4237 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
06-09 17:15:44.914  4226  4237 D BluetoothLeScanner: Exiting stopAllScan
06-09 17:15:44.914  3503  3601 D BluetoothAdapter: onBluetoothStateChange: up=false
06-09 17:15:44.914  3503  3601 D BluetoothAdapter: Bluetooth is turned off, stop adv
06-09 17:15:44.914  3503  3601 D BluetoothAdapter: There are no active google scan apps, stop scan
,06-09 17:15:44.914  9069  9080 D BluetoothSap: onBluetoothStateChange: up=false
,06-09 17:15:44.914  3933  4602 D BluetoothA2dp: onBluetoothStateChange: up=false
,06-09 17:15:44.914  3933  3952 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-09 17:15:44.914  3933  3952 D BluetoothAdapter: Bluetooth is turned off, stop adv
06-09 17:15:44.914  3933  3952 D BluetoothAdapter: There are no active google scan apps, stop scan
,06-09 17:15:44.914  3933  3944 D BluetoothSap: onBluetoothStateChange: up=false
,06-09 17:15:44.924  3933  5501 D BluetoothPan: onBluetoothStateChange on: false
,06-09 17:15:44.924  4953  4967 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-09 17:15:44.924  3933  4324 D BluetoothInputDevice: onBluetoothStateChange: up=false
,06-09 17:15:44.924  7439  7450 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-09 17:15:44.924  3933  4602 D BluetoothPbap: onBluetoothStateChange: up=false
,06-09 17:15:44.924  4990  5007 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-09 17:15:44.924  4990  5007 D BluetoothAdapter: Bluetooth is turned off, stop adv
06-09 17:15:44.924  4990  5007 D BluetoothAdapter: There are no active google scan apps, stop scan
,06-09 17:15:44.924  9370  9370 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
06-09 17:15:44.924  8694  8704 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-09 17:15:44.924  8694  8704 D BluetoothAdapter: Bluetooth is turned off, stop adv
06-09 17:15:44.924  8694  8704 D BluetoothAdapter: There are no active google scan apps, stop scan
06-09 17:15:44.934  3933  3952 D BluetoothMap: onBluetoothStateChange: up=false
,06-09 17:15:44.934  3503  3601 D BluetoothPan: onBluetoothStateChange on: false
,06-09 17:15:44.934  7033  7044 D BluetoothAdapter: onBluetoothStateChange: up=false
06-09 17:15:44.934  7033  7044 D BluetoothAdapter: Bluetooth is turned off, stop adv
,06-09 17:15:44.934  7033  7044 D BluetoothAdapter: There are no active google scan apps, stop scan
,06-09 17:15:44.934  9069  9081 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-09 17:15:44.934  9069  9081 D BluetoothAdapter: Bluetooth is turned off, stop adv
06-09 17:15:44.934  9069  9081 D BluetoothAdapter: There are no active google scan apps, stop scan
,06-09 17:15:44.934  4241  4257 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-09 17:15:44.934  4241  4257 D BluetoothAdapter: Bluetooth is turned off, stop adv
06-09 17:15:44.934  4241  4257 D BluetoothAdapter: There are no active google scan apps, stop scan
06-09 17:15:44.934  3933  5501 D BluetoothLeAudio: onBluetoothStateChange: up=false
,06-09 17:15:44.934  3933  5501 D BluetoothLeAudio: Unbinding service...
06-09 17:15:44.934  4254  4616 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-09 17:15:44.934  4254  4616 D BluetoothAdapter: Bluetooth is turned off, stop adv
,06-09 17:15:44.944  4254  4616 D BluetoothAdapter: There are no active google scan apps, stop scan
06-09 17:15:44.944  4990  5006 D BluetoothA2dp: onBluetoothStateChange: up=false
,06-09 17:15:44.944  3503  3601 D BluetoothA2dp: onBluetoothStateChange: up=false
,06-09 17:15:44.944  9370  9381 D BluetoothAdapter: onBluetoothStateChange: up=false
,06-09 17:15:44.944  9370  9381 D BluetoothAdapter: Bluetooth is turned off, stop adv
06-09 17:15:44.944  9370  9381 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
06-09 17:15:44.944  9370  9381 D BluetoothLeAdvertiser: Exit stop advertising
,06-09 17:15:44.944  9370  9381 D BluetoothAdapter: There are no active google scan apps, stop scan
06-09 17:15:44.944  9370  9381 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
06-09 17:15:44.944  9370  9381 D BluetoothLeScanner: Exiting stopAllScan
06-09 17:15:44.944  9069  9080 D BluetoothPan: onBluetoothStateChange on: false
,06-09 17:15:44.944  3503  3503 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,06-09 17:15:44.944  3503  3503 I InputMethodManagerService: [BT Setting State] State =10
06-09 17:15:44.944  3503  3503 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,06-09 17:15:44.944  3933  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:44.944  3933  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,06-09 17:15:44.954  4298  4298 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,06-09 17:15:44.954  4746  4746 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,06-09 17:15:44.954  3503  3503 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,06-09 17:15:44.954  3503  3503 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
,06-09 17:15:44.954  3503  3503 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,06-09 17:15:44.954  9069  9069 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,06-09 17:15:44.964  9069  9069 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,06-09 17:15:44.964  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:44.964  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9ef3f8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6c9d1a2 9069:com.android.settings/1000}
,06-09 17:15:44.974  3933  4163 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,06-09 17:15:44.974  3503  4293 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,06-09 17:15:44.974  9069  9069 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,06-09 17:15:44.994  3503  4845 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9ef3f8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:45.004  9069  9069 D DockEventReceiver: finishStartingService: stopping service
,06-09 17:15:45.014  3503  4845 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9ef3f8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{270f4ef 4226:com.google.android.gms.persistent/u0a19}
,06-09 17:15:45.014  4226  4226 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,06-09 17:15:45.034  3503  4845 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9ef3f8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff468ad 8694:com.sec.android.app.shealth:remote/u0a36}
,06-09 17:15:45.044  3503  4209 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9ef3f8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6c9d1a2 9069:com.android.settings/1000}
,06-09 17:15:45.054  9370  9451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
06-09 17:15:45.054  9069  9069 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:45.054  9370  9451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-09 17:15:45.054  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:45.054  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:45.054  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-09 17:15:45.054  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-09 17:15:45.054  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-09 17:15:45.054  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-09 17:15:45.054  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-09 17:15:45.054  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-09 17:15:45.054  9069  9069 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,06-09 17:15:45.054  9370  9451 D BluetoothAdapter: enable()
,06-09 17:15:45.054  9370  9433 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:45.064  3503  4414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9ef3f8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12753ec 4953:com.android.bluetooth/1002}
,06-09 17:15:45.074  4953  9459 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,06-09 17:15:45.074  4953  9459 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,06-09 17:15:45.074  3503  4412 W ActivityManager: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,06-09 17:15:45.074  3503  4412 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
06-09 17:15:45.074  3503  4412 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:45.074  3503  4412 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-09 17:15:45.074  3503  4412 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
06-09 17:15:45.074  3503  4412 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
06-09 17:15:45.074  3503  4412 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
06-09 17:15:45.074  3503  4412 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
06-09 17:15:45.074  3503  4412 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
06-09 17:15:45.074  3503  4412 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,06-09 17:15:45.074  3503  4412 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
06-09 17:15:45.074  3503  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9ef3f8b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3a11a8 7033:com.google.android.apps.maps/u0a119}
06-09 17:15:45.084  3503  4412 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,06-09 17:15:45.084  9370  9451 D BluetoothAdapter: BT is in BLE_ON State or TURNING_OFF state
,06-09 17:15:45.094  4953  5076 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,06-09 17:15:45.104  3503  3524 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f2cc481 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:45.104  4953  5076 D BluetoothAdapterProperties: Setting state to 11
06-09 17:15:45.104  4953  5076 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
06-09 17:15:45.104  4953  5076 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-09 17:15:45.104  4953  5076 D BluetoothAdapterService: updateAdapterState state is 11
,06-09 17:15:45.104  3503  3601 D BluetoothManagerService: Turning On/Off, G state: 1, S state: 2, mBLE count: 2, s BLE count: 2
,06-09 17:15:45.104  4953  5076 D BluetoothAdapterService: Autoconnection is available 
06-09 17:15:45.104  4953  5076 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
06-09 17:15:45.104  4953  5076 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
06-09 17:15:45.104  4953  5076 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
06-09 17:15:45.104  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,06-09 17:15:45.124  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,06-09 17:15:45.124  4953  4953 D HeadsetService: Received start request. Starting profile...
06-09 17:15:45.124  4953  4953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@de8cfc3
06-09 17:15:45.124  4953  4953 D HeadsetProvider: make
06-09 17:15:45.124  4953  4953 D HeadsetProvider: HeadsetProvider
06-09 17:15:45.124  4953  4953 I HeadsetProvider: clearAllHeadsetSettings(0)
,06-09 17:15:45.134  4953  4953 D HeadsetStateMachine: make
,06-09 17:15:45.134  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,06-09 17:15:45.134  3503  3503 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:45.134  3503  3503 I InputMethodManagerService: [BT Setting State] State =11
,06-09 17:15:45.134  4953  4953 E HeadsetStateMachine: # of Max HF connection is 3
,06-09 17:15:45.134  3933  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:45.134  3933  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,06-09 17:15:45.144  4298  4298 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,06-09 17:15:45.144  4746  4746 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,06-09 17:15:45.144  3503  3503 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,06-09 17:15:45.144  3503  3503 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:45.144  3503  3503 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,06-09 17:15:45.144  9069  9069 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:45.144  9069  9069 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,06-09 17:15:45.154  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:45.154  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4f6d314 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6c9d1a2 9069:com.android.settings/1000}
,06-09 17:15:45.164  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,06-09 17:15:45.174  3933  4163 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
,06-09 17:15:45.174  3503  4209 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,06-09 17:15:45.174  3933  3933 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
06-09 17:15:45.174  3503  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4f6d314 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:45.174  4953  4953 I bt_bluedroid: get_profile_interface handsfree
,06-09 17:15:45.184  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,06-09 17:15:45.194  3503  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4f6d314 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{270f4ef 4226:com.google.android.gms.persistent/u0a19}
,06-09 17:15:45.194  4226  4226 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,06-09 17:15:45.204  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,06-09 17:15:45.214  3503  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4f6d314 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff468ad 8694:com.sec.android.app.shealth:remote/u0a36}
,06-09 17:15:45.234  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
06-09 17:15:45.234  4953  4953 E DualScoManager: Dual Sco Manager already instantiated
06-09 17:15:45.234  4953  4953 I DualScoManager: Set HeadsetServiceHelper
06-09 17:15:45.234  4953  4953 D BluetoothAtMessage: createCMTIContentObservers
,06-09 17:15:45.244  3503  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4f6d314 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6c9d1a2 9069:com.android.settings/1000}
,06-09 17:15:45.244  9069  9069 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:45.244  9069  9069 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,06-09 17:15:45.254  3503  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4f6d314 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12753ec 4953:com.android.bluetooth/1002}
,06-09 17:15:45.264  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
06-09 17:15:45.274  4953  5076 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
06-09 17:15:45.274  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
06-09 17:15:45.274  4953  5076 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,06-09 17:15:45.274  4953  5076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,06-09 17:15:45.274  4953  4953 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@17e79af
,06-09 17:15:45.274  4953  4953 D HeadsetProvider: setHeadsetDB - Can't find 300 for 44:78:3E:94:2C:XX
,06-09 17:15:45.274  4953  5076 I BluetoothAdapterState: Entering PendingCommandState
,06-09 17:15:45.284  4953  5076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@de8cfc3
,06-09 17:15:45.284  4953  4953 I HeadsetProvider: setHeadsetDB - 44:78:3E:94:2C:XX, 300, 1, true
,06-09 17:15:45.294  4953  4953 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@13fb49a
,06-09 17:15:45.294  4953  4953 D HeadsetProvider: setHeadsetDB - Can't find 400 for 44:78:3E:94:2C:XX
,06-09 17:15:45.304  4953  4953 I HeadsetProvider: setHeadsetDB - 44:78:3E:94:2C:XX, 400, 1, true
,06-09 17:15:45.304  4953  9461 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,06-09 17:15:45.304  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
,06-09 17:15:45.304  4953  4953 E HeadsetService: notifyProfileServiceStateChanged
,06-09 17:15:45.304  4953  4953 D A2dpService: Received start request. Starting profile...
,06-09 17:15:45.304  4953  9461 D HeadsetStateMachine: Clear mHeadsetBrsf
06-09 17:15:45.304  4953  4953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@de8cfc3
06-09 17:15:45.304  4953  9461 D HeadsetStateMachine: map size, before remove : 0
06-09 17:15:45.304  4953  9461 D HeadsetStateMachine: map size, after remove: 0
06-09 17:15:45.304  4953  4953 I bt_bluedroid: get_profile_interface avrcp
,06-09 17:15:45.314  4953  4953 I Avrcp   : No of Audio players :: 1
06-09 17:15:45.314  4953  4953 I Avrcp   : App Package name is GM
,06-09 17:15:45.314  4953  4953 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,06-09 17:15:45.314  4953  4953 I Avrcp   : No of Video players :: 2
,06-09 17:15:45.314  4953  4953 I Avrcp   : Video App Package name is others
,06-09 17:15:45.314  4953  4953 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,06-09 17:15:45.314  4953  4953 I Avrcp   : Video App Package name is VP
,06-09 17:15:45.314  4953  4953 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,06-09 17:15:45.314  4953  4953 I Avrcp   : Add tempPlayer
06-09 17:15:45.314  4953  4953 V Avrcp   : MediaPlayerInfo: mPlayerId=4
06-09 17:15:45.314  4953  4953 V Avrcp   : no_of_players : 4
06-09 17:15:45.314  4953  4953 I Avrcp   : Total no of players: 4
06-09 17:15:45.314  4953  4953 V Avrcp   : Samsung player is the 1st player
06-09 17:15:45.314  4953  4953 D Avrcp   : Compose Browsing Service Candidate
,06-09 17:15:45.314  4953  4953 D Avrcp   : ResolveInfo info ResolveInfo{77defa7 com.google.android.music/.browse.MediaBrowserService m=0x108000}
06-09 17:15:45.314  4953  4953 D Avrcp   : Initialize Media Controller
,06-09 17:15:45.314  4953  4953 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,06-09 17:15:45.324  4953  4953 E Avrcp   : getActiveSessions
,06-09 17:15:45.324  4953  4953 D Avrcp   : pick active media Controller
06-09 17:15:45.324  4953  4953 D Avrcp   : Get the active Media Controller 
06-09 17:15:45.324  4953  4953 D A2dpStateMachine: make
,06-09 17:15:45.324  4953  4953 I bt_bluedroid: get_profile_interface a2dp
,06-09 17:15:45.324  4953  4953 E bt_btif : warning : media task started media_task_refcnt 1 
,06-09 17:15:45.324  4953  9464 D A2dpStateMachine: Enter Disconnected: -2
,06-09 17:15:45.324  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
,06-09 17:15:45.324  4953  4953 E A2dpService: notifyProfileServiceStateChanged
,06-09 17:15:45.334  4953  4953 D HidService: Received start request. Starting profile...
,06-09 17:15:45.334  4953  4953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@de8cfc3
06-09 17:15:45.334  4953  4953 I bt_bluedroid: get_profile_interface hidhost
,06-09 17:15:45.334  4953  4953 D HidService: setHidService(): set to: null
06-09 17:15:45.334  3503  4414 I Telecom : BluetoothPhoneService: queryPhoneState
06-09 17:15:45.334  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
06-09 17:15:45.334  3503  4414 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
06-09 17:15:45.334  4953  4953 E HidService: notifyProfileServiceStateChanged
06-09 17:15:45.334  4953  4953 D HeadsetStateMachine: Try to query the phonestate on bind
,06-09 17:15:45.334  4953  4953 D HeadsetStateMachine: Proxy object connected
06-09 17:15:45.334  4953  4953 D HealthService: Received start request. Starting profile...
06-09 17:15:45.334  4953  4953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@de8cfc3
,06-09 17:15:45.334  4953  4953 I bt_bluedroid: get_profile_interface health
,06-09 17:15:45.334  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
06-09 17:15:45.334  4953  4953 E HealthService: notifyProfileServiceStateChanged
06-09 17:15:45.334  4953  4953 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,06-09 17:15:45.334  4953  4953 D HeadsetPhoneState: sendDeviceDataStateChanged
06-09 17:15:45.334  4953  9461 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-09 17:15:45.334  4953  9461 E HeadsetStateMachine: Unknown message: 11
06-09 17:15:45.334  4953  4953 D HeadsetPhoneState: Signal level : previous=0 curr=4
06-09 17:15:45.334  4953  9461 D HeadsetStateMachine: Disconnected process message: 19, size: 0
06-09 17:15:45.334  4953  9461 E HeadsetStateMachine: Unknown message: 19
,06-09 17:15:45.334  4953  4953 D PanService: Received start request. Starting profile...
06-09 17:15:45.334  4953  4953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@de8cfc3
06-09 17:15:45.334  4953  4953 D BluetoothPanServiceJni: initializeNative(L118): pan
06-09 17:15:45.334  4953  4953 I bt_bluedroid: get_profile_interface pan
,06-09 17:15:45.334  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
06-09 17:15:45.334  4953  4953 E PanService: notifyProfileServiceStateChanged
,06-09 17:15:45.344  4953  4953 D BluetoothMapService: Received start request. Starting profile...
,06-09 17:15:45.344  4953  4953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@de8cfc3
,06-09 17:15:45.344  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
,06-09 17:15:45.344  4953  4953 E BluetoothMapService: notifyProfileServiceStateChanged
,06-09 17:15:45.344  4953  4953 V SapService: SapBinder()
,06-09 17:15:45.344  4953  4953 D SapService: Received start request. Starting profile...
06-09 17:15:45.344  4953  4953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@de8cfc3
06-09 17:15:45.344  4953  4953 V SapService: start()
06-09 17:15:45.344  4953  4953 D SapService: Disable sap : false
,06-09 17:15:45.354  3503  3975 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4f6d314 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3a11a8 7033:com.google.android.apps.maps/u0a119}
,06-09 17:15:45.354  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
06-09 17:15:45.354  4953  4953 E SapService: notifyProfileServiceStateChanged
,06-09 17:15:45.354  4953  4953 D BleAudioService: Received start request. Starting profile...
06-09 17:15:45.354  4953  4953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@de8cfc3
06-09 17:15:45.354  4953  4953 E DualScoManager: Dual Sco Manager already instantiated
06-09 17:15:45.354  4953  4953 D BleAudioStateMachine: make
,06-09 17:15:45.364  4953  4953 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
06-09 17:15:45.364  4953  4953 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 0
06-09 17:15:45.364  4953  4953 I bt_bluedroid: get_profile_interface bleaudio_source
06-09 17:15:45.364  4953  4953 D BleAudioStateMachine: make
,06-09 17:15:45.364  4953  9469 E BleAudioStateMachine_L: Enter Disconnected: -2
,06-09 17:15:45.364  4953  4953 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
06-09 17:15:45.364  4953  4953 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 1
06-09 17:15:45.364  4953  4953 V BleAudioService: [registerCallStateListener]
,06-09 17:15:45.364  4953  9470 E BleAudioStateMachine_R: Enter Disconnected: -2
,06-09 17:15:45.364  3503  3975 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aab5f6b u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:45.374  4953  4953 V BleAudioService: [registerAobleStateChangeListener]
,06-09 17:15:45.374  4953  4953 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Message sending
,06-09 17:15:45.374  4953  4953 E BleAudioService: notifyProfileServiceStateChanged
06-09 17:15:45.374  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
06-09 17:15:45.374  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
06-09 17:15:45.374  4953  4953 V BluetoothAdapterState: isTurningOff()=false
,06-09 17:15:45.374  4953  4953 V BluetoothAdapterState: isTurningOn()=true
06-09 17:15:45.374  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:45.374  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
06-09 17:15:45.374  4953  4953 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-09 17:15:45.374  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
06-09 17:15:45.374  4953  9461 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-09 17:15:45.374  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
06-09 17:15:45.374  4953  9461 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-09 17:15:45.374  4953  9461 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-09 17:15:45.374  4953  9461 E HeadsetStateMachine: Unknown message: 11
06-09 17:15:45.374  4953  4953 V BluetoothAdapterState: isTurningOff()=false
06-09 17:15:45.374  4953  4953 V BluetoothAdapterState: isTurningOn()=true
06-09 17:15:45.374  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:45.374  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
,06-09 17:15:45.374  4953  4953 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-09 17:15:45.374  4953  4953 D HeadsetPhoneState: sendDeviceDataStateChanged
06-09 17:15:45.374  4953  9461 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-09 17:15:45.374  4953  9461 E HeadsetStateMachine: Unknown message: 11
06-09 17:15:45.374  4953  9461 D HeadsetStateMachine: Disconnected process message: 19, size: 0
06-09 17:15:45.374  4953  4953 D HeadsetPhoneState: Signal level : previous=0 curr=4
06-09 17:15:45.374  4953  9461 E HeadsetStateMachine: Unknown message: 19
06-09 17:15:45.374  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
,06-09 17:15:45.374  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isTurningOff()=false
06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isTurningOn()=true
06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
06-09 17:15:45.384  4953  4953 D BluetoothAdapterService: HID Host service started
,06-09 17:15:45.384  3933  4129 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,06-09 17:15:45.384  4953  4953 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
06-09 17:15:45.384  3933  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
06-09 17:15:45.384  3933  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
06-09 17:15:45.384  3933  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
06-09 17:15:45.384  3933  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
06-09 17:15:45.384  3933  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
06-09 17:15:45.384  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
06-09 17:15:45.384  3933  4129 D HidProfile: mService is null. need to get proxy again!!
06-09 17:15:45.384  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
06-09 17:15:45.384  9069  9069 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,06-09 17:15:45.384  9069  9069 D BluetoothMap: Create BluetoothMap proxy object
,06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isTurningOff()=false
06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isTurningOn()=true
06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
06-09 17:15:45.384  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
06-09 17:15:45.384  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
,06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isTurningOff()=false
,06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isTurningOn()=true
06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
06-09 17:15:45.384  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
06-09 17:15:45.384  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isTurningOff()=false
06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isTurningOn()=true
06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:45.384  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
,06-09 17:15:45.394  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
06-09 17:15:45.394  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,06-09 17:15:45.394  4953  4953 V BluetoothAdapterState: isTurningOff()=false
06-09 17:15:45.394  4953  4953 V BluetoothAdapterState: isTurningOn()=true
06-09 17:15:45.394  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
,06-09 17:15:45.394  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
06-09 17:15:45.394  4953  4953 D BleAudioService: [onCallStateChanged] ENTER -- State: (0)
06-09 17:15:45.394  4953  4953 D BleAudioService: [onCallStateChanged] No devices in connected state
06-09 17:15:45.394  4953  4953 D BleAudioService: [onCallStateChanged][PHONECALL STATE Changed]: EXIT
06-09 17:15:45.394  4953  4953 E BluetoothAdapterService: handleMessage() - Message: 1
06-09 17:15:45.394  4953  4953 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Before synchronized
,06-09 17:15:45.394  3933  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,06-09 17:15:45.394  4953  4953 V BluetoothAdapterState: isTurningOff()=false
06-09 17:15:45.394  4953  4953 V BluetoothAdapterState: isTurningOn()=true
06-09 17:15:45.394  4953  4953 V BluetoothAdapterState: isBleTurningOn()=false
06-09 17:15:45.394  4953  4953 V BluetoothAdapterState: isBleTurningOff()=false
06-09 17:15:45.394  4953  5076 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,06-09 17:15:45.394  4953  5076 E BluetoothServiceJni: enableBrEdrNative:
06-09 17:15:45.394  4953  5076 I bt_bluedroid: enable_bredr
,06-09 17:15:45.394  9069  9069 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,06-09 17:15:45.404  3933  3933 D BluetoothInputDevice: Proxy object connected
06-09 17:15:45.404  3933  3933 D HidProfile: Bluetooth service connected
,06-09 17:15:45.404  4953  5083 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf37eff29
06-09 17:15:45.404  4953  5083 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
06-09 17:15:45.404  4953  5314 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
06-09 17:15:45.404  4953  5083 D BluetoothAdapterProperties: Address is:44:78:3E:94:2C:E6
06-09 17:15:45.404  4953  5083 E BluetoothServiceJni: populateRssiValuesNative
06-09 17:15:45.404  4953  5083 I bt_bluedroid: getModelRssiValues
06-09 17:15:45.404  4953  5083 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
06-09 17:15:45.404  4953  5083 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,06-09 17:15:45.404  4953  5083 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7
,06-09 17:15:45.404  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{ad415f8: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.404  3503  3503 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
06-09 17:15:45.404  4953  5314 D CODEC_IF_MOD: codec_open: codec_open
06-09 17:15:45.404  4953  5314 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
06-09 17:15:45.404  4953  5314 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
06-09 17:15:45.404  4953  5314 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
06-09 17:15:45.404  4953  5314 D CODEC_IF: codec_if_open: codec module opened (v0.1
06-09 17:15:45.404  4953  5314 D CODEC_IF: codec_if_close: codec_if_close hdl -363036668
06-09 17:15:45.404  4953  5314 D CODEC_IF_MOD: codec_close: codec_close
06-09 17:15:45.404  4953  5314 D CODEC_IF_MOD: codec_close: freed apt-x encoder
06-09 17:15:45.404  4953  5314 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
06-09 17:15:45.404  4953  5314 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
06-09 17:15:45.404  4953  5314 D CODEC_IF_SSHD: codec_open: codec_open
06-09 17:15:45.404  4953  5314 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
06-09 17:15:45.404  4953  5314 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
06-09 17:15:45.404  4953  5314 D CODEC_IF: codec_if_open: codec module opened (v0.1
06-09 17:15:45.404  4953  5314 D CODEC_IF: codec_if_close: codec_if_close hdl -558912128
06-09 17:15:45.404  4953  5314 D CODEC_IF_SSHD: codec_close: codec_close
06-09 17:15:45.404  4953  5314 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
06-09 17:15:45.404  4953  5314 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
,06-09 17:15:45.404  4953  5314 D CODEC_IF_MOD: codec_open: codec_open
06-09 17:15:45.404  4953  5314 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
06-09 17:15:45.404  4953  5314 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
06-09 17:15:45.404  4953  5314 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
06-09 17:15:45.404  4953  5314 D CODEC_IF: codec_if_open: codec module opened (v0.1
06-09 17:15:45.404  4953  5314 D CODEC_IF: codec_if_close: codec_if_close hdl -363036668
06-09 17:15:45.404  4953  5314 D CODEC_IF_MOD: codec_close: codec_close
06-09 17:15:45.404  4953  5314 D CODEC_IF_MOD: codec_close: freed apt-x encoder
06-09 17:15:45.404  4953  5314 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
06-09 17:15:45.404  4953  5314 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
06-09 17:15:45.404  4953  5314 D CODEC_IF_SSHD: codec_open: codec_open
06-09 17:15:45.404  4953  5314 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
06-09 17:15:45.404  4953  5314 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
06-09 17:15:45.404  4953  5314 D CODEC_IF: codec_if_open: codec module opened (v0.1
06-09 17:15:45.404  4953  5314 D CODEC_IF: codec_if_close: codec_if_close hdl -558912128
06-09 17:15:45.404  4953  5314 D CODEC_IF_SSHD: codec_close: codec_close
06-09 17:15:45.404  4953  5314 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
,06-09 17:15:45.414  9069  9069 D LocalBluetoothProfileManager: Adding local BleAudio profile
,06-09 17:15:45.414  4953  5083 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
06-09 17:15:45.414  4953  5083 D BluetoothAdapterProperties: Scan Mode:20
06-09 17:15:45.414  4953  5083 D BluetoothAdapterProperties: Discoverable Timeout:-1
06-09 17:15:45.414  4953  5083 E bt_btif : btif_handle_bluetooth_enable_evt
06-09 17:15:45.414  9069  9069 D BluetoothLeAudio: getProfileProxy()
06-09 17:15:45.414  4953  5083 E bt_btif : JVenable fails
,06-09 17:15:45.414  4953  5083 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
06-09 17:15:45.414  4953  5083 D IOP_DB_BT: db_open: db_open : handle 4084670480l, read 18483 bytes onto local cache
06-09 17:15:45.414  4953  5083 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
06-09 17:15:45.414  4953  5083 D IOP_DB_BT: db_query: result 1
06-09 17:15:45.414  4953  5083 I         : iop_db_open: iop_db_open status 0
06-09 17:15:45.414  4953  5083 E BluetoothAdapterState: stateChangeCallback : 17
06-09 17:15:45.414  4953  5083 E bt_btif : no av cb found, event:0, BTA_A [NonDisc-0, ignored!
06-09 17:15:45.414  4953  5083 E bt_btif : btif_sm_dispatch : Invalid handle
06-09 17:15:45.414  4953  5083 E bt_btif : no av control block available at state:3
06-09 17:15:45.414  4953  5083 E bt_btif : btm_sec_set_security_level : sec: 0x36
06-09 17:15:45.414  4953  5083 E bt_btif :                : sec: 0x30b6e at state:2
06-09 17:15:45.414  4953  5083 E bt_btif :                : sec: 0x30b6, service na
06-09 17:15:45.414  4953  5083 E bt_btif : no av control block available at state:3
06-09 17:15:45.414  4953  5083 E bt_btif : BTM_SEC_REG[13]: id 25evel : sec: 0x36
06-09 17:15:45.414  4953  5083 W bt_btif : BTM_SEC_REG[13]: id 25evel : sec: 0x36
,06-09 17:15:45.414  4953  5083 E bt_btif : Adding UUID=0x11 : into EIR,
06-09 17:15:45.414  4953  5083 E bt_btif : Adding UUID=0x1116 into EIR
06-09 17:15:45.414  4953  5083 E bt_btif : no av control block available at state:3
06-09 17:15:45.414  4953  5083 E bt_btif : no av control block available at state:2
06-09 17:15:45.414  4953  5083 E bt_btif : Write Extended Inquiry Response to contr
06-09 17:15:45.414  4953  5083 E bt_btif : Adding UUID=0x1115 into EIR
06-09 17:15:45.414  4953  5083 E bt_btif : no av control block available at state:2
06-09 17:15:45.414  4953  5083 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
06-09 17:15:45.414  4953  5083 E bt_btif : btif_sm_dispatch : Invalid handle
06-09 17:15:45.414  4953  5083 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
06-09 17:15:45.414  4953  5076 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
,06-09 17:15:45.424  4953  5076 D BluetoothAdapterProperties: ScanMode =  20
06-09 17:15:45.424  4953  5076 D BluetoothAdapterProperties: State =  11
,06-09 17:15:45.424  3503  4412 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,06-09 17:15:45.424  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{1004936: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.434  3503  3848 D SecContentProvider: insert(), uri = 2
,06-09 17:15:45.434  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:45.434  4953  5076 D BluetoothAdapterProperties: Setting state to 12
06-09 17:15:45.434  4953  5076 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
06-09 17:15:45.434  4953  5076 D HeadsetService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@bc918dd
06-09 17:15:45.434  4953  5076 D A2dpService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@bc918dd
06-09 17:15:45.434  4953  5076 D BleAudioService: setHeadsetService: setting HeadsetService
06-09 17:15:45.434  4953  5076 D BleAudioService: setA2dpService: setting A2dpService
06-09 17:15:45.434  4953  5076 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-09 17:15:45.434  4953  5076 D BluetoothAdapterService: updateAdapterState state is 12
06-09 17:15:45.434  9069  9069 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,06-09 17:15:45.434  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{159930d: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.444  4953  5076 V BluetoothAdapterService: start opp service
,06-09 17:15:45.444  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,06-09 17:15:45.454  4953  5083 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
06-09 17:15:45.454  4953  5083 D BluetoothAdapterProperties: Scan Mode:21
06-09 17:15:45.454  4953  5083 D BluetoothAdapterProperties: Discoverable Timeout:-1
,06-09 17:15:45.454  9069  9069 D BluetoothMap: Proxy object connected
,06-09 17:15:45.454  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{5995309: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.454  9069  9069 D MapProfile: Bluetooth service connected
06-09 17:15:45.454  9069  9069 D BluetoothMap: getConnectedDevices()
,06-09 17:15:45.454  4953  5076 D BluetoothAdapterService: Autoconnection is available 
06-09 17:15:45.454  4953  5076 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
06-09 17:15:45.454  4953  5076 D BluetoothAdapterService: starting service from this receiver
,06-09 17:15:45.454  4226  4237 D BluetoothAdapter: onBluetoothStateChange: up=true
06-09 17:15:45.454  4226  4237 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-09 17:15:45.454  9370  9370 D BluetoothAdapter: STATE_ON
,06-09 17:15:45.464  9069  9080 D BluetoothLeAudio: onBluetoothStateChange: up=true
06-09 17:15:45.464  9069  9080 D BluetoothLeAudio: Binding service...
,06-09 17:15:45.464  9370  9370 D BluetoothAdapter: STATE_ON
,06-09 17:15:45.464  9370  9370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
06-09 17:15:45.464  4953  5076 D BluetoothAdapterService: BT on, init HID DEV count : 0
06-09 17:15:45.464  4953  5076 I BluetoothAdapterState: Entering OnState
06-09 17:15:45.464  9069  9080 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,06-09 17:15:45.464  3503  3601 D BluetoothAdapter: onBluetoothStateChange: up=true
06-09 17:15:45.464  3503  3601 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-09 17:15:45.464  4953  4953 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,06-09 17:15:45.474  9069  9080 D BluetoothSap: onBluetoothStateChange: up=true
06-09 17:15:45.474  9069  9080 D BluetoothSap: Binding service...
,06-09 17:15:45.474  4953  4953 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,06-09 17:15:45.474  9069  9069 D BluetoothInputDevice: Proxy object connected
,06-09 17:15:45.474  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{cb793c: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:45.474  9069  9069 D HidProfile: Bluetooth service connected
,06-09 17:15:45.474  4953  4953 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,06-09 17:15:45.474  9370  9370 D BluetoothAdapter: STATE_ON
,06-09 17:15:45.484  4953  4953 V BtOppService: isOwner == true
,06-09 17:15:45.484  3933  5501 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-09 17:15:45.484  3933  5501 D BluetoothA2dp: Binding service...
,06-09 17:15:45.484  9370  9370 D BluetoothAdapter: STATE_ON
,06-09 17:15:45.484  3933  5501 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,06-09 17:15:45.484  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{634ef4b: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.484  9370  9370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,06-09 17:15:45.484  9069  9069 D BluetoothLeAudio: Proxy object connected
,06-09 17:15:45.494  9069  9069 D BleAudioProfile: Bluetooth service connected
,06-09 17:15:45.494  9069  9069 D BluetoothLeAudio: getConnectedDevices()
,06-09 17:15:45.494  3933  4324 D BluetoothAdapter: onBluetoothStateChange: up=true
06-09 17:15:45.494  3933  4324 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-09 17:15:45.494  3933  4602 D BluetoothSap: onBluetoothStateChange: up=true
,06-09 17:15:45.494  3933  4602 D BluetoothSap: Binding service...
06-09 17:15:45.494  9069  9069 D BluetoothPbap: Proxy object connected
,06-09 17:15:45.494  9069  9069 D PbapServerProfile: Bluetooth service connected
,06-09 17:15:45.504  4953  4953 I BluetoothPbapService: Handler(): got msg=1
,06-09 17:15:45.504  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{e62597d: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.504  3503  4415 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,06-09 17:15:45.504  3933  3952 D BluetoothPan: onBluetoothStateChange on: true
,06-09 17:15:45.504  3933  3952 D BluetoothPan: onBluetoothStateChange calling doBind()
,06-09 17:15:45.514  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{e4e3940: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.514  9370  9370 D BluetoothAdapter: STATE_ON
,06-09 17:15:45.514  4953  9476 V BluetoothPbapService: PBAP Service initSocket try: 0
,06-09 17:15:45.514  4953  5382 D BluetoothAdapter: onBluetoothStateChange: up=true
06-09 17:15:45.514  4953  5382 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-09 17:15:45.514  3933  3944 D BluetoothInputDevice: onBluetoothStateChange: up=true
06-09 17:15:45.514  3933  3944 D BluetoothInputDevice: Binding service...
,06-09 17:15:45.514  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{a9da21f: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.524  4953  9476 D BluetoothSocket: bindListen(): myUserId = 0
06-09 17:15:45.524  4953  9476 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-09 17:15:45.524  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-09 17:15:45.524  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:45.524  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:45.524  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-09 17:15:45.524  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-09 17:15:45.524  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-09 17:15:45.524  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-09 17:15:45.524  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-09 17:15:45.524  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-09 17:15:45.524  3933  3933 D BluetoothInputDevice: Proxy object connected
06-09 17:15:45.524  3933  3933 D HidProfile: Bluetooth service connected
,06-09 17:15:45.524  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{194666e: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.534  9069  9081 D BluetoothInputDevice: onBluetoothStateChange: up=true
,06-09 17:15:45.534  9069  9473 D BluetoothMap: onBluetoothStateChange: up=true
,06-09 17:15:45.534  4953  9476 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,06-09 17:15:45.534  3933  4324 D BluetoothInputDevice: onBluetoothStateChange: up=true
,06-09 17:15:45.534  9370  9370 D BluetoothAdapter: STATE_ON
,06-09 17:15:45.534  7439  7449 D BluetoothAdapter: onBluetoothStateChange: up=true
06-09 17:15:45.534  7439  7449 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-09 17:15:45.534  3933  4602 D BluetoothPbap: onBluetoothStateChange: up=true
06-09 17:15:45.534  3933  4602 D BluetoothPbap: Binding service...
,06-09 17:15:45.544  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{a79510f: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.544  3933  3933 D BluetoothSap: Proxy object connected
06-09 17:15:45.544  3933  3933 D SapProfile: Bluetooth service connected
,06-09 17:15:45.544  9069  9069 D BluetoothSap: Proxy object connected
06-09 17:15:45.544  9069  9069 D SapProfile: Bluetooth service connected
,06-09 17:15:45.544  9370  9370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,06-09 17:15:45.544  3933  3933 D BluetoothPbap: Proxy object connected
,06-09 17:15:45.544  3933  3933 D PbapServerProfile: Bluetooth service connected
,06-09 17:15:45.544  3933  3933 D BluetoothA2dp: Proxy object connected
,06-09 17:15:45.544  3933  3933 D A2dpProfile: Bluetooth service connected
,06-09 17:15:45.554  3503  4415 V AlarmManager:  remove PendingIntent] PendingIntent{aa47b7a: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.554  3503  4845 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,06-09 17:15:45.554  4953  5387 D A2dpStateMachine: getConnectedDevices : size=0
,06-09 17:15:45.554  9069  9081 D BluetoothPbap: onBluetoothStateChange: up=true
,06-09 17:15:45.554  4990  5007 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-09 17:15:45.554  4990  5007 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-09 17:15:45.554  8694  8704 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-09 17:15:45.554  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{3ef2b: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.554  8694  8704 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-09 17:15:45.554  3933  3952 D BluetoothMap: onBluetoothStateChange: up=true
06-09 17:15:45.554  3933  3952 D BluetoothMap: Binding service...
,06-09 17:15:45.564  3933  3933 D BluetoothPan: BluetoothPAN Proxy object connected
,06-09 17:15:45.564  3933  3933 D PanProfile: Bluetooth service connected
,06-09 17:15:45.564  3503  3601 D BluetoothPan: onBluetoothStateChange on: true
,06-09 17:15:45.564  3503  3601 D BluetoothPan: onBluetoothStateChange calling doBind()
06-09 17:15:45.564  3503  3503 D BluetoothPan: BluetoothPAN Proxy object connected
,06-09 17:15:45.564  7033  7043 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-09 17:15:45.564  7033  7043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-09 17:15:45.564  3933  3933 D BluetoothMap: Proxy object connected
06-09 17:15:45.564  3933  3933 D MapProfile: Bluetooth service connected
,06-09 17:15:45.564  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{ce9ac34: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:45.564  3933  3933 D BluetoothMap: getConnectedDevices()
,06-09 17:15:45.574  4953  9478 D BluetoothSocket: bindListen(): myUserId = 0
,06-09 17:15:45.574  4953  9478 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-09 17:15:45.574  9069  9473 D BluetoothAdapter: onBluetoothStateChange: up=true
06-09 17:15:45.574  9069  9473 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-09 17:15:45.574  4241  5649 D BluetoothAdapter: onBluetoothStateChange: up=true
06-09 17:15:45.574  4241  5649 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-09 17:15:45.574  4953  9478 I BtOppRfcommListener: Accept thread started.
,06-09 17:15:45.574  3933  4602 D BluetoothLeAudio: onBluetoothStateChange: up=true
,06-09 17:15:45.574  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{62e5a5d: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:45.574  3933  4602 D BluetoothLeAudio: Binding service...
,06-09 17:15:45.574  4953  9477 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,06-09 17:15:45.574  3933  3933 D BluetoothLeAudio: Proxy object connected
06-09 17:15:45.574  3933  3933 D BleAudioProfile: Bluetooth service connected
06-09 17:15:45.574  3933  3933 D BluetoothLeAudio: getConnectedDevices()
06-09 17:15:45.574  3933  4602 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,06-09 17:15:45.584  4254  5421 D BluetoothAdapter: onBluetoothStateChange: up=true
06-09 17:15:45.584  4254  5421 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-09 17:15:45.584  3503  4293 V AlarmManager:  remove PendingIntent] PendingIntent{81518a3: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.584  4990  5006 D BluetoothA2dp: onBluetoothStateChange: up=true
06-09 17:15:45.584  4990  5006 D BluetoothA2dp: Binding service...
,06-09 17:15:45.584  4990  5006 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,06-09 17:15:45.584  4953  9477 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,06-09 17:15:45.584  4990  4990 D BluetoothA2dp: Proxy object connected
,06-09 17:15:45.584  3503  3601 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-09 17:15:45.584  3503  3601 D BluetoothA2dp: Binding service...
06-09 17:15:45.584  3503  3601 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
06-09 17:15:45.584  3503  4209 V AlarmManager:  remove PendingIntent] PendingIntent{39d471e: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.584  3503  3503 D BluetoothA2dp: Proxy object connected
,06-09 17:15:45.594  4953  5387 D A2dpStateMachine: getConnectedDevices : size=0
,06-09 17:15:45.594  9370  9380 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-09 17:15:45.594  9370  9380 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-09 17:15:45.594  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{f177815: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:45.594  9069  9080 D BluetoothPan: onBluetoothStateChange on: true
06-09 17:15:45.594  9069  9080 D BluetoothPan: onBluetoothStateChange calling doBind()
,06-09 17:15:45.594  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{10c7ab8: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.594  9069  9069 D BluetoothPan: BluetoothPAN Proxy object connected
,06-09 17:15:45.594  9069  9069 D PanProfile: Bluetooth service connected
,06-09 17:15:45.604  3503  3503 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,06-09 17:15:45.604  3503  3503 I InputMethodManagerService: [BT Setting State] State =12
06-09 17:15:45.604  3503  3503 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,06-09 17:15:45.604  3933  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,06-09 17:15:45.604  3933  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,06-09 17:15:45.604  4298  4298 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,06-09 17:15:45.604  3503  3503 I Telecom : BluetoothPhoneService: queryPhoneState
,06-09 17:15:45.604  4746  4746 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
06-09 17:15:45.604  3503  3503 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
06-09 17:15:45.604  9370  9451 D BluetoothAdapter: STATE_ON
,06-09 17:15:45.604  3503  3503 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,06-09 17:15:45.604  3503  3503 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:45.604  3503  3503 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,06-09 17:15:45.614  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,06-09 17:15:45.614  9370  9451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-09 17:15:45.614  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:45.614  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:45.614  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-09 17:15:45.614  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-09 17:15:45.614  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-09 17:15:45.614  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-09 17:15:45.614  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-09 17:15:45.614  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-09 17:15:45.614  9370  9433 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,06-09 17:15:45.624  3503  4408 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-09 17:15:45.624  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:45.624  3503  4408 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-09 17:15:45.624  9370  9433 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:45.624  3503  4408 D WifiService: setWifiEnabled: false pid=9370, uid=10074
,06-09 17:15:45.634  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2048091 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6c9d1a2 9069:com.android.settings/1000}
,06-09 17:15:45.634  9069  9069 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,06-09 17:15:45.634  9069  9069 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,06-09 17:15:45.644  9479  9479 E Zygote  : v2
06-09 17:15:45.644  9479  9479 I libpersona: KNOX_SDCARD checking this for 10049
06-09 17:15:45.644  9479  9479 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:45.654  9479  9479 E Zygote  : isSdpEnabledProcess - SDP enabled
,06-09 17:15:45.654  9479  9479 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:15:45.654  3503  3981 I ActivityManager: Start proc 9479:com.samsung.android.email.provider/u0a49 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
,06-09 17:15:45.654  3503  4408 D SettingsProvider: isChangeAllowed() : name = wifi_on
06-09 17:15:45.654  9479  9479 E Zygote  : accessInfo : 64
,06-09 17:15:45.654  3503  3852 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
06-09 17:15:45.654  9479  9479 E Zygote  : isSdpEnabledProcess - SDP enabled
,06-09 17:15:45.654  3503  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
06-09 17:15:45.654  9479  9479 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
06-09 17:15:45.654  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{c3d1bf6: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:45.654  9479  9479 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
06-09 17:15:45.654  3503  3857 D WifiController: [FCC]setFccChannel() is called !!!
,06-09 17:15:45.654  3503  3854 D WifiBigDataLog: getJsonFormat() - feature : ONOF
06-09 17:15:45.654  3503  3857 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
06-09 17:15:45.654  3503  3857 D WifiStateMachine: setFccChannel: channel = -1
06-09 17:15:45.654  3503  3857 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
06-09 17:15:45.654  3503  3857 D SecContentProvider: insert(), uri = 2
,06-09 17:15:45.664  3933  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
06-09 17:15:45.664  3933  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
06-09 17:15:45.664  3933  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
06-09 17:15:45.664  3933  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
,06-09 17:15:45.664  3933  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,06-09 17:15:45.664  3503  3854 D WifiBigDataLog: init : 
,06-09 17:15:45.664  9069  9069 D LocalBluetoothProfileManager: Adding local A2DP profile
,06-09 17:15:45.674  3503  3854 D WifiStateMachine: setFccChannelNative: channel = -1
,06-09 17:15:45.674  3503  3854 D WifiNative-wlan0: callSECApiInt - ID [230]
,06-09 17:15:45.674  3503  3852 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: true, uidstate: 16, mProxSensorScreenOff: false
,06-09 17:15:45.674  9069  9069 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,06-09 17:15:45.684  3503  4415 V AlarmManager:  remove PendingIntent] PendingIntent{3170182: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.694  9069  9069 D LocalBluetoothProfileManager: Adding local HEADSET profile
,06-09 17:15:45.694  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{7ddb0c9: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.694  9069  9069 E BluetoothHeadset: BTStateChangeCB is registed
,06-09 17:15:45.694  9069  9069 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
06-09 17:15:45.704  9069  9069 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
06-09 17:15:45.704  9069  9069 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
06-09 17:15:45.704  9069  9069 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
06-09 17:15:45.704  9069  9069 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,06-09 17:15:45.704  9479  9479 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:45.704  9479  9479 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:45.704  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{6bac1fc: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.704  3503  3854 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,06-09 17:15:45.714  9069  9069 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,06-09 17:15:45.714  3503  3854 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,06-09 17:15:45.714  3933  4163 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,06-09 17:15:45.714  3503  4408 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f02049a) visible user=0 )
06-09 17:15:45.724  3503  4845 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,06-09 17:15:45.724  3503  3854 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-09 17:15:45.724  3503  3854 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,06-09 17:15:45.724  3503  3854 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-09 17:15:45.734  9479  9479 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,06-09 17:15:45.734  9069  9069 D BluetoothA2dp: Proxy object connected
,06-09 17:15:45.734  9069  9069 D A2dpProfile: Bluetooth service connected
,06-09 17:15:45.734  3933  4129 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:15:45.734  3933  4129 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,06-09 17:15:45.744  3503  4413 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:15:45.744  9479  9479 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
06-09 17:15:45.744  3503  4209 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2048091 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:45.744  9479  9479 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:45.754  3503  3854 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-09 17:15:45.754  3503  3854 D SecContentProvider: insert(), uri = 2
,06-09 17:15:45.754  4953  5382 D A2dpStateMachine: getConnectedDevices : size=0
,06-09 17:15:45.754  9479  9479 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:45.764  3503  4209 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2048091 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{270f4ef 4226:com.google.android.gms.persistent/u0a19}
,06-09 17:15:45.764  4226  4226 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,06-09 17:15:45.764  3503  3854 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,06-09 17:15:45.764  3503  3854 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-09 17:15:45.764  3503  3854 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,06-09 17:15:45.764  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{89f3eda: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.774  3933  4129 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:15:45.774  3933  4129 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,06-09 17:15:45.774  3503  4408 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2048091 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff468ad 8694:com.sec.android.app.shealth:remote/u0a36}
,06-09 17:15:45.784  9479  9479 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,06-09 17:15:45.784  9069  9069 D DockEventReceiver: finishStartingService: stopping service
,06-09 17:15:45.784  3503  3854 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,06-09 17:15:45.794  3503  4408 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2048091 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6c9d1a2 9069:com.android.settings/1000}
,06-09 17:15:45.794  9069  9069 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:45.794  9069  9069 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,06-09 17:15:45.794  3503  3854 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-09 17:15:45.794  3503  3854 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,06-09 17:15:45.804  3503  3853 D WifiP2pService: InactiveState{ what=143375 }
,06-09 17:15:45.804  3503  3853 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-09 17:15:45.804  3503  3524 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2048091 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12753ec 4953:com.android.bluetooth/1002}
,06-09 17:15:45.804  3503  4845 D RCPManagerService: exchangeData() failure , invalid userId
,06-09 17:15:45.814  3503  4873 V AlarmManager:  remove PendingIntent] PendingIntent{2f001e8: PendingIntentRecord{c8c4bb0 android broadcastIntent}}
,06-09 17:15:45.814  3154  3616 D CommandListener: Clearing all IP addresses on wlan0
,06-09 17:15:45.814  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-09 17:15:45.824  4226  7602 V NativeCrypto: Read error: ssl=0x7fa557a080: I/O error during system call, Connection timed out
,06-09 17:15:45.834  3503  4414 V AlarmManager:  remove PendingIntent] PendingIntent{235b001: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.834  3503  3863 E ConnectivityService: updateNetworkInfo()
06-09 17:15:45.834  3503  3863 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
06-09 17:15:45.834  3503  3863 E ConnectivityService: updateNetworkInfo()
06-09 17:15:45.834  3503  3863 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
06-09 17:15:45.834  3503  3863 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 6
,06-09 17:15:45.834  3503  3863 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:15:45.834  3503  3863 V NetworkStats: updateIfacesLocked()
06-09 17:15:45.834  3503  3863 V NetworkStats: performPollLocked(flags=0x1)
,06-09 17:15:45.854  4226  7602 V NativeCrypto: SSL shutdown failed: ssl=0x7fa557a080: I/O error during system call, Broken pipe
06-09 17:15:45.854  3503  3863 D NetworkStatsRecorder: entry.iface is null
06-09 17:15:45.854  3503  3863 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:15:45.854  3503  3863 D NetworkStatsRecorder: entry.iface is null
06-09 17:15:45.854  3503  3863 D NetworkStatsRecorder: entry.iface is null
06-09 17:15:45.854  3503  3863 D NetworkStatsRecorder: entry.iface is null
06-09 17:15:45.854  3503  3863 V NetworkStats: performPollLocked() took 12ms
,06-09 17:15:45.854  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{e426ea6: PendingIntentRecord{faa78c4 com.google.android.gms broadcastIntent}}
,06-09 17:15:45.854  4226  7602 E GCM     : Wifi connection closed with errorCode 20
,06-09 17:15:45.864  3503  3503 I WifiTrafficPoller: evaluateTrafficStatsPolling
,06-09 17:15:45.864  3503  3503 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
06-09 17:15:45.864  3503  3503 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
,06-09 17:15:45.864  3503  3503 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
,06-09 17:15:45.864  3503  3503 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
06-09 17:15:45.864  3503  3861 I WifiHs20Service: Message received 5007
,06-09 17:15:45.864  3503  3503 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,06-09 17:15:45.874  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-09 17:15:45.874  4254  4254 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
06-09 17:15:45.874  3503  3863 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:45.874  3503  3854 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
06-09 17:15:45.874  3503  3863 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
06-09 17:15:45.874  3503  3863 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
06-09 17:15:45.874  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:45.874  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:45.874  3503  3863 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:45.884  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
06-09 17:15:45.884  3503  3863 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [] ]
06-09 17:15:45.884  3503  3853 D WifiP2pService: InactiveState{ what=131204 }
06-09 17:15:45.884  3503  3853 D WifiP2pService: P2pEnabledState{ what=131204 }
06-09 17:15:45.884  3503  3853 D WifiP2pService: sending p2p persistent groups changed broadcast
,06-09 17:15:45.884  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:45.894  3503  3863 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:45.894  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:45.894  3503  3863 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:45.904  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:45.904  3503  3863 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:45.904  3503  4412 D ConnectivityService: getVpnConfig > userId : 0
,06-09 17:15:45.904  3503  3863 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:45.904  3503  4870 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,06-09 17:15:45.904  3503  3890 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:45.904  3503  3890 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
06-09 17:15:45.904  3503  3890 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
06-09 17:15:45.904  3503  3890 D Ethernet: evalRequest
06-09 17:15:45.904  3503  3890 D Ethernet:   done
,06-09 17:15:45.914  3503  3854 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:45.914  3503  3854 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:45.914  3503  3854 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-09 17:15:45.914  3503  3854 D WIFI_UT : evalRequest
06-09 17:15:45.914  3503  3854 D WIFI_UT :   done
,06-09 17:15:45.914  3503  3854 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:45.914  3503  3854 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:45.914  3503  3854 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-09 17:15:45.914  3503  3854 D WIFI    : evalRequest
06-09 17:15:45.914  3503  3854 D WIFI    :   done
06-09 17:15:45.914  3503  3854 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:45.914  3503  3854 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:45.914  3503  3854 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
06-09 17:15:45.914  3503  3854 D WIFI    : evalRequest
06-09 17:15:45.914  3503  3854 D WIFI    :   needNetworkFor
,06-09 17:15:45.934  3503  3503 D RttService: SCAN_AVAILABLE : 1
,06-09 17:15:45.934  3503  3889 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,06-09 17:15:45.934  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
,06-09 17:15:45.934  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
,06-09 17:15:45.934  3503  4293 D RCPManagerService: exchangeData() failure , invalid userId
,06-09 17:15:45.944  4118  4118 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,06-09 17:15:45.944  3503  3503 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
06-09 17:15:45.944  4118  4118 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
06-09 17:15:45.944  3503  3503 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
06-09 17:15:45.944  3503  3853 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,06-09 17:15:45.944  3933  3933 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,06-09 17:15:45.944  3503  3601 D EntConnectivity: Not allowed due to - mEnabled false
,06-09 17:15:45.944  9479  9479 D InjectionManager: InjectionManager
,06-09 17:15:45.944  9479  9479 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,06-09 17:15:45.944  3503  4209 V AlarmManager:  remove PendingIntent] PendingIntent{4b75494: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:45.954  9479  9479 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
06-09 17:15:45.954  9479  9479 I InjectionManager: featureStore :{}
,06-09 17:15:45.954  3503  3602 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:45.954  3503  3602 I WifiDisplayAdapter: onP2pDisconnected
06-09 17:15:45.954  3503  3602 D IpRemoteDisplayController: disconnectWfdBridgeServer
06-09 17:15:45.954  3503  3602 D IpRemoteDisplayController: WfdBridgeServer is already null
,06-09 17:15:45.954  3933  3933 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,06-09 17:15:45.954  4953  4953 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
06-09 17:15:45.954  3503  3853 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
06-09 17:15:45.954  4953  4953 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is12
06-09 17:15:45.964  4953  9469 D BleAudioStateMachine_L: [Disconnected] Disconnected process message: 41
06-09 17:15:45.964  4953  9469 D BleAudioStateMachine_L: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
06-09 17:15:45.964  4953  9470 D BleAudioStateMachine_R: [Disconnected] Disconnected process message: 41
06-09 17:15:45.964  4953  9470 D BleAudioStateMachine_R: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,06-09 17:15:45.964  3503  3853 D SecContentProvider: insert(), uri = 2
,06-09 17:15:45.964  3154  3616 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,06-09 17:15:45.964  4953  9469 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 1
,06-09 17:15:45.964  4953  9470 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 2
06-09 17:15:45.964  4953  9469 D BleAudioService: NotifyEvents: n : 0
,06-09 17:15:45.964  4953  9470 D BleAudioService: NotifyEvents: n : 0
06-09 17:15:45.964  3503  3503 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
06-09 17:15:45.964  3503  3853 D WifiP2pService: P2pDisablingState
06-09 17:15:45.964  3503  3602 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
06-09 17:15:45.964  3503  3602 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
06-09 17:15:45.964  3503  3853 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:45.964  3503  3853 D WifiP2pService: P2pDisablingState{ what=147458 }
06-09 17:15:45.964  3503  3602 D WifiDisplayController: disconnect
,06-09 17:15:45.964  3503  3853 D WifiP2pService: p2p socket connection lost
06-09 17:15:45.964  3503  3853 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:45.974  3503  3853 D WifiP2pService: P2pDisabledState
06-09 17:15:45.964  3503  3853 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
06-09 17:15:45.964  3503  3853 D WIFI_P2P: evalRequest
06-09 17:15:45.964  3503  3602 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
06-09 17:15:45.964  3503  3853 D WIFI_P2P:   done
06-09 17:15:45.964  3503  3853 D SecContentProvider: insert(), uri = 2
06-09 17:15:45.974  3503  3602 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
,06-09 17:15:45.964  3933  3933 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
06-09 17:15:45.974  3503  3602 I WifiDisplayAdapter: onP2pDisconnected
06-09 17:15:45.974  3503  3602 D IpRemoteDisplayController: disconnectWfdBridgeServer
06-09 17:15:45.974  3503  3602 D IpRemoteDisplayController: WfdBridgeServer is already null
,06-09 17:15:45.974  3503  3854 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
06-09 17:15:45.974  3933  3933 D HeadsetProfile: Bluetooth service connected
,06-09 17:15:45.974  3503  3853 D WifiP2pService: P2pDisabledState{ what=143375 }
,06-09 17:15:45.974  3503  3853 D WifiP2pService: DefaultState{ what=143375 }
,06-09 17:15:45.974  4953  4953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@de8cfc3
06-09 17:15:45.974  4953  4953 D BtConfig.SecureMode: isSecureModeOn:false
,06-09 17:15:45.974  9069  9069 D HeadsetProfile: Bluetooth service connected
,06-09 17:15:45.984  3154  3616 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,06-09 17:15:45.984  3503  3863 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
06-09 17:15:45.984  3503  3863 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
06-09 17:15:45.984  3503  3863 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,06-09 17:15:45.994  3503  3601 D EntConnectivity: Not allowed due to - mEnabled false
,06-09 17:15:45.994  3154  3616 D CommandListener: Clearing all IP addresses on wlan0
06-09 17:15:45.994  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{c4c4b3d: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:46.004  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-09 17:15:46.004  3503  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2048091 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3a11a8 7033:com.google.android.apps.maps/u0a119}
,06-09 17:15:46.014  3933  3933 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
06-09 17:15:46.014  3933  3933 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
06-09 17:15:46.014  3933  3933 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,06-09 17:15:46.014  3503  4845 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
06-09 17:15:46.014  3933  3933 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,06-09 17:15:46.034  9506  9506 E Zygote  : v2
06-09 17:15:46.034  9506  9506 I libpersona: KNOX_SDCARD checking this for 10003
06-09 17:15:46.034  9506  9506 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:46.034  9506  9506 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-09 17:15:46.034  3503  4408 I ActivityManager: Start proc 9506:com.sec.android.provider.badge/u0a3 for content provider com.sec.android.provider.badge/.BadgeProvider
,06-09 17:15:46.034  9506  9506 E Zygote  : accessInfo : 0
06-09 17:15:46.034  9506  9506 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,06-09 17:15:46.034  3503  4293 I ActivityManager: Killing 8778:com.samsung.android.app.aodservice:settingui/u0a0 (adj 15): DHA:empty #33
,06-09 17:15:46.044  4953  4953 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,06-09 17:15:46.054  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-09 17:15:46.064  3503  3588 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
06-09 17:15:46.064  3503  3588 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:46.064  3503  3588 D GpsLocationProvider: updateNetworkState unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:46.074  4746  4746 D SamsungIME: EngineType = SWIFTKEY
,06-09 17:15:46.074  4746  4746 D SamsungIME: mNetworkChangeReceiver isWLANConnected : false
,06-09 17:15:46.074  5001  5100 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
06-09 17:15:46.074  5001  5100 I CellLocationSupport: onCellLocationChanged
,06-09 17:15:46.074  9506  9506 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:46.074  9506  9506 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:46.084  5001  5001 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
06-09 17:15:46.084  5001  5001 D PdnController: isSuspended [false] networktype [1]
,06-09 17:15:46.084  3503  4415 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:46.084  5001  5001 D PdnController: isPdnUp  [false] networktype [1]
06-09 17:15:46.084  5001  5001 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [false] 
,06-09 17:15:46.094  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
,06-09 17:15:46.094  5393  5393 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f6e08df and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:15:46.094  3503  3852 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:46.094  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:15:46.094  3503  3852 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,06-09 17:15:46.094  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:15:46.094  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
,06-09 17:15:46.094  5001  5100 I CellLocationSupport: Block to update PANI information in non VoWIFI
,06-09 17:15:46.094  5001  5100 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
06-09 17:15:46.094  3503  3524 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.094  5001  5100 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
06-09 17:15:46.094  5001  5100 D PdnController: isPdnUp  [false] networktype [0]
06-09 17:15:46.094  5001  5100 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,06-09 17:15:46.104  4254  4617 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,06-09 17:15:46.104  3154  3616 E Netd    : netlink response contains error (No such file or directory)
,06-09 17:15:46.104  3154  3612 D EnterpriseController: netId is 0
06-09 17:15:46.104  3154  3612 D Netd    : getNetworkForDns: using netid 0 for uid 10001
,06-09 17:15:46.104  3503  3863 D ConnectivityService: nai.networkMonitor.doQuit()
06-09 17:15:46.104  3503  3863 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
06-09 17:15:46.104  3503  3863 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
06-09 17:15:46.104  3503  3863 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:46.104  3503  3863 E ConnectivityService: updateNetworkInfo()
06-09 17:15:46.104  3503  3863 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
06-09 17:15:46.104  3503  3863 E ConnectivityService: updateNetworkInfo()
,06-09 17:15:46.104  4542  9522 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
06-09 17:15:46.104  4542  9522 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
06-09 17:15:46.104  4542  9522 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
06-09 17:15:46.104  4542  9522 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-09 17:15:46.104  4542  9522 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
06-09 17:15:46.104  4542  9522 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
06-09 17:15:46.104  4542  9522 E         : 	at java.lang.Thread.run(Thread.java:818)
06-09 17:15:46.104  4542  9522 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
06-09 17:15:46.104  4542  9522 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
06-09 17:15:46.104  4542  9522 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
06-09 17:15:46.104  4542  9522 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
06-09 17:15:46.104  4542  9522 E         : 	... 9 more
06-09 17:15:46.104  4542  9522 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
06-09 17:15:46.104  4542  9522 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
06-09 17:15:46.104  4542  9522 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
06-09 17:15:46.104  4542  9522 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
06-09 17:15:46.104  4542  9522 E         : 	... 24 more
06-09 17:15:46.104  4542  9522 E         : 
06-09 17:15:,46.104  4542  9522 E         : Unable to fetch advertisement frequency.
06-09 17:15:46.104  4542  9522 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
06-09 17:15:46.104  4542  9522 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
06-09 17:15:46.104  4542  9522 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-09 17:15:46.104  4542  9522 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
06-09 17:15:46.104  4542  9522 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
06-09 17:15:46.104  4542  9522 E         : 	at java.lang.Thread.run(Thread.java:818)
06-09 17:15:46.104  4542  9522 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
06-09 17:15:46.104  4542  9522 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
06-09 17:15:46.104  4542  9522 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
06-09 17:15:46.104  4542  9522 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
06-09 17:15:46.104  4542  9522 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
06-09 17:15:46.104  4542  9522 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
06-09 17:15:46.104  4542  9522 E         : 	... 9 more
06-09 17:15:46.104  4542  9522 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
06-09 17:15:46.104  4542  9522 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
06-09 17:15:46.104  4542  9522 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
06-09 17:15:46.104  4542  9522 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
06-09 17:15:46.104  4542  9522 E         : 	... 24 more
06-09 17:15:46.104  4542  9522 E         : 
06-09 17:15:46.104  5001  5100 D RegistrationManager: handleMessage(): 5
,06-09 17:15:46.104  3503  4403 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.114  5001  5100 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
06-09 17:15:46.114  5001  5100 D PdnController: isPdnUp  [false] networktype [11]
06-09 17:15:46.114  5001  5100 D RegistrationManager: setEPDGIPSecConnected [false]
06-09 17:15:46.114  5001  5100 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [false] IPAddresses [[]] DNSAddresses [[]] 
06-09 17:15:46.114  5001  5100 D RegistrationManager: isEPDGAvailable [false]
06-09 17:15:46.114  5001  5100 D CoreController: setState [DEREGISTERED]
06-09 17:15:46.114  3503  3524 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.114  6677  6677 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1060/IIllllIIlIIllIIIIlll)] WiFi network Connected : false
06-09 17:15:46.114  4420  4420 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
06-09 17:15:46.124  9370  9370 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
06-09 17:15:46.124  3503  3854 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
06-09 17:15:46.124  4118  4118 I wpa_supplicant: Blacklist: Clear (all) 
06-09 17:15:46.124  4118  4118 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
06-09 17:15:46.134  3503  3524 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.134  9370  9370 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
06-09 17:15:46.134  4254  4617 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
06-09 17:15:46.144  9370  9370 D BluetoothAdapter: STATE_ON
06-09 17:15:46.144  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-09 17:15:46.144  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:46.144  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:46.144  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-09 17:15:46.144  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-09 17:15:46.144  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-09 17:15:46.144  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
06-09 17:15:46.144  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-09 17:15:46.144  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-09 17:15:46.144  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:15:46.144  4254  4254 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
06-09 17:15:46.144  9370  9370 D BluetoothAdapter: STATE_ON
,06-09 17:15:46.154  3503  3588 D TelephonyManager: getDataEnabled: retVal=true
,06-09 17:15:46.154  9370  9370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,06-09 17:15:46.154  3503  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{996cf32 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:46.164  9370  9451 D BluetoothAdapter: STATE_ON
,06-09 17:15:46.164  4953  4969 D A2dpStateMachine: getConnectedDevices : size=0
,06-09 17:15:46.164  4953  9518 D BluetoothSocket: bindListen(): myUserId = 0
,06-09 17:15:46.164  4953  9518 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-09 17:15:46.164  3503  4293 D ActivityManager: cleanUpApplicationRecord -- 8778
06-09 17:15:46.174  3154  3609 D Netd    : Iface p2p0 link up
,06-09 17:15:46.174  5001  5016 D PdnController: Interface Changed p2p0 link up
,06-09 17:15:46.174  9370  9451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-09 17:15:46.174  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:46.174  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:46.174  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-09 17:15:46.174  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-09 17:15:46.174  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-09 17:15:46.174  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
06-09 17:15:46.174  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-09 17:15:46.174  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-09 17:15:46.174  3503  4293 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.aodservice, Auto Run ON
,06-09 17:15:46.174  3503  3596 D Tethering: interfaceLinkStateChanged p2p0, true
06-09 17:15:46.174  3503  3596 D Tethering: interfaceStatusChanged p2p0, true
,06-09 17:15:46.174  9370  9451 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-09 17:15:46.174  9370  9433 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:46.174  4953  4953 D BluetoothSocket: bindListen(): myUserId = 0
06-09 17:15:46.174  4953  4953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-09 17:15:46.184  3503  3848 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-09 17:15:46.184  3503  3848 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-09 17:15:46.184  3503  3848 D WifiService: setWifiEnabled: true pid=9370, uid=10074
,06-09 17:15:46.194  7033  7232 I SQLiteDatabase: can't enable WAL for memory databases.
,06-09 17:15:46.194  3503  4412 I ActivityManager: Killing 8463:com.google.android.talk/u0a112 (adj 15): DHA:empty #33
,06-09 17:15:46.194  5001  5100 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
06-09 17:15:46.194  5001  5100 D RegistrationManager: getNetworkType [0]
06-09 17:15:46.194  5001  5100 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [false] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
06-09 17:15:46.204  5001  5100 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,06-09 17:15:46.204  5001  5100 D CoreStackAdaptor2: ipList =  Null
06-09 17:15:46.204  5001  5100 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
06-09 17:15:46.204  5001  5100 D RegistrationManager: isPreconditionProperToGoOn
06-09 17:15:46.204  5001  5100 D RegistrationManager: isDeviceShutdown [false]
06-09 17:15:46.204  5001  5100 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
06-09 17:15:46.204  5001  5100 D RegistrationManager: isDmVoLTEUpdated [false]
,06-09 17:15:46.204  3503  3503 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@cff2600
06-09 17:15:46.204  3503  3503 D BluetoothHeadset: registerMessageListener
06-09 17:15:46.204  5001  5100 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
06-09 17:15:46.204  5001  5100 D RegistrationManager: tryRegister : Not all preconditions are met!
,06-09 17:15:46.204  3503  3854 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-09 17:15:46.204  7033  7232 I SQLiteDatabase: can't enable WAL for memory databases.
,06-09 17:15:46.214  4118  4118 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,06-09 17:15:46.214  4118  4118 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,06-09 17:15:46.214  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:15:46.214  3933  3933 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-09 17:15:46.214  3933  3933 I HotspotTile: Provider is not defined returning false
,06-09 17:15:46.214  3933  3933 D HotspotTile: onReceive : 0, 0
,06-09 17:15:46.224  3933  3933 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
06-09 17:15:46.224  3154  3609 D Netd    : Iface wlan0 link up
,06-09 17:15:46.224  3503  4415 D ActivityManager: cleanUpApplicationRecord -- 8463
,06-09 17:15:46.224  9506  9506 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package com.sec.android.provider.badge
,06-09 17:15:46.224  5001  5016 D PdnController: Interface Changed wlan0 link up
,06-09 17:15:46.234  3503  3596 D Tethering: interfaceLinkStateChanged wlan0, true
,06-09 17:15:46.234  3503  4415 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
06-09 17:15:46.234  3503  3596 D Tethering: interfaceStatusChanged wlan0, true
,06-09 17:15:46.234  4254  4266 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@8309b5, selection=nullselectionArgs=null, sort=name ASC
,06-09 17:15:46.244  3503  4403 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:15:46.244  9506  9506 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
06-09 17:15:46.244  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:46.244  9506  9506 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:46.244  3503  3848 W WifiService: Failed getting userId using ActivityManagerNative
06-09 17:15:46.244  3503  3848 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:46.244  3503  3848 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-09 17:15:46.244  3503  3848 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-09 17:15:46.244  3503  3848 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-09 17:15:46.244  3503  3848 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-09 17:15:46.244  3503  3848 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
06-09 17:15:46.244  3503  3848 W ActivityManager: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:46.244  4254  4266 D TelephonyProvider: query: match = 5
06-09 17:15:46.244  3503  3848 D SettingsProvider: isChangeAllowed() : name = wifi_on
06-09 17:15:46.244  3503  3848 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-09 17:15:46.244  4254  4266 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
06-09 17:15:46.244  4254  4266 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,06-09 17:15:46.244  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{a375e39: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:46.254  3503  3857 D WifiStateMachine: setFccChannel: channel = -1
,06-09 17:15:46.254  3503  3857 D WifiController: [FCC]setFccChannel() is called !!!
06-09 17:15:46.254  3503  3857 D WifiStateMachine: setFccChannel: channel = -1
06-09 17:15:46.254  3503  3857 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
06-09 17:15:46.254  3503  3857 D SecContentProvider: insert(), uri = 2
,06-09 17:15:46.254  3503  3854 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,06-09 17:15:46.254  3503  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,06-09 17:15:46.254  4953  9518 D BluetoothSdpJni: sdpCreateSapsRecordNative:
06-09 17:15:46.254  4953  9518 D BluetoothSdpJni: SDP Create record success - handle: 0
,06-09 17:15:46.264  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:46.264  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{15eac7e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8118759 6368:com.enhance.gameservice/u0a106}
06-09 17:15:46.264  9506  9506 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:46.264  4953  5382 D HeadsetService: registerMessageListener
06-09 17:15:46.264  3503  3854 D WifiBigDataLog: init : 
,06-09 17:15:46.264  4953  5382 D HeadsetService: registerMessageListener
06-09 17:15:46.274  3503  3503 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
06-09 17:15:46.274  3503  3503 I Telecom : BluetoothManager : register MessageListener
06-09 17:15:46.274  3503  3503 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.274  3503  3503 D Tethering: Tethering got CONNECTIVITY_ACTION
06-09 17:15:46.274  3503  3503 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
06-09 17:15:46.274  3503  3601 D Tethering: MasterInitialState.processMessage what=3
06-09 17:15:46.274  3503  3503 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.274  4953  9461 D HeadsetStateMachine: Disconnected process message: 70, size: 0
06-09 17:15:46.274  3503  3503 I CLocInfoService: CLoinfo wifi false
06-09 17:15:46.274  4953  9461 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@ba89076
06-09 17:15:46.274  3503  3503 V MARsPolicyManager: DataConnection: false
06-09 17:15:46.274  3503  3503 I WifiTrafficPoller: evaluateTrafficStatsPolling
06-09 17:15:46.274  3503  3503 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
06-09 17:15:46.274  3503  3503 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
06-09 17:15:46.274  3503  4193 V AlarmManager:  remove PendingIntent] PendingIntent{95129bd: PendingIntentRecord{7748bb2 android broadcastIntent}}
06-09 17:15:46.274  3503  3503 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
06-09 17:15:46.274  3503  3503 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
06-09 17:15:46.274  3503  3861 I WifiHs20Service: Message received 5007
,06-09 17:15:46.274  3503  3503 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
06-09 17:15:46.274  3503  3503 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,06-09 17:15:46.274  3503  3861 I WifiHs20Service: Message received 5011
06-09 17:15:46.274  3503  4192 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:46.274  3503  4192 W SLocation: No Active Data Connection
06-09 17:15:46.274  9506  9506 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
,06-09 17:15:46.274  3503  3503 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,06-09 17:15:46.274  4571  9526 D MdnsClient: Multicast lock held. Releasing
06-09 17:15:46.274  3503  9527 I ApplicationPolicy: updateDataUsageMap
06-09 17:15:46.284  3503  4414 V AlarmManager:  remove PendingIntent] PendingIntent{55205df: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:46.284  3503  3588 E GpsLocationProvider: No APN found to select.
,06-09 17:15:46.284  9506  9506 D BadgeProvider: onCreate
,06-09 17:15:46.284  9506  9506 D BadgeProvider: DatabaseHelper
,06-09 17:15:46.284  3503  3865 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,06-09 17:15:46.284  4254  5421 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,06-09 17:15:46.284  4254  5421 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,06-09 17:15:46.284  3503  3503 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
06-09 17:15:46.284  3503  3503 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,06-09 17:15:46.294  3503  3865 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,06-09 17:15:46.294  3503  3865 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,06-09 17:15:46.294  4254  4266 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
06-09 17:15:46.294  4254  4266 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,06-09 17:15:46.294  3503  3865 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,06-09 17:15:46.334  4953  4953 D BluetoothSocket: bindListen(): myUserId = 0
06-09 17:15:46.334  4953  4953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-09 17:15:46.344  4118  4118 I wpa_supplicant: Blacklist: Clear (all) 
06-09 17:15:46.344  4118  4118 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,06-09 17:15:46.344  9506  9506 D InjectionManager: InjectionManager
06-09 17:15:46.344  9506  9506 D InjectionManager: fillFeatureStoreMap com.sec.android.provider.badge
,06-09 17:15:46.344  9506  9506 I InjectionManager: Constructor com.sec.android.provider.badge, Feature store :{}
06-09 17:15:46.344  9506  9506 I InjectionManager: featureStore :{}
,06-09 17:15:46.354  3503  4408 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3503  pkgName : BADGE_UPDATE@CPU_MIN@1
,06-09 17:15:46.364  9529  9529 E Zygote  : v2
06-09 17:15:46.364  9529  9529 I libpersona: KNOX_SDCARD checking this for 10112
06-09 17:15:46.364  9529  9529 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:46.364  9529  9529 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:15:46.364  9529  9529 E Zygote  : accessInfo : 0
,06-09 17:15:46.364  9529  9529 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
06-09 17:15:46.364  3503  3592 I ActivityManager: Start proc 9529:com.google.android.talk/u0a112 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
06-09 17:15:46.364  3503  3588 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,06-09 17:15:46.364  4953  4953 D ObexServerSockets: Succeed to create listening sockets 
,06-09 17:15:46.364  4953  4953 D ObexServerSockets: startAccept()
,06-09 17:15:46.364  4953  9534 D ObexServerSockets: Accepting socket connection for masId0
,06-09 17:15:46.364  4953  9536 D ObexServerSockets: Accepting socket connection for masId0
06-09 17:15:46.364  9506  9517 D BaseReflect: null getOwnClass TEST
06-09 17:15:46.364  9506  9517 D MethodReflector: android.content.ContentResolver getClass TEST
,06-09 17:15:46.364  9506  9517 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
06-09 17:15:46.364  9506  9517 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,06-09 17:15:46.374  4953  4953 D BluetoothMapMasInstance: set MAP SDP message type : 1
06-09 17:15:46.374  4953  4953 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
06-09 17:15:46.374  4953  4953 D BluetoothSdpJni: SDP Create record success - handle: 1
,06-09 17:15:46.384  3503  6040 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:46.384  9529  9529 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:46.384  9529  9529 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:46.394  3154  3609 D Netd    : Iface wlan0 link up
06-09 17:15:46.394  3154  3609 D Netd    : Iface wlan0 link up
,06-09 17:15:46.394  5001  5285 D PdnController: Interface Changed wlan0 link up
,06-09 17:15:46.394  3503  3596 D Tethering: interfaceLinkStateChanged wlan0, true
06-09 17:15:46.394  3503  3596 D Tethering: interfaceStatusChanged wlan0, true
06-09 17:15:46.394  5001  5013 D PdnController: Interface Changed wlan0 link up
,06-09 17:15:46.394  3503  3596 D Tethering: interfaceLinkStateChanged wlan0, true
06-09 17:15:46.394  3503  3596 D Tethering: interfaceStatusChanged wlan0, true
,06-09 17:15:46.394  3154  3609 D Netd    : Iface p2p0 link down
,06-09 17:15:46.394  5001  5016 D PdnController: Interface Changed p2p0 link down
06-09 17:15:46.394  3503  3596 D Tethering: interfaceLinkStateChanged p2p0, false
06-09 17:15:46.394  3503  3596 D Tethering: interfaceStatusChanged p2p0, false
,06-09 17:15:46.424  3503  3592 D ActivityManager:  getDeferredInfo final delay 300
,06-09 17:15:46.424  9506  9517 D MethodReflector: notifyChange is called
,06-09 17:15:46.424  4267  4267 D Launcher.Model: reloadBadges entered.
06-09 17:15:46.424  4267  4267 D Launcher.Model: reloadBadges entered.
,06-09 17:15:46.424  9506  9517 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
06-09 17:15:46.424  9506  9517 D BadgeProvider: sendNotify, [notify] : null
,06-09 17:15:46.434  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{b30a22c: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:46.434  9506  9517 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
06-09 17:15:46.434  9506  9517 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
06-09 17:15:46.434  9506  9517 D BadgeProvider: update, [uri.query] : null
06-09 17:15:46.434  9506  9517 D BadgeProvider: update, [BadgeCount] : badgecount=0
06-09 17:15:46.434  9506  9517 D BadgeProvider: update, [UpdateCount] : 1
,06-09 17:15:46.434  3503  4293 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f26a4f5 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{435128a 9529:com.google.android.talk/u0a112}
,06-09 17:15:46.454  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{6fb20fb: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:46.454  9506  9517 D BadgeProvider: query, [selection] : null
,06-09 17:15:46.454  9529  9529 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,06-09 17:15:46.464  3503  4403 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:15:46.464  9529  9529 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:46.464  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{a1bb518: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:46.464  4267  4332 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
06-09 17:15:46.464  4267  4332 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
06-09 17:15:46.464  4267  4332 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
06-09 17:15:46.464  4267  4332 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
06-09 17:15:46.464  4267  4332 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
06-09 17:15:46.464  4267  4332 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
06-09 17:15:46.464  4267  4332 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
06-09 17:15:46.464  4267  4332 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,06-09 17:15:46.464  9529  9529 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:46.464  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{7899b71: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:46.474  9529  9529 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:46.484  9529  9529 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
06-09 17:15:46.484  9506  9517 D BadgeProvider: query, [selection] : null
,06-09 17:15:46.494  9545  9545 E Zygote  : v2
06-09 17:15:46.494  9545  9545 I libpersona: KNOX_SDCARD checking this for 10049
06-09 17:15:46.494  9545  9545 E Zygote  : isSdpEnabledProcess - SDP enabled
06-09 17:15:46.494  9545  9545 I libpersona: KNOX_SDCARD not a persona
06-09 17:15:46.494  9545  9545 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-09 17:15:46.494  3503  3525 I ActivityManager: Start proc 9545:com.samsung.android.email.provider:service/u0a49 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
06-09 17:15:46.494  9545  9545 E Zygote  : accessInfo : 64
06-09 17:15:46.494  9545  9545 E Zygote  : isSdpEnabledProcess - SDP enabled
06-09 17:15:46.494  9545  9545 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
06-09 17:15:46.494  9545  9545 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,06-09 17:15:46.494  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{d59cd56: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:46.494  4267  4332 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
06-09 17:15:46.494  4267  4332 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
06-09 17:15:46.494  4267  4332 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
06-09 17:15:46.494  4267  4332 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
06-09 17:15:46.494  4267  4332 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
,06-09 17:15:46.494  4267  4332 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
06-09 17:15:46.494  4267  4332 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
06-09 17:15:46.494  4267  4332 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,06-09 17:15:46.504  3503  4414 V AlarmManager:  remove PendingIntent] PendingIntent{250d1d7: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:46.504  9529  9529 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,06-09 17:15:46.504  9545  9545 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:46.504  9545  9545 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:46.524  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{d4b7dad: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:46.524  3503  4293 V AlarmManager:  remove PendingIntent] PendingIntent{a3d68e2: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:46.524  9545  9545 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,06-09 17:15:46.524  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{2e6b473: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:46.524  3503  4413 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:15:46.524  9545  9545 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:46.534  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{b280f30: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
06-09 17:15:46.534  9545  9545 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:46.534  3503  4293 V AlarmManager:  remove PendingIntent] PendingIntent{3cf47a9: PendingIntentRecord{9c58d9 com.android.bluetooth broadcastIntent}}
,06-09 17:15:46.534  9545  9545 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:46.544  9545  9545 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,06-09 17:15:46.544  4953  9558 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,06-09 17:15:46.544  4953  9558 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,06-09 17:15:46.584  9545  9545 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,06-09 17:15:46.584  9529  9529 I Babel_telephony: TeleModule.onApplicationCreate
06-09 17:15:46.584  9545  9545 I QBNRClientHelper: init SyncClientHelper : Email
,06-09 17:15:46.604  9529  9567 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
06-09 17:15:46.604  9529  9567 I Babel_SMS: MmsConfig.loadMmsSettings
,06-09 17:15:46.604  3503  4413 D RCPManagerService: exchangeData() failure , invalid userId
,06-09 17:15:46.604  9545  9545 D InjectionManager: InjectionManager
06-09 17:15:46.604  9545  9545 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,06-09 17:15:46.604  9545  9545 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
06-09 17:15:46.604  9545  9545 I InjectionManager: featureStore :{}
,06-09 17:15:46.604  9529  9567 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
06-09 17:15:46.604  9529  9567 I Babel_SMS: MmsConfig.loadFromDatabase
,06-09 17:15:46.614  9529  9529 I Babel_Crash: Startup - clean
,06-09 17:15:46.614  9529  9567 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
06-09 17:15:46.614  9529  9567 I Babel_SMS: MmsConfig.loadFromResources
06-09 17:15:46.614  9529  9567 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
06-09 17:15:46.614  9529  9567 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,06-09 17:15:46.614  3503  3524 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10112
,06-09 17:15:46.624  3503  4293 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10112
,06-09 17:15:46.624  3503  4403 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10112
,06-09 17:15:46.634  3503  3981 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10112
,06-09 17:15:46.634  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.634  3503  3848 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10112
06-09 17:15:46.634  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.634  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.634  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.634  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.634  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.634  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.634  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.634  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.644  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.644  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.644  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
06-09 17:15:46.644  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.644  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.644  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true,]
06-09 17:15:46.644  9529  9529 I Babel_Prime: startMemoryMonitor
06-09 17:15:46.644  9529  9529 I Babel_Prime: isMemoryEnabled=false
06-09 17:15:46.644  9529  9529 I Babel_Prime: isTimerEnabled=true
06-09 17:15:46.654  9529  9529 D InjectionManager: InjectionManager
06-09 17:15:46.654  9529  9529 D InjectionManager: fillFeatureStoreMap com.google.android.talk
06-09 17:15:46.664  9529  9529 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
06-09 17:15:46.664  9529  9529 I InjectionManager: featureStore :{}
06-09 17:15:46.664  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81e3806 9370:com.thaliproject.thalitest/u0a74}
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.664  3503  3525 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.674  3503  4845 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{398d68e 3503:system/1000}
,06-09 17:15:46.684  3503  3503 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7df235 4571:com.google.android.gms/u0a19}
06-09 17:15:46.684  4571  4571 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
06-09 17:15:46.684  4571  5591 I iu.UploadsManager: num queued entries: 0
06-09 17:15:46.684  4571  5591 I iu.UploadsManager: num updated entries: 0
06-09 17:15:46.684  4571  5591 I iu.SyncManager: NEXT; no task
06-09 17:15:46.694  3503  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7df235 4571:com.google.android.gms/u0a19}
06-09 17:15:46.704  9529  9529 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
06-09 17:15:46.704  3503  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{270f4ef 4226:com.google.android.gms.persistent/u0a19}
06-09 17:15:46.704  9529  9529 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
06-09 17:15:46.704  9529  9529 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:15:46.704  9529  9529 I InjectionManager: Inside getClassLibPath caller 
06-09 17:15:46.714  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{255ce92 8813:com.osp.app.signin/u0a41}
06-09 17:15:46.714  8813  8813 I SA      : [DM] init START
06-09 17:15:46.714  8813  8813 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
06-09 17:15:46.714  8813  8813 I SA      : [DM] This device is not a Vodafone
,06-09 17:15:46.724  9529  9529 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: Failure getting entry for 0x7f0a0002 (t=9 e=2) (error -75)
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  3503  3592 D ActivityManager:  getDeferredInfo final delay 300
,06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: Failure getting entry for 0x7f0a0005 (t=9 e=5) (error -75)
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-09 17:15:46.724  8813  8813 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-09 17:15:46.724  8813  8813 I SA      : support phone number id : true
,06-09 17:15:46.724  8813  8813 I SA      : [DM] Supports Ref Jpn : true
06-09 17:15:46.724  8813  8813 I SA      : [DM] init END
06-09 17:15:46.724  8813  8813 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = MMB29K M = SM-G930F OKLEFT false DIS MMB29K.G930FXXU1BPJG PSS = 5.059173621445858  ]
,06-09 17:15:46.734  8813  8813 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
06-09 17:15:46.734  8813  8813 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,06-09 17:15:46.734  8813  8813 I SA      : [SLFUCHKMGR] constructor called
,06-09 17:15:46.734  8813  8813 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
06-09 17:15:46.734  8813  8813 I SA      : [OR] == isSIMCardReady false ==
,06-09 17:15:46.734  8813  8813 I SA      : [SCU] == networkStateCheck == false
06-09 17:15:46.734  8813  8813 I SA      : [OR] onReceive END
,06-09 17:15:46.744  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a65a063 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8118759 6368:com.enhance.gameservice/u0a106}
,06-09 17:15:46.754  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3b5a460 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81e3806 9370:com.thaliproject.thalitest/u0a74}
,06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:46.754  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:46.754  9370  9451 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-09 17:15:46.754  3503  4403 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-09 17:15:46.754  3503  4403 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-09 17:15:46.754  3503  4403 D WifiService: setWifiEnabled: true pid=9370, uid=10074
06-09 17:15:46.754  3503  4403 W WifiService: Failed getting userId using ActivityManagerNative
06-09 17:15:46.754  3503  4403 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:46.754  3503  4403 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-09 17:15:46.754  3503  4403 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-09 17:15:46.754  3503  4403 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-09 17:15:46.754  3503  4403 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-09 17:15:46.754  3503  4403 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
06-09 17:15:46.754  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eac6d19 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
06-09 17:15:46.754  3503  4403 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-09 17:15:46.754  3503  4403 W ActivityManager: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:46.754  3503  3854 D WifiBigDataLog: getJsonFormat() - feature : ONOF
06-09 17:15:46.754  3503  4403 D SettingsProvider: isChangeAllowed() : name = wifi_on
06-09 17:15:46.754  3503  3854 D WifiBigDataLog: init : 
06-09 17:15:46.754  3503  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,06-09 17:15:46.754  3503  3857 D WifiController: [FCC]setFccChannel() is called !!!
06-09 17:15:46.754  3503  3857 D WifiStateMachine: setFccChannel: channel = -1
06-09 17:15:46.754  3503  3857 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,06-09 17:15:46.764  3503  3975 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2fe41de u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:46.774  9529  9529 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,06-09 17:15:46.784  9529  9529 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-09 17:15:46.784  3503  4209 V AlarmManager:  remove PendingIntent] PendingIntent{b289dea: PendingIntentRecord{d64b8db com.google.android.talk startService}}
,06-09 17:15:46.794  9529  9583 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,06-09 17:15:46.934  3154  3609 D Netd    : Iface wlan0 link down
,06-09 17:15:46.934  5001  5016 D PdnController: Interface Changed wlan0 link down
06-09 17:15:46.934  5001  5016 D PdnController: Removed Interface [wlan0] For Network [1]
06-09 17:15:46.934  3503  3596 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:46.944  5001  5016 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
06-09 17:15:46.944  5001  5016 D PdnController: isSuspended [false] networktype [1]
06-09 17:15:46.944  3503  3596 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:46.944  5001  5016 D PdnController: isPdnUp  [false] networktype [1]
,06-09 17:15:46.944  5001  5016 D PdnController: Ignore Notifying Same Result to LocalIP Registrants!
06-09 17:15:46.944  3503  3596 D Tethering: interfaceLinkStateChanged wlan0, false
06-09 17:15:46.944  3503  3596 D Tethering: interfaceStatusChanged wlan0, false
,06-09 17:15:46.994  4118  4118 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,06-09 17:15:47.024  3503  3592 D ActivityManager:  getDeferredInfo final delay 300
,06-09 17:15:47.094  3503  3854 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,06-09 17:15:47.094  3503  3503 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,06-09 17:15:47.094  3503  3503 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
06-09 17:15:47.094  3503  3503 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,06-09 17:15:47.104  3503  3503 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
06-09 17:15:47.104  3503  3503 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,06-09 17:15:47.104  3503  3858 D HS20StateMachine: WIFI_STATE_DISABLED
06-09 17:15:47.104  3503  3861 I WifiHs20Service: Message received 5011
06-09 17:15:47.104  3503  3858 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
06-09 17:15:47.104  3503  3858 D HS20StateMachine: enter : DisablingState
06-09 17:15:47.104  3503  3860 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
06-09 17:15:47.104  3503  3858 D HS20StateMachine: enter : DisabledState
,06-09 17:15:47.104  3503  3865 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,06-09 17:15:47.104  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:15:47.104  3503  3503 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,06-09 17:15:47.104  4254  4266 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
06-09 17:15:47.104  4254  4266 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,06-09 17:15:47.104  3933  3933 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-09 17:15:47.104  3503  3865 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
06-09 17:15:47.104  3933  3933 I HotspotTile: Provider is not defined returning false
,06-09 17:15:47.104  3933  3933 D HotspotTile: onReceive : 1, 0
,06-09 17:15:47.114  4226  4916 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-09 17:15:47.114  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:47.114  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8979f78 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81e3806 9370:com.thaliproject.thalitest/u0a74}
,06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
,06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.114  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:47.264  9370  9451 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-09 17:15:47.264  3503  4279 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-09 17:15:47.264  3503  4279 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-09 17:15:47.264  3503  4279 D WifiService: setWifiEnabled: true pid=9370, uid=10074
06-09 17:15:47.264  3503  4279 W ActivityManager: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,06-09 17:15:47.264  3503  4279 W WifiService: Failed getting userId using ActivityManagerNative
06-09 17:15:47.264  3503  4279 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:47.264  3503  4279 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-09 17:15:47.264  3503  4279 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-09 17:15:47.264  3503  4279 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-09 17:15:47.264  3503  4279 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-09 17:15:47.264  3503  4279 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
06-09 17:15:47.264  3503  4279 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-09 17:15:47.264  3503  4279 D SettingsProvider: isChangeAllowed() : name = wifi_on
06-09 17:15:47.264  3503  3857 D WifiStateMachine: setFccChannel: channel = -1
06-09 17:15:47.264  3503  3857 D WifiController: [FCC]setFccChannel() is called !!!
06-09 17:15:47.264  3503  3857 E WifiController: illegal state found both WifiController and WifiStateMachine
06-09 17:15:47.264  3503  3857 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,06-09 17:15:47.294  3503  3854 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
06-09 17:15:47.294  3503  3854 E WifiHW  : ##################### set firmware type 0 #####################
,06-09 17:15:47.304  3154  3616 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,06-09 17:15:47.304  3154  3616 I WifiHW  : module is semco
06-09 17:15:47.304  3154  3616 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
06-09 17:15:47.304  3154  3616 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
06-09 17:15:47.304  3154  3616 E WifiHW  : TEMP_FAILURE_RETRY complete
06-09 17:15:47.304  3154  3616 D SoftapController: Softap fwReload - Ok
,06-09 17:15:47.304  3154  3616 D CommandListener: Setting iface cfg
06-09 17:15:47.304  3154  3616 D CommandListener: Trying to bring down wlan0
,06-09 17:15:47.304  3154  3616 D CommandListener: Clearing all IP addresses on wlan0
,06-09 17:15:47.304  3503  3854 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,06-09 17:15:47.314  3503  3854 D wifi    : Can not initialize the vendor function pointer table
06-09 17:15:47.314  3503  3854 E WifiNative-HAL: Could not start hal
06-09 17:15:47.314  3503  3854 E WifiStateMachine: Failed to start HAL
,06-09 17:15:47.314  3503  3854 E WifiHW  : supplicant_name : p2p_supplicant
,06-09 17:15:47.324  3503  3592 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:47.344  9585  9585 E Zygote  : v2
06-09 17:15:47.344  9585  9585 I libpersona: KNOX_SDCARD checking this for 1000
06-09 17:15:47.344  9585  9585 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:47.344  9585  9585 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:15:47.344  9585  9585 E Zygote  : accessInfo : 0
,06-09 17:15:47.354  3503  3592 I ActivityManager: Start proc 9585:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,06-09 17:15:47.364  3503  3588 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
,06-09 17:15:47.364  3503  3588 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
06-09 17:15:47.364  3503  3588 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
06-09 17:15:47.364  3503  3588 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,06-09 17:15:47.374  9585  9585 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-09 17:15:47.374  9585  9585 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:47.384  3503  4209 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{15eac7e u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f5a651 9585:com.sec.android.diagmonagent/1000}
,06-09 17:15:47.394  9585  9585 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package com.sec.android.diagmonagent
,06-09 17:15:47.394  3503  3524 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:15:47.394  9585  9585 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:47.394  9585  9585 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:47.394  9585  9585 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:47.404  9585  9585 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,06-09 17:15:47.414  3503  3854 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,06-09 17:15:47.414  3503  3503 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
06-09 17:15:47.414  3503  3503 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,06-09 17:15:47.414  3503  3861 I WifiHs20Service: Message received 5011
,06-09 17:15:47.414  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:15:47.414  3503  3503 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,06-09 17:15:47.414  3503  3865 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,06-09 17:15:47.414  3933  3933 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-09 17:15:47.414  3933  3933 I HotspotTile: Provider is not defined returning false
,06-09 17:15:47.414  3933  3933 D HotspotTile: onReceive : 2, 0
,06-09 17:15:47.424  4254  4594 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
06-09 17:15:47.424  4254  4594 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,06-09 17:15:47.424  3503  3865 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,06-09 17:15:47.424  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:47.424  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9eaaeb6 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81e3806 9370:com.thaliproject.thalitest/u0a74}
,06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:47.424  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:47.434  9585  9585 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,06-09 17:15:47.444  3503  3524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-09 17:15:47.444  3503  3524 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-09 17:15:47.444  3503  3524 D BatteryService: online:4, current avg:-44, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-09 17:15:47.444  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-09 17:15:47.444  3503  3503 I MotionRecognitionService: Plugged
06-09 17:15:47.444  3503  3503 D MotionRecognitionService:   cableConnection= 1
06-09 17:15:47.444  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-09 17:15:47.444  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,06-09 17:15:47.444  3503  3857 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-09 17:15:47.444  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-09 17:15:47.454  3933  3933 D KeyguardUpdateMonitor: handleBatteryUpdate
06-09 17:15:47.454  3933  3933 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-09 17:15:47.454  5001  5001 D CommonServiceConfiguration: getStringValueSetting
,06-09 17:15:47.464  5001  5001 D BatteryMonitor: new battery level: 100
,06-09 17:15:47.464  4953  4953 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-09 17:15:47.464  4953  9461 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-09 17:15:47.474  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-09 17:15:47.474  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-09 17:15:47.474  9584  9584 I FIPS_bssl: FIPS approved mode (1) | 9584 | /system/bin/wpa_supplicant
,06-09 17:15:47.474  9584  9584 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
06-09 17:15:47.474  9584  9584 I wpa_supplicant: Successfully initialized wpa_supplicant
06-09 17:15:47.474  9584  9584 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
,06-09 17:15:47.474  9584  9584 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,06-09 17:15:47.494  9584  9584 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,06-09 17:15:47.494  3015  3015 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9584
06-09 17:15:47.494  3015  3015 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
06-09 17:15:47.494  9584  9584 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-09 17:15:47.494  9584  9584 I wpa_supplicant: ssSupport state is = 1
06-09 17:15:47.494  9584  9584 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
06-09 17:15:47.494  9584  9584 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,06-09 17:15:47.494  3015  3015 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9584
06-09 17:15:47.494  3015  3015 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,06-09 17:15:47.504  9584  9584 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,06-09 17:15:47.514  9585  9585 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,06-09 17:15:47.514  9585  9585 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
06-09 17:15:47.514  9585  9585 D InjectionManager: InjectionManager
06-09 17:15:47.514  9585  9585 D InjectionManager: fillFeatureStoreMap com.sec.android.diagmonagent
,06-09 17:15:47.514  9585  9585 I InjectionManager: Constructor com.sec.android.diagmonagent, Feature store :{}
06-09 17:15:47.514  9585  9585 I InjectionManager: featureStore :{}
,06-09 17:15:47.514  9585  9585 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,06-09 17:15:47.514  9585  9585 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
06-09 17:15:47.514  9585  9585 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
06-09 17:15:47.514  9585  9585 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,06-09 17:15:47.544  3503  3975 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:47.554  9599  9599 E Zygote  : v2
06-09 17:15:47.554  9599  9599 I libpersona: KNOX_SDCARD checking this for 1000
06-09 17:15:47.554  9599  9599 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:47.554  9599  9599 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:15:47.554  9599  9599 E Zygote  : accessInfo : 0
,06-09 17:15:47.564  3503  3975 I ActivityManager: Start proc 9599:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,06-09 17:15:47.564  3503  3975 I ActivityManager: Killing 8800:com.samsung.android.scloud:contentsync/5009 (adj 15): DHA:empty #33
,06-09 17:15:47.574  3503  4209 D ActivityManager: cleanUpApplicationRecord -- 8800
,06-09 17:15:47.574  3503  4209 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,06-09 17:15:47.574  9599  9599 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:47.574  9599  9599 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:47.584  3503  3524 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{15eac7e u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec07b7 9599:com.sec.knox.switcher/1000}
,06-09 17:15:47.584  9599  9599 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package com.sec.knox.switcher
,06-09 17:15:47.584  3503  4403 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:15:47.584  9599  9599 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:47.584  9599  9599 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:47.594  9599  9599 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:47.594  9599  9599 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,06-09 17:15:47.594  9599  9599 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
06-09 17:15:47.594  9599  9599 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,06-09 17:15:47.594  9599  9599 D InjectionManager: InjectionManager
06-09 17:15:47.594  9599  9599 D InjectionManager: fillFeatureStoreMap com.sec.knox.switcher
,06-09 17:15:47.594  9599  9599 I InjectionManager: Constructor com.sec.knox.switcher, Feature store :{}
06-09 17:15:47.594  9599  9599 I InjectionManager: featureStore :{}
,06-09 17:15:47.594  9599  9599 I usagelog: received in receiver
06-09 17:15:47.594  9599  9599 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,06-09 17:15:47.604  9599  9599 I KnoxUsageLogPro: premStatus:2
,06-09 17:15:47.604  9599  9599 I KnoxUsageLogPro: isEulaShown : false
06-09 17:15:47.604  9599  9599 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,06-09 17:15:47.604  3503  3981 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:47.614  9611  9611 E Zygote  : v2
06-09 17:15:47.614  9611  9611 I libpersona: KNOX_SDCARD checking this for 10135
06-09 17:15:47.614  9611  9611 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:47.614  9611  9611 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-09 17:15:47.614  3503  3981 I ActivityManager: Start proc 9611:com.samsung.android.sm.policy/u0a135 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
,06-09 17:15:47.614  9611  9611 E Zygote  : accessInfo : 0
,06-09 17:15:47.614  9611  9611 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
06-09 17:15:47.614  3503  3981 I ActivityManager: Killing 8076:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,06-09 17:15:47.644  3503  4415 D ActivityManager: cleanUpApplicationRecord -- 8076
,06-09 17:15:47.644  3503  4415 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,06-09 17:15:47.644  9611  9611 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:47.644  9611  9611 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:47.654  3503  3848 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{15eac7e u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d633b24 9611:com.samsung.android.sm.policy/u0a135}
,06-09 17:15:47.664  9611  9611 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package com.samsung.android.sm.policy
,06-09 17:15:47.664  3503  4414 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:15:47.664  9611  9611 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:47.664  9611  9611 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:47.664  9611  9611 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:47.674  9611  9611 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm64
,06-09 17:15:47.674  9611  9611 D InjectionManager: InjectionManager
06-09 17:15:47.674  9611  9611 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.policy
,06-09 17:15:47.674  9611  9611 I InjectionManager: Constructor com.samsung.android.sm.policy, Feature store :{}
06-09 17:15:47.674  9611  9611 I InjectionManager: featureStore :{}
,06-09 17:15:47.684  3503  4412 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:47.694  9624  9624 E Zygote  : v2
06-09 17:15:47.694  9624  9624 I libpersona: KNOX_SDCARD checking this for 5005
06-09 17:15:47.694  9624  9624 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-09 17:15:47.694  9624  9624 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:47.694  9624  9624 E Zygote  : accessInfo : 0
06-09 17:15:47.694  9624  9624 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,06-09 17:15:47.704  3503  4412 I ActivityManager: Start proc 9624:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,06-09 17:15:47.704  3503  4412 I ActivityManager: Killing 8831:com.google.android.apps.photos/u0a129 (adj 15): DHA:empty #33
,06-09 17:15:47.724  9624  9624 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:47.724  9624  9624 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:47.734  3503  3848 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{11d568d u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7eb0042 9624:com.samsung.android.app.FileShareClient/5005}
,06-09 17:15:47.734  9624  9624 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,06-09 17:15:47.734  3503  4208 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-09 17:15:47.734  9624  9624 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:47.734  3503  4414 D ActivityManager: cleanUpApplicationRecord -- 8831
06-09 17:15:47.734  3503  4414 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,06-09 17:15:47.734  9624  9624 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:47.744  9624  9624 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:47.744  9624  9624 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,06-09 17:15:47.754  9624  9624 D InjectionManager: InjectionManager
,06-09 17:15:47.754  9624  9624 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
06-09 17:15:47.754  9624  9624 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{}
06-09 17:15:47.754  9624  9624 I InjectionManager: featureStore :{}
,06-09 17:15:47.754  9624  9624 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,06-09 17:15:47.754  9624  9624 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,06-09 17:15:47.764  9370  9451 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-09 17:15:47.774  3503  3848 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-09 17:15:47.774  3503  3848 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-09 17:15:47.774  9624  9624 D FileShare-Client: Outbound.stopDelayTimer - 
,06-09 17:15:47.784  3503  4293 D ActivityManager:  getDeferredInfo final delay 0
06-09 17:15:47.784  3503  3848 D WifiService: setWifiEnabled: true pid=9370, uid=10074
,06-09 17:15:47.794  9636  9636 E Zygote  : v2
06-09 17:15:47.794  9636  9636 I libpersona: KNOX_SDCARD checking this for 5005
06-09 17:15:47.794  9636  9636 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-09 17:15:47.794  9636  9636 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:47.794  9636  9636 E Zygote  : accessInfo : 0
,06-09 17:15:47.794  9636  9636 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
,06-09 17:15:47.794  3503  4293 I ActivityManager: Start proc 9636:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
,06-09 17:15:47.794  3503  4293 I ActivityManager: Killing 8520:com.android.providers.calendar/u0a47 (adj 15): DHA:empty #33
,06-09 17:15:47.804  3503  3848 W ActivityManager: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,06-09 17:15:47.804  3503  3848 W WifiService: Failed getting userId using ActivityManagerNative
06-09 17:15:47.804  3503  3848 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:47.804  3503  3848 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-09 17:15:47.804  3503  3848 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-09 17:15:47.804  3503  3848 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-09 17:15:47.804  3503  3848 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-09 17:15:47.804  3503  3848 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
06-09 17:15:47.804  3503  3848 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-09 17:15:47.804  3503  3848 D SettingsProvider: isChangeAllowed() : name = wifi_on
06-09 17:15:47.804  3503  3857 D WifiStateMachine: setFccChannel: channel = -1
06-09 17:15:47.804  3503  3857 D WifiController: [FCC]setFccChannel() is called !!!
06-09 17:15:47.804  3503  3857 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,06-09 17:15:47.804  9584  9584 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
,06-09 17:15:47.804  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,06-09 17:15:47.814  3503  3525 D ActivityManager: cleanUpApplicationRecord -- 8520
,06-09 17:15:47.824  3503  3525 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,06-09 17:15:47.824  9636  9636 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:47.824  9636  9636 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:47.834  3503  4209 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{11d568d u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e2f6853 9636:com.samsung.android.app.FileShareServer/5005}
,06-09 17:15:47.844  9636  9636 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareServer/AllshareFileShareServer.apk / 1.0 running in com.samsung.android.app.FileShareServer rsrc of package com.samsung.android.app.FileShareServer
,06-09 17:15:47.844  3503  4293 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-09 17:15:47.844  9636  9636 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:47.844  9636  9636 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:15:47.844  9584  9584 I wpa_supplicant: Ctrl_iface: loading system cred
,06-09 17:15:47.844  9584  9584 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,06-09 17:15:47.844  9636  9636 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:47.854  9636  9636 D InjectionManager: InjectionManager
,06-09 17:15:47.854  9636  9636 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareServer
06-09 17:15:47.854  9636  9636 I InjectionManager: Constructor com.samsung.android.app.FileShareServer, Feature store :{}
06-09 17:15:47.854  9636  9636 I InjectionManager: featureStore :{}
,06-09 17:15:47.854  9636  9636 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,06-09 17:15:47.854  9636  9636 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,06-09 17:15:47.854  9636  9636 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,06-09 17:15:47.864  3503  4845 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:47.864  9584  9584 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,06-09 17:15:47.864  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9584
,06-09 17:15:47.864  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
06-09 17:15:47.864  9584  9584 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
06-09 17:15:47.864  9584  9584 I wpa_supplicant: ssSupport state is = 1
06-09 17:15:47.864  9584  9584 I wpa_supplicant: Blacklist: Clear (all) 
,06-09 17:15:47.874  9584  9584 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
,06-09 17:15:47.874  9584  9584 I wpa_supplicant: [getIMSI]: sim_num 0
,06-09 17:15:47.874  9584  9584 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-09 17:15:47.884  9649  9649 E Zygote  : v2
06-09 17:15:47.884  9649  9649 I libpersona: KNOX_SDCARD checking this for 1000
06-09 17:15:47.884  9649  9649 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:47.884  9649  9649 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-09 17:15:47.884  3503  4845 I ActivityManager: Start proc 9649:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
,06-09 17:15:47.884  9649  9649 E Zygote  : accessInfo : 0
,06-09 17:15:47.884  3503  4845 I ActivityManager: Killing 8346:com.google.android.talk:matchstick/u0a112 (adj 15): DHA:empty #33
,06-09 17:15:47.914  9649  9649 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:47.914  9649  9649 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:47.914  3503  3524 D ActivityManager: cleanUpApplicationRecord -- 8346
,06-09 17:15:47.914  3503  3524 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,06-09 17:15:47.924  3503  4208 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f2ae590 9649:com.policydm/1000}
,06-09 17:15:47.934  9649  9649 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package com.policydm
,06-09 17:15:47.934  3503  4408 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:15:47.934  9649  9649 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:47.934  9649  9649 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:47.944  9649  9649 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:47.954  9649  9649 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,06-09 17:15:47.964  9649  9649 I FOTA    : [lIlIIlIIlIlllIIIIlll(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
06-09 17:15:47.964  9649  9649 I FOTA    : [lIlIIlIIlIlllIIIIlll(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,06-09 17:15:47.974  9649  9649 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,06-09 17:15:47.984  9649  9649 I DBG_POLICYDM: [com.policydm.db.XDB(1600/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,06-09 17:15:47.994  9649  9649 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(142/llIIIIlllllIIllIIllI)] try read dbString
,06-09 17:15:48.054  9649  9649 I DBG_POLICYDM: [com.policydm.XDMService(161/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,06-09 17:15:48.054  9649  9649 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(52/<init>)] 
,06-09 17:15:48.054  9649  9649 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:56 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:19 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:25 
,06-09 17:15:48.074  9665  9665 E Zygote  : v2
06-09 17:15:48.074  9665  9665 I libpersona: KNOX_SDCARD checking this for 1000
06-09 17:15:48.074  9665  9665 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-09 17:15:48.074  9665  9665 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:48.074  3503  4414 I ActivityManager: Start proc 9665:com.samsung.aasaservice/1000 for service com.samsung.aasaservice/.AASAService
06-09 17:15:48.074  9665  9665 E Zygote  : accessInfo : 0
,06-09 17:15:48.074  9649  9649 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(28/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,06-09 17:15:48.084  9649  9649 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,06-09 17:15:48.084  9649  9649 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,06-09 17:15:48.084  9649  9649 D InjectionManager: InjectionManager
06-09 17:15:48.084  9649  9649 D InjectionManager: fillFeatureStoreMap com.policydm
,06-09 17:15:48.084  9649  9649 I InjectionManager: Constructor com.policydm, Feature store :{}
06-09 17:15:48.084  9649  9649 I InjectionManager: featureStore :{}
,06-09 17:15:48.094  9665  9665 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:48.094  9665  9665 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:48.104  9649  9649 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,06-09 17:15:48.104  9649  9649 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,06-09 17:15:48.104  9649  9649 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
06-09 17:15:48.104  9665  9665 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package com.samsung.aasaservice
,06-09 17:15:48.104  3503  3524 D ActivityManager:  getDeferredInfo final delay 300
06-09 17:15:48.104  3503  4403 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-09 17:15:48.104  9665  9665 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
06-09 17:15:48.104  3503  3524 I ActivityManager: Killing 8879:com.android.defcontainer/u0a8 (adj 15): DHA:empty #33
,06-09 17:15:48.104  9665  9665 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:48.114  9665  9665 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:48.114  9665  9665 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm64
,06-09 17:15:48.114  9665  9665 D InjectionManager: InjectionManager
06-09 17:15:48.114  9665  9665 D InjectionManager: fillFeatureStoreMap com.samsung.aasaservice
,06-09 17:15:48.114  9665  9665 I InjectionManager: Constructor com.samsung.aasaservice, Feature store :{}
06-09 17:15:48.114  9665  9665 I InjectionManager: featureStore :{}
,06-09 17:15:48.114  9665  9665 D AASAservice: onCreate()
,06-09 17:15:48.124  9649  9649 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(38/onServiceConnected)] AASA: onServiceConnected
06-09 17:15:48.124  3503  4412 I ActivityManager: Killing 8970:com.samsung.android.app.galaxylabs/u0a15 (adj 15): DHA:empty #33
,06-09 17:15:48.124  3503  3975 D ActivityManager: cleanUpApplicationRecord -- 8879
,06-09 17:15:48.134  3503  3975 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,06-09 17:15:48.144  3503  4208 D ActivityManager: cleanUpApplicationRecord -- 8970
06-09 17:15:48.144  3503  4208 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.galaxylabs, Auto Run ON
,06-09 17:15:48.304  9370  9451 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-09 17:15:48.314  3503  4845 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-09 17:15:48.314  3503  4845 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-09 17:15:48.314  3503  4845 D WifiService: setWifiEnabled: true pid=9370, uid=10074
06-09 17:15:48.314  3503  4845 W WifiService: Failed getting userId using ActivityManagerNative
06-09 17:15:48.314  3503  4845 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:48.314  3503  4845 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-09 17:15:48.314  3503  4845 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-09 17:15:48.314  3503  4845 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-09 17:15:48.314  3503  4845 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-09 17:15:48.314  3503  4845 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
06-09 17:15:48.314  3503  4845 W ActivityManager: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:48.314  3503  4845 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
06-09 17:15:48.314  3503  4845 D SettingsProvider: isChangeAllowed() : name = wifi_on
,06-09 17:15:48.314  3503  3857 D WifiController: [FCC]setFccChannel() is called !!!
06-09 17:15:48.314  3503  3857 D WifiStateMachine: setFccChannel: channel = -1
06-09 17:15:48.314  3503  3857 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,06-09 17:15:48.364  3503  4209 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3503  tag : BADGE_UPDATE@CPU_MIN@1
,06-09 17:15:48.374  3503  3588 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
06-09 17:15:48.374  3503  3588 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
06-09 17:15:48.374  3503  3588 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,06-09 17:15:48.404  3503  3592 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:48.414  3503  6040 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:48.424  3503  3592 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f2ae590 9649:com.policydm/1000}
,06-09 17:15:48.424  9649  9649 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,06-09 17:15:48.424  3503  4415 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:48.434  3503  4415 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7cec27 6677:com.wssyncmldm/1000}
,06-09 17:15:48.444  3503  4415 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:48.454  3503  4415 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{269b2ff 6815:com.samsung.fresco.logging/5015}
,06-09 17:15:48.454  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:48.454  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:48.464  3503  4415 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:48.474  3503  4415 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a708799 7292:com.sec.spp.push/u0a39}
,06-09 17:15:48.474  7292  7292 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,06-09 17:15:48.474  7292  7292 E SPPClientService: [SystemStateMoniter] Current Time : 304683
,06-09 17:15:48.474  7292  7292 E SPPClientService: [SystemStateMoniter] No Connect : true
,06-09 17:15:48.484  3503  4415 D ActivityManager:  getDeferredInfo final delay 300
,06-09 17:15:48.484  7292  9678 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,06-09 17:15:48.704  3154  3609 D Netd    : Iface wlan0 link up
,06-09 17:15:48.704  3154  3609 D Netd    : Iface wlan0 link up
06-09 17:15:48.704  3154  3609 D Netd    : Iface wlan0 link up
06-09 17:15:48.704  5001  5013 D PdnController: Interface Changed wlan0 link up
,06-09 17:15:48.704  3503  3596 D Tethering: interfaceLinkStateChanged wlan0, true
06-09 17:15:48.704  3503  3596 D Tethering: interfaceStatusChanged wlan0, true
,06-09 17:15:48.704  5001  5016 D PdnController: Interface Changed wlan0 link up
,06-09 17:15:48.704  3503  3596 D Tethering: interfaceLinkStateChanged wlan0, true
06-09 17:15:48.704  3503  3596 D Tethering: interfaceStatusChanged wlan0, true
,06-09 17:15:48.714  5001  5285 D PdnController: Interface Changed wlan0 link up
,06-09 17:15:48.714  3503  3596 D Tethering: interfaceLinkStateChanged wlan0, true
06-09 17:15:48.714  3503  3596 D Tethering: interfaceStatusChanged wlan0, true
,06-09 17:15:48.814  9584  9584 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
06-09 17:15:48.814  9584  9584 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,06-09 17:15:48.814  9370  9451 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-09 17:15:48.824  3503  3848 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-09 17:15:48.824  3503  3848 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-09 17:15:48.824  3503  3848 D WifiService: setWifiEnabled: true pid=9370, uid=10074
,06-09 17:15:48.854  9584  9584 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,06-09 17:15:48.854  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9584
06-09 17:15:48.854  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,06-09 17:15:48.854  9584  9584 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
06-09 17:15:48.854  9584  9584 I wpa_supplicant: ssSupport state is = 1
,06-09 17:15:48.854  9584  9584 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-09 17:15:48.854  9584  9584 E wpa_supplicant: nl80211: Could not configure driver mode
06-09 17:15:48.854  9584  9584 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,06-09 17:15:48.854  9584  9584 E wpa_supplicant: p2p0: Failed to initialize driver interface
06-09 17:15:48.854  9584  9584 I wpa_supplicant: Blacklist: Clear (all) 
06-09 17:15:48.854  9584  9584 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,06-09 17:15:48.854  9584  9584 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,06-09 17:15:48.874  3503  3592 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:48.884  3503  3592 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a16f41 4820:android.process.media/u0a48}
,06-09 17:15:48.884  3503  3848 W ActivityManager: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:48.884  3503  3848 W WifiService: Failed getting userId using ActivityManagerNative
06-09 17:15:48.884  3503  3848 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:48.884  3503  3848 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-09 17:15:48.884  3503  3848 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-09 17:15:48.884  3503  3848 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-09 17:15:48.884  3503  3848 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-09 17:15:48.884  3503  3848 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
06-09 17:15:48.884  3503  3848 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,06-09 17:15:48.884  3503  3848 D SettingsProvider: isChangeAllowed() : name = wifi_on
06-09 17:15:48.884  3503  3857 D WifiStateMachine: setFccChannel: channel = -1
06-09 17:15:48.884  3503  3857 D WifiController: [FCC]setFccChannel() is called !!!
06-09 17:15:48.884  9584  9584 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,06-09 17:15:48.884  3503  3857 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
06-09 17:15:48.884  4820  4820 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
06-09 17:15:48.884  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9584
06-09 17:15:48.884  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
06-09 17:15:48.884  9584  9584 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
06-09 17:15:48.884  9584  9584 I wpa_supplicant: ssSupport state is = 1
,06-09 17:15:48.884  9584  9584 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-09 17:15:48.894  3503  3981 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:48.894  9584  9584 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,06-09 17:15:48.904  3503  3854 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,06-09 17:15:48.904  3503  3854 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
06-09 17:15:48.904  3503  3854 E WifiStateMachine: Deffering msg in Supplicant Starting State131156
,06-09 17:15:48.904  3503  3854 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,06-09 17:15:48.904  3503  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,06-09 17:15:48.904  9684  9684 E Zygote  : v2
,06-09 17:15:48.904  9684  9684 I libpersona: KNOX_SDCARD checking this for 1000
06-09 17:15:48.904  9684  9684 I libpersona: KNOX_SDCARD not a persona
06-09 17:15:48.914  9684  9684 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:15:48.914  9684  9684 E Zygote  : accessInfo : 0
,06-09 17:15:48.914  3503  3981 I ActivityManager: Start proc 9684:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
,06-09 17:15:48.924  3503  3854 D WifiBigDataLog: init : 
,06-09 17:15:48.924  3503  3854 E WifiStateMachine: Deffering msg in Supplicant Starting State131083
,06-09 17:15:48.924  3503  3854 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,06-09 17:15:48.934  3503  3854 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,06-09 17:15:48.934  3503  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,06-09 17:15:48.934  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b03ca45 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:48.934  3503  3854 D WifiBigDataLog: init : 
,06-09 17:15:48.934  3503  3854 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,06-09 17:15:48.934  3503  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,06-09 17:15:48.944  3503  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e9c559a u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:48.944  9684  9684 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:48.944  9684  9684 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:48.954  3503  3854 D WifiBigDataLog: init : 
,06-09 17:15:48.954  3503  3854 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,06-09 17:15:48.954  3503  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,06-09 17:15:48.964  3503  4279 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9c18ecb 9684:com.samsung.android.SettingsReceiver/1000}
,06-09 17:15:48.974  3503  3854 D WifiBigDataLog: init : 
,06-09 17:15:48.974  3503  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cedd6a8 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
06-09 17:15:48.974  9684  9684 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
,06-09 17:15:48.974  3503  4408 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:15:48.974  3503  3854 D WifiNative-wlan0: callSECApiBoolean - ID [301]
06-09 17:15:48.974  9684  9684 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:48.974  9584  9584 I wpa_supplicant: HOTSPOT20_ENABLE called ON
,06-09 17:15:48.974  9584  9584 I wpa_supplicant: Blacklist: Clear (all) 
,06-09 17:15:48.974  9684  9684 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:48.984  9584  9584 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,06-09 17:15:48.984  9684  9684 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:48.994  3503  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{69bc5c1 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:48.994  9584  9584 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,06-09 17:15:48.994  9684  9684 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
,06-09 17:15:48.994  3503  3854 D WifiNative-wlan0: callSECApiInt - ID [210]
06-09 17:15:49.004  9684  9684 D InjectionManager: InjectionManager
06-09 17:15:49.004  9684  9684 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
06-09 17:15:49.004  3503  3503 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
06-09 17:15:49.004  3503  3503 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
06-09 17:15:49.004  3503  3858 D HS20StateMachine: WIFI_STATE_ENABLED
06-09 17:15:49.004  3503  3858 D HS20StateMachine: reloadCredentialsToSupplicant
06-09 17:15:49.004  9684  9684 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
06-09 17:15:49.004  9684  9684 I InjectionManager: featureStore :{}
06-09 17:15:49.004  3503  3858 D HotspotDBHandler: getCredentialIds
06-09 17:15:49.004  3503  3861 I WifiHs20Service: Message received 5011
,06-09 17:15:49.004  3503  3865 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,06-09 17:15:49.004  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:15:49.004  9684  9684 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.android.settings
,06-09 17:15:49.014  3933  3933 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,06-09 17:15:49.014  3503  3503 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
06-09 17:15:49.014  4254  4616 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,06-09 17:15:49.014  4254  4616 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
06-09 17:15:49.014  3503  4192 W SLocation: No Active Data Connection
06-09 17:15:49.014  3933  3933 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-09 17:15:49.014  3933  3933 I HotspotTile: Provider is not defined returning false
,06-09 17:15:49.014  3503  3865 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,06-09 17:15:49.014  3933  3933 D HotspotTile: onReceive : 3, 0
,06-09 17:15:49.014  9684  9684 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:49.034  9370  9370 D BluetoothAdapter: STATE_ON
,06-09 17:15:49.034  3503  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ada3166 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81e3806 9370:com.thaliproject.thalitest/u0a74}
,06-09 17:15:49.034  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-09 17:15:49.034  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:49.034  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:49.034  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-09 17:15:49.034  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-09 17:15:49.034  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-09 17:15:49.034  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
06-09 17:15:49.034  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-09 17:15:49.034  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-09 17:15:49.034  9370  9370 D BluetoothAdapter: STATE_ON
,06-09 17:15:49.044  9370  9370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,06-09 17:15:49.044  9584  9584 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:49.044  3503  4845 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:49.044  3503  3854 D WifiConfigStore: Loading config and enabling all networks 
,06-09 17:15:49.054  9697  9697 E Zygote  : v2
06-09 17:15:49.054  9697  9697 I libpersona: KNOX_SDCARD checking this for 10114
06-09 17:15:49.054  9697  9697 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:49.054  9697  9697 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:15:49.054  9697  9697 E Zygote  : accessInfo : 0
06-09 17:15:49.054  9697  9697 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
06-09 17:15:49.054  3503  3858 I ActivityManager: Start proc 9697:com.samsung.hs20provider/u0a114 for content provider com.samsung.hs20provider/.Hs20Provider
,06-09 17:15:49.064  9684  9684 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
06-09 17:15:49.064  3503  3854 I WifiConfigStore: "AndroidHotspot2346" is a verified password AP: true
06-09 17:15:49.064  3503  3854 E WifiConfigStore: Not a HS20
,06-09 17:15:49.074  3503  3854 I WifiConfigStore: "MC" is a verified password AP: true
06-09 17:15:49.074  3503  3854 E WifiConfigStore: Not a HS20
,06-09 17:15:49.074  3503  3981 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:49.084  3503  3854 I WifiConfigStore: "MC" is a verified password AP: false
06-09 17:15:49.084  3503  3854 E WifiConfigStore: Not a HS20
,06-09 17:15:49.094  3503  3981 I ActivityManager: Start proc 9710:com.samsung.android.themestore/u0a64 for broadcast-5 com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,06-09 17:15:49.094  9710  9710 E Zygote  : v2
06-09 17:15:49.094  9710  9710 I libpersona: KNOX_SDCARD checking this for 10064
06-09 17:15:49.094  9710  9710 I libpersona: KNOX_SDCARD not a persona
06-09 17:15:49.094  9710  9710 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:15:49.094  3503  3981 I ActivityManager: Killing 8988:com.google.android.partnersetup/u0a23 (adj 15): DHA:empty #33
,06-09 17:15:49.094  9710  9710 E Zygote  : accessInfo : 0
,06-09 17:15:49.094  9710  9710 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
06-09 17:15:49.094  9697  9697 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-09 17:15:49.094  9697  9697 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:49.094  3503  3854 I WifiConfigStore: "NG700" is a verified password AP: true
,06-09 17:15:49.094  3503  3854 E WifiConfigStore: Not a HS20
,06-09 17:15:49.104  3503  3854 D WifiConfigStore: loaded 0 passpoint configs
,06-09 17:15:49.104  3503  3854 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,06-09 17:15:49.104  3503  3854 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
06-09 17:15:49.104  3503  3854 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,06-09 17:15:49.104  3503  3854 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,06-09 17:15:49.104  3503  3854 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 4
06-09 17:15:49.104  3503  3854 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
06-09 17:15:49.104  3503  3854 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
06-09 17:15:49.104  3503  3854 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
06-09 17:15:49.104  3503  3854 E WifiConfigStore: found sortedWifiConfigurations : "MC"NONE
,06-09 17:15:49.114  3503  3854 D WifiConfigStore: setNetworkPriorityDefault: networkId = 1, priority = 1
06-09 17:15:49.114  3503  3503 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
06-09 17:15:49.114  3503  3503 D WifiHs20Service: reason: 2
06-09 17:15:49.114  3503  3861 I WifiHs20Service: Message received 5014
06-09 17:15:49.114  3503  3861 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
06-09 17:15:49.114  3503  3861 E WifiHs20Service: The changed config is NULL
06-09 17:15:49.114  3503  3854 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
,06-09 17:15:49.114  3503  3854 D WifiConfigStore: setNetworkPriorityDefault: networkId = 3, priority = 1
,06-09 17:15:49.114  3503  3854 D WifiConfigStore: setNetworkPriorityDefault: networkId = 2, priority = 1
,06-09 17:15:49.114  3503  3854 D WifiNative-wlan0: callSECApiInt - ID [65]
,06-09 17:15:49.114  3503  4415 D ActivityManager: cleanUpApplicationRecord -- 8988
,06-09 17:15:49.124  3503  3854 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,06-09 17:15:49.124  9584  9584 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
,06-09 17:15:49.124  9584  9584 I wpa_supplicant: resume autoscan
06-09 17:15:49.124  3503  4415 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
06-09 17:15:49.124  9584  9584 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
06-09 17:15:49.124  9697  9697 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
06-09 17:15:49.124  9584  9584 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
06-09 17:15:49.124  9584  9584 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
06-09 17:15:49.124  9584  9584 I wpa_supplicant: reset timer : RESET_TIMER 0
06-09 17:15:49.124  9584  9584 I wpa_supplicant: P2P: Current p2p state = IDLE
06-09 17:15:49.124  9584  9584 I wpa_supplicant: First Scan Start
,06-09 17:15:49.124  3503  4412 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:15:49.124  9697  9697 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:49.124  9584  9584 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,06-09 17:15:49.124  9697  9697 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:49.124  3503  3854 D WifiNative-wlan0: Setting external_sim to 1
,06-09 17:15:49.124  3503  3854 D WifiStateMachine: Setting OUI to DA-A1-19
,06-09 17:15:49.134  9584  9584 I wpa_supplicant: bt_status is set be DISCONNECTED
,06-09 17:15:49.134  9697  9697 I InjectionManager: Inside getClassLibPath caller 
06-09 17:15:49.134  9710  9710 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:49.134  9710  9710 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:49.134  3503  3854 E WifiNative-wlan0: do suspend false
,06-09 17:15:49.134  9697  9697 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,06-09 17:15:49.144  3503  3981 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d84ca7 9710:com.samsung.android.themestore/u0a64}
,06-09 17:15:49.144  3503  3854 D WifiStateMachine:  p2p Needed be enabled 
,06-09 17:15:49.144  3503  3854 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
06-09 17:15:49.144  3503  3853 D WifiP2pService: P2pDisabledState{ what=131203 }
06-09 17:15:49.144  3503  3854 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
06-09 17:15:49.144  3503  3854 D WifiStateMachine: [FCC]Airplane off, setFccChannel(-1)!!!
06-09 17:15:49.154  9710  9710 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeStore_3xh/ThemeStore_3xh.apk / 1.0 running in com.samsung.android.themestore rsrc of package com.samsung.android.themestore
06-09 17:15:49.144  3503  3854 D WifiStateMachine: setFccChannelNative: channel = -1
06-09 17:15:49.154  3503  4412 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-09 17:15:49.144  3503  3854 D WifiNative-wlan0: callSECApiInt - ID [230]
06-09 17:15:49.144  9697  9697 D InjectionManager: InjectionManager
06-09 17:15:49.144  9697  9697 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
06-09 17:15:49.154  9697  9697 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
06-09 17:15:49.154  9697  9697 I InjectionManager: featureStore :{}
06-09 17:15:49.154  3503  3888 E WifiScanningService: could not start HAL
06-09 17:15:49.154  3154  3616 D CommandListener: Setting iface cfg
06-09 17:15:49.154  3154  3616 D CommandListener: Trying to bring up p2p0
06-09 17:15:49.154  3503  3503 D RttService: SCAN_AVAILABLE : 3
06-09 17:15:49.154  3503  3889 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
06-09 17:15:49.154  3154  3609 D Netd    : Iface p2p0 link up
06-09 17:15:49.154  3503  3853 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
06-09 17:15:49.154  3503  3853 D SecContentProvider: insert(), uri = 2
,06-09 17:15:49.154  9710  9710 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:49.154  5001  5013 D PdnController: Interface Changed p2p0 link up
06-09 17:15:49.154  3503  3853 D WifiP2pService: P2pEnablingState
06-09 17:15:49.154  3503  3596 D Tethering: interfaceLinkStateChanged p2p0, true
06-09 17:15:49.164  9710  9710 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:49.164  3503  3596 D Tethering: interfaceStatusChanged p2p0, true
06-09 17:15:49.164  3503  3853 D WifiP2pService: P2pEnablingState{ what=147457 }
06-09 17:15:49.164  3503  3853 D SecContentProvider: insert(), uri = 2
06-09 17:15:49.164  3503  3853 D WifiP2pService: P2p socket connection successful
06-09 17:15:49.164  3503  3853 D WifiP2pService: P2pEnabledState
,06-09 17:15:49.164  3503  3853 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
06-09 17:15:49.164  9710  9710 I InjectionManager: Inside getClassLibPath caller 
06-09 17:15:49.164  3503  3863 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
06-09 17:15:49.164  3503  3863 E ConnectivityService: updateNetworkInfo()
06-09 17:15:49.164  3503  3503 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,06-09 17:15:49.164  3503  3602 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
06-09 17:15:49.164  3503  3602 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
06-09 17:15:49.164  3503  3602 D WifiDisplayController: disconnect
,06-09 17:15:49.164  3503  3602 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-09 17:15:49.174  9710  9710 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeStore_3xh/lib/arm64
,06-09 17:15:49.174  9697  9709 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
06-09 17:15:49.174  9697  9709 D HotspotProvider: CREDENTIAL
06-09 17:15:49.174  3933  3933 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,06-09 17:15:49.174  9697  9709 D HotspotProvider: No prepend tags
06-09 17:15:49.174  3933  3933 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,06-09 17:15:49.174  3933  3933 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
06-09 17:15:49.174  3503  3524 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-09 17:15:49.174  3933  3933 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,06-09 17:15:49.184  3503  3602 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:49.184  3503  3602 I WifiDisplayAdapter: onP2pDisconnected
06-09 17:15:49.184  3503  3602 D IpRemoteDisplayController: disconnectWfdBridgeServer
06-09 17:15:49.184  3503  3602 D IpRemoteDisplayController: WfdBridgeServer is already null
,06-09 17:15:49.184  3933  3933 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,06-09 17:15:49.184  9710  9710 D a       : Exist Config : false
06-09 17:15:49.184  9710  9710 D a       : getMcc
06-09 17:15:49.184  9710  9710 D ai      : isQaMode
,06-09 17:15:49.194  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e5dfcfd u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7eb0042 9624:com.samsung.android.app.FileShareClient/5005}
,06-09 17:15:49.194  9710  9710 D a       : getMnc
06-09 17:15:49.194  9710  9710 D a       : getCsc
06-09 17:15:49.194  9710  9710 D a       : getSystemCountryCode
06-09 17:15:49.194  9710  9710 D a       : getImei
06-09 17:15:49.194  9624  9624 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,06-09 17:15:49.194  3503  3858 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
06-09 17:15:49.194  3503  3858 D HS20StateMachine: enter : DiscoveringState
,06-09 17:15:49.194  9624  9624 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
06-09 17:15:49.194  9624  9624 D FileShare-Client: Outbound.stopDelayTimer - 
,06-09 17:15:49.204  9710  9710 D ai      : getMd5HashString
,06-09 17:15:49.204  9710  9710 D ai      : getSha256HashString
,06-09 17:15:49.204  9710  9710 D a       : getMsisdn
,06-09 17:15:49.204  4254  4266 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,06-09 17:15:49.214  9584  9584 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
06-09 17:15:49.214  9584  9584 I wpa_supplicant: Scan aborted because the firmware maybe busy.
06-09 17:15:49.214  9584  9584 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
06-09 17:15:49.214  9584  9584 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
06-09 17:15:49.214  3503  3854 I WifiStateMachine: mWifiNative.bssFlush()
,06-09 17:15:49.214  9584  9584 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,06-09 17:15:49.214  9584  9584 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,06-09 17:15:49.214  3503  4293 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e5dfcfd u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e2f6853 9636:com.samsung.android.app.FileShareServer/5005},
,06-09 17:15:49.224  3503  3854 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-09 17:15:49.224  9636  9636 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,06-09 17:15:49.224  9636  9636 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,06-09 17:15:49.224  9636  9636 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,06-09 17:15:49.224  3503  3854 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-09 17:15:49.224  9710  9710 D a       : getModelName
06-09 17:15:49.234  4254  4265 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,06-09 17:15:49.234  9710  9710 D a       : getVirtualModelName
06-09 17:15:49.234  9710  9710 D a       : getAndroidSDKVersion
06-09 17:15:49.234  9710  9710 D a       : getLanguageCode
06-09 17:15:49.234  9710  9710 D a       : getCountryCode
,06-09 17:15:49.234  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:49.234  3503  4414 I ActivityManager: Killing 9007:com.samsung.android.asksmanager/u0a171 (adj 15): DHA:empty #33
,06-09 17:15:49.244  9710  9710 D a       : getNetworkType
,06-09 17:15:49.244  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:49.254  9710  9710 D t       : isSupportedAodSystemFeature
,06-09 17:15:49.254  9710  9710 D a       : isLogPrintMode
,06-09 17:15:49.264  9710  9710 D ai      : isQaMode
,06-09 17:15:49.264  3503  4413 D ActivityManager: cleanUpApplicationRecord -- 9007
,06-09 17:15:49.264  3503  4413 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.asksmanager, Auto Run ON
,06-09 17:15:49.264  9710  9710 D a       : getVerName
,06-09 17:15:49.274  9710  9710 D a       : getVerCode
,06-09 17:15:49.274  9710  9710 D a       : getPackageName
06-09 17:15:49.274  9710  9710 D a       : getAutoUpgradeInterval
,06-09 17:15:49.274  9710  9710 D a       : loadCountrySearchEx
,06-09 17:15:49.274  3503  3853 E WifiP2pService: Failed to set my phone number info into probe response
,06-09 17:15:49.274  3503  3853 D WifiNative-p2p0: p2pGetDeviceAddress
,06-09 17:15:49.274  3503  3853 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a9:a3:f3
,06-09 17:15:49.284  9710  9710 I a       : voCountrySearchEx loaded.
,06-09 17:15:49.284  3503  3853 D WifiP2pService: DeviceAddress: 4e:a3:f3
06-09 17:15:49.284  9710  9710 I a       : # initConfig Time : 102
06-09 17:15:49.284  3503  3602 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  deviceAddress: 4e:66:41:a9:a3:f3
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  primary type: 10-0050F204-5
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  secondary type: null
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  wps: 0
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  grpcapab: 0
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  devcapab: 0
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  status: 3
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  wfdInfo: null
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  groupownerAddress: null
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  GOdeviceName: null
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  interfaceAddress: 
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  SConnectInfo : null
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  contactInfoHash : null
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  ssDevInfo : 0
06-09 17:15:49.284  3503  3602 D WifiDisplayController:  iconIdx : 0
06-09 17:15:49.284  9710  9710 I a       : ● MCCNNC : 260 0
06-09 17:15:49.284  9710  9710 I a       : ● Model : SM-G930F_TM
06-09 17:15:49.284  9710  9710 I a       : ● MyApp Vertion : 1.03.22(20160524)
06-09 17:15:49.284  9710  9710 I a       : ● OS Vertion : 23
,06-09 17:15:49.294  3503  3853 D WifiP2pService: sending p2p persistent groups changed broadcast
,06-09 17:15:49.294  3503  3853 D WifiP2pService: InactiveState
06-09 17:15:49.294  3503  3853 D WifiP2pService: InactiveState{ what=143376 }
,06-09 17:15:49.294  3503  3853 D WifiP2pService: P2pEnabledState{ what=143376 }
,06-09 17:15:49.294  9584  9584 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,06-09 17:15:49.294  9710  9710 D InjectionManager: InjectionManager
,06-09 17:15:49.294  9710  9710 D InjectionManager: fillFeatureStoreMap com.samsung.android.themestore
,06-09 17:15:49.304  9710  9710 I InjectionManager: Constructor com.samsung.android.themestore, Feature store :{}
06-09 17:15:49.304  3503  3853 D WifiP2pService: InactiveState{ what=143376 }
06-09 17:15:49.304  9710  9710 I InjectionManager: featureStore :{}
06-09 17:15:49.304  3503  3853 D WifiP2pService: P2pEnabledState{ what=143376 }
06-09 17:15:49.304  9710  9710 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,06-09 17:15:49.304  3503  4293 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:49.314  9729  9729 E Zygote  : v2
06-09 17:15:49.314  9729  9729 I libpersona: KNOX_SDCARD checking this for 5009
06-09 17:15:49.314  9729  9729 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:49.314  9729  9729 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:15:49.314  9729  9729 E Zygote  : accessInfo : 0
06-09 17:15:49.324  3503  4293 I ActivityManager: Start proc 9729:com.samsung.android.scloud:contentsync/5009 for broadcast-5 com.samsung.android.scloud/.cloudagent.detector.DetectorReceiver
,06-09 17:15:49.324  9729  9729 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud:contentsync 
,06-09 17:15:49.324  3503  4293 I ActivityManager: Killing 9033:com.samsung.svoice.sync/u0a40 (adj 15): DHA:empty #33
,06-09 17:15:49.334  3503  3848 D ActivityManager: cleanUpApplicationRecord -- 9033
,06-09 17:15:49.334  3503  3848 D ActivityManager: isAutoRunBlockedApp:: com.samsung.svoice.sync, Auto Run ON
,06-09 17:15:49.344  3503  6040 D SSRM:n  : SIOP:: AP = 330, PST = 326 (W:14), CP = 266, CUR = -44, LCD = 40
,06-09 17:15:49.354  3503  6040 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:49.354  9729  9729 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:49.354  9729  9729 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:49.364  3503  3524 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9c7fdf2 9729:com.samsung.android.scloud:contentsync/5009}
,06-09 17:15:49.374  9729  9729 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.scloud
,06-09 17:15:49.374  3503  4413 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:15:49.374  9729  9729 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:49.374  9729  9729 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:49.384  9729  9729 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:49.384  9729  9729 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungCloud/lib/arm64
,06-09 17:15:49.394  9370  9451 D BluetoothAdapter: STATE_ON
,06-09 17:15:49.394  9370  9451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-09 17:15:49.394  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:49.394  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:49.394  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-09 17:15:49.394  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-09 17:15:49.394  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-09 17:15:49.394  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
06-09 17:15:49.394  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-09 17:15:49.394  9370  9451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-09 17:15:49.394  9370  9433 D BluetoothAdapter: enable()
,06-09 17:15:49.404  9370  9433 D BluetoothAdapter: enable(): BT is already enabled..!
,06-09 17:15:49.414  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4b30c43 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:49.414  9370  9433 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,06-09 17:15:49.424  3503  4209 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,06-09 17:15:49.424  3503  4209 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,06-09 17:15:49.434  3503  4209 D WifiService: setWifiEnabled: true pid=9370, uid=10074
06-09 17:15:49.434  3503  4209 W ActivityManager: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,06-09 17:15:49.434  3503  4209 W WifiService: Failed getting userId using ActivityManagerNative
06-09 17:15:49.434  3503  4209 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9370, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
06-09 17:15:49.434  3503  4209 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
06-09 17:15:49.434  3503  4209 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
06-09 17:15:49.434  3503  4209 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
06-09 17:15:49.434  3503  4209 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
06-09 17:15:49.434  3503  4209 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,06-09 17:15:49.434  3503  4209 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,06-09 17:15:49.434  3503  4209 D SettingsProvider: isChangeAllowed() : name = wifi_on
,06-09 17:15:49.434  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,06-09 17:15:49.434  3503  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
06-09 17:15:49.434  9370  9433 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,06-09 17:15:49.434  3503  3857 D WifiController: [FCC]setFccChannel() is called !!!
06-09 17:15:49.434  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-09 17:15:49.434  3503  3857 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
06-09 17:15:49.434  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,06-09 17:15:49.434  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-09 17:15:49.434  9370  9433 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c033c2 removed from the list
06-09 17:15:49.434  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c033c2 removed from the list
06-09 17:15:49.434  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-09 17:15:49.434  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca755d3 removed from the list
06-09 17:15:49.434  9370  9433 D io.jxcore.node.ConnectivityMonitor: stop
06-09 17:15:49.434  9370  9433 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,06-09 17:15:49.434  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-09 17:15:49.434  3503  3854 D WifiBigDataLog: getJsonFormat() - feature : ONOF
06-09 17:15:49.434  3503  3854 D WifiBigDataLog: init : 
06-09 17:15:49.434  9370  9433 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
06-09 17:15:49.434  9729  9729 I [SC]CloudManager: requestInit
06-09 17:15:49.434  3503  3857 D WifiStateMachine: setFccChannel: channel = -1
06-09 17:15:49.434  3503  3854 D WifiStateMachine: setFccChannelNative: channel = -1,
,06-09 17:15:49.434  3503  3854 D WifiNative-wlan0: callSECApiInt - ID [230]
06-09 17:15:49.444  9370  9741 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
06-09 17:15:49.444  9370  9741 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
06-09 17:15:49.444  3154  3612 D EnterpriseController: netId is 0
,06-09 17:15:49.444  3154  3612 D Netd    : getNetworkForDns: using netid 0 for uid 10074
06-09 17:15:49.444  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ccad2c0 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b9e1afd 4990:com.samsung.android.providers.context/u0a7}
,06-09 17:15:49.454  9370  9743 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
06-09 17:15:49.454  9370  9743 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
06-09 17:15:49.454  9370  9743 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
06-09 17:15:49.454  9370  9741 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
06-09 17:15:49.454  9370  9741 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
06-09 17:15:49.454  9370  9741 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,06-09 17:15:49.454  9370  9743 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
06-09 17:15:49.454  9370  9741 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
06-09 17:15:49.454  9370  9743 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
06-09 17:15:49.454  9370  9741 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,06-09 17:15:49.454  9370  9746 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.454  9370  9746 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:49.454  9370  9746 D io.jxcore.node.StreamCopyingThread:  id: 75
,06-09 17:15:49.454  9370  9745 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.454  9370  9745 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:49.454  9370  9745 D io.jxcore.node.StreamCopyingThread:  id: 74
,06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 239, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread:  id: 74
,06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 239, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread:  id: 74
,06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread:  id: 74
06-09 17:15:49.454  9370  9748 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 240, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.454  9370  9748 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:49.454  9370  9748 D io.jxcore.node.StreamCopyingThread:  id: 75
06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-09 17:15:49.454  9370  9747 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
06-09 17:15:49.454  9370  9748 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 240, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.454  9370  9748 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:49.454  9370  9748 D io.jxcore.node.StreamCopyingThread:  id: 75
06-09 17:15:49.454  9370  9748 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.454  9370  9748 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:49.454  9370  9748 D io.jxcore.node.StreamCopyingThread:  id: 75
06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 239, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:49.454  9370  9747 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
06-09 17:15:49.454  9370  9748 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-09 17:15:49.464  9370  9748 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
06-09 17:15:49.464  9370  9745 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 237, thread name: IncomingSocketThread/Sender): Socket closed
06-09 17:15:49.464  9370  9748 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
06-09 17:15:49.464  9370  9748 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
06-09 17:15:49.464  9370  9746 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 238, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
06-09 17:15:49.464  9370  9748 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-09 17:15:49.464  9370  9748 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,06-09 17:15:49.464  9370  9748 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 240, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.464  9370  9748 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:49.464  9370  9748 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
06-09 17:15:49.464  9370  9745 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.464  9370  9745 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:49.464  9370  9745 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
06-09 17:15:49.464  9370  9745 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
06-09 17:15:49.464  9370  9746 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.464  9370  9746 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:49.464  9370  9746 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
06-09 17:15:49.464  9370  9745 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
06-09 17:15:49.464  9370  9746 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
06-09 17:15:49.464  9370  9745 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.464  9370  9745 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:49.464  9370  9745 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
06-09 17:15:49.464  9370  9746 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
06-09 17:15:49.464  9370  9746 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:49.464  9370  9746 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:49.464  9370  9746 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,06-09 17:15:49.474  9729  9729 I [SC]Utils: folder : cachecreate fail, try again.
06-09 17:15:49.474  9729  9729 I [SC]Utils: folder : cache create fail.
,06-09 17:15:49.474  9729  9729 I [SC]Utils: folder : thumbnailcreate fail, try again.
06-09 17:15:49.474  9729  9729 I [SC]Utils: folder : thumbnail create fail.
06-09 17:15:49.474  9729  9729 I [SC]Utils: folder : sharecreate fail, try again.
06-09 17:15:49.474  9729  9729 I [SC]Utils: folder : share create fail.
06-09 17:15:49.474  9729  9729 I [SC]Utils: folder : scratchcreate fail, try again.
06-09 17:15:49.474  9729  9729 I [SC]Utils: folder : scratch create fail.
,06-09 17:15:49.474  9729  9729 I [SC]Utils: folder : eventSynccreate fail, try again.
,06-09 17:15:49.474  9729  9729 I [SC]Utils: folder : eventSync create fail.
,06-09 17:15:49.494  9729  9729 V SamsungCloudLogs:  set Log level [4->4]act[false]
,06-09 17:15:49.494  9729  9729 I [SC]CommonUtil: isSemAvailable:0
,06-09 17:15:49.504  9729  9729 I [SC]SamsungCloudApp: AppVer[2.1.14][L:4]Sem[false]V21MAIN_R slog[false]com.samsung.android.scloud:contentsync
06-09 17:15:49.504  9729  9729 D InjectionManager: InjectionManager
,06-09 17:15:49.504  9729  9729 D InjectionManager: fillFeatureStoreMap com.samsung.android.scloud
06-09 17:15:49.504  9729  9729 I InjectionManager: Constructor com.samsung.android.scloud, Feature store :{}
06-09 17:15:49.504  9729  9729 I InjectionManager: featureStore :{}
,06-09 17:15:49.504  9729  9729 I [SC]FeatureManager: FeatureManager 
06-09 17:15:49.504  9729  9729 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_CONFIG_CLOUD_USAGE_MENU_TREE]str 
06-09 17:15:49.504  9729  9729 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_ENABLE_SETTING_MENU]bln true
,06-09 17:15:49.504  9729  9729 E [SC]SCLOUD_ERR-Utils: isShipMode : 1 
,06-09 17:15:49.504  9729  9729 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
06-09 17:15:49.504  9729  9729 I [SC]CloudManager: requestInit
06-09 17:15:49.504  9729  9729 I [SC]Utils: folder : cachecreate fail, try again.
,06-09 17:15:49.504  9729  9729 I [SC]Utils: folder : cache create fail.
06-09 17:15:49.504  9729  9729 I [SC]Utils: folder : thumbnailcreate fail, try again.
06-09 17:15:49.514  9729  9729 I [SC]Utils: folder : thumbnail create fail.
06-09 17:15:49.514  9729  9729 I [SC]Utils: folder : sharecreate fail, try again.
06-09 17:15:49.514  9729  9729 I [SC]Utils: folder : share create fail.
06-09 17:15:49.514  9729  9729 I [SC]Utils: folder : scratchcreate fail, try again.
,06-09 17:15:49.514  9729  9729 I [SC]Utils: folder : scratch create fail.
06-09 17:15:49.514  9729  9729 I [SC]Utils: folder : eventSynccreate fail, try again.
06-09 17:15:49.514  9729  9729 I [SC]Utils: folder : eventSync create fail.
,06-09 17:15:49.524  8813  8824 I SA      : [SCU] isHaveSA() - false
06-09 17:15:49.524  8813  8824 I SA      : [OCP] Samsung account is not Signed-in
,06-09 17:15:49.524  8813  8824 I SA      : [OCP] Delete DB (TNC data)
,06-09 17:15:49.534  9729  9729 I [SC]CommonUtil: Samsung Account Not Logged in
,06-09 17:15:49.534  3503  4845 D ActivityManager:  getDeferredInfo final delay 80
,06-09 17:15:49.534  3503  3811 V AlarmManager: Expired Alarm result :4
,06-09 17:15:49.534  3503  4412 I ActivityManager: Killing 9089:com.samsung.android.provider.shootingmodeprovider/u0a57 (adj 15): DHA:empty #33
,06-09 17:15:49.564  3503  3981 D ActivityManager: cleanUpApplicationRecord -- 9089
,06-09 17:15:49.564  3503  3981 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,06-09 17:15:49.614  3503  3592 D ActivityManager:  getDeferredInfo final delay 80
,06-09 17:15:49.694  3503  3592 D ActivityManager:  getDeferredInfo final delay 80
,06-09 17:15:49.774  3503  3592 D ActivityManager:  getDeferredInfo final delay 80
,06-09 17:15:49.904  3503  3592 D ActivityManager:  getDeferredInfo final delay 80
,06-09 17:15:49.994  3503  3592 D ActivityManager:  getDeferredInfo final delay 80
,06-09 17:15:50.064  3503  3592 D ActivityManager:  getDeferredInfo final delay 80
,06-09 17:15:50.154  3503  3592 D ActivityManager:  getDeferredInfo final delay 80
,06-09 17:15:50.214  9584  9584 I wpa_supplicant: P2P: Current p2p state = IDLE
,06-09 17:15:50.214  9584  9584 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,06-09 17:15:50.234  3503  3592 D ActivityManager:  getDeferredInfo final delay 80
,06-09 17:15:50.314  3503  3592 D ActivityManager:  getDeferredInfo final delay 80
,06-09 17:15:50.394  3503  3592 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:50.424  9751  9751 E Zygote  : v2
06-09 17:15:50.424  9751  9751 I libpersona: KNOX_SDCARD checking this for 5011
06-09 17:15:50.424  9751  9751 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:50.424  9751  9751 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:15:50.434  9751  9751 E Zygote  : accessInfo : 0
06-09 17:15:50.434  9751  9751 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.coreapps 
06-09 17:15:50.434  3503  3592 I ActivityManager: Start proc 9751:com.samsung.android.coreapps/5011 for broadcast-5 com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener
,06-09 17:15:50.464  9751  9751 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:50.464  9751  9751 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:50.484  3503  4414 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e05594a 9751:com.samsung.android.coreapps/5011}
,06-09 17:15:50.504  9751  9751 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.samsung.android.coreapps
,06-09 17:15:50.504  3503  4415 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:15:50.504  9751  9751 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:50.504  9751  9751 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:50.514  9751  9751 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:50.524  9751  9751 W System  : ClassLoader referenced unknown path: /system/app/CoreApps/lib/arm64
,06-09 17:15:50.544  9751  9751 D CoreApps: SEC_LOG - true
,06-09 17:15:50.594  9751  9751 E GooglePlayServicesUtil: The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,06-09 17:15:50.774  9751  9751 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.android.mms
,06-09 17:15:50.774  9751  9751 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:50.784  9751  9751 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.google.android.talk
,06-09 17:15:50.794  9751  9751 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:50.804  9751  9751 D InjectionManager: InjectionManager
,06-09 17:15:50.804  9751  9751 D InjectionManager: fillFeatureStoreMap com.samsung.android.coreapps
06-09 17:15:50.804  9751  9751 I InjectionManager: Constructor com.samsung.android.coreapps, Feature store :{}
,06-09 17:15:50.804  9751  9751 I InjectionManager: featureStore :{}
,06-09 17:15:50.804  3503  4412 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:50.824  3503  4412 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e05594a 9751:com.samsung.android.coreapps/5011}
,06-09 17:15:50.844  3503  3848 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:50.854  3503  3848 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e05594a 9751:com.samsung.android.coreapps/5011}
,06-09 17:15:50.894  3503  3848 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:50.894  3503  3848 I ActivityManager: Killing 8905:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #33
,06-09 17:15:50.904  3503  3848 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{50ddaa0 4807:com.microsoft.skydrive/u0a124}
,06-09 17:15:50.904  3503  3975 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:50.924  3503  4208 D ActivityManager: cleanUpApplicationRecord -- 8905
,06-09 17:15:50.924  3503  4208 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,06-09 17:15:50.934  3503  4412 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,06-09 17:15:50.934  3503  4408 D ActivityManager:  getDeferredInfo final delay 300
,06-09 17:15:51.234  3503  3592 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:51.254  9781  9781 E Zygote  : v2
06-09 17:15:51.254  9781  9781 I libpersona: KNOX_SDCARD checking this for 10129
06-09 17:15:51.254  9781  9781 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:51.254  9781  9781 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:15:51.264  3503  3592 I ActivityManager: Start proc 9781:com.google.android.apps.photos/u0a129 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
06-09 17:15:51.264  3503  3852 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,06-09 17:15:51.264  9781  9781 E Zygote  : accessInfo : 0
06-09 17:15:51.264  9781  9781 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,06-09 17:15:51.294  9781  9781 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-09 17:15:51.294  9781  9781 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:51.324  3503  4208 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{780a131 9781:com.google.android.apps.photos/u0a129}
,06-09 17:15:51.324  3503  3852 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: true, uidstate: 11, mProxSensorScreenOff: false
,06-09 17:15:51.334  9781  9781 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,06-09 17:15:51.334  3503  4415 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:15:51.334  9781  9781 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:51.344  9781  9781 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:51.344  9781  9781 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:51.364  9781  9781 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm64
,06-09 17:15:51.584  9781  9781 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,06-09 17:15:51.664  9781  9781 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,06-09 17:15:51.794  9529  9529 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,06-09 17:15:51.804  9781  9781 D InjectionManager: InjectionManager
06-09 17:15:51.804  9781  9781 D InjectionManager: fillFeatureStoreMap com.google.android.apps.photos
,06-09 17:15:51.804  9781  9781 I InjectionManager: Constructor com.google.android.apps.photos, Feature store :{}
06-09 17:15:51.804  9781  9781 I InjectionManager: featureStore :{}
,06-09 17:15:51.814  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2986bf0 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{780a131 9781:com.google.android.apps.photos/u0a129}
,06-09 17:15:51.814  3503  3975 D ActivityManager:  getDeferredInfo final delay 300
,06-09 17:15:51.824  3503  3848 I ActivityManager: Killing 9103:com.samsung.android.themecenter/1000 (adj 15): DHA:empty #33
,06-09 17:15:51.844  3503  3975 I ActivityManager: Killing 9117:com.samsung.android.scloud/5009 (adj 15): DHA:empty #33
,06-09 17:15:51.854  3503  4279 D ActivityManager: cleanUpApplicationRecord -- 9103
,06-09 17:15:51.854  3503  4279 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themecenter, Auto Run ON
,06-09 17:15:51.874  3503  3524 D ActivityManager: cleanUpApplicationRecord -- 9117
,06-09 17:15:51.874  3503  3524 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,06-09 17:15:51.994  3154  3609 D Netd    : Iface wlan0 link up
,06-09 17:15:51.994  9584  9584 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
,06-09 17:15:52.004  9584  9584 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
,06-09 17:15:52.004  9584  9584 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
06-09 17:15:52.004  9584  9584 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
06-09 17:15:52.004  9584  9584 I wpa_supplicant:    allow  - level is under -85dBm [-40] or selected nid [-1] [3]
,06-09 17:15:52.004  5001  5016 D PdnController: Interface Changed wlan0 link up
,06-09 17:15:52.004  3503  3596 D Tethering: interfaceLinkStateChanged wlan0, true
,06-09 17:15:52.004  3503  3596 D Tethering: interfaceStatusChanged wlan0, true
,06-09 17:15:52.014  9584  9584 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
,06-09 17:15:52.014  9584  9584 I wpa_supplicant:    allow  - level is under -85dBm [-40] or selected nid [-1] [3]
06-09 17:15:52.014  9584  9584 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2442 MHz level=-40) 
,06-09 17:15:52.064  3503  3854 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-09 17:15:52.074  3503  3503 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,06-09 17:15:52.084  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7b0571c u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{13d0d1b 3933:com.android.systemui/u0a62}
,06-09 17:15:52.084  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:52.124  9584  9584 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,06-09 17:15:52.134  3154  3609 D Netd    : Iface wlan0 link up
06-09 17:15:52.134  3154  3609 D Netd    : Iface wlan0 link up
06-09 17:15:52.134  3154  3609 D Netd    : Iface wlan0 link up
,06-09 17:15:52.134  5001  5285 D PdnController: Interface Changed wlan0 link up
,06-09 17:15:52.134  3503  3596 D Tethering: interfaceLinkStateChanged wlan0, true
,06-09 17:15:52.134  3503  3596 D Tethering: interfaceStatusChanged wlan0, true
06-09 17:15:52.144  5001  5013 D PdnController: Interface Changed wlan0 link up
,06-09 17:15:52.144  3503  3596 D Tethering: interfaceLinkStateChanged wlan0, true
06-09 17:15:52.144  3503  3596 D Tethering: interfaceStatusChanged wlan0, true
06-09 17:15:52.144  5001  5016 D PdnController: Interface Changed wlan0 link up
,06-09 17:15:52.144  3503  3596 D Tethering: interfaceLinkStateChanged wlan0, true
,06-09 17:15:52.144  3503  3596 D Tethering: interfaceStatusChanged wlan0, true
,06-09 17:15:52.144  9584  9584 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,06-09 17:15:52.154  9584  9584 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,06-09 17:15:52.154  9584  9584 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,06-09 17:15:52.164  3503  3854 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-09 17:15:52.174  9584  9584 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,06-09 17:15:52.174  9584  9584 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,06-09 17:15:52.184  3503  3592 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:52.184  9584  9584 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,06-09 17:15:52.184  9584  9584 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=3 id_str=]
06-09 17:15:52.184  3154  3609 D Netd    : Iface wlan0 link up
06-09 17:15:52.184  9584  9584 I wpa_supplicant: Blacklist: Clear (temp) 
,06-09 17:15:52.184  5001  5285 D PdnController: Interface Changed wlan0 link up
06-09 17:15:52.184  3503  3596 D Tethering: interfaceLinkStateChanged wlan0, true
06-09 17:15:52.184  3503  3596 D Tethering: interfaceStatusChanged wlan0, true
,06-09 17:15:52.194  3503  3592 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{780a131 9781:com.google.android.apps.photos/u0a129}
,06-09 17:15:52.194  3503  3854 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-09 17:15:52.204  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:52.204  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c47cf25 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{780a131 9781:com.google.android.apps.photos/u0a129}
,06-09 17:15:52.204  3503  4412 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:52.214  3503  3854 D WifiNative-wlan0: callSECApiVoid - ID [50]
,06-09 17:15:52.214  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:52.214  3503  4412 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d5f0b24 4627:com.sec.android.daemonapp/u0a159}
,06-09 17:15:52.224  4627  4627 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,06-09 17:15:52.224  4627  4627 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,06-09 17:15:52.234  3503  3854 V AlarmManager:  remove PendingIntent] PendingIntent{258fd8a: PendingIntentRecord{fe02ffb android broadcastIntent}}
,06-09 17:15:52.234  3503  3854 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,06-09 17:15:52.234  3503  3854 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-09 17:15:52.234  3503  3863 E ConnectivityService: updateNetworkInfo()
06-09 17:15:52.234  3503  3863 D ConnectivityService: Got NetworkAgent Messenger
06-09 17:15:52.244  3503  3863 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:52.244  3503  3863 D ConnectivityService: NetworkAgent connected
06-09 17:15:52.244  3503  3503 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
06-09 17:15:52.244  3503  3503 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-09 17:15:52.244  3154  3616 D CommandListener: Setting iface cfg
,06-09 17:15:52.244  3503  3503 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,06-09 17:15:52.244  3503  3861 I WifiHs20Service: Message received 5007
06-09 17:15:52.244  3503  3503 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,06-09 17:15:52.254  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-09 17:15:52.254  4254  4254 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,06-09 17:15:52.254  3503  4412 D ActivityManager:  getDeferredInfo final delay 300
,06-09 17:15:52.264  3503  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c02e37f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f5a651 9585:com.sec.android.diagmonagent/1000}
,06-09 17:15:52.274  9585  9585 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,06-09 17:15:52.274  9585  9585 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
06-09 17:15:52.274  9585  9585 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,06-09 17:15:52.274  9585  9585 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,06-09 17:15:52.274  3503  3854 D WifiStateMachine: Start Dhcp Watchdog 2
,06-09 17:15:52.284  3503  3854 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,06-09 17:15:52.284  3503  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c02e37f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8118759 6368:com.enhance.gameservice/u0a106}
,06-09 17:15:52.294  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:52.304  3503  3854 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,06-09 17:15:52.304  3503  3863 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
06-09 17:15:52.304  3503  3863 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,06-09 17:15:52.304  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:15:52.304  3503  3863 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,06-09 17:15:52.324  3503  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c02e37f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec07b7 9599:com.sec.knox.switcher/1000}
,06-09 17:15:52.324  9599  9599 I usagelog: received in receiver
06-09 17:15:52.324  9599  9599 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
06-09 17:15:52.324  9599  9599 I KnoxUsageLogPro: premStatus:2
,06-09 17:15:52.324  9599  9599 I KnoxUsageLogPro: isEulaShown : false
06-09 17:15:52.324  9599  9599 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,06-09 17:15:52.344  3503  4412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c02e37f u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d633b24 9611:com.samsung.android.sm.policy/u0a135}
,06-09 17:15:52.404  3503  3854 E WifiNative-wlan0: do suspend false
,06-09 17:15:52.424  3503  3854 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
06-09 17:15:52.424  3503  3853 D WifiP2pService: InactiveState{ what=143375 }
,06-09 17:15:52.424  3503  3853 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-09 17:15:52.434  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-09 17:15:52.454  9811  9811 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,06-09 17:15:52.454  9811  9811 I dhcpcd  : version 5.5.6 starting
,06-09 17:15:52.464  9811  9811 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,06-09 17:15:52.534  9811  9811 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
06-09 17:15:52.534  9811  9811 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
06-09 17:15:52.534  9811  9811 I dhcpcd  : bssid match
,06-09 17:15:52.534  9811  9811 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
,06-09 17:15:52.554  3503  3592 D ActivityManager:  getDeferredInfo final delay 300
,06-09 17:15:52.624  9811  9811 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,06-09 17:15:52.654  9811  9811 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,06-09 17:15:52.664  3503  3863 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,06-09 17:15:52.854  3503  3592 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:52.864  3503  3592 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e2742e1 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d1d06f 7806:com.sec.android.app.samsungapps/u0a14}
,06-09 17:15:52.874  3503  3848 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:52.884  3503  3848 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{a65a063 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f5a651 9585:com.sec.android.diagmonagent/1000}
,06-09 17:15:52.884  9585  9585 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,06-09 17:15:52.884  9585  9585 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
06-09 17:15:52.884  9585  9585 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,06-09 17:15:52.894  3503  3848 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:52.904  3503  3848 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{a65a063 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec07b7 9599:com.sec.knox.switcher/1000}
,06-09 17:15:52.904  9599  9599 I usagelog: received in receiver
06-09 17:15:52.904  9599  9599 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
06-09 17:15:52.904  9599  9599 I KnoxUsageLogPro: premStatus:2
,06-09 17:15:52.904  9599  9599 I KnoxUsageLogPro: isEulaShown : false
06-09 17:15:52.904  9599  9599 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,06-09 17:15:52.904  3503  3848 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:52.914  3503  3848 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{a65a063 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d633b24 9611:com.samsung.android.sm.policy/u0a135}
,06-09 17:15:52.924  3503  3848 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:52.934  9835  9835 E Zygote  : v2
06-09 17:15:52.934  9835  9835 I libpersona: KNOX_SDCARD checking this for 1000
06-09 17:15:52.934  9835  9835 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:52.944  9835  9835 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:15:52.944  9835  9835 E Zygote  : accessInfo : 0
,06-09 17:15:52.944  3503  3848 I ActivityManager: Start proc 9835:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,06-09 17:15:52.974  9835  9835 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:52.974  9835  9835 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:52.984  3503  4414 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ada3166 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d2d84d 9835:com.samsung.android.securitylogagent/1000}
,06-09 17:15:52.994  9835  9835 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package com.samsung.android.securitylogagent
,06-09 17:15:52.994  3503  4413 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-09 17:15:52.994  9835  9835 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:52.994  9835  9835 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:52.994  9835  9835 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:53.004  9835  9835 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,06-09 17:15:53.004  9835  9835 D InjectionManager: InjectionManager
,06-09 17:15:53.004  9835  9835 D InjectionManager: fillFeatureStoreMap com.samsung.android.securitylogagent
06-09 17:15:53.004  9835  9835 I InjectionManager: Constructor com.samsung.android.securitylogagent, Feature store :{}
06-09 17:15:53.004  9835  9835 I InjectionManager: featureStore :{}
06-09 17:15:53.004  9835  9835 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
,06-09 17:15:53.004  9835  9835 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
,06-09 17:15:53.024  9835  9835 D SecurityLogAgent: KnoxConfiguration : Current State = 1
06-09 17:15:53.024  9835  9835 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,06-09 17:15:53.024  9835  9835 D SecurityLogAgent: StateMachine : Current State = 1
,06-09 17:15:53.024  3503  4414 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:53.024  3503  4414 I ActivityManager: Killing 9137:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #33
,06-09 17:15:53.044  3503  3853 D WifiP2pService: InactiveState{ what=143375 }
,06-09 17:15:53.054  3503  3853 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-09 17:15:53.054  3503  3863 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,06-09 17:15:53.064  3503  4209 D ActivityManager: cleanUpApplicationRecord -- 9137
,06-09 17:15:53.064  3503  4209 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,06-09 17:15:53.074  3503  3854 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,06-09 17:15:53.074  3503  3854 D WifiStateMachine: VerifyingLinkState enter
,06-09 17:15:53.074  3503  3863 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
,06-09 17:15:53.074  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-09 17:15:53.084  3503  3503 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
06-09 17:15:53.084  3503  3863 E ConnectivityService: updateNetworkInfo()
,06-09 17:15:53.084  3503  3863 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}, oldLp = null
06-09 17:15:53.084  3503  3863 D ConnectivityService: Adding iface wlan0 to network 503
,06-09 17:15:53.094  3503  3503 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
06-09 17:15:53.094  3503  3503 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.094  3503  3503 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
06-09 17:15:53.094  3503  3861 I WifiHs20Service: Message received 5007
,06-09 17:15:53.094  3503  3503 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,06-09 17:15:53.094  3503  3881 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,06-09 17:15:53.094  3503  3881 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,06-09 17:15:53.094  3503  3881 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,06-09 17:15:53.094  3503  3881 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
06-09 17:15:53.094  3503  3881 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
06-09 17:15:53.094  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-09 17:15:53.094  4254  4254 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,06-09 17:15:53.114  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3bbf02 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f5a651 9585:com.sec.android.diagmonagent/1000}
,06-09 17:15:53.114  3503  3881 I WifiManager: isCaptivePortalException
06-09 17:15:53.114  9585  9585 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
06-09 17:15:53.114  3503  3881 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-09 17:15:53.114  3503  3881 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-09 17:15:53.114  3503  3881 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
06-09 17:15:53.114  3503  3881 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {6676210}
06-09 17:15:53.114  3503  3881 I WifiManager: isCaptivePortalException
,06-09 17:15:53.114  3503  3881 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-09 17:15:53.114  3503  3881 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,06-09 17:15:53.114  9585  9585 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
06-09 17:15:53.114  9585  9585 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
06-09 17:15:53.114  9585  9585 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,06-09 17:15:53.114  3503  3854 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,06-09 17:15:53.124  3503  3854 D SecContentProvider: insert(), uri = 2
,06-09 17:15:53.124  3503  3525 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3bbf02 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8118759 6368:com.enhance.gameservice/u0a106}
,06-09 17:15:53.124  3503  3863 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,06-09 17:15:53.134  3503  3863 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,06-09 17:15:53.134  3503  3863 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,06-09 17:15:53.134  3503  3863 E ConnectivityService: Unexpected mtu value: 0, wlan0
06-09 17:15:53.134  3503  3863 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,06-09 17:15:53.144  3503  3525 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3bbf02 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec07b7 9599:com.sec.knox.switcher/1000}
,06-09 17:15:53.144  9599  9599 I usagelog: received in receiver
06-09 17:15:53.144  9599  9599 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
06-09 17:15:53.144  9599  9599 I KnoxUsageLogPro: premStatus:2
,06-09 17:15:53.144  9599  9599 I KnoxUsageLogPro: isEulaShown : false
06-09 17:15:53.144  9599  9599 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,06-09 17:15:53.144  3503  3863 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:15:53.144  3503  3863 V NetworkStats: updateIfacesLocked()
06-09 17:15:53.144  3503  3863 V NetworkStats: performPollLocked(flags=0x1)
06-09 17:15:53.154  3503  3503 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,06-09 17:15:53.154  3503  3863 D NetworkStatsRecorder: entry.iface is null
06-09 17:15:53.154  3503  3863 D NetworkStatsRecorder: entry.iface is null
06-09 17:15:53.154  3503  3863 D NetworkStatsRecorder: entry.iface is null
06-09 17:15:53.154  3503  3863 D NetworkStatsRecorder: entry.iface is null
,06-09 17:15:53.154  3503  3863 V NetworkStats: performPollLocked() took 5ms
06-09 17:15:53.154  3503  3863 D NtpTrustedTime: currentTimeMillis() cache hit
,06-09 17:15:53.154  3503  3525 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3bbf02 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d633b24 9611:com.samsung.android.sm.policy/u0a135}
,06-09 17:15:53.164  3503  3863 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:53.164  3503  3854 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,06-09 17:15:53.164  3503  3863 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
06-09 17:15:53.164  3503  3863 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
06-09 17:15:53.164  3503  3503 I WifiTrafficPoller: evaluateTrafficStatsPolling
06-09 17:15:53.164  3503  3854 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,06-09 17:15:53.164  3503  3863 D ConnectivityService: Not required to send intent.
06-09 17:15:53.164  3503  3863 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
,06-09 17:15:53.164  3503  3863 E ConnectivityService: updateNetworkInfo()
06-09 17:15:53.164  3503  3863 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
06-09 17:15:53.164  3503  3503 D WifiNative-wlan0: callSECApiVoid - ID [212]
06-09 17:15:53.164  3503  3863 V NetworkStats: updateIfacesLocked()
06-09 17:15:53.164  3503  3863 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:15:53.164  3503  3863 V NetworkStats: performPollLocked(flags=0x1)
,06-09 17:15:53.174  3503  3503 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
06-09 17:15:53.174  3503  3503 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-09 17:15:53.174  3503  3503 D HS20StateMachine: SSID : "NG700"
06-09 17:15:53.174  3503  3503 D HS20StateMachine: NetId : 3
06-09 17:15:53.174  3503  3503 D HS20StateMachine: checkifOSUAP  null
06-09 17:15:53.174  3503  3863 D NetworkStatsRecorder: entry.iface is null
06-09 17:15:53.174  3503  3863 D NetworkStatsRecorder: entry.iface is null
06-09 17:15:53.174  3503  3863 D NetworkStatsRecorder: entry.iface is null
06-09 17:15:53.174  3503  3503 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,06-09 17:15:53.174  3503  3863 D NetworkStatsRecorder: entry.iface is null
06-09 17:15:53.174  3503  3861 I WifiHs20Service: Message received 5007
06-09 17:15:53.174  3503  3503 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
06-09 17:15:53.174  3503  3863 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:15:53.174  3503  3863 V NetworkStats: performPollLocked() took 6ms
,06-09 17:15:53.174  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-09 17:15:53.184  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:15:53.184  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
,06-09 17:15:53.184  4254  4254 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,06-09 17:15:53.184  3503  3863 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,06-09 17:15:53.184  3503  3863 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
06-09 17:15:53.184  3503  3863 D ConnectivityService: scheduleUnvalidatedPrompt 503
06-09 17:15:53.184  3503  9807 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
06-09 17:15:53.184  3503  3863 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
,06-09 17:15:53.184  3503  9807 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
06-09 17:15:53.184  3503  3863 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
06-09 17:15:53.184  3503  9807 D NetworkMonitor: registerReceiver Captive portal receiver
06-09 17:15:53.184  3503  3863 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-09 17:15:53.184  3503  3854 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,06-09 17:15:53.194  3503  3854 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,06-09 17:15:53.194  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
,06-09 17:15:53.194  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:15:53.194  3503  4845 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,06-09 17:15:53.204  3503  4414 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,06-09 17:15:53.204  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,06-09 17:15:53.204  3503  3863 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,06-09 17:15:53.204  4254  4265 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
06-09 17:15:53.204  4254  4265 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
06-09 17:15:53.204  3503  3863 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,06-09 17:15:53.204  3503  3863 D ConnectivityService: currentScore = 0, newScore = 20
06-09 17:15:53.204  3503  3890 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.204  3503  3863 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
06-09 17:15:53.204  3503  3854 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.204  3503  3863 D ConnectivityService:    accepting network in place of null
06-09 17:15:53.204  3503  3890 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
,06-09 17:15:53.204  3503  3863 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.204  3503  3854 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:53.204  3503  3890 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
06-09 17:15:53.204  3503  3890 D Ethernet: evalRequest
06-09 17:15:53.204  3503  3890 D Ethernet:   done
06-09 17:15:53.204  3503  3525 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{581ac49 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f5a651 9585:com.sec.android.diagmonagent/1000}
06-09 17:15:53.204  3503  3854 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-09 17:15:53.204  3503  3854 D WIFI_UT : evalRequest
06-09 17:15:53.204  3503  3854 D WIFI_UT :   done
06-09 17:15:53.204  3503  3854 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.204  3503  4412 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
06-09 17:15:53.204  3503  3853 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.204  3503  3854 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,06-09 17:15:53.204  3503  3854 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-09 17:15:53.204  3503  3854 D WIFI    : evalRequest
06-09 17:15:53.204  3503  3853 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:53.204  3503  3854 D WIFI    :   done
06-09 17:15:53.204  3503  3853 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
06-09 17:15:53.204  3503  3853 D WIFI_P2P: evalRequest
06-09 17:15:53.204  3503  3853 D WIFI_P2P:   done
06-09 17:15:53.204  3503  3854 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:53.204  3503  3854 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:53.204  3503  3854 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-09 17:15:53.204  3503  3854 D WIFI    : evalRequest
06-09 17:15:53.204  3503  3854 D WIFI    :   done
06-09 17:15:53.204  9585  9585 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
06-09 17:15:53.214  9585  9585 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
06-09 17:15:53.214  9585  9585 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,06-09 17:15:53.214  9585  9585 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3635 
,06-09 17:15:53.214  3503  4413 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,06-09 17:15:53.214  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-09 17:15:53.214  3503  9807 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-09 17:15:53.214  3503  9807 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
,06-09 17:15:53.224  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,06-09 17:15:53.224  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-09 17:15:53.234  3503  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{581ac49 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8118759 6368:com.enhance.gameservice/u0a106}
,06-09 17:15:53.234  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-09 17:15:53.234  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-09 17:15:53.244  3933  4129 D ViewRootImpl: #1 mView = android.widget.LinearLayout{8667bf5 V.E...... ......I. 0,0-0,0 #102039c android:id/toast_layout_root}
,06-09 17:15:53.254  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,06-09 17:15:53.254  3503  3863 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,06-09 17:15:53.254  3503  4412 D ISSUE_DEBUG: InputChannelName : 8887e8b Toast
,06-09 17:15:53.254  3503  4412 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
06-09 17:15:53.254  3503  4845 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{581ac49 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec07b7 9599:com.sec.knox.switcher/1000}
,06-09 17:15:53.254  9599  9599 I usagelog: received in receiver
06-09 17:15:53.264  9599  9599 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
06-09 17:15:53.264  9599  9599 I KnoxUsageLogPro: premStatus:2
,06-09 17:15:53.264  9599  9599 I KnoxUsageLogPro: isEulaShown : false
06-09 17:15:53.264  9599  9599 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,06-09 17:15:53.274  3933  3933 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,06-09 17:15:53.274  3503  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{581ac49 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d633b24 9611:com.samsung.android.sm.policy/u0a135}
,06-09 17:15:53.284  3154  3616 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,06-09 17:15:53.294  3011  3011 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=4, Uoast
,06-09 17:15:53.304  3503  4408 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9ed9b81 u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f5a651 9585:com.sec.android.diagmonagent/1000}
,06-09 17:15:53.304  9585  9585 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
,06-09 17:15:53.304  9585  9585 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
06-09 17:15:53.304  9585  9585 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,06-09 17:15:53.314  3154  3616 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,06-09 17:15:53.314  3503  3863 D ConnectivityService: 503 network ip type : v4
,06-09 17:15:53.314  3503  3863 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:53.314  3503  3863 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.314  3503  4403 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3503
,06-09 17:15:53.324  3503  3863 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:53.324  3503  3863 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:53.324  3503  3863 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,06-09 17:15:53.324  3503  3863 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
06-09 17:15:53.334  3503  3863 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
06-09 17:15:53.334  3503  3863 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,06-09 17:15:53.334  3503  3601 D EntConnectivity: Not allowed due to - mEnabled false
,06-09 17:15:53.334  3503  4845 D ConnectivityService: getVpnConfig > userId : 0
06-09 17:15:53.334  3503  3863 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-09 17:15:53.334  3503  3863 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3503 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.334  3503  3863 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-09 17:15:53.334  3503  3863 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
06-09 17:15:53.334  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.334  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:53.334  3503  3863 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.334  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
06-09 17:15:53.334  3503  3863 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
,06-09 17:15:53.334  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:53.344  3503  3863 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:53.344  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.344  3503  3863 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:53.344  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:53.344  3933  4124 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1033x201]-format:1
06-09 17:15:53.344  3503  3863 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:15:53.344  3503  3601 D EntConnectivity: Not allowed due to - mEnabled false
,06-09 17:15:53.344  3503  3863 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
06-09 17:15:53.344  3503  3863 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation  passed
06-09 17:15:53.344  3503  3863 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
06-09 17:15:53.344  3503  3863 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
06-09 17:15:53.344  3503  3863 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,06-09 17:15:53.354  3503  3503 D Tethering: Tethering got CONNECTIVITY_ACTION
06-09 17:15:53.354  3503  3601 D Tethering: MasterInitialState.processMessage what=3
06-09 17:15:53.354  3503  3503 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-09 17:15:53.354  3503  3503 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
06-09 17:15:53.354  3503  3503 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.354  3503  3503 I CLocInfoService: CLocinfo wifi true 
,06-09 17:15:53.354  3933  4129 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,06-09 17:15:53.354  3933  4129 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-09 17:15:53.364  3503  3865 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,06-09 17:15:53.364  4254  4594 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
06-09 17:15:53.364  4254  4594 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,06-09 17:15:53.364  3503  3865 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,06-09 17:15:53.374  3503  3524 V WindowStateAnimator: Finishing drawing window Window{8887e8b u0 d0 Toast}: mDrawState=DRAW_PENDING
,06-09 17:15:53.374  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd9b88708
,06-09 17:15:53.374  3503  3588 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
06-09 17:15:53.374  3503  3588 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-09 17:15:53.374  3503  3588 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-09 17:15:53.374  3503  4193 V AlarmManager:  remove PendingIntent] PendingIntent{95129bd: PendingIntentRecord{7748bb2 android broadcastIntent}}
,06-09 17:15:53.374  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-09 17:15:53.384  3503  3863 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,06-09 17:15:53.394  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
06-09 17:15:53.394  3503  3503 V MARsPolicyManager: DataConnection: true
,06-09 17:15:53.404  4746  4746 D SamsungIME: EngineType = SWIFTKEY
06-09 17:15:53.404  4746  4746 D SamsungIME: mNetworkChangeReceiver isWLANConnected : true
,06-09 17:15:53.404  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
,06-09 17:15:53.404  3503  3852 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:53.404  3503  3852 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
06-09 17:15:53.404  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:15:53.404  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
,06-09 17:15:53.404  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:15:53.404  3503  3852 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,06-09 17:15:53.414  3503  4192 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.414  5001  5100 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
06-09 17:15:53.414  5001  5100 I CellLocationSupport: onCellLocationChanged
,06-09 17:15:53.414  4254  4265 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,06-09 17:15:53.414  5393  5393 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f6e08df and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:15:53.414  4254  4265 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,06-09 17:15:53.414  5393  5393 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
06-09 17:15:53.424  5001  5001 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected true
06-09 17:15:53.424  5001  5001 D PdnController: isSuspended [false] networktype [1]
06-09 17:15:53.424  5001  5001 D PdnController: Updated Interface [wlan0] For Network [1]
,06-09 17:15:53.424  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-09 17:15:53.424  3503  3885 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,06-09 17:15:53.424  5001  5001 D PdnController: isPdnUp  [true] networktype [1]
06-09 17:15:53.424  5001  5001 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [true] 
,06-09 17:15:53.434  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,06-09 17:15:53.434  3503  4414 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-09 17:15:53.434  6677  6677 I FOTA_AGENT: [lIlIIlIlIlIllllllIII(91/llllIIIllIlIIIIllllI)] WiFi Network is connected
06-09 17:15:53.434  3503  3588 D TelephonyManager: getDataEnabled: retVal=true
,06-09 17:15:53.444  5001  5100 I CellLocationSupport: Block to update PANI information in non VoWIFI
06-09 17:15:53.444  5001  5100 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,06-09 17:15:53.444  3503  4209 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:53.444  5001  5100 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
06-09 17:15:53.444  5001  5100 D PdnController: isPdnUp  [false] networktype [0]
06-09 17:15:53.444  5001  5100 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,06-09 17:15:53.454  5001  5100 D RegistrationManager: handleMessage(): 5
,06-09 17:15:53.454  3503  4412 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:53.454  5001  5100 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
06-09 17:15:53.454  5001  5100 D PdnController: isPdnUp  [false] networktype [11]
06-09 17:15:53.454  5001  5100 D RegistrationManager: setEPDGIPSecConnected [false]
06-09 17:15:53.454  5001  5100 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [true] IPAddresses [[/192.168.1.135]] DNSAddresses [[/192.168.1.1]] 
06-09 17:15:53.454  5001  5100 D RegistrationManager: isEPDGAvailable [false]
06-09 17:15:53.454  5001  5100 D RegistrationManager: setWifiPreparedOnAPM [true]
,06-09 17:15:53.454  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-09 17:15:53.464  9048  9048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
,06-09 17:15:53.464  4182  4182 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with 799116d , interval = 1800000 through LocationManagerService
,06-09 17:15:53.464  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-09 17:15:53.474  3503  3884 D WifiWatchdogStateMachine: response code : 204
,06-09 17:15:53.474  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-09 17:15:53.484  5001  5100 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
06-09 17:15:53.484  5001  5100 D RegistrationManager: getNetworkType [0]
,06-09 17:15:53.484  5001  5100 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [true] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
06-09 17:15:53.484  5001  5100 D CellLocationSupport: Siso Stack not called RegisterAN yet on XAN_NWK_TYPE_WLAN
06-09 17:15:53.484  5001  5100 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,06-09 17:15:53.484  5001  5100 D CoreStackAdaptor2: ipList Not Null[/192.168.1.135]
06-09 17:15:53.484  5001  5100 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
06-09 17:15:53.484  5001  5100 D RegistrationManager: isPreconditionProperToGoOn
06-09 17:15:53.484  5001  5100 D RegistrationManager: isDeviceShutdown [false]
06-09 17:15:53.484  5001  5100 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
06-09 17:15:53.484  5001  5100 D RegistrationManager: isDmVoLTEUpdated [false]
06-09 17:15:53.484  5001  5100 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
06-09 17:15:53.484  5001  5100 D RegistrationManager: tryRegister : Not all preconditions are met!
,06-09 17:15:53.494  4420  4420 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,06-09 17:15:53.494  4254  4617 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@bbe784a, selection=nullselectionArgs=null, sort=name ASC
,06-09 17:15:53.494  9370  9370 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,06-09 17:15:53.494  3503  3885 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,06-09 17:15:53.514  3154  3612 D EnterpriseController: netId is 0
06-09 17:15:53.514  3154  3612 D Netd    : getNetworkForDns: using netid 503 for uid 10001
,06-09 17:15:53.524  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,06-09 17:15:53.534  9649  9660 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
06-09 17:15:53.534  4962  4962 E audit   : type=1400 msg=audit(1497021353.534:278): avc:  denied  { ioctl } for  pid=6989 comm="ChromiumNet" path="socket:[39232]" dev="sockfs" ino=39232 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
06-09 17:15:53.534  4962  4962 E audit   :  SEPF_SECMOBILE_6.0.1_0031
06-09 17:15:53.534  4962  4962 E audit   : type=1300 msg=audit(1497021353.534:278): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f906fecc8 a3=7f906fec90 items=0 ppid=3178 pid=6989 auid=4294967295 uid=10068 gid=10068 euid=10068 suid=10068 fsuid=10068 egid=10068 sgid=10068 fsgid=10068 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-09 17:15:53.534  4962  4962 E audit   : type=1327 msg=audit(1497021353.534:278): proctitle="com.google.android.googlequicksearchbox:search"
06-09 17:15:53.534  4962  4962 E audit   : type=1320 msg=audit(1497021353.534:278): 
,06-09 17:15:53.534  4962  4962 E audit   : type=1400 msg=audit(1497021353.534:279): avc:  denied  { ioctl } for  pid=6989 comm="ChromiumNet" path="socket:[39233]" dev="sockfs" ino=39233 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
06-09 17:15:53.534  4962  4962 E audit   :  SEPF_SECMOBILE_6.0.1_0031
06-09 17:15:53.534  4962  4962 E audit   : type=1300 msg=audit(1497021353.534:279): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f906fecc8 a3=7f906fec90 items=0 ppid=3178 pid=6989 auid=4294967295 uid=10068 gid=10068 euid=10068 suid=10068 fsuid=10068 egid=10068 sgid=10068 fsgid=10068 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-09 17:15:53.534  4962  4962 E audit   : type=1327 msg=audit(1497021353.534:279): proctitle="com.google.android.googlequicksearchbox:search"
06-09 17:15:53.534  4962  4962 E audit   : type=1320 msg=audit(1497021353.534:279): 
06-09 17:15:53.534  9649  9660 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,06-09 17:15:53.544  9649  9660 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
06-09 17:15:53.544  9370  9370 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
06-09 17:15:53.554  9649  9659 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
06-09 17:15:53.554  9649  9659 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
06-09 17:15:53.554  9649  9659 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
06-09 17:15:53.564  3503  3863 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
06-09 17:15:53.564  3503  3863 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-09 17:15:53.564  3503  3863 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3503 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.564  3503  3863 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
06-09 17:15:53.564  3503  3863 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
06-09 17:15:53.564  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.564  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.564  3503  3863 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.564  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
06-09 17:15:53.564  3503  3863 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,06-09 17:15:53.564  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.564  3503  3863 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.564  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.574  3503  3863 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.574  3503  3863 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.574  3503  3863 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.584  3503  3890 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.584  3503  3863 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.584  3503  3854 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.584  3503  3890 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
06-09 17:15:53.584  3503  3890 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
06-09 17:15:53.584  3503  3854 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:53.584  3503  3890 D Ethernet: evalRequest
06-09 17:15:53.584  3503  3890 D Ethernet:   done
06-09 17:15:53.584  3503  3854 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-09 17:15:53.584  3503  3854 D WIFI_UT : evalRequest
06-09 17:15:53.584  3503  3854 D WIFI_UT :   done
06-09 17:15:53.584  3503  3853 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.584  3503  3863 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
06-09 17:15:53.584  3503  3854 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.584  3503  3853 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:53.584  3503  3854 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:53.584  3503  3853 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
06-09 17:15:53.584  3503  3854 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-09 17:15:53.584  3503  3853 D WIFI_P2P: evalRequest
06-09 17:15:53.584  3503  3854 D WIFI    : evalRequest
06-09 17:15:53.584  3503  3811 V AlarmManager: Expired Alarm result :4
06-09 17:15:53.584  3503  3853 D WIFI_P2P:   done
06-09 17:15:53.584  3503  3854 D WIFI    :   done
06-09 17:15:53.584  3503  3854 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:15:53.584  3503  3854 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-09 17:15:53.584  3503  3854 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-09 17:15:53.584  3503  3854 D WIFI    : evalRequest
06-09 17:15:53.584  3503  3854 D WIFI    :   done
06-09 17:15:53.594  9868  9868 E Zygote  : v2
06-09 17:15:53.594  9868  9868 I libpersona: KNOX_SDCARD checking this for 1000
06-09 17:15:53.594  9868  9868 I libpersona: KNOX_SDCARD not a persona
06-09 17:15:53.594  9868  9868 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
06-09 17:15:53.594  9868  9868 E Zygote  : accessInfo : 0
,06-09 17:15:53.604  3503  3975 I ActivityManager: Start proc 9868:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
06-09 17:15:53.604  9370  9370 D BluetoothAdapter: STATE_ON
06-09 17:15:53.604  3503  3854 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
06-09 17:15:53.604  3503  3854 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
06-09 17:15:53.614  3503  3854 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-09 17:15:53.614  3503  3854 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-09 17:15:53.614  3503  3854 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
06-09 17:15:53.614  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:15:53.614  3503  3854 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-09 17:15:53.614  3503  3854 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
06-09 17:15:53.614  4254  4617 D TelephonyProvider: query: match = 5
06-09 17:15:53.614  4254  4617 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
06-09 17:15:53.614  4254  4617 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
06-09 17:15:53.624  9370  9370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-09 17:15:53.624  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-09 17:15:53.624  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-09 17:15:53.624  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-09 17:15:53.624  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-09 17:15:53.624  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-09 17:15:53.624  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
06-09 17:15:53.624  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-09 17:15:53.624  9370  9370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-09 17:15:53.624  9370  9370 D BluetoothAdapter: STATE_ON
06-09 17:15:53.634  3933  4129 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:15:53.634  3933  4129 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
06-09 17:15:53.634  9370  9370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
06-09 17:15:53.644  9868  9868 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:53.644  9868  9868 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:53.664  3503  3588 E GpsLocationProvider: No APN found to select.
,06-09 17:15:53.674  3503  3588 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,06-09 17:15:53.674  9868  9868 W ResourcesManager: getTopLevelResources: /system/priv-app/SOAgent/SOAgent.apk / 1.0 running in com.sec.android.soagent rsrc of package com.sec.android.soagent
,06-09 17:15:53.684  3503  3525 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-09 17:15:53.684  9868  9868 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:53.684  9868  9868 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:53.684  9868  9868 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:53.694  9868  9868 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,06-09 17:15:53.714  9868  9868 D InjectionManager: InjectionManager
06-09 17:15:53.714  9868  9868 D InjectionManager: fillFeatureStoreMap com.sec.android.soagent
,06-09 17:15:53.714  9868  9868 I InjectionManager: Constructor com.sec.android.soagent, Feature store :{}
06-09 17:15:53.714  9868  9868 I InjectionManager: featureStore :{}
,06-09 17:15:53.744  3503  3981 I ActivityManager: Killing 9149:com.google.android.apps.docs/u0a93 (adj 15): DHA:empty #33
,06-09 17:15:53.764  3503  3524 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81e3806 9370:com.thaliproject.thalitest/u0a74}
,06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-09 17:15:53.764  3503  4279 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:53.774  3503  6076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-09 17:15:53.784  3503  3524 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{398d68e 3503:system/1000}
,06-09 17:15:53.794  3503  4412 D ActivityManager: cleanUpApplicationRecord -- 9149
06-09 17:15:53.794  3503  4412 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,06-09 17:15:53.814  3503  3503 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7df235 4571:com.google.android.gms/u0a19}
,06-09 17:15:53.814  4571  4571 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,06-09 17:15:53.814  4571  5591 I iu.UploadsManager: num queued entries: 0
,06-09 17:15:53.824  4571  5591 I iu.UploadsManager: num updated entries: 0
,06-09 17:15:53.824  4571  5591 I iu.SyncManager: NEXT; no task
,06-09 17:15:53.824  3503  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7df235 4571:com.google.android.gms/u0a19}
,06-09 17:15:53.834  3503  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{270f4ef 4226:com.google.android.gms.persistent/u0a19}
,06-09 17:15:53.854  3154  3612 D EnterpriseController: netId is 0
06-09 17:15:53.854  3154  3612 D Netd    : getNetworkForDns: using netid 503 for uid 10019
,06-09 17:15:53.854  3503  3975 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f2ae590 9649:com.policydm/1000}
,06-09 17:15:53.874  9649  9649 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,06-09 17:15:53.884  9649  9649 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,06-09 17:15:53.884  9649  9649 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,06-09 17:15:53.954  3503  3592 D ActivityManager:  getDeferredInfo final delay 420
,06-09 17:15:53.974  3503  3852 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
06-09 17:15:53.974  3503  3852 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,06-09 17:15:54.314  3503  3863 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,06-09 17:15:54.374  3503  3592 D ActivityManager:  getDeferredInfo final delay 120
,06-09 17:15:54.494  3503  3592 D ActivityManager:  getDeferredInfo final delay 120
,06-09 17:15:54.614  3503  3592 D ActivityManager:  getDeferredInfo final delay 120
,06-09 17:15:54.654  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2b875 u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{435128a 9529:com.google.android.talk/u0a112}
,06-09 17:15:54.654  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{4da600a: PendingIntentRecord{faa78c4 com.google.android.gms broadcastIntent}}
,06-09 17:15:54.674  3503  3588 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
06-09 17:15:54.674  3503  3588 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
06-09 17:15:54.674  3503  3588 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
06-09 17:15:54.674  3503  3588 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,06-09 17:15:54.744  3503  3592 D ActivityManager:  getDeferredInfo final delay 120
,06-09 17:15:54.864  3503  3592 D ActivityManager:  getDeferredInfo final delay 120
,06-09 17:15:54.944  9370  9433 I io.jxcore.node.IncomingSocketThreadTest: testRun
,06-09 17:15:54.944  9370  9433 I !!      :  finally closed
,06-09 17:15:54.944  9370  9433 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,06-09 17:15:54.944  9370  9433 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,06-09 17:15:54.954  9370  9433 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
06-09 17:15:54.954  9370  9433 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,06-09 17:15:54.954  9370  9433 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,06-09 17:15:54.954  9370  9433 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,06-09 17:15:54.954  9370  9433 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.thaliproject.thalitest.MainActivity@f9f9688 Bundle[{}]
,06-09 17:15:54.964  9370  9433 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
06-09 17:15:54.964  9370  9433 I io.jxcore.node.LifeCycleMonitor: start: OK
06-09 17:15:54.964  9370  9433 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-09 17:15:54.964  9370  9433 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
06-09 17:15:54.964  9370  9433 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,06-09 17:15:54.964  9370  9433 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
06-09 17:15:54.964  9370  9433 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,06-09 17:15:54.964  9370  9433 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
06-09 17:15:54.964  9370  9433 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,06-09 17:15:54.974  9370  9433 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,06-09 17:15:54.974  9370  9433 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,06-09 17:15:54.974  9370  9433 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,06-09 17:15:54.974  9370  9433 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,06-09 17:15:54.974  9370  9433 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,06-09 17:15:54.984  9370  9433 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,06-09 17:15:54.984  9370  9433 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,06-09 17:15:54.984  9370  9433 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,06-09 17:15:54.984  9370  9433 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,06-09 17:15:54.994  9370  9887 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
06-09 17:15:54.994  9370  9887 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,06-09 17:15:54.994  3154  3612 D EnterpriseController: netId is 0
06-09 17:15:54.994  3154  3612 D Netd    : getNetworkForDns: using netid 503 for uid 10074
,06-09 17:15:54.994  9370  9889 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
06-09 17:15:54.994  9370  9889 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
06-09 17:15:55.004  9370  9889 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
06-09 17:15:55.004  9370  9889 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
06-09 17:15:55.004  9370  9887 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
06-09 17:15:55.004  9370  9887 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
06-09 17:15:55.004  9370  9887 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
06-09 17:15:55.004  9370  9889 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
06-09 17:15:55.004  9370  9887 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,06-09 17:15:55.004  9370  9887 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,06-09 17:15:55.014  9370  9893 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 246, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9893 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:55.014  9370  9893 D io.jxcore.node.StreamCopyingThread:  id: 78
,06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 244, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread:  id: 77
06-09 17:15:55.014  9370  9892 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 245, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9892 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:55.014  9370  9892 D io.jxcore.node.StreamCopyingThread:  id: 77
,06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 247, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread:  id: 78
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 247, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread:  id: 78
,06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread:  id: 78
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-09 17:15:55.014  9370  9894 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
06-09 17:15:55.014  9370  9893 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 246, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 247, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:55.014  9370  9894 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
06-09 17:15:55.014  9370  9893 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 246, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9893 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:55.014  9370  9893 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 4096 and the total number of bytes written 4096
06-09 17:15:55.014  9370  9893 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
,06-09 17:15:55.014  9370  9893 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
06-09 17:15:55.014  9370  9893 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 246, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9893 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:15:55.014  9370  9893 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 4096 and the total number of bytes written 4096
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 244, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread:  id: 77
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread:  id: 77
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-09 17:15:55.014  9370  9891 I io.jxcore.node.IncomingSocketThread: The sending thread is done
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 244, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:55.014  9370  9891 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,06-09 17:15:55.014  9370  9892 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 245, thread name: IncomingSocketThread/Receiver): sendto failed: EPIPE (Broken pipe)
06-09 17:15:55.014  9370  9892 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 245, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9892 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:55.014  9370  9892 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 12288 and the total number of bytes written 8192
06-09 17:15:55.014  9370  9892 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)", this is likely due to peer having disconnected
06-09 17:15:55.014  9370  9892 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
06-09 17:15:55.014  9370  9892 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 245, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:15:55.014  9370  9892 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
06-09 17:15:55.014  9370  9892 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 12288 and the total number of bytes written 8192
,06-09 17:15:55.024  3503  3592 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:55.034  3503  3592 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f2ae590 9649:com.policydm/1000}
,06-09 17:15:55.034  9649  9649 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,06-09 17:15:55.064  9649  9649 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,06-09 17:15:55.074  9649  9649 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,06-09 17:15:55.074  9649  9649 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,06-09 17:15:55.084  9649  9649 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(342/lllIlIlIIIllIIlIllIl)] OMC not Supported model
,06-09 17:15:55.094  9649  9649 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(111/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,06-09 17:15:55.094  9649  9649 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(281/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,06-09 17:15:55.094  9649  9649 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] Next heartbeat time:2017/06/20/08:31:20
,06-09 17:15:55.094  9649  9649 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(55/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,06-09 17:15:55.104  3503  4208 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:55.104  3503  4208 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{255ce92 8813:com.osp.app.signin/u0a41}
,06-09 17:15:55.104  8813  8813 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = MMB29K M = SM-G930F OKLEFT false DIS MMB29K.G930FXXU1BPJG PSS = 5.059173621445858  ]
06-09 17:15:55.104  8813  8813 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
06-09 17:15:55.104  8813  8813 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,06-09 17:15:55.114  8813  8813 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,06-09 17:15:55.114  8813  8813 I SA      : [OR] == isSIMCardReady false ==
06-09 17:15:55.114  8813  8813 I SA      : [SCU] == networkStateCheck == true
,06-09 17:15:55.124  8813  8813 I SA      : [DM] getCountryCodeFromCSC : PL
06-09 17:15:55.124  8813  8813 I SA      : isChinaCountryCode : false
06-09 17:15:55.124  8813  8813 I SA      : [SCU] is ChinestModel Data Restricted   : false
06-09 17:15:55.124  8813  8813 I SA      : [OR] == networkStateCheck true ==
,06-09 17:15:55.124  8813  8813 I SA      : [OR] GetMyCountryZoneTask
,06-09 17:15:55.124  8813  8813 I SA      : [OR] onReceive END
06-09 17:15:55.124  3503  4293 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:55.124  8813  9895 I SA      : [SRS] prepareGetMyCountryZone
,06-09 17:15:55.134  3503  4293 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b7cec27 6677:com.wssyncmldm/1000}
,06-09 17:15:55.144  8813  9895 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,06-09 17:15:55.144  8813  9895 I SA      : [SSP] query invoked
,06-09 17:15:55.144  3503  3981 D ActivityManager:  getDeferredInfo final delay 300
,06-09 17:15:55.154  6677  9897 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
06-09 17:15:55.154  8813  9895 I SA      : [TPMU] GetMccFromDB : null
06-09 17:15:55.154  8813  9895 I SA      : [SCU] getMccFromPreferece mcc = 260
06-09 17:15:55.154  8813  9895 I SA      : [LBE] isSupportCheckDomainRegion : true
,06-09 17:15:55.154  8813  9895 I SA      : [TPM] isNoProxy(default) : true
,06-09 17:15:55.254  3933  4129 D ViewRootImpl: #3 mView = null
,06-09 17:15:55.264  3503  3975 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3503) eventTime = 311471
,06-09 17:15:55.264  3503  3975 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3503 (0x0)
06-09 17:15:55.264  3503  3975 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3503, ws=WorkSource{10062}) (elapsedTime=1944)
,06-09 17:15:55.314  3503  3863 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
,06-09 17:15:55.324  3933  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,06-09 17:15:55.444  3503  3592 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:55.454  3503  3592 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{269b2ff 6815:com.samsung.fresco.logging/5015}
,06-09 17:15:55.464  3503  3981 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-09 17:15:55.464  3503  4415 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-09 17:15:55.464  3503  4413 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:55.464  8813  9895 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,06-09 17:15:55.474  3503  4413 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a708799 7292:com.sec.spp.push/u0a39}
,06-09 17:15:55.474  7292  7292 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
06-09 17:15:55.474  7292  7292 E SPPClientService: [SystemStateMoniter] Current Time : 311686
,06-09 17:15:55.474  7292  7292 E SPPClientService: [SystemStateMoniter] No Connect : false
,06-09 17:15:55.484  8813  9895 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,06-09 17:15:55.484  8813  9895 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-09 17:15:55.484  8813  9895 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-09 17:15:55.484  3154  3612 D EnterpriseController: netId is 0
06-09 17:15:55.484  3154  3612 D Netd    : getNetworkForDns: using netid 503 for uid 10041
06-09 17:15:55.484  3503  4413 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:55.494  3503  4413 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a16f41 4820:android.process.media/u0a48}
,06-09 17:15:55.494  4820  4820 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,06-09 17:15:55.504  3503  3803 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-09 17:15:55.504  3503  3802 D TimaService: TimaServiceHandler.handleMessage what =1
06-09 17:15:55.504  3503  3803 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-09 17:15:55.514  3503  3803 I TLC_TIMA_PKM_initialize: initializing...
,06-09 17:15:55.514  3503  3803 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
06-09 17:15:55.514  3503  3803 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
,06-09 17:15:55.514  3503  3803 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
06-09 17:15:55.514  3503  3803 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
06-09 17:15:55.514  3503  3803 I TZ: mc_tlc_communication: root = 0, root_len = 1
06-09 17:15:55.514  3503  3803 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
06-09 17:15:55.514  3503  3803 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
06-09 17:15:55.514  3503  3803 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
06-09 17:15:55.514  3503  3803 I TZ: mc_tlc_communication: device_id = 0x0
,06-09 17:15:55.514  3503  3803 I TZ: mc_tlc_communication: tlc_open() was called
06-09 17:15:55.514  3503  4208 D ActivityManager:  getDeferredInfo final delay 300
06-09 17:15:55.514  3503  3803 I TZ: mc_tlc_communication: Opening MobiCore device
06-09 17:15:55.514  3503  3803 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
06-09 17:15:55.514  3503  3803 I TZ: mc_tlc_communication: Allocating message buffer for TCI
06-09 17:15:55.514  3503  3803 I TZ: mc_tlc_communication: Opening the session
,06-09 17:15:55.534  3503  4414 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,06-09 17:15:55.534  3503  3803 I TZ: mc_tlc_communication: tlc_open() succeeded
,06-09 17:15:55.534  3503  3803 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,06-09 17:15:55.544  3503  3803 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,06-09 17:15:55.554  3503  3803 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,06-09 17:15:55.584  3503  3803 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,06-09 17:15:55.584  3503  3803 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-09 17:15:55.684  3503  3588 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
06-09 17:15:55.684  3503  3588 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
06-09 17:15:55.684  3503  3588 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,06-09 17:15:55.814  3011  3974 I SurfaceFlinger: id=20 Removed Uoast (9/11)
,06-09 17:15:55.814  3011  3019 I SurfaceFlinger: id=20 Removed Uoast (-2/11)
,06-09 17:15:55.814  3503  3592 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:55.824  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd9b88828
,06-09 17:15:55.834  3503  3592 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9c18ecb 9684:com.samsung.android.SettingsReceiver/1000}
,06-09 17:15:55.834  9684  9684 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,06-09 17:15:55.834  3503  4408 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:55.854  3503  4408 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d84ca7 9710:com.samsung.android.themestore/u0a64}
,06-09 17:15:55.854  9710  9710 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,06-09 17:15:55.874  9710  9710 D AutoSelfUpgradeService: onCreate() 
06-09 17:15:55.874  3503  3975 D ActivityManager:  getDeferredInfo final delay 300
,06-09 17:15:55.884  9710  9710 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
,06-09 17:15:55.884  9710  9900 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
,06-09 17:15:55.884  9710  9900 D AutoSelfUpgradeService: getAlarmIntent() 
,06-09 17:15:55.884  9710  9900 D AutoSelfUpgradeService: isAlarmActivated() true
,06-09 17:15:55.894  9710  9710 D AutoSelfUpgradeService: onDestroy()
,06-09 17:15:56.184  8813  9895 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 699
,06-09 17:15:56.184  8813  9895 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,06-09 17:15:56.204  8813  9895 I SA      : [OCP] update openData : PL
,06-09 17:15:56.214  8813  9895 I SA      : [TPMU] getNetworkMcc : 260
,06-09 17:15:56.224  3503  3592 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:56.234  3503  3592 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9c7fdf2 9729:com.samsung.android.scloud:contentsync/5009}
,06-09 17:15:56.234  9729  9729 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
,06-09 17:15:56.234  9729  9729 I [SC]CloudManager: requestInit
06-09 17:15:56.234  9729  9729 I [SC]Utils: folder : cachecreate fail, try again.
,06-09 17:15:56.234  9729  9729 I [SC]Utils: folder : cache create fail.
,06-09 17:15:56.234  8813  9895 I SA      : [SCU] saveMccToPreferece Start
06-09 17:15:56.234  9729  9729 I [SC]Utils: folder : thumbnailcreate fail, try again.
,06-09 17:15:56.234  8813  9895 I SA      : [SCU] RegionMCC : 260
06-09 17:15:56.234  8813  9895 I SA      : [SSP] query invoked
06-09 17:15:56.234  9729  9729 I [SC]Utils: folder : thumbnail create fail.
,06-09 17:15:56.234  9729  9729 I [SC]Utils: folder : sharecreate fail, try again.
06-09 17:15:56.234  9729  9729 I [SC]Utils: folder : share create fail.
06-09 17:15:56.234  9729  9729 I [SC]Utils: folder : scratchcreate fail, try again.
06-09 17:15:56.234  9729  9729 I [SC]Utils: folder : scratch create fail.
,06-09 17:15:56.234  9729  9729 I [SC]Utils: folder : eventSynccreate fail, try again.
06-09 17:15:56.234  9729  9729 I [SC]Utils: folder : eventSync create fail.
,06-09 17:15:56.244  8813  9895 I SA      : [TPMU] GetMccFromDB : null
,06-09 17:15:56.244  8813  9895 I SA      : [SCU] getMccFromPreferece mcc = 260
06-09 17:15:56.244  8813  9895 I SA      : [SCU] saveMccToPreferece End
06-09 17:15:56.244  8813  9895 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 777
06-09 17:15:56.244  8813  9895 I SA_HTTPURLCONNECTION: [RC New] Execute end
,06-09 17:15:56.244  8813  8813 I SA      : [OR] GetMyCountryZoneTask mcc = 260
06-09 17:15:56.244  8813  8813 I SA      : [OR] GetMyCountryZoneTask Success
,06-09 17:15:56.254  8813  8824 I SA      : [SCU] isHaveSA() - false
06-09 17:15:56.254  8813  8824 I SA      : [OCP] Samsung account is not Signed-in
,06-09 17:15:56.254  8813  8824 I SA      : [OCP] Delete DB (TNC data)
,06-09 17:15:56.254  9729  9729 I [SC]CommonUtil: Samsung Account Not Logged in
,06-09 17:15:56.254  3503  4403 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:56.264  3503  4403 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e05594a 9751:com.samsung.android.coreapps/5011}
,06-09 17:15:56.314  3503  4279 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:56.324  3503  4279 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e05594a 9751:com.samsung.android.coreapps/5011}
,06-09 17:15:56.344  3503  3981 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:56.354  3503  3981 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e05594a 9751:com.samsung.android.coreapps/5011}
,06-09 17:15:56.354  3503  3981 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:56.364  3503  3981 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{50ddaa0 4807:com.microsoft.skydrive/u0a124}
,06-09 17:15:56.384  3503  4412 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,06-09 17:15:56.384  3503  3525 D ActivityManager:  getDeferredInfo final delay 300
,06-09 17:15:56.684  3503  3592 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:56.704  3503  3592 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{780a131 9781:com.google.android.apps.photos/u0a129}
,06-09 17:15:56.724  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{58ee662 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{780a131 9781:com.google.android.apps.photos/u0a129}
06-09 17:15:56.724  3503  3525 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:56.734  3503  3525 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{780a131 9781:com.google.android.apps.photos/u0a129}
,06-09 17:15:56.774  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1388b0 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{780a131 9781:com.google.android.apps.photos/u0a129}
06-09 17:15:56.774  3503  4293 D ActivityManager:  getDeferredInfo final delay 300
,06-09 17:15:56.894  9811  9811 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-09 17:15:57.074  3503  3592 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:57.094  3503  3592 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d5f0b24 4627:com.sec.android.daemonapp/u0a159}
,06-09 17:15:57.094  4627  4627 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,06-09 17:15:57.094  4627  4627 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
,06-09 17:15:57.094  3503  4279 D ActivityManager:  getDeferredInfo final delay 0
,06-09 17:15:57.114  3503  4279 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f6ad3ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d1d06f 7806:com.sec.android.app.samsungapps/u0a14}
,06-09 17:15:57.114  7806  7806 D WaitQueueForNetworkActivate: notifyNetworkActivated
,06-09 17:15:57.114  7806  7806 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,06-09 17:15:57.134  7806  7806 D [SAUI]  : Global::recovered::false
06-09 17:15:57.134  3503  4845 D ActivityManager:  getDeferredInfo final delay 300
06-09 17:15:57.134  7806  7806 D [SAUI]  : AutoUpdateService::onStartCommand
06-09 17:15:57.134  7806  7806 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,06-09 17:15:57.144  7806  7806 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,06-09 17:15:57.144  7806  7806 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
06-09 17:15:57.144  7806  7806 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,06-09 17:15:57.144  7806  9905 D [SA_INIT]: createTaskForServiceInitialize()
,06-09 17:15:57.154  7806  9907 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,06-09 17:15:57.154  7806  9907 D [SA_INIT]: NetworkStateCheckUnit result : 1
,06-09 17:15:57.154  7806  7806 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 233103915_0] [END] FINISHED
06-09 17:15:57.154  7806  7806 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
,06-09 17:15:57.154  7806  7806 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
,06-09 17:15:57.154  7806  7806 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
06-09 17:15:57.154  7806  7806 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,06-09 17:15:57.244  3503  3515 I art     : Background sticky concurrent mark sweep GC freed 173716(12MB) AllocSpace objects, 70(1440KB) LOS objects, 29% free, 36MB/51MB, paused 3.843ms total 120.022ms
,06-09 17:15:57.604  3503  4130 E Watchdog: !@Sync 10 [06-09 17:15:57.615]
,06-09 17:15:58.754  3503  3803 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-09 17:15:58.754  3503  3803 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-09 17:15:58.764  3503  3803 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-09 17:15:58.764  3503  3803 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-09 17:15:59.114  4303  4437 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-09 17:15:59.114  4303  4437 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-09 17:15:59.134  3503  3811 V AlarmManager: Expired Alarm result :4
,06-09 17:15:59.154  9584  9584 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
06-09 17:15:59.154  9584  9584 I wpa_supplicant: P2P: Current p2p state = IDLE
,06-09 17:15:59.164  9584  9584 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,06-09 17:15:59.174  9912  9912 E Zygote  : v2
06-09 17:15:59.184  9912  9912 I libpersona: KNOX_SDCARD checking this for 1000
06-09 17:15:59.184  9912  9912 I libpersona: KNOX_SDCARD not a persona
,06-09 17:15:59.184  9912  9912 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:15:59.184  3503  3811 I ActivityManager: Start proc 9912:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
06-09 17:15:59.184  9912  9912 E Zygote  : accessInfo : 0
,06-09 17:15:59.234  9912  9912 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:15:59.234  9912  9912 D ActivityThread: Added TimaKeyStore provider
,06-09 17:15:59.264  9912  9912 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,06-09 17:15:59.264  3503  3525 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-09 17:15:59.264  9912  9912 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:15:59.274  9912  9912 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:15:59.274  9912  9912 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:15:59.284  9912  9912 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,06-09 17:15:59.294  9912  9912 D InjectionManager: InjectionManager
,06-09 17:15:59.294  9912  9912 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
,06-09 17:15:59.294  9912  9912 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
06-09 17:15:59.294  9912  9912 I InjectionManager: featureStore :{}
,06-09 17:15:59.324  3503  4293 I ActivityManager: Killing 9170:com.samsung.dcmservice/5004 (adj 15): DHA:empty #33
,06-09 17:15:59.354  3503  3981 D ActivityManager: cleanUpApplicationRecord -- 9170
,06-09 17:15:59.354  3503  3981 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcmservice, Auto Run ON
,06-09 17:15:59.374  3503  6040 D SSRM:n  : SIOP:: AP = 320, PST = 328 (W:14), CP = 266, CUR = -44, LCD = 40
,06-09 17:15:59.994  3503  3811 V AlarmManager: Expired Alarm result :8
,06-09 17:15:59.994  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-09 17:15:59.994  3933  3933 D KeyguardUpdateMonitor: handleTimeUpdate
,06-09 17:16:00.014  3933  3933 D Clock   : received broadcast android.intent.action.TIME_TICK
,06-09 17:16:00.104  3933  3933 D DateView: received broadcast android.intent.action.TIME_TICK
,06-09 17:16:00.134  4627  4627 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,06-09 17:16:00.134  4627  4627 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,06-09 17:16:00.144  4627  4627 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,06-09 17:16:00.144  4627  4627 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,06-09 17:16:00.144  4627  4627 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A03F1EB0A7711A3063C3316A38046948D8BB167501C90E7F14D3891FC0E1953A69C8257D3F5491BE6FAC62A38DCCD105AA]}
,06-09 17:16:00.144  4627  4627 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,06-09 17:16:00.504  9370  9433 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,06-09 17:16:00.504  9370  9433 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,06-09 17:16:00.504  9370  9433 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,06-09 17:16:00.904  9811  9811 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-09 17:16:01.204  3503  3863 D ConnectivityService: handlePromptUnvalidated 503
,06-09 17:16:01.494  3503  3592 I ActivityManager: Waited long enough for: ServiceRecord{fa30ac4 u0 com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService}
,06-09 17:16:01.504  9370  9433 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,06-09 17:16:01.514  9370  9433 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,06-09 17:16:01.514  9370  9433 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,06-09 17:16:01.514  9370  9433 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 256)
,06-09 17:16:01.514  9370  9433 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
06-09 17:16:01.514  9370  9433 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
06-09 17:16:01.514  9370  9433 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 257)
,06-09 17:16:01.514  9370  9433 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,06-09 17:16:01.524  9370  9433 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,06-09 17:16:01.524  9370  9433 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,06-09 17:16:01.524  9370  9433 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,06-09 17:16:01.524  9370  9433 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e077c2f added. We now have 2 listener(s)
06-09 17:16:01.524  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e077c2f added. We now have 3 listener(s)
06-09 17:16:01.524  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,06-09 17:16:01.534  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
06-09 17:16:01.534  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-09 17:16:01.534  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
06-09 17:16:01.534  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-09 17:16:01.534  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c60623c added. We now have 4 listener(s)
06-09 17:16:01.534  9370  9433 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-09 17:16:01.534  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-09 17:16:01.544  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:01.554  9370  9433 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,06-09 17:16:01.554  9370  9433 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
06-09 17:16:01.554  9370  9433 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,06-09 17:16:01.554  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
06-09 17:16:01.554  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-09 17:16:01.554  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:2C:E6"}
,06-09 17:16:01.554  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:2C:E6"}
06-09 17:16:01.554  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.554  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-09 17:16:01.564  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:2C:E6"}
,06-09 17:16:01.564  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:2C:E6"}
06-09 17:16:01.564  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.564  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
06-09 17:16:01.564  9370  9433 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
06-09 17:16:01.564  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
06-09 17:16:01.564  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-09 17:16:01.564  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,06-09 17:16:01.564  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,06-09 17:16:01.564  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
06-09 17:16:01.564  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
06-09 17:16:01.564  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,06-09 17:16:01.564  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
06-09 17:16:01.564  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-09 17:16:01.564  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,06-09 17:16:01.564  9370  9370 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
06-09 17:16:01.564  9370  9927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,06-09 17:16:01.564  9370  9927 D BluetoothSocket: bindListen(): myUserId = 0
06-09 17:16:01.564  9370  9927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-09 17:16:01.574  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,06-09 17:16:01.574  9370  9433 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
06-09 17:16:01.574  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,06-09 17:16:01.574  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:01.574  9529  9562 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
06-09 17:16:01.574  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:01.584  9370  9927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
06-09 17:16:01.584  9370  9927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@474791a, port: 6, type: 1, local socket address: null, socket type: 0
06-09 17:16:01.584  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:01.584  9529  9564 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,06-09 17:16:01.584  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:01.584  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,06-09 17:16:01.584  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:01.584  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:01.584  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
06-09 17:16:01.584  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
06-09 17:16:01.584  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
06-09 17:16:01.584  3503  3975 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10112
,06-09 17:16:01.594  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:01.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:01.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.594  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
06-09 17:16:01.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
06-09 17:16:01.594  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d35cbc72-f199-41c1-9eeb-d4ccb56ee509", Bluetooth MAC address: "44:78:3E:94:2C:E6"
06-09 17:16:01.594  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E 94 2C E6
,06-09 17:16:01.594  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:16:01.594  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:16:01.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:01.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
06-09 17:16:01.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:16:01.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.594  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.594  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.594  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:01.594  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:01.594  9370  9433 D BluetoothLeAdvertiser: start advertising
06-09 17:16:01.594  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:01.604  4953  9505 D BtGatt.GattService: registerClient() - UUID=3db82b7e-feb0-4414-9b52-3e9787c607a4
,06-09 17:16:01.614  9929  9929 E Zygote  : v2
06-09 17:16:01.614  9929  9929 I libpersona: KNOX_SDCARD checking this for 10112
06-09 17:16:01.614  9929  9929 I libpersona: KNOX_SDCARD not a persona
,06-09 17:16:01.614  9929  9929 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:16:01.614  3503  3592 I ActivityManager: Start proc 9929:com.google.android.talk:matchstick/u0a112 for broadcast-3 com.google.android.talk/com.google.android.libraries.matchstick.net.MatchstickInProcessReceiver
,06-09 17:16:01.624  9929  9929 E Zygote  : accessInfo : 0
06-09 17:16:01.624  9929  9929 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk:matchstick 
,06-09 17:16:01.624  3503  4414 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,06-09 17:16:01.634  9529  9529 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,06-09 17:16:01.634  9529  9529 W Babel   : BAM#gBA: invalid account id: -1
06-09 17:16:01.634  9529  9529 W Babel   : BAM#gBA: invalid account id: -1
06-09 17:16:01.634  9529  9529 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,06-09 17:16:01.644  3503  4845 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,06-09 17:16:01.644  4953  5083 D BtGatt.GattService: onClientRegistered() - UUID=3db82b7e-feb0-4414-9b52-3e9787c607a4, clientIf=8
,06-09 17:16:01.654  9370  9380 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,06-09 17:16:01.654  4953  4967 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,06-09 17:16:01.654  9929  9929 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:16:01.654  9929  9929 D ActivityThread: Added TimaKeyStore provider
06-09 17:16:01.654  4953  4967 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-09 17:16:01.654  4953  4967 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:16:01.654  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
06-09 17:16:01.654  4953  5144 D BtGatt.AdvertiseManager: message : 0
,06-09 17:16:01.654  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
06-09 17:16:01.654  4953  5144 D BtGatt.AdvertiseManager: number of adv instance running = 0
,06-09 17:16:01.654  4953  5144 D BtGatt.AdvertiseManager: size of list is =0
,06-09 17:16:01.664  9529  9577 W Babel   : ayr TOOK TOO LONG! (15000ms > 10000ms)
,06-09 17:16:01.664  4953  5144 D BtGatt.AdvertiseManager: starting advertising
,06-09 17:16:01.674  4953  5171 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 33
06-09 17:16:01.674  4953  5171 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24950356
06-09 17:16:01.674  4953  5171 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
06-09 17:16:01.674  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-09 17:16:01.674  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
,06-09 17:16:01.674  3503  4293 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d03647 u0 register_intent_action qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{21aee74 9929:com.google.android.talk:matchstick/u0a112}
,06-09 17:16:01.684  4953  5144 D BtGatt.AdvertiseManager: isStandardAdv = false
,06-09 17:16:01.694  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{bd70f9d: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:01.694  9929  9929 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,06-09 17:16:01.694  4953  5083 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,06-09 17:16:01.694  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{5327de0: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:01.694  3503  4413 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-09 17:16:01.704  4953  5144 D BtGatt.AdvertiseManager: starting multi advertising
06-09 17:16:01.704  9929  9929 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-09 17:16:01.704  4953  5083 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
06-09 17:16:01.704  4953  5144 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
06-09 17:16:01.704  4953  5144 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
06-09 17:16:01.704  4953  5144 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
06-09 17:16:01.704  4953  5144 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
,06-09 17:16:01.704  9370  9381 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,06-09 17:16:01.704  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:01.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
06-09 17:16:01.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.704  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{41a0899: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:01.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.704  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:01.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
06-09 17:16:01.704  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
06-09 17:16:01.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:01.704  9929  9929 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:16:01.714  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.714  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.714  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:01.714  9370  9370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
06-09 17:16:01.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
06-09 17:16:01.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
06-09 17:16:01.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
06-09 17:16:01.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
06-09 17:16:01.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
06-09 17:16:01.714  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
06-09 17:16:01.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-09 17:16:01.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
06-09 17:16:01.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
06-09 17:16:01.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-09 17:16:01.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
06-09 17:16:01.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-09 17:16:01.714  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
06-09 17:16:01.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,06-09 17:16:01.724  3503  4209 V AlarmManager:  remove PendingIntent] PendingIntent{d0a775e: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:01.724  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
06-09 17:16:01.724  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
06-09 17:16:01.724  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
06-09 17:16:01.724  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
06-09 17:16:01.724  9370  9370 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,06-09 17:16:01.724  9929  9929 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:16:01.734  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{e71980c: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:01.744  9929  9929 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,06-09 17:16:01.744  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{7f99555: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:01.744  3503  4293 V AlarmManager:  remove PendingIntent] PendingIntent{582ab6a: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:01.754  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{6d9785b: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:01.824  9929  9929 D InjectionManager: InjectionManager
,06-09 17:16:01.824  9929  9929 D InjectionManager: fillFeatureStoreMap com.google.android.talk
06-09 17:16:01.824  9929  9929 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
06-09 17:16:01.824  9929  9929 I InjectionManager: featureStore :{}
,06-09 17:16:01.964  9929  9949 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } isPeriodic:false
,06-09 17:16:01.984  9929  9949 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,06-09 17:16:01.984  9929  9949 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:16:01.994  9929  9949 I InjectionManager: Inside getClassLibPath caller 
,06-09 17:16:02.014  9929  9949 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,06-09 17:16:02.104  9929  9949 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,06-09 17:16:02.144  9929  9949 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-09 17:16:02.144  9929  9949 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,06-09 17:16:02.154  3503  4209 I ActivityManager: Killing 9187:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #33
,06-09 17:16:02.184  3503  3524 D ActivityManager: cleanUpApplicationRecord -- 9187
,06-09 17:16:02.184  3503  3524 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,06-09 17:16:02.214  9370  9433 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
06-09 17:16:02.214  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
06-09 17:16:02.214  9370  9433 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,06-09 17:16:02.214  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
06-09 17:16:02.214  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
06-09 17:16:02.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
06-09 17:16:02.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
06-09 17:16:02.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
06-09 17:16:02.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
06-09 17:16:02.214  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
06-09 17:16:02.214  9370  9927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
06-09 17:16:02.214  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
06-09 17:16:02.214  9370  9927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
06-09 17:16:02.214  9370  9927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
06-09 17:16:02.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.214  9370  9370 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
06-09 17:16:02.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
06-09 17:16:02.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
06-09 17:16:02.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.214  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:02.224  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:02.224  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:02.224  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,06-09 17:16:02.224  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:02.224  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:02.224  9370  9433 D BluetoothLeScanner: could not find callback wrapper
06-09 17:16:02.224  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,06-09 17:16:02.234  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.234  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:02.234  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.234  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,06-09 17:16:02.234  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.234  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:02.234  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:02.234  9370  9433 D BluetoothLeAdvertiser: stop advertising
,06-09 17:16:02.254  4953  9505 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-09 17:16:02.254  4953  9505 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:16:02.254  4953  5144 D BtGatt.AdvertiseManager: message : 1
06-09 17:16:02.254  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,06-09 17:16:02.254  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
,06-09 17:16:02.254  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-09 17:16:02.254  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
06-09 17:16:02.254  4953  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
06-09 17:16:02.254  4953  5144 D BtGatt.AdvertiseManager: stop advertise for client =  8
,06-09 17:16:02.254  4953  5144 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,06-09 17:16:02.254  4953  5144 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,06-09 17:16:02.264  4953  5083 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
06-09 17:16:02.264  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{50b31d1: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:02.264  4953  5083 D BtGatt.GattService: Client app is not null!
06-09 17:16:02.264  9370  9380 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
06-09 17:16:02.264  4953  4967 D BtGatt.GattService: unregisterClient() - clientIf=8
,06-09 17:16:02.274  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,06-09 17:16:02.274  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.274  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{7981436: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:02.274  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
06-09 17:16:02.274  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.274  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.274  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.274  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
06-09 17:16:02.274  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
06-09 17:16:02.274  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,06-09 17:16:02.274  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:02.274  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.274  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
06-09 17:16:02.274  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.274  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:02.274  9370  9370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
06-09 17:16:02.284  9370  9370 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
06-09 17:16:02.284  9370  9370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
06-09 17:16:02.284  9370  9370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-09 17:16:02.284  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-09 17:16:02.284  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-09 17:16:02.284  9370  9370 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
06-09 17:16:02.284  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
06-09 17:16:02.284  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,06-09 17:16:02.284  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
06-09 17:16:02.284  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
06-09 17:16:02.284  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-09 17:16:02.284  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
06-09 17:16:02.284  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-09 17:16:02.284  9370  9370 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,06-09 17:16:02.284  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{9ad3f37: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:02.294  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{390dca4: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:02.294  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{2c01a0d: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:02.304  3503  4209 V AlarmManager:  remove PendingIntent] PendingIntent{6c93dc2: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:02.304  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{a8c97d3: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:02.314  3503  4293 V AlarmManager:  remove PendingIntent] PendingIntent{4511f10: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:02.784  9370  9370 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,06-09 17:16:03.184  3154  3609 D Netd    : Iface wlan0 link up
,06-09 17:16:03.184  9584  9584 I wpa_supplicant: nl80211: Received scan results (25 BSSes)
,06-09 17:16:03.184  5001  5016 D PdnController: Interface Changed wlan0 link up
,06-09 17:16:03.184  3503  3596 D Tethering: interfaceLinkStateChanged wlan0, true
06-09 17:16:03.184  9584  9584 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
06-09 17:16:03.184  3503  3596 D Tethering: interfaceStatusChanged wlan0, true
,06-09 17:16:03.194  3503  3853 D WifiP2pService: InactiveState{ what=147461 }
,06-09 17:16:03.194  3503  3853 D WifiP2pService: P2pEnabledState{ what=147461 }
06-09 17:16:03.194  3503  3853 D WifiP2pService: DefaultState{ what=147461 }
,06-09 17:16:03.224  3503  3503 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,06-09 17:16:03.234  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4614a09 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{13d0d1b 3933:com.android.systemui/u0a62}
,06-09 17:16:03.964  3503  3852 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,06-09 17:16:03.964  3503  3852 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,06-09 17:16:04.914  9811  9811 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-09 17:16:04.914  9811  9811 I dhcpcd  : wlan0: no IPv6 Routers available
,06-09 17:16:05.284  9370  9433 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,06-09 17:16:05.284  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
06-09 17:16:05.284  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
06-09 17:16:05.284  9370  9433 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
06-09 17:16:05.284  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
06-09 17:16:05.284  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-09 17:16:05.284  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,06-09 17:16:05.294  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,06-09 17:16:05.294  9370  9433 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
06-09 17:16:05.294  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,06-09 17:16:05.304  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.304  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.304  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.314  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:05.314  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,06-09 17:16:05.314  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.314  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:05.324  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,06-09 17:16:05.324  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
06-09 17:16:05.324  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,06-09 17:16:05.324  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.324  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.334  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.334  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.334  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:05.334  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
06-09 17:16:05.334  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
06-09 17:16:05.334  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 38436
06-09 17:16:05.344  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=38436, mManufacturerData=null, mManufacturerDataMask=null]
,06-09 17:16:05.344  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:05.344  9370  9433 D BluetoothLeScanner: Start Scan
,06-09 17:16:05.344  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.344  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.354  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.354  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.364  4953  9505 D BtGatt.GattService: registerClient() - UUID=ba57f933-bc95-4b11-a32a-8b85edccd5c9
,06-09 17:16:05.414  4953  5083 D BtGatt.GattService: onClientRegistered() - UUID=ba57f933-bc95-4b11-a32a-8b85edccd5c9, clientIf=8
,06-09 17:16:05.414  9370  9381 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=8
06-09 17:16:05.414  4953  4967 D BtGatt.GattService: start scan with filters
,06-09 17:16:05.414  4953  4967 D BtGatt.GattService: getScanSettings
,06-09 17:16:05.414  4953  4967 D BtGatt.GattService: Is it foreground application = true
,06-09 17:16:05.414  4953  4967 D BtGatt.GattService: not a background application
,06-09 17:16:05.424  4953  4967 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs 100/5)
,06-09 17:16:05.434  4953  4967 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-09 17:16:05.434  4953  4967 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-09 17:16:05.434  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
06-09 17:16:05.434  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
,06-09 17:16:05.434  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,06-09 17:16:05.434  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:05.434  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
06-09 17:16:05.434  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:05.434  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,06-09 17:16:05.434  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
06-09 17:16:05.434  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,06-09 17:16:05.434  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
06-09 17:16:05.434  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
06-09 17:16:05.434  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-09 17:16:05.434  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
06-09 17:16:05.434  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,06-09 17:16:05.434  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
06-09 17:16:05.434  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
06-09 17:16:05.444  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:05.444  4953  5161 D BtGatt.ScanManager: handling starting scan
06-09 17:16:05.444  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:05.444  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
06-09 17:16:05.444  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:05.444  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:05.444  4953  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest : 18
06-09 17:16:05.444  4953  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest, com.thaliproject.thalitest
06-09 17:16:05.444  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
06-09 17:16:05.444  4953  5161 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.444  4953  5161 D BluetoothAdapter: STATE_ON
,06-09 17:16:05.454  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{ecb7dc5: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.454  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,06-09 17:16:05.454  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
06-09 17:16:05.454  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
06-09 17:16:05.454  9370  9370 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.thaliproject.thalitest : 1
06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24950356
06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.thaliproject.thalitest : 2
06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
,06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 2 => 2
06-09 17:16:05.454  3503  4293 V AlarmManager:  remove PendingIntent] PendingIntent{854c31a: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-09 17:16:05.454  4953  5083 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=8, status=0, action=1
06-09 17:16:05.454  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
06-09 17:16:05.454  4953  5161 D BtGatt.ScanManager: set filter index= 7 for clientIf= 8
,06-09 17:16:05.454  4953  5161 D BtGatt.ScanManager: High Rssi Filter value is = -128
06-09 17:16:05.454  4953  5161 D BtGatt.ScanManager: Low Rssi Filter value is = -128
06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 2 => 2
06-09 17:16:05.454  4953  5161 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 2 => 2
,06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24950356
06-09 17:16:05.454  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 5
06-09 17:16:05.464  4953  5083 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=0, availableSpace=27
,06-09 17:16:05.464  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:05.464  4953  5161 D BtGatt.ScanManager: Starting BLE batch scan
06-09 17:16:05.464  4953  5161 D BtGatt.ScanManager: configuring batch scan storage, appIf 8
,06-09 17:16:05.464  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{fa52e4b: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.464  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 6 => 11
,06-09 17:16:05.474  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{671c028: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.474  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, A time : 5 => 10
,06-09 17:16:05.474  4953  5171 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.samsung.android.beaconmanager : 2
06-09 17:16:05.474  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-09 17:16:05.474  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 11 => 11
06-09 17:16:05.474  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@LowLatency, A time : 1 => 1
06-09 17:16:05.474  4953  5171 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.samsung.android.beaconmanager : 24950356
,06-09 17:16:05.474  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{deb3141: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.484  3503  4209 V AlarmManager:  remove PendingIntent] PendingIntent{f6bf6e6: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.484  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{2166427: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.494  4953  5083 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=8, status=0
,06-09 17:16:05.494  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,06-09 17:16:05.494  4953  5083 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=1
06-09 17:16:05.494  3503  4414 V AlarmManager:  remove PendingIntent] PendingIntent{336b6d4: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.494  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:05.494  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{5f8a07d: PendingIntentRecord{9709b72 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.504  3503  3981 V AlarmManager:  remove PendingIntent] PendingIntent{7b1bc3: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.504  3503  4415 V AlarmManager:  remove PendingIntent] PendingIntent{2b26c40: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.504  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{c73c779: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.514  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{4a8fcbe: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.514  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{1e9b11f: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.524  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{1720c6c: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:05.954  9370  9370 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,06-09 17:16:05.954  9370  9370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
06-09 17:16:05.954  9370  9370 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,06-09 17:16:06.494  3503  3811 V AlarmManager: Expired Alarm result :4
,06-09 17:16:06.504  4953  4953 D BtGatt.ScanManager: awakened up at time 322711
,06-09 17:16:06.504  4953  5161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-09 17:16:06.504  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{b7426ca: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:06.504  4953  5083 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
,06-09 17:16:06.504  3503  4414 V AlarmManager:  remove PendingIntent] PendingIntent{e82403b: PendingIntentRecord{9709b72 com.android.bluetooth broadcastIntent}}
06-09 17:16:06.504  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,06-09 17:16:06.534  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{5a98358: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:06.544  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{d41ecb1: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:07.174  7806  7806 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,06-09 17:16:07.174  7806  7806 D PreloadUpdateManagerStateMachine: exit::IDLE
06-09 17:16:07.174  7806  7806 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,06-09 17:16:07.174  7806  7806 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,06-09 17:16:07.174  7806  7806 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,06-09 17:16:07.184  7806  7806 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
06-09 17:16:07.184  7806  7806 D PreloadUpdateManagerStateMachine: entry::IDLE
,06-09 17:16:07.514  3503  3811 V AlarmManager: Expired Alarm result :4
,06-09 17:16:07.514  4953  4953 D BtGatt.ScanManager: awakened up at time 323725
,06-09 17:16:07.514  4953  5161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-09 17:16:07.524  3503  3981 V AlarmManager:  remove PendingIntent] PendingIntent{2df7d04: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:07.534  4953  5083 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=1
,06-09 17:16:07.534  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,06-09 17:16:07.534  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{657a2ed: PendingIntentRecord{9709b72 com.android.bluetooth broadcastIntent}}
06-09 17:16:07.534  4953  5083 D BtGatt.GattService: current time is 323742822845
06-09 17:16:07.534  4953  5083 D BtGatt.GattService: Batch record : [-8, -102, 99, -52, 44, 68, 1, -128, -88, 12, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0, 0]
,06-09 17:16:07.534  4953  5083 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0]
06-09 17:16:07.534  4953  5083 D ScanRecord: parseFromBytes
06-09 17:16:07.534  4953  5083 D ScanRecord: first manudata for manu ID
,06-09 17:16:07.544  9370  9381 D ScanRecord: parseFromBytes
06-09 17:16:07.544  9370  9381 D ScanRecord: first manudata for manu ID
06-09 17:16:07.544  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=44:2C:CC:63:9A:F8, mScanRecord=ScanRecord [mAdvertiseFlags=26, mServiceUuids=null, mManufacturerSpecificData={76=[16, 2, 11, 0]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-88, mTimestampNanos=323143580691}
,06-09 17:16:07.544  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{742c522: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:07.554  3503  4414 V AlarmManager:  remove PendingIntent] PendingIntent{9ca7bb3: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:07.554  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{c596570: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:07.564  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{39880e9: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:07.564  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{c6c116e: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.444  9370  9433 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
06-09 17:16:08.444  9370  9433 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
06-09 17:16:08.444  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
06-09 17:16:08.444  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-09 17:16:08.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:2C:E6"}
06-09 17:16:08.454  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:2C:E6"}
,06-09 17:16:08.454  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.454  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,06-09 17:16:08.464  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:2C:E6"}
,06-09 17:16:08.464  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:2C:E6"}
06-09 17:16:08.464  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.464  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
06-09 17:16:08.464  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 38436
06-09 17:16:08.464  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
06-09 17:16:08.464  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
06-09 17:16:08.464  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
06-09 17:16:08.464  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
06-09 17:16:08.464  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
06-09 17:16:08.464  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
06-09 17:16:08.464  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
06-09 17:16:08.464  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.464  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
,06-09 17:16:08.464  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.464  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.464  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
06-09 17:16:08.464  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,06-09 17:16:08.464  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.464  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.464  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.464  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:08.474  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:08.474  4953  5382 D BtGatt.GattService: flushPendingBatchResults - clientIf=8, isServer=false
06-09 17:16:08.474  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,06-09 17:16:08.474  4953  5161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-09 17:16:08.474  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:08.474  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{67200f: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:08.484  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:08.484  9370  9433 D BluetoothLeScanner: Stop Scan
06-09 17:16:08.484  4953  5083 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=1
,06-09 17:16:08.484  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:08.484  4953  5083 D BtGatt.GattService: current time is 324691208613
06-09 17:16:08.484  4953  5083 D BtGatt.GattService: Batch record : [-8, -102, 99, -52, 44, 68, 1, -128, -94, 3, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0, 0]
06-09 17:16:08.484  4953  5083 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0]
06-09 17:16:08.484  4953  5083 D ScanRecord: parseFromBytes
,06-09 17:16:08.484  4953  5083 D ScanRecord: first manudata for manu ID
06-09 17:16:08.484  9370  9380 D ScanRecord: parseFromBytes
06-09 17:16:08.484  9370  9380 D ScanRecord: first manudata for manu ID
06-09 17:16:08.484  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=44:2C:CC:63:9A:F8, mScanRecord=ScanRecord [mAdvertiseFlags=26, mServiceUuids=null, mManufacturerSpecificData={76=[16, 2, 11, 0]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-94, mTimestampNanos=324541394729}
06-09 17:16:08.484  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{247689c: PendingIntentRecord{9709b72 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.484  4953  4967 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,06-09 17:16:08.484  4953  4967 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:16:08.484  4953  4967 D BtGatt.GattService: stopScan() - queue size =2
06-09 17:16:08.484  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
06-09 17:16:08.484  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
,06-09 17:16:08.484  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-09 17:16:08.484  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
06-09 17:16:08.484  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 2 => 2
,06-09 17:16:08.484  4953  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_ACTUAL_DB
06-09 17:16:08.494  4953  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_REQUESTED_DB
,06-09 17:16:08.494  4953  5387 D BtGatt.GattService: unregisterClient() - clientIf=8
,06-09 17:16:08.494  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{eef42a5: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
06-09 17:16:08.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
06-09 17:16:08.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.494  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,06-09 17:16:08.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:08.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.494  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
06-09 17:16:08.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
06-09 17:16:08.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 38436
,06-09 17:16:08.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=38436, mManufacturerData=null, mManufacturerDataMask=null]
06-09 17:16:08.494  4953  5161 D BtGatt.ScanManager: filter size is 1
,06-09 17:16:08.494  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.494  9370  9433 D BluetoothLeScanner: Start Scan
06-09 17:16:08.494  4953  5161 D BtGatt.ScanManager: delete FilterIndex - 7
06-09 17:16:08.494  4953  5083 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=1, availableSpace=28
,06-09 17:16:08.494  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:08.494  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:08.494  4953  5161 D BtGatt.ScanManager: stopping BLe Batch
,06-09 17:16:08.504  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:08.504  4953  5083 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=0
06-09 17:16:08.504  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:08.504  4953  5161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
06-09 17:16:08.504  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:08.504  4953  5083 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
06-09 17:16:08.504  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{2cbd67a: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:08.504  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:08.504  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:08.504  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{87fae2b: PendingIntentRecord{9709b72 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.504  3503  4414 V AlarmManager:  remove PendingIntent] PendingIntent{5b07288: PendingIntentRecord{9709b72 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.514  4953  4967 D BtGatt.GattService: registerClient() - UUID=56997f3d-4629-4aab-ae17-e43eecd57e69
,06-09 17:16:08.514  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{c366421: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.514  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{830e046: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.524  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{d490207: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.524  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{f1e2f34: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.524  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{874215d: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.534  3503  4293 V AlarmManager:  remove PendingIntent] PendingIntent{68abad2: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.534  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{e69b7a3: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.544  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{4090aa0: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.544  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{d67659: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.554  4953  5083 D BtGatt.GattService: onClientRegistered() - UUID=56997f3d-4629-4aab-ae17-e43eecd57e69, clientIf=8
,06-09 17:16:08.554  9370  9910 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=8
06-09 17:16:08.554  3503  4414 V AlarmManager:  remove PendingIntent] PendingIntent{535b21e: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:08.554  4953  5382 D BtGatt.GattService: start scan with filters
,06-09 17:16:08.554  4953  5382 D BtGatt.GattService: getScanSettings
,06-09 17:16:08.554  4953  5382 D BtGatt.GattService: Is it foreground application = true
06-09 17:16:08.554  4953  5382 D BtGatt.GattService: not a background application
06-09 17:16:08.554  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{5562aff: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.564  4953  5382 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs 100/5)
,06-09 17:16:08.564  3503  4209 V AlarmManager:  remove PendingIntent] PendingIntent{70430cc: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.564  4953  5382 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:16:08.564  4953  5382 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:16:08.564  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
06-09 17:16:08.564  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
,06-09 17:16:08.574  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
06-09 17:16:08.574  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.574  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,06-09 17:16:08.574  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.574  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,06-09 17:16:08.574  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.574  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,06-09 17:16:08.574  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
06-09 17:16:08.574  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
06-09 17:16:08.574  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
06-09 17:16:08.584  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{d6f1f15: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:08.574  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-09 17:16:08.574  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-09 17:16:08.574  9370  9433 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
06-09 17:16:08.574  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
06-09 17:16:08.574  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-09 17:16:08.574  4953  5161 D BtGatt.ScanManager: handling starting scan
06-09 17:16:08.574  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
06-09 17:16:08.574  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
06-09 17:16:08.574  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
06-09 17:16:08.574  4953  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest : 19
,06-09 17:16:08.574  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
06-09 17:16:08.574  4953  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest, com.thaliproject.thalitest
,06-09 17:16:08.574  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
06-09 17:16:08.574  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
06-09 17:16:08.574  9370  9370 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,06-09 17:16:08.574  9370  9957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
06-09 17:16:08.574  4953  5161 D BluetoothAdapter: STATE_ON
06-09 17:16:08.584  9370  9957 D BluetoothSocket: bindListen(): myUserId = 0
06-09 17:16:08.584  9370  9957 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-09 17:16:08.584  4953  5161 D BluetoothAdapter: STATE_ON
,06-09 17:16:08.584  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,06-09 17:16:08.584  9370  9433 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
06-09 17:16:08.584  4953  5083 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=8, status=0, action=1
06-09 17:16:08.584  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:08.584  4953  5161 D BtGatt.ScanManager: set filter index= 8 for clientIf= 8
06-09 17:16:08.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.thaliproject.thalitest : 2
06-09 17:16:08.584  4953  5161 D BtGatt.ScanManager: High Rssi Filter value is = -128
06-09 17:16:08.584  4953  5161 D BtGatt.ScanManager: Low Rssi Filter value is = -128
06-09 17:16:08.604  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{306d22a: PendingIntentRecord{9709b72 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24950356
06-09 17:16:08.584  4953  5161 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
06-09 17:16:08.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.thaliproject.thalitest : 2
06-09 17:16:08.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
06-09 17:16:08.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-09 17:16:08.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
06-09 17:16:08.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 2 => 2
,06-09 17:16:08.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-09 17:16:08.584  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
06-09 17:16:08.584  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:08.584  4953  5083 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=0, availableSpace=27
06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 2 => 2
06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
06-09 17:16:08.604  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{46c781b: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:08.594  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-09 17:16:08.594  9370  9957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
,06-09 17:16:08.594  9370  9957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@8992e7d, port: 6, type: 1, local socket address: null, socket type: 0
06-09 17:16:08.594  4953  5161 D BtGatt.ScanManager: Starting BLE batch scan
06-09 17:16:08.594  4953  5161 D BtGatt.ScanManager: configuring batch scan storage, appIf 8
06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 2 => 2
,06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24950356
06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 11 => 11
06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@LowLatency, A time : 1 => 1
06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.samsung.android.beaconmanager : 2
06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 11 => 11
06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@LowLatency, A time : 1 => 1
06-09 17:16:08.594  4953  5171 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.samsung.android.beaconmanager : 24950356
06-09 17:16:08.594  4953  5083 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=8, status=0
06-09 17:16:08.594  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:08.594  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:08.594  4953  5083 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=1
06-09 17:16:08.594  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:08.604  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:08.604  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:08.624  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:08.624  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{ea98db8: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.624  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.624  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.624  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.634  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,06-09 17:16:08.634  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
06-09 17:16:08.634  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d35cbc72-f199-41c1-9eeb-d4ccb56ee509", Bluetooth MAC address: "44:78:3E:94:2C:E6"
06-09 17:16:08.634  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E 94 2C E6
06-09 17:16:08.634  9370  9433 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:16:08.634  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:16:08.634  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:08.634  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.634  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
06-09 17:16:08.634  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
06-09 17:16:08.634  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.634  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.634  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d35cbc72-f199-41c1-9eeb-d4ccb56ee509], mManufacturerSpecificData={}, mServiceData={d35cbc72-f199-41c1-9eeb-d4ccb56ee509=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:08.634  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:08.634  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:08.634  9370  9433 D BluetoothLeAdvertiser: start advertising
,06-09 17:16:08.634  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:08.644  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{baf9791: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.644  4953  5387 D BtGatt.GattService: registerClient() - UUID=3a9dd1c9-e5eb-4d67-bf11-81ab747d9d1d
,06-09 17:16:08.654  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{517e6f6: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.654  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{bd07af7: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.664  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{f45cd64: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.664  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{4a51bcd: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.664  3503  3981 V AlarmManager:  remove PendingIntent] PendingIntent{6537c82: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.674  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{7cf93: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.674  3503  4415 V AlarmManager:  remove PendingIntent] PendingIntent{3445bd0: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.674  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{af4a7c9: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.684  3503  4209 V AlarmManager:  remove PendingIntent] PendingIntent{3c0dece: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.684  3503  4414 V AlarmManager:  remove PendingIntent] PendingIntent{e55d1ef: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.684  4953  5083 D BtGatt.GattService: onClientRegistered() - UUID=3a9dd1c9-e5eb-4d67-bf11-81ab747d9d1d, clientIf=9
,06-09 17:16:08.684  9370  9910 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=9
,06-09 17:16:08.694  4953  4967 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,06-09 17:16:08.694  4953  4967 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:16:08.694  4953  4967 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:16:08.694  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
06-09 17:16:08.694  4953  5144 D BtGatt.AdvertiseManager: message : 0
,06-09 17:16:08.694  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
06-09 17:16:08.694  4953  5144 D BtGatt.AdvertiseManager: number of adv instance running = 0
06-09 17:16:08.694  4953  5144 D BtGatt.AdvertiseManager: size of list is =0
,06-09 17:16:08.694  4953  5144 D BtGatt.AdvertiseManager: starting advertising
,06-09 17:16:08.694  4953  5144 D BtGatt.AdvertiseManager: isStandardAdv = false
,06-09 17:16:08.704  4953  5171 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 34
,06-09 17:16:08.704  4953  5171 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24950356
06-09 17:16:08.704  4953  5171 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
06-09 17:16:08.704  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{e5b64fc: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.704  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-09 17:16:08.704  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
,06-09 17:16:08.704  4953  5083 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=9, status=0
,06-09 17:16:08.704  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{c96f785: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.704  4953  5144 D BtGatt.AdvertiseManager: starting multi advertising
,06-09 17:16:08.704  4953  5083 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=9, status=0
06-09 17:16:08.704  4953  5144 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
06-09 17:16:08.704  4953  5144 D BtGatt.AdvertiseManager: clientIf: 9, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,06-09 17:16:08.704  4953  5144 D BtGatt.AdvertiseManager: postCallback clientIf = 9 status = 0
06-09 17:16:08.704  4953  5144 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=9, status=0, isStart=true
06-09 17:16:08.704  9370  9380 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
06-09 17:16:08.704  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:08.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
06-09 17:16:08.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.704  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:08.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
06-09 17:16:08.704  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
06-09 17:16:08.704  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
06-09 17:16:08.714  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
06-09 17:16:08.714  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:08.714  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{19019da: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.714  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:08.714  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:08.714  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:08.714  9370  9370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
06-09 17:16:08.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
06-09 17:16:08.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
06-09 17:16:08.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
06-09 17:16:08.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
06-09 17:16:08.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,06-09 17:16:08.714  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
06-09 17:16:08.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-09 17:16:08.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
,06-09 17:16:08.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
06-09 17:16:08.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-09 17:16:08.714  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{ad79e0b: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:08.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
,06-09 17:16:08.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-09 17:16:08.714  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
06-09 17:16:08.714  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
06-09 17:16:08.724  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
06-09 17:16:08.724  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
06-09 17:16:08.724  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
06-09 17:16:08.724  9370  9370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
06-09 17:16:08.724  9370  9370 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,06-09 17:16:08.724  3503  3981 V AlarmManager:  remove PendingIntent] PendingIntent{777d4e8: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.724  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{4548701: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.734  3503  4415 V AlarmManager:  remove PendingIntent] PendingIntent{4e5f9a6: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:08.734  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{4600fe7: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:09.224  9370  9370 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,06-09 17:16:09.224  9370  9370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
06-09 17:16:09.224  9370  9370 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,06-09 17:16:09.394  3503  6040 D SSRM:n  : SIOP:: AP = 310, PST = 330 (W:14), CP = 264, CUR = -44, LCD = 40
,06-09 17:16:09.614  3503  3811 V AlarmManager: Expired Alarm result :4
,06-09 17:16:09.614  4953  4953 D BtGatt.ScanManager: awakened up at time 325821
,06-09 17:16:09.614  4953  5161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-09 17:16:09.624  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{701923d: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:09.624  4953  5083 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=1
06-09 17:16:09.624  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,06-09 17:16:09.624  4953  5083 D BtGatt.GattService: current time is 325835758266
06-09 17:16:09.624  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{e680a32: PendingIntentRecord{9709b72 com.android.bluetooth broadcastIntent}}
06-09 17:16:09.624  4953  5083 D BtGatt.GattService: Batch record : [-8, -102, 99, -52, 44, 68, 1, -128, -97, 16, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0, 0]
06-09 17:16:09.624  4953  5083 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0]
06-09 17:16:09.624  4953  5083 D ScanRecord: parseFromBytes
06-09 17:16:09.624  4953  5083 D ScanRecord: first manudata for manu ID
06-09 17:16:09.624  9370  9910 D ScanRecord: parseFromBytes
06-09 17:16:09.624  9370  9910 D ScanRecord: first manudata for manu ID
06-09 17:16:09.624  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=44:2C:CC:63:9A:F8, mScanRecord=ScanRecord [mAdvertiseFlags=26, mServiceUuids=null, mManufacturerSpecificData={76=[16, 2, 11, 0]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-97, mTimestampNanos=325036052497}
,06-09 17:16:09.634  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{a13c383: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:09.644  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{a4e5900: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:09.644  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{87a1539: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:09.654  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{188977e: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:09.664  3503  3981 V AlarmManager:  remove PendingIntent] PendingIntent{ec514df: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:10.634  3503  3811 V AlarmManager: Expired Alarm result :4
,06-09 17:16:10.634  4953  4953 D BtGatt.ScanManager: awakened up at time 326846
,06-09 17:16:10.634  4953  5161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-09 17:16:10.644  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{45dcbf5: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:10.644  4953  5083 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=1
06-09 17:16:10.644  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,06-09 17:16:10.644  4953  5083 D BtGatt.GattService: current time is 326859863035
06-09 17:16:10.654  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{492ad8a: PendingIntentRecord{9709b72 com.android.bluetooth broadcastIntent}}
06-09 17:16:10.654  4953  5083 D BtGatt.GattService: Batch record : [-8, -102, 99, -52, 44, 68, 1, -128, -90, 9, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0, 0]
,06-09 17:16:10.654  4953  5083 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0]
06-09 17:16:10.654  4953  5083 D ScanRecord: parseFromBytes
06-09 17:16:10.654  4953  5083 D ScanRecord: first manudata for manu ID
06-09 17:16:10.654  9370  9381 D ScanRecord: parseFromBytes
06-09 17:16:10.654  9370  9381 D ScanRecord: first manudata for manu ID
06-09 17:16:10.654  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=44:2C:CC:63:9A:F8, mScanRecord=ScanRecord [mAdvertiseFlags=26, mServiceUuids=null, mManufacturerSpecificData={76=[16, 2, 11, 0]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-90, mTimestampNanos=326410327496}
,06-09 17:16:10.664  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{6101ffb: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:10.674  3503  4415 V AlarmManager:  remove PendingIntent] PendingIntent{5be4818: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:10.684  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{68c3271: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:10.694  3503  4209 V AlarmManager:  remove PendingIntent] PendingIntent{5761856: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:10.704  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{736c0d7: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.654  3503  3811 V AlarmManager: Expired Alarm result :4
,06-09 17:16:11.654  4953  4953 D BtGatt.ScanManager: awakened up at time 327869
,06-09 17:16:11.664  4953  5161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-09 17:16:11.664  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{f6084ad: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.674  4953  5083 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
,06-09 17:16:11.674  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:11.674  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{f5363e2: PendingIntentRecord{9709b72 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.684  3503  4293 V AlarmManager:  remove PendingIntent] PendingIntent{1bc9373: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.694  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{2a0230: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.714  9370  9433 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,06-09 17:16:11.714  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-09 17:16:11.724  9370  9433 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
06-09 17:16:11.724  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
06-09 17:16:11.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
06-09 17:16:11.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
06-09 17:16:11.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,06-09 17:16:11.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
06-09 17:16:11.724  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-09 17:16:11.724  9370  9957 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
06-09 17:16:11.724  9370  9370 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
06-09 17:16:11.724  9370  9957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
06-09 17:16:11.724  9370  9433 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e077c2f removed from the list
06-09 17:16:11.724  9370  9957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
06-09 17:16:11.724  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e077c2f removed from the list
,06-09 17:16:11.724  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-09 17:16:11.724  9370  9433 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
06-09 17:16:11.724  9370  9370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
06-09 17:16:11.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.724  9370  9370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
06-09 17:16:11.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
06-09 17:16:11.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
06-09 17:16:11.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:11.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.724  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
06-09 17:16:11.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.724  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:11.724  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:11.724  4953  4969 D BtGatt.GattService: flushPendingBatchResults - clientIf=8, isServer=false
,06-09 17:16:11.724  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
06-09 17:16:11.724  4953  5161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-09 17:16:11.724  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:11.734  4953  5083 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
,06-09 17:16:11.734  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{fadbea9: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:11.734  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,06-09 17:16:11.734  3503  4415 V AlarmManager:  remove PendingIntent] PendingIntent{cc7dc2e: PendingIntentRecord{9709b72 com.android.bluetooth broadcastIntent}}
06-09 17:16:11.734  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:11.734  9370  9433 D BluetoothLeScanner: Stop Scan
,06-09 17:16:11.744  4953  9505 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:16:11.744  4953  9505 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:16:11.744  4953  9505 D BtGatt.GattService: stopScan() - queue size =2
06-09 17:16:11.744  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
06-09 17:16:11.744  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
,06-09 17:16:11.744  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
06-09 17:16:11.744  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
06-09 17:16:11.744  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 2 => 2
06-09 17:16:11.744  3503  4414 V AlarmManager:  remove PendingIntent] PendingIntent{fc2f3cf: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:11.744  4953  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_ACTUAL_DB
06-09 17:16:11.744  4953  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_REQUESTED_DB
,06-09 17:16:11.744  4953  5387 D BtGatt.GattService: unregisterClient() - clientIf=8
06-09 17:16:11.744  4953  5161 D BtGatt.ScanManager: filter size is 1
06-09 17:16:11.744  4953  5161 D BtGatt.ScanManager: delete FilterIndex - 8
,06-09 17:16:11.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
06-09 17:16:11.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,06-09 17:16:11.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.744  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,06-09 17:16:11.744  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.744  4953  5083 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=1, availableSpace=28
06-09 17:16:11.744  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,06-09 17:16:11.744  4953  5161 D BtGatt.ScanManager: stopping BLe Batch
06-09 17:16:11.744  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:11.744  4953  5083 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=0
06-09 17:16:11.744  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:11.744  4953  5161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,06-09 17:16:11.754  4953  5083 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
06-09 17:16:11.754  4953  5083 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
06-09 17:16:11.754  9370  9433 D BluetoothAdapter: STATE_ON
06-09 17:16:11.754  9370  9433 D BluetoothLeAdvertiser: stop advertising
06-09 17:16:11.754  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{d65115c: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:11.754  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{87a9c65: PendingIntentRecord{9709b72 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.754  3503  4413 V AlarmManager:  remove PendingIntent] PendingIntent{2f98d3a: PendingIntentRecord{9709b72 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.754  4953  4969 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:16:11.754  4953  4969 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
06-09 17:16:11.754  4953  5171 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
06-09 17:16:11.754  4953  5171 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 9, currDate: 9
06-09 17:16:11.754  4953  5171 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
06-09 17:16:11.754  4953  5171 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 2 => 2
06-09 17:16:11.754  4953  5171 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
06-09 17:16:11.754  4953  5144 D BtGatt.AdvertiseManager: message : 1
,06-09 17:16:11.754  3503  4209 V AlarmManager:  remove PendingIntent] PendingIntent{224fdeb: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:11.754  4953  5144 D BtGatt.AdvertiseManager: stop advertise for client =  9
06-09 17:16:11.754  4953  5144 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 9
,06-09 17:16:11.764  4953  5144 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,06-09 17:16:11.764  4953  5083 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=9, status=0
06-09 17:16:11.764  4953  5083 D BtGatt.GattService: Client app is not null!
06-09 17:16:11.764  9370  9381 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
06-09 17:16:11.764  4953  5382 D BtGatt.GattService: unregisterClient() - clientIf=9
,06-09 17:16:11.764  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{ddfe748: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.764  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,06-09 17:16:11.764  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.764  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
06-09 17:16:11.764  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.764  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:11.764  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.764  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
06-09 17:16:11.764  9370  9433 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
06-09 17:16:11.764  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-09 17:16:11.764  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.774  3503  4414 V AlarmManager:  remove PendingIntent] PendingIntent{a7d99e1: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:11.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:11.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
06-09 17:16:11.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
,06-09 17:16:11.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
06-09 17:16:11.774  9370  9433 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c60623c removed from the list
06-09 17:16:11.774  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-09 17:16:11.774  9370  9433 D io.jxcore.node.ConnectivityMonitor: stop
06-09 17:16:11.774  9370  9433 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,06-09 17:16:11.774  9370  9433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-09 17:16:11.774  9370  9370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
06-09 17:16:11.774  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
06-09 17:16:11.774  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-09 17:16:11.774  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
06-09 17:16:11.774  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
06-09 17:16:11.774  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
06-09 17:16:11.774  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
06-09 17:16:11.774  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-09 17:16:11.774  3503  4209 V AlarmManager:  remove PendingIntent] PendingIntent{1634306: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:11.774  9370  9370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
06-09 17:16:11.774  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
06-09 17:16:11.774  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
06-09 17:16:11.774  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
06-09 17:16:11.774  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,06-09 17:16:11.774  9370  9370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
06-09 17:16:11.774  9370  9370 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
06-09 17:16:11.774  9370  9433 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
06-09 17:16:11.774  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
06-09 17:16:11.774  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
06-09 17:16:11.774  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
06-09 17:16:11.774  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,06-09 17:16:11.774  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
06-09 17:16:11.774  9370  9433 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
06-09 17:16:11.774  9370  9433 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
06-09 17:16:11.774  9370  9433 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
06-09 17:16:11.774  9370  9433 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
06-09 17:16:11.774  9370  9433 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,06-09 17:16:11.774  3503  4415 V AlarmManager:  remove PendingIntent] PendingIntent{2538dc7: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
06-09 17:16:11.784  9370  9433 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,06-09 17:16:11.784  9370  9433 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,06-09 17:16:11.784  9370  9433 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
06-09 17:16:11.784  9370  9433 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,06-09 17:16:11.784  3503  4408 V AlarmManager:  remove PendingIntent] PendingIntent{1b02ff4: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.784  3503  4403 V AlarmManager:  remove PendingIntent] PendingIntent{158f31d: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.794  3503  4279 V AlarmManager:  remove PendingIntent] PendingIntent{2608992: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.794  3503  3981 V AlarmManager:  remove PendingIntent] PendingIntent{5f13f63: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.794  3503  3975 V AlarmManager:  remove PendingIntent] PendingIntent{29a5760: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.804  3503  4845 V AlarmManager:  remove PendingIntent] PendingIntent{696a419: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.804  3503  3848 V AlarmManager:  remove PendingIntent] PendingIntent{879acde: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.814  3503  4412 V AlarmManager:  remove PendingIntent] PendingIntent{2e6ebf: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.814  3503  4293 V AlarmManager:  remove PendingIntent] PendingIntent{3d898c: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.824  3503  3524 V AlarmManager:  remove PendingIntent] PendingIntent{86468d5: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.824  3503  3525 V AlarmManager:  remove PendingIntent] PendingIntent{46fb8ea: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:11.834  3503  4208 V AlarmManager:  remove PendingIntent] PendingIntent{ce537db: PendingIntentRecord{4ceb5 com.android.bluetooth broadcastIntent}}
,06-09 17:16:12.274  9370  9370 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,06-09 17:16:13.784  9370  9433 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,06-09 17:16:13.794  3503  6076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-09 17:16:13.944  9370  9962 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 270, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:13.944  9370  9962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:13.944  9370  9962 D io.jxcore.node.StreamCopyingThread:  id: 83
,06-09 17:16:14.714  9370  9962 W !!      : call onHalfStreamCopied
06-09 17:16:14.714  9370  9962 I testCopyDataAndClose: closing input stream
,06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 270, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread:  id: 83
06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread:  id: 83
06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 270, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:15.404  9370  9962 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,06-09 17:16:17.494  3503  4414 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-09 17:16:17.494  3503  4414 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4292, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-09 17:16:17.494  3503  4414 D BatteryService: online:4, current avg:-84, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-372
06-09 17:16:17.494  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-09 17:16:17.504  3503  3503 I MotionRecognitionService: Plugged
,06-09 17:16:17.504  3503  3503 D MotionRecognitionService:   cableConnection= 1
06-09 17:16:17.504  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-09 17:16:17.504  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,06-09 17:16:17.504  3503  3857 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-09 17:16:17.514  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-09 17:16:17.514  3933  3933 D KeyguardUpdateMonitor: handleBatteryUpdate
06-09 17:16:17.514  3933  3933 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-09 17:16:17.524  5001  5001 D CommonServiceConfiguration: getStringValueSetting
,06-09 17:16:17.534  5001  5001 D BatteryMonitor: new battery level: 100
,06-09 17:16:17.534  4953  4953 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-09 17:16:17.534  4953  9461 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-09 17:16:17.544  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-09 17:16:17.544  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-09 17:16:17.904  9370  9433 I StreamCopyingThreadTest: Starting test: testCopyBigData
,06-09 17:16:17.954  9370  9965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 273, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:17.954  9370  9965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:17.954  9370  9965 D io.jxcore.node.StreamCopyingThread:  id: 85
,06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 273, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread:  id: 85
06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread:  id: 85
06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 273, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:19.404  9370  9965 D io.jxcore.node.StreamCopyingThread:  id: 85 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,06-09 17:16:19.414  3503  6040 D SSRM:n  : SIOP:: AP = 360, PST = 332 (W:6), CP = 264, CUR = -84, LCD = 40
,06-09 17:16:21.844  9370  9433 I StreamCopyingThreadTest: Starting test: testRunNotify
,06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 275, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread:  id: 86
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 275, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread:  id: 86
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread:  id: 86
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 275, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:21.844  9370  9966 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
06-09 17:16:21.844  9370  9433 I StreamCopyingThreadTest: Starting test: testSetBufferSize
06-09 17:16:21.844  9370  9433 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
06-09 17:16:21.844  9370  9433 I StreamCopyingThreadTest: Starting test: testRunWithException
06-09 17:16:21.844  9370  9967 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 279, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:21.844  9370  9967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:21.844  9370  9967 D io.jxcore.node.StreamCopyingThread:  id: 89
06-09 17:16:21.844  9370  9967 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 279, thread name: My test thread name): Test exception.
06-09 17:16:21.844  9370  9967 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 279, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:21.844  9370  9967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:21.844  9370  9967 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
06-09 17:16:21.844  9370  9967 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
06-09 17:16:21.844  9370  9967 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 279, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
06-09 17:16:21.844  9370  9967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
06-09 17:16:21.844  9370  9967 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
06-09 17:16:21.844  9370  9433 I jxcore-log: 2017-06-09 15:16:21 - DEBUG UnitTest_app: 'Running unit tests'
06-09 17:16:21.844  9370  9433 I jxcore-log: 
06-09 17:16:21.844  9370  9433 I jxcore-log: *Native ,tests were executed*
06-09 17:16:21.844  9370  9433 I jxcore-log: 
06-09 17:16:21.844  9370  9433 I jxcore-log: Total number of executed tests:  78
06-09 17:16:21.844  9370  9433 I jxcore-log: 
06-09 17:16:21.844  9370  9433 I jxcore-log: Number of passed tests:  76
06-09 17:16:21.844  9370  9433 I jxcore-log: 
06-09 17:16:21.844  9370  9433 I jxcore-log: Number of failed tests:  0
06-09 17:16:21.844  9370  9433 I jxcore-log: 
06-09 17:16:21.844  9370  9433 I jxcore-log: Number of ignored tests:  2
06-09 17:16:21.844  9370  9433 I jxcore-log: 
06-09 17:16:21.844  9370  9433 I jxcore-log: Total duration:  44855
06-09 17:16:21.844  9370  9433 I jxcore-log: 
06-09 17:16:21.844  9370  9433 I jxcore-log: 2017-06-09 15:16:21 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G930F''
06-09 17:16:21.844  9370  9433 I jxcore-log: 
06-09 17:16:21.844  9370  9433 I jxcore-log: 2017-06-09 15:16:21 - WARN testUtils: 'myNameCallback not set!'
06-09 17:16:21.844  9370  9433 I jxcore-log: 
,06-09 17:16:23.314  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
06-09 17:16:23.314  9370  9433 I jxcore-log: 
,06-09 17:16:23.324  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
06-09 17:16:23.324  9370  9433 I jxcore-log: 
,06-09 17:16:23.334  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
06-09 17:16:23.334  9370  9433 I jxcore-log: 
,06-09 17:16:23.444  8642  8687 W PlayEventLogger: No account for auth token provided
,06-09 17:16:23.444  8642  8687 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-09 17:16:23.444  8642  8687 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-09 17:16:23.454  3154  3612 D EnterpriseController: netId is 0
,06-09 17:16:23.454  3154  3612 D Netd    : getNetworkForDns: using netid 503 for uid 10032
,06-09 17:16:23.494  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
06-09 17:16:23.494  9370  9433 I jxcore-log: 
,06-09 17:16:23.524  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
06-09 17:16:23.524  9370  9433 I jxcore-log: 
,06-09 17:16:23.534  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testTests.js'
06-09 17:16:23.534  9370  9433 I jxcore-log: 
,06-09 17:16:23.564  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testUsn.js'
06-09 17:16:23.564  9370  9433 I jxcore-log: 
,06-09 17:16:23.584  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
06-09 17:16:23.584  9370  9433 I jxcore-log: 
,06-09 17:16:23.584  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
06-09 17:16:23.584  9370  9433 I jxcore-log: 
,06-09 17:16:23.634  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
06-09 17:16:23.634  9370  9433 I jxcore-log: 
,06-09 17:16:23.644  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
06-09 17:16:23.644  9370  9433 I jxcore-log: 
,06-09 17:16:23.644  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
06-09 17:16:23.644  9370  9433 I jxcore-log: 
,06-09 17:16:23.644  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
06-09 17:16:23.644  9370  9433 I jxcore-log: 
,06-09 17:16:23.854  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
06-09 17:16:23.854  9370  9433 I jxcore-log: 
,06-09 17:16:23.954  9370  9433 I jxcore-log: 2017-06-09 15:16:23 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
06-09 17:16:23.954  9370  9433 I jxcore-log: 
,06-09 17:16:24.024  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
06-09 17:16:24.024  9370  9433 I jxcore-log: 
,06-09 17:16:24.034  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
06-09 17:16:24.034  9370  9433 I jxcore-log: 
,06-09 17:16:24.044  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
06-09 17:16:24.044  9370  9433 I jxcore-log: 
,06-09 17:16:24.074  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
06-09 17:16:24.074  9370  9433 I jxcore-log: 
,06-09 17:16:24.114  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
06-09 17:16:24.114  9370  9433 I jxcore-log: 
,06-09 17:16:24.144  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
06-09 17:16:24.144  9370  9433 I jxcore-log: 
,06-09 17:16:24.174  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
06-09 17:16:24.174  9370  9433 I jxcore-log: 
,06-09 17:16:24.184  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
06-09 17:16:24.184  9370  9433 I jxcore-log: 
,06-09 17:16:24.224  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
06-09 17:16:24.224  9370  9433 I jxcore-log: 
,06-09 17:16:24.254  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
06-09 17:16:24.254  9370  9433 I jxcore-log: 
,06-09 17:16:24.844  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
06-09 17:16:24.844  9370  9433 I jxcore-log: 
,06-09 17:16:24.864  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
06-09 17:16:24.864  9370  9433 I jxcore-log: 
,06-09 17:16:24.874  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
06-09 17:16:24.874  9370  9433 I jxcore-log: 
,06-09 17:16:24.874  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
06-09 17:16:24.874  9370  9433 I jxcore-log: 
,06-09 17:16:24.894  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
06-09 17:16:24.894  9370  9433 I jxcore-log: 
,06-09 17:16:24.914  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
06-09 17:16:24.914  9370  9433 I jxcore-log: 
,06-09 17:16:24.924  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
06-09 17:16:24.924  9370  9433 I jxcore-log: 
,06-09 17:16:24.934  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
06-09 17:16:24.934  9370  9433 I jxcore-log: 
,06-09 17:16:24.944  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
06-09 17:16:24.944  9370  9433 I jxcore-log: 
,06-09 17:16:24.944  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
06-09 17:16:24.944  9370  9433 I jxcore-log: 
,06-09 17:16:24.964  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
06-09 17:16:24.964  9370  9433 I jxcore-log: 
,06-09 17:16:24.974  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
06-09 17:16:24.974  9370  9433 I jxcore-log: 
,06-09 17:16:24.984  9370  9433 I jxcore-log: 2017-06-09 15:16:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
06-09 17:16:24.984  9370  9433 I jxcore-log: 
,06-09 17:16:25.074  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
06-09 17:16:25.074  9370  9433 I jxcore-log: 
,06-09 17:16:25.244  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testHttp.js'
06-09 17:16:25.244  9370  9433 I jxcore-log: 
,06-09 17:16:25.254  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
06-09 17:16:25.254  9370  9433 I jxcore-log: 
,06-09 17:16:25.264  9370  9433 D BluetoothAdapter: STATE_ON
,06-09 17:16:25.264  9370  9433 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,06-09 17:16:25.264  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - INFO testUtils: 'BLE multiple advertisement supported'
06-09 17:16:25.264  9370  9433 I jxcore-log: 
06-09 17:16:25.274  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
06-09 17:16:25.274  9370  9433 I jxcore-log: 
,06-09 17:16:25.274  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
06-09 17:16:25.274  9370  9433 I jxcore-log: 
,06-09 17:16:25.274  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
06-09 17:16:25.274  9370  9433 I jxcore-log: 
06-09 17:16:25.274  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
06-09 17:16:25.274  9370  9433 I jxcore-log: 
06-09 17:16:25.274  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
06-09 17:16:25.274  9370  9433 I jxcore-log: 
06-09 17:16:25.274  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
06-09 17:16:25.274  9370  9433 I jxcore-log: 
,06-09 17:16:25.274  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
06-09 17:16:25.274  9370  9433 I jxcore-log: 
06-09 17:16:25.274  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
06-09 17:16:25.274  9370  9433 I jxcore-log: 
06-09 17:16:25.284  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
06-09 17:16:25.284  9370  9433 I jxcore-log: 
06-09 17:16:25.284  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
06-09 17:16:25.284  9370  9433 I jxcore-log: 
06-09 17:16:25.284  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
06-09 17:16:25.284  9370  9433 I jxcore-log: 
,06-09 17:16:25.284  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
06-09 17:16:25.284  9370  9433 I jxcore-log: 
06-09 17:16:25.284  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
06-09 17:16:25.284  9370  9433 I jxcore-log: 
,06-09 17:16:25.284  9370  9370 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
06-09 17:16:25.284  9370  9370 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,06-09 17:16:25.314  9370  9433 I jxcore-log: 2017-06-09 15:16:25 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
06-09 17:16:25.314  9370  9433 I jxcore-log: 
,06-09 17:16:27.604  3503  4130 E Watchdog: !@Sync 11 [06-09 17:16:27.617]
,06-09 17:16:28.354  9370  9433 I jxcore-log: 2017-06-09 15:16:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect EHOSTUNREACH', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-09 17:16:28.354  9370  9433 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-09 17:16:28.354  9370  9433 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-09 17:16:28.354  9370  9433 I jxcore-log: emit@events.js:82:1
06-09 17:16:28.354  9370  9433 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-09 17:16:28.354  9370  9433 I jxcore-log: emit@events.js:82:1''
06-09 17:16:28.354  9370  9433 I jxcore-log: 
,06-09 17:16:29.434  3503  6040 D SSRM:n  : SIOP:: AP = 370, PST = 336 (W:6), CP = 278, CUR = -84, LCD = 40
,06-09 17:16:31.354  9370  9433 I jxcore-log: 2017-06-09 15:16:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect EHOSTUNREACH', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-09 17:16:31.354  9370  9433 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-09 17:16:31.354  9370  9433 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-09 17:16:31.354  9370  9433 I jxcore-log: emit@events.js:82:1
06-09 17:16:31.354  9370  9433 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-09 17:16:31.354  9370  9433 I jxcore-log: emit@events.js:82:1''
06-09 17:16:31.354  9370  9433 I jxcore-log: 
,06-09 17:16:31.364  9370  9433 I jxcore-log: 2017-06-09 15:16:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect EHOSTUNREACH', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
06-09 17:16:31.364  9370  9433 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
06-09 17:16:31.364  9370  9433 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
06-09 17:16:31.364  9370  9433 I jxcore-log: emit@events.js:82:1
06-09 17:16:31.364  9370  9433 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
06-09 17:16:31.364  9370  9433 I jxcore-log: emit@events.js:82:1''
06-09 17:16:31.364  9370  9433 I jxcore-log: 
,06-09 17:16:33.794  3503  6076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-09 17:16:39.464  3503  6040 D SSRM:n  : SIOP:: AP = 330, PST = 336 (W:14), CP = 275, CUR = -84, LCD = 40
,06-09 17:16:47.544  3503  3848 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-09 17:16:47.544  3503  3848 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-09 17:16:47.544  3503  3848 D BatteryService: online:4, current avg:-28, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-09 17:16:47.544  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-09 17:16:47.544  3503  3503 I MotionRecognitionService: Plugged
06-09 17:16:47.544  3503  3503 D MotionRecognitionService:   cableConnection= 1
06-09 17:16:47.544  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-09 17:16:47.544  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,06-09 17:16:47.554  3503  3857 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-09 17:16:47.554  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-09 17:16:47.554  3933  3933 D KeyguardUpdateMonitor: handleBatteryUpdate
06-09 17:16:47.564  3933  3933 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-09 17:16:47.574  5001  5001 D CommonServiceConfiguration: getStringValueSetting
,06-09 17:16:47.594  5001  5001 D BatteryMonitor: new battery level: 100
06-09 17:16:47.594  4953  4953 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-09 17:16:47.594  4953  9461 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-09 17:16:47.594  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-09 17:16:47.594  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-09 17:16:47.834  3503  3811 V AlarmManager: Expired Alarm result :4
,06-09 17:16:48.594  9370  9433 I jxcore-log: 2017-06-09 15:16:48 - DEBUG CoordinatedClient: 'reconnected to the test server'
06-09 17:16:48.594  9370  9433 I jxcore-log: 
,06-09 17:16:48.604  9370  9433 I jxcore-log: 2017-06-09 15:16:48 - DEBUG CoordinatedClient: 'connected to the test server'
06-09 17:16:48.604  9370  9433 I jxcore-log: 
,06-09 17:16:49.484  3503  6040 D SSRM:n  : SIOP:: AP = 320, PST = 332 (W:14), CP = 269, CUR = -28, LCD = 40
,06-09 17:16:53.794  3503  6076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-09 17:16:57.604  3503  4130 E Watchdog: !@Sync 12 [06-09 17:16:57.619]
,06-09 17:16:59.224  4303  4437 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-09 17:16:59.224  4303  4437 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-09 17:16:59.514  3503  6040 D SSRM:n  : SIOP:: AP = 310, PST = 331 (W:14), CP = 266, CUR = -28, LCD = 40
,06-09 17:16:59.984  3503  3811 V AlarmManager: Expired Alarm result :8
,06-09 17:16:59.994  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-09 17:16:59.994  3933  3933 D KeyguardUpdateMonitor: handleTimeUpdate
,06-09 17:17:00.014  3933  3933 D Clock   : received broadcast android.intent.action.TIME_TICK
,06-09 17:17:00.104  3933  3933 D DateView: received broadcast android.intent.action.TIME_TICK
,06-09 17:17:00.134  4627  4627 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,06-09 17:17:00.144  4627  4627 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,06-09 17:17:00.144  4627  4627 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,06-09 17:17:00.144  4627  4627 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,06-09 17:17:00.144  4627  4627 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A03F1EB0A7711A3063C3316A38046948D8BB167501C90E7F14D3891FC0E1953A69C8257D3F5491BE6FAC62A38DCCD105AA]}
,06-09 17:17:00.144  4627  4627 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,06-09 17:17:09.534  3503  6040 D SSRM:n  : SIOP:: AP = 300, PST = 330 (W:14), CP = 263, CUR = -28, LCD = 40
,06-09 17:17:13.804  3503  6076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-09 17:17:14.534  9370  9433 I jxcore-log: TAP version 13
06-09 17:17:14.534  9370  9433 I jxcore-log: 
,06-09 17:17:14.554  9370  9433 I jxcore-log: # setup
06-09 17:17:14.554  9370  9433 I jxcore-log: 
,06-09 17:17:17.594  3503  3524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-09 17:17:17.594  3503  3524 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-09 17:17:17.594  3503  3524 D BatteryService: online:4, current avg:-5, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-09 17:17:17.594  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-09 17:17:17.604  3503  3503 I MotionRecognitionService: Plugged
,06-09 17:17:17.604  3503  3503 D MotionRecognitionService:   cableConnection= 1
06-09 17:17:17.604  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-09 17:17:17.604  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,06-09 17:17:17.604  3503  3857 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-09 17:17:17.614  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-09 17:17:17.614  3933  3933 D KeyguardUpdateMonitor: handleBatteryUpdate
06-09 17:17:17.614  3933  3933 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-09 17:17:17.634  5001  5001 D CommonServiceConfiguration: getStringValueSetting
,06-09 17:17:17.654  5001  5001 D BatteryMonitor: new battery level: 100
,06-09 17:17:17.654  4953  4953 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-09 17:17:17.654  4953  9461 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-09 17:17:17.654  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-09 17:17:17.654  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-09 17:17:19.564  3503  6040 D SSRM:n  : SIOP:: AP = 300, PST = 326 (W:14), CP = 261, CUR = -5, LCD = 40
,06-09 17:17:27.614  3503  4130 E Watchdog: !@Sync 13 [06-09 17:17:27.620]
,06-09 17:17:29.584  3503  6040 D SSRM:n  : SIOP:: AP = 300, PST = 321 (W:14), CP = 260, CUR = -5, LCD = 40
,06-09 17:17:33.804  3503  6076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-09 17:17:39.614  3503  6040 D SSRM:n  : SIOP:: AP = 300, PST = 319 (W:14), CP = 259, CUR = -5, LCD = 40
,06-09 17:17:47.644  3503  4412 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-09 17:17:47.644  3503  4412 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-09 17:17:47.644  3503  4412 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-09 17:17:47.644  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-09 17:17:47.654  3503  3503 I MotionRecognitionService: Plugged
,06-09 17:17:47.654  3503  3503 D MotionRecognitionService:   cableConnection= 1
06-09 17:17:47.654  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-09 17:17:47.654  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,06-09 17:17:47.664  3503  3857 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-09 17:17:47.664  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-09 17:17:47.664  3933  3933 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-09 17:17:47.664  3933  3933 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-09 17:17:47.674  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-09 17:17:47.684  5001  5001 D CommonServiceConfiguration: getStringValueSetting
,06-09 17:17:47.694  5001  5001 D BatteryMonitor: new battery level: 100
06-09 17:17:47.694  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-09 17:17:47.694  4953  4953 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-09 17:17:47.694  4953  9461 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-09 17:17:49.644  3503  6040 D SSRM:n  : SIOP:: AP = 300, PST = 317 (W:14), CP = 258, LCD = 40
,06-09 17:17:53.804  3503  6076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-09 17:17:57.614  3503  4130 E Watchdog: !@Sync 14 [06-09 17:17:57.622]
,06-09 17:17:59.324  4303  4437 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-09 17:17:59.324  4303  4437 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-09 17:17:59.384  4303  4437 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 54ms lastUpdatedAfter : 130126ms
,06-09 17:17:59.664  3503  6040 D SSRM:n  : SIOP:: AP = 300, PST = 315 (W:14), CP = 257, LCD = 40
,06-09 17:17:59.984  3503  3811 V AlarmManager: Expired Alarm result :8
,06-09 17:17:59.994  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-09 17:17:59.994  3933  3933 D KeyguardUpdateMonitor: handleTimeUpdate
,06-09 17:18:00.014  3933  3933 D Clock   : received broadcast android.intent.action.TIME_TICK
,06-09 17:18:00.064  3933  3933 D DateView: received broadcast android.intent.action.TIME_TICK
,06-09 17:18:00.084  4627  4627 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,06-09 17:18:00.084  4627  4627 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,06-09 17:18:00.094  4627  4627 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,06-09 17:18:00.094  4627  4627 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,06-09 17:18:00.094  4627  4627 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A03F1EB0A7711A3063C3316A38046948D8BB167501C90E7F14D3891FC0E1953A69C8257D3F5491BE6FAC62A38DCCD105AA]}
06-09 17:18:00.094  4627  4627 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,06-09 17:18:09.694  3503  6040 D SSRM:n  : SIOP:: AP = 300, PST = 312 (W:14), CP = 257, LCD = 40
,06-09 17:18:13.804  3503  6076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-09 17:18:14.594  9370  9433 I jxcore-log: 2017-06-09 15:18:14 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - closeAll can close even when connections open, error: 'TimeoutError', stack: 'TimeoutError: 
06-09 17:18:14.594  9370  9433 I jxcore-log:     at SubError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
06-09 17:18:14.594  9370  9433 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
06-09 17:18:14.594  9370  9433 I jxcore-log:     at timeoutTimeout@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
06-09 17:18:14.594  9370  9433 I jxcore-log:     at $9@timers.js:120:1
06-09 17:18:14.594  9370  9433 I jxcore-log: ''
06-09 17:18:14.594  9370  9433 I jxcore-log: 
,06-09 17:18:14.594  9370  9433 I jxcore-log: 2017-06-09 15:18:14 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'android''
06-09 17:18:14.594  9370  9433 I jxcore-log: 
,06-09 17:18:17.694  3503  3975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-09 17:18:19.724  3503  6040 D SSRM:n  : SIOP:: AP = 300, PST = 310 (W:14), CP = 256, LCD = 40
,06-09 17:18:27.614  3503  4130 E Watchdog: !@Sync 15 [06-09 17:18:27.623]
,06-09 17:18:29.744  3503  6040 D SSRM:n  : SIOP:: AP = 290, PST = 307 (W:14), CP = 255, LCD = 40
,06-09 17:18:33.804  3503  6076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-09 17:18:39.144  9370  9433 I jxcore-log: 2017-06-09 15:18:39 - DEBUG CoordinatedClient: 'all tests completed'
06-09 17:18:39.144  9370  9433 I jxcore-log: 
,06-09 17:18:39.774  3503  6040 D SSRM:n  : SIOP:: AP = 300, PST = 305 (W:10), CP = 255, LCD = 40
,06-09 17:18:47.744  3503  3524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-09 17:18:47.744  3503  3524 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-09 17:18:47.744  3503  3524 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-09 17:18:47.754  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-09 17:18:47.754  3503  3503 I MotionRecognitionService: Plugged
,06-09 17:18:47.754  3503  3503 D MotionRecognitionService:   cableConnection= 1
06-09 17:18:47.754  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-09 17:18:47.754  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,06-09 17:18:47.764  3503  3857 D WifiController: ApOrStaEnabledState  msg.what= 155652
,06-09 17:18:47.764  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-09 17:18:47.764  3933  3933 D KeyguardUpdateMonitor: handleBatteryUpdate
06-09 17:18:47.764  3933  3933 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-09 17:18:47.794  5001  5001 D CommonServiceConfiguration: getStringValueSetting
,06-09 17:18:47.804  4953  4953 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-09 17:18:47.804  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-09 17:18:47.804  4953  9461 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-09 17:18:47.804  3933  3933 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-09 17:18:47.804  5001  5001 D BatteryMonitor: new battery level: 100
,06-09 17:18:49.134  3186  3186 I bootchecker: bootchecker wake up!!
,06-09 17:18:49.804  3503  6040 D SSRM:n  : SIOP:: AP = 290, PST = 298 (W:10), CP = 255, LCD = 40
,06-09 17:18:53.804  3503  6076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-09 17:18:57.614  3503  4130 E Watchdog: !@Sync 16 [06-09 17:18:57.625]
,06-09 17:18:59.454  4303  4437 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-09 17:18:59.454  4303  4437 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-09 17:18:59.834  3503  6040 D SSRM:n  : SIOP:: AP = 290, PST = 297 (W:10), CP = 254, LCD = 40
,06-09 17:18:59.984  3503  3811 V AlarmManager: Expired Alarm result :8
,06-09 17:18:59.994  3933  3933 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-09 17:18:59.994  3933  3933 D KeyguardUpdateMonitor: handleTimeUpdate
,06-09 17:19:00.014  3933  3933 D Clock   : received broadcast android.intent.action.TIME_TICK
,06-09 17:19:00.074  3933  3933 D DateView: received broadcast android.intent.action.TIME_TICK
,06-09 17:19:00.094  4627  4627 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,06-09 17:19:00.094  4627  4627 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,06-09 17:19:00.094  4627  4627 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,06-09 17:19:00.104  4627  4627 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,06-09 17:19:00.104  4627  4627 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A03F1EB0A7711A3063C3316A38046948D8BB167501C90E7F14D3891FC0E1953A69C8257D3F5491BE6FAC62A38DCCD105AA]}
,06-09 17:19:00.104  4627  4627 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,06-09 17:19:09.854  3503  6040 D SSRM:n  : SIOP:: AP = 290, PST = 296 (W:10), CP = 254, LCD = 40
,06-09 17:19:13.814  3503  6076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-09 17:19:17.794  3503  4208 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-09 17:19:19.884  3503  6040 D SSRM:n  : SIOP:: AP = 290, PST = 295 (W:14), CP = 254, LCD = 40
,06-09 17:19:27.614  3503  4130 E Watchdog: !@Sync 17 [06-09 17:19:27.627]
,06-09 17:19:29.914  3503  6040 D SSRM:n  : SIOP:: AP = 290, PST = 292 (W:14), CP = 253, LCD = 40
,06-09 17:19:33.814  3503  6076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-09 17:19:34.704  9370  9433 I jxcore-log: 2017-06-09 15:19:34 - DEBUG CoordinatedClient: 'test client disconnected'
06-09 17:19:34.704  9370  9433 I jxcore-log: 
,06-09 17:19:34.704  9370  9433 I jxcore-log: 2017-06-09 15:19:34 - DEBUG CoordinatedClient: 'test client failed'
06-09 17:19:34.704  9370  9433 I jxcore-log: 
,06-09 17:19:34.724  9370  9433 I jxcore-log: 2017-06-09 15:19:34 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, event: 'setup_closeAll can close even when connections open_finished', test: 'closeAll can close even when connections open'', stack: 'CoordinatedClient.prototype._customError@/data/data/com.thaliproject.thalitest/files/www/jxcore/lib/CoordinatedClient.js:291:27
06-09 17:19:34.724  9370  9433 I jxcore-log: Emitter.prototype.emit@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
06-09 17:19:34.724  9370  9433 I jxcore-log: Socket.prototype.onevent@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
06-09 17:19:34.724  9370  9433 I jxcore-log: Socket.prototype.onpacket@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
06-09 17:19:34.724  9370  9433 I jxcore-log: module.exports/<@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/component-bind/index.js:21:12
06-09 17:19:34.724  9370  9433 I jxcore-log: Emitter.prototype.emit@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7''
06-09 17:19:34.724  9370  9433 I jxcore-log: 
,06-09 17:19:34.724  9370  9433 I jxcore-log: 2017-06-09 15:19:34 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
06-09 17:19:34.724  9370  9433 I jxcore-log: 
,06-09 17:19:34.734  9370  9433 I jxcore-log: 2017-06-09 15:19:34 - ERROR runTests: 'TimeoutError: timeout exceeded, event: 'setup_closeAll can close even when connections open_finished', test: 'closeAll can close even when connections open'
06-09 17:19:34.734  9370  9433 I jxcore-log: CoordinatedClient.prototype._customError@/data/data/com.thaliproject.thalitest/files/www/jxcore/lib/CoordinatedClient.js:291:27
06-09 17:19:34.734  9370  9433 I jxcore-log: Emitter.prototype.emit@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
06-09 17:19:34.734  9370  9433 I jxcore-log: Socket.prototype.onevent@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
06-09 17:19:34.734  9370  9433 I jxcore-log: Socket.prototype.onpacket@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
06-09 17:19:34.734  9370  9433 I jxcore-log: module.exports/<@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/component-bind/index.js:21:12
06-09 17:19:34.734  9370  9433 I jxcore-log: Emitter.prototype.emit@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7'
06-09 17:19:34.734  9370  9433 I jxcore-log: 
,06-09 17:19:35.204  9989  9989 I FIPS_bssl: FIPS approved mode (1) | 9989 | app_process
,06-09 17:19:35.204  9989  9989 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,06-09 17:19:35.204  9989  9989 D AndroidRuntime: CheckJNI is OFF
06-09 17:19:35.204  9989  9989 D AndroidRuntime: readGMSProperty: start
06-09 17:19:35.204  9989  9989 D AndroidRuntime: readGMSProperty: already setted!!
06-09 17:19:35.204  9989  9989 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-09 17:19:35.204  9989  9989 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-09 17:19:35.204  9989  9989 D AndroidRuntime: readGMSProperty: end
06-09 17:19:35.204  9989  9989 D AndroidRuntime: addProductProperty: start
,06-09 17:19:35.224  9989  9989 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,06-09 17:19:35.244  9989  9989 I Radio-JNI: register_android_hardware_Radio DONE
,06-09 17:19:35.254  9989  9989 E AffinityControl: AffinityControl: registerfunction enter
,06-09 17:19:35.264  9989  9989 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,06-09 17:19:35.274  3503  4293 D PackageManager: START PACKAGE DELETE: observer{71425421}
06-09 17:19:35.274  3503  4293 D PackageManager: pkg{<packageName>}
06-09 17:19:35.274  3503  4293 D PackageManager: user{0}
06-09 17:19:35.274  3503  4293 D PackageManager: caller{2000}
06-09 17:19:35.274  3503  4293 D PackageManager: flags{2}
,06-09 17:19:35.274  3503  4293 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-09 17:19:35.274  3503  4293 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-09 17:19:35.274  3503  4293 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-09 17:19:35.274  3503  4293 D PackageManager: deletePackageAsUser- pkg:com.thaliproject.thalitest, userId:0, flag2
06-09 17:19:35.274  3503  4293 D PackageManager: deletePackageAsUser- pkg:com.thaliproject.thalitest, userId:0, flag2
,06-09 17:19:35.274  3503  3620 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-09 17:19:35.274  3503  3620 D PackageManagerService: deletePackage- pkg:com.thaliproject.thalitest, edmuserId:0
06-09 17:19:35.274  3503  3620 D PackageManagerService: deletePackage- pkg:com.thaliproject.thalitest, edmuserId:-1
06-09 17:19:35.274  3503  3620 D ApplicationPolicy: getApplicationUninstallationEnabled
06-09 17:19:35.274  3503  3620 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,06-09 17:19:35.274  3503  3620 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,06-09 17:19:35.284  3503  3620 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.thaliproject.thalitest
,06-09 17:19:35.284  3503  3620 D PackageManager: !@killApplicatoin: 10074, uninstall pkg
06-09 17:19:35.284  3503  3620 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,06-09 17:19:35.284  3503  3592 I ActivityManager: Force stopping com.thaliproject.thalitest appid=10074 user=-1: uninstall pkg
06-09 17:19:35.284  3503  3620 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.thaliproject.thalitest
06-09 17:19:35.284  3503  3592 I ActivityManager: Killing 9370:com.thaliproject.thalitest/u0a74 (adj 0): stop com.thaliproject.thalitest cause uninstall pkg
,06-09 17:19:35.284  3503  3592 D ActivityManager: cleanUpApplicationRecord -- 9370
,06-09 17:19:35.284  3503  3592 D ActivityManager: isAutoRunBlockedApp:: com.thaliproject.thalitest, Auto Run ON
06-09 17:19:35.284  3503  3592 W ActivityManager: Force removing ActivityRecord{ca726be u0 com.thaliproject.thalitest/.MainActivity t5}: app died, no saved state
,06-09 17:19:35.304  3503  3592 D InputDispatcher: Focused application set to: xxxx
,06-09 17:19:35.314  3503  3592 D InputDispatcher: Focus left window: 9370
,06-09 17:19:35.324  3011  3021 I SurfaceFlinger: id=19 Removed NainActivit (6/10)
,06-09 17:19:35.324  3011  3974 I SurfaceFlinger: id=19 Removed NainActivit (-2/10)
,06-09 17:19:35.334  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd9b887f8
06-09 17:19:35.334  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd9b887f8
06-09 17:19:35.334  3011  3011 D libEGL  : eglTerminate EGLDisplay = 0x7fd9b887f8
,06-09 17:19:35.344  3503  3602 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3503 uid:1000
06-09 17:19:35.344  3503  3592 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3503  pkgName : ACTIVITY_RESUME_BOOSTER@3
06-09 17:19:35.344  3503  3602 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-09 17:19:35.344  3503  3620 D AASAinstall: there is not AASApackages.xml file
,06-09 17:19:35.354  3503  3592 D ActivityManager: mDVFSHelper.acquire()
,06-09 17:19:35.414  3503  3524 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@99a7b42)
06-09 17:19:35.414  3503  4208 D GraphicsStats: Buffer count: 5
06-09 17:19:35.414  3503  4415 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@f60c753)
06-09 17:19:35.414  3503  3863 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:19:35.414  3503  3863 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:19:35.414  3503  3863 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:19:35.414  3503  3863 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:19:35.414  3503  3863 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-09 17:19:35.414  3503  3863 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-09 17:19:35.524  3503  3620 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,06-09 17:19:35.564  3503  3620 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,06-09 17:19:35.564  3167  3167 W keystore: ENTER clear_uid from uid 1000 for 10074
,06-09 17:19:35.564  3503  3620 I art     : Starting a blocking GC Explicit
,06-09 17:19:35.574  3503  3503 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,06-09 17:19:35.574  3011  3011 I SurfaceFlinger: id=21 createSurf (1528x2641),1 flag=4, VSBConnecti
,06-09 17:19:35.574  3503  4414 V WindowOrientationListener: setCurrentAppOrientation :1
06-09 17:19:35.574  3503  4414 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
06-09 17:19:35.574  3503  4414 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-09 17:19:35.574  3503  4414 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
,06-09 17:19:35.574  4267  4267 D Launcher: onRestart, Launcher: 262551277
06-09 17:19:35.574  3503  4414 D InputDispatcher: Focus entered window: 6104
,06-09 17:19:35.574  4267  4267 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
06-09 17:19:35.584  4267  4267 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:19:35.584  4267  4267 D ApplicationPackageManager: we has com.sec.android.app.clockpackage class. reuse it 
,06-09 17:19:35.584  4267  4267 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.sec.android.app.clockpackage
,06-09 17:19:35.594  3503  3592 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,06-09 17:19:35.594  3503  3592 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
06-09 17:19:35.594  3503  3592 E MARsPolicyManager: getPackageInfo package com.rockwellautomation.thalitest not installed!
,06-09 17:19:35.594  3503  3602 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3503 uid:1000
06-09 17:19:35.594  3503  3602 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-09 17:19:35.594  3503  3594 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{bd9a99 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,06-09 17:19:35.594  3503  6040 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
06-09 17:19:35.594  3933  3933 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
06-09 17:19:35.594  6677  6677 V ActivityThread: updateVisibility : ActivityRecord{3053e02 token=android.os.BinderProxy@528871d {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : true
06-09 17:19:35.594  3503  3524 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
06-09 17:19:35.594  3503  3524 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-09 17:19:35.594  3503  3503 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-09 17:19:35.604  3011  3011 I SurfaceFlinger: id=22 createSurf (1528x2656),1 flag=4, YUIInstallC
,06-09 17:19:35.604  3503  3503 I KnoxTimeoutHandler: Shared devices show user statefalse
,06-09 17:19:35.604  3503  3503 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,06-09 17:19:35.604  6677  7504 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1528x2656]-format:1
,06-09 17:19:35.604  4267  4267 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
,06-09 17:19:35.614  4267  4267 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:19:35.614  4267  4267 D ApplicationPackageManager: we has com.android.calendar class. reuse it 
,06-09 17:19:35.614  3011  3011 I SurfaceFlinger: id=23 createSurf (193x193),1 flag=4, YUIInstallC
,06-09 17:19:35.624  4267  4267 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
,06-09 17:19:35.624  3503  6040 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
06-09 17:19:35.624  4267  4267 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,06-09 17:19:35.624  4267  4267 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
06-09 17:19:35.624  4267  4267 D Minikin : FontFamily bestFont == NULL, so return vacant FakedFont
,06-09 17:19:35.624  3503  3975 V WindowStateAnimator: Finishing drawing window Window{bd9a99 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,06-09 17:19:35.624  6677  7504 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [193x193]-format:1
,06-09 17:19:35.624  3503  6040 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,06-09 17:19:35.624  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd9b88708
,06-09 17:19:35.624  4267  4267 D Launcher: onStart, Launcher: 262551277
06-09 17:19:35.624  4267  4267 D Launcher.HomeView: onStart
,06-09 17:19:35.634  4267  4267 D Launcher.MenuAppsGrid: updateGridSize:GRID_4x4 cellWidth:348  cellHeight:432
06-09 17:19:35.634  3011  3011 I SurfaceFlinger: id=24 createSurf (1592x384),1 flag=4, VSBConnecti
,06-09 17:19:35.634  3503  3602 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-09 17:19:35.634  3503  3503 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-09 17:19:35.634  3503  3503 I KnoxTimeoutHandler: SD activityfalse
,06-09 17:19:35.644  3503  4413 V WindowStateAnimator: Finishing drawing window Window{f0b71f7 u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}: mDrawState=DRAW_PENDING
,06-09 17:19:35.644  3503  6040 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,06-09 17:19:35.644  3503  4293 V WindowStateAnimator: Finishing drawing window Window{e6a6acd u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}: mDrawState=DRAW_PENDING
,06-09 17:19:35.644  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd9b88708
,06-09 17:19:35.644  3503  6040 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
06-09 17:19:35.644  3503  6040 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
06-09 17:19:35.644  4267  4267 V ActivityThread: updateVisibility : ActivityRecord{c9ea9a3 token=android.os.BinderProxy@9980970 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
,06-09 17:19:35.654  3011  3011 I SurfaceFlinger: id=25 createSurf (1440x2560),1 flag=4, MauncherAct
,06-09 17:19:35.654  3503  4209 V WindowStateAnimator: Finishing drawing window Window{772893f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,06-09 17:19:35.654  3503  3602 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-09 17:19:35.654  3503  3503 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-09 17:19:35.654  4267  4604 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,06-09 17:19:35.654  3503  3503 I KnoxTimeoutHandler: SD activityfalse
,06-09 17:19:35.664  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd9b88708
,06-09 17:19:35.664  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd9b88708
,06-09 17:19:35.664  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd9b88708
,06-09 17:19:35.674  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd9b88708
,06-09 17:19:35.694  3503  4279 V WindowStateAnimator: Finishing drawing window Window{10115df u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: mDrawState=DRAW_PENDING
,06-09 17:19:35.694  3933  3933 D WallpaperService: updateSurface:[forceRelayout]false[redrawNeeded]false
,06-09 17:19:35.694  3933  3933 D ImageWallpaper: onVisibilityChanged:true
06-09 17:19:35.694  3933  3933 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
06-09 17:19:35.694  3933  3933 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
06-09 17:19:35.694  3933  3933 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,06-09 17:19:35.694  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd9b88708
,06-09 17:19:35.694  3011  3011 D libEGL  : eglInitialize EGLDisplay = 0x7fd9b88708
,06-09 17:19:35.704  3503  3602 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-09 17:19:35.704  3503  3503 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-09 17:19:35.704  3503  3503 I KnoxTimeoutHandler: SD activityfalse
,06-09 17:19:35.714  3503  3620 I art     : Explicit concurrent mark sweep GC freed 185937(10MB) AllocSpace objects, 143(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.386ms total 152.336ms
,06-09 17:19:35.724  6104  6104 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@50f40b1 time:531939
,06-09 17:19:35.734  3503  3620 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.thaliproject.thalitest-1/base.apk, retcode=-1
,06-09 17:19:35.734  3503  3620 D AASAuninstall: userId = 0, info.removedAppID = 10074, info.uid = 10074, packageName = com.thaliproject.thalitest
,06-09 17:19:35.734  3503  3620 D AASAinstall: there is not AASApackages.xml file
,06-09 17:19:35.734  3503  3620 D PackageManager: result of delete: 1{71425421}
,06-09 17:19:35.734  3503  3620 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.thaliproject.thalitest}
06-09 17:19:35.734  3503  3620 D PackageManager: userId{-1}
06-09 17:19:35.734  3503  3620 D PackageManager: andCode{true}
,06-09 17:19:35.734  9989  9989 I art     : System.exit called, status: 0
06-09 17:19:35.734  9989  9989 I AndroidRuntime: VM exiting with result code 0.
,06-09 17:19:35.754 10002 10002 E Zygote  : v2
06-09 17:19:35.754 10002 10002 I libpersona: KNOX_SDCARD checking this for 10008
06-09 17:19:35.754 10002 10002 I libpersona: KNOX_SDCARD not a persona
06-09 17:19:35.754 10002 10002 E libpersona: scanKnoxPersonas
,06-09 17:19:35.754 10002 10002 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
06-09 17:19:35.754  3503  3620 I ActivityManager: Start proc 10002:com.android.defcontainer/u0a8 for service com.android.defcontainer/.DefaultContainerService
06-09 17:19:35.754  3503  3620 I ActivityManager: Force stopping com.thaliproject.thalitest appid=10074 user=0: pkg removed
,06-09 17:19:35.754 10002 10002 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,06-09 17:19:35.754 10002 10002 E Zygote  : accessInfo : 0
06-09 17:19:35.754 10002 10002 E libpersona: scanKnoxPersonas
06-09 17:19:35.754 10002 10002 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
,06-09 17:19:35.794  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,06-09 17:19:35.794  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,06-09 17:19:35.804  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:19:35.804  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.804  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.804 10002 10002 D TimaKeyStoreProvider: TimaSignature is unavailable
06-09 17:19:35.804 10002 10002 D ActivityThread: Added TimaKeyStore provider
,06-09 17:19:35.804  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:19:35.804  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.804  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.804  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.804  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.804  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.804  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,06-09 17:19:35.804  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,06-09 17:19:35.814  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.814  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.814  3933  3933 D ShortcutManager: onReceive : android.intent.action.PACKAGE_REMOVED
06-09 17:19:35.814  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
06-09 17:19:35.814  3933  3933 D ShortcutManager: onReceive : Intent.EXTRA_REPLACING false,com.thaliproject.thalitest
06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.814  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,06-09 17:19:35.814  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.814  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
06-09 17:19:35.814  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,06-09 17:19:35.814  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
06-09 17:19:35.814  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
06-09 17:19:35.814  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.814  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,06-09 17:19:35.814  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.814  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,06-09 17:19:35.814  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:19:35.814  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.814  3503  3602 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
06-09 17:19:35.824  3503  3602 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.824  3503  3602 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
06-09 17:19:35.824  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
06-09 17:19:35.824  3503  3825 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-09 17:19:35.824  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
06-09 17:19:35.824  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
06-09 17:19:35.824  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
06-09 17:19:35.824  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.824  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.824  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
06-09 17:19:35.824  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
06-09 17:19:35.824  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
06-09 17:19:35.824  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
06-09 17:19:35.824  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.824  4254  4254 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.android.phone rsrc of package com.android.mms
,06-09 17:19:35.824  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,06-09 17:19:35.824  4226  4770 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-09 17:19:35.824  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback,
06-09 17:19:35.834  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  5001  5238 D PresenceModule: onReceive: package removed
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  5001  5238 D PresenceModule: handleMessage: msg 50, Last Publish Info: null
,06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  5001  5238 D PresenceModule: Application package removed
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  5001  5238 D PresenceModule: onAppPkgRemoved: com.thaliproject.thalitest
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  5001  5238 D PresenceModule: onApplicationPackageRemoved: invalid package
,06-09 17:19:35.834  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3588 D AccessibilityManagerService: onUserStateChangedLocked()
,06-09 17:19:35.834  3503  3588 D AccessibilityManagerService: updateServicesLocked().mIsAccessibilityEnabled : false
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
06-09 17:19:35.834  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
06-09 17:19:35.844  7439  7439 W BeaconManager: AppControlManager.mPackageReceiver - Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.thaliproject.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
06-09 17:19:35.844  7439  7439 D BeaconManager: AppControlManager.mPackageReceiver - ACTION_PACKAGE_REMOVED com.thaliproject.thalitest
06-09 17:19:35.834  4254  4254 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:19:35.834  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.834  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
06-09 17:19:35.844  4254  4254 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.phone rsrc of package com.google.android.talk
,06-09 17:19:35.844  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
06-09 17:19:35.844  4254  4254 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:19:35.844  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
06-09 17:19:35.844  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.854  3503  3588 D EnterpriseDeviceManagerService: Package has changed for user 0
,06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.854  3503  3588 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.854  3503  3850 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
06-09 17:19:35.844  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
,06-09 17:19:35.844  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.854  3503  3852 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
06-09 17:19:35.844  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
06-09 17:19:35.854  3503  3852 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
06-09 17:19:35.854  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
,06-09 17:19:35.854  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.854  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
06-09 17:19:35.854  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
06-09 17:19:35.854  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,06-09 17:19:35.854  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
06-09 17:19:35.854  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
06-09 17:19:35.854  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,06-09 17:19:35.854  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
06-09 17:19:35.854  3503  3850 V NetworkStats: removeUidsLocked() for UIDs [10074]
06-09 17:19:35.854  3503  3850 V NetworkStats: performPollLocked(flags=0x3)
06-09 17:19:35.854  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3/SamsungIMEv3.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
06-09 17:19:35.854  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,06-09 17:19:35.854  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
06-09 17:19:35.854  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
06-09 17:19:35.854  3503  3850 D NetworkStatsRecorder: entry.iface is null
06-09 17:19:35.854  3503  3503 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
06-09 17:19:35.854  3503  3850 D NetworkStatsRecorder: entry.iface is null
06-09 17:19:35.854  3503  3850 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/dev.1496409649191- -> /data/system/netstats/dev.1496409649191-.backup
06-09 17:19:35.854  3503  3503 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:19:35.854  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/dev.1496409649191-
06-09 17:19:35.854  3503  3850 D NetworkStatsRecorder: entry.iface is null
06-09 17:19:35.854  3503  3850 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/dev.1496409649191-.backup -> /data/system/netstats/dev.1496409649191-
06-09 17:19:35.854  3503  3850 D NetworkStatsRecorder: entry.iface is null
06-09 17:19:35.854  3503  3503 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
06-09 17:19:35.854  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.854  3503  3503 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.thaliproject.thalitest
06-09 17:19:35.854  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
,06-09 17:19:35.854  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
06-09 17:19:35.854  3503  3503 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
06-09 17:19:35.854  3503  3503 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
,06-09 17:19:35.864  3503  3503 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,06-09 17:19:35.864  3503  3592 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95dfb0a u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b866b7f 6481:com.samsung.klmsagent/u0a26}
06-09 17:19:35.864  3503  3503 I OTPFW   : PackageRemovalReceiver::onReceive Enter
06-09 17:19:35.864  6481  6481 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.thaliproject.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } | timestamp: Fri Jun 09 17:19:35 GMT+02:00 2017
06-09 17:19:35.864  3503  3503 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.thaliproject.thalitest uid = 10074 container id = 0
06-09 17:19:35.864  3503  3503 I OTPFW   : ProvisionData::getAllEntries Enter
06-09 17:19:35.864  3503  3503 E OTPFW   : ProvisionData::getAllEntries Table is empty
06-09 17:19:35.864  3503  3503 E SDAgentPackageStateReceiver: Not going to handle 'com.thaliproject.thalitest'!
,06-09 17:19:35.864  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.864  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
06-09 17:19:35.864  3503  3503 D UcmService: onReceive android.intent.action.PACKAGE_REMOVED
06-09 17:19:35.864  3503  3503 D UcmService: Package update in userId-0 and uid-10074
06-09 17:19:35.864  3503  3503 D InjectionManagerService -AppFeature:  Info before com.thaliproject.thalitest removal target ={} 
06-09 17:19:35.864  3503  3503 D InjectionManagerService -AppFeature:  source ={}
06-09 17:19:35.864  3503  3503 W SQLiteLog: (28) failed to open "/data/system/gamemanager.db" with flag (131138) and mode_t (0) due to error (30)
06-09 17:19:35.864  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
06-09 17:19:35.864  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
06-09 17:19:35.864  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,06-09 17:19:35.864  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.864  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: Failed to open database '/data/system/gamemanager.db'.
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: #################################################################
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: #################################################################
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at com.android.server.SystemServer.run(SystemServer.java:508)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at com.android.server.SystemServer.main(SystemServer.java:363)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
06-09 17:19:35.864  3503  3503 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
06-09 17:19:35.864  3503  3503 D AndroidRuntime: Shutting down VM
06-09 17:19:35.864  3503  3588 D ResourcesManager: For user 0 ,new overlays fetched Null
06-09 17:19:35.864  3503  3503 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: main
06-09 17:19:35.864  3503  3503 E AndroidRuntime: java.lang.RuntimeException: Error receiving broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.thaliproject.thalitest flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) } in com.samsung.android.game.GameManagerService$UninstallReceiver@706c476
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1003)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at com.android.server.SystemServer.run(SystemServer.java:508)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at com.android.server.SystemServer.main(SystemServer.java:363)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-09 17:19:35.864  3503  3503 E AndroidRuntime: #################################################################
06-09 17:19:35.864  3503  3503 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
06-09 17:19:35.864  3503  3503 E AndroidRuntime: #################################################################
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at com.samsung.android.game.data.DatabaseHelper.removeGame(DatabaseHelper.java:144)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at com.samsung.android.game.GameManagerService$UninstallReceiver.onReceive(GameManagerService.java:512)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(Loa,dedApk.java:993)
06-09 17:19:35.864  3503  3503 E AndroidRuntime: 	... 8 more
06-09 17:19:35.864  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
06-09 17:19:35.864  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
06-09 17:19:35.864  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.864  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
06-09 17:19:35.864  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
06-09 17:19:35.864  4254  4254 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
06-09 17:19:35.864  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
06-09 17:19:35.864  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
06-09 17:19:35.874  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.874  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
06-09 17:19:35.874  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
06-09 17:19:35.874  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.874  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
06-09 17:19:35.874  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
06-09 17:19:35.874  3503  4208 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4807, uid=10124 that is not exported from uid 10122
06-09 17:19:35.874  3503  3878 D MdnieScenarioControlService:  packageName : com.samsung.android.MtpApplication    className : com.samsung.android.MtpApplication.USBConnection
06-09 17:19:35.874  4023  4023 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_REMOVE
06-09 17:19:35.874  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.874  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
06-09 17:19:35.874  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.874  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
06-09 17:19:35.874  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
06-09 17:19:35.874  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: Can't write: netstats_dump
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:292)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1218)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
06-09 17:19:35.874  3503  3850 E DropBoxManagerService: 	... 16 more
06-09 17:19:35.874  3503  3850 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop93.tmp
06-09 17:19:35.874  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
06-09 17:19:35.874  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/dev.1496409649191-
06-09 17:19:35.874  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/dev.1493809894162-1495108734886
06-09 17:19:35.874  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/dev.1495113062657-1496409629386
06-09 17:19:35.874  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
06-09 17:19:35.874  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/dev.1492484995634-1493787528777
06-09 17:19:35.874  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/dev.1488334589779-1489647768474
06-09 17:19:35.874  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/dev.1491161787329-1492460658317
06-09 17:19:35.874  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/dev.1489825933125-1491136204202
06-09 17:19:35.874  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
06-09 17:19:35.884  3503  3503 E android.os.Debug: THIS IS SYSTEM_SERVER.. store dumpState!!
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in null rsrc of package com.sec.android.app.launcher
06-09 17:19:35.884  3503  3850 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/xt.1496409649191- -> /data/system/netstats/xt.1496409649191-.backup
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
06-09 17:19:35.884  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/xt.1496409649191-
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
06-09 17:19:35.884  3503  3850 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netstats/xt.1496409649191-.backup -> /data/system/netstats/xt.1496409649191-
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
06-09 17:19:35.884  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
06-09 17:19:35.884  6481  6481 I KLMS-2.6.201: : KLMSAbstractReciever(): onReceive().END.
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: Can't write: netstats_dump
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:292)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at android.os.DropBoxManager.addData(DropBoxManager.java:282)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.recoverFromWtf(NetworkStatsRecorder.java:500)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.forcePersistLocked(NetworkStatsRecorder.java:324)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsRecorder.maybePersistLocked(NetworkStatsRecorder.java:306)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.performPollLocked(NetworkStatsService.java:1219)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.removeUidsLocked(NetworkStatsService.java:1288)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService.access$1600(NetworkStatsService.java:151)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at com.android.server.net.NetworkStatsService$5.onReceive(NetworkStatsService.java:883)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:158)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
06-09 17:19:35.884  3503  3850 E DropBoxManagerService: 	... 16 more
06-09 17:19:35.884  3503  3850 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop93.tmp
06-09 17:19:35.884  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/xt.1489825933125-1491136204202
06-09 17:19:35.884  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/xt.1496409649191-
06-09 17:19:35.884  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/xt.1491161787329-1492460658317
06-09 17:19:35.884  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/xt.1493809894162-1495108734886
06-09 17:19:35.884  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/xt.1492484995634-1493787528777
06-09 17:19:35.884  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/xt.1495113062657-1496409629386
06-09 17:19:35.884  3503  3850 W System.err: remove failed: EROFS (Read-only file system) : /data/system/netstats/xt.1488334589779-1489647768474
06-09 17:19:35.884  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.884  3503  3850 V NetworkStats: performPollLocked() took 35ms
06-09 17:19:35.884  3503  3850 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
06-09 17:19:35.884  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
06-09 17:19:35.894  6481  6481 I KLMS-2.6.201: : KLMSIntentService(): onCreate()
06-09 17:19:35.894  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.894  6481  6481 I KLMS-2.6.201: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
06-09 17:19:35.894  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
06-09 17:19:35.894 10002 10002 W ResourcesManager: getTopLevelResources: /system/priv-app/DefaultContainerService/DefaultContainerService.apk / 1.0 running in com.android.defcontainer rsrc of package com.android.defcontainer
06-09 17:19:35.894  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
06-09 17:19:35.894  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
06-09 17:19:35.894  6481  6481 I KLMS-2.6.201: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
06-09 17:19:35.894  6481 10019 I KLMS-2.6.201: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.thaliproject.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
06-09 17:19:35.894  6481 10019 D KLMS-2.6.201: : KLMSIntentService(): PACKAGE_REMOVED
06-09 17:19:35.894  6481 10019 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemoved().START
06-09 17:19:35.894  6481 10019 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemoved().packageName: com.thaliproject.thalitest
06-09 17:19:35.894  6481 10019 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemovedforELM().START - com.thaliproject.thalitest
06-09 17:19:35.894  6481 10019 I KLMS-2.6.201: : MDMBridge(): getAllLicenseInfoFromSDK()
06-09 17:19:35.894  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.894  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
06-09 17:19:35.894  3503  4414 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-09 17:19:35.894 10002 10002 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
06-09 17:19:35.894  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
06-09 17:19:35.894  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
06-09 17:19:35.894  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
06-09 17:19:35.894 10002 10002 D ResourcesManager: For user 0 new overlays fetched Null
06-09 17:19:35.894  6481 10019 I KLMS-2.6.201: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
06-09 17:19:35.894  6481 10019 I KLMS-2.6.201: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
06-09 17:19:35.894  3503  4293 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95dfb0a u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{398d68e 3503:system/1000}
06-09 17:19:35.894  6481 10019 I KLMS-2.6.201: : MDMBridge(): getAllLicenseInfoFromSDK()
06-09 17:19:35.894 10002 10002 I InjectionManager: Inside getClassLibPath caller 
06-09 17:19:35.894  6481 10019 D KLMS-2.6.201: : Systemprocess(): arrayLicenseInfo is null
06-09 17:19:35.904  6481 10019 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
06-09 17:19:35.904  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
06-09 17:19:35.904  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:19:35.904  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
06-09 17:19:35.904  3503  3852 D NtpTrustedTime: currentTimeMillis() cache hit
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: #################################################################
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: #################################################################
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:587)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:523)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
06-09 17:19:35.904  6481 10019 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-09 17:19:35.904  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: #################################################################
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: #################################################################
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:587)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:523)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
06-09 17:19:35.904  6481 10019 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-09 17:19:35.904  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
06-09 17:19:35.904  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
06-09 17:19:35.904  6481 10019 W SQLiteOpenHelper: Opened klms.db in read-only mode
06-09 17:19:35.904  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
06-09 17:19:35.904  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
06-09 17:19:35.904  6481 10019 D KLMS-2.6.201: : DataSource(): Fetched Data from data base count : 0
06-09 17:19:35.904  3503  3975 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
06-09 17:19:35.904  3503  3975 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
06-09 17:19:35.904  3503  3975 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-09 17:19:35.904  3503  3975 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-09 17:19:35.904  3503  3975 D SettingsProvider: selectionArgs: false
06-09 17:19:35.904  3503  3975 D SettingsProvider: selectionArgs: 10026
06-09 17:19:35.904 10002 10002 D InjectionManager: InjectionManager
06-09 17:19:35.904 10002 10002 D InjectionManager: fillFeatureStoreMap com.android.defcontainer
06-09 17:19:35.904 10002 10002 I InjectionManager: Constructor com.android.defcontainer, Feature store :{}
06-09 17:19:35.904 10002 10002 I InjectionManager: featureStore :{}
,06-09 17:19:35.904  3503  3975 D SettingsProvider: ret = -1
06-09 17:19:35.904  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
06-09 17:19:35.914  6481 10019 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemovedforELM().END
06-09 17:19:35.914  6481 10019 I KLMS-2.6.201: : Systemprocess(): listeningToPackageRemovedforKLM().START - com.thaliproject.thalitest
06-09 17:19:35.934  4241 10020 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
06-09 17:19:35.934  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
06-09 17:19:35.934  4241 10020 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
06-09 17:19:35.934  4241 10020 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
06-09 17:19:35.934  4241 10020 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
06-09 17:19:35.934  4241 10020 D RegisteredComponentCache: Collect Tech packages for Knox
06-09 17:19:35.934  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
06-09 17:19:35.944 10002 10021 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.thaliproject.thalitest
,06-09 17:19:35.954  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,06-09 17:19:35.954 10002 10021 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.thaliproject.thalitest
,06-09 17:19:35.954  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
,06-09 17:19:35.954 10002 10021 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.thaliproject.thalitest
,06-09 17:19:35.964  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
,06-09 17:19:35.964  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
,06-09 17:19:35.964  3503  4412 I ActivityManager: Killing 9200:com.sec.android.widgetapp.samsungapps/u0a105 (adj 15): DHA:empty #33
,06-09 17:19:35.964  3503  3588 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
,06-09 17:19:35.964  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage
,06-09 17:19:35.974  3503  3588 D ResourcesManager: For user 0 new overlays fetched Null
,06-09 17:19:35.974  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage
06-09 17:19:35.974  3503  3878 I MdnieScenarioControlService: mGameModeLauncher : false
,06-09 17:19:35.974  3503  3878 I MdnieScenarioControlService: setUIMode
,06-09 17:19:35.974  3503  3588 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage

```
