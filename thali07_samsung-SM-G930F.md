#### Test 97727103c899188_thali07_samsung-SM-G930F Logs


```
--------- beginning of system
12-15 11:45:03.043  3503  4394 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:45:03.043  3503  4394 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:45:03.043  3503  4394 D BatteryService: online:4, current avg:163, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:157
12-15 11:45:03.043  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:45:03.053  3503  3503 I MotionRecognitionService: Plugged
12-15 11:45:03.053  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:45:03.053  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-15 11:45:03.053  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
12-15 11:45:03.053  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
12-15 11:45:03.053  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-15 11:45:03.053  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
12-15 11:45:03.063  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
12-15 11:45:03.073  4961  4961 D CommonServiceConfiguration: getStringValueSetting
12-15 11:45:03.073  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-15 11:45:03.073  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
12-15 11:45:03.083  4961  4961 D BatteryMonitor: new battery level: 100
12-15 11:45:03.093  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-15 11:45:03.093  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-15 11:45:03.523  9131  9131 I FIPS_bssl: FIPS approved mode (1) | 9131 | app_process
12-15 11:45:03.533  9131  9131 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
12-15 11:45:03.533  9131  9131 D AndroidRuntime: CheckJNI is OFF
12-15 11:45:03.533  9131  9131 D AndroidRuntime: readGMSProperty: start
12-15 11:45:03.533  9131  9131 D AndroidRuntime: readGMSProperty: already setted!!
12-15 11:45:03.533  9131  9131 D AndroidRuntime: propertySet: couldn't set property (it is from app)
12-15 11:45:03.533  9131  9131 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
12-15 11:45:03.533  9131  9131 D AndroidRuntime: readGMSProperty: end
12-15 11:45:03.533  9131  9131 D AndroidRuntime: addProductProperty: start
12-15 11:45:03.563  9131  9131 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
12-15 11:45:03.583  9131  9131 I Radio-JNI: register_android_hardware_Radio DONE
12-15 11:45:03.593  9131  9131 E AffinityControl: AffinityControl: registerfunction enter
12-15 11:45:03.613  9131  9131 D AndroidRuntime: Calling main entry com.android.commands.am.Am
12-15 11:45:03.653  3503  4272 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
12-15 11:45:03.653  3503  4272 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
12-15 11:45:03.683  3503  4272 D ResourcesManager: For user 0 new overlays fetched Null
12-15 11:45:03.683  3503  4272 D GameManagerService: identifyGamePackage. com.test.thalitest
12-15 11:45:03.683  3503  4272 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
12-15 11:45:03.683  3503  4272 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3503  pkgName : ACTIVITY_RESUME_BOOSTER@3
12-15 11:45:03.693  3503  4272 D ActivityManager: mDVFSHelper.acquire()
12-15 11:45:03.693  3503  4272 V WindowManager: addAppToken: AppWindowToken{d0edb9f6 token=Token{abcd691 ActivityRecord{eb868b8 u0 com.test.thalitest/.MainActivity t171}}} to stack=2 task=171 at 0
12-15 11:45:03.693  3007  3018 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (95 us)
12-15 11:45:03.713  3503  3601 I InjectionManager: Inside getClassLibPath caller 
12-15 11:45:03.713  3503  4272 D InputDispatcher: Focused application set to: xxxx
12-15 11:45:03.713  3503  4272 D InputDispatcher: Focus left window: 6154
12-15 11:45:03.713  3503  3591 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{f5575b2 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
12-15 11:45:03.713  3503  3601 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{41e11ce V.E...... R.....ID 0,0-0,0}
12-15 11:45:03.713  3503  3601 D SecWifiDisplayUtil: Metadata value : SecSettings2
12-15 11:45:03.713  3503  3601 D ISSUE_DEBUG: InputChannelName : b434ffc Starting com.test.thalitest
12-15 11:45:03.713  9131  9131 D AndroidRuntime: Shutting down VM
12-15 11:45:03.713  3931  3931 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
12-15 11:45:03.723  3503  3601 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3503 uid:1000
12-15 11:45:03.723  3503  3601 D PointerIcon: setMouseCustomIcon IconType is same.101
12-15 11:45:03.723  3503  4133 E Watchdog: !@Sync 4 [12-15 11:45:03.728]
12-15 11:45:03.733  9141  9141 E Zygote  : v2
12-15 11:45:03.733  9141  9141 I libpersona: KNOX_SDCARD checking this for 10074
12-15 11:45:03.733  9141  9141 I libpersona: KNOX_SDCARD not a persona
12-15 11:45:03.733  9141  9141 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
12-15 11:45:03.733  3503  4674 I ActivityManager: Start proc 9141:com.test.thalitest/u0a74 for activity com.test.thalitest/.MainActivity
12-15 11:45:03.733  9141  9141 E Zygote  : accessInfo : 0
12-15 11:45:03.733  9141  9141 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
12-15 11:45:03.733  3503  3846 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
12-15 11:45:03.733  3007  3007 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, uhalitest
12-15 11:45:03.743  9141  9141 D TimaKeyStoreProvider: TimaSignature is unavailable
12-15 11:45:03.743  9141  9141 D ActivityThread: Added TimaKeyStore provider
12-15 11:45:03.753  3503  3843 V WindowOrientationListener: setCurrentAppOrientation :-1
12-15 11:45:03.753  3503  3601 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
12-15 11:45:03.753  3503  3843 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
12-15 11:45:03.753  3503  3843 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
12-15 11:45:03.753  3503  3843 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
12-15 11:45:03.753  3503  3843 D ActivityManager:  Launching com.test.thalitest, updated priority
12-15 11:45:03.753  4260  4260 D Launcher.HomeView: onStop
12-15 11:45:03.753  4260  4260 D capture : ----destroy
12-15 11:45:03.753  4260  4260 V ActivityThread: updateVisibility : ActivityRecord{de55745 token=android.os.BinderProxy@1163b06 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
12-15 11:45:03.763  3503  3503 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
12-15 11:45:03.763  9141  9141 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
12-15 11:45:03.763  3503  3590 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
12-15 11:45:03.763  3503  4405 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-15 11:45:03.763  9141  9141 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
12-15 11:45:03.763  3503  6063 D GameManagerService: identifyGamePackage. com.test.thalitest
12-15 11:45:03.763  3503  6063 D GameManagerService: identifyGamePackage. com.test.thalitest
12-15 11:45:03.773  9141  9141 D ResourcesManager: For user 0 new overlays fetched Null
12-15 11:45:03.773  3007  4430 D libEGL  : eglTerminate EGLDisplay = 0x7fa12ffe78
12-15 11:45:03.773  3007  4430 D libEGL  : eglTerminate EGLDisplay = 0x7fa12ffe78
12-15 11:45:03.773  9141  9141 I InjectionManager: Inside getClassLibPath caller 
12-15 11:45:03.783  4260  4260 D Launcher: onTrimMemory. Level: 20
12-15 11:45:03.783  9141  9141 D InjectionManager: InjectionManager
12-15 11:45:03.783  9141  9141 D InjectionManager: fillFeatureStoreMap com.test.thalitest
12-15 11:45:03.783  3503  3601 V WindowStateAnimator: Finishing drawing window Window{b434ffc u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
12-15 11:45:03.783  9141  9141 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
12-15 11:45:03.783  9141  9141 I InjectionManager: featureStore :{}
12-15 11:45:03.793  9141  9141 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
12-15 11:45:03.793  9141  9141 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-15 11:45:03.793  9141  9141 D RelationGraph: garbageCollect()
12-15 11:45:03.793  3503  3591 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{b434ffc u0 d0 Starting com.test.thalitest}
12-15 11:45:03.793  3503  6063 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
12-15 11:45:03.793  9141  9141 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
12-15 11:45:03.793  3503  6063 D GameManagerService: identifyGamePackage. com.test.thalitest
12-15 11:45:03.803  3503  6063 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
12-15 11:45:03.803  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fc5c97c28
12-15 11:45:03.803  3503  6063 D GameManagerService: identifyGamePackage. com.test.thalitest
12-15 11:45:03.803  3503  6063 D GameManagerService: identifyGamePackage. com.test.thalitest
12-15 11:45:03.803  3007  4430 D libEGL  : eglTerminate EGLDisplay = 0x7fa12ffe78
12-15 11:45:03.803  3007  4430 D libEGL  : eglTerminate EGLDisplay = 0x7fa12ffe78
12-15 11:45:03.803  9141  9141 I CordovaLog: Changing log level to DEBUG(3)
12-15 11:45:03.803  9141  9141 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
12-15 11:45:03.803  9141  9141 D CordovaActivity: CordovaActivity.onCreate()
12-15 11:45:03.813  9141  9141 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
12-15 11:45:03.833  9141  9141 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
12-15 11:45:03.833  9141  9141 D ResourcesManager: For user 0 new overlays fetched Null
12-15 11:45:03.833  9141  9141 I InjectionManager: Inside getClassLibPath caller 
12-15 11:45:03.833  9141  9141 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
12-15 11:45:03.853  3503  3515 I art     : Background partial concurrent mark sweep GC freed 264229(17MB) AllocSpace objects, 60(3MB) LOS objects, 30% free, 35MB/51MB, paused 1.367ms total 152.401ms
12-15 11:45:03.873  9141  9141 I cr_LibraryLoader: Time to load native libraries: 22 ms (timestamps 3908-3930)
12-15 11:45:03.873  9141  9141 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
12-15 11:45:03.893  9141  9156 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
12-15 11:45:03.903  9141  9141 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2cc8018}
12-15 11:45:03.903  9141  9141 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
12-15 11:45:03.923  9141  9141 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,12-15 11:45:03.953  9141  9141 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,12-15 11:45:04.013  3503  3872 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,12-15 11:45:04.033  9141  9141 D libEGL  : eglInitialize EGLDisplay = 0xffccdb54
,12-15 11:45:04.073  3503  4947 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10074
,12-15 11:45:04.073  3503  4947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,12-15 11:45:04.093  3503  3846 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,12-15 11:45:04.113  9141  9141 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9141
,12-15 11:45:04.113  3503  4057 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9141 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,12-15 11:45:04.113  3503  3858 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
12-15 11:45:04.113  3503  3858 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,12-15 11:45:04.113  3503  3872 I MdnieScenarioControlService: mGameModeLauncher : false
,12-15 11:45:04.123  3503  3872 I MdnieScenarioControlService: setUIMode
,12-15 11:45:04.123  3503  3858 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,12-15 11:45:04.123  3503  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,12-15 11:45:04.123  3503  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,12-15 11:45:04.133  9141  9141 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,12-15 11:45:04.133  3503  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,12-15 11:45:04.133  3503  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,12-15 11:45:04.133  3503  3858 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,12-15 11:45:04.143  9141  9141 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,12-15 11:45:04.143  9141  9141 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,12-15 11:45:04.153  9141  9141 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,12-15 11:45:04.163  9141  9141 D PluginManager: init()
,12-15 11:45:04.163  9141  9141 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,12-15 11:45:04.173  9141  9141 I cr_Ime  : ImeThread is not enabled.
,12-15 11:45:04.173  3007  3016 I SurfaceFlinger: id=9 Removed MauncherAct (4/12)
,12-15 11:45:04.173  3007  4332 I SurfaceFlinger: id=9 Removed MauncherAct (-2/12)
12-15 11:45:04.173  3007  4004 I SurfaceFlinger: id=15 Removed VSBConnecti (4/11)
,12-15 11:45:04.173  3007  3018 I SurfaceFlinger: id=15 Removed VSBConnecti (-2/11)
12-15 11:45:04.173  3007  3016 I SurfaceFlinger: id=14 Removed VSBConnecti (5/10)
12-15 11:45:04.173  3007  4430 I SurfaceFlinger: id=14 Removed VSBConnecti (-2/10)
,12-15 11:45:04.183  3931  3931 D ImageWallpaper: onVisibilityChanged:false
12-15 11:45:04.183  9141  9141 D Activity: performCreate Call Injection manager
,12-15 11:45:04.183  3931  3931 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
12-15 11:45:04.183  3931  3931 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
12-15 11:45:04.183  3931  3931 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,12-15 11:45:04.183  9141  9141 D CordovaActivity: Started the activity.
12-15 11:45:04.183  9141  9141 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
12-15 11:45:04.183  9141  9141 D CordovaActivity: Resumed the activity.
,12-15 11:45:04.183  9141  9141 D SecWifiDisplayUtil: Metadata value : SecSettings2
,12-15 11:45:04.193  9141  9141 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{c4f0eb7 I.E...... R.....ID 0,0-0,0}
,12-15 11:45:04.193  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc5c97d48
,12-15 11:45:04.193  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc5c97d48
12-15 11:45:04.193  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc5c97d48
,12-15 11:45:04.193  9141  9191 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,12-15 11:45:04.193  3503  4388 D ISSUE_DEBUG: InputChannelName : 523a4c7 com.test.thalitest/com.test.thalitest.MainActivity
,12-15 11:45:04.193  3503  3524 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
12-15 11:45:04.193  3503  3524 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
12-15 11:45:04.193  3503  3503 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,12-15 11:45:04.193  3503  3503 I KnoxTimeoutHandler: Shared devices show user statefalse
,12-15 11:45:04.203  9141  9141 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9141
,12-15 11:45:04.203  3503  4286 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9141 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,12-15 11:45:04.203  3503  3858 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
12-15 11:45:04.203  9141  9156 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
12-15 11:45:04.203  3503  3858 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,12-15 11:45:04.203  3503  3858 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,12-15 11:45:04.203  3503  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,12-15 11:45:04.203  3503  3846 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,12-15 11:45:04.213  3503  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
12-15 11:45:04.213  3503  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
12-15 11:45:04.213  9141  9141 D SecWifiDisplayUtil: Metadata value : SecSettings2
12-15 11:45:04.213  3503  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
12-15 11:45:04.213  3503  3858 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
12-15 11:45:04.213  3503  3858 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
12-15 11:45:04.223  3007  3007 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
12-15 11:45:04.223  3503  4286 D InputDispatcher: Focus entered window: 9141
12-15 11:45:04.223  3503  3601 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3503 uid:1000
12-15 11:45:04.223  3503  3601 D PointerIcon: setMouseCustomIcon IconType is same.101
12-15 11:45:04.223  9141  9191 D libEGL  : eglInitialize EGLDisplay = 0xdd33c7c4
12-15 11:45:04.223  9141  9191 I OpenGLRenderer: Initialized EGL, version 1.4
12-15 11:45:04.233  9141  9191 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,12-15 11:45:04.243  9141  9141 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,12-15 11:45:04.263  9141  9195 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
12-15 11:45:04.263  9141  9195 D libEGL  : eglInitialize EGLDisplay = 0xda79f3e4
,12-15 11:45:04.273  9141  9195 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,12-15 11:45:04.283  3503  3843 V WindowStateAnimator: Finishing drawing window Window{523a4c7 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,12-15 11:45:04.283  9141  9141 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
12-15 11:45:04.283  3503  4057 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,12-15 11:45:04.283  3503  3601 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
12-15 11:45:04.283  3503  3503 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
12-15 11:45:04.283  3503  3601 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +572ms
,12-15 11:45:04.283  3503  3601 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3503  tag : ACTIVITY_RESUME_BOOSTER@3
,12-15 11:45:04.283  3503  3601 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{eb868b8 u0 com.test.thalitest/.MainActivity t171} time:134348
12-15 11:45:04.283  3503  3601 D ActivityManager: mDVFSHelper.release()
12-15 11:45:04.283  3503  3601 D ViewRootImpl: #3 mView = null
12-15 11:45:04.283  3503  3590 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3503  pkgName : ACTIVITY_RESUME_BOOSTER@9
,12-15 11:45:04.293  3503  3503 I KnoxTimeoutHandler: SD activityfalse
,12-15 11:45:04.293  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fc5c97c28
,12-15 11:45:04.293  4769  4769 D SamsungIME: IMPL finishInput
12-15 11:45:04.293  4769  4769 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
12-15 11:45:04.293  4769  4769 D SamsungIME: saveAndClear +
12-15 11:45:04.293  4769  4769 D SamsungIME: saveAndClear -
,12-15 11:45:04.293  3503  4286 V WindowStateAnimator: Finishing drawing window Window{523a4c7 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,12-15 11:45:04.303  9141  9141 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,12-15 11:45:04.303  9141  9141 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9141
,12-15 11:45:04.303  9141  9141 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
12-15 11:45:04.303  9141  9141 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
12-15 11:45:04.303  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fc5c97c28
,12-15 11:45:04.313  9141  9141 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a37acdf time:134373
,12-15 11:45:04.313  6154  6154 V ActivityThread: updateVisibility : ActivityRecord{bd83775 token=android.os.BinderProxy@90b8bcf {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,12-15 11:45:04.343  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fc5c97c28
,12-15 11:45:04.373  9141  9141 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,12-15 11:45:04.473  3007  4004 I SurfaceFlinger: id=16 Removed uhalitest (7/10)
,12-15 11:45:04.483  3007  4332 I SurfaceFlinger: id=16 Removed uhalitest (-2/10)
,12-15 11:45:04.483  9141  9204 D jxcore_app_log: JniHelper::setJavaVM(0xf48b4000), pthread_self() = -692061904
,12-15 11:45:04.493  9141  9141 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,12-15 11:45:04.493  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc5c97d48
,12-15 11:45:04.493  9141  9141 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
12-15 11:45:04.493  9141  9141 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,12-15 11:45:04.583  3503  3872 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,12-15 11:45:04.583  3503  3503 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3503  tag : ACTIVITY_RESUME_BOOSTER@9
,12-15 11:45:04.653  3503  6063 D SSRM:n  : SIOP:: AP = 330, PST = 351 (W:6), CP = 274, CUR = 163, LCD = 40
,12-15 11:45:04.683  3503  3872 I MdnieScenarioControlService: mGameModeLauncher : false
,12-15 11:45:04.683  3503  3872 I MdnieScenarioControlService: setUIMode
,12-15 11:45:04.733  4016  4016 D Recents : onTaskStackChanged
,12-15 11:45:04.733  4016  4016 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,12-15 11:45:04.753  4016  4016 D ResourcesManager: For user 0 new overlays fetched Null
,12-15 11:45:04.763  3503  6064 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,12-15 11:45:04.913  9141  9205 W jxcore-log: Initializing JXcore engine
12-15 11:45:04.913  9141  9205 W jxcore-log: JXcore engine is ready
,12-15 11:45:04.933  4929  4929 E audit   : type=1400 msg=audit(1481798704.933:262): avc:  denied  { ioctl } for  pid=9205 comm="Thread-138" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4232 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
12-15 11:45:04.933  4929  4929 E audit   :  SEPF_SECMOBILE_6.0.1_0031
12-15 11:45:04.933  4929  4929 E audit   : type=1300 msg=audit(1481798704.933:262): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d60053c8 items=0 ppid=3177 pid=9205 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
12-15 11:45:04.933  4929  4929 E audit   : type=1327 msg=audit(1481798704.933:262): proctitle="com.test.thalitest"
12-15 11:45:04.933  4929  4929 E audit   : type=1320 msg=audit(1481798704.933:262): 
,12-15 11:45:04.933  4929  4929 E audit   : type=1400 msg=audit(1481798704.933:263): avc:  denied  { ioctl } for  pid=9205 comm="Thread-138" path="socket:[10164]" dev="sockfs" ino=10164 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
12-15 11:45:04.933  4929  4929 E audit   :  SEPF_SECMOBILE_6.0.1_0031
12-15 11:45:04.933  4929  4929 E audit   : type=1300 msg=audit(1481798704.933:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=2 a3=d60053c8 items=0 ppid=3177 pid=9205 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
12-15 11:45:04.933  4929  4929 E audit   : type=1327 msg=audit(1481798704.933:263): proctitle="com.test.thalitest"
12-15 11:45:04.933  4929  4929 E audit   : type=1320 msg=audit(1481798704.933:263): 
,12-15 11:45:04.933  9141  9205 W jxcore-log: Starting JXcore engine
,12-15 11:45:04.973  9141  9205 W jxcore-log: Platform android
12-15 11:45:04.973  9141  9205 W jxcore-log: 
12-15 11:45:04.973  9141  9205 W jxcore-log: Process ARCH arm
12-15 11:45:04.973  9141  9205 W jxcore-log: 
,12-15 11:45:05.003  4382  4434 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-15 11:45:05.003  4382  4434 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-15 11:45:05.073  9141  9205 I jxcore-log: JXcore Cordova bridge is ready!
12-15 11:45:05.073  9141  9205 I jxcore-log: 
12-15 11:45:05.073  9141  9205 W jxcore-log: JXcore engine is started
,12-15 11:45:06.703  3503  3898 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/171_task.xml.bak
,12-15 11:45:06.773  3503  6063 D GameManagerService: identifyGamePackage. com.test.thalitest
,12-15 11:45:09.813  3503  6063 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-15 11:45:11.083  9141  9205 E JX-Cordova: JavaCall recevied a call for unknown method didRegisterToNative
12-15 11:45:11.083  9141  9205 E JX-Cordova: JavaCall recevied a call for unknown method didRegisterToNative
12-15 11:45:11.083  9141  9205 E JX-Cordova: JavaCall recevied a call for unknown method didRegisterToNative
12-15 11:45:11.083  9141  9205 E JX-Cordova: JavaCall recevied a call for unknown method didRegisterToNative
,12-15 11:45:11.243  9141  9205 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
12-15 11:45:11.243  9141  9205 I jxcore-log: Failed to execute UT.
12-15 11:45:11.243  9141  9205 I jxcore-log: 
,12-15 11:45:11.243  9141  9205 I jxcore-log: 2016-12-15 10:45:11 - DEBUG UnitTest_app: 'Failed to execute UT.'
12-15 11:45:11.243  9141  9205 I jxcore-log: 
,12-15 11:45:11.243  9141  9205 I jxcore-log: 2016-12-15 10:45:11 - DEBUG UnitTest_app: 'Unit Test app is loaded'
12-15 11:45:11.243  9141  9205 I jxcore-log: 
,12-15 11:45:11.263  9141  9141 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,12-15 11:45:11.263  9141  9141 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,12-15 11:45:12.703  4274  5798 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,12-15 11:45:13.103  3503  4286 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:45:13.113  3503  4286 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:45:13.113  3503  4286 D BatteryService: online:4, current avg:-27, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:220
12-15 11:45:13.113  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:45:13.113  3503  3503 I MotionRecognitionService: Plugged
12-15 11:45:13.113  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:45:13.113  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-15 11:45:13.113  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:45:13.123  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:45:13.123  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-15 11:45:13.123  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-15 11:45:13.123  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:45:13.133  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:45:13.143  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:45:13.143  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-15 11:45:13.153  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:45:13.153  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:45:13.163  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:45:13.763  3503  3619 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,12-15 11:45:13.783  3503  3619 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,12-15 11:45:14.673  3503  6063 D SSRM:n  : SIOP:: AP = 360, PST = 328 (W:6), CP = 284, CUR = -27, LCD = 40
,12-15 11:45:14.693  3503  6063 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-15 11:45:19.543  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:45:23.163  3503  4273 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:45:23.163  3503  4273 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:45:23.163  3503  4273 D BatteryService: online:4, current avg:103, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:180
12-15 11:45:23.163  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:45:23.173  3503  3503 I MotionRecognitionService: Plugged
12-15 11:45:23.173  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:45:23.173  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-15 11:45:23.173  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:45:23.173  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:45:23.183  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-15 11:45:23.183  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-15 11:45:23.183  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:45:23.193  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:45:23.203  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-15 11:45:23.203  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:45:23.203  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:45:23.213  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:45:23.213  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:45:24.723  3503  6063 D SSRM:n  : SIOP:: AP = 330, PST = 328 (W:14), CP = 283, CUR = 103, LCD = 40
,12-15 11:45:25.313  3503  3806 V AlarmManager: Expired Alarm result :4
,12-15 11:45:25.333  3503  3590 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b595bea u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3a35804 4274:com.google.android.gms.persistent/u0a19}
,12-15 11:45:25.353  3503  4286 V AlarmManager:  remove PendingIntent] PendingIntent{99edb: PendingIntentRecord{ee06e27 com.google.android.gms broadcastIntent}}
,12-15 11:45:25.443  4586  9211 D UdcContextInitService: registered all accounts: true
,12-15 11:45:25.533  3503  4387 V AlarmManager:  remove PendingIntent] PendingIntent{df3fc51: PendingIntentRecord{ee06e27 com.google.android.gms broadcastIntent}}
,12-15 11:45:25.843  4274  9213 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,12-15 11:45:25.843  4274  9213 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,12-15 11:45:26.173  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-15 11:45:26.173  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-15 11:45:26.173  3152  3614 D EnterpriseController: netId is 0
12-15 11:45:26.173  3152  3614 D Netd    : getNetworkForDns: using netid 502 for uid 10019
,12-15 11:45:26.233  4274  9213 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4274, getuid(): 10019
,12-15 11:45:26.273  4274  9213 I qtaguid : Tagging socket 67 with tag 3000120100000000{805310977,0} uid -1, pid: 4274, getuid(): 10019
,12-15 11:45:26.683  4274  9213 W Uploader: GMM_PRIMES no longer exists, so no auth token.
,12-15 11:45:26.683  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-15 11:45:26.683  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-15 11:45:26.683  4274  9213 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4274, getuid(): 10019
,12-15 11:45:26.783  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-15 11:45:26.783  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-15 11:45:26.783  4274  9213 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4274, getuid(): 10019
,12-15 11:45:26.873  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-15 11:45:26.873  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-15 11:45:26.873  4274  9213 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4274, getuid(): 10019
,12-15 11:45:26.983  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-15 11:45:26.983  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-15 11:45:26.983  4274  9213 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4274, getuid(): 10019
,12-15 11:45:27.103  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-15 11:45:27.103  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-15 11:45:27.103  4274  9213 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4274, getuid(): 10019
,12-15 11:45:27.213  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-15 11:45:27.213  4274  9213 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-15 11:45:27.213  4274  9213 I qtaguid : Tagging socket 63 with tag 3000120100000000{805310977,0} uid -1, pid: 4274, getuid(): 10019
,12-15 11:45:27.413  3503  3967 V AlarmManager:  remove PendingIntent] PendingIntent{d24045: PendingIntentRecord{ee06e27 com.google.android.gms broadcastIntent}}
,12-15 11:45:33.223  3503  4674 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:45:33.223  3503  4674 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:45:33.223  3503  4674 D BatteryService: online:4, current avg:140, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:152
12-15 11:45:33.223  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:45:33.233  3503  3503 I MotionRecognitionService: Plugged
,12-15 11:45:33.233  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:45:33.233  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-15 11:45:33.233  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:45:33.233  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:45:33.243  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-15 11:45:33.243  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
12-15 11:45:33.243  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:45:33.253  4961  4961 D CommonServiceConfiguration: getStringValueSetting
12-15 11:45:33.253  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-15 11:45:33.263  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:45:33.273  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:45:33.293  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-15 11:45:33.293  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:45:33.723  3503  4133 E Watchdog: !@Sync 5 [12-15 11:45:33.730]
,12-15 11:45:34.743  3503  6063 D SSRM:n  : SIOP:: AP = 320, PST = 329 (W:14), CP = 279, CUR = 140, LCD = 40
,12-15 11:45:39.553  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:45:43.283  3503  4405 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:45:43.283  3503  4405 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:45:43.283  3503  4405 D BatteryService: online:4, current avg:147, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:141
12-15 11:45:43.283  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:45:43.283  3503  3503 I MotionRecognitionService: Plugged
,12-15 11:45:43.283  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:45:43.283  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-15 11:45:43.283  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:45:43.293  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:45:43.293  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-15 11:45:43.293  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-15 11:45:43.303  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:45:43.313  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:45:43.313  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-15 11:45:43.323  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:45:43.323  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:45:43.343  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-15 11:45:43.343  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:45:44.773  3503  6063 D SSRM:n  : SIOP:: AP = 310, PST = 328 (W:14), CP = 276, CUR = 147, LCD = 40
,12-15 11:45:53.343  3503  4272 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:45:53.343  3503  4272 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:45:53.343  3503  4272 D BatteryService: online:4, current avg:144, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:144
12-15 11:45:53.343  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:45:53.343  3503  3503 I MotionRecognitionService: Plugged
,12-15 11:45:53.353  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:45:53.353  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-15 11:45:53.353  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
12-15 11:45:53.353  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
12-15 11:45:53.353  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-15 11:45:53.353  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
12-15 11:45:53.363  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:45:53.373  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:45:53.383  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-15 11:45:53.383  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:45:53.383  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:45:53.403  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:45:53.403  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:45:54.793  3503  6063 D SSRM:n  : SIOP:: AP = 310, PST = 328 (W:14), CP = 273, CUR = 144, LCD = 40
,12-15 11:45:59.553  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:45:59.993  3503  3806 V AlarmManager: Expired Alarm result :8
,12-15 11:46:00.003  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-15 11:46:00.003  3931  3931 D KeyguardUpdateMonitor: handleTimeUpdate
,12-15 11:46:00.023  3931  3931 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-15 11:46:00.063  3931  3931 D DateView: received broadcast android.intent.action.TIME_TICK
,12-15 11:46:00.083  4740  4740 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-15 11:46:00.083  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-15 11:46:00.083  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-15 11:46:00.093  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-15 11:46:00.093  4740  4740 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0A4E14BED9EB8890D11FAA0FE25E6936D396B88B1054FC0D740255A221425EB37CA5E7098CFC8F411607A3F8F469DD214]}
,12-15 11:46:00.093  4740  4740 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-15 11:46:03.403  3503  4674 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:46:03.403  3503  4674 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:46:03.403  3503  4674 D BatteryService: online:4, current avg:139, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:138
12-15 11:46:03.403  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:46:03.413  3503  3503 I MotionRecognitionService: Plugged
,12-15 11:46:03.413  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:46:03.413  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-15 11:46:03.413  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:46:03.413  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:46:03.413  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-15 11:46:03.423  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
12-15 11:46:03.423  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-15 11:46:03.433  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:46:03.443  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-15 11:46:03.443  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:46:03.443  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:46:03.453  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-15 11:46:03.453  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:46:03.723  3503  4133 E Watchdog: !@Sync 6 [12-15 11:46:03.731]
,12-15 11:46:04.813  3503  6063 D SSRM:n  : SIOP:: AP = 310, PST = 327 (W:14), CP = 272, CUR = 139, LCD = 40
,12-15 11:46:05.103  4382  4434 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-15 11:46:05.103  4382  4434 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-15 11:46:05.213  4382  4434 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 1Kb duration : 101ms lastUpdatedAfter : 130671ms
,12-15 11:46:13.453  3503  4947 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-15 11:46:13.463  3503  4947 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:46:13.463  3503  4947 D BatteryService: online:4, current avg:135, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:131
12-15 11:46:13.463  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:46:13.463  3503  3503 I MotionRecognitionService: Plugged
,12-15 11:46:13.463  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:46:13.463  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,12-15 11:46:13.463  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:46:13.473  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:46:13.473  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-15 11:46:13.473  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-15 11:46:13.473  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:46:13.493  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:46:13.503  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-15 11:46:13.503  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:46:13.513  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:46:13.523  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:46:13.523  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:46:14.843  3503  6063 D SSRM:n  : SIOP:: AP = 310, PST = 323 (W:14), CP = 271, CUR = 135, LCD = 40
,12-15 11:46:19.553  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:46:23.523  3503  4405 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:46:23.523  3503  4405 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:46:23.523  3503  4405 D BatteryService: online:4, current avg:130, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:119
12-15 11:46:23.523  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:46:23.533  3503  3503 I MotionRecognitionService: Plugged
,12-15 11:46:23.533  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:46:23.533  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-15 11:46:23.533  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:46:23.533  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:46:23.533  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-15 11:46:23.543  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-15 11:46:23.543  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:46:23.553  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:46:23.553  4961  4961 D CommonServiceConfiguration: getStringValueSetting
12-15 11:46:23.563  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-15 11:46:23.563  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:46:23.563  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:46:23.583  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:46:24.863  3503  6063 D SSRM:n  : SIOP:: AP = 310, PST = 322 (W:14), CP = 270, CUR = 130, LCD = 40
,12-15 11:46:33.723  3503  4133 E Watchdog: !@Sync 7 [12-15 11:46:33.733]
,12-15 11:46:34.893  3503  6063 D SSRM:n  : SIOP:: AP = 310, PST = 320 (W:14), CP = 269, CUR = 130, LCD = 40
,12-15 11:46:39.553  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:46:44.913  3503  6063 D SSRM:n  : SIOP:: AP = 310, PST = 319 (W:14), CP = 269, CUR = 130, LCD = 40
,12-15 11:46:53.573  3503  3525 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:46:53.573  3503  3525 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:46:53.573  3503  3525 D BatteryService: online:4, current avg:8, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-15 11:46:53.573  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:46:53.573  3503  3503 I MotionRecognitionService: Plugged
,12-15 11:46:53.573  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:46:53.573  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,12-15 11:46:53.573  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:46:53.583  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:46:53.583  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-15 11:46:53.583  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
12-15 11:46:53.583  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:46:53.603  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:46:53.613  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-15 11:46:53.613  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:46:53.613  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:46:53.623  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-15 11:46:53.623  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:46:54.943  3503  6063 D SSRM:n  : SIOP:: AP = 310, PST = 317 (W:14), CP = 268, CUR = 8, LCD = 40
,12-15 11:46:59.553  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:46:59.993  3503  3806 V AlarmManager: Expired Alarm result :8
,12-15 11:47:00.003  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-15 11:47:00.003  3931  3931 D KeyguardUpdateMonitor: handleTimeUpdate
,12-15 11:47:00.013  3931  3931 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-15 11:47:00.063  3931  3931 D DateView: received broadcast android.intent.action.TIME_TICK
,12-15 11:47:00.083  4740  4740 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-15 11:47:00.083  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-15 11:47:00.083  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-15 11:47:00.093  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-15 11:47:00.093  4740  4740 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0A4E14BED9EB8890D11FAA0FE25E6936D396B88B1054FC0D740255A221425EB37CA5E7098CFC8F411607A3F8F469DD214]}
,12-15 11:47:00.093  4740  4740 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-15 11:47:03.723  3503  4133 E Watchdog: !@Sync 8 [12-15 11:47:03.734]
,12-15 11:47:04.963  3503  6063 D SSRM:n  : SIOP:: AP = 310, PST = 316 (W:14), CP = 268, CUR = 8, LCD = 40
,12-15 11:47:05.313  4382  4434 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-15 11:47:05.313  4382  4434 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-15 11:47:14.993  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 314 (W:14), CP = 267, CUR = 8, LCD = 40
,12-15 11:47:19.563  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:47:23.623  3503  4286 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:47:23.623  3503  4286 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4344, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:47:23.623  3503  4286 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-15 11:47:23.623  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:47:23.623  3503  3503 I MotionRecognitionService: Plugged
,12-15 11:47:23.623  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:47:23.623  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-15 11:47:23.623  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:47:23.633  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:47:23.633  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-15 11:47:23.633  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-15 11:47:23.643  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:47:23.643  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:47:23.653  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:47:23.663  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-15 11:47:23.663  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:47:23.673  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:47:23.683  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:47:25.013  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 312 (W:14), CP = 267, LCD = 40
,12-15 11:47:33.733  3503  4133 E Watchdog: !@Sync 9 [12-15 11:47:33.736]
,12-15 11:47:35.043  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 310 (W:14), CP = 267, LCD = 40
,12-15 11:47:39.563  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:47:45.063  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 307 (W:14), CP = 266, LCD = 40
,12-15 11:47:53.673  3503  4033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:47:53.673  3503  4033 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:47:53.673  3503  4033 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-15 11:47:53.673  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:47:53.683  3503  3503 I MotionRecognitionService: Plugged
,12-15 11:47:53.683  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:47:53.683  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,12-15 11:47:53.683  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:47:53.683  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:47:53.683  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-15 11:47:53.693  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-15 11:47:53.693  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:47:53.713  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:47:53.713  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-15 11:47:53.713  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:47:53.723  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:47:53.743  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:47:53.743  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:47:55.093  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 306 (W:14), CP = 266, LCD = 40
,12-15 11:47:59.563  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:47:59.993  3503  3806 V AlarmManager: Expired Alarm result :8
,12-15 11:48:00.003  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-15 11:48:00.003  3931  3931 D KeyguardUpdateMonitor: handleTimeUpdate
,12-15 11:48:00.023  3931  3931 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-15 11:48:00.083  3931  3931 D DateView: received broadcast android.intent.action.TIME_TICK
,12-15 11:48:00.103  4740  4740 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-15 11:48:00.103  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-15 11:48:00.103  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-15 11:48:00.103  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-15 11:48:00.103  4740  4740 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0A4E14BED9EB8890D11FAA0FE25E6936D396B88B1054FC0D740255A221425EB37CA5E7098CFC8F411607A3F8F469DD214]}
,12-15 11:48:00.103  4740  4740 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-15 11:48:01.213  3503  3798 D TimaService: TIMA: TimaService scheduler is intialized. 
12-15 11:48:01.213  3503  3798 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,12-15 11:48:01.213  3503  3797 D TimaService: TimaServiceHandler.handleMessage what =1
,12-15 11:48:01.223  3503  3798 I TLC_TIMA_PKM_initialize: initializing...
,12-15 11:48:01.223  3503  3798 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
12-15 11:48:01.223  3503  3798 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
12-15 11:48:01.223  3503  3798 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
12-15 11:48:01.223  3503  3798 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
12-15 11:48:01.223  3503  3798 I TZ: mc_tlc_communication: root = 0, root_len = 1
,12-15 11:48:01.223  3503  3798 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
12-15 11:48:01.223  3503  3798 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
12-15 11:48:01.223  3503  3798 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
12-15 11:48:01.223  3503  3798 I TZ: mc_tlc_communication: device_id = 0x0
12-15 11:48:01.223  3503  3798 I TZ: mc_tlc_communication: tlc_open() was called
12-15 11:48:01.223  3503  3798 I TZ: mc_tlc_communication: Opening MobiCore device
,12-15 11:48:01.223  3503  3798 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-15 11:48:01.223  3503  3798 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-15 11:48:01.223  3503  3798 I TZ: mc_tlc_communication: Opening the session
,12-15 11:48:01.263  3503  3798 I TZ: mc_tlc_communication: tlc_open() succeeded
,12-15 11:48:01.263  3503  3798 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,12-15 11:48:01.273  3503  3798 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,12-15 11:48:01.283  3503  3798 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,12-15 11:48:01.313  3503  3798 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,12-15 11:48:01.323  3503  3798 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,12-15 11:48:03.733  3503  4133 E Watchdog: !@Sync 10 [12-15 11:48:03.738]
,12-15 11:48:04.923  3503  3798 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
12-15 11:48:04.933  3503  3798 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,12-15 11:48:04.933  3503  3798 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,12-15 11:48:04.933  3503  3798 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,12-15 11:48:05.113  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 305 (W:14), CP = 266, LCD = 40
,12-15 11:48:05.323  4382  4434 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-15 11:48:05.323  4382  4434 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-15 11:48:15.143  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 305 (W:14), CP = 266, LCD = 40
,12-15 11:48:19.563  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:48:23.723  3503  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:48:23.723  3503  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:48:23.723  3503  3843 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-15 11:48:23.723  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:48:23.733  3503  3503 I MotionRecognitionService: Plugged
12-15 11:48:23.733  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:48:23.733  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,12-15 11:48:23.733  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:48:23.743  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:48:23.743  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-15 11:48:23.743  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
12-15 11:48:23.743  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-15 11:48:23.753  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:48:23.783  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:48:23.783  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:48:23.783  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-15 11:48:23.783  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:48:23.793  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:48:25.173  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 304 (W:14), CP = 265, LCD = 40
,12-15 11:48:29.303  8511  8563 W PlayEventLogger: No account for auth token provided
,12-15 11:48:29.313  8511  8563 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-15 11:48:29.313  8511  8563 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-15 11:48:29.313  3152  3614 D EnterpriseController: netId is 0
12-15 11:48:29.313  3152  3614 D Netd    : getNetworkForDns: using netid 502 for uid 10032
,12-15 11:48:33.733  3503  4133 E Watchdog: !@Sync 11 [12-15 11:48:33.739]
,12-15 11:48:35.203  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 303 (W:14), CP = 265, LCD = 40
,12-15 11:48:39.563  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:48:45.223  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 302 (W:14), CP = 265, LCD = 40
,12-15 11:48:53.773  3503  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:48:53.773  3503  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:48:53.773  3503  3843 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-15 11:48:53.773  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:48:53.783  3503  3503 I MotionRecognitionService: Plugged
,12-15 11:48:53.783  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:48:53.783  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-15 11:48:53.783  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:48:53.783  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:48:53.793  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-15 11:48:53.793  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
12-15 11:48:53.793  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:48:53.803  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:48:53.823  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-15 11:48:53.823  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:48:53.823  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:48:53.833  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:48:53.833  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:48:55.253  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 302 (W:14), CP = 265, LCD = 40
,12-15 11:48:59.563  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:48:59.993  3503  3806 V AlarmManager: Expired Alarm result :8
,12-15 11:49:00.003  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-15 11:49:00.003  3931  3931 D KeyguardUpdateMonitor: handleTimeUpdate
,12-15 11:49:00.023  3931  3931 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-15 11:49:00.103  3931  3931 D DateView: received broadcast android.intent.action.TIME_TICK
,12-15 11:49:00.123  4740  4740 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-15 11:49:00.123  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
12-15 11:49:00.123  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-15 11:49:00.133  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-15 11:49:00.133  4740  4740 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0A4E14BED9EB8890D11FAA0FE25E6936D396B88B1054FC0D740255A221425EB37CA5E7098CFC8F411607A3F8F469DD214]}
12-15 11:49:00.133  4740  4740 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-15 11:49:01.083  3503  3806 V AlarmManager: Expired Alarm result :4
,12-15 11:49:01.093  4093  4093 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,12-15 11:49:01.093  4093  4093 I wpa_supplicant: P2P: Current p2p state = IDLE
12-15 11:49:01.113  4093  4093 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
12-15 11:49:01.133  3503  3590 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d6c00c0 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ff5f72 4586:com.google.android.gms/u0a19}
,12-15 11:49:01.173  9251  9251 E Zygote  : v2
12-15 11:49:01.173  9251  9251 I libpersona: KNOX_SDCARD checking this for 1000
12-15 11:49:01.173  9251  9251 I libpersona: KNOX_SDCARD not a persona
,12-15 11:49:01.173  9251  9251 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,12-15 11:49:01.173  9251  9251 E Zygote  : accessInfo : 0
,12-15 11:49:01.173  3503  3806 I ActivityManager: Start proc 9251:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,12-15 11:49:01.213  9251  9251 D TimaKeyStoreProvider: TimaSignature is unavailable
12-15 11:49:01.213  9251  9251 D ActivityThread: Added TimaKeyStore provider
,12-15 11:49:01.243  9251  9251 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,12-15 11:49:01.243  3503  4405 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-15 11:49:01.243  9251  9251 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-15 11:49:01.243  9251  9251 D ResourcesManager: For user 0 new overlays fetched Null
,12-15 11:49:01.243  4586  9262 I EventLogService: Aggregate from 1481797140994 (log), 1481797140994 (data)
,12-15 11:49:01.253  9251  9251 I InjectionManager: Inside getClassLibPath caller 
,12-15 11:49:01.253  9251  9251 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,12-15 11:49:01.263  9251  9251 D InjectionManager: InjectionManager
12-15 11:49:01.263  9251  9251 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
,12-15 11:49:01.263  9251  9251 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
12-15 11:49:01.263  9251  9251 I InjectionManager: featureStore :{}
,12-15 11:49:01.283  3503  4033 I ActivityManager: Killing 8164:com.samsung.android.scloud:contentsync/5009 (adj 15): DHA:empty #33
,12-15 11:49:01.313  3503  4675 D ActivityManager: cleanUpApplicationRecord -- 8164
,12-15 11:49:01.313  3503  4675 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,12-15 11:49:01.363  9267  9267 E Zygote  : v2
12-15 11:49:01.363  9267  9267 I libpersona: KNOX_SDCARD checking this for 1000
12-15 11:49:01.363  9267  9267 I libpersona: KNOX_SDCARD not a persona
,12-15 11:49:01.363  9267  9267 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
12-15 11:49:01.363  3503  3590 I ActivityManager: Start proc 9267:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
12-15 11:49:01.373  9267  9267 E Zygote  : accessInfo : 0
,12-15 11:49:01.403  9267  9267 D TimaKeyStoreProvider: TimaSignature is unavailable
12-15 11:49:01.403  9267  9267 D ActivityThread: Added TimaKeyStore provider
,12-15 11:49:01.413  3503  4286 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{96d174a u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dc7a6bb 9267:com.samsung.android.sm/1000}
,12-15 11:49:01.423  9267  9267 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_NoIcon/SmartManager_v3_NoIcon.apk / 1.0 running in com.samsung.android.sm rsrc of package com.samsung.android.sm
,12-15 11:49:01.423  3503  4387 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-15 11:49:01.423  9267  9267 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-15 11:49:01.433  9267  9267 D ResourcesManager: For user 0 new overlays fetched Null
,12-15 11:49:01.433  9267  9267 I InjectionManager: Inside getClassLibPath caller 
,12-15 11:49:01.453  9267  9267 D InjectionManager: InjectionManager
12-15 11:49:01.453  9267  9267 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm
,12-15 11:49:01.453  9267  9267 I InjectionManager: Constructor com.samsung.android.sm, Feature store :{}
12-15 11:49:01.453  9267  9267 I InjectionManager: featureStore :{}
,12-15 11:49:01.463  3503  3843 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{27127d8 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dc7a6bb 9267:com.samsung.android.sm/1000}
,12-15 11:49:01.473  3503  3843 I ActivityManager: Killing 7313:com.osp.app.signin/u0a41 (adj 15): DHA:empty #33
,12-15 11:49:01.503  3503  4272 D ActivityManager: cleanUpApplicationRecord -- 7313
,12-15 11:49:01.503  3503  4272 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,12-15 11:49:03.733  3503  4133 E Watchdog: !@Sync 12 [12-15 11:49:03.741]
,12-15 11:49:05.103  3152  3610 D Netd    : Iface wlan0 link up
,12-15 11:49:05.103  4093  4093 I wpa_supplicant: nl80211: Received scan results (17 BSSes)
12-15 11:49:05.103  4961  4975 D PdnController: Interface Changed wlan0 link up
12-15 11:49:05.103  3503  3593 D Tethering: interfaceLinkStateChanged wlan0, true
12-15 11:49:05.103  3503  3593 D Tethering: interfaceStatusChanged wlan0, true
,12-15 11:49:05.103  4093  4093 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,12-15 11:49:05.113  3503  3847 D WifiP2pService: InactiveState{ what=147461 }
,12-15 11:49:05.113  3503  3847 D WifiP2pService: P2pEnabledState{ what=147461 }
12-15 11:49:05.113  3503  3847 D WifiP2pService: DefaultState{ what=147461 }
,12-15 11:49:05.143  3503  3503 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,12-15 11:49:05.153  3503  3590 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d61f731 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a10f759 3931:com.android.systemui/u0a62}
,12-15 11:49:05.273  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 301 (W:14), CP = 265, LCD = 40
,12-15 11:49:05.433  4382  4434 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-15 11:49:05.433  4382  4434 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-15 11:49:05.493  4382  4434 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 54ms lastUpdatedAfter : 180282ms
,12-15 11:49:15.303  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 265, LCD = 40
,12-15 11:49:19.563  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:49:23.823  3503  4273 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:49:23.823  3503  4273 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:49:23.823  3503  4273 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-15 11:49:23.823  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:49:23.833  3503  3503 I MotionRecognitionService: Plugged
12-15 11:49:23.833  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:49:23.833  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-15 11:49:23.833  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:49:23.843  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:49:23.843  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-15 11:49:23.843  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
12-15 11:49:23.843  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:49:23.853  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:49:23.863  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:49:23.873  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-15 11:49:23.873  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:49:23.873  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:49:23.883  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:49:25.323  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 265, LCD = 40
,12-15 11:49:33.733  3503  4133 E Watchdog: !@Sync 13 [12-15 11:49:33.743]
,12-15 11:49:35.343  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 264, LCD = 40
,12-15 11:49:39.573  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:49:45.373  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 264, LCD = 40
,12-15 11:49:53.863  3503  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:49:53.863  3503  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:49:53.863  3503  3843 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-15 11:49:53.863  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:49:53.863  3503  3503 I MotionRecognitionService: Plugged
12-15 11:49:53.863  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:49:53.863  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-15 11:49:53.863  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:49:53.873  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:49:53.873  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-15 11:49:53.873  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-15 11:49:53.873  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:49:53.883  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:49:53.883  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:49:53.893  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-15 11:49:53.893  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:49:53.893  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:49:53.903  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:49:55.393  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 264, LCD = 40
,12-15 11:49:59.573  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:49:59.993  3503  3806 V AlarmManager: Expired Alarm result :8
,12-15 11:50:00.003  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-15 11:50:00.003  3931  3931 D KeyguardUpdateMonitor: handleTimeUpdate
,12-15 11:50:00.023  3931  3931 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-15 11:50:00.073  3931  3931 D DateView: received broadcast android.intent.action.TIME_TICK
,12-15 11:50:00.093  4740  4740 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-15 11:50:00.093  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-15 11:50:00.093  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-15 11:50:00.093  4740  4740 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-15 11:50:00.093  4740  4740 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0A4E14BED9EB8890D11FAA0FE25E6936D396B88B1054FC0D740255A221425EB37CA5E7098CFC8F411607A3F8F469DD214]}
,12-15 11:50:00.093  4740  4740 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-15 11:50:03.733  3503  4133 E Watchdog: !@Sync 14 [12-15 11:50:03.744]
,12-15 11:50:05.423  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 264, LCD = 40
,12-15 11:50:05.493  4382  4434 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-15 11:50:05.493  4382  4434 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-15 11:50:15.443  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 264, LCD = 40
,12-15 11:50:19.573  3503  6099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-15 11:50:23.923  3503  4387 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-15 11:50:23.923  3503  4387 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-15 11:50:23.923  3503  4387 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-15 11:50:23.923  3503  3503 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-15 11:50:23.923  3503  3503 I MotionRecognitionService: Plugged
12-15 11:50:23.923  3503  3503 D MotionRecognitionService:   cableConnection= 1
12-15 11:50:23.923  3503  3503 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-15 11:50:23.923  3503  3503 D MotionRecognitionService: skip setTransmitPower. 
,12-15 11:50:23.933  3503  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-15 11:50:23.933  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-15 11:50:23.933  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-15 11:50:23.933  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-15 11:50:23.943  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:50:23.943  4961  4961 D CommonServiceConfiguration: getStringValueSetting
,12-15 11:50:23.943  4909  4909 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-15 11:50:23.943  4909  5289 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-15 11:50:23.943  4961  4961 D BatteryMonitor: new battery level: 100
,12-15 11:50:23.963  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-15 11:50:25.473  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 264, LCD = 40
,12-15 11:50:33.743  3503  4133 E Watchdog: !@Sync 15 [12-15 11:50:33.746]
,12-15 11:50:35.493  3503  6063 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 264, LCD = 40

```
